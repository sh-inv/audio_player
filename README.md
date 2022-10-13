<br>

## **프로젝트 소개 - 오디오 재생 프로그램 만들기**

```

안녕하세요. 저희는 프리온보딩 2주차 프론트 1팀입니다.

이번 프로젝트는 주식회사 하이에서 제공한 과제인 오디오 관리 프로그램 개발을 진행했습니다.

```

<br>

## 프로젝트 설치 및 실행 방법
### 설치 방법
1. Node.js를 설치해주세요.
```
https://nodejs.org/
```

2. 레포지토리를 클론해주세요. 
```
git clone https://github.com/sh-inv/audio_player
```

3. dependencies를 설치해주세요.
```
npm install
```

### 실행방법
1. 명령어를 통해 server를 실행해주세요. (build vite 사용)
```
npm run dev
```

2. 브라우저에서 하기의 배포주소로 접속해주세요.
📒 배포 주소(https://whimsical-snickerdoodle-2f1ebb.netlify.app/)

## 기능 소개

- 오디오를 녹음하고, 재생하는 등 오디오 파일을 관리하는 프로그램입니다.

- 상단 메뉴바를 통해서 오디오, 녹음 메뉴로 이동가능합니다.

- 오디오 플레이 리스트와 사운드바는 오디오, 녹음 메뉴 둘 다 공통으로 사용합니다.

- UI는 자유롭게 작업하되 반응형을 구현했습니다.

- 오디오 플레이 리스트에서 음악을 선택하면 플레이 컨텐츠 항목에서 파형이 생셩되고 사운드바에서 조절할 수 있습니다.

- 하단에 오디오 파일 다운로드 버튼을 클릭하면 mp3 파일 형식으로 다운로드 됩니다.

- 녹음메뉴에서 마이크 아이콘을 누르면 녹음이 시작됩니다. 이때 녹음 가능 시간을 선택할 수 있습니다.

- 하단에 음성녹음 다운로드 버튼을 클릭하면 다운로드 됩니다.

### 오디오 플레이어
![오디오플레이어1](https://user-images.githubusercontent.com/108816777/195650085-20463dbd-f92f-4f3e-8c04-bcf3cbd800b0.gif)

### 녹음 플레이어
![녹음플레이어1](https://user-images.githubusercontent.com/108816777/195650493-163027ef-6cf2-4425-bd5a-76d0d254ee95.gif)

![ezgif com-gif-maker](https://user-images.githubusercontent.com/108816777/195652100-78d11533-1648-40e8-b392-e36dea7cfa14.gif)
<br>

## 역할 분담

### [이고운] - 오디오 플레이 리스트 및 사운드 바 구현

- 구현한 기능 : react-h5-audio-player 라이브러리 사용하여 사운드 바 구현 및 오디오 플레이 리스트 생성

### [구현]
- 구현한 기능 : wavesurfer.js 사용하여 파형 구형 및 오디오 파일 다운로드 기능 구현

### [유상호]
- 구현한 기능 : 데스크탑 녹음 허용 권한 통해 녹음기능 구현 및 녹음 파일 다운로드 기능 구현

<br>


## **적용 기술**

> React.js, styled-component, axios

<br>


## **팀 노션**

📝[2주차 프론트 1팀](https://www.notion.so/wecode/1-0836f4996a4e4c90b48508414ee81018)
