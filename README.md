# 🚀 AI Agent Custom Skills Repository

이 저장소는 AI 코딩 에이전트(Antigravity 등)의 생산성을 극대화하기 위해 직접 개발하고 관리하는 **커스텀 스킬(Custom Skills)** 모음집입니다.

## 🛠️ 포함된 스킬 목록

| 스킬 이름 | 설명 | 트리거 키워드 |
| :--- | :--- | :--- |
| [git-commit-helper](skills/git-commit-helper/SKILL.md) | Conventional Commits 표준에 맞는 Git 커밋 메시지 자동 생성 | `커밋 메시지 작성해줘`, `git commit` |

---

## ⚙️ 적용 및 사용 방법

### 1. 로컬 프로젝트에 적용하기
이 저장소를 프로젝트 루트의 `.agents` 폴더로 설정하면 에이전트가 스킬들을 자동으로 로드합니다.

```bash
# 프로젝트 루트 디렉토리에서 실행
git clone https://github.com/skyonline112/skills.git .agents
```

### 2. 글로벌 설정에 적용하기
에이전트가 모든 워크스페이스에서 이 스킬들을 전역적으로 사용하도록 하려면, 에이전트의 글로벌 설정 디렉토리 아래에 스킬 폴더를 배치합니다.
- **경로**: `C:\Users\<사용자명>\.gemini\config\skills\`
