theme.css
og background: https://i.imgur.com/0TtyZL7.png

https://i.imgur.com/AByByvb.jpeg


rintyuus/testing, line 21 js


 document.addEventListener("DOMContentLoaded", function () {
        var ball = document.createElement("div");
        ball.style.width = "50px";
        ball.style.height = "50px";
        ball.style.backgroundColor = "red";
        ball.style.borderRadius = "50%";
        ball.style.position = "absolute";
        ball.style.top = "0px";
        ball.style.left = "0px";
        document.body.appendChild(ball);

        var ballX = 0;
        var ballY = 0;
        var ballSpeedX = 10;
        var ballSpeedY = 10;

        function animate() {
          ballX += ballSpeedX;
          ballY += ballSpeedY;
          if (ballX > window.innerWidth - 50) {
            ballSpeedX = -ballSpeedX;
          }
          if (ballX < 0) {
            ballSpeedX = -ballSpeedX;
          }
          if (ballY > window.innerHeight - 50) {
            ballSpeedY = -ballSpeedY;
          }
          if (ballY < 0) {
            ballSpeedY = -ballSpeedY;
          }
          ball.style.left = ballX + "px";
          ball.style.top = ballY + "px";
          requestAnimationFrame(animate);
        }

        animate();
      });
    </script>
    <script>
      var box = document.createElement("div");
      box.style.width = "50px";
      box.style.height = "50px";
      box.style.backgroundColor = "blue";
      box.style.position = "absolute";
      box.style.top = "0px";
      box.style.left = "0px";
      document.body.appendChild(box);
      var boxX = 0;
      var boxY = 0;
      var boxSpeedX = 10;
      var boxSpeedY = 10;
      function animateBox() {
        boxX += boxSpeedX;
        boxY += boxSpeedY;
        if (boxX > window.innerWidth - 50) {
          boxSpeedX = -boxSpeedX;
        }
        if (boxX < 0) {
          boxSpeedX = -boxSpeedX;
        }
        if (boxY > window.innerHeight - 50) {
          boxSpeedY = -boxSpeedY;
        }
        if (boxY < 0) {
          boxSpeedY = -boxSpeedY;
        }
        box.style.left = boxX + "px";
        box.style.top = boxY + "px";
        requestAnimationFrame(animateBox);
      }
      animateBox();