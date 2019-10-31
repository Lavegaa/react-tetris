# react-tetris
react와 hooks를 사용해 테트리스 만드는 강좌를 보고 제작했다.  
[강좌 - https://www.youtube.com/watch?v=ZGOaCxX8HIU&t=8334s]  

![tetris](https://user-images.githubusercontent.com/34911173/67923850-606e2780-fbf2-11e9-9598-24d37a0f0903.PNG)

# 빠른시작

## 클론

```
git clone https://github.com/Lavegaa/react-tetris.git
```

```
cd number-game
```

## dependencies 설치

```
npm install
```

or

```
yarn
```

## 시작

```
npm start
```

or

```
yarn start
```
# hooks
## useInterval
강좌에서 주어지는 hook이다. 테트리스 블록이 시간마다 내려가는 것을 도와준다.

## usePlayer
현재 내가 움직이는 block에 관한 hook이다. 회전, 리셋등의 기능이 있다.

## useStage
게임의 판을 그려주는 hook이다. 쌓여진 블록들의 정보도 처리해준다.

# 기타
## tetrominos.js
블록에 대한 정보(모양, 색)를 가지고 있다. randomTetromino함수에서는 key값에 따라 랜덤으로 블록을 생성해준다.


