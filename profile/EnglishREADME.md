# :lock: DID-based facility use agreement generation and verification system
There is a risk of personal information leakage when writing a consent form for facility use or consent form for personal information in an offline environment. The consent form for the use of facilities written in paper is inconvenient for business operators to manage, and it is cumbersome for users to fill out and submit it in paper.

**Our custom sign service** is a DID based personal information submission system that utilizes SSI(Self-Signature Identifier) which is managed by users with sovereignty over personal information And we also uses PlateChain, the open-source public blockchain we made..

## 서비스 소개
<p align="center">
<a href="https://coral-piranha-fd5.notion.site/CustomSign-2521b412b83144498284b498f67f8a9d"><img  src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" width=160></a>
<a href="https://www.youtube.com/watch?si=hySRRINMpvC4hQV1&v=x4O0WdMcpEY&feature=youtu.be"><img  src="https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=Youtube&logoColor=white" width=175></a>
<a href="http://www.customsign.shop"><img  src="https://user-images.githubusercontent.com/83829352/266290884-d336e405-8138-4c94-b0bc-8b87b79a0b1e.png" width=150></a>
</p>

<p align="center">
<b>DemoID : theclimb01 / DemoPW : theclimb01!</b>
</p>

### 📱 사용자 앱
[Repository (GitHub)](https://github.com/2023-oss/OSS-APP)
<p>
<img src="https://user-images.githubusercontent.com/22852287/265966811-21446caf-4c1e-4e1a-b366-91f08a0a686d.png">
</p>

### 🖥️ 기관 페이지
[Repository (GitHub)](https://github.com/2023-oss/OSS-WEB)
<p>
<img src="https://github.com/2023-oss/OSS-WEB/assets/102888719/6a0ad2c5-1476-43f1-9a90-a124aab8376a">
</p>
<p>
<img src="https://github.com/2023-oss/OSS-WEB/assets/102888719/ad414a3e-ce1f-4f4e-a886-cf741eeaa27b">
</p>

### 🕸️ 블록체인

[Repository (GitHub)](https://github.com/2023-oss/OSS-PLATECHAIN)
### :mag: 기관 서버

[Repository (GitHub)](https://github.com/2023-oss/OSS-BACKEND)

### ⚡ 인증 서버
[Repository (GitHub)](https://github.com/2023-oss/OSS-ISSUER)


## 아키텍처
<br/>

![](https://user-images.githubusercontent.com/22852287/265968000-09658fac-4e28-4456-81d3-d64959ce978c.png)

## 프로젝트 플로우차트
### DID란?
Decentralized Identity(탈중앙 신원증명, DID)는 데이터의 주권을 개개인에게 부여하고 중앙화된 제 3자를 거치지 않고 인증에 성공할 수 있는 차세대 인증방식 입니다. 특정 기관이 신원 정보를 갖고 있는 것이 아니라, 블록체인에서 모든 블록에 신원이 분산되어 있습니다. <br/>
DID를 통해 개인정보는 개인이 소유하고, 필요할 때 최소한의 정보만 활용할 수 있어 신원주권을 회복할 수 있습니다.
![](https://user-images.githubusercontent.com/83829352/266076494-7cd11b21-a114-434e-89b6-7890774c0506.png)

### 전체적인 흐름도
![](https://user-images.githubusercontent.com/83829352/266094215-16944ccc-321e-4531-974f-0148fe998f71.png)

## ⚙️ 주요 오픈소스 사용정보
### 📊 `BlockChain`

|service|version|
|--|--|
|**NodeJS**|v14.x|
|**NGINX**|v1.23.x|
|**Docker Compose**|v20.x|
|**Helia**|v3.2.x|
|**Couchbase**|v2.x|

### 🖇  `Server`

|service|version|
|--|--|
|**SpringBoot**|v2.7.x|
|**Redis**|v3.0.x|
|**CoolSMS**|sms_service|
|**MySQL**|8.3.x|
|**Docker**|v24.0.x|


### 🚏 `Web`
|service|version|
|--|--|
|**React**|v16.x|
|**react-beautiful-dnd**|v4.x|
|**styled-component**|v3.0.x|

### 📱 `APP`

|service|version|
|--|--|
|**Flutter**|v3.x|
|**Figma**|web_service|

## 👪 팀 정보
- 김채원 (chae401@naver.com), Github Id: chae401 (Server, Web)

- 강은솔 (eunsol2953@gmail.com), Github Id: eunsolkang (Blockchain, App)

- 이창규 (darkdon66@naver.com), Github Id: mangoggul (Web)

- 김수민 (haon0319@naver.com), Github Id: eunsolkang (Design)

## ⚖️ 저작권 및 사용권 정보

* [GNU]([https://github.com/osamhack2022/CLOUD_APP_IOT_KeepYourEndeavor_Moment/blob/main/LICENSE](https://github.com/2023-oss/.github/blob/main/LICENSE))

This project is licensed under the terms of the GNU license.

