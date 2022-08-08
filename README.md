# JavaScript
## Notes
> #### 1. JS의 구동 방식의 한계 극복
👉 __defer__ 이용
- JS가 위에서부터 읽어 나가기 때문에 ```<body>```에 넣은 script는 ```<head>```에서 실행 안되지만 defer을 써두면 끝가지 읽고 실행 <br>
  ```
  <head>
    <script src="./hello.js" defer></script>
  </head>
  <body>
    <script src="./hello.js" defer></script>
  </body>
  ```