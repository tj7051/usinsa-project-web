# SpringBoot(MSA)-Project-USINSA

![musinsa1](https://github.com/tj7051/usinsa-project-web/assets/133080387/cc2d0374-a24a-4685-a544-e83266067003)

## :tv:  프로젝트 소개

🛍️ **새로운 차원의 쇼핑몰 - MSA 아키텍처 기반으로 구축된 혁신적인 플랫폼** 🚀

유명 쇼핑몰 무신사(musinsa)를 참조하여 만든 쇼핑몰 어플리케이션입니다. 

**주요 기능 및 사용 기술:**

1. 🏢 **MSA 아키텍처**: 우리의 쇼핑몰은 각 기능을 독립된 마이크로서비스로 분리하여 개발되었습니다. 이렇게 함으로써 서비스 간 통신이 더욱 간편해지며, 확장성과 유지보수성을 높일 수 있습니다.
 
2. 🛒 **상품 주문 및 재고 관리**: 고객이 상품을 주문할 때마다 상품의 재고가 실시간으로 감소되는 기능을 제공합니다. 이를 통해 고객은 항상 최신의 재고 정보를 확인하고 신속하게 주문할 수 있습니다.
 
3. 📦 **개인화된 주문 목록**: 각 회원은 로그인하여 자신의 주문 목록을 확인할 수 있습니다. OpenFeign을 통한 서비스 간 통신으로 각 회원의 주문 내역을 편리하게 조회할 수 있습니다.
 
4. 🖥️ **효율적인 프론트엔드**: 프론트엔드는 리액트(React)를 사용하여 구축되었습니다. 이를 통해 다양한 기기와 환경에서도 일관된 사용자 경험을 제공하며, 효율적인 UI/UX를 실현합니다.
 
5. 🔒 **보안 강화**: 보안을 위해 JWT와 Spring Security를 활용하여 사용자 인증 및 권한 부여를 철저히 관리합니다. 또한 ModelMapper와 같은 라이브러리를 활용하여 데이터베이스 조작을 안전하고 효율적으로 처리합니다.

6. 🛠 **지속적 통합 및 배포**: (CI/CD): 우리는 지속적 통합 및 배포 프로세스를 구축하여 개발과 배포를 자동화하였습니다. 각 마이크로서비스의 변경 사항은 자동으로 테스트되며, 검증된 코드는 실시간으로 스테이징 및 운영 환경으로 배포됩니다.

7. ☁ **AWS 클라우드 배포**: 애플리케이션은 Amazon Web Services(AWS)를 활용하여 클라우드 환경에서 운영됩니다. AWS의 다양한 서비스를 통해 안정적이고 확장 가능한 인프라를 구축하고 관리합니다.

8. 🔄 ORM으로 JPA 사용: 데이터베이스 조작에는 ORM 기술인 JPA를 활용하여 객체 지향적인 방식으로 데이터베이스와 상호작용합니다. 이로써 SQL 쿼리 작성 및 데이터베이스 조작의 복잡성을 줄이고, 보안과 성능을 향상시킵니다.

---

## :alarm_clock:  개발 기간
● 23.05.01 - 23.05.19

---

## :low_brightness: 사용 기술 스택
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <br/>
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <br/>
<img src="https://img.shields.io/badge/Apache Maven-C71A36?style=for-the-badge&logo=Apache Maven&logoColor=white"> <br/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <br/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/> <br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Dokcer&logoColor=white"/> <br/>
<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"/> <br/>
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat-square&logo=GitHub Actions&logoColor=white"/> <br/>
---

## 🖥 주요 기능
#### 회원가입 & 로그인 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85,-%EB%A1%9C%EA%B7%B8%EC%9D%B8)">상세보기 - Wiki 이동</a>

#### 메인 홈페이지 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EB%A9%94%EC%9D%B8-%ED%99%88%ED%8E%98%EC%9D%B4%EC%A7%80)">상세보기 - Wiki 이동</a>

#### 마이페이지 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(My-Page)">상세보기 - Wiki 이동</a>

#### 상품 등록 & 수정 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EC%83%81%ED%92%88-%EB%93%B1%EB%A1%9D-&-%EC%88%98%EC%A0%95)">상세보기 - Wiki 이동</a>

#### 상품 주문 & 취소 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EC%83%81%ED%92%88-%EC%A3%BC%EB%AC%B8-&-%EC%B7%A8%EC%86%8C)">상세보기 - Wiki 이동</a>

#### 댓글 - <a href="https://github.com/tj7051/usinsa-project-web/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C(%EB%8C%93%EA%B8%80-%EA%B8%B0%EB%8A%A5)">상세보기 - Wiki 이동</a>

---

## 🔗 구조도

---

## 🔍  ERD

