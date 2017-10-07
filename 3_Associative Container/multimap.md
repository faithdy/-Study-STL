# multimap 컨테이너
map 컨테이너와 거의 동일하나 중복 원소를 가질 수 있다는 점만 다름.


## 생성자
- [x] multimap m
- [ ] multimap m(pred)
- [x] multimap m(m2)
- [x] multimap m(b,e)
- [ ] multimap m(b,e,pred)


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
