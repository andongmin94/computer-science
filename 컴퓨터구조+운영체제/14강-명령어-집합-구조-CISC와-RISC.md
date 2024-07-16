### [14강. 명령어 집합 구조, CISC와 RISC](https://www.youtube.com/watch?v=lJwIERMo_N4)

- 허나 명령어마다 세세한 생김새, 연산, 주소 지정 방식 등은 CPU마다 다르다.
- 명령어 집합 (구조) : CPU가 이해할 수 있는 명령어들의 모음, ISA라고 부르기도 함.
  - 명령어가 달라지면 명령어 해석 방식, 레지스터의 종류와 개수, 파이프라이닝의 용이성 등 많은 것이 달라짐.
![image](https://github.com/user-attachments/assets/cb8de933-06d0-4062-8437-379e0bf712de)
![image](https://github.com/user-attachments/assets/79bb87e9-90ab-484e-bdbc-0c3740a0e51d)

- 명령어 집합의 두 축 CISC & RISC
- CISC(Complex Instruction Set Computer)
  - 복잡한 명령어 집합을 활용하는 컴퓨터(CPU)
  - x86, x86-64는 CISC기반 명령어 집합 구조
  - 메모리를 최대한 아끼며 개발해야했던 시절에는 인기가 높았으나
  - 명령어 파이프라이닝이 불리하다는 치명적인 단점이 있음.
  - 명령어가 워낙 복잡하고 다양한 기능을 제공하는 탓에
  - 명령어의 크기와 실행되기까지의 시간이 일정하지 않음.
  - 복잡한 명령어 때문에 명령어 하나를 실행하는데에 여러 클럭 주기가 필요함.
- RISC(Reduced Instruction Set Computer)
  - 명령어의 종류가 적고, 짧고 규격화된 명령어 사용
  - 메모리 접근 최소화(load, store), 레지스터 십분 활용
  - 명령어 종류가 CISC보다 적기에 더 많은 명령어로 프로그램을 동작시킴.
![image](https://github.com/user-attachments/assets/df89f1e9-2c2c-4fbc-a0e3-682e0d38bf1c)
