## Success of React Environmental Setting
나 선생 강의 따라가는 중인데..중간중간 어려움이 있었지만 일단 그래도 잘 따라왔다.
visual code로 react를 작동시키기위한 환경설정을 한다
먼저 내가 react작업을 할 폴더를 생성시킨다.

1. C드라이브에 React_Project_Tutorial이라는 폴더를 만든다.
2. cmd 창을 열고 경로를 설정 : cd C:\React_Project_Tutorial
3. npm install -g create-react-app
4. create-react-app react_study   <= react_study라는 폴더가 C:\React+Project_Tutorial>react_study로 생성된다.
5. cd react_study  <=경로 설정!!
6. yarn start


----------------------------------------------------------------------------------------------------------------------

C
먼저 Git을 이용하기 위해서는 
1. 운영체제에 맞는 Git program을 다운 받기
2. 명령프롬프트 cmd에 들어간다.
3. git config --global user.name bbonyo
4. git config --golbal user.email sss652456gmail.com
5. 내 컴퓨터 c드라이브에 education이라는 folder를 만들음(작동원리 이해를 위해)
6. cmd에서 cd c:\education경로지정
7. git clone 주소(repository주소) :  이 뒷부분은 github 내 repository에 있는 
   경로주소를 복사해서 입력 : clon 작업은 일종의 download로 이해하라! 즉 github에서 내 컴퓨터로 download!!

------------------------------------------------------------------------------------------------------------------------
8. education 폴더를 확인해보면 github에 있는 내용들이 
   폴더로서 형성되어 있음을 확인
9. 이번에 education>React-Management-Tutoria에 리액트공부.txt라는 
   문서를 만들어서 역으로 github에 올리는 작업
   (React-Management-Tutoria는 github에서 repository만들때
    만든 이름)

10. 리액트공부.txt 라는 파일을 만든 후
11.cmd에서 cd React-Management-Tutoria로 경로를 이동하면
   c:\education>React-Management-Tutoria로 경로가 설정된다.
12. cmd에 'git add 리액트공부.txt' 라고 입력 enter
13. git commit -m "Add Text File[리액트공부.txt]"
     위 명령은 clone을 할 때 마치 snap shot을 찍어 놓은 것과
     같아 project를 수정하거나 할 때 유용하게?이용한다.

14. 마지막으로 'git push'명령을 실행해야 실제 github의 
     repository에 upload된다.

--------------------------------------------------------------
<visual code로 작업한 것들을 github에 올리기 위해서는>
1. visual code좌측 3번째 tree그림 모양 메뉴를 click
2. 변경된 내역들(changes)를 stage에 올린다(Stage All Changes)(+ button click)
3. 그 바로 위 입력창에 commit명령어 입력: Create React Project => commit button click(v그림) 
4. visual code 상단 menu tab에 '터미널 -> 새 터미널' 열고 github의 내가 저장하고싶은
    repositiory의 주소를 붙여널는 작업을 할 것이다.
5. visual code의 terminal창에 다음과 같이 입력한다.
6. git remote add origin 주소(저장하고자 하는 repository주소)
7. git push --set-upstream origin master
8. 한 번 terminal에 이 설정이 끝나고 나면 commit할때 상단의 ***메뉴바를 클릭해서 push를 누르면 된다.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
