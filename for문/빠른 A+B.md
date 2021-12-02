# 문제
본격적으로 for문 문제를 풀기 전에 주의해야 할 점이 있다. 입출력 방식이 느리면 여러 줄을 입력받거나 출력할 때 시간초과가 날 수 있다는 점이다.

Python을 사용하고 있다면, input 대신 sys.stdin.readline을 사용할 수 있다. 단, 이때는 맨 끝의 개행문자까지 같이 입력받기 때문에 문자열을 저장하고 싶을 경우 .rstrip()을 추가로 해 주는 것이 좋다.

# 풀이방법
1. import sys는 sys를 포함하겠다는 것으로 sys.stdin.readline()을 사용할 수 있도록 하는 코드입니다.
2. 사용자가 원하는 개수를 받는 input 변수를 지정해줍니다.
3. for문을 inp값에서 하나 뺀 값까지 반복해 a와 b를 입력받고, 둘을 더한 값을 출력해줍니다.

```python
import sys

inp = int(input())
for i in range(inp):
    a,b = map(int, sys.stdin.readline().split())
    print(a+b)
```
