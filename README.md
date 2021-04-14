# MyloginStudy-01
koa로 node.js써서 로그인 서버 한번 만들어보기 


## intall

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash

node install 

node -v 

npm init

npm install koa

npm install -g eslint

<img width="531" alt="Screen Shot 2021-04-14 at 11 30 54" src="https://user-images.githubusercontent.com/31498653/114645690-ea418000-9d14-11eb-992b-e068e6727efd.png">

## 그외 설정
'''
module.exports = {
    "extends": "standard",
    "rules": {
        "indent": [
            "error",
            4
        ],
        "semi": [
            "error",
            "always"
        ],
        "no-trailing-spaces": 0,
        "keyword-spacing": 0,
        "no-unused-vars": 1,
        "no-multiple-empty-lines": 0,
        "space-before-function-paren": 0,
        "eol-last": 0
    }
};
'''
再起動する

node src -> http://localhost:4000/

## nodemon

$ npm install -g nodemon

자동재시작

$ nodemon --watch src/ src/index.js
