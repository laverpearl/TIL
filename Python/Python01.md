# 문자열, 배열 입력 받기
<br/>

> #### 1차원 배열 입력받기  

map함수를 사용하면 한줄에 여러개의 정수를 입력 받을 수 있다.  
split함수는 문자열을 나눌 떄 사용한다.
  
```python
num_list = list(map(int, input().split()))
```
  
결과
```python
# 입력
1 2 3 4 5

# 출력
[1, 2, 3, 4, 5]
```
<br/>

> #### 한줄에 정수형 변수 여러개 입력받기  

받을 변수의 개수를 지정할 수 있다.

```python
a, b, c, d = map(int, input().split())
```

결과
```python
# 입력
1 2 3 4

# 출력
>> print(a)
1
>> print(b)
2
```




