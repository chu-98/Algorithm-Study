# 문제
두 정수 A와 B를 입력받은 다음, A+B를 출력하는 프로그램을 작성하시오.

# 풀이방법
가장 많이 틀린 문제..!
1. 테스트 케이스 개수 t를 입력한다.
2. range 안에 t를 통째로 넣는다.
3. %d => 각 자리에 들어갈 변수를 순서대로 넣는다.

## 오답
```python
t = int(input()) # 테스트 케이스 개수 t를 입력

for x in range(1, t+1): # 1부터 t까지
    a,b = map(int, input().split())
    print(f'Case #{x}: {a}+{b}={a+b}')
```
## 정답
```python
t = int(input()) # 테스트 케이스 개수 t를 입력

for i in range(t): # 1부터 t까지
    a,b = map(int, input().split())
    print("Case #%d: %d + %d = %d" %(i+1, a, b, a+b))
```
