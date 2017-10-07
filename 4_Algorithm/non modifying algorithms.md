# 원소를 수정하지 않는 알고리즘
원소의 순서나 원소의 값을 변경하지 않고 원소를 읽기만 하는 알고리즘
>Notice : lexicoraphical_compare 기본 옵션인 less에 대해서 .. return lef < right라면 [10,20,30], [10,20,50]이 있을때 10에서 먼저 걸러져야 되는 것 아닌가? 내부 알고리즘에 대해서 알아보자.

- [x] p=adjacent_find(b,e)
- [x] p=adjacent_find(b,e,f)


>Notice : if not found, it returns the iterator about e, NOT PAST-THE-END


- [x] n=count(b,e,x)
- [x] n=count_if(b,e,f)


- [x] equal(b,e,b2)
- [x] equal(b,e,b2,f)


>Notice : equal( ), compare two sequence. but it doen's need 2nd sequence's end. generally, in checking equality, both sequence have same length.  


- [x] p=find(b,e,x)
- [x] p=find_if(b,e,f)


>Notice : find and find_if returns first iterator whethere duplicated data or not.


- [x] p=find_end(b,e,b2,e2)
- [x] p=find_end(b,e,b2,e2,f)


>Notice : find_end(b,e,b2,e2)의 경우, [b,e)의 순차열에 [b2,e2)의 순차열이 일치하는지를 판단하여, 일치하는 순차열 구간이 여러 개라면 마지막 순차열의 첫 원소 반복자를 반환한다.


- [x] p=find_first_of(b,e,b2,e2)
- [x] p=find_first_of(b,e,b2,e2,f)


>Notice : cartesian product를 하듯, [b,e)를 순차적으로 돌면서 각각에 대해 [b2,e2)의 원소를 찾는지 검사. 일치하는 것중 첫번째 원소의 반복자를 반환한다.


- [x] f=for_each(b,e,f)


>Notice : f(함수류) => void pred(T*), 혹은 함수 객체


- [x] lexicographical_compare(b,e,b2,e2)
- [x] lexicographical_compare(b,e,b2,e2,f)


- [x] k=max(a,b)
- [x] k=max(a,b,f)
- [x] k=min(a,b)
- [x] k=min(a,b,f)
- [x] p=max_element(b,e)
- [x] p=max_element(b,e,f)
- [x] p=min_element(b,e)
- [x] p=min_element(b,e,f)


- [x] pair(p,q)=mismatch(b,e,b2)
- [x] pair(p,q)=mismatch(b,e,b2,f)


>Notice : 원소의 값이 서로 다른 첫번째 위치


- [x] p=search(b,e,b2,e2)
- [x] p=search(b,e,b2,e2,f)
- [x] p=search_n(b,e,n,x)
- [x] p=search_n(b,e,n,x,f)
