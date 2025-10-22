### 개발 환경 설정

```bash
git clone https://github.com/bbstation09/NOVA-P1-seokjuksun.git
cd [clone한 (로컬에서의) 폴더명]
git lfs pull
pip install -r requirements.txt
```

<br>

### ✅ Commit Convention
| 태그 이름      | 설명 |
|------------| --- |
| [chore]    | 코드 수정, 내부 파일 수정 |
| [feat]     | 새로운 기능 구현 |
| [add]      | FEAT 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 |
| [hotfix]   | issue나 QA에서 급한 버그 수정에 사용 |
| [fix]      | 버그, 오류 해결 |
| [remove]   | 쓸모 없는 코드 삭제 |
| [docs]     | README나 WIKI 등의 문서 개정 |
| [correct]  | 주로 문법의 오류나 타입의 변경, 이름 변경에 사용 |
| [move]     | 프로젝트 내 파일이나 코드의 이동 |
| [rename]   | 파일 이름 변경이 있을 때 사용 |
| [improve]  | 향상이 있을 때 사용 |
| [refactor] | 전면 수정이 있을 때 사용 |
| [test]     | 테스트 코드 추가 시 사용 |

<br>

### 🔸커밋 메세지 작성
- ex) [feat] 로그인 api 개발

<br>

#### 선택사항 ㅣ 이모티콘을 이용한 커밋 메세지 작성 
https://inpa.tistory.com/entry/GIT-%E2%9A%A1%EF%B8%8F-Gitmoji-%EC%82%AC%EC%9A%A9%EB%B2%95-Gitmoji-cli
- `ex) :fire: [remove] main.py 삭제`

<br>

### 🔸 Git Working Process
1. issue를 등록한다.
2. 깃 컨벤션에 맞게 Branch를 생성한다.
3. Local Repository에서 Add - Commit 후 Remote Repository에 해당 브랜치를 Push한다.
4. Github에서 PR을 생성하여 main Branch에 Merge를 진행한다.
8. merge된 Branch는 삭제한다.
9. 종료된 Issue와 Pull Request의 Label과 Project를 관리한다.

<br>

🌴 브랜치
---
#### 📌 브랜치 단위
- 브랜치 단위 = 이슈 단위 = PR단위

#### 📌 브랜치명
- 브랜치는 뷰 단위로 생성합니다.
- 브랜치 규칙 → feature/#이슈번호
- `ex) feature/#1`
