# 문제
두 정수 A와 B를 입력받은 다음, A×B를 출력하는 프로그램을 작성하시오.

# 풀이방법
1. input 받은 문자를 split 함수로 나누면 해당 수를 변수에 선언해준다.
2. input 함수로 입력받은 문자는 int 함수를 이용해서 정수로 변환하고 * 기호를 사용해서 두 수를 곱해주면 된다.
3. map 함수로도 가능하다!

```python
A,B = input().split()
print(int(A)*int(B))
```
```python
A,B = map(int, input().split())
print(A*B)
```
