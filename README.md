# codesquad-java-backend-projects

> [코드 스쿼드 마스터즈 코스 자바 백엔드](https://codesquad.kr/page/masters/be.html) 과정을 진행하면서 수행했던 내용을 정리하고 있습니다.



## Java 

### 몬스터 레이스

#### 개요

- Java를 활용한 몬스터 레이스 게임 구현



#### 사용기술

- Java



#### 학습하고, 고민한 점

- 객체가 어떤 메서드를 가지고 있어야 할 지, 즉 어떤 역할을 맡아야 하고, 어디에 메세지를 보내야할 지 고민할 수 있었습니다.

- 재귀적인 메서드 구현을 시도해봤습니다.

- `Optional` 을 알게 되었고, `Null` 에 대해 어떻게 다뤄야할지 생각하게 되었습니다.

- 가장 핵심적인 사항은 **가독성 좋은 코드** 의 중요성을 알게 되었습니다.

  - 충분한 생각, 설계없이 작성한 코드는 프로그램의 전반적인 흐름을 파악하는 데 힘들어지고 나아가 유지보수 및 기능 추가에 큰 악영향을 미친다는 것을 알 수 있었습니다.

  - 자신 뿐만 아니라, 상대방을 위해 읽기 쉽고 간결한 코드가 필요함을 알게 되었습니다.
  - `Spring` 같은 프레임워크의 사용 필요성을 느끼게 되었습니다.



#### 참고

- [github_link](https://github.com/102092/java-monster-race/tree/102092)
- [PR_link](https://github.com/code-squad/java-monster-race/pulls?q=is:pr+is:closed+author:102092)



### QnA 게시판

#### 개요

- CRUD 기능을 가지고 있는 간단한 게시판 구현



#### 사용기술

- Java, SpringBoot, Spring Data JPA, Heroku, H2, Swagger, Gradle



#### 학습하고, 고민한점

- Spring Data JPA 의 간편함과 무서움을 느끼게 되었습니다.
  - Annotation을 통해, Entity Mapping등 정말 간결하게 객체 생성 및 기능을 구현할 수 있었습니다.
  - 그렇지만 내부적으로 작동 방식을 잘 몰랐기 때문에, 오류 발생 시 해결하는 데 어려웠습니다.
  - 사용하는 기술에 대한 이해가 필요함을 느겼습니다.
- 네트워크 전반적인 부분에 대해 학습했습니다.
  - DNS의 역할, HTTP 프로토콜, HTTP Status Code, Session과 Cookie
- ORM, JPA, Hibernate 관계에 대해 학습했습니다.
- API 문서의 필요성과 Swagger로 어떻게 하면 구현할 수 있는지 고민하고, 시도해봤습니다.



#### 참고

- [github_link](https://github.com/102092/java-qna)

- [PR_link](https://github.com/code-squad/java-qna/pulls?q=is:pr+is:closed+author:102092)




### 웹서버 구현

#### 개요

- **페어프로그래밍**을 통해  간단한 `Web Server` 구현



#### 사용기술

- Java



#### 학습하고, 고민한점

- 어떤 방식의 페어 프로그래밍과 태도가 저와 동료에게 도움이 될 지 고민해보는 계기가 되었습니다.
  - 프로젝트 진행 방식은, [github issue 작성](https://github.com/beginin15/java-was/issues)을 통해 각 단계별로 해야될 일들에 대해 세분화하였고, 추후 학습해야할 부분은 댓글로 기록하였습니다.
  - 내가 생각한 것과, 상대방의 생각한 것의 간격을 줄이기 위해서 적극적인 의사소통을 시도했습니다.
  - 항상 다른 가능성을 열어두는 열린 자세를 취하기 위해 노력했습니다.
- WebServer, Application Server 차이점에 대해 공부했습니다.
- `Session` 의 전반적인 작동 방식을 구현해봤습니다.
- 

#### 참고

- [github_link](https://github.com/beginin15/java-was)
- [PR_link](https://github.com/code-squad/java-was/pull/48)



---

## 마스터즈 프로젝트

> 작성되어있는 기획서를 기반으로, FE - BE - IOS 팀이 되어 프로젝트를 진행하였습니다.



### 회원 가입 (1 week)

- [기획서](https://docs.google.com/presentation/d/1xvs24VWVJc2KhmHUoj1Rm88zvtzItzQuD-6vBuzkvA0/edit#slide=id.p)
- [signup-11](https://github.com/codesquad-member-2020/signup-11)
- [PR_링크](https://github.com/codesquad-member-2020/signup-11/pull/45)
- 학습한 점
  - `Spring Boot`
  - `Spring Data Jdbc`
  - `handlebars`
  - `H2 database`
  - `github action`



### 미세먼지 서비스 (1 week)

- [웹기획서](https://docs.google.com/presentation/d/1Yl4nM2FReIhZASlBM73asWMcLe3366hglP8E_Dded1U/edit#slide=id.g7e682b64ec_0_23)

- [dust-11](https://github.com/codesquad-member-2020/dust-11)
- [PR_링크](https://github.com/codesquad-member-2020/dust-11/pulls?q=is%3Apr+is%3Aclosed+author%3A102092)
- 학습한 점
  - `Open-API` 사용 방법
  - `heroku` 배포
  - `AWS EC2` 
  - `Spring data jdbc`



### TODO 리스트 서비스 (2 weeks)

- [웹기획서](https://docs.google.com/presentation/d/13OX2mGk-wvwPyI06afMPITMPz9jGYLe4y2FIFBImeyA/edit?usp=sharing)
- [todo-8](https://github.com/codesquad-member-2020/todo-8)
- [PR_링크-1](https://github.com/codesquad-member-2020/todo-8/pull/63)
- [PR_링크-2](https://github.com/codesquad-member-2020/todo-8/pull/102)
- 학습한 점
  - `Spring Data JDBC` 관계설정
  - `Spring AOP`
  - `Dependency Injection`
  - `JWT` 인증방식
  - `Interceptor`
  - `mockup API` 필요성
  - 페어 프로그래밍, 어떻게 하면 같이 발전할 수 있는지에 대해
  - `shell script`
  - `Nginx` 사용방법, 필요성
  - `MySQL` Join



### 온라인 반찬 서비스 (2 weeks)

- [웹기획서](https://docs.google.com/presentation/d/1jcrUXkTHVNhh-aj_eM-yOhAkuRdaE3w2Vry2UUY42JU/edit#slide=id.p)
- [sidedish-08](https://github.com/codesquad-member-2020/sidedish-08)
- [PR_링크](https://github.com/codesquad-member-2020/sidedish-08/pull/76)
- 학습한 점
  - `Spring JDBC template`
  - `RESTful API`
  - `MySQL` Join, Index
  - ERD
  - `github OAuth` 
  - 자동 배포



### 온라인 야구 게임 (2 weeks)

- [웹기획서](https://docs.google.com/presentation/d/1KY4myrtBFlvr6eKvgl-CVv5Cbk1zQlo1GkTz4hNjXqE/edit?usp=sharing)
- [baseball-09](https://github.com/codesquad-member-2020/baseball-09)
- [PR_링크](https://github.com/codesquad-member-2020/baseball-09/pull/77)
- 학습한 점
  - `Builder Pattern`
  - 객체의 역할, 객체간 커뮤니케이션
  - 객체 설계의 중요성
  - 도메인 지식의 중요성
  - DDD
  - `AWS VPC, subnet`
  - `AWS RDS`



### 숙소 예약 서비스 (3 weeks)

- [웹기획서](https://docs.google.com/presentation/d/1jmpiOizAY_gvQN4ei5K1FDlDXLuTijZBFH6GFi28HD8/edit?usp=sharing)
- [airbnb-11](https://github.com/codesquad-member-2020/airbnb-11)
- [PR_링크-1](https://github.com/codesquad-member-2020/airbnb-11/pulls)
- [PR_링크-2](https://github.com/codesquad-member-2020/airbnb-11/pull/141)
- 학습한 점
  - `github action`을 통한 CI/CD
  - `MySQL` Index
  - `MySQL` 트랜잭션
  - `Spring Data Jdbc` ManyToMany 관계
  - `flyway` 기본 이용방법
  - `ErrorHandler`



### 이슈 관리 서비스 (3 weeks)

- [웹기획서](https://docs.google.com/presentation/d/1iA-tpumHl_TpR_yUwgYcnb_X8GbW6XvjZOTh2Ucvu0A/edit#slide=id.p)
- [issue-tracker-03](https://github.com/codesquad-member-2020/issue-tracker-03)
- [PR_링크](https://github.com/codesquad-member-2020/issue-tracker-03/pull/83)
- 학습한 점
  - `AWS S3`를 통한 이미지 업로드
  - `Spring Data JPA`
  - `CORS`
  - 객체 관계 맵핑
  - `mappedBy`
  - 할 일을 나누고, 같이 협업하기

