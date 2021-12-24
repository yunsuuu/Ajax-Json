# Ajax-Json

Ajax란 비동기적(Asynchronous)인 웹 어플리케이션을 제작하기 위한 웹개발 기법으로, 
클라이언트 조작을 단순화하도록 설계된 크로스 플랫폼의 자바스크립트 라이브러리

## 기본구조
$.ajax({
    type:"GET",
    url:"......url",
    success: function(data) {
      ....
    }
});

## 오픈 API
* 사용할 데이터는 영화진흥위원회 오픈 API 홈페이지의 박스오피스 데이터입니다.
