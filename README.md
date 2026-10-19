# lost-and-found-practice
"교내 분실물 관리 서비스" 실습 저장소

## 프로젝트 소개
교내에서 잃어버린 물건을 등록하고 조회할 수 있는 서비스를 Python으로 개발하는 실습 프로젝트입니다.
AI Agent(Claude Code)와 협업하며 SW 개발 생명주기(SDLC)와 Git 버전 관리를 익히는 것을 목표로 합니다.

## 폴더 구조
```
lost-and-found-practice/
├─ README.md              # 프로젝트 소개와 기본 사용 안내
├─ AGENTS.md              # Agent가 따라야 할 프로젝트 규칙
├─ CLAUDE.md              # Claude Code가 AGENTS.md를 읽도록 연결
├─ .gitignore             # Git에서 제외할 Python 임시 파일
├─ src/lost_and_found/
│  └─ __init__.py         # Python 패키지 표시
├─ tests/                 # 테스트 코드
└─ docs/                  # 산출물 문서
```

## 기본 사용 안내
```
git clone https://github.com/methesteam-ux/lost-and-found-practice
cd lost-and-found-practice
python -m venv .venv
```
* 가상환경 활성화: Windows `.venv\Scripts\activate` / macOS·Linux `source .venv/bin/activate`
* 커밋 메시지 규칙은 [AGENTS.md](AGENTS.md)를 참고

## 요구사항 분석
### 고객 요구사항
- 고객 요구사항을 분석하기 위한 문서 작성

### 소프트웨어 요구사항 분석


### 아키텍처 설계
