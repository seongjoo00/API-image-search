#API 이미지 검색 구현 방법

1. 스크립트에 jquery CDN 추가

2. jquery ajax 검색 examples 스크립트태그 만들어서 복붙

3. https://developers.kakao.com/ daum 검색 개발 가이드

4. Request 확인

curl -v -X GET "https://dapi.kakao.com/v2/search/image" \
--data-urlencode "query=설현" \
-H(headers) "Authorization: KakaoAK kkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkk”

카카오에서 GET 방식을 쓰기 떄문에 method:GET
query:input의 값—> $(#input_search).val();

5. 카카오사이트에서 내 애플리케이션 / 애플리케이션 추가 / REST API키를 kkk쪽에 넣음

5. 브라우저 확인후 개발자도구 열어서 console창에서 오른쪽 클리후 속성들 확인

6. 입력하고 싶은 속성 선택후 .done에 넣음