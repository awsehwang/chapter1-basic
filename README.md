# 깃 계정 전환해서 쓰는법

### 1. 레포지토리에 새로운 계정과 이메일 설정

`git config user.name "<아이디>"`

`git congig user.email "<이메일>"`
<br/><br/>

### 2. 원격 저장소와 연동

`git remote add origin <레포지토리 주소>`
<br/><br/>

### 3. 새로운 계정의 인증토큰 적용

`git git remote set-url origin https://<아이디>:<퍼스널 토큰>@<레포지토리 주소>`
