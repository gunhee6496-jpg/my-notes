> [!info] Cherry Studio 소개
> **Cherry Studio**는 Gemini, GPT등의 다양한 AI 대형 언어 모델(LLM)을 하나의 플랫폼에서 통합 관리할 수 있는 **올인원 AI 데스크톱 클라이언트**입니다.
> 전문가부터 일반 사용자까지 누구나 쉽게 AI를 활용할 수 있도록 설계된 이 도구는 직관적인 인터페이스와 강력한 기능을 제공합니다.

---

## 1. Cherry Studio 설치

[Cherry Studio 다운로드 페이지](https://www.cherry-ai.com/download)에서 설치 파일을 다운로드하세요.

1. Cherry Studio 홈페이지에서 다운로드
2. 우측 상단의 최근 다운로드 - cherry-studio-setup 폴더 열기
3. 설치 옵션, 설치 위치 선택 후 설치

![[Cherry studio 가이드 사진 1.jpg]]

---

## 2. Anthropic 모델 등록

현재 JiminAPI는 Anthropic과 Open AI 두 가지 형태의 API 방식을 제공하고 있습니다.

### API 키 등록

1. Cherry Studio 실행 후 우측 상단의 설정 버튼 클릭
2. **Model provider** 항목 선택
3. **Anthropic** 선택
4. **API Key**에 할당받은 API 키 입력
5. **API Host**에 `https://api.jiminbox.com` 입력
6. Models 목록 우측의 `-`를 클릭해 현재 등록된 모델 제거
7. **+ Add** 클릭
8. **Model ID**에 지원 모델을 입력 후 **Add Model** 클릭
9. API Key 우측의 **Check** 버튼 클릭
10. **Connection Successful** 확인 후 우측 상단 활성화 버튼 클릭

> [!tip] 지원 모델 목록
> 현재 jiminAPI에서 제공하는 Anthropic 모델:
> - `claude-opus-4-5-thinking`
> - `claude-sonnet-4-5`
> - `claude-sonnet-4-5-thinking`

> [!warning] 주의
> Model ID는 jiminAPI에서 제공하는 모델명과 **정확히 동일하게** 입력해야 합니다.

![[Cherry studio 가이드 사진 2.jpg]]

---

## 3. Open AI 방식 모델 등록

### API 키 등록

1. Cherry Studio 실행 후 우측 상단의 설정 버튼 클릭
2. **Model provider** 항목 선택
3. **New API** 선택
4. **API Key**에 할당받은 API 키 입력
5. **API Host**에 `https://api.jiminbox.com` 입력
6. **Manage** 클릭
7. 우측의 **+** 버튼을 눌러 원하는 모델을 추가
8. API Key 우측의 **Check** 버튼 클릭
9. 테스트할 모델을 선택 후 **OK** 버튼 클릭
10. **Connection Successful** 확인 후 우측 상단 활성화 버튼 클릭

![[Cherry studio 가이드 사진 3.jpg]]

---

## 다음 단계

- [[jiminbox 빠른 시작 가이드]] - jiminbox 시작하기
- [[opencode 설치 가이드(window)]] - OpenCode에서 API 키 설정하기

---

#jiminbox #CherryStudio #API #설치가이드
