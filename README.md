# VetConsult 팀 컨벤션

단일 레포 · 모놀리식(헥사 모듈) 기준의 **팀 규칙**만 모은 저장소다.

## 문서

| 파일 | 용도 |
|------|------|
| [CODE_CONVENTIONS.md](CODE_CONVENTIONS.md) | 코드 작성·리뷰 |
| [GIT_CONVENTIONS.md](GIT_CONVENTIONS.md) | 커밋·브랜치·PR |
| [CONFIG.md](CONFIG.md) | local / dev / prod 설정 |
| [.github/pull_request_template.md](.github/pull_request_template.md) | PR 템플릿 |
| [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) | 이슈 폼 |
| [.cursor/rules/](.cursor/rules/) | Cursor 룰 |

## 팀원 사용

1. 이 레포를 clone 하거나 필요한 파일을 복사한다.
2. Cursor: `.cursor/rules/*.mdc` → 앱 워크스페이스 `.cursor/rules/`
3. 앱 레포(단일 모놀리식): `.github/` 템플릿을 앱 루트에 복사

설계 DDL·소유권 문서(`design-guide` 등)는 이 레포에 포함하지 않는다.
