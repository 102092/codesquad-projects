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
- `Session` 의 전반적인 작동 방식을 학습하고, 구현해봤습니다.



#### 참고

- [github_link](https://github.com/beginin15/java-was)
- [PR_link](https://github.com/code-squad/java-was/pull/48)



---

## 마스터즈 프로젝트

> 작성되어있는 기획서를 기반으로, FE - BE - IOS 팀이 되어 프로젝트를 진행하였습니다.



### 회원 가입

#### 개요

- 4인 (FE 2명, IOS 1명, BE 1명), 1주간 진행한 프로젝트

- 기본적인 회원가입 기능을 가진 웹 사이트 구현이 목표



#### 사용 기술

- Java, Spring Boot, Spring Data JDBC, H2, Heroku



#### 학습하고, 고민한 점

- [스프레드 시트](https://docs.google.com/spreadsheets/d/1TbW89rU3hsL2aIAoNEiQA1i6cu5iaMkXKbpbfciA15E/edit#gid=0) 를 통해서, 기능에 대해 서로 같은 이해를 하고 있는 지 확인하고자 하였습니다.
- Spring Data JDBC가 제공하는 CRUD 기능을 학습하고, 사용하였습니다.
- 기초적인 웹 구현에 필요한 SQL 구문을 학습하였습니다.
- `Swagger` 를 통해 API 문서를 제공하여, 클라이언트와 원활한 소통이 가능하도록 노력하였습니다.
- 테스트에 사용되는 `Junit5` 에 대해 학습하였습니다.



#### 아쉬웠던 점

- 회원 가입 시, 필요한 Validation에 대해 많이 적용하지 못한 부분이 아쉬웠습니다.
- 프론트 자원까지 배포해야 했지만, Webpack에 대해 이해가 부족하여 하지 못하였습니다.



#### 참고

- [기획서](https://docs.google.com/presentation/d/1xvs24VWVJc2KhmHUoj1Rm88zvtzItzQuD-6vBuzkvA0/edit#slide=id.p)
- [signup-11](https://github.com/codesquad-member-2020/signup-11)
- [PR_링크](https://github.com/codesquad-member-2020/signup-11/pull/45)



### 미세먼지 서비스

#### 개요

- 4인 (FE 2명, IOS 1명, BE 1명), 1주간 진행한 프로젝트
- OPEN API 와 통신을 통해, 미세먼지 현황을 제공하는 기능 구현이 목표



#### 사용 기술

- Java, SpringBoot, Spring Data JDBC, H2, AWS EC2, Apache



#### 학습하고, 고민한 점

- **OPEN API**와 통신하기 위해, 해당 API(Kakao, 공공 데이터) 제공하는 문서를 학습하고 이용하였습니다.
- `RestTemplate` 에 대해 학습하고 이용하였습니다. 
  - 이 과정에서, `Json` 에 대해 자세하게 다뤄볼 수 있는 기회를 얻었습니다.
- Elastic IP를 할당하여 ubuntu를 기반한 AWS EC2를 생성하였습니다.
  - 또한 git clone 명령어를 통해, 저장소를 클론하였고 `gradle` 을 이용하여 jar 파일로 빌드하였습니다.
  - `nohup` 이용하여, 백그라운드에서 jar 파일을 실행시켰습니다.
- Apache Web Server를 이용해, 프론트를 배포하였습니다.
- `REST API` 는 무엇인지 고민하고, 학습하였습니다.



#### 아쉬웠던 점

- 프론트를 맡은 팀원들이 중간에 하차하는 일이 있었습니다. 짦은 시간 임팩트 있게 진행되는 프로젝트인 만큼 체력적인 한계를 느끼신 듯 했습니다.
  - 프로젝트는 같이 하는 만큼, 혼자만이 아닌 다른 사람들도 충분히 살피고 생각해야된다고 느끼게 되었습니다.
- 기능 구현에 급급하다 보니, 코드 품질에는 신경 쓰지 못했습니다.



#### 참고

- [웹기획서](https://docs.google.com/presentation/d/1Yl4nM2FReIhZASlBM73asWMcLe3366hglP8E_Dded1U/edit#slide=id.g7e682b64ec_0_23)

- [dust-11](https://github.com/codesquad-member-2020/dust-11)
- [PR_링크](https://github.com/codesquad-member-2020/dust-11/pull/45)



### TODO 리스트 서비스

#### 개요 

- 4인 (FE 1명, IOS 1명, BE 2명), 2주간 진행
- CRUD 기능을 가진 TODO APP을 구현하는 프로젝트



#### 사용기술

- Java, SpringBoot, Spring Data JDBC, MySQL, JWT, AWS EC2, Nginx

#### 

#### 학습하고, 고민한 점

- 백엔드 2명으로 진행한 만큼 , [위키](https://github.com/codesquad-member-2020/todo-8/wiki) 작성을 통해,  같이 성장하고 학습하는 프로젝트를 진행하고 싶었습니다.
  - 개발하면서, 학습하거나 혹은 느꼈던 부분들에 대해 위키에서 **BE Topic**  목록 아래 정리하였습니다.
  - 예시 : [JWT에 대해서]([https://github.com/codesquad-member-2020/todo-8/wiki/JWT-%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C](https://github.com/codesquad-member-2020/todo-8/wiki/JWT-에-대해서))
  - 함께 성장하는 재미와 즐거움을 알게 되었습니다.
- Spring Data JDBC 대해 학습하였습니다.
  - 객체 맵핑(1 대 다, 1 대 1등..)에 대해 학습하고 사용하였습니다.
  - DDD(Domain-Driven-Design) 에 대해 약간의 개념을 잡았습니다.
  - Aggregation Root를 왜 중요하게 생각하는 알게되었습니다.
  - 너무 객체지향적이지도, 너무 SQL 지향적이지도 않은 Spring Data JDBC가 제공하는 철학과 기술에 대해 배우는 데 즐거움을 느꼈습니다.
- PostMan을 통해 MockAPI를 제공하였습니다.
  - Mock API 작성을 통해, 어떠한 API를 추후 개발해야할 지 생각하게 되었고 팀원들과 필요 기능에 대해 좀 더 소통할 수 있는 시간이 되었습니다.
- CORS Error에 대해 경험하고, 학습하였습니다.
- JWT의 토큰 방식 인증에 대해 학습하고, 프로젝트에 적용해봤습니다.
  - Spring Interceptor 학습을 통해, 통신 흐름에 대해 조금 알게되었습니다.



#### 아쉬었던 점

- 다른 파트의 개발 진행 사항 때문에, JWT 토근 방식 인증을 적용해보진 못했습니다.
  - 인증 기능을 프로젝트 진행 기간 중, 언제 하면 좋을 지 생각해보는 계기가 되었습니다.
- 서로의 코드를 적극적으로 리뷰하지 못했습니다.
  - 처음인 만큼, 어디까지 리뷰해야 할 지 알지 못했습니다.
  - 단순히 기능 작동 여부, 혹은 변수명에 대한 리뷰에 그쳤습니다.

- 프로젝트에서 같은 구조를 답습하고 있다는 생각이 들었습니다.
  - MVC 패키지 구조로 프로젝트를 항상 구성하고 있다고 느겼습니다.
  - 어떤 구조가 좋은 구조인 지 생각하게 되었습니다.



#### 참고

- [웹기획서](https://docs.google.com/presentation/d/13OX2mGk-wvwPyI06afMPITMPz9jGYLe4y2FIFBImeyA/edit?usp=sharing)
- [todo-8](https://github.com/codesquad-member-2020/todo-8)
- [PR_링크-1](https://github.com/codesquad-member-2020/todo-8/pull/63)
- [PR_링크-2](https://github.com/codesquad-member-2020/todo-8/pull/102)



### 온라인 반찬 서비스

#### 개요

- 4인 (FE 1명, IOS 1명, BE 2명), 2주간 진행
- 배민찬 서비스를 클론하는 프로젝트



#### 사용 기술

- Java, SpringBoot, Spring Data JDBC, Spring JDBC Template, MySQL, OAuth2, JWT, AWS EC2, Nginx



#### 학습하고, 고민한 점

- script 파일 작성을 통해, EC2에서 자동 배포하는 방법을 학습하였습니다.
- Github OAuth가 어떤 방식으로 작동하는 지 학습하고, Spring Security를 사용하지 않고 구현하였습니다.
- SQL Join 에 해당하는 부분을 학습하고, DAO를 통해 기능을 구현하였습니다.
  - SQL 친화적인 애플리케이션은, 객체 설계와 DB 연결에서 조금 자유를 주는 것을 느꼈습니다.
  - 하지만 SQL에 대한 관리, mapper 를 어디에 둘 것인가 등등 코드 가독성과 유지 보수를 위해 좀 더 신경써야 겠다는 생각이 들었습니다.
- 백엔드는 페어로 진행되는 만큼, 월화목금 1시부터 4시까지, 코어 집중시간을 설정하였습니다.
  - 코어 집중 시간 전에 각자 맡은 기능들에 대해서 pull request를 보낸 후, 해당 시간에 왜 이렇게 작성하였는지 서로의 코드를 리뷰하는 시간을 가졌습니다.
  - 자신의 코드에 대해 이유를 설명하는 것이 생각보다 힘들다는 것을 깨달았습니다.
  - 어떻게 하면 자연스럽게 읽을 수 있는 코드를 구현할 수 있을까 생각하게 되었습니다.



#### 아쉬웠던 점

- 클래스 별로 많은 소통을 하지 못했던 점입니다.
  - 온라인 주로 진행한 만큼, 핵심적인 내용에 대해서만 이야기를 나눴던 점이 조금 아쉬웠습니다.
- 프로젝트 관리에 대해 신경쓰지 못했습니다.
  - 기능을 구현한 만큼 중요한 점이지만, 다소 신경쓰지 못했습니다.



#### 참고

- [웹기획서](https://docs.google.com/presentation/d/1jcrUXkTHVNhh-aj_eM-yOhAkuRdaE3w2Vry2UUY42JU/edit#slide=id.p)
- [sidedish-08](https://github.com/codesquad-member-2020/sidedish-08)
- [PR_링크](https://github.com/codesquad-member-2020/sidedish-08/pull/76)



### 온라인 야구 게임

#### 개요

- 4인 (FE 2명, IOS 1명, BE 1명), 2주간 진행
- 간단한 멀티 유저 기반, 온라인 야구 게임을 만드는 것이 목표



#### 사용 기술

- Java, SpringBoot, Spring JDBC Template. MySQL, AWS EC2/RDS, JWT, OAuth2, Nginx



#### 학습하고, 고민한 점

- AWS VPC, Routing Table, Subnet, Security Group

- 보안을 위해 AWS RDS는 Private Subet 로 설정하였습니다.
  - 또한 RDS Security 그룹을 수정하여, EC2에서만 RDS로 통신할 수 있도록 하였습니다.
- 편의를 위해 Repository에서 모든 SQL를 관리하도록 했습니다.
- SQL에서 `ON DUPLICATE KEY UPDATE ` 에 대해 학습하고 이용해봤습니다.
- `Builder Pattern` 이용하여, 객체 생성에 좀 더 편의성과 안정성을 추구했습니다.



#### 아쉬었던 점

- 구현을 다하지 못했습니다.

  - 야구에 대한 도메인 지식의 부족으로 인해 , 초반 객체 설계에서 오류가 발생하였습니다.
  - 이로 인하여, 중간에 프로젝트를 새로이 시작하게 되었습니다.
  - 충분히 도메인 지식에 대해 이해할 시간이 필요하다는 것을 알게 되었습니다.

  

#### 참고

- [웹기획서](https://docs.google.com/presentation/d/1KY4myrtBFlvr6eKvgl-CVv5Cbk1zQlo1GkTz4hNjXqE/edit?usp=sharing)
- [baseball-09](https://github.com/codesquad-member-2020/baseball-09)
- [PR_링크](https://github.com/codesquad-member-2020/baseball-09/pull/77)



### 숙소 예약 서비스 

#### 개요

- 3인 (FE 1명, BE 2명), 3주간 진행
- 기본적인 검색 기능을 가진 Airbnb를 클론하는 프로젝트



#### 사용 기술

- Java, SpringBoot, Spring Data JDBC, Spring JDBC Template, OAuth2, JWT, MySQL, AWS EC2/RDS/CodeDeploy,  Github CI/CD



#### 학습하고, 고민한 점

- Github Action 학습하고 이용하여 CI, CD 기능을 구현했습니다.
- flyway를 통해 Database를 관리했습니다.

  - Database의 버젼관리 시스템 같은 기능을 함을 배웠습니다.
- **돈** 이라는 도메인이, Database에서 어떻게 다뤄져야 할지 생각하게 되었습니다.

  - `BigMoney` 를 사용하여, Dollar DB에 저장하고, 
  - 일정한 환율을 통해 원화로 변환되도록 하였습니다.
- `Slicing Test` 를 학습하고 적용해봤습니다.

  - `@WebMvcTest` 를 통해 특정 Controller를 테스트 시도해봤습니다.
- 여러 번의 프로젝트를 진행한 만큼, 이전 프로젝트에서 상대방이 작성한 코드를 기반으로 재 구현하기도 하였습니다.

  - 이를 통해 파트너의 코드, 리뷰를 이해하고, 생각하는 시간을 가졌습니다
    - code indent, variable name등 어떻게 보면 작은 부분까지 생각할 수 있는 시간을 가졌습니다.
    - 학습을 넘어서, 실무적인 운영에서 코드를 바라볼 수 있는 기회를 갔게 되었습니다.
- 프로그래밍적으로 **옳은 것**이 있을 까에 대해 생각하게 되었습니다.
  - 프로그래밍의 패러다임을 주도하는 사람들의 의견(DDD, Spring Layer에 대한 생각)이 강력하게 지켜야할 사항인 것일까 에 대한 의문이 들었습니다.
  - 좀 더 열린 마음으로 코드와 인프라를 바라볼 필요를 느꼈습니다.




#### 아쉬웠던 점

- 팀원과 이 프로젝트를 바라보는 시선이 조금 달랐습니다.
  - 저는 이 프로젝트는 학습이 우선 구현은 조금 후순위 였지만, 팀원은 구현이 우선 순위에 있었습니다.
  - 그러다보니, 기능 구현이 늦어졌을 때 팀원이 전부 구현해오는 경우가 있었습니다.
  - 팀원과 의사소통이 다소 미흡했던 점이 아쉬었습니다.
- 테스트 코드 작성이 부족했습니다.
  - 테스트 코드 작성에 중점을 두고자 했지만, 시간 관계성 미룰 수 밖에 없었습니다.



#### 참고

- [웹기획서](https://docs.google.com/presentation/d/1jmpiOizAY_gvQN4ei5K1FDlDXLuTijZBFH6GFi28HD8/edit?usp=sharing)
- [airbnb-11](https://github.com/codesquad-member-2020/airbnb-11)
- [PR_링크-1](https://github.com/codesquad-member-2020/airbnb-11/pulls)
- [PR_링크-2](https://github.com/codesquad-member-2020/airbnb-11/pull/141)



### 이슈 관리 서비스

#### 개요

- 4인 (FE 2명, BE 2명), 3주간 진행
- Github Issue 기능을 클론하는 프로젝트



#### 사용 기술

- java, SpringBoot, Spring Data JPA, OAuth2, JWT, AWS, MySQL, 



#### 학습하고, 고민한 점

- `lombok` 을 통해, 조금 더 간결한 코드를 작성하였습니다.
- 특정 요청 사항을 담당하는 DTO 생성 시, validate를 하도록 하였습니다.
  - `@NotBlank` 같은 어노테이션을 학습하고 이용하였습니다.
- 어떻게 하면 좋은 commit message 적을지 생각하게 되었습니다.
  - commit title은 명령문으로, 그에 대한 설명을 아래 간결하게 적었습니다.
- [API Document](https://github.com/codesquad-member-2020/issue-tracker-03/wiki/API-문서) 를 github wiki를 통해 배포하였습니다.
  - 좀 더 자유로운 문서를 작성하기 위해 시도하였습니다.
- Spring Data JPA 에 전반적인 내용에 대해 학습하고 적용하였습니다.
  - FetchType, MappedBy 내용에 대해 학습했습니다.
  - JPA를 사용하는 만큼 프로젝트 구조를 DDD concept에 맞도록 작성하였습니다
- AWS S3를 통한 이미지 업로드 기능을 구현하였습니다.
- Unit Test를 작성하였습니다.





#### 아쉬웠던 점

- Spring Data JPA에 대해 깊이 있는 학습을 하지 못했습니다.
  - 객체지향과 Database에 대해 깊이 있게 알아야 해당 기술을 이용할 수 있다는 말을 체감하게 되었습니다.
- 기능 구현이 부족했습니다.
  - 학습 기간이 길어, 기능 구현에 많은 시간을 투자하지 못한 점이 아쉬웠습니다.



#### 참고

- [웹기획서](https://docs.google.com/presentation/d/1iA-tpumHl_TpR_yUwgYcnb_X8GbW6XvjZOTh2Ucvu0A/edit#slide=id.p)
- [issue-tracker-03](https://github.com/codesquad-member-2020/issue-tracker-03)
- [PR_링크](https://github.com/codesquad-member-2020/issue-tracker-03/pull/83)

  

