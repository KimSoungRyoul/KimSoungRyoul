<h1 align="center">KimSoungRyoul</h1>

## 1. Work Experience

### 1-1. Naver Biz Corp | MLOps
`2022.06 ~ Present`

> *Currently employed*

---

### 1-2. Delivery Hero Korea (Yogiyo) | Web Backend
`2018.09 ~ 2022.05` **(3 years 5 months)**

<details>
<summary><b>View Details</b></summary>

#### Tech Blog Post
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white)](https://soungryoul-kim.medium.com/) 

[The Concept of Interface in Cheese Tonkatsu - Interface and OOP with Java](https://soungryoul-kim.medium.com/)

#### [Order Exp Squad] OrderDisplayo - New Micro Service Development
`2021.12 ~ 2022.01`
- Order Micro Service separation
- Order domain Query-purpose Micro Service design and development

#### [Order Exp Squad] Docker Base Multi Staging Environment Setup
`2021.12 ~ 2022.01` **(1 month)**
- **Problems Solved:**
  - New employees unable to test locally due to weak QA infrastructure
  - Lack of event-based feature testing environment
- **Work Done:**
  - Dockerfile creation for each Micro Service
  - Local development environment docker-compose setup
  - Staging environment docker-swarm/ECS planning
  - Production EKS migration preparation

#### [Order Exp Squad] Customer Domain Architecture Proposal
`2021.10 ~ 2021.11` **(1 month)**
- MSA architecture design review and proposal

#### [Order Exp Squad] Shopyo - New Micro Service Development
`2021.08 ~ 2021.11` **(3 months)**
- Service for distributing coordinate-based store list query traffic
- Data Batch Sync between legacy and new systems
- **Tech Stack:** FastAPI, PostgreSQL, Django

#### [Vendor Squad] VMS (Vendor Management Service) - New Micro Service Development
`2019.10 ~ 2021.07` **(1 year 9 months)**
- Vendor-related domain service MSA separation
  - Contract, Termination, Modification management
  - Store, Business owner management
  - Franchise management
  - Employee task management (mini Jira)
- Business owner/Contract/Store DB Schema design
- Slow Query tuning
- **Tech Stack:** Django, DRF, JWT, MySQL, AWS (SQS, SNS, Lambda), Docker

#### [Vendor Squad] Vendor Maintenance
`2019.06 ~ 2019.09` **(3 months)**
- Yogiyo Plus supplier data Sync Batch Job
- Store owner NPS (survey) daily batch job
- Store owner review reply feature
- Order history query tuning

#### [Platform Ops Squad] Maintenance Squad
`2019.01 ~ 2019.06` **(6 months)**
- Legacy system maintenance

</details>

---

## 2. Open Source Contributions

### Major Contributions

#### Django - `db_comment` Feature ([PR #14463](https://github.com/django/django/pull/14463))
> Added support for database comments on columns and tables in Django 4.2+

<details>
<summary><b>Code Example</b></summary>

```python
class MyModel(models.Model):
    name = models.CharField(max_length=100, db_comment="User's display name")
    
    class Meta:
        db_table_comment = "Stores user information"
```

</details>

<a href="https://github.com/django/django">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=django&repo=django&theme=tokyonight" />
</a>

#### drf-spectacular - OpenAPI/Swagger Enhancement
> Listed as Contributor in DRF Official Documentation ([Third Party Packages](https://www.django-rest-framework.org/topics/documenting-your-api/#third-party-packages))

<details>
<summary><b>Contributions</b></summary>

- OpenAPI Examples support
- SwaggerUI Settings support
- QuerySerializer documentation

</details>

<a href="https://github.com/tfranzel/drf-spectacular">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=tfranzel&repo=drf-spectacular&theme=tokyonight" />
</a>

### Other Contributions

<details>
<summary><b>View All</b></summary>

| Project | Contributions | Link |
|---------|--------------|------|
| [bentoml/BentoML](https://github.com/bentoml/BentoML) | Docs fixes, Bug fixes, Client improvements | 6+ PRs |
| [bentoml/Yatai](https://github.com/bentoml/Yatai) | Korean localization | 1 PR |
| [bentoml/yatai-deployment](https://github.com/bentoml/yatai-deployment) | Minikube profile support | 1 PR |
| [kserve/models-web-app](https://github.com/kserve/models-web-app) | Bug fixes | 1 PR |
| [pytest-tipsi-django](https://github.com/micro-fan/pytest-tipsi-django) | Cache DB test fixture bug fix | 1 PR |

</details>

---

## 3. Publications & Talks

### Book

| Year | Title | Publisher | Link |
|------|-------|-----------|------|
| 2023 | **백엔드 개발을 위한 핸즈온 장고** (Hands-On Django for Backend Development) | Hanbit Media | [![Kyobo](https://img.shields.io/badge/Kyobo-1A3D7C?style=flat-square&labelColor=7CB342)](https://product.kyobobook.co.kr/detail/S000202404727) |

### Conference Talks

| Year | Conference | Topic | Link |
|------|------------|-------|------|
| 2024 | **Naver DAN24** | CPU Inference Optimization | [![NAVER](https://img.shields.io/badge/NAVER-03C75A?style=flat-square&logo=naver&logoColor=white)](https://naver.me/5cqQlzHo) |
| 2023 | **PyCon Korea** | Model Serving Architecture with BentoML | [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/2AjVDjR0jLM?si=QAH9K76JLUzRDTL5) |
| 2020 | **PyCon Korea** | Django ORM (QuerySet) Structure, Principles and Optimization Strategies | [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=EZgLfDrUlrk) |

<details>
<summary><b>Internal Tech Sessions (Yogiyo)</b></summary>

| Year | Topic | Pages |
|------|-------|-------|
| 2021 | **Persistence Layer in Python Application** | 66 pages |
| 2021 | **DDD with Python** | 50 pages |

</details>



---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KimSoungRyoul&layout=compact&theme=tokyonight&hide=css,html,javascript" alt="Top Languages" />
</p>

---
