# Codex Pulse — Claude Code 규칙

## 이슈 생성 규칙

### 라벨

이슈를 생성할 때 반드시 아래 라벨을 모두 부착한다.

| 구분 | 라벨 | 설명 |
|------|------|------|
| 상태 | `status: ready` | 생성 즉시 작업 가능 상태 |
| 우선순위 | `priority: high` / `priority: medium` / `priority: low` | 긴급도에 따라 1개 선택 |
| 카테고리 | `enhancement` / `documentation` / `bug` | 작업 성격에 따라 1개 선택 |

### 제목

- **한국어**로 작성한다.
- **동사형**으로 시작한다. (예: "추가하다", "수정하다", "개선하다")
- **70자 이내**로 작성한다.
- 예시: `CI 워크플로우에 캐싱 단계 추가하기`

### 본문 형식

아래 순서를 반드시 지킨다.

```markdown
## 배경
<!-- 왜 이 작업이 필요한지 설명 -->

## 작업 내용
- [ ] 할 일 1
- [ ] 할 일 2

## 관련 파일
- `path/to/file.rs`

## 비고
<!-- 참고 사항, 관련 이슈 링크 등 -->
```

## 커밋 · 브랜치 컨벤션

[CONTRIBUTING.md](./CONTRIBUTING.md)의 Commit Convention 및 Development Workflow 섹션을 따른다.

## PR 규칙

- PR 템플릿(`.github/pull_request_template.md`)을 따른다.
- 관련 이슈가 있으면 본문에 `Closes #이슈번호`를 포함한다.
