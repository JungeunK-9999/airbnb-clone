# Airbnb Clne

니꼴라스 선생님을 따라 django로 에어비엔비를 클론하고 있습니다.
환경설정부터 말을 안 들어먹는 불량 학생이긴 하지만 언젠가는 끝내겠죠 뭐...

#2.5까지는 코드를 쓸 일이 없네용

#2.6 : djano application 만들기

- application name은 복수형이어야 한다.
- app을 이렇게 먼저 만들어놓고 시작할 수도 있구나.

#2.7 : django application의 구조에 대한 간단한 설명

- 장고는 라이브러리가 아니라 프레임워크기 때문에 폴더나 변수명을 함부로 바꿔서는 아니 됩니다.

#3.0
??? 영상에 뜨는 에러가 나한테 안 나는데??? 히이이익
-> 안 난게 아니라 서버 띄운 터미널 확인을 안 한 거였다.
-> dependency 에러가 떠야 하는데 계속 user모델 에러가 떠서 장고 버전의 차이인가 했는데 그냥 오타였음. AUTH_USER_MODEL 을 AUTH_USER_MODELR이라 적음.

#3.1 : 장고 모델을 사용하는 기본적인 방법

- makemigrations와 migrate
- 어드민에 등록
- 아 배고프다

#3.2 : UserModel의 계속

- null, blank : null은 db에서, blank는 form에서

#3.4 : 모델을 어드민에 등록하는 두 가지 방법

- 데코레이터
- admin.site.register()
