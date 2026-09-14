# Java 백엔드 기반 풀스택 개발자 포트폴리오 웹사이트

GitHub Pages(`https://<username>.github.io`)에 빌드 과정 없이 즉시 배포할 수 있는 모던 포트폴리오 템플릿입니다.

---

## 🌟 주요 특징

- **직무 맞춤형 섹션**:
  - **Key Metrics**: 수치화된 엔지니어링 성과 (응답 지연 감소 %, 가용성 등)
  - **System Architecture & Data Flow**: 분산 아키텍처 및 계층별 데이터 흐름 시각화
  - **Engineering Deep-Dive & Troubleshooting**: 문제 정의(Problem) -> 기술적 해결(Action) -> 성과(Result) 구조의 트러블슈팅 케이스
  - **Full-Stack Tech Matrix**: Java/Spring Boot, DB/Redis, React/TypeScript, DevOps/AWS 스택 맵
- **모던 테크 UI**:
  - 다크 모드 / 라이트 모드 실시간 토글 (사용자 설정 저장)
  - Pretendard & JetBrains Mono 폰트
  - Tailwind CSS + Lucide Icons 기반
  - 인쇄 및 PDF 이력서 저장 최적화 (Print-friendly CSS)

---

## 🚀 GitHub Pages 배포 방법

### 1단계: GitHub 저장소 생성
1. GitHub에서 새로운 저장소(New Repository)를 생성합니다.
2. 저장소 이름을 반드시 **`<username>.github.io`**로 설정합니다. (예: `yjnoh.github.io`)

### 2단계: 파일 푸시
```bash
git add .
git commit -m "feat: initial portfolio website"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

### 3단계: Pages 활성화 확인
- GitHub 저장소의 **Settings** -> **Pages** 탭에서 Source가 `Deploy from a branch (main / root)`로 설정되어 있는지 확인합니다.
- 약 1~2분 후 `https://<username>.github.io`로 접속하면 웹사이트가 배포됩니다.

---

## ✏️ 내 정보로 커스터마이징하기

`index.html` 파일을 열고 다음 항목들을 본인의 정보로 수정하세요:

1. **기본 정보**: 이름, 이메일 주소, GitHub 링크, 블로그 링크
2. **Key Highlights & Metrics**: 연차, 도메인, 수치 성과
3. **경력 사항 (Work Experience)**: 회사명, 직책, 재직 기간, 주요 기여 사항
4. **트러블슈팅 (Troubleshooting)**: 본인이 실제로 겪었던 문제 해결 경험(JPA 쿼리 튜닝, 동시성 제어 등)
5. **프로젝트 (Projects)**: 프로젝트 이름, 설명, 사용 기술 태그, GitHub 링크
