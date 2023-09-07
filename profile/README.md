<p align="center">
<a href="http://www.customsign.shop"><img width = "500px" src='https://user-images.githubusercontent.com/83829352/266327858-61f56df2-663a-4952-ab22-47936be470fa.png'/>
</a>
</p>
<br/>
<br/>
<p align="center">
<img src="https://img.shields.io/github/contributors/2023-oss/OSS-PLATECHAIN">
<img src="https://img.shields.io/github/languages/count/2023-oss/OSS-PLATECHAIN">
<img alt="GitHub license" src="https://img.shields.io/github/issues/2023-oss/OSS-PLATECHAIN">
<img alt="GitHub license" src="https://img.shields.io/github/issues-closed/2023-oss/OSS-PLATECHAIN">
<img src="https://img.shields.io/github/license/2023-oss/OSS-PLATECHAIN">
</p>
<p align="center">
<a href="https://coral-piranha-fd5.notion.site/CustomSign-2521b412b83144498284b498f67f8a9d"><img  src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" width=90></a>
<a href="https://www.youtube.com/watch?si=hySRRINMpvC4hQV1&v=x4O0WdMcpEY&feature=youtu.be"><img  src="https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=Youtube&logoColor=white" width=95></a>
<a href="http://www.customsign.shop"><img  src="https://user-images.githubusercontent.com/83829352/266290884-d336e405-8138-4c94-b0bc-8b87b79a0b1e.png" width=90></a>
</p>

<br/>
<br/>

# :lock: DID 기반 시설이용 동의서 생성 및 검증 시스템



오프라인 환경에서의 시설이용 동의서나 개인정보 동의서 작성시 개인정보 유출에 위험이 있습니다.

종이로 작성되는 시설이용 동의서는 사업자 입장에서도 관리하기 불편한 부분이 있고 사용자 입장에서도 종이로 작성하고 제출하는 것은 번거로운 일입니다.

  

**커스텀 사인** 서비스는 자체적으로 개발한 오픈소스 퍼블릭 블록체인 `Plate Chain` 을 활용하여

사용자가 개인정보에 대한 주권을 가지고 개인이 관리하는 `SSI : Self Soverign Identifier 자기주권 신원` 개념을 활용하는 `DID : Decentralized Identifier 분산 식별자` 기반 개인정보 제출 시스템입니다.

현재 서비스 하고있는 Blockchain DID 서비스가 많지만 기존에 DID가 내역 증빙과 문서의 신뢰도를 다뤘다면 우리 오픈소스는 좀 더 개인정보 보호를 위한 문서 자동파기 시스템들을 고안하여 추가적인 메리트를 제공합니다.

또한 다른 퍼블릭 블록체인 (ex. 이더리움, 비트코인) 등에 의존하거나 완성된 프레임워크를 활용하지 않고
**직접 개발한** 퍼블릭 블록체인 네트워크를 활용한 오픈소스 프로젝트이기 때문에 새로운 아이디어나 DID 에 접목시켜볼 기술이 있을 때 가볍게 적용해볼 수 있습니다. 

  

## 서비스 소개

### 📱 사용자 앱

[Repository (GitHub)](https://github.com/2023-oss/OSS-APP)

사용자는 PlateWallet App 을 통해서 개인정보를 보관하고 필요시 기업에게 제출할 수 있는 기능을 제공합니다.

<p>

<img  src="https://user-images.githubusercontent.com/22852287/265966811-21446caf-4c1e-4e1a-b366-91f08a0a686d.png">

</p>

  

### 🖥️ 기관 페이지

[Repository (GitHub)](https://github.com/2023-oss/OSS-WEB)

<p  align="center">

<b>DemoID : theclimb01 / DemoPW : theclimb01!</b>

</p>

개인정보 동의서나 기관이용 동의서를 오프라인으로 관리하는 기업 또는 업장을 위한 웹 서비스 입니다.
Drag and Drop 방식으로 간편하게 동의서를 제작할 수 있고 사용자들이 제출한 동의서를 디지털로 간편하게 관리할 수 있습니다.

<p>

<img  src="https://github.com/2023-oss/OSS-WEB/assets/102888719/6a0ad2c5-1476-43f1-9a90-a124aab8376a">

</p>

<p>

<img  src="https://github.com/2023-oss/OSS-WEB/assets/102888719/ad414a3e-ce1f-4f4e-a886-cf741eeaa27b">

</p>

  

### 🕸️ 블록체인
[Repository (GitHub)](https://github.com/2023-oss/OSS-PLATECHAIN)

DID 기능과 암호화폐 전송 기능을 갖춘 PoW 기반 퍼블릭 블록체인입니다. 

- [블록체인 뷰어](http://block.platechain.shop/) 에서 모든 블록체인 트랜잭션과 블록을 조회할 수 있습니다.
- [블록체인 지갑](http://block.platechain.shop/) 상장되어있지만 송금 기능과 지갑기능을 확인해볼 수 있는 PTC 단위의 블록체인 지갑 데모입니다.  
![](https://user-images.githubusercontent.com/22852287/266316405-1a42dbd8-b4fa-452e-9488-5a82d89a47b3.png)
  



### :mag: 기관 서버
동의서를 보관하고 VP 와 퍼블릭키를 통해서 검증하며 블록체인의 정보를 바탕으로 자동 파기를 담당합니다.

[Repository (GitHub)](https://github.com/2023-oss/OSS-BACKEND)

  

### ⚡ 인증 서버
VC 생성 및 발급을 담당합니다. 

[Repository (GitHub)](https://github.com/2023-oss/OSS-ISSUER)

  
  

## 아키텍처

<br/>

  

![](https://user-images.githubusercontent.com/22852287/265968000-09658fac-4e28-4456-81d3-d64959ce978c.png)

  

## 프로젝트 플로우차트

### DID란?

Decentralized Identity(탈중앙 신원증명, DID)는 데이터의 주권을 개개인에게 부여하고 중앙화된 제 3자를 거치지 않고 인증에 성공할 수 있는 차세대 인증방식 입니다. 개인정보를 본인의 단말기에 저장하여 내가 나임을 증명해야할 때 **내가 직접** 제출하는 방식입니다.

DID를 통해 개인정보는 개인이 소유하고, 필요할 때 최소한의 정보만 활용할 수 있어 자기신원주권 (SSI) 이라고 불립니다.

![](https://user-images.githubusercontent.com/83829352/266076494-7cd11b21-a114-434e-89b6-7890774c0506.png)

1. 사용자(Holder), 발급 기관 (Issuer) 은 각각 공개키 쌍을 생성해서 블록체인 네트워크에 전송합니다.
2. 사용자(Holder)는 검증된 발급 기관 (Issuer) 으로 부터 서명된 사용자 자격(VC) 를 발급받습니다. 
3. 사용자는 발급 받은 자격 (VC) 를 블록체인에 있는 공개키로 검증 후 신뢰하는 기관이 발급한 자격이라면 개인 단말기에 생체정보나 패스워드를 통해서 암호화 후 단말기에 저장합니다. 
4. 개인정보를 전송해야하는 기업(Verifier) 이 있다면 기기에 있는 자격(VC) 을 바탕으로 기업이 요청한 정보를 조합하여 VP(제출 자격) 을 생성합니다.
5. 사용자는 생성된 VP(제출 자격) 을 개인키로 서명하여 기업에게 전송합니다. 
6. 기업은 VP 에서 DID 를 추출하고 해당 DID 를 바탕으로 블록체인에 공개키를 요청한 뒤 해당 공개키로 VP 를 검증합니다.


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

  

### 🖇 `Server`

  

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
