<!-- Matrix Banner -->
<p align="center">
  <img src="https://github.com/azizbekboyxonov/azizbekboyxonov/raw/main/8289995_25336.jpg" width="100%" alt="Matrix Background" />
</p>

<h1 align="center">Azizbek Boyxonov</h1>
<p align="center"><b>Internetdagi maxsus dunyomga xush kelibsiz</b></p>

---

## 🟩 Matrix Rain (JavaScript Code)

> Mana mashhur *Matrix* yomg‘ir animatsiyasi kodini HTML sahifangizga joylab, jonli ko‘rishingiz mumkin.

```html
<canvas id="matrixCanvas"></canvas>
<script>
  const canvas = document.getElementById("matrixCanvas");
  const ctx = canvas.getContext("2d");
  canvas.height = window.innerHeight;
  canvas.width = window.innerWidth;
  const katakana = "アイウエオカキクケコサシスセソタチツテト";
  const latin = "ABCDEFGHIJKLMNOPQRSTUVWXYZ123456789@#$%^&*()*&^%";
  const alphabet = katakana + latin;
  const fontSize = 16;
  const columns = canvas.width / fontSize;
  const drops = Array.from({ length: columns }).fill(1);
  function draw() {
    ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
    ctx.fillRect(0, 0, canvas.width, canvas.height);
    ctx.fillStyle = "#0f0";
    ctx.font = fontSize + "px monospace";
    for (let i = 0; i < drops.length; i++) {
      const text = alphabet.charAt(Math.floor(Math.random() * alphabet.length));
      ctx.fillText(text, i * fontSize, drops[i] * fontSize);
      if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
        drops[i] = 0;
      }
      drops[i]++;
    }
  }
  setInterval(draw, 35);
  window.addEventListener('resize', () => {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  });
</script>
```

---

## 👨‍💻 Haqimda qisqacha

- 🏗️ Hozir o‘rganayapman: **Python, Web va Mobil Dasturlash**
- 🚀 Maqsad: Haqiqiy ilovalar yaratish va texnologiya bilan o‘sish
- 🌱 Har kuni yangi texnologiyalarni o‘rganaman
- 💡 Qiziqish: O‘yinlar, algoritmlar va muammolarni yechish

---

## 🚀 Tech Stack & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,flutter,react,html,css,git,github,linux,figma,sqlite,postgres&perline=8" />
</p>

---

## 📂 Top Proyektlarim

<table>
  <tr>
    <td align="center">
      <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=320&q=80" width="120"><br>
      <a href="https://github.com/azizbekboyxonov/ai-chatbot"><b>AI Chatbot</b></a>
    </td>
    <td align="center">
      <img src="https://images.unsplash.com/photo-1453928582365-b6ad33cbcf64?auto=format&fit=crop&w=320&q=80" width="120"><br>
      <a href="https://github.com/azizbekboyxonov/flutter-notes-app"><b>Flutter Notes</b></a>
    </td>
    <td align="center">
      <img src="https://images.unsplash.com/photo-1482062364825-616fd23b8fc1?auto=format&fit=crop&w=320&q=80" width="120"><br>
      <a href="https://github.com/azizbekboyxonov/fastapi-starter"><b>FastAPI Starter</b></a>
    </td>
  </tr>
</table>

---

## 📈 GitHub Statistika

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=azizbekboyxonov&show_icons=true&theme=tokyonight&hide_border=true" width="47%">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=azizbekboyxonov&theme=tokyonight_duo&hide_border=true" width="47%">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=azizbekboyxonov&layout=compact&theme=tokyonight&hide_border=true&hide=html,css" width="52%" />
</p>

---

## 💬 Aloqa

<p>
  <a href="mailto:azizbekboyxonov13092008@gmail.com">
    <img src="https://img.shields.io/badge/Email-azizbekboyxonov13092008@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white">
  </a>
  <a href="https://t.me/boyxonovv1">
    <img src="https://img.shields.io/badge/Telegram-@boyxonovv1-229ED9?style=flat-square&logo=telegram">
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3a8dde,6de195&height=90&section=footer&text=Rahmat%20tashrifingiz%20uchun!%20👋&fontSize=27&fontColor=fff" />
</p>
