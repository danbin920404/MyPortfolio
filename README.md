# MyPortfolio

-----

## [경험요약및핵심보유역량]
```
- Swift와 UIKit을 활용한 iOS Application 개발 경험 
- Git을 통한 버전 관리 및 협업 경험 
- AutoLayout
- MVC및MVVM아키텍쳐에 대한 기초지식 보유
- Cocoapods, SPM을 이용한 라이브러리 추가 및 활용 경험
- OPEN API 사용 경험(블로그페이(쇼핑몰), 공공 휴일 데이터 API 등)
- 파이어베이스 경험
- 자료구조에 대한 기초 지식 보유(Stack, Queue, etc...)
- 적극적인 코드 개선 및 코드 리뷰 태도
- 꾸준한 학습과 인내심 그리고 책임감 보유
- 앱스토어에 배포 경험 - 붕세권 -
```

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

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/B%EA%B8%89%EC%9E%A5%ED%84%B0Image/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202020-10-18%20%EC%98%A4%EC%A0%84%204.26.24.png" width="800" height="550">

-----


## 4. 붕세권

- 디자이너 : 1명
- 개발인원 : 1명
- 사용언어 : Swift
- 담당분야 : 모두
- 앱스토어 출시
- 시연영상 : https://youtu.be/6GW7BFGoEao
- 코드 : https://github.com/danbin920404/BungsegwonPortfolio

### 구현 내용

##### 1. 구현 기능

- 네이버맵에서 유저들이 등록한 위치를 확인
- 등록하고 싶은 가게를 등록
- 상세페이지에서 댓글, 찜, 수정 가능
- 마이페이지에서 내가찜한 가게, 내가 등록한 가게, 내가 쓴 댓글 확인 가능 및 삭제 가능
- 개발자에게 이메일 문의 가능
- 로그인 및 닉네임, 닉네임 수정
- 카카오 우편번호 서비스로 위치 검색

##### 2. 사용 라이브러리

- SnapKit
- NMapsMap
- FBSDKLoginKit (페이스북 측에 앱 인증을 안 받아서 일단 보류 - 기능 구현은 완료)
- Firebase/Firestore
- Firebase/Auth
- GoogleSignIn

##### 3. 개발 주요 특이사항

- No Storyboard, Only Code Development
- autolayout

<img src="https://github.com/danbin920404/MyPortfolio/blob/main/BungsegwonImage/Bungsegwon.png">






