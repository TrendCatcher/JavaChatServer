# Mission - Chatting Server

## 🔍 진행 방식

- VM ware 상에서 우분투를 활용하여 채팅서버를 구현
- Phase 가 거듭될수록 다양한 기능이 추가됨을 터미널에서 `git diff` 명령어를 통하여 확인한다.   
- 기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.
- Test Case를 통해 요구사항에 맞게 SW가 설계되었는지 검증한다.

## 📮 진행 내용

- Simple notation for Server, Process, Thread
    - Client-Server Architecture의 이해
    - Server, Process, Thread 표기법
    
- SimpleChat Phase 2
    - Client side
        '#quit' : 클라이언트를 종료시킨다. 프로그램을 종료시키기전 서버가 먼저 종료되어야함
        '#logoff' : quit은 아니지만 서버와 클라이언트의 연결을 끊는다.
        '#sethost<host>' : 클라이언트안의 setHost메소드를 호출, 클라이언트가 logoff되어 있을떄만 허용한다; 아니면 오류메시지 출력함
        '#setport' : 클라이언트 안의 setPort메소드를 호출, '#setHost와 동일하다.' 
        '#login' : 클라이언트와 서버를 연결. 
        '#gethost' : 현재 호스트 이름을 나열
        '#getport' : 련재 포트번호 나열
    - Server side :
    
- SimpleChat Phase 3~4
    - Client side
    - Server side

## 🚨 다양한 패턴방식 적용

- MVC pattern
- Observer Pattern 
- Factory Pattern 

### Observer pattern
클래스 다이어그램을 통해서 객체의 상태변화를 관찰하는 Obervers의 동작원리를 이해
실시간 통신이 어려운 기존의 polling 방식에서 벗어나 update()함수를 사용하는 방식 적용


```

```

---

## 🚀phase 2 기능 요구 사항

1.
2.
3. 

---

## 🎯 프로그래밍 요구 사항

- JDK 11 버전에서 실행 가능해야 한다. **JDK 11에서 정상적으로 동작하지 않을 경우 0점 처리한다.**
- `build.gradle`을 변경할 수 없고, 외부 라이브러리를 사용하지 않는다.
- 프로그램 종료 시 `System.exit()`를 호출하지 않는다.
- 프로그램 구현이 완료되면 `ApplicationTest`의 모든 테스트가 성공해야 한다. **테스트가 실패할 경우 0점 처리한다.**
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 이름을 수정하거나 이동하지 않는다.

---
