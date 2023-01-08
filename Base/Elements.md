# C++ 프로그램 구성요소  
아래의 기본적인 프로그램을 보고 분석을 해보자.

```c++
#include <stdio.h>
using namespace std;

int main(int argc, char const* argv[])
{
	int x, y;
	printf("두 수를 입력하시오 : ");
	scanf_s("%d %d",&x,&y); 
	printf("%d + %d =  %d", x, y, x + y);

	return 0;                    
}
```

### main() 함수
C++ 프로그램에서 실행 파일의 실행의 시작점은 **main** 함수이다.  
main 함수가 종료되면 프로그램도 종료된다.

```c++
int main(int argc, char const *argv[])
{
	return 0;                                  // 실행 종료를 알리는 명령
}
```

### 주석문
주석문은 프로그램의 실행에 영향을 주지 않으며 프로그래머가 작성한 프로그램 또는 프로그램 코드에 대한 설명을 추가할 때 사용된다.  
```c++
        1.
	// 주석문                         
```
`//` 한 줄에 대한 설명  


```c++
	2.
	/* 
	주석문 
	*/
```
`/* */` 여러 줄에 대한 설명

### 
