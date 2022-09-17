# NoobLoL_DBDocs

## 왜 작업을 진행하였는지?

> [진행한 프로젝트 저장소](https://github.com/f-lab-edu/NoobLoL`) 해당 프로젝트의 DB ERD설계를 진행하고 문서화를 해보고 싶었으나, 굳이 오랜시간 들여가면서 문서화를 하기는 귀찮고, 간단한 관리를 하고 싶은게 주 목적이었고 선택한게 DBDocs이다.<br><br>
> 이후 문서화를 진행한 해당 프로젝트를 자동화 관리할 수 있는 방법을 늦게 알게 되었고, 문서화의 중요성을 많이 체감했던 편이라 자동화까지 진행을 해보게 되었다.

<br><br>

## 작동 로직

1. Main브랜치로 Commit
2. Git Action에서 우분투와 Node의 설치
3. DBDocs를 실행하여 기존의 프로젝트를 변경된 noob.dbml로 정보를 변경
   <br><br><br>

## DBDocs를 통한 문서화 자동 배포 방법

1. [자동 배포에 대한 방법 포스팅](https://devjong12.tistory.com/69)
   <br>
2. [DBDcos의 배포 튜토리얼](https://dbdocs.io/docs/ci-integration)
