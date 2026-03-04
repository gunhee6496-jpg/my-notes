### 1. 기본 설치 (Node.js & Opencode)

1. **Node.js 설치**
   - Node.js가 설치되어 있어야 합니다. 설치되지 않았다면 아래 가이드를 참고하세요.
   - 참조: [[node.js 설치 가이드]]

2. **Opencode 설치**
   - `Windows` 키 + `R`을 누르고 `cmd`를 입력하거나, 시작 메뉴에서 **명령 프롬프트**를 실행합니다.
   - 아래 명령어를 입력하고 엔터를 누릅니다.
     ```bat
     npm i -g opencode-ai
     ```

3. **설치 확인**
   - 설치가 끝나면 `cmd` 창에 `opencode`를 입력해봅니다.
   - 아래 사진과 같은 화면이 나오면 설치가 완료된 것입니다.
   ![[opencode 설치 가이드(window) 사진 1.png]]

---

### 2. API 설정하기 (필수)

Opencode를 사용하려면 API Key를 설정 파일에 등록해야 합니다.

#### 1단계: 설정 파일 생성
1. **내용 복사**: [[opencode.json]] 파일을 열어 내용을 전체 복사합니다.
2. **폴더 이동**: 아래 경로로 이동합니다.
   - 경로: `C:\Users\<사용자명>\.config\opencode`
1. **파일 생성**:
   - 해당 폴더에 메모장(텍스트 파일)을 새로 만듭니다.
   - **중요**: 파일 확장자가 보이도록 설정해야 합니다. 탐색기 상단 메뉴에서 **[보기]** -> **[표시]** -> **[파일 확장명]**을 체크해주세요.
     ![[opencode 설치 가이드(window) 사진 2.png]]
   - 파일 이름을 `opencode.json`으로 변경합니다. (`.txt`가 남지 않도록 주의!)

#### 2단계: API Key 입력
1. 생성한 `opencode.json` 파일을 우클릭하여 **메모장**으로 엽니다.
2. `Ctrl` + `F`를 눌러 `apiKey`를 검색합니다.
3. 아래 사진의 강조된 부분(따옴표 `""` 사이)에 발급받은 API Key를 붙여넣습니다.
   ![[opencode 설치 가이드(window) 사진 3.png]]
   - **예시**: `"apiKey": "sk-wJs..................."`
4. 만약 여러 모델을 사용한다면, 아래 화살표를 눌러 다음 `apiKey` 위치도 찾아 입력합니다.
   ![[opencode 설치 가이드(window) 사진 4.png]]
5. 입력을 마쳤으면 파일을 저장(`Ctrl` + `S`)하고 닫습니다.

#### 3단계: 설정 확인
1. `cmd` 창에서 `opencode`를 실행합니다.
2. 입력창에 `/models`를 입력하고 엔터를 칩니다.
3. 스크롤을 내렸을 때, 아래 사진처럼 jiminbox에서 제공하는 모델 목록이 보이면 설정 성공입니다.
   ![[opencode 설치 가이드(window) 사진 5.png]]

---

### 3. 확장 기능 (Oh My Opencode)
*선택 사항: jiminAPI에서 추천하는 Opencode 플러그인입니다.*

**설치 방법**
1. `opencode`를 실행합니다.
2. 아래 박스 안의 내용을 복사하여 프롬프트 창에 붙여넣고 엔터를 누릅니다.

```text
Install and configure oh-my-opencode by following the instructions here:
https://raw.githubusercontent.com/code-yeongyu/oh-my-opencode/refs/heads/master/docs/guide/installation.md
```
3. opencode가 질문하는 항목들에 전부 no로 답변하면 설치가 완료됩니다.