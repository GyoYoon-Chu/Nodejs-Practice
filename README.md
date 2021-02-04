# Nodejs-Practice

## Nodejs를 이용한 웹 어플리케이션.

-----------------------------------------------------------
http, fs, url 모듈을 이용해봤다.

http.createServer함수를 통해서 app.listen(3000) 포트를 열어주었다.

request 받은 url을 이용하여 queryString에 접근할 수 있었다.

fs모듈을 이용해서 data폴더에 생성되는 파일들의 list를 읽어올 수 있었다. (fs.readdir함수)

fs모듈을 이용해서 data폴더 안에 있는 파일들의 내용을 읽을 수 있었따. (fs.readFile함수)

`${} ` 역따옴표 안에서 ${} 자바스크립트의 변수들을 넣어서 동적으로 데이터를 넣을 수 있었다.

결과적으로 queryString을 통해서 생성된 새로운 url을 a태그의 href로 넣어주는 작업을 해봤다!
