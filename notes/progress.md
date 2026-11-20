# 진행 상황 (새 대화를 시작하면 여기부터 확인)

## 마지막 기록: 2026-11-17

### 0단계 환경 준비: 진행 중
- [x] IntelliJ IDEA 2026.3 설치
- [x] JDK 25 설치: IntelliJ에서 Eclipse Temurin 25.0.5 다운로드 (`C:\Users\dlwog\.jdks\temurin-25.0.5`)
- [x] `C:\java-study` 폴더를 IntelliJ 프로젝트로 열기 (File → Open), `src`를 Sources Root로 지정
- [x] `src/day01/HelloWorld.java` 작성 및 실행 성공, 서버 접속 메시지 3줄 출력 도전 완료
- [ ] **Git 저장소 만들기 ← 여기서 멈춤**
  - `git config --global init.defaultBranch main`
  - `git init`
  - `.gitignore` 작성: `out/`, `.idea/workspace.xml`, `.idea/shelf/`
  - `git status` → `git add .` → `git status` → `git commit -m "0단계: 프로젝트 설정과 Hello World"` → `git log --oneline`
  - 확인 질문: `git add .` 전과 후에 `git status` 결과가 어떻게 달라졌고, 왜 그럴까?
- [ ] IntelliJ 디버거(중단점) 사용해 보기

### 겪은 문제와 배운 점
- New Project의 Location에 `C:\java-study`를 넣으면 `C:\java-study\java-study`가 생긴다. Location 안에 Name 폴더를 새로 만들기 때문이다.
- Location을 `C:\`로 하면 "기록할 수 없습니다" 오류가 난다. Windows가 C 드라이브 루트에 쓰는 것을 막기 때문이다.
- 해결: 이미 있는 폴더는 **File → Open**으로 연다.
