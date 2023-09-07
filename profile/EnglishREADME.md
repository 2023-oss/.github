[Korean Document](https://github.com/2023-oss/.github/blob/main/profile/README.md)
# :lock: DID-based facility use agreement generation and verification system
There is a risk of personal information leakage when writing a consent form for facility use or consent form for personal information in an offline environment. 
<br/>
The consent form for the use of facilities written in paper is inconvenient for business operators to manage, and it is cumbersome for users to fill out and submit it in paper.

**Our custom sign service** utilizes its own open-source public blockchain "Plate Chain" and it is a 'DID' based personal information submission system that utilizes 'SSI(Self-Signature Identifier)' which is managed by users with sovereignty over personal information.

There are many Blockchain DID services currently in service, but if DID previously dealt with historical evidence and document reliability, our open source provides additional advantages by devising more automatic document destruction systems for privacy.

In addition, it is an open source project using a public blockchain network developed directly without relying on other public blockchains (ex. Ethereum, Bitcoin), etc., so it can be applied lightly when there is a new idea or technology to be applied to DID.
## Services
<p align="center">
<a href="https://coral-piranha-fd5.notion.site/CustomSign-2521b412b83144498284b498f67f8a9d"><img  src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" width=160></a>
<a href="https://www.youtube.com/watch?si=hySRRINMpvC4hQV1&v=x4O0WdMcpEY&feature=youtu.be"><img  src="https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=Youtube&logoColor=white" width=175></a>
<a href="http://www.customsign.shop"><img  src="https://user-images.githubusercontent.com/83829352/266290884-d336e405-8138-4c94-b0bc-8b87b79a0b1e.png" width=150></a>
</p>

<p align="center">
<b>DemoID : theclimb01 / DemoPW : theclimb01!</b>
</p>

### 📱 User Application
[Repository (GitHub)](https://github.com/2023-oss/OSS-APP)

The Plate Wallet App provides users with the ability to keep personal information and submit it to the company if necessary.
<p>
<img src="https://user-images.githubusercontent.com/22852287/265966811-21446caf-4c1e-4e1a-b366-91f08a0a686d.png">
</p>

### 🖥️ Institution page
[Repository (GitHub)](https://github.com/2023-oss/OSS-WEB)

<p  align="center">

<b>DemoID : theclimb01 / DemoPW : theclimb01!</b>

</p>


It is a web service for companies or businesses that manage personal information agreements or institutional use agreements offline. The Drag and Drop method makes it easy to produce consent forms and digitally manage consent forms submitted by users.


<p>
<img src="https://github.com/2023-oss/OSS-WEB/assets/102888719/6a0ad2c5-1476-43f1-9a90-a124aab8376a">
</p>
<p>
<img src="https://github.com/2023-oss/OSS-WEB/assets/102888719/ad414a3e-ce1f-4f4e-a886-cf741eeaa27b">
</p>

### 🕸️ BlockChain

It is a PoW-based public blockchain with DID function and cryptocurrency transfer function.

-  You can see all blockchain transactions and blocks in [BlockChain Viewer](http://block.platechain.shop/).
- [BlockChain Wallet](http://block.platechain.shop/) It is a blockchain wallet demo in PTC unit that is listed but allows you to check the remittance function and wallet function.
![](https://user-images.githubusercontent.com/22852287/266316405-1a42dbd8-b4fa-452e-9488-5a82d89a47b3.png)
  
### :mag: Institution Server

We keep the consent form, verify it through VP and Public Key, and are in charge of automatic destruction based on the information on the blockchain.

[Repository (GitHub)](https://github.com/2023-oss/OSS-BACKEND)

### ⚡ Verification Server

creating and issuing VCs.

[Repository (GitHub)](https://github.com/2023-oss/OSS-ISSUER)


## Architecture
<br/>

![](https://user-images.githubusercontent.com/22852287/265968000-09658fac-4e28-4456-81d3-d64959ce978c.png)

## Project FlowChart
### What's DID?
Decentralized Identification (DID) is a next-generation authentication method that grants individuals the sovereignty of data and enables successful authentication without going through a centralized third party. Not a particular agency has identity information, but identity is distributed across all blocks in the blockchain.<br/>
Through DID, personal information is owned by individuals and minimal information can be used when necessary, so identity sovereignty can be restored.
![](https://user-images.githubusercontent.com/83829352/266076494-7cd11b21-a114-434e-89b6-7890774c0506.png)

### OverAll FlowChart
![](https://user-images.githubusercontent.com/83829352/266094215-16944ccc-321e-4531-974f-0148fe998f71.png)

1.The user (Holder) and the issuer (Issuer) each generate a public key pair and send it to the blockchain network.

2.The Holder receives a signed user qualification (VC) from a validated issuer.

3. Qualifications issued by trusted organizations

## ⚙️ Open Source Usage Information
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

## 👪 Team
- 김채원 (chae401@naver.com), Github Id: chae401 (Server, Web)

- 강은솔 (eunsol2953@gmail.com), Github Id: eunsolkang (Blockchain, App)

- 이창규 (darkdon66@naver.com), Github Id: mangoggul (Web)

- 김수민 (haon0319@naver.com), Github Id: eunsolkang (Design)

## ⚖️ Copyright and License
* [GNU]([https://github.com/osamhack2022/CLOUD_APP_IOT_KeepYourEndeavor_Moment/blob/main/LICENSE](https://github.com/2023-oss/.github/blob/main/LICENSE))

This project is licensed under the terms of the GNU license.

