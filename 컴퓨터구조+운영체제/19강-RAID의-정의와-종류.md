### [19강. RAID의 정의와 종류](https://www.youtube.com/watch?v=lgFmNUG_Atw)

![image](https://github.com/user-attachments/assets/7b0d8e36-9197-4936-9b2d-6822ba4812b3)

- RAID의 정의
  - RAID (Redundant Array of Independent Disks)
    - 하드 디스크와 SSD로 사용하는 기술
    - 데이터의 안전성 혹은 높은 성능을 위해 여러 물리적 보조기억장치를 마치 하나의 논리적 보조기억장치처럼 사용하는 기술
  - RAID 레벨
    - RAID를 구성하는 기술
    - RAID 0, RAID 1, RAID 2, RAID 3 ... 6
    - 그로부터 파생된 RAID 10, RAID 50 ...

![image](https://github.com/user-attachments/assets/fac8e52c-5713-431b-b6f4-c5136332edf8)

![image](https://github.com/user-attachments/assets/3b394418-bcb3-41c4-9552-a13da9f9d5dd)

- RAID 0
  - 장점 : 입출력 속도의 향상
  - 단점 : 저장된 정보가 안전하지 않음.
 
![image](https://github.com/user-attachments/assets/1da5569e-637d-436e-8996-ce7b8eb69ae2)

- RAID 1
  - 미러링 (mirroring) : 복사본을 만드는 방식
  - 데이터를 쓸 때 원본과 복사본 두 군데에 씀 (느린 쓰기 속도)
  - 장점 : 백업과 복구가 쉬움.
  - 단점 : 하드 디스크 개수가 한정되었을 때 사용 가능한 용량이 적어짐.

![image](https://github.com/user-attachments/assets/0566c34c-f311-4fc3-a909-db9005e8b7b4)

- RAID 4
  - RAID 1처럼 완전한 복사본을 만드는 대신 오류를 검출하고 복구하기 위한 정보인 패리티 비트를 저장함.
  - 단점 : 패리티 디스크의 병목

![image](https://github.com/user-attachments/assets/35c07b24-94c8-4ec4-90b4-4192e21a4e8b)
![image](https://github.com/user-attachments/assets/d3af3cee-383b-44d8-bbcd-28453a3c4033)

- RAID 5
  - 패리티 정보를 분산하여 저장하는 방식

![image](https://github.com/user-attachments/assets/9a0f002b-00b6-4980-bbc2-0e775534e597)

- RAID 6
  - 두 종류의 패리티(오류를 검출하고 복구할 수 있는 수단)
  - RAID 5보다 안전, 쓰기는 RAID 5보다 느림.

![image](https://github.com/user-attachments/assets/b2a23066-62d2-451e-8a28-4b6e25c44fca)

![image](https://github.com/user-attachments/assets/c2af7ea0-8b11-4403-883c-c01dc250a24a)
