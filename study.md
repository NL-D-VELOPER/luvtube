## 1. SET UP

### (1) package.json

프로그래머가 프로젝트 정보를 저장하기 위해 만든 텍스트 파일

- **dependencies** : express가 작동되려면 필요한 패키지.  
  다른 사람의 프로젝트를 공유 받을 때 npm i 를 입력하면 dependencies에 있는 패키지를 다운 받을 수 있음

- **devDependencies** : 개발자에게 필요한 depndencies.

### (2) [babel](https://babeljs.io/)

nodeJS가 이해하지 못하는 최신 자바스크립트 코드를 babel이 컴파일 해줌

- **preset** : babel을 위한 엄청 거대한 플러그인
- [preset-env](https://babeljs.io/docs/babel-preset-env) : 최신 자바스크립트를 쓸 수 있음

### (3) Nodemon

nodemon은 우리가 만든 파일이 수정되는 걸 감시해주는 패키지
