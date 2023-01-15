# 2023_CSL_Note
## 1. Box
- 실험실 인터넷 환경으로 인해 sudo apt upgrade 등의 다운로드 명령어 실행 시간이 너무 길어짐. 그래서 daum kakao 서버로 바꾸게 변경(https://jhleeeme.github.io/change-apt-server/)
- LAN 포트가 1개인 nuc과 2개인 nuc의 nuc 포트 명칭 차이를 구분하는 설명을 필요한 부분마다 넣어두는 것이 안 헷갈릴 것 같음
- 2-4에 'ovs-vsctl show' -> 'sudo ovs-vsctl show'
## 2. InterConnect
- PI에 설치할 OS를 HypriotOS 1.9에서 1.12.3으로 변경
- HypriotOS 1.12.3은 OS 설치 후 ip 설정이 필요한데 이를 위해 /etc/network/interface에 설정 후 재부팅(재부팅 했을 시에도 안된다면 /etc/network/interface.d/<file name> 경로의 file name을 삭제한 후 재부팅 해보기)
## 3. Tower
## 4. IoT
- python3에서 Adafruit를 import 못하는 문제가 있는데 'sudo pip3 Adafruit'하면 해결 가능
