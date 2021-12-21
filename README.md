# 2021 오픈소스소프트웨어 termproject

## 사용자의 양 손 움직임을 파악해서 두 동작이 같은지 판별하는 프로그램입니다.

#### reference
* https://google.github.io/mediapipe/solutions/hands.html (mediapipe)
* https://github.com/ntu-rris/google-mediapipe (손 동작 데이터 참조)
* https://github.com/kairess/Rock-Paper-Scissors-Machine (위의 데이터를 이용해서 가위바위보 게임을 하는 프로그램)

#### 구성
* gesture_train.csv (프로그램에 쓰일 11가지 손 동작에 대한 데이터)
* same.ipynb (메인 코드)

#### 프로그램 설명
* 구글에서 제작한 Mediapipe 오픈소스 기반으로 만들어진 프로그램입니다.
* 양 손가락을 관절과 관절 단위로 인지해서 움직임을 파악합니다.
* 총 11가지의 손동작 데이터를 이용해서 양 손의 움직임이 같으면 상단에 Same이라는 문구가 뜨게 합니다.

#### 예시 사진
<img width="1052" alt="스크린샷 2021-12-21 오후 11 35 43" src="https://user-images.githubusercontent.com/91201852/146950871-a4bb3363-2293-4e22-bc38-0f5abeded530.png">
<img width="1053" alt="스크린샷 2021-12-21 오후 11 35 22" src="https://user-images.githubusercontent.com/91201852/146951324-ea3d741c-8017-4227-889b-66b709d87bef.png">
<img width="1227" alt="22" src="https://user-images.githubusercontent.com/91201852/146951635-c56bbea6-bec3-4646-b4c3-63c7949a999c.png">

