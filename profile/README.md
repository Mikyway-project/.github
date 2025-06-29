# 청소업체 은하수홈케어 웹사이트

---
> 경상남도 지역을 연고로 설립된 청소 업체의 공식 웹사이트
직접 프로젝트의 기획 부터, 프론트엔드, 백엔드, 배포까지 전체 과정정을 담당하였음.

# 프로젝트 개요
- ***프로젝트명*** : 경상남도 청소업체 은하수홈케어 홈페이지
- ***기간*** : 2025.03.08 ~ 2025.05.27 (약 2개월)
- ***개발 형태*** : 단독 설계 개발 프로젝트
- ***기여도*** : 100%
- ***URL*** : https://www.mlikway.co.kr

---

# 사용 기술 스택

## Frontend
- React + TypeScript + Vite
- Redux (전역 상태 관리)
- Styled-Components + Tailwind CSS + SCSS

## Backend
- SpringBoot + Mybatis + JPA/Hibernate
- Session + SpringBoot Security로 보안 설정
- Java 17 + Spring Boot 3.2.1
- Swagger를 통한 API 문서 구현

## Infra / DevOps
- AWS EC2 (Ubuntu)
- Docker, Docker Compose
- Nginx(HTTPS, Reverse Proxy)
- Github Action (CI/CD)
- AWS RDS (MYSQL)
- AWS S3 (이미지 데이터를 저장하기 위한 목적)

## 기타
- Google Analytics (GA4), Naver Analytics
- robots.txt, sitemap.xml, Open Graph

---
# 주요기능
## 사용자
 - 모바일 반응형 UI 지원
 - 청소업체 소개 페이지에서 바로 전화상담
 - 은하수홈케어 네이버 블로그 게시글 연동
 - 시스템을 통한 청소 문의 기능 제공
 - 청소 예약 신청 폼 및 제출
 - 질문 게시판 작성(비밀번호를 맞아야 댓글 입력 가능)
## 관리자
- 문의 신청 현황 확인 및 관리
- 청소업체 홈페이지 내 청소 후기글 작성 및 관리
- 대표적인 질문에 대한 작성 기능
- 이미 업무 일정이 잡혔을 경우, 일정 제어
- 로그인 상태라면 비밀번호가 틀려도 댓글 남기기 가능

---
# 주요화면

## 홈 화면
![스크린샷_29-6-2025_94153_mlikway co kr](https://github.com/user-attachments/assets/3bef9da0-f5d8-4955-add2-c263adbc120d)

## 서비스 소개 및 청소 전후 리뷰
![스크린샷_29-6-2025_9458_mlikway co kr](https://github.com/user-attachments/assets/970b0708-3821-47bb-bb72-91393ebff7e4)

## 청소 전후 소개 
![청소 전후 소개](https://github.com/user-attachments/assets/63d4b815-e894-4455-ad90-43e8f9153714)

## 예약 상담 신청
![청소 에약](https://github.com/user-attachments/assets/2795fded-ee6d-4f7c-b392-eaf990a88d42)

## 청소 Q&A
![청소 Q A](https://github.com/user-attachments/assets/2c0c581d-2853-42c1-9343-4f3aab73f793)

---
# 배포 및 운영
- AWS EC2 서버에 Docker 기반 프론트/백엔드 배포
- Nginx로 Https 및 인증서 처리
- GitHub Actions로 CI/CD 자동화

---
# SEO / 검색 최적화
- 메타태그, Open Graph, favicon 설정
- sitemap.xml 및 robots.txt 작성
- Google Search Console / Naver Search Advisor 등록 완료
---
# 내부적인 성과
---
- 실서비스 운영 중 (2025.06 기준)
- 서비스 오픈 이후 약 1주 내 Google/네이버 검색 노출 확인
- 네이버 로그인 API 검수 통과
- 클라이언트 만족도 높음
- 업종 및 업체 특성상, 방문자수는 많지 않지만 꾸준히 증가하는 추세에 있음
![image](https://github.com/user-attachments/assets/f7726410-5bd1-4159-8c93-1966e43c0830)
- 준수한 LightHouse 성능 지표 확인
![image](https://github.com/user-attachments/assets/1c7d864b-ef98-4e22-929e-31acb5c5a45c)

  > 백엔드 관련 내용 추가 필요!! 정리 후 할 예정
---
# 회고
- 실제 서비스 전반을 직접 개발하며 SEO, 로그인, CI/CD 자동화, 서버 구성 등 실전 경험을 폭넓게 체득함
- 초기 배포 중 Nginx 프록시 설정 누락으로 발생한 CORS 오류를 직접 해결하며 서버 인프라에 대한 이해도 향상
- Vite + React 환경에서 react-helmet-async를 사용하여 각 페이지별 meta 태그를 구성하고 SEO 최적화 경험
- AWS RDS를 활용하여 EC2 인스턴스 외부에 데이터베이스를 구성, JWT가 아닌 Session 기반 로그인 처리 시 고려사항을 학습함
- Postman 기반 테스트와 Spring Boot의 테스트 코드 기반 테스트 방식의 차이를 비교하며 테스트 기반 개발(TDD)에 대한 감을 익힘
- 👉 다음 프로젝트에서는 실제 테스트 코드 기반 개발 방식(Test Driven Development) 을 적극적으로 시도해볼 계획
- 평소 백엔드 위주의 개발을 해왔지만, 이번 프로젝트에서는 프론트엔드까지 직접 구현하며 **React, Vite, Helmet 등 프론트 기술 스택에 대한 감각과 이해도를 높일 수 있는 계기**가 될 수 있었습니다.
- 프론트엔드 개발 과정에서 UI/UX 구성의 중요성을 실감하였고, **향후 협업 시 프론트 개발자와의 소통에 있어 실질적인 이해 기반을 마련하게 됨**

---
# 개발자
----
- ***이름*** : 최연철
- ***이메일***: yyy1459@naver.com
