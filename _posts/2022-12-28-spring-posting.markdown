---
layout: single
title : "spring 면접 질문 9일차"
categories: spring 면접 질문
tag: [java, Spring]
toc: true
author_profile: true
---

## spring 면접 질문

# 25. Base64 인코딩이란 무엇인가요?

Base64란 이진데이터를 6비트 묶음으로 표현해 64개의 ASCII 문자들로 변환시키는 인코딩입니다.

# 26. 프로세스와 스레드를 비교하여 설명해주실 수 있을까요?

프로그램이 실행되는 상태, 컴퓨터가 어떤 일을 하고 있는 상태를 프로세스라고 합니다.
즉, 우리가 쓰고 있는 프로그램이 OS에 의해 메모리 공간을 할당 받아 실행 중인 것을 말합니다.
스레드는 프로세스 내에서 실제로 작업을 수행하는 주체를 의미합니다.
모든 프로세스에는 한 개 이상의 스레드가 존재하여 작업을 수행합니다.
예를 들어, 크롬을 열면 하나의 프로세스가 실행되고 있는 것인데, 크롬을 열어 게임을 다운로드 받으면서 검색도 할 수 있습니다.
이 게임을 다운로드 받거나 검색을 하는 갈래 하나하나가 스레드입니다.

# 27. 동기와 비동기를 비교하여 설명해주실 수 있을까요?

동기는 요청과 응답이 동시에 일어난다는 의미이고, 비동기는 요청과 응답이 동시에 일어나지 않는다를 의미합니다.
동기는 설계가 매우 간단하고 직관적이지만 결과가 주어질 때까지 멈춰있는 상태로 대기해야 하는 단점이 있습니다.
비동기는 동기보다 설계가 복잡하지만 결과가 주어지는데 시간이 걸려도 그 동안 다른 작업을 할 수 있어 자원을 효율적으로 사용할 수 있습니다. 