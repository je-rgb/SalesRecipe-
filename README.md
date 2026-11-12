# 🚀 AI 서비스 기획 프로젝트

> 프로젝트에 대한 한 줄 소개를 작성해주세요.

---

## 👥 팀원 소개

| 이름 | 역할 | GitHub 프로필 | 담당 업무 |
| :---: | :---: | :---: | :---: |
| 홍나희 | PM | [@github_id](https://github.com/) | 서비스 기획, 일정 관리 |
| 안정은 | PL | [@github_id](https://github.com/) | AI 모델링, API 개발 |
| 이대성 | 프론트 / UI | [@github_id](https://github.com/) | UI/UX 디자인, 프로토타입 구현 |

---

## 🌿 브랜치 전략 (GitHub Flow 권장)

팀 협업 시 `main` 브랜치에 직접 커밋하지 않고, 기능별 브랜치를 생성하여 PR(Pull Request) 후 병합합니다.

- `main`: 배포 및 최종 제출 가능한 안정된 브랜치
- `feat/{기능명}`: 새로운 기능 개발 또는 기획서 작성 (예: `feat/login`, `feat/prd-draft`)
- `fix/{버그명}`: 버그 수정 (예: `fix/api-error`)
- `docs/{문서명}`: 문서 작성 및 수정 (예: `docs/readme-update`)

### 작업 흐름
1. 최신 `main` 브랜치에서 새 브랜치 생성: `git checkout -b feat/your-feature`
2. 작업 후 커밋 및 원격 브랜치에 푸시: `git push origin feat/your-feature`
3. GitHub에서 `main` 브랜치로 PR 생성 및 팀원 리뷰
4. 리뷰 및 승인(Approve) 후 Squash and Merge 또는 Create a merge commit

---

## 📝 커밋 컨벤션 (Commit Convention)

커밋 메시지는 다음과 같은 형식으로 통일합니다:

```text
<type>(선택적 scope): <subject>

[선택적 본문]
```

### Type 분류

| Type | 설명 |
| :--- | :--- |
| `feat` | 새로운 기능 추가 / 신규 기획 문서 작성 |
| `fix` | 버그 수정 또는 잘못된 내용 수정 |
| `docs` | README, 기획서, 주석 등 문서 수정 |
| `style` | 코드 포맷팅, 세미콜론 누락 등 (코드 로직 변화 없음) |
| `refactor` | 코드 리팩토링 |
| `test` | 테스트 코드 추가 / 수정 |
| `chore` | 빌드 업무, 패키지 매니저 설정, .gitignore 등 잡무 |

### 커밋 메시지 예시
- `feat: 사용자 설문조사 기반 AI 추천 로직 추가`
- `docs: 서비스 요구사항 정의서(PRD) 초안 작성`
- `fix: API 응답 파싱 에러 해결`
- `chore: .gitignore에 모델 가중치 파일 제외 규칙 추가`

---

## 🛠️ 시작 가이드

```bash
# 저장소 복제
git clone <저장소-URL>
cd AI서비스기획

# 환경변수 템플릿 복사 (필요 시)
cp .env.example .env
```
