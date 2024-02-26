크롤링 : 자동화된 방법으로 웹을 탐색하는 작업, 여러 개의 인터넷 사이트의 페이지를 수집 분류

axios, chreerio 모듈 사용
# cheerio 함수
load() : html 문자열을 cheerio 객체로 변환 <br>
children() : html selector를 파라미터로 받은 뒤 cheerio 객체에서 선택된 html 문자열에 해당하는 모든 태그를 반환<br>
each() : 콜백 함수를 파라미터로 받아 태그들이 담긴 배열을 순회하면서 콜백 함수를 실행<br>
find() : html selector를 문자열로 받아 해당 태그를 반환<br>
