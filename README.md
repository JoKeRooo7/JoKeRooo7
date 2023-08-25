<!DOCTYPE html>
<html>
<head>
<style>
  @keyframes shine {
    0% {
      background-position: 0 0;
    }
    100% {
      background-position: 100% 0;
    }
  }

  .glowing-text {
    font-size: 24px;
    font-weight: bold;
    background: linear-gradient(to right, violet, deepskyblue);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    animation: shine 5s linear infinite;
  }
</style>
</head>
<body>
  <div class="glowing-text">Hey, I'm Renal</div>
</body>
</html>