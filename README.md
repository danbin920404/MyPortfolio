# MyPortfolio

-----

## 1. 문자, 음성 번역과 번역 채팅

- 개발인원 : 2명
- 사용언어 : Swift
- 담당분야 : Firebase 번역 API로 번역 기능 구현, 전체적인 UI 구현, Firebase를 이용 채팅 구현, 문자 번역
- 시연영상 : https://www.youtube.com/watch?v=FzjLj-RyJ_A&t=40s
- 코드 : https://github.com/danbin920404/SCTranslateProj

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

##### 3. 개발 주요 특이사항

- No Storyboard, Only Code Development
- autolayout

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/SCTranslationImages/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-15%20%EC%98%A4%ED%9B%84%205.33.15.png" width="100%" height="350">

-----


## 2. 날씨 정보

- 개발인원 : 1명
- 사용언어 : Swift
- 당담부분 : 전체
- 시연영상 : https://www.youtube.com/watch?v=t14Riv0KT5g&list=PLF1yVh0AvRtjPkPgbOfDg0RkDJxQu6ohm&index=1
- 코드: https://github.com/danbin920404/WeatherApp

### 구현 내용

##### 1. 구현 기능

- OpenWeather API를 이용한 최대 일 주일 구현
- TableVIew를 이용
- 애니메이션 이용

##### 2. 사용 라이브러리 및 프레임워크

- `CoreLocation` 사용
- `SnapKit` 사용

##### 3. 개발 주요 특이사항

- No Storyboard, Only Code Development
- autolayout

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/WeatherAppImage/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-18%20%EC%98%A4%EC%A0%84%201.57.55.png" width="100%" height="350">

-----


## 3. B급장터(못난이상품)

- 개발인원 : 2명
- 기획 : 1명
- 디자이너 : 2명
- 사용언어 : Swift
- 사용 디자인 툴 : 피그마
- 당담부분 : 메인 뷰, 상세페이지, 채팅하기 구현
- B급장터 소개 영상 : https://www.youtube.com/watch?v=y0CsgbG18wc
- 시연영상 : https://www.youtube.com/watch?v=ogybTfhysNA
- 코드 : https://github.com/danbin920404/2020AngelHack

### 구현 내용

##### 1. 구현 기능

- 메인뷰에 collectionView를 사용 및 검색 기능

##### 2. 사용 라이브러리

- 없음

##### 3. 개발 주요 특이사항

- No Storyboard, Only Code Development
- autolayout

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/B%EA%B8%89%EC%9E%A5%ED%84%B0Image/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-18%20%EC%98%A4%EC%A0%84%204.26.24.png" width="100%" height="800">

-----


## 4. 도미노피자 App

- 개발인원 : 1명
- 사용언어 : Swift
- 당담부분 : 모두
- 시연영상 : https://www.youtube.com/watch?v=jz_sIyUgOGQ
- 코드: https://github.com/danbin920404/TIL/tree/master/SwiftProgrammingPractice/Domino

### 구현 내용

##### 1. 구현 기능

- CategoryViewController 에서 logo 는 TableView 의 .tableHeaderView 속성을 활용 하여 구현
- 각 ViewController 에 NavigationController 의 Title 이 보여지도록 구현 DetailViewController 에서 추가된 정보를 WishListViewController 에서 확인할 수 있도
록 구현
- WishListController 에서 ‘목록 지우기’와 ‘주문’ 버튼을 눌렀을때 DetailViewController 에 서도 반영되도록 구현
- WishListController ‘주문’ 버튼을 눌렀을때 AlertController 를 화면과 같이 구현

##### 2. 사용 라이브러리

- 없음

##### 3. 개발 주요 특이사항

- No Storyboard, Only Code Development
- autolayout

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/DominoImages/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-15%20%EC%98%A4%ED%9B%84%206.17.39.png" width="100%" height="800">

-----














