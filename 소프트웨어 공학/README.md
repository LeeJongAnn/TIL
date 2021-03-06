# 소프트웨어 공학


## 요구공학

   - 요구사항 도출 
   - 요구사항 분석 - Unified Modeling Language
   - 요구사항 명세 - 정형 언어 , 비정형 언어
   - 요구사항 확인 - 요구사항 확인 및 검증

## 애자일 개발론 
  > 1) 문서화 된 내용보다는 개발에 집중한다.

## 테일러링

## 테스트 - 테스트 오라클,화이트박스 테스트, 블랙박스 테스트 
   - 화이트박스 테스트 : 코드를 중점적으로 테스트 하는것(Ex : 루프 검사)
   - 블랙박스 테스트 : 기능을 중점적을 테스트 하는것 (Ex :동치 분할 ,경계값 분석 .. )
## 객체지향

### 1. 객체지향
    
    1.객체 지향의 구성요소     

    2.객체 지향개발의 원칙
     - 단일 책임 원칙 : 모든 클래스는 하나의 책임만 가지며, 클래스는 그 책임을 완전히 캡슐화해야 함을 일컫는다.
     - 개방 폐쇄 원칙 : 확장에 대해 열려 있어야 하고, 수정에 대해서는 닫혀 있어야 한다는 프로그래밍 원칙이다.
     - 리스코프 치환 원칙 : 상위 개체는 하위 개체로 치환할 수 있어야 한다.
     - 인터페이스 분리 원칙 : 사용하지 않는 인터페이스에 대해서는 의존하지 않아야 한다. 
     - 의존성 역전의 원칙 : ?
    
    3.객체 지향개발론 - 야콥슨 , 럼바우 , 부치
     - OOSE(Object Oriented Structure Engineering) 야콥슨
     - OMT(Object Modeling Tech?) 럼바우 - 객체 모델링 -> 동적 모델링 -> 기능 모델링 순으로 진행된다.
     - OT 부치
     - Cordn and Yarndon? ....
### 2. 디자인패턴

     1. 디자인 패턴의 구조

       - 문맥 (Context)
       - 문제 (Problem)
       - 해결책 (Solution)

     2. 디자인 패턴의 종류 
       GoF(Gang of four) : 소프트웨어 개발 영역에서 디자인 패턴을 정의한 사람 4명을 일컫는다.

       - 생성 패턴 : 객체 생성과 관련된 패턴으로 
          Abstract Factory,Builder,Factory Method,Prototype,Singleton 등이 있다.
       
       - 구조 패턴 : 클래스나 객체를 조합해서 큰 구조를 만드는 패턴 
          Adapter,Bridge,Composite,Decorator,Proxy 등이 있다.

       - 행위 패턴 : 객체나 클래스 사이의 알고리즘이나 책임 분배에 관련된 패턴
          observer,Interpreter,Iterator,State,Strategy,Visitor
        
       observer - 어떤 객체가 변화할때 그와 관련된 객체들에게 알림을 보내는 디자인 패턴 (ex: 발행 혹은 구독했을 때 상태변화로 알림이 오는 경우)

       

### 3. 브룩스의 법칙 , 롱테일 법칙, 파레토 법칙

    1. 브룩스의 법칙: 인원이 더 들어와도 작업시간이 빨라지진 않는다.
    2. 파레토 법칙: 20%의 부분에서 80%의 결과가 나타난다. -> 결함과 오류의 대부분은 특정부분에서 발생한다.
    3. 롱테일 법칙: 80%의 평범한 사람이 20%의 뛰어난 사람보다 낫다. (파레토 법칙의 반대)


### 4. 소프트웨어 테스트 방법

    
    1. 테스트 오라클 
    2. 테스트 레벨 - 단위테스트 , 통합테스트 , 인수테스트(베타 테스트)
    3. 블랙박스 테스트 - 사용자의 요구사항을 프로그램을 실행시켜가며 테스트 해보는것
       - 경계값 분석 혹은 동치 분할 테스트
    4. 화이트박스 테스트 - 프로그램 코드 내부 소스를 확인하며 오류가 발생할만한 부분을 테스트 해보는것
       - 결정 커버리지 , 반복문 테스트 
    TDD(Test Driven Developement) 테스트 주도 개발의 약자로 테스트를 하며 프로그램을 개발하는 것을 일컫는다.   
    프로그램을 개발하는데 필수적인 것이다.

## * 접근통제기술
    1. MAC (Mandatory Access Control) - 사용자는 관리자로부터 자원에 대한 권한을 받는다.
    1. DAC (Discretionary Access Control) - 사용자 계정에 기반해 접근 권한을 갖는다.
    2. RBAC (Role Based Access Control) - 관리자가 사용자에게 해당 역할에 따라 자원에 대한 접근 권한을 설정해준다.

## * 정적 분석 도구 - 
    - 소프트웨어를 실행하지 않고 코드 분석만으로 오류를 찾아내는것 - 화이트박스 테스트와 유사!
    1. PMD


