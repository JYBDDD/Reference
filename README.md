# Reference
설명 참고용

1. API 설명
  - API는 응용 프로그램에서 사용할 수 있도록, 운영 체제 혹은 프로그래밍 언어게 제공하는 인터페이스(규격)
  참고 - https://steemit.com/kr/@yahweh87/it-api
  
 2. Regex(Regular Expression) 설명
  참고 - https://github.com/dream-ellie/regex
  참고 - 연습용사이트 : https://regexone.com/
  
 3. 메모리 프로파일링 (유니티)
  참고 - https://youtu.be/d_0uDfNEOk8
  
 4. 딥링크 : 어느 웹사이트에서 이동하였는지 확인하는 것? (추가 내용 필요) //////////////////////////////
	-> Airbrige(에어브릿지)  SDK 로그 출력 작업
  
 5. 크로스 플랫폼 네이티브 플러그인  
  참고-> http://wiki.hash.kr/index.php/%ED%81%AC%EB%A1%9C%EC%8A%A4_%ED%94%8C%EB%9E%AB%ED%8F%BC
 
 6. 벨리데이션 : 
  실행순서 ->
    1. 클라이언트에서 Request로 요청사항을 넘긴후 해당 요청사항이 맞는 정보인지 체크
    2. Request 에서 요청사항이 맞다면 벨리데이션으로 값 전달
    3. 벨리데이션이 받은 값을 결과값을 만들수있도록 값을 (결과값 만들고 체크하는 곳)으로 넘겨주고 값체크, 결과값 생성
    4. 결과값 생성이 되었다면 Java 서버로 값 전달
    5. Java 서버에서 값 체크후 이상이 없다면 클라이언트로 값 전달
  
