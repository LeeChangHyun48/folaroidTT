# TT - For TRPG with Online!

![185549536-c7840946-7b3b-4174-bf82-a2d307e4a308](https://user-images.githubusercontent.com/116571873/198022314-607437c8-5da0-4de8-9f96-47beaaa16b06.png)

## TT 소개
[TT](https://i7a809.p.ssafy.io/)
온라인에서도 TRPG를 즐길 수 있는 서비스입니다!

## 기획 배경
오프라인에서 즐길 수 있는 TRPG를 시간과 공간에 제약을 줄이고 TRPG의 장르상 입문하기 어려운 진입장벽을 허물어 간단한 UI와 짧은 플레이 타임으로 누구나 쉽게 즐길 수 있는 서비스를 기획하고자 했습니다.

## 서비스 화면
### 첫 화면
  
![185575228-57aee800-b0ce-43ef-8177-b7d973018e25](https://user-images.githubusercontent.com/116571873/198022673-1ef4fb05-574c-4a64-b6b0-33aebd8290f8.png)
홈페이지에 들어갔을 나타나는 첫 화면입니다.
회원가입을 진행하신 다음, 로그인을 하면 서비스를 이용할 수 있습니다.

### 1. 파티 모집 게시판 - 작성

![185575440-0e6ab967-ae25-413d-bcb2-26c758cd1892](https://user-images.githubusercontent.com/116571873/198022806-e869153d-bc93-40ec-b844-e5d0f3ad644b.png)

같이 게임을 즐길 인원을 모집하는 게시판입니다.<br />
같이 플레이할 인원 수와 게임할 시간, 그리고 작성자가 GM과 플레이어 중 어느 포지션으로 게임을 뛸 것인지 고를 수 있습니다.

### 2. 파티 모집 게시판 - 플레이어 등록

![185575586-93d4c5f7-5fc8-4055-8d6c-ead14d770a7c](https://user-images.githubusercontent.com/116571873/198022916-944a429c-de89-47e8-aeb0-7a10e8847b56.png)

파티 모집 중인 게시물에 들어가서 참가 신청을 할 수 있습니다.

### 3. 파티 모집 게시판 - 방 입장

![185575683-56bfd208-2831-4aa1-9064-5562b6f6fc77](https://user-images.githubusercontent.com/116571873/198023031-7f180e0a-74ff-4cd6-bb9d-bb97114dc341.png)

게시글에 적힌 시간이 되면 참가 신청을 한 사람에 한하여 방에 입장할 수 있는 버튼이 생깁니다.

### 4. 플레이어 첫 화면
  
![185575998-e958851f-d4bc-4dde-aed5-c2ebea3c3b01](https://user-images.githubusercontent.com/116571873/198023598-62f79b88-9b8a-479f-a863-6652d90408fc.png)

플레이어가 방에 입장한 후 보이는 첫 화면입니다.<br />
직업을 고를 수 있고, info를 통해 해당 직업에 대한 설명도 볼 수 있습니다.

### 5. 플레이어 캐릭터 프로필      

![185576188-1acb8346-2721-4392-ae2c-a2e0587e0969](https://user-images.githubusercontent.com/116571873/198023704-557c9ca8-a770-4a51-8747-dfc1fb87e02d.png)

처음 보이는 캐릭터 프로필 생성을 완료하면 볼 수 있는 프로필 화면입니다.

### 6. GM 첫 화면

![185575827-87d630d8-9e54-44e3-aaaa-42e629b7900a](https://user-images.githubusercontent.com/116571873/198023868-9dc4a90c-ba7b-4ecb-9051-e7a6c9dec06d.png)

GM이 방에 입장한 후 보이는 첫 화면입니다.<br />
GM은 플레이어와 다르게 프로필을 생성하지 않습니다. 다만 GM만이 운영할 수 있는 시스템이 있습니다.

### 7. GM 게임 운영 메뉴     

![185575918-e3bef179-73d5-4f3e-acbb-a65798567613](https://user-images.githubusercontent.com/116571873/198023927-f3013f4e-9cc2-4039-ba1f-98526e896402.png)

GM이 게임을 진행하면서 누를 수 있는 버튼입니다.<br />
플레이어의 HP에 변화를 주거나, 아이템을 주고, 스탯을 보상으로 주는 등의 메뉴가 있습니다.

### 8. 지도  

![185576270-33ad317d-24d6-4167-a8b4-70bb63ceea0a](https://user-images.githubusercontent.com/116571873/198024273-3357960a-0396-4034-9f5c-d518bd920c27.png)

지도입니다. 여러분이 계신 또 다른 공간을 보여줍니다. GM만이 지도에서 장소를 변경할 수 있습니다. <br />플레이어는 지도를 클릭하면 해당하는 지역의 몬스터 정보를 볼 수 있습니다.

### 9. 주사위     

![185576323-3d5445a7-7b05-444a-8a03-040608ce3aa0](https://user-images.githubusercontent.com/116571873/198024443-d5a4f696-d411-41af-a4c7-7014fe9366d3.png)
  
주사위입니다. 여러분의 실력에 따라 미래가 바뀔 것입니다.


## 개발
### 기술 스택
- FRONTEND:       
  - JAVASCRIPT
  - TYPESCRIPT
  - React
  - ReactRouter
  - REDUX       
  - Axios
  - SockJS
  - StompJS    

- **BACKEND**:    
  - SpringBoot
  - JPA
  - JWT   
  - MYSQL

- **CI/CD**

  - Amazon EC2
  - NGINX
  - Docker

### 사용 IDE
- FRONTEND:     
  - VSCODE
- BACKEND:     
  - INTELLIJ
  - MYSQLWorkbench
- 추가:   
  - MobaXterm


## 플로우 차트
1. 프론트엔드
![untitled - Chrome 2022-08-19 오후 3_47_07](https://user-images.githubusercontent.com/40424414/185560235-b2af36ba-41c5-4605-b05b-8d5d632bf3f5.png)
![untitled - Chrome 2022-08-19 오후 3_48_08](https://user-images.githubusercontent.com/40424414/185560369-10754daa-868e-4c91-87e6-d04f4b8e86e1.png)
2. 백엔드
![서버1](https://user-images.githubusercontent.com/40424414/185569561-f4faf474-e104-4a85-8500-0c742072cb2c.jpg)
![서버2](https://user-images.githubusercontent.com/40424414/185571697-a0f01b5b-1513-495f-acff-404e97ab73be.jpg)

## 배포 환경

- Ubuntu 20.04.4 LTS

- Node.js 16.16.0

- NGINX 1.18.0 (Ubuntu)

- Docker version 20.10.17

- JAVA openjdk version 1.8.0_342

### 배포 아키텍쳐

![화면 캡처 2022-08-19 200133](https://user-images.githubusercontent.com/116571873/198024558-ebb63f40-d417-4657-b41d-55e4e9c5907e.png)


## 팀 멤버

![화면 캡처 2022-08-19 200854](https://user-images.githubusercontent.com/116571873/198024641-50538094-2895-4b34-ab60-da44b217e648.png)
