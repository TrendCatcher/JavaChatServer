# Mission - Chatting Server

## 🔍 진행 방식

- VM ware 상에서 우분투를 활용하여 채팅서버를 구현
- Phase 가 거듭될수록 다양한 기능이 추가됨을 터미널에서 `git diff` 명령어를 통하여 확인한다.   
- 기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.

## 📮 진행 내용

- Simple notation for Server, Process, Thread
    - Client-Server Architecture의 이해
    - Server, Process, Thread 표기법
- SimpleChat Phase 2
    - Client side
    - Server side
- SimpleChat Phase 3~4
    - Client side
    - Server side

## 🚨 다양한 패턴방식 적용

- MVC pattern
- Observer Pattern 
- Factory Pattern 

### 테스트 실행 가이드

- 터미널에서 `java -version`을 실행하여 Java 버전이 11인지 확인한다. 또는 Eclipse 또는 IntelliJ IDEA와 같은 IDE에서 Java 11로 실행되는지 확인한다.
- 터미널에서 Mac 또는 Linux 사용자의 경우 `./gradlew clean test` 명령을 실행하고,   
  Windows 사용자의 경우  `gradlew.bat clean test` 명령을 실행할 때 모든 테스트가 아래와 같이 통과하는지 확인한다.

```
BUILD SUCCESSFUL in 0s
```

---

## 🚀 기능 요구 사항
아래의 7가지 기능 요구 사항을 모두 해결해야 한다.

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
