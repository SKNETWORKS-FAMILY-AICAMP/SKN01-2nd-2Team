# SKN01-2nd-2Team

Vue + Django + FastAPI 기반 이모티콘 구매 사이트 가입 고객 이탈 예측 및 구매 동향 예측

SK-NETWORK-FAMILY-AI 1기 2차 프로젝트

- 구매 동향 분석
- 가설 - 나이와 성별에 따라 선호 카테고리에 영향을 미칠까?
- 가설 확인 -> lgbm 모델을 사용하여 분류 모델을 사용
   


## WBS를 Agile Board(애자일 보드) 로 변경

```c
실제로 우리는 수업 초반부터 프로세스를 학습하여
과정 전반에 걸쳐 애자일 프로세스를 사용하며 Backlog를 작성하고 있습니다.
그러므로 폭포수 방식의 WBS 보다는 저희가 사용하는 애자일 프로세스에 맞게
애자일 보드의 Status View와 Domain View를 위주로 업로드하기로 하였습니다.
```

# 1. 팀 소개
- ### 나는 춘식이
<div align="center">
<img width="300" alt="image" src="https://github.com/younghyen7956/study/blob/5f6982971526d9245d3fa41ffc43a56e1c7337cf/image/%EC%B6%98%EC%8B%9D.jpg">
</div>

| 김용현 | 송준호 | 이용우 | 이용휘 | 최민지|
|:----------:|:----------:|:----------:|:----------:|:----------:|
| <img width="120px" src="https://github.com/Jh-jaehyuk/Jh-jaehyuk.github.io/assets/126551524/33ea2a85-1853-484b-b2a4-c750f854a26b" /> | <img width="120px" src="https://github.com/user-attachments/assets/628ab454-d1b8-41d3-88fc-a013ade00cb7" /> | <img width="120px" src="https://github.com/younghyen7956/study/assets/155882166/68939030-b840-4e41-8970-afe6cdbce4d5" /> |  <img width="120px" src="https://github.com/younghyen7956/study/assets/155882166/cd405d10-d646-4ba8-bda8-051f24d1bf30" /> | <img width="120px" src="https://github.com/younghyen7956/study/assets/155882166/b04d5f5d-e9fe-4941-a39e-83f19c8bd394" /> |
| [@younghyen7956](https://github.com/younghyen7956) | [@6-6ho](https://github.com/6-6ho) | [@lyw00](https://github.com/lyw00) | [@y0ng98](https://github.com/y0ng98) | [@Minn-ji](https://github.com/Minn-ji) |
| Backend & Frontend & FastAPI | Backend & Frontend | Frontend | Frontend & Backend | Backend & Frontend & FastAPI |

2. 프로젝트

## 소개
나는 춘식이는 사용자들이 다양한 이모티콘을 구매하고, 리뷰를 작성하며, 자신만의 게시글을 작성할 수 있는 플랫폼입니다. 이 프로젝트는 사용자들이 감정을 나타내는 다양한 이모티콘을 편리하게 찾고 구매할 수 있도록 돕습니다.

## 배경
현대 사회에서는 디지털 커뮤니케이션이 더욱 중요해지고 있습니다. 특히 이모티콘은 텍스트를 넘어서 감정과 의도를 보다 명확하게 전달하는 역할을 합니다. 하지만 다양한 이모티콘을 찾기 위해서는 여러 플랫폼을 돌아다니거나 시간을 소모해야 하는 문제가 있습니다. 이에 따라 춘식이모티콘은 사용자들이 편리하게 원하는 이모티콘을 찾고 구매할 수 있는 공간을 제공합니다.

## 목표
- **다양한 이모티콘 제공**: 사용자들이 다양한 감정과 상황에 맞는 이모티콘을 찾을 수 있도록 다양한 제품을 제공합니다.
- **사용자 리뷰와 게시글 플랫폼**: 사용자들이 구매한 이모티콘에 대한 리뷰를 작성하고, 자신만의 게시글을 작성할 수 있는 공간을 제공하여 커뮤니티를 활성화합니다.
- **편리한 구매 경험**: 사용자들이 쉽고 빠르게 원하는 이모티콘을 검색하고 구매할 수 있도록 직관적이고 효율적인 사용자 경험을 제공합니다.
- **정보 보안**: 사용자 정보와 결제 정보를 안전하게 관리하여 신뢰성 있는 서비스를 제공합니다.

# 3. 기술 스택
### Machine Learing
![TensorFlow](https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Backend
![PyCharm](https://img.shields.io/badge/pycharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white)

### Frontend
![Vue.js](https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Vuetify](https://img.shields.io/badge/vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/visual%20studio%20code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![axios](https://img.shields.io/badge/axios-5A5A5A?style=for-the-badge&logo=axios&logoColor=white)
![Graphviz](https://img.shields.io/badge/graphviz-2E8B57?style=for-the-badge&logo=graphviz&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


### Database
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-red?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Communication

![Discord](https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Notion](https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

## Code Processing
![GitHub](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)


## 4. 분석
### [구매 동향 분석]
**01. 가설**
- 나이와 성별에 따라 선호 카테고리에 영향을 미칠까?

**2. 검정**
* 서비스 연결이 진행되지 않아 구매 데이터를 직접 생성하였기 때문에 의미있는 데이터 분석은 아니지만, 이후 서비스를 구현하고 실제 데이터가 있을 때의 분석 기법을 구현했습니다.

- 데이터 분포
<div>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/a7f1927f-8e7f-455d-9f6c-125c409cff80">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/0a9de183-86c2-4221-ada7-04e166824f12">
</div>

- 분석 그래프
  
<div>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/eaa939b3-f38c-4bdb-8ed3-413930a93574">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/56799dec-f85d-4ab2-9035-974f85cf1bf9">
</div>

* 모델의 성능 또한 실제 데이터가 아니므로 낮은 성능을 보였습니다. 실제 서비스 연결이 완료되면 의미있는 데이터 학습이 가능하므로, 보다 좋은 성능의 모델을 사용할 수 있을 것으로 예상합니다.
- confusion_matrix 
<div>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/282df594-23af-48cd-b536-7f8141fff798">
</div>

- classification_report
  
<div>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/533c7aa5-316c-4bec-a6f5-fcc79b2f10e6">
</div>


# 5. Agile Board (애자일 보드)
# **Frontend**
[Frontend](https://www.notion.so/eddi-robot-academy/DoC-Vue-DoCV-878338995f3344f3957e019c80285465)  
# **Backend**
[Backend](https://www.notion.so/eddi-robot-academy/DoC-Django-DoCD-8b672def70aa4dd6a56a2cd33a7042f2)  
# **FastAPI**
[FastAPI](https://www.notion.so/eddi-robot-academy/DoC-FastAPI-DoCF-d7089397825a45f5a6f2917e2610a9df)

# 5. Commit History (커밋 이력)
# **Frontend**
[Frontend](https://github.com/EDDI-RobotAcademy/DoC-Vue-Frontend/pulls?q=is%3Apr+is%3Aclosed)
# **Backend**
[Backend](https://github.com/EDDI-RobotAcademy/DoC-Django-Backend/pulls?q=is%3Apr+is%3Aclosed)
# **FastAPI**
[FastAPI](https://github.com/EDDI-RobotAcademy/DoC-FastAPI-AI/pulls?q=is%3Apr+is%3Aclosed)

# 6. 발생한 이슈 내역  
# **Issue**

[Issue](https://www.notion.so/eddi-robot-academy/d116cc9b8198453c80649d391c6e3642)

## 우선 순위를 5 단계로 나눠서 관리  


- 긴급하고 중요한 문제 (Do it now):

이 문제들은 즉시 대응해야 하며, 해결해야 하는 것입니다. 예를 들어, 심각한 시스템 다운이나 긴급한 보안 문제 등이 여기에 해당할 수 있습니다.

- 중요하지만 미룰 수 있는 문제 (Schedule it):

이 문제들은 중요하지만 즉각적인 대응이 필요하지 않은 경우입니다. 예를 들어, 비상 상황이 아니더라도 긴박한 프로젝트 기한이나 장기적인 시스템 개선 등이 포함될 수 있습니다.
-긴급하지만 중요하지 않은 문제 (Delegate it):

이 문제들은 당장 해결해야 하지만, 본인이 직접 해결하지 않아도 되는 경우입니다. 다른 사람에게 위임할 수 있는 문제들이 이에 해당할 수 있습니다.
- 긴급하지도 중요하지도 않은 문제 (Don't do it):

이 문제들은 현재 시점에서 처리하지 않아도 되는 경우입니다. 자원을 소모하지 않고 무시할 수 있는 문제들이 여기에 해당할 수 있습니다.
- 중요하지도 긴급하지도 않은 문제 (Postpone it):

이 문제들은 중요하지만 현재 시점에서 처리할 필요가 없는 경우입니다. 나중에 시간이 생길 때나 적절한 시점에 해결할 수 있는 문제들이 여기에 해당할 수 있습니다.


# 7. ERD
<div align="center">
<img width="1200" alt="image" src="https://github.com/younghyen7956/study/blob/fddc1fd0786afb6191af994ee3b332b3484b12cc/image/proj_erd.svg">
</div>

# 8. 주요 Domain 요소들
- **Board**
- **Cart**
- **Product**
- **Review**
- **Home**
- **Analysis**
- **Notification**
- **Order**
- **Report**
- **Account**
- **Navigation Bar**
- **Authentication**

# 9. 수행결과(테스트/시연 페이지)
<div align="center">
<img width="1200" alt="image" src="https://github.com/younghyen7956/study/assets/155882166/6d057837-fe0f-42a7-8132-e369c3b0b68f">
</div>

# 10. 한 줄 회고
-용현 : 이번 프로젝트 팀장을 맡아서 해보니 부담감이 많았지만 팀원 분들이 잘 따라주고 잘해주셨다. 팀원 분들 감사합니다.  
-용우 : 팀플을 진행하면서 에러나 쨔슈때문에 어려움이 많았는데 팀원분들이 잘 도와주셔서 잘 마친거 같습니다  
-용휘 : 장고와 뷰를 처음 접했는데 이번 프로젝트를 통해서 많이 배웠고, 팀원분들 모두 열심히 해주셔서 잘 마무리할 수 있었습니다.  
-민지 : 한 달이라는 짧은 기간동안 진행된 프로젝트인 만큼 세밀하고 구체적으로 구현하지 못한 점이 아쉬웠습니다. 앞으로 진행하게 될 프로젝트에 도움이 될 것이라는 점에서 의의가 있으며 좋은 경험이었다고 생각합니다.    
