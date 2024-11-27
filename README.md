# git-clone-troubles
깃랩 데스크탑에 클론에러 나올 시 해결법


Cloging into 'project'...

remote: Repository not found.

fatal: repository 'https://github.com/user/project.git/' not found

라고 에러가 뜨며 클론이 되지 않는다.

 

구글링을 해보니 에러 해결 방법으로 이런 것들이 있었다.

### 1. 오타 체크

클론시 사용한 깃 주소를 브라우저에 입력해서 들어가지는지로 확인해볼 수 있다.

 

### 2. 윈도우 자격 증명 삭제

 제어판>사용자 계정>자격 증명 관리자>windows 자격 증명

으로 가면 일반 자격 증명 란에 여러가지 자격 증명이 있을텐데 여기서 github 관련된 걸 삭제하라고 함. 

git 관련 자격 증명을 삭제하면 clone이 되는 경우가 있음

### 3. 데스크탑 접속
