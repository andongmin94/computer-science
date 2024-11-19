### [31강. CPU 스케줄링 개요](https://www.youtube.com/watch?v=CdrozYcVccE)

- CPU 스케줄링?
  - 운영체제가 프로세스들에게 공정하고 합리적으로 CPU 자원을 배분하는 것

- 가장 공정한 CPU 스케줄링?
  - CPU를 사용하고 싶어하는 프로세스들이 차례대로 돌아가며?
  - 아니다, 빨리 처리해야하는 프로세스가 있음(우선순위가 다르다)
![image](https://github.com/user-attachments/assets/8ad26f1e-5f6a-43aa-ab4a-ae2854d43846)

![image](https://github.com/user-attachments/assets/0e37b2ed-361a-4a2f-9156-f059d1b2c735)

![image](https://github.com/user-attachments/assets/1628ec89-9e8e-474f-bfa2-4b61445bbe15)

![image](https://github.com/user-attachments/assets/f3fe3c5e-9e00-4689-9bdb-076ba36a694c)

![image](https://github.com/user-attachments/assets/a6da9ec7-d9af-43e4-8015-3f530b497ed2)

![image](https://github.com/user-attachments/assets/ba8fddfe-0cea-4968-9cfc-de757cb21fa7)

- 선점형과 비선점형 스케줄링
![image](https://github.com/user-attachments/assets/71e69f00-7d53-427c-a5be-987e01a51c51)
  - 현재 CPU를 사용 중인 프로세스로부터 CPU 자원을 빼앗아 다른 프로세스에 할당
  - 현재 CPU를 사용 중인 프로세스의 작업이 끝날 때까지 프로세스 기다리게 함.
