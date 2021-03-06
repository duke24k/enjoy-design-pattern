# Java 언어로 배우는 디자인 패턴 입문

## Iterator
	순서대로 지정해서 처리하기

## Adapter
	바꿔서 재이용하기
	
## Template Method
	하위 클래스에서 구체적으로 처리하기

## Factory Method
	하위 클래스에서 인스턴스 작성하기

## Singleton 
	인스턴스를 한 개만 만들기
	
## Prototype
	복사해서 인스턴스 만들기
	
## Builder
 	복잡한 인스턴스 조립하기
 	
## Abstract Factory 
	관련 부품을 조합해서 제품 만들기

## Bridge
	기능 계층과 구현 계층 분리하기
	
## Strategy
	 알고리즘을 모두 바꾸기

## Composite
	그릇과 내용물을 동일시하기

## Decorator
	장식과 내용물을 동일시하기
	
## Visitor
	데이터 구조를 돌아다니면서 처리하기

## Chain of Responsibility
    복수의 오브젝트가 연결되어 있는 내부의 어딘가에서 일을 수행

## Facade
    복잡하게 얽힌 클래스를 개별적으로 제어하는 것이 아니라, 창구 역할을 하는 클래스를 하나 배치해서 시스템 전체의 조작성을 좋게 함

## Mediator
    복수의 클래스가 상호간에 직접 의사 소통을 하는 것이 아니라, 중개역을 하는 클래스를 하나 준비하고, 그 클래스하고만 의사 소통을 하게 해서 프로그램을 단순하게 만드듬

## Observer
    상태가 변화하는 클래스와 그 변화를 통지받는 클래스를 분리해서 생각

## Memento
    현재의 상태를 저장해 두고 필요할 때 복귀시키는 Undo 기능을 설정

## com.pearl.genius.state
    상태를 클래스로 표현하고 상태에 적합한 switch 문의 사용을 줄여줌

## Flyweight
    복수의 장소에서 동일한 것이 등장할 때 그것들을 공유해서 낭비를 없앰

## Proxy
    정말로 목적한 것이 필요하게 될 때까지 대리인을 사용해서 처리하는 진행

## Command
    요구나 명령을 형태로 만들어서 클래스로 표현

## Interpreter
    문법규칙을 클래스로 표현