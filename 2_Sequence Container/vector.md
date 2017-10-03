# vector 컨테이너

## 생성자
- [x] vector v
- [x] vector v(n)
- [x] vector v(n,x)
- [ ] vector v(v2)
- [ ] vector v(b,e)

## 멤버 함수
- [x] x = v.size()
- [x] x = v.max_size()
- [x] x = v.capacity()


- [x] v.resize(n)
- [x] v.resize(n,x)


- [x] v.clear()
- [x] v.empty()
- [x] v.swap(v2)


- [x] &T = v.front()
- [x] &T = v.back()
- [x] &T = v.at(size_type)


- [x] p = v.begin()
- [x] p = v.end()
- [x] p = v.rbegin()
- [x] p = v.rend()


- [x] v.assign(n,x)
- [ ] v.assign(b,e)
- [ ] q = v.erase(p)
- [ ] q = v.erase(b,e)
- [ ] q = v.insert(p,x)
- [ ] v.insert(p, n, x)
- [ ] v.insert(p, b, e)
- [ ] v.pop_back()
- [x] v.push_back(x)
- [ ] v.reserve(n)

## 연산자
- [ ] v1 == v2
- [ ] v1 != v2
- [ ] v1 < v2
- [ ] v1 <= v2
- [ ] v1 > v2
- [ ] v1 >= v2
- [x] v[i]
