# MusicMate Media Player Library Release Notes

## 1.0.8 (2017.01.10)
* WebView를 새로 만든 경우에도 getProperty 값을 보존함
* setPlaylist currentIndex < 0인 경우 currentMetadata 함수 오동작 수정
* getVersion 함수 추가

## 1.0.7 (2017.01.09)
* setProperty, getProperty 함수 추가
* currentState, currentMetadata 함수 오동작 수정
* setPlayList 호출시 비어있는 배열인 경우 강제 종료되는 버그 수정

## 1.0.6 (2017.12.21)
* proguard 규칙 추가

## 1.0.5 (2017.12.21)
* MusicMate 3.4.2 변경사항 반영
* compile 환경 변경 - Java 1.7, CompileSDK23, SupportLibrary 24.0.0
* library 버전 변경
  - exoplayer:r2.0.0
  - gson:2.7
  - glide:3.7.0
  - retrofit:2.1.0
  - okhttp:3.4.1
  - okio:1.11.0
  - converter-gson:2.1.0
  - logging-interceptor:3.4.1

## 1.0.4 (2017.12.05)
* MusicMallWebLibrary.logout 호출시 강제 종료되는 버그 수정

## 1.0.3 (2017.11.28)
* getToken 호출시 강제 종료되는 버그 수정
* setToken 호출시 자동로그인하도록 변경

## 1.0.2 (2017.11.28)
* onTicket response 추가
* onPlayResponse code 추가: 4014, 4015, 4033, 4043, 4045

## 1.0.1 (2017.11.22)
* 로그아웃, 데이터 네트워크 확인 Native API 추가
  - MusicMallWebLibrary.logout 함수 추가
  - MusicMallWebLibrary.isAllowCellularNetwork/setAllowCellularNetwork 함수 추가

## 1.0.0 (2017.11.22)
* 최초 배포
* MusicMate 3.4 기준 라이브러리
