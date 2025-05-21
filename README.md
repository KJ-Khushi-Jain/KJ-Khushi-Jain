

<!--
**KJ-Khushi-Jain/KJ-Khushi-Jain** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Happy to see a Visitor on My GitHub Account!!!
## Hi there 👋

![Visitor Count]![Profile Visits](https://img.shields.io/endpoint?url=https://yasinkalkan.com/api/githubvisitorstats/track/?user=KJ-Khushi-Jain)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Visitor Counter - Digital Clock Style</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');

    body {
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      background-color: #000;
    }

    .digital-counter {
      font-family: 'Orbitron', monospace;
      color: #00ff00;
      font-size: 5rem;
      background: #111;
      padding: 20px 40px;
      border-radius: 10px;
      box-shadow: 0 0 20px #0f0;
    }
  </style>
</head>
<body>

<div class="digital-counter" id="visitorCount">000000</div>

<script>
  async function fetchVisitorCount() {
    try {
      const response = await fetch('https://yasinkalkan.com/api/githubvisitorstats/track/?user=KJ-Khushi-Jain');
      const data = await response.json();
      const count = data.value.toString().padStart(6, '0'); // Always 6 digits
      document.getElementById('visitorCount').textContent = count;
    } catch (error) {
      console.error('Failed to fetch visitor count:', error);
    }
  }

  // Fetch on load
  fetchVisitorCount();
</script>

</body>
</html>



<p align=center><a href="https://github.com/avinal/Profile-Readme-WakaTime/blob/master/LICENSE"><img src="https://img.shields.io/github/license/avinal/Profile-Readme-WakaTime" alt="License"></a> <a href="https://github.com/avinal/Profile-Readme-WakaTime/releases"><img src="https://img.shields.io/github/v/release/avinal/Profile-Readme-WakaTime" alt="Releases"></a> <a href="https://github.com/avinal/lark"><img src="https://img.shields.io/badge/uses-avinal%2Flark-blueviolet"></a> <img src="https://github.com/avinal/avinal/workflows/Build%20Graph/badge.svg" alt="Build"> <img src="https://wakatime.com/badge/github/avinal/Profile-Readme-WakaTime.svg" alt="Time Tracked"> <a href="https://github.com/avinal/Profile-Readme-WakaTime/discussions"><img src="https://img.shields.io/badge/QnA-Discussions-blueviolet"></a></p>

## My WakaTime Coding Activity

<img src="https://github.com/KJ-Khushi-Jain/KJ-Khushi_Jain/blob/main/images/stat.svg" alt="Khushi's WakaTime Activity"/>

[![Khushi Jain's GitHub stats:](https://github-readme-stats.vercel.app/api?username=KJ-Khushi-Jain&show_icons=true&theme=transparent)](https://github.com/KJ-Khushi-Jain)

[![GitHub Streak](https://streak-stats.demolab.com/?user=KJ-Khushi-Jain&theme=transparent)](https://github.com/KJ-Khushi-Jain)
