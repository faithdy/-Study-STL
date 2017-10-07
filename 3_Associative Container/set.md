# set 컨테이너
key라 불리는 원소의 집합.  
모든 연관 컨테이너는 노드 기반 컨테이너이며, 균형 이진 트리로 구성  
set 컨테이너는 value와 key type이 동일하다.

>NOTICE: 연관 컨테이너의 찾기 관련 멤버 함수는 key(원소)를 찾을 때 == 연산을 사용하지 않는다. 연관 컨테이너는 정렬 기준에 의해 key(원소)가 정렬되어 있으므로 컨테이너의 정렬 기준 조건자를 이용해찾기 연산을 수행한다.
> 예로 set 정렬 기준이 less라면 less는 < 연산을 수행하므로 비교하는 두 원소 a와 b가 !(a<b)&&!(b<a)라면 두 원소는 같다(equivalence)고 판단한다.
> s 컨테이너의 정렬 기준을 반환하는 멤버 함수가 eky_comp()이므로 비교하는 두 원소 a와 b가 !s.key_comp()(a,b) && !s.key_comp(b,a)이면 두 원소는 같다.

## 생성자
- [x] set s
- [ ] set s(pred)
- [x] set s(s2)
- [x] set s(b,e)
- [ ] set s(b,e,pred)


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
