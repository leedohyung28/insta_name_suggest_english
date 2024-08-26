# Instagram Name Suggestion (Generator) Site

English : https://ignamegenerator.netlify.app/ <br>
Korean : https://instanamesuggest.netlify.app/

<br><br>

## 📖 Introduction
Nickname generating/suggesting homepage for [Instagram](https://www.instagram.com/) newcomers
<br><br>

## ⭐ Suggesting Methods
English Version Site
- Generate with **Full Name (First, Middle, Last)**
- Combine **Birthday** (with Name also)
- Suggest with **Words Combination**
- Generate with **Current Time (Server Time)**
- Suggest with **Foreign Words (French, Italian, Spanish, Heberian)**
- Suggest with **Emoticons**
- **Hitting the Keyboard**

Korean Version Site (Includes all Methods from English Version)
- Generate with **Korean Name**
- Suggest from **Maxim (Words of Wisdom)**

<br><br>

## ⏰ Develop Timeline
2024.01 ~ 2024.02 : Develop & Deploy
2024.02 : Setting SEO
2024.03 ~ : Maintenance and Error Debugging
<br><br>

## 🛠 Develop Tools
### FrontEnd

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">

### BackEnd

<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white">
<img src="https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge&logo=Nodemon&logoColor=white">

<br><br>

## 🎪 Techs
- Use the **DeepL API**, **Express**, and **CloudType** servers to translate the Korean name (nickname) entered by the user into an English nickname using the Translation API on the page.
- To reflect the popularity of hit the keyboard by fist (random) for nicknames, used **HTML Image Maps** to make the keyboard image react to clicks on the keyboard's keyboard keys.
- Using **Bootstrap** for responsive web with screens that work on both mobile and web
- Utilize **Google Search Console** to make the site accessible, improve **SEO** (100 points on LightHouse), publishing the site after sepearate to Korean/English version each.

<br><br>

## 🔥 Problems & Solution
- It was first time utilizing external APIs and cloud servers to me, some integration issues occurred<br>
→ Reduce debugging time with using **Nodemon** instead of **Node** , use **CORS** to troubleshoot web security issues, and connect via reading API documentation<br>

- Reduced performance when using **Database** to fetch information that will be utilized for nicknames (pretty foreign words, birthstones, etc...)<br>
→ Hardcoded informations in the ‘data’ folder to improve speed.
