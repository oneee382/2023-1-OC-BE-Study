# MVC 패턴이란?
MVC 패턴이란 Model(모델), View(뷰), Controller(컨트롤러)의 앞글자를 따서 이름지어진 디자인 패턴이다.

각 컴포넌트는 아래와 같은 역할을 갖고 있다.



모델(Model):
애플리케이션 데이터만을 포함하고, 데이터 조작하는 로직을 포함하지 않는다.

뷰(View) :
모델(데이터)를 사용자에게 표시한다.

컨트롤러 (Controller):
뷰와 모델 사이에 컨트롤러가 있다.
뷰(또는 다른 외부 소스)에 의해 변경요청된 이벤트들을 감지하고,
이러한 이벤트들에 대한 적절한 로직을 실행한다.

# API와 서버?
API는 여러 프로그램들과 데이터베이스, 그리고 기능들의 상호 통신 방법을 규정하고 도와주는 매개체이다. API는 데이터베이스가 아니지만, 액세스 권한이 있는 앱의 권한 규정과 “서비스 요청”에 따라 데이터나 서비스 기능을 제공하는 메신저 역할을 한다.

# RESTful이란?
- RESTful은 일반적으로 REST라는 아키텍처를 구현하는 웹 서비스를 나타내기 위해 사용되는 용어이다.
- RESTful은 REST를 REST답게 쓰기 위한 방법으로, 누군가가 공식적으로 발표한 것이 아니다.
## RESTful의 목적
- 이해하기 쉽고 사용하기 쉬운 REST API를 만드는 것
- RESTful한 API를 구현하는 근본적인 목적이 성능 향상에 있는 것이 아니라 일관적인 컨벤션을 통한 API의 이해도 및 호환성을 높이는 것이 주 동기이니, 성능이 중요한 상황에서는 굳이 RESTful한 API를 구현할 필요는 없다.
