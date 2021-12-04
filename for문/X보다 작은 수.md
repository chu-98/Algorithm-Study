# 문제
정수 N개로 이루어진 수열 A와 정수 X가 주어진다. 이때, A에서 X보다 작은 수를 모두 출력하는 프로그램을 작성하시오.

# 풀이방법
1. N과 X를 입력한다.
2. num이라는 list로 랜덤한 수열을 만든다.
3. for과 if를 한꺼번에 쓴다.
4. range(N)는 0부터 N-1까지 라는 뜻이다.
5. 만약 X보다 수열 num 중 i번째 숫자가 작다면, print한다.
6. print는 num[i]와 함께 띄어쓰기를 위해 end=" "를 적어준다.

```python
N, X = map(int, input().split())
num = list(map(int, input().split()))

for i in range(N): # 0 ~ N-1까지 입력된다
    if num[i] < X:
        print(num[i], end=" ")
```
