# chat_backend
- express를 기반 채팅 앱 백엔드 서버


## backend create
- express-generator 설치
    ``` sh
    yarn global add express-generator
    ```
- express 프로젝트 생성
    ``` sh
    cd chat
    express --view=pug backend
    ```
- 필요한 패키지 설치
    ``` sh
    cd backend
    yarn add -D mocha
    yarn add cross-env ampqlib
    ```
