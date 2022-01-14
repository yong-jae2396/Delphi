# DelPhi Source File의 구조

****

### Source File의 종류

* 프로젝트 소스 파일 - 프로그램 구동에 필요한 소스코드

* 유닛 파일 - 실질적인 소스 파일

* 폼 파일  - 폼 정보 기록, 이벤트 등의 소스 파일 정보 포함

---

### Project Source(.dpr)

#**프로젝트 소스 보기 : Project Manager ---  View Source**

* program - 프로그램 명

* uses - 참조할 Unit(Source) 목록

* begin ... end - Project Source Code

****

### 유닛(.pas)

* unit - Unit 이름

* interface - 선언부, 다른 Unit에서 참조 가능

* implimentation - 구현부
- uses - 참조할 Unit(Source) 목록

- initialization - (옵션)Unit 초기화 시 수행할 코드

- finalization - (옵션)Unit 종료 시 수행할 코드

- end. - Source의 끝

****

### 폼 파일(.dfm, .fmx)

* #폼 정보 보기 :  폼 디자이너 ---  View as Text (Alt + F12)

* #폼 화면 보기 :  코드 에디터 --- View as Form (Alt + F 2)

****

## 문법 요소

* 한 문장의 단위 
  * ; 으로 마무리
  * begin ... end;
* 들여쓰기, 빈줄 공백
* 주석 
  * // - 한줄주석
  * {} - 여러 줄 주석(방식 1)
  * (**) -  여러 줄 수석(방식 2)

****


