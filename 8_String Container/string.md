# string 컨테이너
string 컨테이너는 vector 컨테이너 기반
* string (char 문자 용)
* wstring (유니코드 용)

## 생성자
- [x] string s
- [x] string s(sz)
- [x] string s(sz, n)
- [x] string s(n, c)
- [x] string s(iter1, iter2)
- [x] string s(p1, p2)
- [x] string s(s2)

## 멤버 함수
- [x] s.size()
- [x] s.length()
- [x] n=s.capacity()
- [x] n=s.max_size()
- [x] p=s.begin()
- [x] p=s.end()
- [x] p=s.rbegin()
- [x] p=s.rend()
- [x] s.clear()
- [x] s.empty()


>### append & assign version :
>method()  
>* string  
>* string, offset, length  
>* char*  
>* char*, length
>* length, single character
>* [iter1, iter2)
>* [p1, p2)  
>  
>operator()
>* operator(string)
>* operator(char*)
>  
> when use **operator**? assign&append **all** strings  
> when use **method**? assign&append **sub** strings  

- [x] s.append(sz)
- [x] s.assign(sz)
- [x] s.push_back(c)


- [x] s.c_str()
- [x] s.data()


- [ ] s.at(i)
- [ ] s.compare(s2)
- [ ] s.copy(buf,n)
- [ ] q=s.erase(p)
- [ ] q=s.erase(b,e)
- [ ] s.find(c)
- [ ] s.insert(n,sz)
- [ ] s.replace(pos,n,sz)
- [ ] s.reserve(n)
- [ ] s.rsize(n)
- [ ] s.rsize(n,c)
- [ ] s.rfind(c)
- [ ] s2=s.substr(pos)
- [ ] s.swap(s2)


## 연산자
- [ ] s[i]
- [x] s+=s2
- [x] s+s2
- [x] s=s2
- [ ] out<<s
- [ ] in>>s
- [ ] getilne(in,s)
- [ ] s==s2
- [ ] s!=s2
- [ ] s<s2
- [ ] s>s2
- [ ] s<=s2
- [ ] s>=s2
