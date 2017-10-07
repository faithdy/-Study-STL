# multiset 컨테이너
set 컨테이너와 거의 동일하나 중복 원소를 가질 수 있다는 점만 다름.


## 생성자
- [x] multiset s
- [ ] multiset s(pred)
- [x] multiset s(s2)
- [x] multiset s(b,e)
- [ ] multiset s(b,e,pred)


## 멤버 함수
- [x] s.size()
- [x] s.empty()
- [x] s.clear()
- [x] n=s.max_size()
- [x] s.swap(s2)


- [x] pred=s.key_comp()
- [x] pred=s.value_comp()


- [x] q=s.erase(p)
- [x] q=s.erase(b,e)
- [x] n=s.erase(k)
- [x] p=s.inert(k)
- [x] q=s.insert(p,k)
- [x] s.insert(b,e)


- [x] p=s.find(k)
- [x] n=s.count(k)


- [x] p=s.lower_bound(k)
- [x] p=s.upper_bound(k)
- [x] p=s.equal_range(k)
- [x] p=s.begin()
- [x] p=s.end()
- [x] p=s.rbegin()
- [x] p=s.rend()


## 연산자
- [x] s1==s2
- [x] s1!=s2
- [x] s1<s2
- [x] s1<=s2
- [x] s1>s2
- [x] s1>=s2
