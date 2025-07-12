<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>สุขสันต์วันเกิด</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      font-family: 'Prompt', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .container {
      text-align: center;
      color: #fff;
      animation: popin 1s ease-out forwards;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }
    p {
      font-size: 1.5em;
      margin: 0 2em;
    }
    .boom {
      font-size: 4em;
      color: #fffa65;
      animation: boomAnim 1s ease forwards;
    }
    @keyframes boomAnim {
      0% { transform: scale(0.1); opacity: 0; }
      60% { transform: scale(1.3); opacity: 1; }
      100% { transform: scale(1); }
    }
    @keyframes popin {
      from { transform: scale(0); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="boom">🎉💥 BOOM! 💥🎉</div>
    <h1>สุขสันต์วันเกิดนะพี่!!! 🎂🎈</h1>
    <p>วันนี้เป็นวันของพี่ ขอให้ทุกวินาทีเต็มไปด้วยรอยยิ้ม เสียงหัวเราะ และความสุขล้นๆ 💖<br>
    ขอให้มีแต่สิ่งดีๆ เข้ามา มีคนรักเยอะๆ รวมถึงคนแอบรักก็ด้วย อิอิ 😘<br>
    ขอให้ปีนี้เป็นปีที่เจ๋งที่สุดในชีวิตเลย!</p>
    <p>✨ กินเค้กให้อร่อย เที่ยวให้สนุก นอนให้เต็มอิ่ม<br>
    แต่ที่สำคัญ... อย่าลืมว่ามีคนคนหนึ่งอวยพรอยู่ตรงนี้เสมอ :)</p>
    <p style="margin-top: 1em; font-size: 1.8em;">รักนะเว้ย! 🎉🎂🎁</p>
  </div>
</body>
</html>
