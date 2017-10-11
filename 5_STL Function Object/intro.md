# STL 함수 객체
함수 객체(function object), 함수자(functor)  
operator() 연산자를 오버로딩한 클래스 객체

1. 일반 함수 객체 : 특정 기능을 수행
  - 산술 연산 함수 객체
  - 비교 연산 함수 객체 조건자
  - 논리 연산 함수 개게 조건자

2. 함수 어댑터 : 함수류를 인자로 받아 다른 함수 객체로 변환
  - 바인더
  - 부정자
  - 함수 포인터 어댑터
  - 멤버 함수포인터 어댑터

* * *
## 산술 연산 함수 객체
- plus<T>
- minus<T>
- multiplies<T>
- divides<T>
- modulus<T>
- negate<T>

## 비교 연산 조건자
- equal_to<T>
- not_equal_to<T>
- less<T>
- less_equal<T>
- greater<T>
- greater_equal<T>

## 논리 연산 조건자
- logical_and<T>
- logical_or<T>
- logical_not<T>

## 바인더
이항 함수자를 단항 함수자로
- bind1st : 1번째 인자를 고정
- bind2nd : 2번째 인자를 고정

## 부정자
- not1
- not2

## 멤버 함수 포인터어댑터
- mem_fun_ref()
- mem_fun()
