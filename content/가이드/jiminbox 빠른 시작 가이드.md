
> [!info] 시작하기 전에
> jiminbox는 다양한 AI 모델을 API 형태로 제공하는 서비스입니다.
> API 키는 jiminbox의 AI 모델을 외부 프로그램에서 사용하기 위한 열쇠입니다.

---

## 1. 계정 신청 및 로그인

먼저 [계정 신청하기 (Google Form)](https://forms.gle/FPWrXX2sZj4tJGAy5) 링크를 클릭하여 신청서를 작성해 주세요.

> [!warning] 중요
> 구글 폼에 **희망하는 아이디와 비밀번호**를 작성하여 제출하면, 관리자가 확인 후 계정을 생성합니다.
> **계정 생성 완료** 안내를 받은 후 아래 단계를 진행해 주세요.

계정 생성이 완료되었다는 안내를 받으셨다면, [api.jiminbox.com](https://api.jiminbox.com)에 접속하여 로그인하세요. 사이트 우측 상단의 sign in -> contine with OIDC를 클릭하여 로그인합니다. 또한 동일하게 우측 상단에서 언어를 영어로 변경할 수 있습니다.

![[jiminbox 빠른 시작 가이드 사진 1.png]]

---

## 2. 구독 플랜 및 사용량 확인

로그인 후 화면 좌측의 **Wallet Management** 메뉴를 선택하세요. 구독 중인 플랜과 사용량을 확인할 수 있습니다.

- 사용량은 5시간마다 초기화됩니다
- 총 사용량 현황 (예: $0.00 / $20.00)

![[jiminbox 빠른 시작 가이드 사진 2.png]]

---

## 3. API 키 발급

화면 좌측의 **Token Management** 메뉴로 이동 후 **Create Token** 버튼을 클릭하세요.

![[jiminbox 빠른 시작 가이드 사진 3.png]]

> [!tip] 초보자 권장 설정
> 아래 설정은 기본값을 그대로 유지하시면 됩니다:
> - **Name**: 식별 가능한 이름을 자유롭게 입력 (필수)
> - **Token grouping**: `default` 유지
> - **Expiration time**: `Never expires` 유지 (만료 없음)
> - **Quota Settings**: `Unlimited quota` 체크 유지 (사용량 제한 없음)
> - **Model restrictions**: 설정 불필요 (모든 모델 사용 가능)

![[jiminbox 빠른 시작 가이드 사진 4.png]]

설정 완료 후 **Submit** 버튼을 클릭하여 API 키를 발급받으세요.

---

## 다음 단계: API 키 사용하기

발급받은 API 키를 복사한 후, 아래 가이드를 참고하여 원하는 프로그램에 설정하세요:

- [[opencode 설치 가이드(window)]] - OpenCode에서 API 키 설정하기
- [[Cherry studio 가이드]] - Cherry Studio에서 API 키 설정하기

---

#jiminbox #API #초보자가이드
