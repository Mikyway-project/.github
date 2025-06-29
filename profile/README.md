# 청소업체 은하수홈케어 웹사이트

---
> 경상남도 지역을 연고로 설립된 청소 업체의 공식 웹사이트
직접 프로젝트의 기획 부터, 프론트엔드, 백엔드, 배포까지 전체 개발을 담당하였음.

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
- SpringBoot + Mybatis + JPA
- Session + SpringBoot Security로 보안 설정

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

### 서비스 소개 및 청소 전후 리뷰
![스크린샷_29-6-2025_9458_mlikway co kr](https://github.com/user-attachments/assets/970b0708-3821-47bb-bb72-91393ebff7e4)

