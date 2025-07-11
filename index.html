<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Starlink Timers</title>
  <style>
    body {
      font-family: sans-serif;
      background: #111;
      color: #fff;
      margin: 0;
      padding: 2rem;
    }
    h1 {
      text-align: center;
      color: #0ff;
    }
    .user-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .user {
      background: #222;
      border: 2px solid #0ff;
      border-radius: 12px;
      padding: 1rem;
      text-align: center;
      font-size: 1.2rem;
    }
    .name {
      font-weight: bold;
      font-size: 1.4rem;
    }
    .timer {
      color: #0f0;
      font-size: 1.6rem;
      margin-top: 0.5rem;
    }
  </style>
</head>
<body>
  <h1>🌐 Starlink Timers</h1>
  <div class="user-list" id="userList"></div>

  <script>
    const timers = [
      { name: "Ahmed", minutes: 90 },
      { name: "Sarah", minutes: 45 },
      { name: "John", minutes: 60 },
    ];

    const userList = document.getElementById("userList");

    function createTimerElement(user) {
      const userDiv = document.createElement("div");
      userDiv.className = "user";

      const name = document.createElement("div");
      name.className = "name";
      name.textContent = user.name;

      const timer = document.createElement("div");
      timer.className = "timer";
      timer.textContent = formatTime(user.minutes * 60);

      userDiv.appendChild(name);
      userDiv.appendChild(timer);
      userList.appendChild(userDiv);

      const interval = setInterval(() => {
        user.minutes -= 1 / 60;
        if (user.minutes <= 0) {
          timer.textContent = "Time's up! ❌";
          timer.style.color = "#f00";
          clearInterval(interval);
        } else {
          timer.textContent = formatTime(user.minutes * 60);
        }
      }, 1000);
    }

    function formatTime(seconds) {
      const m = Math.floor(seconds / 60);
      const s = Math.floor(seconds % 60);
      return `${m.toString().padStart(2, "0")}:${s.toString().padStart(2, "0")}`;
    }

    timers.forEach(createTimerElement);
  </script>
</body>
</html>
