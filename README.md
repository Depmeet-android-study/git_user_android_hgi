# git_user_android_hgi

#### 사용기술
- Kotlin
- MVVM
- Flow
- Retrofit2
- Room
- Paging3 With Room
- Compose? (Not Yet <- ComposeView로 현재 대체)
- Jetpack Navigation
- Version Catalogs (gradle to Kotlin DSL)

#### 패키지 구조
- app : android app 모듈
- data : Data Layer (데이터 관련 <- Remote & Local)
- domain : Domain Layer (비즈니스 로직 관련 <- 순수 자바 & 코틀린 모듈)
- presentation : Presentation Layer (View관련 <- View, ViewModel등)
