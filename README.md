# 🧑‍💻 공용 협업 연습용 저장소

이 저장소는 **GitHub 협업 방식**을 연습하기 위한 공용 레포지토리입니다.  
팀원들은 이곳에서 **branch 생성, commit, pull request, conflict 해결** 등의 과정을 실습합니다.

---

## 🚀 목적 (Purpose)
- Git과 GitHub의 협업 흐름을 실습하기 위해  
- Branch 전략과 Pull Request 과정을 이해하기 위해  
- 협업 시 코드 충돌(conflict) 해결 경험을 쌓기 위해  

---

## ⚙️ 개발 환경 설정 (Development Setup)

```bash
git clone https://github.com/bbstation09/NOVA-P1-seokjuksun.git
cd [clone한 (로컬에서의) 폴더명]
git lfs pull
pip install -r requirements.txt
```
<br>

---

## ✅ Commit Convention

| 태그 이름    | 설명 |
|--------------|------|
| [chore]      | 코드 수정, 내부 파일 수정 |
| [feat]       | 새로운 기능 구현 |
| [add]        | FEAT 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 |
| [hotfix]     | issue나 QA에서 급한 버그 수정에 사용 |
| [fix]        | 버그, 오류 해결 |
| [remove]     | 쓸모 없는 코드 삭제 |
| [docs]       | README나 WIKI 등의 문서 개정 |
| [correct]    | 주로 문법의 오류나 타입의 변경, 이름 변경에 사용 |
| [move]       | 프로젝트 내 파일이나 코드의 이동 |
| [rename]     | 파일 이름 변경이 있을 때 사용 |
| [improve]    | 향상이 있을 때 사용 |
| [refactor]   | 전면 수정이 있을 때 사용 |
| [test]       | 테스트 코드 추가 시 사용 |

---

### 🔸 커밋 메세지 작성
- 예시: `[feat] 로그인 api 개발`

#### 선택사항 ㅣ 이모티콘을 이용한 커밋 메세지 작성  
- Gitmoji 사용 예시: `:fire: [remove] main.py 삭제`  
- 참고 링크: https://inpa.tistory.com/entry/GIT-%E2%9A%A1%EF%B8%8F-Gitmoji-%EC%82%AC%EC%9A%A9%EB%B2%95-Gitmoji-cli

---

## 🔸 Git Working Process
1. Issue를 등록한다.  
2. 깃 컨벤션에 맞게 Branch를 생성한다.  
3. Local Repository에서 `git add` → `git commit` 후 Remote Repository에 해당 브랜치를 `git push` 한다.  
4. GitHub에서 Pull Request(PR)를 생성하여 main 브랜치로 Merge 요청을 보낸다.  
5. 코드 리뷰 및 자동 테스트(CI)를 확인한다.  
6. 충돌(conflict)이 있을 경우 로컬에서 `git pull origin main`으로 최신화 후 충돌을 해결한다.  
7. Merge가 완료되면 Merge된 Branch는 삭제한다.  
8. 종료된 Issue와 Pull Request의 Label과 Project를 정리/관리한다.

---

## 🌴 브랜치 규칙

#### 📌 브랜치 단위
- 브랜치 단위 = 이슈 단위 = PR 단위

#### 📌 브랜치명
- 브랜치는 뷰(View) 단위로 생성합니다.  
- 브랜치 규칙: `feature/#이슈번호`  
- 예시: `feature/#1`

---

## ⚙️ 개발 환경 설정 (참고)
```bash
git clone https://github.com/bbstation09/NOVA-P1-seokjuksun.git
cd [clone한 (로컬에서의) 폴더명]
git lfs pull
pip install -r requirements.txt
