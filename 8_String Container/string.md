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


- [x] s.at(i)
- [x] s.reserve(n)
- [x] s.resize(n)
- [x] s.resize(n,c)
- [x] s.swap(s2)


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


>### compare version :
>compare()
>* string
>* offset, length, string
>* offset, length, string, offset, length
>* char*
>* offset, length, char*
>* offset, length, char*, length
>* offset, length, char*, offset, length

- [x] s.compare(s2)


>### copy version :
>copy()
>* char*, length
>* char*, length, offset
>
>NOTICE : copy() copies original string without '\0'


- [x] s.copy(buf,n)

>### find version :
>find()
>* single character
>* single character, offset
>* char*
>* char*, offset
>* char*, offset, length
>* string
>* string, offset

>NOTICE : the parameter 'offset' of find() means caller's offset.  
>find returns offset, size_type pos.  
>if not found, it returns -1(=npos).


- [x] s.find(c)
- [x] s.rfind(c)


>### insert version :
>insert()
>* offset, char*
>* offset, char*, length
>* offset, string
>* offset, string, string.offset, length
>* offset, length, single character
>* iterator
>* iteartor, single character
>* iteartor, length, single character
>* iterator, [iter1, iter2)

>NOTICE : the parameter 'offset' of find() means caller's offset.  


- [x] s.insert(n,sz)
- [x] q=s.erase(p)
- [x] q=s.erase(b,e)


>### replace version :
>replace()
>* offset, length, char*
>* offset, length, string
>* offset, length, char*, length2
>* offset, length, string, offset2, length2
>* offset, length, character.length, single character
>* [iterB, iterE), sz
>* [iterB, iterE), s
>* [iterB, iterE), sz, length
>* [iterB, iterE), character.length, single character
>* [iterB, iterE), [iter2B, iter2E)


- [x] s.replace(pos,n,sz)


>### substr version :
>substr()
>* offset
>* offset, string::npos
>* offset, length

>NOTICE : the type string::npos seems like string.end()


- [x] s2=s.substr(pos)


## 연산자
- [x] s[i]
- [x] s+=s2
- [x] s+s2
- [x] s=s2

- [x] out<<s
- [x] in>>s
- [x] getilne(in,s)
- [x] s==s2
- [x] s!=s2
- [x] s<s2
- [x] s>s2
- [x] s<=s2
- [x] s>=s2
