html, body {
    /* The universe takes up all available space */
    width: 100%;
    height: 100vh;
    overflow:hidden;
    
    /* The universe is black */
    background-color: black;
}

#sun {
    position: absolute;
    /* Positions the top-left corner of the image to be *
    /* in the middle of the box */
    top: 50%;
    left: 50%;
    
    /* Play with these numbers to see what it does */
    height: 200px;
    width: 200px;
    margin-top: -100px; 
    margin-left: -100px;
    
    border-color: orange;
    border-width: 1px;
    border-style: solid;
    border-radius: 50%;
    
    box-shadow: 0 0 128px red;
    background: yellow;
}

#earth {
    /* Style your earth */
    position: absolute;
    top: 0;
    left: 50%;
    
    height: 50px;
    width: 50px;
    margin-left: -25px;
    margin-top: -25px;
    
    border-color: blue;
    border-width: 0px;
    border-style: solid;
    border-radius: 50%;
    
    -webkit-box-shadow: 0px 0px 20px 0px rgba(255, 255, 255, 0.5);
-moz-box-shadow:    0px 0px 20px 0px rgba(255, 255, 255, 0.5);
box-shadow:         0px 0px 20px 0px rgba(255, 255, 255, 0.5);
  background: lightblue;
}

#earth-orbit {
    /* For Section #2 */
    position: absolute;
    top: 50%;
    left: 50%;

    width: 650px;
    height: 500px;
    margin-top: -250px;
    margin-left: -250px;

    border-width: 0px;
    border-style: dotted;
    border-color: white;
    border-radius: 50%;
    
    -webkit-animation: spin-right 10s linear infinite;
     -moz-animation: spin-right 10s linear infinite;
      -ms-animation: spin-right 10s linear infinite;
       -o-animation: spin-right 10s linear infinite;
          animation: spin-right 10s linear infinite;
}

#moon {
    /* Style your earth */
    position: absolute;
    top: 0;
    left: 50%;
    
    height: 20px;
    width: 20px;
    margin-left: -25px;
    margin-top: -25px;
    -webkit-border-radius: 15px;
    -moz-border-radius: 15px;
    border-radius: 15px;
    
    -webkit-box-shadow: 1px 1px 16px 0px rgba(255, 255, 255, .6);
-moz-box-shadow:    1px 1px 16px 0px rgba(255, 255, 255, .6);
box-shadow:         1px 1px 16px 0px rgba(255, 255, 255, .6);
  background: lightgray;
}

#moon-orbit {
    /* For Section #2 */
    position: absolute;
    top: 50%;
    left: 50%;

    width: 110px;
    height: 80px;
    margin-top: -285px;
    margin-left: -45px;

    border-width: 0px;
    border-style: dotted;
    border-color: white;
    border-radius: 50%;
    
    -webkit-animation: spin-right 10s linear infinite;
     -moz-animation: spin-right 10s linear infinite;
      -ms-animation: spin-right 10s linear infinite;
       -o-animation: spin-right 10s linear infinite;
          animation: spin-right 10s linear infinite;
}

@-webkit-keyframes spin-right {
  100% {
    -webkit-transform: rotate(360deg);
       -moz-transform: rotate(360deg);
        -ms-transform: rotate(360deg);
         -o-transform: rotate(360deg);
            transform: rotate(360deg);
  }
}

@keyframes spin-right {
  100% {
    -webkit-transform: rotate(360deg);
       -moz-transform: rotate(360deg);
        -ms-transform: rotate(360deg);
         -o-transform: rotate(360deg);
            transform: rotate(360deg);
  }
}

.stars {
  background-color: black;
  width: 100%;
  height: 100%;
  display: block;
}
.star {
    width: 2px;
    height: 2px;
    border-radius: 50%;
    border-top-left-radius: 50%;
    border-top-right-radius: 50%;
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
    background-color: white;
    position: absolute;
    left: 40px;
    top: 40px;
    -webkit-shadow: 0 0 8px 2px rgba(255,255,255,0.6);
    -moz-shadow: 0 0 8px 2px rgba(255,255,255,0.6);
    box-shadow: 0 0 8px 2px rgba(255,255,255,0.6)
    animation: star 4s infinite;
    -webkit-animation: star 4s infinite; /* Safari and Chrome */
}

@keyframes star
{
0% {opacity: 0.2;}
50% {opacity: 1;}
100% {opacity: 0.2;}
}

@-webkit-keyframes star
{
0% {opacity: 0.2;}
50% {opacity: 1;}
100% {opacity: 0.2;}
}
<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffd6e0,25:e7c6ff,50:c8e7ff,75:d0f4de,100:fff1c1&height=85&section=header&animation=twinkling" />
</p>

</div>

<div style="margin-top:-50px;"></div>

<div align="center">

<table cellspacing="0" cellpadding="0">
<tr>
<td width="160">

<img src="https://github.com/phucphan31231023315-lgtm/Up_-nh/blob/main/%E1%BA%A2nh_profile.jpg" width="130"/>

</td>

<td>

<h1 style="margin-bottom:5px;">Hi 👋, I'm Phan Le Hoang Phuc</h1>
<h3 style="margin-top:0;"> Business Analyst Intern | MIS Student at UEH</h3>

</td>
</tr>
</table>

</div>

## 📫 How to reach me:

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/fukwang_) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/phúc-phan-lê-hoàng-5619882b9) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://tiktok.com/@@fusquang) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:phuchoang.path@gmail.com) 

---

## 🌷 About Me
💼 An ambitious and driven individual who is always committed to giving my best and creating meaningful value.
<br>
🎸 Guitar player | ⚽ Goalkeeper | 🎥 Building personal brand on TikTok


---

## 🛠️ Tools & Technologies

### 📊 Business Analysis & Visualization
<p>
  <img src="https://img.shields.io/badge/PowerBI-ffe0ac?style=for-the-badge&logo=powerbi"/>
  <img src="https://img.shields.io/badge/Draw.io-e2f0cb?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PowerDesigner-c7ceea?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Figma-ffdac1?style=for-the-badge&logo=figma"/>
</p>

### 🏢 ERP & CRM Systems
<p>
  <img src="https://img.shields.io/badge/Odoo-b5ead7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Dynamics%20365-a0c4ff?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/SAP-ffd6a5?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Salesforce-ffb7b2?style=for-the-badge&logo=salesforce"/>
  <img src="https://img.shields.io/badge/Bizfly-ff9aa2?style=for-the-badge"/>
</p>

### 📈 Marketing & Customer Tools
<p>
  <img src="https://img.shields.io/badge/Facebook%20Ads-c7ceea?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Google%20Ads-b5ead7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/UCall-ffdac1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Lead%20Generation-ffe0ac?style=for-the-badge"/>
</p>

### 💻 Data & Development
<p>
  <img src="https://img.shields.io/badge/SQL-a0c4ff?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/Google%20Apps%20Script-e2f0cb?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JavaScript-ffd6a5?style=for-the-badge&logo=javascript"/>
  <img src="https://img.shields.io/badge/HTML-ffb7b2?style=for-the-badge&logo=html5"/>
  <img src="https://img.shields.io/badge/CSS-ff9aa2?style=for-the-badge&logo=css3"/>
</p>

### 🌐 Website & Platforms
<p>
  <img src="https://img.shields.io/badge/WordPress-c7ceea?style=for-the-badge&logo=wordpress"/>
  <img src="https://img.shields.io/badge/Microsoft%20Office-b5ead7?style=for-the-badge"/>
</p>

---

## 🏢 Experience
- ERP: Odoo, SAP, Dynamics 365, Salesforce, Bizfly
- Marketing: UCall, Facebook Ads, Google Ads  
- Web: HTML, CSS, JavaScript, WordPress  
- AI: Effective in communicating with AI
- E-commerce: Wholesale and retail processes integrated with Odoo
---

## 📌 Project Experience

### 🚀 Odoo ERP Implementation
- Collected and analyzed business requirements from stakeholders  
- Translated requirements into ERP workflows  
- Supported system configuration and UAT testing  

### 📱 Mobile Application (WikiMoney)
- Gathered user requirements for feature development  
- Performed testing and reported issues to developers  

### ⚙️ CRM & Marketing Optimization
- Managed customer data using Bizfly CRM  
- Supported campaigns with Facebook Ads and lead generation tools  
- Automated reporting using Google Apps Script  

---

## 🏆 Achievements
- 🥉 Top 3 / 114 teams — MIS Talent Competition (NEU)  
- 🏅 Prize B — Scientific Research on Green Transformation  
- 📊 GPA: 3.4 / 4.0  

---

<p align="center">
  💖 <i>Bridging business needs with technology through structured thinking</i>
</p>

<!-- FOOTER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>
</p>

