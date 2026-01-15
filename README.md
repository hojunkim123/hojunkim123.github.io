# 파이썬 기초 퀴즈

파이썬 기초 학습 내용을 바탕으로 한 10개의 퀴즈입니다.

---

## 문제 1. 변수 명명 규칙

**다음 중 변수 이름으로 사용할 수 없는 것은?**

1. user_name
2. userName
3. 2user
4. user2

<details>
<summary>정답 보기</summary>

**정답: 3번**

📝 **해설:** 변수 이름은 숫자로 시작할 수 없습니다. 숫자는 두 번째 문자부터 사용 가능합니다.

</details>

---

## 문제 2. 데이터 타입

**다음 코드의 출력 결과는?**

```python
age = '25'
print(type(age))
```

1. `<class 'int'>`
2. `<class 'str'>`
3. `<class 'float'>`
4. 오류 발생

<details>
<summary>정답 보기</summary>

**정답: 2번**

📝 **해설:** 작은따옴표로 감싸진 '25'는 문자열(str) 타입입니다.

</details>

---

## 문제 3. 조건문 실행 흐름

**다음 코드의 출력 결과는?**

```python
score = 75
if score >= 80:
    print('A')
elif score >= 60:
    print('B')
else:
    print('C')
```

1. A
2. B
3. C
4. 오류 발생

<details>
<summary>정답 보기</summary>

**정답: 2번**

📝 **해설:** score가 75이므로 첫 번째 조건(>=80)은 거짓, 두 번째 조건(>=60)은 참이므로 'B'가 출력됩니다.

</details>

---

## 문제 4. 논리 연산자

**다음 중 논리 연산자가 아닌 것은?**

1. and
2. or
3. not
4. if

<details>
<summary>정답 보기</summary>

**정답: 4번**

📝 **해설:** 'if'는 조건문 키워드이며, 논리 연산자는 and, or, not입니다.

</details>

---

## 문제 5. range() 함수

**다음 코드의 출력 결과는?**

```python
for i in range(3):
    print(i, end=' ')
```

1. 1 2 3
2. 0 1 2
3. 0 1 2 3
4. 1 2

<details>
<summary>정답 보기</summary>

**정답: 2번**

📝 **해설:** range(3)은 0부터 2까지의 숫자를 생성합니다. (3은 포함되지 않음)

</details>

---

## 문제 6. 반복문 제어

**반복문에서 현재 반복을 건너뛰고 다음 반복으로 넘어가는 키워드는?**

1. break
2. continue
3. pass
4. skip

<details>
<summary>정답 보기</summary>

**정답: 2번**

📝 **해설:** 'continue'는 현재 반복을 건너뛰고 다음 반복으로 넘어갑니다. 'break'는 반복문을 완전히 종료합니다.

</details>

---

## 문제 7. 기본값 매개변수

**다음 함수의 반환값은?**

```python
def multiply(a, b=2):
    return a * b

result = multiply(5)
```

1. 5
2. 7
3. 10
4. 오류 발생

<details>
<summary>정답 보기</summary>

**정답: 3번**

📝 **해설:** b의 기본값이 2이므로 multiply(5)는 5 × 2 = 10을 반환합니다.

</details>

---

## 문제 8. 람다 함수

**람다 함수의 특징으로 옳지 않은 것은?**

1. 익명 함수이다
2. 한 줄로 작성된다
3. return 키워드가 필요하다
4. 간단한 함수를 정의할 때 유용하다

<details>
<summary>정답 보기</summary>

**정답: 3번**

📝 **해설:** 람다 함수는 return 키워드 없이 자동으로 결과를 반환합니다.

</details>

---

## 문제 9. 리스트 인덱싱

**다음 코드의 출력 결과는?**

```python
fruits = ['사과', '바나나', '오렌지']
print(fruits[-1])
```

1. 사과
2. 바나나
3. 오렌지
4. 오류 발생

<details>
<summary>정답 보기</summary>

**정답: 3번**

📝 **해설:** 음수 인덱스 -1은 리스트의 마지막 요소를 가리킵니다.

</details>

---

## 문제 10. 딕셔너리 메서드

**다음 코드의 출력 결과는?**

```python
student = {'이름': '홍길동', '나이': 20}
print(student.get('학과', '미정'))
```

1. None
2. 미정
3. 오류 발생
4. 홍길동

<details>
<summary>정답 보기</summary>

**정답: 2번**

📝 **해설:** get() 메서드는 키가 없을 때 두 번째 인자로 지정한 기본값('미정')을 반환합니다.

</details>

---

## 채점 기준

- **100% (10/10)**: 🎉 완벽합니다! 모든 문제를 맞히셨네요!
- **80% 이상 (8-9/10)**: 👍 훌륭합니다! 대부분의 문제를 맞히셨어요!
- **60% 이상 (6-7/10)**: 👌 좋아요! 조금만 더 복습하면 완벽할 거예요!
- **60% 미만**: 💪 화이팅! 샘플 코드를 다시 한 번 복습해보세요!

---

## 학습 자료

퀴즈와 관련된 샘플 코드:

- [01_variables_and_types.py](file:///c:/Users/User/Desktop/용원고/01_variables_and_types.py) - 변수와 데이터 타입
- [02_conditionals.py](file:///c:/Users/User/Desktop/용원고/02_conditionals.py) - 조건문
- [03_loops.py](file:///c:/Users/User/Desktop/용원고/03_loops.py) - 반복문
- [04_functions.py](file:///c:/Users/User/Desktop/용원고/04_functions.py) - 함수
- [05_lists_and_dicts.py](file:///c:/Users/User/Desktop/용원고/05_lists_and_dicts.py) - 리스트와 딕셔너리
