---
layout: single
title : "spring 면접 질문 2일차"
categories: spring 면접 질문
tag: [java, Spring]
toc: true
author_profile: true
---

## spring 면접 질문

# 7.  Call by reference란 무엇이고 보통 어떻게 쓰이나요?

함수를 호출 방식 중 참조에 의한 호출 방식을 말합니다.
함수를 호출할 때 메모리 공간 안에는 함수를 위한 별도의 임시 공간이 생성됩니다.
이 임시 공간은 함수 호출이 종료되면 사라집니다.
여기서 reference는 그 메모리 속 임시 공간에 있는 값에 대한 참조 주소를 말합니다.
함수를 직접 참조하는 방식이므로 함수 안에 값이 변경되면, 함수 호출할 때 있던 변수들도 값이 변경됩니다.


# 8. Override 와 Overload 를 설명해주실 수 있을까요?

Override는 상속과 관련된 개념으로 부모 클래스의 메소드를 재 정의합니다.

Overload는 이름이 비슷하지만 상속과는 관련 없는 내용입니다.
Overload는 같은 메소드라도 매개변수만 다르면 정의하고 사용할 수 있는 개념입니다.
Overload는 같은 기능을 하는 메소드를 하나의 이름으로 사용하기 위해 쓰는 개념입니다.


# 9. MVC 모델이란 무엇인지 설명해주실 수 있을까요?

model-view-controller의 약자로 개발을 할 때 3가지 형태로 나누어 개발하는 패턴을 말합니다.
사용자가 보는 페이지,컨트롤, 데이터 처리 이 3가지 방식을 구현한 것입니다.
크게 Client - Controller - Service - Repository - DB 구조가 MVC 패턴을 구현하는 흐름 방식입니다.
controller는 클라이언트의 요청을 처리 한 후 지정된 페이지에 모델 객체를 넘겨주는 역할을 합니다.
service는 controller에서 호출 받은 요청을 처리하는 역할을 합니다.
DB의 데이터가 필요한 요청을 경우 Repository에게 요청을 하고  알맞은 정보를 가공하여 controller에게 데이터를 넘겨줍니다.
그리고 controller는 servic의 결과물 데이터를 사용자에게 전달해줍니다.
repository는 entity에 의해 생성된 db에 접근하는 메소드들을 사용하기 위한 인터페이스입니다.
DB에 연결,해제, 데이터 관리를 합니다.