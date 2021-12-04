# 문제
두 정수 A와 B를 입력받은 다음, A+B를 출력하는 프로그램을 작성하시오.

# 풀이방법
1. 테스트 케이스 수 입력받기
2. 반복문을 작성한다. 1부터 t까지
3. 테스트 케이스 숫자만큼 반복하며, a,b 두 수를 입력받는다.
4. **f-string**을 이용해서 출력문 작성!!!

```python
t = int(input()) # 테스트 케이스 개수 t를 입력

for i in range(1, t+1): # 1부터 t까지
    a,b = map(int, input().split())
    print(f'Case #{i}: {a+b}')
```
