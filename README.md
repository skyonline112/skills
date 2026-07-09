# 🚀 AI Agent Custom Skills Repository

이 저장소는 AI 코딩 에이전트(Gemini, ChatGPT, Claude, Cursor 등)의 생산성을 극대화하기 위해 직접 개발하고 관리하는 **범용 커스텀 스킬 & 프롬프트(Custom Skills & Universal Prompts)** 모음집입니다.

특정 플랫폼이나 도구에 종속되지 않고, 현존하는 어떤 AI 에이전트에서도 최적의 성능을 낼 수 있도록 설계되었습니다.

---

## 🛠️ 포함된 스킬 목록

| 스킬 이름 | 설명 | 트리거 키워드 | 파일 링크 |
| :--- | :--- | :--- | :--- |
| **git-commit-helper** | Conventional Commits 표준에 맞는 Git 커밋 메시지 자동 생성 | `커밋 메시지 작성해줘`, `git commit` | [SKILL.md](skills/git-commit-helper/SKILL.md) |

---

## ⚙️ 적용 및 사용 방법

### 1. Antigravity / Gemini 기반 에이전트 (Workspace Local)
프로젝트 루트 디렉토리 아래에 `.agents` 폴더로 이 저장소를 클론하면 에이전트가 스킬을 자동으로 감지하고 로드합니다.
```bash
git clone https://github.com/skyonline112/skills.git .agents
```

### 2. Cursor IDE / VS Code Copilot
* `Cursor Settings` > `Features` > `Rules for AI` 또는 프로젝트 루트의 `.cursorrules` 파일에 [SKILL.md](skills/git-commit-helper/SKILL.md)의 본문 내용을 복사하여 추가합니다.

### 3. Claude Projects / Custom GPTs (Web UI)
* Claude의 Project Instructions이나 ChatGPT의 Custom GPT Instructions에 [SKILL.md](skills/git-commit-helper/SKILL.md) 파일 내용을 그대로 업로드하거나 복사/붙여넣기하여 시스템 프롬프트로 지정합니다.

### 4. 일반적인 LLM (ChatGPT, Claude 등) 직접 사용 시
* Git 변경 사항(`git diff` 등)을 채팅창에 입력하기 전에 [SKILL.md](skills/git-commit-helper/SKILL.md) 본문 전체를 프롬프트로 주입하여 AI에게 먼저 '역할(Role)'을 부여한 뒤 사용합니다.
