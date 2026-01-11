# BaPick - 운세 기반 맛집 추천 AI 채팅 플랫폼 🍀

> '오늘 뭐 먹지?' 매일 반복되는 고민, 이제 운세로 **재미있게, 나에게 딱 맞게** 해결하세요.  
> 운세와 취향을 바탕으로 메뉴부터 식당까지 Pick해드려요!

<div align="center">
  <p align="center">
    <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2Fbd8231e1-f082-4120-ad5e-9c000885516a%2FIMG_7304.png/size/w=2000?exp=1768219337&sig=WhdTTlRB2VoxBbVw83S4szsJl3tUfxQ43tq4Rs3dRfo&id=2d25de76-f7fd-8038-a0ea-f1830dde219b&table=block" width="100%" />
  </p>
  
  **[🚀 서비스 바로가기](https://bapick.kr)** | **[📖 API 문서](https://bapick.duckdns.org/docs)** 
  
</div>

<br>

## 주요 기능
### 🔮 운세 기반 메뉴 추천
생년월일시를 기반으로 오행을 계산하고 오늘의 기운을 더해, 매일매일 달라지는 운세를 확인할 수 있습니다.
부족한 기운은 채우고, 과한 기운은 눌러주는 음식까지 함께 확인할 수 있습니다. 
<div>
  <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2F628f764f-772e-4c45-8f15-fc7b0ddb84e0%2FIMG_7321-modified.png/size/w=580?exp=1768218014&sig=3zkopsHFOTOec5z-ksVGLq27cvxYkUDMCwWEXRWvQRU&id=2d25de76-f7fd-8028-bb53-e37477cb92a8&table=block" width="300"> 
</div>
<br>

### 💬 AI 채팅으로 메뉴 선택
AI 챗봇을 통해 오행에 맞춰 구체적인 메뉴를 추천받을 수 있습니다.
<div>
  <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2F62cb4b76-20ee-46c7-9951-4b79c16d16ab%2FIMG_7322-modified.png/size/w=580?exp=1768218269&sig=OACYzj02F1eZYGvssUFvDV8k8Wdx_l_NPri_VbQVBJQ&id=2d25de76-f7fd-8070-9ab8-ca02733a062d&table=block" width="300"> 
</div>
<br>

### 📍 위치 기반 식당 추천
메뉴를 결정한 이후 해당 메뉴를 판매하는 식당까지 바로 확인할 수 있습니다.
- 현재 위치 근처 추천이 기본, 원하면 사용자가 설정한 다른 위치도 가능
- RAG 기반 LLM을 사용해 정확한 식당 정보 제공
  
<div>
  <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2F2d29d68f-ac55-461f-8736-e0be9137fbb5%2FIMG_7323-modified.png/size/w=580?exp=1768218417&sig=CzwXtxawMbeeKcQYitmGxHiYG00vySAjRHp0dyx7X0Q&id=2d25de76-f7fd-8078-ab05-e2ac79a37256&table=block" width="300"> 
</div>
<br>

### ⭐ 식당 정보 확인 & 스크랩
마음에 드는 식당 정보를 바로 확인하고, 스크랩 기능을 통해 나중에 다시 찾아볼 수 있습니다.
<div>
  <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2Fb08aa3a6-08db-45a4-9818-873478f25f4b%2FIMG_7325-modified.png/size/w=580?exp=1768218506&sig=uIsmbL3vSNslkl0Zy2jdjzaZkYYo8aMRCTbOCabGM_E&id=2d25de76-f7fd-8075-b066-f85325975e7e&table=block" width="300"> 
</div>
<br>

### 👥 단체 채팅
친구나 동료들과 함께 채팅하며 메뉴와 식당을 한 번에 해결할 수 있습니다.
<div>
  <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Fbdb5de76-f7fd-8180-b313-0003d1a4bea2%2F2585d36f-ae2f-4e13-a6e4-9fe6e86128d1%2FIMG_7324-modified.png/size/w=480?exp=1768218672&sig=YW3RNCQpKyGevwgIu5vQfKD3lGGsPC6T9Eyxuj72L-0&id=2d25de76-f7fd-80d1-abb4-c3058a50b246&table=block" width="300">
</div>
<br>

## 시스템 아키텍처
  <p align="center">
    <img src="./architecture.png" width="100%" />
  </p>
<br>

## 기술 스택
### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜⛓️_LangChain-121212?style=flat-square)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)

### AI/ML
![Gemma](https://img.shields.io/badge/Gemma-4285F4?style=flat-square&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=flat-square&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)

### Data Collection
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Database & Cache
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

<br />

## 팀원 소개
|이름|역할|
|:---|:---|
|권현진|FrontEnd|
|김재희|BackEnd|
|마디나보누|FrontEnd|
|방예진|BackEnd|
|유서현|BackEnd, Infra|
