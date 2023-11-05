# electron-test
js. html. css. json. comeon

electron 연습용.

MFC 를 대체해보자.


about electron 

pros
- UI 만들기 편하다. (MFC에 비해서)
- build 만 해도 설치파일 제공, 알아서 설치하고 바탕화면에 바로가기까지 만들어주니 사용자 입장에서는 굿.

cons
- 간단한 테스트 프로그램을 만들었는데 파일 크기가 너무 크다. 기본 100메가 되는듯? 쓸데없는 파일 줄이는 로직이 있을수도 있으니 이건 일단 보류
- app.asar 에 모든 정보가 다 들어있다. 디컴파일 하니 주석까지 전부 복구된다... (UI & high level 코드는 전부 공개된다고 봐야함)
- 그러면 디스코드나 vs code의 코드도 내가 볼 수 있음.?

중요한거는 c++ 로 dll 작성하고 import 하는거,
이미지를 포인터로 전송 가능한지,
이미지 데이터를 통으로 전송하면 main process 와 renderer process 간의 통신 속도 임.







