# 반복자의 종류

- 입력 반복자
- 출력 반복자
- 순방향 반복자
- 양방향 반복자
- 임의 접근 반복자

```c++
reverse_iterator<vector<int>::iterator> riter(iter);
// iter 반복자의 역방향 반복자를 생성

iter = riter.base()
// base() : 역방향 -> 정방향
```

- 삽입 반복자

```
insert_iterator<vector<int>> insert(v2, v2.begin());
copy(v1.begin(), v1.end(), insert);
//혹은


copy(v1.begin(), v1.end(), inserter<vector<int>>(v2, v2.begin()));
//v2.begin()을 넣으면 에러지만, 삽입모드 반복자 어댑터인 inserter()를 이용하여 삽입모드로 해결하면된다.
```

- 보조함수
advance(p, n)
n = distance(p1, p2)
