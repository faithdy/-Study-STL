# map 컨테이너
원소를 key와 value의 쌍(pair)으로 저장.  
set과 같이 중복 저장이 안되는 컨테이너.  
key의 type이 string이라면
```c++
s["Apple"] = 3
```
와 같이 string으로 indexing이 가능함.


## 생성자
- [x] map m
- [ ] map m(pred)
- [x] map m(m2)
- [x] map m(b,e)
- [ ] map m(b,e,pred)


## 멤버 함수
- [x] m.size()
- [x] m.empty()
- [x] m.clear()
- [x] n=m.max_size()
- [x] m.swap(m2)


- [x] pred=m.key_comp()
- [x] pred=m.value_comp()


- [x] q=m.erase(p)
- [x] q=m.erase(b,e)
- [x] n=m.erase(k)
- [x] p=m.inert(k)
- [x] q=m.insert(p,k)
- [x] m.insert(b,e)


- [x] p=m.find(k)
- [x] n=m.count(k)


- [x] p=m.lower_bound(k)
- [x] p=m.upper_bound(k)
- [x] p=m.equal_range(k)
- [x] p=m.begin()
- [x] p=m.end()
- [x] p=m.rbegin()
- [x] p=m.rend()


## 연산자
- [x] m1==m2
- [x] m1!=m2
- [x] m1<m2
- [x] m1<=m2
- [x] m1>m2
- [x] m1>=m2
- [x] m[k]=v
