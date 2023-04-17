## 클래스 다이어그램
---
> 클래스 다이어그램은 구조 다이어그램에 속하며, 클래스 내부의 정적인 내용이나 클래스 사이의 관계를 표기하는 다이어그램  
UML은 크게 3가지 **개념, 명세, 구현**의 차원들로 목적에 따라 다르게 사용되며 그중에서 소스코드와 관계가 깊은 명세, 구현 
차원에 해당

## 클래스 다이어그램의 요소
1. Class : 클래스는 3개의 구획(compartment)으로 나누어, 클래스의 이름, 속성, 기능을 표기함.  
           속성과 기능은 옵션으로 생략이 가능
<img src="organize-my-thoughts\ClassDiagram\클래스 예시.png">
```
======
User : 클래스의 이름
======
접근제한자 속성명 : 타입
- age : int       속성
- name : String   속성
+ num : int       속성
======
접근제한자 기능명 : 반환타입
+ getter() : int  기능(메서드)
+ setter() : void 기능(메서드)
======
- : private 
+ : public
```

2. 스테레오 타입 (나중에 알아보도록 하자)

3. 추상 클래스/메서드

## 클래스간의 관계
<img src="organize-my-thoughts\ClassDiagram\클래스간 관계.png">