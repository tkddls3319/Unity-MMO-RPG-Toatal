# My-MMO-RPG-Total

Unity MMORPG Total 프로젝트는 클라이언트, 서버, 그리고 패킷 자동화 프로그램으로 구성된 멀티플레이어 온라인 MMORPG 시스템을 개발한 결과물 입니다.
Unity를 활용한 게임 개발과 C# 기반의 고성능 IOCP 서버를 결합하여 실시간 멀티플레이 환경의 베이스 제공합니다.

서버를 먼저 실행시키고 Unity빌드 파일을 여러개 실행시켜 테스트를 진행 할 수 있습니다.

## 프로젝트 구성

### Client 폴더
- Unity로 구현된 클라이언트 프로젝트로, 실시간 데이터 송수신과 사용자 인터페이스를 관리합니다.
- **My-MMORPG-Client 저장소와 동일**

### Server 폴더
- C# 기반의 IOCP 서버로, 클라이언트 간의 실시간 데이터 동기화와 게임 상태 관리를 담당합니다.
- **My-MMORPG-Server 저장소와 동일**

### Common 폴더
- 패킷 자동화 프로그램으로, Protobuf 기반의 패킷 정의를 바탕으로 클라이언트와 서버에서 공용으로 사용할 C# 코드를 자동 생성합니다.
- **My-MMORPG-PacketControl 저장소와 동일**

## 주요 특징
- **Unity와 IOCP 서버의 결합**:
  - Unity 클라이언트를 IOCP 기반 서버와 통신 가능하도록 설계.
- **멀티플레이 환경**:
  - 1,000명 이상의 클라이언트가 동시에 접속 가능한 서버.
- **유지보수성과 확장성**:
  - 다양한 디자인 패턴 적용 및 모듈화된 구조.
- **실시간 상호작용**:
  - 플레이어 간 채팅, 이동, 스킬 사용 등을 지원.

## 조작 방법
- **이동**: `W`, `A`, `S`, `D`
- **공격 모션**: `Space Bar`

- ![Lobby](https://github.com/tkddls3319/My-MMORPG-Client/assets/54829486/40da8c9a-3729-4947-807f-6784cbf4b4f4)
![Game](https://github.com/tkddls3319/My-MMORPG-Client/assets/54829486/8a31a323-f72b-4046-978c-01ee3966b24a)

https://github.com/tkddls3319/My-MMORPG-Client/assets/54829486/d5026087-c4fc-49fa-9784-d0226afd0a12

https://github.com/tkddls3319/My-MMORPG-Client/assets/54829486/ee0cc47b-7455-474d-8bc0-194cdb9ff70a
