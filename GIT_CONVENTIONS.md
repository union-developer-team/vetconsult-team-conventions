# 기여 가이드 (Git)

이 프로젝트는 **단일 레포**다. 브랜치·PR·이슈는 모두 이 레포에서 진행한다.

## 커밋 메시지

```text
<타입>: <한글 설명>
```

| 타입 | 설명 |
|------|------|
| `feat` | 새 기능 |
| `fix` | 버그 수정 |
| `docs` | 문서 |
| `chore` | 빌드·설정 등 |
| `refactor` | 리팩터링 |
| `test` | 테스트 |
| `style` | UI·스타일 (해당 시) |

```text
feat: 회원 가입 API 추가
fix: JWT 검증 오류 수정
docs: README 템플릿 통일
```

## 브랜치

| 브랜치 | 역할 |
|--------|------|
| `main` | 안정·배포 기준 |
| `dev` | 통합 개발. 기능 PR의 **기본 대상** |

> 원본 가이드의 `develop`은 이 프로젝트에서 **`dev`** 로 통일한다.

## 브랜치 명명

1. GitHub Issue를 먼저 만든다. (`.github/ISSUE_TEMPLATE` 폼 사용)
2. 이슈 **승인**(`approved` 라벨 또는 승인 댓글/채팅) 후 작업 브랜치를 딴다.
3. `dev` 최신화 후 분기한다.
4. 이름: `{type}/{issue-number}-{short-slug}`
   예: `feat/1-login-api`, `feat/3-wave-offer-create`

## PR 제목

`.github/pull_request_template.md` 참고.

```text
[#{Issue Number}] Feature : 작업 내용
```

예: `[#12] Feature : 로그인 API 구현` / `[#25] Fix : …` / `[#31] Docs : …`

## PR 대상·머지

- 기능 PR → **`dev`**
- `main` 직행 PR 금지 (별도 합의 없으면)
- 머지는 사람이 한다
- 이슈 전체 완료 시 본문에 `Close #번호` (또는 `Closes #번호`)
