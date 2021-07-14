# Resume

### 임성태

https://www.fobidlim.com

https://github.com/fobidlim

<fobidlim@gmail.com>

Android application 을 개발하고 있습니다.
ReactiveX(Rx) 기술을 좋아하고, Open Source 에 관심이 많습니다. Clean code를 항상 고민합니다.

---

#### 경력

- **레벨13**, 서울 강남구 (2019년 11월 - 현재)

> 클라이언트 개발 팀장과 룩핀(LookPin) 안드로이드 개발을 담당했습니다.

- **아트온행거**, 프리랜서 (2020년 12월 - 2021년 1월)

> 아트온행거 안드로이드 개발을 담당했습니다.

- **밀랑(주)**, 서울 강남구 (2017년 9월 - 2019년 10월)

> 테이블링(Tabling) 매장용과 사용자용 안드로이드 개발을 담당했습니다.

- **(주)파트너**, 서울 강남구 (2015년 1월 - 2017년 9월, 2년 9개월)

> 그랩(Grap) 안드로이드 개발을 담당했으며, 신세계I&C 블라섬(Blossom) 안드로이드 개발을 담당했습니다.

- **쇼플레이**, 인천 연수구 (2014년 6월 - 2014년 11월, 5개월)

> 쇼팅(Shoting) 안드로이드와 서버 개발을 담당했습니다.

---

### 프로젝트

**Flex Tags**
- 개인 프로젝트
- 기간: 2021년 5월 - 현재
- 사용기술: RxJava2.x, Coroutine, MVVM, LiveData, Room, Firebase ML KIt
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.fobidlim.flextags)
```
Coroutine 사용, MVVM 패턴
DataBinding 사용
Room 사용
Firebase ML Kit(이미지 라벨링) 사용
유사어 검색 API 사용, ML Kit 이미지 라벨 양 확대
카카오 번역 API 사용, 사용자 언어 설정 별로 번역 된 해시태그 제공
```

**아트온행거**
- 프리랜서
- 기간: 2020년 12월 - 2021년 1월
- 사용기술: Kotlin, MVVM, Dagger, RxJava2.x
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.artonhanger.app)
```
RxJava(2.x) 사용, MVVM 패턴
구매자, 유료서비스 구독 판매자, 유료서비스 미구독 판매자 등, 사용자의 권한 상태 관리를 ReactiveX로 구현
```

**짤해**
- 개인 프로젝트
- 기간: 2020년 1월 - 현재
- 사용기술: Kotlin, MVVM, Dagger, RxJava2.x, Room, Firebase Auth, Firebase Realtime Database
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.fobid.zzal)
```
RxJava(2.x) 사용, MVVM 패턴
Google Custom Search API 사용, 짤(meme) 검색
이미지 다운로드 구현
이미지 저장 없이 다른 앱으로 공유 기능
Firebase Auth 사용, 페이스북, 구글, 이메일 로그인 지원
Firebase Realtime Database 사용, 이미지 북마크 데이터 저장
Room 사용
```

**룩핀**
- 레벨13
- 기간: 2019년 11월 - 현재
- 사용기술: Kotlin, MVP, RxJava2.x, Dagger, FCM, Firebase Remote Config, Retrofit, Github Actions, Jenkins
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.mozzet.lookpin)
```
RxJava(2.x), LiveData 사용, MVP, MVVM 패턴
DataBinding 사용
Room 사용

코틀린 100% 마이그레이션

Firebase Remote Config 사용 SDUI 구현

Jenkins, Github Actions로 CI 구축
유닛 테스트, UI 테스트, 린트, 개발 앱 배포 및 플레이스토어 업로드, git commit 내역으로 업데이트 내역 작성 자동화

동료와 코드 스타일 통일을 위해 pre-commit으로 lint 수행

사용자 정보, 리스트 아이템의 상태 관리를 ReactiveX로 구현

Kotlin Reflection 사용, Annotation으로 Presenter 클래스 생성 보일러플레이트 코드 최소화

Dagger 도입, 정적 클래스 및 정적 변수를 일반 클래스 및 일반 변수로 변경하여, 인스턴스가 필요한 시점에 의존성 주입

중복 사용되는 동일한 레이아웃 구조의 뷰를 커스텀뷰로 관리

상품 목록을 나타내는 화면이 많고, 화면에 따라 상품을 LinearLayoutManager.HORIZONTAL, LinearLayoutManager.VERTICAL, GridLayoutManager, StaggeredGridLayoutManager 형태로 달리 보여주는 것을, LayoutManager 마다 공통된 리스트 디자인을 사용하도록, 커스텀뷰와 AttributeSet으로 관리

여러 화면에서 상품 목록 커스텀 RecyclerView가 사용되어, 사용자 이벤트를 동일하게 처리하기 위해 ViewHolder에 MVP 패턴 적용

의존성 최소화를 위해 FlexLayout을 ConstraintLayout Flow로 대체

png만 사용하던 모든 이미지 리소스를 벡터로 변경하여 번들 용량 최적화

Lottie 및 Shimmer로 로딩 UI 구현

웹뷰로 보여주는 상품 상세 이미지를 Expansions Panels로 개발하여, 상품 상세 이미지 상세 보기 UX 개선

카카오톡에만 의존하여 상품을 카카오링크 SDK 를 통해 카카오톡으로만 공유 할 수 있는 기능을, 사용자가 설치 한 모든 앱으로 확대하고, 사용자가 공유하는 대상의 앱을 추적하여, 사용자가 주로 사용하는 앱을 분석
(사용 빈도가 높은 앱에 대한 마케팅 효과 증진)

4.0 리뉴얼의 일부로 디자인 시스템이 도입되어, 다수의 컴포넌트 스타일을 앱 테마로 적용하고, 앱에 전체적으로 일관된 컴포넌트 디자인을 적용
추후 다크모드를 지원하기 위한 준비 개발 포함

모바일(안드로이드&iOS), 프론트엔드로 구성 된 클라이언트 개발 팀장 역임
타 팀과 클라이언트 개발 팀 간 커뮤니케이션 담당
개발 스케줄 및 리소스 관리
클라이언트 개발팀 채용 관리
```

**테이블링 프린터**
- 밀랑(주)
- 기간: 2019년 7월 - 2019년 7월
- 사용기술: Kotlin, MVVM, RxJava2.x, DataBinding, Socket
- 소개:
```
외부 프린터 SDK 사용, 매장용 대기 명단 등록 앱(웹앱)과 소켓 통신으로 프린터 동작
RxJava(2.x) 사용, MVVM 패턴
DataBinding 사용
```

**테이블링(매장용)**
- 밀랑(주)
- 기간: 2017년 9월 - 2019년 10월
- 사용기술: Kotlin, MVVM, RxJava2.x, FCM, Firebase Realmtime Database, Retrofit, Realm
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.mealant.simpletable.admin.app)
```
매장 전용 태블릿 애플리케이션
RxJava(1.x) 사용, MVP 패턴
Firebase Realtime Database 사용, 웹 어드민에서 수정하는 테이블, 층 배치 등의 매장 정보를 안드로이드 앱과 실시간 동기화
테이블링 사용자 앱의 대기 및 예약 데이터를 매장용 앱과 실시간 동기화

FCM 사용, 매장의 전화 통화 상태 푸시(Push) 수신, 발신자의 매장 이용 데이터를 태블릿으로 즉시 안내
```

**테이블링**
- 밀랑(주)
- 기간: 2018년 1월 - 2019년 10월
- 사용기술: Kotlin, MVVM, RxJava2.x, Dagger, DataBinding, Retrofit, Realm, Data Binding, Jenkins
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.mealant.tabling)
```
RxJava(2.x) 사용, MVVM 패턴
DataBinding 사용
FCM 사용
Jenkins 사용, CI 구축, 테스트 및 배포 자동화
```

**Read Only**
- 개인 프로젝트
- 기간: 2017년 2월 - 2017년 5월
- 사용기술: Kotlin, MVVM, Realm, RxJava2.x, Firebase Realmtime Database
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.fobid.readonly)
```
RxJava(2.x) 사용, MVVM 패턴
HTML 태그 파싱
Firebase Auth 사용하여, 페이스북, 구글, 이메일 로그인 지원
Firebase Realtime Database 사용
Realm 사용
```

**LinkableText**
- 개인 프로젝트
- 기간: 2016년 11월 - 2017년 1월
- 사용기술: Java
- 소개:
[<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/fobid/linkable-text-android) [<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.github.fobid.linkabletext.sample)
```
사용자 멘션(@)과 해시태그(#)를 링크 할 수 있는 커스텀뷰 라이브러리
멘션과 해시태그는 사용자 커스텀 정규 표현식 지원
TextView의 기본 링크와 함께 멘션, 해시태그의 클릭 액션을 콜백으로 지원하는 안드로이드 라이브러리
```

**WebViewer**
- 개인 프로젝트
- 기간: 2016년 3월 - 2017년 1월
- 사용기술: Java
- 소개:
[<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/fobid/webviewer-android) [<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=com.tfc.webviewer.sample)
```
인앱 웹뷰 안드로이드 라이브러리
```

**블라섬**
- (주)파트너
- 기간: 2016년 5월 - 2016년 11월
- 사용기술: Java, MVP, RxJava1.x, Retrofit, Realm, MQTT, FCM, ExoPlayer
- 소개:
```
신세계 그룹의 그룹웨어 서비스
RxJava(1.x) 사용, MVP 패턴
Realm 사용
FCM, MQTT 푸시 사용
푸시 데이터로 로컬 DB 동기화 및 화면 갱신
이미지 크롭 개발
```

**그랩**
- (주)파트너
- 기간: 2015년 1월 - 2017년 9월
- 사용기술: Kotlin, MVVM, RxJava2.x, Retrofit, Realm, MQTT, FCM, Jenkins, ExoPlayer
- 소개:
[<img alt="Play Store" src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" />](https://play.google.com/store/apps/details?id=so.partner.app.grap)
```
RxJava(1.x) 사용, MVP 패턴
Realm 사용
FCM, MQTT 푸시 사용
푸시 데이터로 로컬 DB 동기화 및 화면 갱신
네트워크 응답 캐싱
이미지 크롭 개발
디바이스 파일함 개발
GA 사용, 기획팀과 협업
Jenkins 사용, CI 구축, 테스트 및 배포 자동화
MQTT 푸시 모듈 로그 시스템 구축
```

**쇼카운트**
- 쇼플레이
- 기간: 2014년 6월 - 2014년 11월
- 사용기술: PHP, MsSql
- 소개:
```
쇼팅 앱과 연동되는 모바일 머니를 가상 계좌로 입금 및 실제 계좌로 송금
```

**쇼팅**
- 쇼플레이
- 기간: 2014년 6월 - 2014년 11월
- 사용기술: Java, MySql, GCM
- 소개:
```
Java+MySQL 백엔드 구현
안드로이드 애플리케이션
php 프론트엔드 구현

서버는 대한민국 내 주요 도시 별, 사용자 연령대 별 채팅방 생성
안드로이드 GPS 데이터로, 사용자의 위치가 속한 도시, 사용자 연령대의 채팅방으로 자동 입장

GCM 사용, 채팅과 쪽지 구현

PG사로 모바일 머니 충전, 쇼카운트(가상계좌 입출금 서비스) 계정으로 모바일 머니 송금
```
