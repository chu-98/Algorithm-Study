# 문제
두 정수 A와 B를 입력받은 다음, A/B를 출력하는 프로그램을 작성하시오.

# 풀이방법
1. 파이썬에서 나누기 연산에 대해 어느 정도 이해가 되어 있다면 다른 수학 연산의 문제와 동일하게 풀 수 있다.

```python
A,B = input().split()
print(int(A)/int(B))
```

```python
A,B = map(int, input().split())
print(A/B)
```
