# goudy
Go language에 대해 공부를 시작하며 내용을 업데이트 할 공간 생성.
* https://golang.org/

# 특징

## 간결한 문법
> go는 nodejs 처럼 스크립트 언어는 `컴파일 언어`이며, C언어 처럼 `main()`함수가 필요 하지만  언어의 차원에서 객체지향의 상징인 `클래스`를 배제함으로써 언어 자체가 단순해졌고, 복잡하기 그지없는 객체지향적 개념을 조금이나마 줄이기 위한 노력을 했다.
```go
package main
import "fmt"

func main() {
	fmt.Println("hello world")
}
```
> 표현의 방법을 달리했을 뿐, 일부 부분은 객체지향에서 가져오긴 했였다. method, 캡슐화라. 물론 상속이 없기 때문에 키워드같은 것은 존재하지 않으며 특이하게도 소문자로 캡슐화를 할 수 있다.
> 또한 반복문은 오질 `for` 하나 뿐이다. 

## 간편한 동시성 제어

## Garbage Collection

## 오픈소스, 패키지 레지스트리 탈 중앙화
> 패키지를 특정 레지스트리(npm, packagist)와 같은 곳에 올려 두지 않고, github에서 직접 가지고 오는 방식을 택하였다. `go get`을 통해 손쉽게 가지고 올 수 있다.
