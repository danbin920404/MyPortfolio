# MyPortfolio

-----

## 문자, 음성 번역과 번역 채팅

- 개발인원 : 2명
- 사용언어 : Swift
- 담당분야 : Firebase 번역 API로 번역 기능 구현, 전체적인 UI 구현, Firebase를 이용 채팅 구현, 문자 번역
- 시연영상 : https://www.youtube.com/watch?v=FzjLj-RyJ_A&t=40s

### 구현 내용

##### 1. 구현 기능

- Firebase MNMLTranslate를 이용한 번역 기능(12가지 언어)
- 문자 번역, 음성 번역
- Firebase를 통한 회원 가입 / 회원 로그인(자동 로그인 기능 포함)
- Firestore를 이용한 실시간 번역 채팅
- UserList 확인 및 Searchbar를 통한 특정 인원 검색

##### 2. 사용 라이브러리 및 프레임워크

- `Firebase/Analytics`, `Firebase/Core`, `Firebase/Auth`, `Firebase/Firestore`: 회원 가입 및 로그인 그리고 실시간 채팅을 하기 위한 Database 사용
- `Firebase/MLNLTranslate`: 번역 API 사용
- `JGProgressHUD`: Data Loading 등에 사용
- `lottie-ios`: 첫 로딩 화면 애니메이션 라이브러리
- `UIKit Framework`: UI 구현
- `AVFoundation Framework`:  Text To Speech 기능 구현
- `Speech Framework`: Speech To Text 기능 구현

##### 3. 개방 주요 특이사항

- No Storyboard, Only Code Development

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/SCTranslationImages/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-15%20%EC%98%A4%ED%9B%84%205.33.15.png" width="100%" height="350">



