# 문제
자연수 N이 주어졌을 때, N부터 1까지 한 줄에 하나씩 출력하는 프로그램을 작성하시오.

# 풀이방법
1. 변수 inp를 지정해 int(input())을 이용해서 입력을 받는다.
2. for문 조건을 작성해줍니다.

```python
inp = int(input())

# range(초기값, 종료값, 증가값)
for i in range(inp, 0, -1):
    print(i)
```
