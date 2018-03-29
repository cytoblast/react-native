## Getting Started
1. 설치
npm install -g create-react-native-app

2. 프로젝트 생성
create-react-native-app AwesomeProject

3. 개발 서버 스타트
cd AwesomeProject
npm start

4. 어플로실행 
( Xcode )
brew install node
brew install watchman
npm install -g react-native-cli
react-native init AwesomeProject
cd AwesomeProject
react-native run-ios
( Android )


4. 수정하기
App.js 에서 수정 해보자

5. 시뮬레이터 또는 가상 장치에서 앱 실행하기
npm run android
npm run ios

## Learn the Basics
?? ES2015 (also known as ES6) 
?? JSX
-> Javascript + XML을 합쳐서 탄생한 기존 자바스크립트의 확장 문법
-> 개발자가 자바스크립트 내부에 마크업 코드를 작성해 줄 수 있게 해줍니다. 단순히 XML만 아니라 변수나 프로퍼티의 바인딩 기능도 제공합니다
?? Component
?? render

## Props
매개 변수에 값을 담고 그것을 사용 할 수 있게 하는 용도
변하지 않는 값을 저장

## State
state생성자에서 초기화 한 다음 setState변경하려고 할 때 호출
?? Redux
