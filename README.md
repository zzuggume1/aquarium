
<meta charset="utf-8">
<html>
  <head>
    <title>내 수조</title>
    <script src="https://aquarium-58de7-default-rtdb.firebaseio.com"></script>
  </head>

  <body>
    <center>
      <h1>민재의 수조</h1>
      <p id="mois"></p>
      <p id="temp"></p>
      <p id="light"></p>

      <button type="button" onclick="ledOnOff()">조명 제어</button>
      <button type="button" onclick="fanOnOff()">팬 제어</button>
    </center>

    <!-- Firebase 정보 가져와서 게이지에 표현하기, 제어용 버튼 클릭 시 Firebase에 데이터 보내기 -->
    <script type="text/javascript" src="firebase.js"> </script>
  </body>
</html>
