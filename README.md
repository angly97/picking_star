# :last_quarter_moon_with_face: 별 따러 온 그대 

## Description

​	   <img src ="./img/whole_project.JPG" width=70% height=70%>

* 빗자루를 통해 공중을 비행하는 판타지적 환경의 체험과 더불어 장애물을 피하고,  별을 획득해 포인트를 얻는 방식의 게임
* 소프트웨어
  * 사용자가 보게 될 가상 현실을 구현
  * 하드웨어로부터 받은 신호(센서 값 등)으로, 가상 현실 내 사용자를 움직임
 * 하드웨어
   * 사용자가 탑승하게 될 장치를 제어
   * 빗자루의 손잡이에 부착된 압력센서 값에 따라 상하 움직임 신호를 Unity에 전송
   * 빗자루 안장에 부착된 자이로센서 값에 따라 좌우 움직임 신호를 Unity에 전송



## Requirement

* HTC VIVE Pro
* UnityHub / Unity2019.1.9.f1
* SteamVR Plugin 1.9.8 or higher
* Arduino uno



## Source

* git hub 용량을 초과하여 구글 드라이브에 업로드
* [2020ESWContest_free_1041 - Google Drive](https://drive.google.com/drive/folders/1n_OGDoIQfan4W8vJZi0yunpLkgdFYJZw)
* Unity 코드:  Flying Game_1.zip
* Arduino 코드: Hardware.ino



## Test

1. VIVE 하드웨어 설정 가이드를 따라 VIVE 설정
2. PC와 Arduino 연결
3. 하드웨어 회로에 25V 인가
4. Unity 실행
