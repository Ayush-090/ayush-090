[ayush_github_profile_v3_impressive.html](https://github.com/user-attachments/files/27176391/ayush_github_profile_v3_impressive.html)

<style>
*{box-sizing:border-box;margin:0;padding:0;}
.root{font-family:var(--font-sans);max-width:680px;padding:1.5rem 0;}

.hero{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:2rem 1.5rem;text-align:center;margin-bottom:1rem;position:relative;overflow:hidden;}
.hero-accent{position:absolute;top:0;left:0;right:0;height:3px;background:#185FA5;}
.av{width:88px;height:88px;border-radius:50%;background:#0C447C;display:flex;align-items:center;justify-content:center;font-size:30px;font-weight:500;color:#B5D4F4;margin:0 auto 14px;}
.hero-name{font-size:24px;font-weight:500;color:var(--color-text-primary);letter-spacing:-0.3px;}
.hero-role{font-size:13px;color:var(--color-text-secondary);margin-top:5px;letter-spacing:0.02em;}
.hero-quote{font-size:13px;color:var(--color-text-secondary);font-style:italic;margin:14px auto 0;max-width:380px;line-height:1.6;font-family:var(--font-serif);}
.badges{display:flex;flex-wrap:wrap;gap:6px;justify-content:center;margin-top:14px;}
.badge{font-size:11px;padding:4px 11px;border-radius:20px;font-weight:500;border:0.5px solid;}
.b-blue{background:#E6F1FB;color:#0C447C;border-color:#85B7EB;}
.b-teal{background:#E1F5EE;color:#085041;border-color:#5DCAA5;}
.b-purple{background:#EEEDFE;color:#3C3489;border-color:#AFA9EC;}
.b-amber{background:#FAEEDA;color:#633806;border-color:#EF9F27;}
.b-coral{background:#FAECE7;color:#712B13;border-color:#F0997B;}
.b-pink{background:#FBEAF0;color:#72243E;border-color:#ED93B1;}
.b-green{background:#EAF3DE;color:#27500A;border-color:#97C459;}

.stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:1rem;}
.stat-c{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:12px 8px;text-align:center;}
.stat-n{font-size:22px;font-weight:500;color:var(--color-text-primary);}
.stat-l{font-size:10px;color:var(--color-text-secondary);margin-top:2px;letter-spacing:0.04em;text-transform:uppercase;}

.sec{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:1rem;}
.sec-hd{display:flex;align-items:center;gap:8px;margin-bottom:14px;}
.sec-icon{width:24px;height:24px;border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:13px;flex-shrink:0;}
.ic-blue{background:#E6F1FB;}
.ic-teal{background:#E1F5EE;}
.ic-purple{background:#EEEDFE;}
.ic-coral{background:#FAECE7;}
.ic-amber{background:#FAEEDA;}
.sec-title{font-size:14px;font-weight:500;color:var(--color-text-primary);}

.stack-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(0,1fr));gap:6px;}
.stack-pill{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:8px 10px;text-align:center;}
.sp-cat{font-size:10px;color:var(--color-text-secondary);text-transform:uppercase;letter-spacing:0.05em;}
.sp-val{font-size:11px;font-weight:500;color:var(--color-text-primary);margin-top:3px;line-height:1.4;}

.proj-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;}
.proj{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:14px;position:relative;overflow:hidden;}
.proj-accent{position:absolute;left:0;top:0;bottom:0;width:3px;}
.pa-blue{background:#185FA5;}
.pa-teal{background:#0F6E56;}
.pa-purple{background:#534AB7;}
.pa-coral{background:#993C1D;}
.proj-inner{padding-left:10px;}
.proj-name{font-size:13px;font-weight:500;color:var(--color-text-primary);}
.proj-sub{font-size:11px;color:var(--color-text-secondary);margin-top:2px;font-style:italic;}
.proj-desc{font-size:12px;color:var(--color-text-secondary);margin-top:6px;line-height:1.55;}
.proj-tags{display:flex;flex-wrap:wrap;gap:4px;margin-top:8px;}
.ptag{font-size:10px;padding:2px 7px;border-radius:20px;background:var(--color-background-secondary);color:var(--color-text-secondary);border:0.5px solid var(--color-border-tertiary);}

.hack-list{display:flex;flex-direction:column;gap:0;}
.hack-row{display:flex;align-items:flex-start;gap:10px;padding:9px 0;border-bottom:0.5px solid var(--color-border-tertiary);}
.hack-row:last-child{border-bottom:none;padding-bottom:0;}
.hack-badge{font-size:10px;font-weight:500;padding:3px 8px;border-radius:20px;white-space:nowrap;flex-shrink:0;margin-top:1px;}
.hb-gold{background:#FAEEDA;color:#633806;border:0.5px solid #EF9F27;}
.hb-green{background:#EAF3DE;color:#27500A;border:0.5px solid #97C459;}
.hb-blue{background:#E6F1FB;color:#0C447C;border:0.5px solid #85B7EB;}
.hb-purple{background:#EEEDFE;color:#3C3489;border:0.5px solid #AFA9EC;}
.hack-txt{font-size:12px;color:var(--color-text-primary);line-height:1.5;}
.hack-sub{font-size:11px;color:var(--color-text-secondary);}

.connect-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:8px;}
.con-card{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-md);padding:10px 12px;display:flex;flex-direction:column;gap:3px;}
.con-platform{font-size:10px;color:var(--color-text-secondary);text-transform:uppercase;letter-spacing:0.05em;}
.con-handle{font-size:12px;font-weight:500;color:var(--color-text-primary);}
.con-card.ig{border-color:#ED93B1;background:#FBEAF0;}
.con-card.ig .con-platform{color:#993556;}
.con-card.ig .con-handle{color:#72243E;}

.copy-btn{margin-top:1rem;width:100%;padding:11px;font-size:14px;font-family:var(--font-sans);cursor:pointer;border-radius:var(--border-radius-md);background:#185FA5;color:#E6F1FB;border:none;font-weight:500;letter-spacing:0.01em;}
.copy-btn:hover{background:#0C447C;}
.copied{background:#0F6E56 !important;}
</style>

<div class="root">

  <div class="hero">
    <div class="hero-accent"></div>
    <div class="av">AB</div>
    <div class="hero-name">Ayush Bhardwaj</div>
    <div class="hero-role">IT Engineering Student &nbsp;·&nbsp; Full-Stack &nbsp;·&nbsp; Flutter &nbsp;·&nbsp; AI/ML &nbsp;·&nbsp; Chandigarh, India</div>
    <div class="hero-quote">"I don't just write code — I build solutions that make a difference."</div>
    <div class="badges">
      <span class="badge b-blue">Full-Stack Dev</span>
      <span class="badge b-purple">Flutter</span>
      <span class="badge b-teal">AI / ML</span>
      <span class="badge b-amber">UI/UX</span>
      <span class="badge b-green">Chandigarh University</span>
      <span class="badge b-coral">Open to Internships</span>
    </div>
  </div>

  <div class="stats-row">
    <div class="stat-c"><div class="stat-n">4</div><div class="stat-l">Projects</div></div>
    <div class="stat-c"><div class="stat-n">3</div><div class="stat-l">Hackathons</div></div>
    <div class="stat-c"><div class="stat-n">5</div><div class="stat-l">Certs</div></div>
    <div class="stat-c"><div class="stat-n">2026</div><div class="stat-l">Active</div></div>
  </div>

  <div class="sec">
    <div class="sec-hd"><div class="sec-icon ic-blue">&#9881;</div><div class="sec-title">Tech stack</div></div>
    <div class="stack-grid">
      <div class="stack-pill"><div class="sp-cat">Languages</div><div class="sp-val">Python · C++ · Java · JS · Dart</div></div>
      <div class="stack-pill"><div class="sp-cat">Web</div><div class="sp-val">HTML · CSS · Express.js</div></div>
      <div class="stack-pill"><div class="sp-cat">AI / ML</div><div class="sp-val">Model Training · Streamlit</div></div>
      <div class="stack-pill"><div class="sp-cat">Mobile</div><div class="sp-val">Flutter · Dart</div></div>
      <div class="stack-pill"><div class="sp-cat">Tools</div><div class="sp-val">Git · GitHub</div></div>
      <div class="stack-pill"><div class="sp-cat">Design</div><div class="sp-val">UI/UX · Figma</div></div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-hd"><div class="sec-icon ic-teal">&#9670;</div><div class="sec-title">Featured projects</div></div>
    <div class="proj-grid">
      <div class="proj">
        <div class="proj-accent pa-blue"></div>
        <div class="proj-inner">
          <div class="proj-name">Sanjeevani</div>
          <div class="proj-sub">Healthcare Web App</div>
          <div class="proj-desc">Full-stack platform delivering accessible medical information with a responsive UI and Express.js backend.</div>
          <div class="proj-tags"><span class="ptag">Express.js</span><span class="ptag">HTML/CSS</span><span class="ptag">Full-Stack</span></div>
        </div>
      </div>
      <div class="proj">
        <div class="proj-accent pa-teal"></div>
        <div class="proj-inner">
          <div class="proj-name">AI Recommendation System</div>
          <div class="proj-sub">ML-Powered Engine</div>
          <div class="proj-desc">Personalised content and music recommendations — end-to-end ML pipeline with an interactive Streamlit UI.</div>
          <div class="proj-tags"><span class="ptag">Python</span><span class="ptag">ML</span><span class="ptag">Streamlit</span></div>
        </div>
      </div>
      <div class="proj">
        <div class="proj-accent pa-purple"></div>
        <div class="proj-inner">
          <div class="proj-name">Ayunetra</div>
          <div class="proj-sub">AI Eye Health Assistant</div>
          <div class="proj-desc">AI-powered vision analysis tool — smart eye health detection using computer vision and machine learning.</div>
          <div class="proj-tags"><span class="ptag">AI/ML</span><span class="ptag">Computer Vision</span><span class="ptag">Python</span></div>
        </div>
      </div>
      <div class="proj">
        <div class="proj-accent pa-coral"></div>
        <div class="proj-inner">
          <div class="proj-name">Ritavi Classes</div>
          <div class="proj-sub">EdTech Platform</div>
          <div class="proj-desc">Online learning platform with a clean student-first UI — making quality education accessible and engaging.</div>
          <div class="proj-tags"><span class="ptag">Web Dev</span><span class="ptag">UI/UX</span><span class="ptag">EdTech</span></div>
        </div>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-hd"><div class="sec-icon ic-amber">&#9733;</div><div class="sec-title">Hackathons & achievements</div></div>
    <div class="hack-list">
      <div class="hack-row">
        <span class="hack-badge hb-gold">IIT Goa</span>
        <div><div class="hack-txt">Hack Overflow Hackathon</div><div class="hack-sub">Competed against top engineering talent nationally</div></div>
      </div>
      <div class="hack-row">
        <span class="hack-badge hb-green">Finalist</span>
        <div><div class="hack-txt">Hack for Green Bharat</div><div class="hack-sub">Sustainability-focused innovation challenge</div></div>
      </div>
      <div class="hack-row">
        <span class="hack-badge hb-blue">Microsoft</span>
        <div><div class="hack-txt">Build for Bharat</div><div class="hack-sub">National-level Microsoft hackathon</div></div>
      </div>
      <div class="hack-row">
        <span class="hack-badge hb-purple">Workshop</span>
        <div><div class="hack-txt">UI/UX Design Workshop</div><div class="hack-sub">Hands-on modern design principles training</div></div>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-hd"><div class="sec-icon ic-purple">&#9654;</div><div class="sec-title">Connect with me</div></div>
    <div class="connect-grid">
      <div class="con-card"><div class="con-platform">GitHub</div><div class="con-handle">Ayush-090</div></div>
      <div class="con-card"><div class="con-platform">LinkedIn</div><div class="con-handle">ayushbhardwaj</div></div>
      <div class="con-card ig"><div class="con-platform">Instagram</div><div class="con-handle">ayushhh._.094</div></div>
      <div class="con-card"><div class="con-platform">Email</div><div class="con-handle">ayushbhardwaj942006</div></div>
    </div>
  </div>

  <button class="copy-btn" id="copyBtn" onclick="copyReadme()">Copy impressive README.md to clipboard</button>
</div>

<script>
function copyReadme(){
const r=`<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=185FA5&height=120&section=header&text=Ayush%20Bhardwaj&fontSize=36&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20%C2%B7%20Flutter%20%C2%B7%20AI%2FML%20%C2%B7%20IT%20Engineering%20Student&descAlignY=58&descSize=14&descColor=B5D4F4" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=185FA5&center=true&vCenter=true&width=500&lines=Building+things+that+matter+%F0%9F%9A%80;Full-Stack+%7C+Flutter+%7C+AI%2FML+Developer;Open+to+Internship+Opportunities!)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayushbhardwaj-bb9bba285)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayush-090)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ayushhh._.094)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushbhardwaj942006@gmail.com)

</div>

---

## 👨‍💻 About Me

> *"I don't just write code — I build solutions that make a difference."*

I'm a passionate **IT Engineering student** at Chandigarh University (2024–2028), deeply invested in building real-world impactful software. From full-stack web apps to AI-powered tools — I love tackling problems that matter.

- 🔭 Currently building: **Ayunetra** (AI Eye Health) & **Ritavi Classes** (EdTech Platform)
- 🌱 Exploring: Advanced AI/ML, Flutter, and modern backend systems
- 💬 Ask me about: Full-Stack Dev, Flutter, Machine Learning, UI/UX
- 📍 Based in: Chandigarh, India
- ⚡ Open to: Internship opportunities

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</div>

---

## 🚀 Featured Projects

<div align="center">
<table>
<tr>
<td width="50%">

### 🏥 Sanjeevani
**Healthcare Web Application**
> Making medical information accessible to everyone.

- Responsive full-stack platform with Express.js backend
- Clean, accessible UI focused on real-world healthcare impact
- Built with usability and empathy at its core

\`Express.js\` \`HTML/CSS\` \`Full-Stack\` \`UI/UX\`

</td>
<td width="50%">

### 🤖 AI Recommendation System
**Personalised ML Engine**
> Smart content & music recommendations powered by ML.

- End-to-end pipeline: preprocessing → training → results
- Interactive Streamlit interface for seamless exploration
- Demonstrates practical AI/ML implementation skills

\`Python\` \`Machine Learning\` \`Streamlit\`

</td>
</tr>
<tr>
<td width="50%">

### 👁️ Ayunetra
**AI Eye Health Assistant**
> Vision care reimagined through artificial intelligence.

- AI-powered eye health analysis using computer vision
- Smart detection and assistance for vision-related concerns
- Bridging healthcare and technology for real impact

\`AI/ML\` \`Computer Vision\` \`Python\` \`Healthcare Tech\`

</td>
<td width="50%">

### 📚 Ritavi Classes
**EdTech Learning Platform**
> Quality education made accessible and engaging.

- Student-first UI for online class access
- Clean, intuitive design for distraction-free learning
- Built to bridge the gap between students and quality content

\`Web Dev\` \`UI/UX\` \`EdTech\` \`Full-Stack\`

</td>
</tr>
</table>
</div>

---

## 🏆 Hackathons & Achievements

| Award | Event | Details |
|:---:|---|---|
| ⚡ | **Hack Overflow — IIT Goa** | Competed against top national engineering talent |
| 🥈 | **Hack for Green Bharat — Finalist** | Sustainability-focused innovation solution |
| 🇮🇳 | **Build for Bharat (Microsoft)** | National-level Microsoft hackathon participant |
| 🎨 | **UI/UX Design Workshop** | Hands-on modern design principles & tools |
| 🐍 | **Programming with Python — Coursera** | Certified Python programmer |

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ayush-090&show_icons=true&theme=github_dark_dimmed&hide_border=true&bg_color=00000000&title_color=378ADD&icon_color=378ADD&text_color=B5D4F4" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush-090&layout=compact&theme=github_dark_dimmed&hide_border=true&bg_color=00000000&title_color=378ADD&text_color=B5D4F4" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Ayush-090&theme=github-dark-blue&hide_border=true&background=00000000&stroke=378ADD&ring=185FA5&fire=D85A30&currStreakLabel=B5D4F4" />
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=185FA5&height=80&section=footer" width="100%"/>
</div>`;
  navigator.clipboard.writeText(r).then(()=>{
    const b=document.getElementById('copyBtn');
    b.textContent='Copied to clipboard!';
    b.classList.add('copied');
    setTimeout(()=>{b.textContent='Copy impressive README.md to clipboard';b.classList.remove('copied');},2500);
  });
}
</script>
