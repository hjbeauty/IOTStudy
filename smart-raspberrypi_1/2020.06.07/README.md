# 2020.06.07

## 기초파이

{% file src="../../.gitbook/assets/pdf-3.pdf" caption="raspberrypi교재3" %}

bit 연산을 위한  명령

주석처리  - \# 문장

{% hint style="info" %}
주석처리

* \#  : 문장 전체 
* " ' " ~ " ' ": docstring 
{% endhint %}

```python
a=100 #주석문장
"'"  
   여기부터 주석문
"'"
```

{% hint style="info" %}
\_\_doc\_\_ , help\(\)

* help\(모르는명령\) :  모르는 명령에 대한 설명이 출력됨
* \_\_doc\_\_ : 어떤 명령에 doc를 추가하기 위한 명령  
{% endhint %}

```python
help(print)

print.__doc__ 
'어쩌구 저쩌구 '
```

## Data type

{% hint style="info" %}
String

* "  , '   쌍을 이루어서 사용하면 된다
* index를 갖는다
* 
문자열 - 시퀀스 형 - 순서를 가지고 있는 것 , 슬라이스 값-&gt; 부분적으로 값을 가져온다 , substring과 같은 말

* 시퀀스형 데이터에 공통적으로 사용되는
{% endhint %}

```text
e=d[:] #요소로 복사한다
e=d #주소를 복사한다 
```

{% hint style="info" %}

{% endhint %}

{% hint style="info" %}
tuple - 리스트와 비슷한 자료형 

* \( 값1,값2 \)로 만든다
* 리스트와 다른점 요소를 변경하거나 제거할 수 없다
{% endhint %}

{% hint style="info" %}
list

클래스 메소드 

* \[ 값1, 값2....\]
* m=\[1,2,3,4\]  m이라는 객체 생성
* m.append\(5\) ==&gt; 처럼 사용가능
{% endhint %}

{% hint style="info" %}
DIC   - 키 : 밸류

* {  키 : 밸류    }
{% endhint %}

{% hint style="info" %}
형변환 함수

* int\(\)
* float\(\)
* str\(\)
* list\(\)
* tuple\(\)
{% endhint %}

{% hint style="info" %}
Format String 

* %d : 정수 
* %f : 실수
* %s : 문자열
* %c : 문자
* %x : 16 진수
* %X : 16진수 대문자
* %% : % 문자 출력
{% endhint %}

![](../../.gitbook/assets/image%20%282%29.png)

![](../../.gitbook/assets/image%20%2833%29.png)



