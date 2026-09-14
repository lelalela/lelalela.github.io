# 🎯 포트폴리오 웹사이트 구축 OKR & 향후 확장 로드맵

Java 백엔드 기반 풀스택 엔지니어 포트폴리오 구축 현황 및 향후 확장 계획을 정리한 문서입니다.

---

## 📌 OKR (Objectives and Key Results)

### **Objective (목표)**
> **"비즈니스 임팩트와 기술적 깊이(아키텍처, 성능 튜닝)를 겸비한 시니어 Java 풀스택 엔지니어로서의 전문성을 효과적으로 전달한다."**

### **Key Results (핵심 결과 지표)**

| 구분 | Key Result | 진행 상태 | 세부 내용 |
| :--- | :--- | :---: | :--- |
| **KR 1** | 모던 테크 UI 기반 단일 페이지 구축 | ✅ 완료 | Tailwind CSS + Lucide Icons, 다크/라이트 모드, 인쇄(PDF) 최적화 |
| **KR 2** | 백엔드 특화 심층 섹션 설계 | ✅ 완료 | 분산 아키텍처 다이어그램 및 Problem-Action-Result 트러블슈팅 카드 |
| **KR 3** | 개인 맞춤 데이터 입력 및 정량 수치 반영 | ⏳ 대기 | `index.html` 내 본인의 실제 프로젝트/경력/수치 성과 업데이트 |
| **KR 4** | GitHub Pages (`username.github.io`) 배포 | ⏳ 대기 | GitHub 원격 저장소 생성 및 메인 브랜치 푸시 |

---

## 🛠️ 향후 추가 확장 아이디어 (Backlog & Roadmap)

나중에 사이트를 고도화할 때 적용할 수 있는 기능 목록입니다:

### 1. 기능성 확장
- [ ] **Contact 폼 실제 메일 발송 연동**:
  - `Formspree` 또는 `EmailJS`를 연동하여 방문자가 사이트에서 바로 이메일을 발송할 수 있도록 구현
- [ ] **프로젝트 상세 팝업/모달 (Modal View)**:
  - 프로젝트 카드를 클릭했을 때 더 자세한 ERD, 아키텍처 다이어그램, 트러블슈팅 상세를 띄우는 모달 창 추가
- [ ] **방문자 분석 (Google Analytics 4)**:
  - 포트폴리오 조회수 및 채용 담당자/유입 경로 추적용 GA 스크립트 삽입

### 2. 콘텐츠 및 브랜딩 확장
- [ ] **기술 블로그 포스팅 연동**:
  - Velog / Tistory / Medium RSS 피드를 가져와 최신 글 목록 자동 노출
- [ ] **영문(English) 지원**:
  - 글로벌 기업/해외 리크루터를 위한 영문/국문 언어 토글 기능
- [ ] **커스텀 도메인 연결**:
  - `yourname.dev` 또는 `yourname.io` 같은 개인 도메인 구매 후 GitHub Pages CNAME 연결

---

## 📂 파일 구조 현황

```text
my-github-homepage/
├── index.html            # 포트폴리오 메인 웹페이지 (전체 UI & 기능)
├── README.md             # 배포 가이드 및 기본 사용 설명서
└── PORTFOLIO_OKR.md      # 포트폴리오 구축 OKR 및 향후 로드맵 (본 문서)
```
