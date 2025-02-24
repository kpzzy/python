## Python 문법

### Data type

- Numbers
- Strings
- Printing
- Lists
- Dictionaries
- Booleans
- Tuples
- Sets

### Numbers

> 넘버 타입은 Integer

사칙연산

```python
1+1
1-1
1*1
1/1
1%1

제곱은 1**1
```

### Strings

싱글쿼트, 더블쿼트 같다

```python
data = 'hello world'

type(data)
str

print(data[0])
h

print(data[-1]) // 뒤에서부터 세기 가능
d

print(data[0:4])
// 콜론으로 지정하면 범위지정 가능
// data[0] = h, data[4] = 'o'인데 'o' 는 포함되지 않음

hell

print(len(data))
11

print(data)
hello world
```

### Variable Assingnment

변수명은 영문 a-z , 숫자 0 - 9, \_ 등이 변수로 될 수 있다.

단 숫자로는 시작할 수 없다

```python
name_of_var = 2

x = 2
y = 3
z = x + y
a,b,c = 1,2,3
print(a,b,c) = 1,2,3
type(x) = int

x = 2.0
type(x) = float // 소수점은 float 라는 타입이다
```

### Printing

파이썬은 인터프리터언어여서 print 로 출력한다

```python
x = 'hello'

print(x)
hello

num = 4
name = kpzzy
print('My age is {one}, my name is {two}'.format(one=num, two=name))

My age is 4, my name is kpzzy

print('My age is {}, my name is {}'.format(num, name))

My age is 4, my name is kpzzy
```

### Lists

모든 데이터 타입이 섞여서 들어올 수 있음

```python
[1,2,3]

['hi', 1, [1,2]]

my_list = ['a','b','c']
my_list.append('d')

['a','b','c','d']

my_list[0] = 'a'

my_list[1:] = ['b','c','d']
```

### Dictionaries

### Tuples

### Sets
