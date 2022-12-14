# 3장 패러다임의 개요

## Structured Programming (구조적 프로그래밍)

**구조적 프로그래밍은 제어흐름의 직접적인 전환에 대해 규칙을 부과한다.**

- 최초로 적용된 패러다임 (하지만 최초로 만들어진 패러다임은 아닌)

- 1968년 Edsger Wybe Dijkstra (에츠허르 비버 데이크스트라) 가 발견

- 무분별한 점프(goto 문장)는 프로그램 구조에 해롭다

- if/then/else, do/while/until 과 같이 더 익숙한 구조로 대체

## Object-Oriented Programming (객체 지향 프로그래밍)

**객체 지향 프로그래밍은 제어흐름의 간접적인 전환에 대해 규칙을 부과한다.**

- 1966년 Ole Johan Dahl (올레 요한 달), Kristen Nygaard (크리스텐 니가드)에 의해 등장

- ALGOL 언어의 함수 호출 스택 프레임(stack frame)을 힙(heap)으로 옮기면, 함수 호출이 반환된 이후에도 함수에서 선언된 지역 변수가 오랫동안 유지될 수 있음을 발견

- 함수 → 클래스의 생성자 / 지역변수 → 인스턴스 변수 / 중첩 함수 → 메서드

- 함수 포인터를 특정 규칙에 따라 사용하는 과정을 통해 필연적으로 다형성이 등장

## Functional Programming (함수형 프로그래밍)

**함수형 프로그래밍은 할당문에 대해 규칙을 부과한다.**

- 컴퓨터 프로그래밍 자체보다 먼저 등장

- Alonzo Church (알론조 처치)는 앨런 튜링도 똑같이 흥미를 느꼈던 어떤 수학적 문제를 해결하는 과정에서 람다 (lambda) 계산법을 발명했는데, 함수형 프로그래밍은 이러한 연구 결과에 직접적인 영향을 받아 만들어졌다.

## 생각할 거리

각 패러다임은 프로그래머에게서 권한을 박탈한다. 즉, 패러다임은 무엇을 해야 할지를 말하기보다는 무엇을 해서는 안 되는지를 말해준다.

구조적 프로그래밍은 goto문을, 객체 지향 프로그래밍은 함수 포인터를, 함수형 프로그래밍은 할당문을 우리로부터 앗아간다.

## 결론

세 가지 패러다임과 아키텍처의 세 가지 큰 관심사(함수, 컴포넌트 분리, 데이터 관리)가 어떻게 서로 연관되는지 주목하자.
