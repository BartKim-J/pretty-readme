<div id="header" align="center">
  <h1>Pretty Read.Me</h1>
  <a href="https://circleci.com/gh/EineBlume/chatie-server/tree/master">
    <img src="https://circleci.com/gh/BartKim-J/pretty-readme/tree/master.svg?style=shield" alt="circleci" />
    <img src="https://codecov.io/gh/BartKim-J/pretty-readme/branch/master/graph/badge.svg?token=lfCT6WAgUr" alt="codecov">
  </a>
  <div
    style="background-image: url(https://avatars.githubusercontent.com/u/36470472?v=4); 
        background-repeat : no-repeat;
        background-size : cover;
        width: 200px; 
        height: 200px;
        border-radius: 50%;
        box-shadow: 10px 10px rgba(0, 0, 255, .2);
        margin: 30px">
  </div>
  <div id="main">
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Python%203.7%20-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="python" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white" alt="docker" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=Kubernetes&logoColor=white" alt="kubernetes" /></a>
  </div>
  <div id="sub">
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Django%202.2-092E20?style=flat&logo=Django&logoColor=white" alt="django" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=Mysql&logoColor=white" alt="mysql" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=flat&logo=Amazon%20DynamoDB&logoColor=white" alt="amazon-dynamodb" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white" alt="redis" /></a>
  </div>
</div>
g

## Getting Started

아래는 `XX 프로젝트` 를 실행하기 위한 가이드 입니다.

### Prerequisites

---
아래 사항들이 설치 및 선행 되어 있어야 합니다.
* #### [Docker Desktop](https://www.docker.com/products/docker-desktop) (example)
    * Mac 설치
        ```
        $ (설치 명령어)
        ```
### Installing

---
아래는 프로젝트를 설치하는 방법입니다.
1. #### 레포지토리 설치 (example)
    ```
    $ git clone https://github.com/BartKim-J/pretty-readme.git 
    $ cd pretty-readme
    ```
2. #### 환경 설치
    ```
    $ (환경설치 명령어)
    ```

## Testing
하단의 스크립트를 실행하면 테스트 코드가 작동합니다.
```
$ (테스트 실행 구문)
```
아래와 같이 테스트가 진행됩니다.
```
(테스트 중)
```
```
(테스트 결과)
```

## Running
아래는 프로젝트를 실질적으로 실행하는 방법에 대해 설명합니다.

> Running Admin URL(http://127.0.0.1:8000) 
> 
> 

* ### [Django](https://docs.djangoproject.com/ko/2.1/intro/tutorial01/#the-development-server) (example)
    ```
    $ python manage.py runserver
    ```
    ```
    (실행 결과)
    ```

* ### [Gunicorn](https://docs.gunicorn.org/en/stable/) (example)
    ```
    $ gunicorn service.main:app
    ```
    ```
    ...
    (실행 결과)
    ```

## Workflow
현재 Workflow 는 기본적으로 [Git Flow](https://techblog.woowahan.com/2553/) 를 사용하고 있습니다.
> * `master` : 제품으로 출시될 수 있는 브랜치
> * `develop` : 다음 출시 버전을 개발하는 브랜치
> * `feature` : 기능을 개발하는 브랜치
> * `release` : 이번 출시 버전을 준비하는 브랜치
> * `hotfix` : 출시 버전에서 발생한 버그를 수정 하는 브랜치
> * `fix` : 기존에 발생한 버그를 수정하는 브랜치
>
>
> <div align="center"> <img src="https://user-images.githubusercontent.com/36470472/128487175-e5d28ce3-b5b7-48f2-914d-4b9383277986.png" width="600" alt="git-flow" /></div>

## Directory Structure(example)
```
.
├── app
│        ├── crud
│        ├── database
│        ├── grpc
│        │       ├── protos
│        │       └── protos_python
│        ├── middleware
│        ├── models
│        ├── routers
│        │       ├── health
│        │       ├── items
│        │       ├── sentry
│        │       └── users
│        ├── schemas
│        └── test
│            └── api
├── docker
│        ├── postgresql
│        └── redis
├── nginx
└── script
         └── grpc


```
