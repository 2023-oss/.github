# :lock: DID 기반 시설이용 동의서 생성 및 검증 시스템
오프라인 환경에서의 시설이용 동의서나 개인정보 동의서 작성시 개인정보 유출에 위험이 있습니다. 
종이로 작성되는 시설이용 동의서는 사업자 입장에서도 관리하기 불편한 부분이 있고 사용자 입장에서도 종이로 작성하고 제출하는것은 번거로운 일입니다. 

**커스텀 사인** 서비스는 자체적으로 개발한 오픈소스 퍼블릭 블록체인 	`Plate Chain` 을 활용하여 
사용자가 개인정보에 대한 주권을 가지고 개인이 관리하는 `SSI : Self Soverign Identifier 자기주권 신원` 개념을 활용하는  `DID : Decentralized Identifier 분산 식별자`  기반 개인정보 제출 시스템입니다.

## 서비스 소개
### 📱 사용자 앱
[Repository (GitHub)](https://github.com/2023-oss/OSS-APP)
<p>
<img src="https://user-images.githubusercontent.com/22852287/265966811-21446caf-4c1e-4e1a-b366-91f08a0a686d.png">
</p>

### 🖥️ 기관 페이지
[Repository (GitHub)](https://github.com/2023-oss/OSS-WEB)
### 🕸️ 블록체인
[Repository (GitHub)](https://github.com/2023-oss/OSS-PLATECHAIN)
### :mag: Verifier Server
[Repository(GitHub)](https://github.com/2023-oss/OSS-BACKEND)

### ⚡ Issuer Server
[Repository(GitHub)](https://github.com/2023-oss/OSS-ISSUER)
<br/>
<br/>
## 아키텍처

![](https://user-images.githubusercontent.com/22852287/265968000-09658fac-4e28-4456-81d3-d64959ce978c.png)

## 프로젝트 플로우차트
![](https://user-images.githubusercontent.com/83829352/266076494-7cd11b21-a114-434e-89b6-7890774c0506.png)

### 전체적인 흐름도
![](https://user-images.githubusercontent.com/83829352/266093392-af17dc2a-88f8-4446-a5e7-69ab55032fd4.jpg)

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
|**CoolSMS**|cloud_service|
|**MySQL**|8.3.x|
|**AWS S3**|storage_service|
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

- 이창규 (mangoggul@gmail.com), Github Id: mangoggul (Web)

- 김수민 (haon0319@naver.com), Github Id: eunsolkang (Design)

## ⚖️ 저작권 및 사용권 정보

* [GNU]([https://github.com/osamhack2022/CLOUD_APP_IOT_KeepYourEndeavor_Moment/blob/main/LICENSE](https://github.com/2023-oss/.github/blob/main/LICENSE))

This project is licensed under the terms of the GNU license.