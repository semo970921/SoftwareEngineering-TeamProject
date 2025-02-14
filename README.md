# 🌱 Spring Blog 소프트웨어공학 분석 문서

> **가톨릭대학교 소프트웨어공학 오재원 교수님 팀플로 진행된 [`Raysmond/SpringBlog`](https://github.com/Raysmond/SpringBlog) 분석 결과를 정리한 문서입니다.**  
> Spring Boot 기반 블로그 시스템의 설계 및 기능을 분석하고, 이를 문서화한 자료를 포함합니다.

---

## ⭐ 주요 분석 내용

- 🏠 **유저 스토리 분석**
  - 메인 페이지 구성 및 주요 기능
  - 게시글, 아카이브, 태그 시스템 구조
  - 백엔드 관리 시스템 (게시글 관리, 설정, 프로필 관리)

- 🛠 **Spring Blog 아키텍처 분석**
  - **Layered Architecture (계층 구조)**
  - **MVC 패턴 적용 방식**
  - **Repository 아키텍처 분석**
  - **Transactional 처리 방식 분석**

- 💻 **기능 흐름 분석**
  - 게시글 CRUD 프로세스
  - 사용자 로그인 및 프로필 수정 흐름
  - 태그 및 아카이브 페이지 구조
  - 관리자 페이지 및 권한 설정

---

## 📂 **파일 설명**
| 파일명 | 설명 |
|--------|------|
| [`SpringBlog_유저스토리.pdf`](./SpringBlog_유저스토리.pdf) | Spring Blog 프로젝트의 유저 스토리 정리 |
| [`SpringBlog_분석.pdf`](./SpringBlog_분석.pdf) | Spring Blog의 시스템 모델링 및 아키텍처 분석 |

📌 **이 문서는 소프트웨어공학 수업의 팀 프로젝트 일환으로 작성되었습니다.**  
📌 **Spring Blog의 원본 코드에는 영향을 주지 않으며, 분석 및 학습 목적으로 제공됩니다.**  
📌 **본 문서는 Raysmond/SpringBlog 프로젝트를 기반으로 작성되었으며, 원본 프로젝트의 라이선스를 준수해야 합니다.**  
📌 **라이선스 등록을 위해 `LICENSE` 파일을 반드시 포함하고, Modified BSD License의 내용을 유지해야 합니다.**  



---

## 📄 **라이선스**
이 저장소의 분석 문서는 [`Raysmond/SpringBlog`](https://github.com/Raysmond/SpringBlog)를 기반으로 작성되었습니다.  
해당 프로젝트는 Modified BSD License를 따르며, 원본 프로젝트의 저작권은 **Jiankun LEI (Raysmond)**에게 있습니다.  
본 문서는 분석 및 학습 목적으로 작성되었으며, 원본 코드 수정 및 배포와는 무관합니다.

라이선스 관련 내용은 [`LICENSE`](./LICENSE) 파일을 참고하세요.



