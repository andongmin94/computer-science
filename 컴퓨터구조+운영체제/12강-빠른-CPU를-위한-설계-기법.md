### [12강. 빠른 CPU를 위한 설계 기법](https://www.youtube.com/watch?v=VO0RQAA7KYc)

![image](https://github.com/andongmin94/computer-science/assets/110483588/25d22f27-f08f-447d-8ae2-9a9267f8d3b9)

- CPU의 속도를 빠르게 만들려면
  - 컴퓨터 부품들은 '클럭 신호'에 맞춰 일사불란하게 움직인다.
  - CPU는 '명령어 사이클'이라는 정해진 흐름에 맞춰 명령어들을 실행한다.

- 클럭 속도 : 헤르츠(Hz) 단위로 측정
- 헤르츠(Hz) : 1초에클럭이 반복되는 횟수
- 클럭이 똑딱 하고 1초에 한번 반복되면 1Hz
- 클럭이 1초에 100번 반복되면 100Hz

- 코어(Core)란?
  - 현대적인 관점에서 "CPU"라는 용어를 재해석해야함.
  - '명령어를 실행하는 부품'?
  - 전통적으로 '명령어를 실행하는 부품'은 원칙적으로 하나만 존재함.
  - 하지만 오늘날 CPU에는 '명령어를 실행하는 부품'이 여러개 존재함.
  - '명령어를 실행하는 부품'을 코어라는 용어로 사용
![image](https://github.com/andongmin94/computer-science/assets/110483588/85ff9a01-ee0c-44b5-83ce-00b7cf7e3c3a)

- 멀티코어
![image](https://github.com/andongmin94/computer-science/assets/110483588/c89a2288-f77c-4887-9647-cde2c059b566)

- 스레드와 멀티 스레드
  - 스레드란 '실행 흐름의 단위'
![image](https://github.com/andongmin94/computer-science/assets/110483588/f969585f-0375-40d7-8da4-84b0b86cdd48)
  - 하드웨어 스레드 : 하나의 코어가 동시에 처리하는 명령어 단위, 논리 프로세서라고도 부른다.
  - 소프트웨어 스레드 : 하나의 프로그램에서 독립적으로 실행되는 단위
![image](https://github.com/andongmin94/computer-science/assets/110483588/b73cd315-a48d-4c1f-ab82-2844b6108f69)
