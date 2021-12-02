# 문제
자연수 N이 주어졌을 때, 1부터 N까지 한 줄에 하나씩 출력하는 프로그램을 작성하시오.

# 풀이방법
1. 자연수 n 입력받기
2. for문 코드 작성
3. comprehension 표현식 : [출력 표현식 for iterable자료 요소 in iterable자료형]

```python
n = int(input())

for i in range(1, n+1): # 1부터 n까지
    print(i)
```
```python
# comprehension 표현식
[print(i) for i in range(1, int(input())+1)]
```
