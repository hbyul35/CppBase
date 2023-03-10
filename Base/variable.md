# 변수  

비주얼 스튜디오를 깔기 힘들다면 해당 사이트에서 연습하는 것을 권장  
https://www.onlinegdb.com/online_c++_compiler   

### 1. 변수의 기본  
메모리는 물리적으로 서로 구별이 가능한 식별자를 통해 접근할 수 있는 값 또는 주소가 저장된 공간이다.  
변수는 데이터를 저장하기 위한 메모리 공간과 관련이 있으며, 값을 담을 수 있는 그릇이라고 생각하면 된다.

### 2. 변수와 메모리  
컴퓨터는 모든 데이터를 **2진수**로 표현한다.  

|명칭|데이터 크기|설명|
|------|---|---|
|비트(bit)|2진수 표시에서 한 자리 수에 해당|0과 1의 값을 가짐|
|바이트(byte)|8bit = 1byte|byte는 아스키 문자 하나를 나타내는 최소 단위|
|워드(word)|CPU가 I/O 장치로부터 한 번에 데이터를 읽어올 수 있는 단위|CPU bit 크기에 따름|


### 3. 변수 선언  
메모리 공간에 값 또는 주소를 저장하기 위해서 메모리를 할당하는 것이다.  
메모리를 할당받는 크기는 변수의 자료형 크기만큼 할당한다.

- 변수 자료형(데이터형) 변수 이름
``` 
char name[10];                                   // 배열 변수 선언
int age, weight;                                 // 여러 개의 일반 변수 선언
```

### 4. 대입 연산자
대입 연산자는 '같다'가 아니라 오른쪽의 변수를 왼쪽으로 대입하는 것이다.
```
int a = 3;                             
```
3을 'a'란 변수에 대입하는 것이므로, a에는 3이 저장된다.  

### 5. 변수의 종류
1. 일반 변수  
특정 자료형의 데이터 '하나'만 저장할 수 있는 저장 공간 ( 데이터 값을 저장)  
``` int i; ```  

2. 배열 변수  
특정 자료형의 데이터 '여러 개'를 저장할 수 있는 저장 공간  
``` int score[10]; ```  

3. 참조 변수  
데이터를 저장 가능한 저장 공간을 할당하지 않고, 이미 할당된 저장 공간에 새로운 별명을 붙인다.  
``` int &ref = i; ```  

4. 포인터 변수  
주소를 저장할 수 있는 저장 공간  
``` int *ptr; ```
