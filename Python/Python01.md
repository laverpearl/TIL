# 문자열, 배열 입력 받기   
  
  
  
  
> 1차원 배열 입력받기
map함수를 사용하면 한줄에 여러개의 정수를 입력 받을 수 있다.  
split함수는 문자열을 나눌 떄 사용한다.
  
```python
num_list = list(map(int, input().split()))
```
  
결과
```python:python01.py
>> 입력
1 2 3 4 5
>> 출력
[1, 2, 3, 4, 5]
```



