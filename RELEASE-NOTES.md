# MusicMate Media Player Library Release Notes

## 1.1.1 (2017.04.25)
* bug-379 오류 발생시 Global Player에 재생중으로 표시되는 문제 수정.
* session token 이상시 에러가 2번 발생하는 문제 수정.

## 1.1.0 (2017.03.29)
* MusicMate 3.6 기준으로 HTTP 헤더 형식과 API 서버 주소를 변경함.

## 1.0.13 (2017.03.05)
* 이전곡 버튼의 곡의 처음으로 이동 기능을 재생중이 아닐 때는 동작하지 않도록 변경.
* Global Player logo 이미지의 너비가 긴경우 작게 나오던 문제 수정.

## 1.0.12 (2017.02.09)
* bug-323 재생 목록 편집 후 현재 재생 중인 곡의 재생 정보가 초기화 되던 문제 수정.
* 재생 불가 음원인 경우 오류 메시지를 표시하도록 함.

## 1.0.11 (2017.02.07)
* bug-293 3초이상 플레이 된 곡 정지상태일때 이전곡 선택시 프로그래스 바가 이동하지 않던 문제 수정.
* bug-295 비밀번호 변경시 오동작 수정.
* bug-298 다른 앱으로 인해 음악이 일시 정지된 후 다시 재생되었을 때 일시 중지상태로 표시되던 문제 수정.
* 다른 폰을 사용해 동시에 재생하는 경우 오동작 수정.

## 1.0.10 (2017.01.26)
* repeat -> setRepeat 함수 이름 변경
* shuffle -> setShuffle 함수 이름 변경
* getRepeat, getShuffle 함수 추가
* 일시 중지 상태에서 currentMetadata 여러번 호출시 metadata 응답이 한 번만 발생하던 버그 수정.

## 1.0.9 (2017.01.19)
* 음원 캐시 기능 복원
* MMMediaPlayerConfig.GlobalPlayerIntent 속성 추가
* connecting state가 발생하지 않던 문제 수정

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
