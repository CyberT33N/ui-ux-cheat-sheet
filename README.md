# UI/UX Cheat Sheet








# UI

<br><br>

## Animations
- https://gsap.com/
- animejs







<br><br>
<br><br>


## Ideas

<details><summary>Click to expand..</summary>
  
# Public Websites that look good
- https://clerk.com/
  
<br><br>

### Fully websites
- https://recent.design/
- https://www.supahero.io/ **HOT**

<br><br>

### Elements
- https://calltoinspiration.com/ **HOT**


</details>

















<br><br>
<br><br>
___
___
<br><br>
<br><br>

## 3d
[spline](https://spline.design/)https://spline.design/

## No code
- webflow











<br><br>
<br><br>
___
___
<br><br>
<br><br>

# 🧰 Sammlung von Web-Elementen und Design-Ressourcen

<details><summary>💡 Klick zum Aufklappen - Eine kuratierte Liste von Code-Snippets, UI-Elementen und Design-Ressourcen</summary>

Eine kuratierte Liste von Code-Snippets, UI-Elementen und Design-Ressourcen, die Ihnen bei der Entwicklung helfen können.

---
## 🚀 Grundlagen & Inspiration

### 🎨 Material Design

| Ressource | Link |
|---|---|
| Bootstrap 4 Collection | [Bootstrap 4 Collection](https://codepen.io/mdbootstrap/pen/LRNZBz) |

### 🌐 Komplexe Webseiten Beispiele

| Ressource | Link |
|---|---|
| Website 1 | [Website 1](https://codepen.io/veronicadev/details/YYvjzO) |
| Website 2 | [Website 2](https://codepen.io/team/webflow/pen/pvydKd) |

---
## 📧 E-Mail Templates

### ✉️ Grundlagen HTML E-Mail

| Plattform | Ressource | Link |
|---|---|---|
| Gmail | How to send HTML email via Gmail | [How to send HTML email via Gmail](https://www.youtube.com/watch?v=MsMSqhMlfao) |
| AppScript | How to send HTML email via AppScript | [How to send HTML email via AppScript](https://codegena.com/send-mail-merge-html-emails-using-google-appscripts/) |
| **AppScript Code Snippet:** |  |  |
|  |  ```javascript
    function myFunction(){

      // html email
      var htmlEmailBody = HtmlService.createTemplateFromFile('html-template-name');

      // email title
      var subject = "sample title..";

      // this must be set or .sendEmail will not work. You can insert your own email address to get a copy of the email or just let it blank. Alternative you can delete bcc and just the emailAddress value to send 1 email only.
      var emailAddress = "";

      // same like emailAddress this must be set aswell. You can just keep it blank and use htmlBody for your html email. Alternative delete htmlBody and use normalBody for plain text email instead.
      var normalBody = "";

      // find any file with this name on your gdrive. If not found email will not be sended..
      var file = DriveApp.getFilesByName('resume_en.pdf');


      if (file.hasNext()) {
        MailApp.sendEmail(emailAddress, subject, normalBody, {
          name: "Dennis Demand",
          attachments: [file.next().getAs(MimeType.PDF)],
          htmlBody: htmlEmailBody.evaluate().getContent(),
          bcc: 'sample1@gmail.com,sample2@web.de'
        });
      }
    }
    ``` |  |

### ⚙️ CSS/HTML Kompatibilität in E-Mails

| Ressource | Link |
|---|---|
| Can I email | [Can I email](https://www.caniemail.com) |

### 📱 Responsive E-Mail Templates

| Kategorie | Ressource | Link |
|---|---|---|
| **🔥 Hot & Tested** | Multi-layer ★ **HOT** - TESTED | [Multi-layer ★ **HOT** - TESTED](https://codepen.io/rodriguezcommaj/pen/RNPzwr) |
|  | Multi-layer ★ **HOT** ★ | [Multi-layer ★ **HOT** ★](https://codepen.io/Mestika/pen/bEerrv) |
|  | Multi-layer ★ **HOT** - TESTED | [Multi-layer ★ **HOT** - TESTED](https://codepen.io/brucej/pen/BjdwVj) |
|  | Material Design Multi-layer ★ **HOT** - Doesn't work real emails..★ | [Material Design Multi-layer ★ **HOT** - Doesn't work real emails..★](https://codepen.io/luong-quynh/pen/agBMbg) |
|  | Product offer ★ **HOT** ★ | [Product offer ★ **HOT** ★](https://codepen.io/reallygoodemails/pen/OMqpmN) |
|  | Multi-layer ★ **HOT** - TESTED | [Multi-layer ★ **HOT** - TESTED](https://codepen.io/maizzle/pen/WYjyvg) |
| Standard | Responsive 1 | [Responsive 1](https://codepen.io/rickygipson/pen/Aouhi) |
|  | Responsive 2 | [Responsive 2](https://codepen.io/zavoloklom/pen/qEVqzx) |
|  | Responsive 3 | [Responsive 3](https://github.com/konsav/email-templates/) |
|  | Responsive 4 | [Responsive 4](https://codepen.io/raybeezdesign/pen/pHlLG) |
|  | Responsive 5 | [Responsive 5](https://codepen.io/RyanHallMedia/pen/qRXBKW) |
|  | Responsive layout | [Responsive layout](https://codepen.io/beeeees/pen/JEDms) |
|  | Multi-layer | [Multi-layer](https://codepen.io/reallygoodemails/pen/ZWqOBz) |
| Small & Clean  | Small clean 1 | [Small clean 1](https://codepen.io/koca/pen/vjzyad) |
|  | Small clean 2 | [Small clean 2](https://codepen.io/shift-tech/pen/eMdePP) |
|  | Small clean 3 | [Small clean 3](https://codepen.io/denner-rondinely/pen/qwdywa) |
|  | Small clean 4 | [Small clean 4](https://codepen.io/dvomaks/pen/xedjBp) |
|  | Small clean 5 | [Small clean 5](https://codepen.io/darcyturk/pen/XxdVbv) |
|  | Small clean 6 | [Small clean 6](https://codepen.io/mtthlbg/pen/KVWggg) |
|  | Small clean 7 | [Small clean 7](https://codepen.io/MarcoZani/details/aRNQmQ) |
|  | Clean 1 | [Clean 1](https://codepen.io/koolkamalkishor/pen/ZEbgyrj) |
|  | Clean card with bg | [Clean card with bg](https://codepen.io/faudau/pen/zJombX) |
|  | Clean card 2 | [Clean card 2](https://codepen.io/saurya3579/pen/poJKdWP) |
|  | Clean 3 | [Clean 3](https://codepen.io/visionarymarketer/pen/rLqZqx) |
| Andere | Animated? | [Animated?](https://codepen.io/reallygoodemails/pen/yJagbN) |
| | Transition image | [Transition image](https://codepen.io/Romaric_aboule/pen/gOpywgG) |
| | Image transition | [Image transition](https://codepen.io/Mr_Rahul_Tiwari/pen/Wqzqpd) |
| | Clean big image | [Clean big image](https://codepen.io/reallygoodemails/pen/ELoOvj) |
| | Material Design | [Material Design](https://codepen.io/judecodes/pen/YBdMLZ) |

---
## 🧱 Layout Elemente

<details><summary>🖼️ Bild-Gitter</summary>

| Ressource | Link |
|---|---|
| Grid 1 | [Grid 1](https://codepen.io/dtab428/pen/bRwMeq) |
| Grid 2 | [Grid 2](https://codepen.io/JohnRiordan/details/Xbjwqe) |
| Grid 3 | [Grid 3](https://codepen.io/tstoik/pen/qZEZJp) |
| Grid 4 | [Grid 4](https://codepen.io/team/keyframers/pen/EzMyQe) |

</details>

<details><summary>🗂️ Tab-Navigation</summary>

| Ressource | Link |
|---|---|
| Tabs 1 | [Tabs 1](https://codepen.io/RGonyeau/pen/Mvrzxx) |
| Tabs 2 | [Tabs 2](https://codepen.io/jdniki/pen/PzZERJ) |
| Tabs 3 | [Tabs 3](https://codepen.io/ejsado/pen/gPVgVv) |
| Tabs 4 | [Tabs 4](https://codepen.io/creativetim/pen/EgVBXa) |
| Tabs 5 | [Tabs 5](https://codepen.io/Danil89/pen/ONBoyG) |
| Vertical Tabs | [Vertical Tabs](https://codepen.io/juliepark/pen/pLMxoP) |
| Fullscreen Slideshow Tabs | [Fullscreen Slideshow Tabs](https://codepen.io/pbutcher/pen/yLLKbNo) |
| Fullscreen Boxes Tabs | [Fullscreen Boxes Tabs](https://codepen.io/dtab428/pen/yYJKma) |
| Fullscreen Tabs | [Fullscreen Tabs](https://codepen.io/team/webflow/pen/dPeVaG) |
| Swipe Tabs | [Swipe Tabs](https://codepen.io/federico/pen/mRovqE) |
| Tabs 6 | [Tabs 6](https://codepen.io/sean_codes/pen/QpoQMR) |
| Tabs 7 | [Tabs 7](https://codepen.io/interstellar/pen/qaRJwm) |

</details>

<details><summary> 🎢 Slider</summary>

| Ressource | Link |
|---|---|
| Gradient Slider | [Gradient Slider](https://codepen.io/egrucza/pen/LEoOQZ) |

</details>

<details><summary> 🗄️ Sidebar</summary>

| Ressource | Link |
|---|---|
| Sidebar 1 | [Sidebar 1](https://codepen.io/azouaoui-med/pen/wpBadb) |

</details>

---
## 🕹️ Interaktive Elemente

<details><summary>✒️ Text-Effekte</summary>

| Ressource | Link |
|---|---|
| Shimmer Effect | [Shimmer Effect](https://codepen.io/redouglas/pen/gobsm) |
| Multiple Shadows | [Multiple Shadows](https://codepen.io/tommyho/pen/abejXMb) |

</details>

<details><summary>🖼️ Lightbox</summary>

| Ressource | Link |
|---|---|
| Lightbox 1 | [Lightbox 1](https://codepen.io/ezra_siton/pen/XNpJaX) |
| PhotoSwipe | [PhotoSwipe](https://photoswipe.com/) |
| nanogallery2 | [nanogallery2](https://nanogallery2.nanostudio.org/) |
| glightbox | [glightbox](https://biati-digital.github.io/glightbox/) |
| simplelightbox | [simplelightbox](https://simplelightbox.com/) |
| Lightgallery Plugin (commercial) | [Lightgallery Plugin (commercial)](https://codepen.io/sachinchoolur/pen/QjLNMM) |
| Single Image 1 | [Single Image 1](https://codepen.io/gschier/pen/HCoqh) |
| Single Image 2 | [Single Image 2](https://codepen.io/ongtiffany/pen/BoOeQV) |
| Gallery 1 | [Gallery 1](https://codepen.io/nsom/pen/VbqLew) |
| Animated Gallery | [Animated Gallery](https://codepen.io/designcouch/pen/DEkcf) |
| Gallery 2 | [Gallery 2](https://codepen.io/svelts/pen/VYxPWW) |
| Grid Gallery with animation to center | [Grid Gallery with animation to center](https://codepen.io/ademilter/pen/ByLwwV) |

</details>

<details><summary>⏱️ Easing</summary>

| Ressource | Link |
|---|---|
| Easing Cheat Sheet | [Easing Cheat Sheet](https://easings.net/) |
| animejs | [animejs](https://animejs.com/documentation/#pennerFunctions) |

</details>

<details><summary>🎵 Musik Player</summary>

| Ressource | Link |
|---|---|
| Music Player 1 | [Music Player 1](https://codepen.io/ecemgo/pen/vYPadZz) |

</details>

<details><summary> 📧 Kontaktformular</summary>

| Ressource | Link |
|---|---|
| Contact Form 1 | [Contact Form 1](https://codepen.io/jq/pen/rVVQXz) |
| Contact Form 2 | [Contact Form 2](https://codepen.io/rickyeckhardt/pen/rNVOrBL) |
| Animation in envelope 1 | [Animation in envelope 1](https://codepen.io/permanentinc/pen/muFxK) |
| Animation in envelope 2 | [Animation in envelope 2](https://codepen.io/asmaa-mohammed/pen/mmVaLE) |
| Contact Form 3 | [Contact Form 3](https://codepen.io/superguru/pen/aGJHA) |
| Contact Form 4 | [Contact Form 4](https://codepen.io/krisantuswanandi/pen/KxrgeZ) |
| Contact Form 5 | [Contact Form 5](https://codepen.io/mayurelbhar/pen/OPbZmy) |
| Contact Form 6 | [Contact Form 6](https://codepen.io/tutsplus/pen/ZNWQje) |
| Contact Form 7 | [Contact Form 7](https://codepen.io/melawire/pen/pGFvs) |
| Contact Form 8 | [Contact Form 8](https://codepen.io/lolwtf/pen/amVPYN) |
| Contact Form 9 | [Contact Form 9](https://codepen.io/sdras/pen/LEorev) |

</details>

<details><summary> 🚧 Fehlerseiten</summary>

| Kategorie | Ressource | Link |
|---|---|---|
| ### 403 (Forbidden) Error Page | Typing Console | [Typing Console](https://codepen.io/leenalavanya/pen/RYqvgK) |
| | Perspective | [Perspective](https://codepen.io/pgalor/pen/dqQqqx) |
| ### 404 (Not Found) Error Page | Lost Astronaut | [Lost Astronaut](https://codepen.io/eroxburgh/pen/zYYyEPg) |
| | Jungle | [Jungle](https://codepen.io/uiswarup/pen/dyoyLOp) |
| ### 500 (Internal Server) Error Page | 500 Error Page | [500 Error Page](https://codepen.io/Souleste/pen/QWLxPPr) |

</details>

<details><summary>👆 Hover Effekte</summary>

| Ressource | Link |
|---|---|
| Hover Plugin | [Hover Plugin](https://github.com/IanLunn/Hover) |

</details>

<details><summary> ℹ️ UserAgent Infos</summary>

| Ressource | Link |
|---|---|
| UserAgent Database | [UserAgent Database](https://developers.whatismybrowser.com/useragents/explore/operating_platform/) |

</details>

<details><summary> ⚛️ Partikel Effekte</summary>

| Ressource | Link |
|---|---|
| WebGL Particle Animation | [WebGL Particle Animation](https://codepen.io/kenjiSpecial/pen/vELOrM) |

</details>

<details><summary> 📊 Tabellen</summary>

| Ressource | Link |
|---|---|
| Table 1 | [Table 1](https://codepen.io/heypablete/pen/qdIsm) |

</details>

<details><summary> 🔎 JSON Viewer</summary>

| Ressource | Link |
|---|---|
| JSON Viewer | [JSON Viewer](http://jsonmaker.com/) |

</details>

<details><summary> 🖱️ Maus Cursor</summary>

| Ressource | Link |
|---|---|
| CSS Cursors Guide | [CSS Cursors Guide](https://css-tricks.com/using-css-cursors/) |
| All available cursors | [All available cursors](https://codepen.io/chriscoyier/pen/uCwfB) |
| Animation following cursor | [Animation following cursor](https://codepen.io/tamm/pen/LIFam) |
| Sticky Cursor **HOT** | [Sticky Cursor **HOT**](https://codepen.io/dev_loop/pen/abxJMxL) |

</details>
<details><summary>🖱️ Maus Cursor SVG Collection</summary>

| Ressource | Link |
|---|---|
| SVG Collection | [SVG Collection](https://mega.nz/file/y3pUUCZS#NPEm6f00U2VLweB0BXLL5yf5BUU53Ndd4f0b-TvW534) |

</details>

<details><summary> 🔄 Ladeanzeigen (Spinner)</summary>

| Ressource | Link |
|---|---|
| loading.io | [loading.io](https://loading.io/) |
| Spinner 1 | [Spinner 1](https://codepen.io/ahmadbassamemran/pen/bXRPdr) |
| Spinner 2 | [Spinner 2](https://codepen.io/akhil_001/pen/YqBZgL) |
| SpinKit | [SpinKit](https://tobiasahlin.com/spinkit/) |
| Windows 10 Spinner | [Windows 10 Spinner](https://codepen.io/jenning/pen/rrkBbq) |
| Spinner 3 | [Spinner 3](https://codepen.io/Godwin/pen/eWBzNX) |
| Big Circle 3d effect | [Big Circle 3d effect](https://codepen.io/mattbhenley/pen/gQgVxG) |
| Loader | [Loader](https://codepen.io/PicturElements/pen/ZOwkwv) |
| Atom Loader | [Atom Loader](https://codepen.io/dmsanchez86/details/WxRovR) |
| Google Loader | [Google Loader](https://codepen.io/AmineMohamed/pen/JZxyYm) |
| Spinner 4 **HOT** | [Spinner 4 **HOT**](https://codepen.io/grssam/details/nZyxQN) |

</details>

---
## ✨ Animationen & Effekte

<details><summary> 💫 SVG Animationen</summary>

| Ressource | Link |
|---|---|
| Lava Lamp | [Lava Lamp](https://codepen.io/lukesmetham/pen/yJVwVr) |
| Developer with notebook | [Developer with notebook](https://codepen.io/jeanoliveira/pen/ObWYmY) |

</details>

<details><summary>📝 SVG Animationen (Text)</summary>

| Ressource | Link |
|---|---|
| Text Animation 1 | [Text Animation 1](https://codepen.io/codecollective/pen/NqqENm) |
| Text Animation 2 | [Text Animation 2](https://codepen.io/gzmiraz/pen/XmqWWx) |
| Text Animation 3 | [Text Animation 3](https://codepen.io/mellis84/pen/JpVZNw) |

</details>

<details><summary> 📜 Scroll Animation</summary>

| Ressource | Link |
|---|---|
| Scroll Animation | [Scroll Animation](https://codepen.io/GreenXIII/pen/VKbNWV) |

</details>

<details><summary> 🔲 Border Animation</summary>

| Ressource | Link |
|---|---|
| Border Animation 1 | [Border Animation 1](https://codepen.io/Rplus/pen/lEDBj) |
| Border Animation 2 | [Border Animation 2](https://codepen.io/uiswarup/pen/RBByzW) |
| Border Animation 3 | [Border Animation 3](https://codepen.io/littlesnippets/pen/oLajBa) |
| Gradient Border | [Gradient Border](https://codepen.io/mike-schultz/pen/NgQvGO) |
| Border Animation 4 **HOT** | [Border Animation 4 **HOT**](https://codepen.io/pineappleSyrup/pen/gNdERJ) |
| Border Animation 5 **HOT** | [Border Animation 5 **HOT**](https://codepen.io/ZachSaucier/pen/nMRbQN) |
| Border Animation 6 **HOT** | [Border Animation 6 **HOT**](https://codepen.io/Huhtamaki/pen/GPzwPY) |

</details>

<details><summary> ✍️ Text Animation</summary>

| Ressource | Link |
|---|---|
| Text Animation 1 | [Text Animation 1](https://codepen.io/team/keyframers/pen/vYNyWwQ) |
| Text Animation 2 | [Text Animation 2](https://codepen.io/KaioRocha/pen/YoEVvZ) |

</details>

<details><summary> 🎬 Anime.js</summary>

| Ressource | Link |
|---|---|
| Animated Letters | [Animated Letters](https://tobiasahlin.com/moving-letters/) |
| Staggering | [Staggering](https://codepen.io/juliangarnier/pen/XvjWvx) |
| Login Box | [Login Box](https://codepen.io/ainalem/pen/EQXjOR) |
| Submit Button | [Submit Button](https://codepen.io/andrewmillen/pen/MoKLob) |
| Animated Hand Signature | [Animated Hand Signature](https://codepen.io/mellis84/pen/JpVZNw) |

</details>

<details><summary> 📦 Animierte Objekte</summary>

| Ressource | Link |
|---|---|
| Animation Plugin | [Animation Plugin](https://animate.style/) |

</details>

<details><summary> ⌨️ Typing Animation</summary>

| Ressource | Link |
|---|---|
| Typing animation | [Typing animation](https://codepen.io/Zhouzi/pen/JoRazP) |

</details>

---
## 🔘 Buttons & Eingabe Elemente

<details><summary> 🔘 Allgemeine Buttons</summary>

| Ressource | Link |
|---|---|
| 3D Flip Glitch Buttons | [3D Flip Glitch Buttons](https://codepen.io/cybert33n/pen/yXwZVx) |
| Button.css | [Button.css](https://codepen.io/kevinfan23/pen/BKbWxP) |
| Sci-fi Button | [Sci-fi Button](https://codepen.io/jeromefarnum/details/VLjxvW) |
| Hold to Verify Button | [Hold to Verify Button](https://codepen.io/aaroniker/pen/WNNWQbM) |
| Button transition with 2 buttons | [Button transition with 2 buttons](https://codepen.io/montechristos/pen/EPvOwJ) |
| Pulsing animated **HOT** | [Pulsing animated **HOT**](https://codepen.io/emileaublet/pen/PNvNma) |
| Call button **HOT** | [Call button **HOT**](https://codepen.io/get-web/pen/bGdVOWq) |
| General button **HOT** | [General button **HOT**](https://codepen.io/simeydotme/pen/ZEgJoXB) |
| Pixel Canvas **HOT** | [Pixel Canvas **HOT**](https://ryanmulligan.dev/blog/pixel-canvas/) |
| Github Repo | [Github Repo](https://github.com/hexagoncircle/pixel-canvas) |

</details>

<details><summary> 🌗 Dark/white Mode Button</summary>

| Ressource | Link |
|---|---|
| Dark/white Mode **HOT** | [Dark/white Mode **HOT**](https://codepen.io/jh3y/pen/ByBjxrW) |

</details>

<details><summary> 📝 Text Verifizierung</summary>

| Ressource | Link |
|---|---|
| Text Verification 1 | [Text Verification 1](https://codepen.io/AlikinVV/pen/WLpRdg) |

</details>

<details><summary> ✅ Erfolgs Button</summary>

| Ressource | Link |
|---|---|
| Confetti Button | [Confetti Button](https://codepen.io/aaroniker/pen/bGVGNrV) |
| With Loading | [With Loading](https://codepen.io/eliortabeka/pen/xOrQZA) |
| Success Button 1 | [Success Button 1](https://codepen.io/colinhorn/pen/KXjYXr) |
| Success Button 2 | [Success Button 2](https://codepen.io/guywald/details/AXwKqP) |
| Success Button 3 | [Success Button 3](https://codepen.io/keenanpayne/details/YmKKer) |
| Success Button 4 | [Success Button 4](https://codepen.io/ky0suke/pen/xwzNzp) |

</details>

<details><summary> 🗑️ Löschen Button</summary>

| Ressource | Link |
|---|---|
| Delete Button 1 | [Delete Button 1](https://codepen.io/estrepitos/pen/JAtKr) |

</details>

<details><summary> ❌ Schließen Button</summary>

| Ressource | Link |
|---|---|
| Animated Close Buttons | [Animated Close Buttons](https://codepen.io/JonasBadalic/pen/MYaMBz) |

</details>

<details><summary> 🚀 Veröffentlichen Button</summary>

| Ressource | Link |
|---|---|
| Hold to Verify | [Hold to Verify](https://codepen.io/aaroniker/pen/BayaBpV) |

</details>

<details><summary> ⬇️ Download Button</summary>

| Ressource | Link |
|---|---|
| Download Button 1 | [Download Button 1](https://codepen.io/aaroniker/pen/yRdoYN) |
| Download Button 2 | [Download Button 2](https://codepen.io/lalit-mohan/pen/rrEzLp) |
| Download Button 3 | [Download Button 3](https://codepen.io/thereyzer/pen/JqLdLr) |
| Download Button 4 | [Download Button 4](https://codepen.io/aaroniker/pen/vYEmery) |
| Download Button 5 | [Download Button 5](https://codepen.io/aaroniker/pen/KjJQER) |

</details>

<details><summary> 🛒 In den Warenkorb Button</summary>

| Ressource | Link |
|---|---|
| Add to cart Button | [Add to cart Button](https://codepen.io/aaroniker/pen/QWWXKVP) |

</details>

<details><summary> ✉️ Senden Button</summary>

| Ressource | Link |
|---|---|
| Send Button | [Send Button](https://codepen.io/aaroniker/pen/BajabVN) |

</details>

<details><summary> ✅ Aktivieren Button</summary>

| Ressource | Link |
|---|---|
| Activate Button | [Activate Button](https://codepen.io/aaroniker/pen/ZVOrOZ) |

</details>

<details><summary> ⬆️ Upload Button</summary>

| Ressource | Link |
|---|---|
| Upload Button 1 | [Upload Button 1](https://codepen.io/balapa/pen/VYVedm) |
| With Pause | [With Pause](https://codepen.io/aaroniker/pen/QXxexJ) |

</details>

<details><summary> 🚚 Bestellung aufgeben Button</summary>

| Ressource | Link |
|---|---|
| Animation with truck 1 | [Animation with truck 1](https://codepen.io/aaroniker/pen/eYOVrNa) |
| Animation with truck 2 | [Animation with truck 2](https://codepen.io/aaroniker/pen/oNgPOwo) |

</details>

<details><summary> ☑️ Checkbox</summary>

| Ressource | Link |
|---|---|
| Checkbox 1 | [Checkbox 1](https://codepen.io/alexjoffroy/pen/ORXOmR) |

</details>

---
## 🧭 Navigation & UI

<details><summary> 💬 Chat UI</summary>

| Ressource | Link |
|---|---|
| Chat UI 1 | [Chat UI 1](https://codepen.io/Momciloo/pen/bEdbxY) |

</details>

<details><summary> 🔢 Pagination</summary>

| Ressource | Link |
|---|---|
| Pagination 1 | [Pagination 1](https://codepen.io/hakimel/details/gfIsk) |
| Pagination 2 | [Pagination 2](https://codepen.io/netzzwerg/pen/hfutI) |
| Infinity Pagination | [Infinity Pagination](https://codepen.io/MarioD/pen/OmWaqz) |
| Svg Animated | [Svg Animated](https://codepen.io/chrisgannon/pen/xVOjZq) |
| Morphing Pagination | [Morphing Pagination](https://codepen.io/aaroniker/pen/pojXjrZ) |

</details>

<details><summary> ☰ Menü Bar</summary>

<details><summary> 🍔 Hamburger Menu Animation</summary>

| Ressource | Link |
|---|---|
| Hamburger Menu Animation | [Hamburger Menu Animation](https://codepen.io/ahmadbassamemran/pen/abopOMY) |

</details>

<details><summary> 📱 Menü Bar Mobil</summary>

| Ressource | Link |
|---|---|
| Mobile Menubar 1 | [Mobile Menubar 1](https://codepen.io/7ssan91/pen/dqLmpP) |
| Mobile Menubar 2 | [Mobile Menubar 2](https://codepen.io/raffaele-filiberti/pen/mPQqVW) |
| Mobile Menubar 3 | [Mobile Menubar 3](https://codepen.io/cateelderflower/pen/jwVPGd) |

</details>

<details><summary> 💻 Menü Bar Desktop</summary>

| Ressource | Link |
|---|---|
| Desktop Menubar 1 | [Desktop Menubar 1](https://codepen.io/will627/pen/ehEpA) |
| Desktop Menubar 2 | [Desktop Menubar 2](https://codepen.io/ejsado/pen/gPVgVv) |
| Desktop Menubar 3 | [Desktop Menubar 3](https://codepen.io/littlesnippets/pen/BLjjVX) |
| Desktop Menubar 4 | [Desktop Menubar 4](https://codepen.io/littlesnippets/pen/pjKeyq) |
| Desktop Menubar 5 | [Desktop Menubar 5](https://codepen.io/jordiorriols/pen/OXbYKO) |
| Animated fullscreen | [Animated fullscreen](https://codepen.io/duchailu/pen/evprLy) |
| Fullscreen 1 | [Fullscreen 1](https://codepen.io/fluxus/pen/gPWvZm) |
| Fullscreen 2 | [Fullscreen 2](https://codepen.io/bosworthco/pen/RjBvgw) |
| 3D Dropdown | [3D Dropdown](https://codepen.io/soulwire/pen/EKmwC) |
| Desktop Menubar 6 | [Desktop Menubar 6](https://codepen.io/littlesnippets/pen/gPGvLq) |
| Desktop Menubar 7 | [Desktop Menubar 7](https://codepen.io/yasinburakkalkan/pen/jPaXgb) |
| Desktop Menubar 8 | [Desktop Menubar 8](https://codepen.io/littlesnippets/pen/OMXYaG) |

</details>

<details><summary> 🗄️ Sidebar Menu</summary>

| Ressource | Link |
|---|---|
| Sidebar Menu 1 | [Sidebar Menu 1](https://codepen.io/jcoulterdesign/pen/qdWxEm) |

</details>

</details>

---
## 🎛️ Oberflächen Komponenten

<details><summary> 📊 Prozentanzeige</summary>

| Ressource | Link |
|---|---|
| Animated Circle | [Animated Circle](https://codepen.io/like-a-boss/pen/pgqgKq) |
| Multiple Charts | [Multiple Charts](https://codepen.io/FilipDanic/pen/xbgbaQ) |

</details>

<details><summary> 📃 One Page Design</summary>

| Ressource | Link |
|---|---|
| One Page 1 | [One Page 1](https://codepen.io/Cutcopy/pen/LpBPLe) |

</details>

<details><summary> 🎴 Karten Elemente</summary>

| Ressource | Link |
|---|---|
| Card 2 | [Card 2](https://codepen.io/iMax723/pen/aNKQyE) |
| Card 3 | [Card 3](https://codepen.io/littlesnippets/pen/VvorBN) |
| With flip | [With flip](https://codepen.io/keithpickering/pen/XJeJMv) |
| Profile card 1 | [Profile card 1](https://codepen.io/team/jotform/details/XWmqoMp) |
| Profile card 2 | [Profile card 2](https://codepen.io/littlesnippets/pen/VvOwbw) |
| Nice Border | [Nice Border](https://codepen.io/HugoGiraudel/pen/FBbDd) |
| 3d flip | [3d flip](https://codepen.io/kharrop/pen/zBjBLx) |
| Multilayer with animation | [Multilayer with animation](https://codepen.io/jebbles/pen/MKoYya) |
| Responsive card slider | [Responsive card slider](https://codepen.io/JavaScriptJunkie/pen/WgRBxw) |
| Gradient **HOT** | [Gradient **HOT**](https://codepen.io/kristen17/pen/NPKrxBd) |
| Gradien Border **HOT** | [Gradien Border **HOT**](https://codepen.io/jh3y/pen/WNmQXyE) |

</details>

<details><summary> 🪟 Popup</summary>

| Ressource | Link |
|---|---|
| Popup 1 | [Popup 1](https://codepen.io/melnik909/pen/QModrM) |

</details>

<details><summary> 🔔 Erfolgsmeldungen</summary>

| Ressource | Link |
|---|---|
| Modal Box animated | [Modal Box animated](https://codepen.io/hynden/pen/qlsJy) |
| Success 1 | [Success 1](https://codepen.io/souporserious/pen/MwmXdg) |
| Success 2 | [Success 2](https://codepen.io/ethanthompson/pen/vpWOmN) |
| Modal Box not animated | [Modal Box not animated](https://codepen.io/iheartkode/pen/yJBBZZ) |
| Success 3 | [Success 3](https://codepen.io/wallaceho/details/vxLbRO) |
| Success 4 | [Success 4](https://codepen.io/sawyer22/pen/bdOoGX) |
| Success 5 | [Success 5](https://codepen.io/InaCarine/pen/RJoepK) |
| Success 6 | [Success 6](https://codepen.io/zhangshupi88/pen/zvWEMm) |
| Success 7 | [Success 7](https://codepen.io/petsto/pen/XaZRGZ) |
| Envelope | [Envelope](https://codepen.io/HamishMW/pen/XJogMg) |

</details>

<details><summary> ⚠️ Erfolgsmeldungen & Fehler</summary>

| Ressource | Link |
|---|---|
| Animated characters | [Animated characters](https://codepen.io/juliepark/pen/vjMOKQ) |
| Tooltips 1 | [Tooltips 1](https://codepen.io/veronicadev/pen/LrZaov) |
| Success & Error 1 | [Success & Error 1](https://codepen.io/MariamSalloum/pen/PBxKzd) |
| Tooltips 2 | [Tooltips 2](https://codepen.io/prallen/details/AsECw) |

</details>

<details><summary> 🗣️ Testimonials</summary>

| Ressource | Link |
|---|---|
| Slider 1 | [Slider 1](https://codepen.io/shamim539/pen/GZPZBp) |
| Slider 2 | [Slider 2](https://codepen.io/Aashima/pen/WdQQMr) |
| Static 1 | [Static 1](https://codepen.io/littlesnippets/pen/EVLJVa) |
| Static 2 | [Static 2](https://codepen.io/littlesnippets/pen/yejzvR) |
| Static 3 | [Static 3](https://codepen.io/littlesnippets/pen/yOvZPV) |
| Static 4 | [Static 4](https://codepen.io/littlesnippets/pen/QjXVrV) |

</details>

---
## 🖼️ Bild Elemente

<details><summary> 🎠 Bild Karussell</summary>

| Ressource | Link |
|---|---|
| Owl Carousel Plugin | [Owl Carousel Plugin](https://owlcarousel2.github.io/OwlCarousel2/) |
| Carousel 1 | [Carousel 1](https://codepen.io/ccallen001/pen/bEYByd) |
| 3D Carousel | [3D Carousel](https://codepen.io/iamdavid/details/CDluy) |
| Carousel 2 | [Carousel 2](https://codepen.io/lmgonzalves/details/djEgmv) |
| Fullscreen vertical | [Fullscreen vertical](https://codepen.io/mxbck/pen/ERNwBy) |
| Fullscreen 1 | [Fullscreen 1](https://codepen.io/Alca/pen/VByeJd) |
| Fullscreen vertical image distortion | [Fullscreen vertical image distortion](https://codepen.io/ashthornton/details/KRQbMO) |
| Fullscreen 2 | [Fullscreen 2](https://codepen.io/lmgonzalves/pen/djEgmv) |

</details>

<details><summary> 🏞️ Bilder Galerien</summary>

| Ressource | Link |
|---|---|
| Gallery 1 | [Gallery 1](https://codepen.io/andata/pen/pEyAGj) |
| Responsive Vertical Scrolling Parallax Gallery **HOT** | [Responsive Vertical Scrolling Parallax Gallery **HOT**](https://codepen.io/noirsociety/pen/NWJvgZg) |

</details>

<details><summary> 📸 Bild Übergänge</summary>

| Ressource | Link |
|---|---|
| Image Transitions 1 | [Image Transitions 1](https://codepen.io/sfi0zy/pen/OQOExE) |

</details>

---
## 🏢 Logo & Social Media

<details><summary> 🏢 Logos</summary>

| Ressource | Link |
|---|---|
| Logo 1 | [Logo 1](https://codepen.io/mkmueller/pen/dCEhA) |
| Orbit Logo | [Orbit Logo](https://codepen.io/guerreiro/pen/obhzc) |
| Free Vector logos with backlink | [Free Vector logos with backlink](https://www.freepik.com/search?format=search&page=2&query=search+engine) |
| Free Vector logos with backlink 2 | [Free Vector logos with backlink 2](pngtree.com) |

</details>

<details><summary> 🌐 Social Media Links</summary>

| Ressource | Link |
|---|---|
| Social Media 1 | [Social Media 1](https://codepen.io/nouribram/pen/WNQzoOd) |
| Social Media 2 | [Social Media 2](https://codepen.io/daniel_wolf/pen/mJRmaQ) |
| Social Media 3 | [Social Media 3](https://codepen.io/FrankieDoodie/pen/dqmKrb) |
| 3D Cubes with Hover | [3D Cubes with Hover](https://codepen.io/gabriellewee/pen/Qdpgwx) |
| Hover with tooltip | [Hover with tooltip](https://codepen.io/kieranfivestars/pen/gbOWbM) |

</details>

---
## 🔮 3D & Hintergrund

<details><summary> ✨ 3D</summary>

| Ressource | Link |
|---|---|
| Card with mouse follow | [Card with mouse follow](https://codepen.io/lembitk/pen/EVmqmY) |
| 3D 1 | [3D 1](https://codepen.io/yotman/pen/VEzXJp) |
| Image Carousel | [Image Carousel](https://codepen.io/hoanghien0410/pen/MMPaqm) |
| Glassomorphic logo | [Glassomorphic logo](https://codepen.io/konstantindenerz/pen/VwoEJqP) |
| Three.js cards | [Three.js cards](https://codepen.io/smcnally000/pen/eYqXWyJ) |

</details>

<details><summary> 🌄 Hintergründe</summary>

| Ressource | Link |
|---|---|
| Background Generator | [Background Generator](https://loading.io/background/) |
| Bridge with clouds | coming soon |
| Desert sun goes down svg | [Desert sun goes down svg](https://codepen.io/Unleashed-Design/pen/VNpjrW) |
| Gradient Collections | [Gradient Collections](https://uigradients.com/#Mystic) |
| Animated Background | [Animated Background](https://codepen.io/juliangarnier/pen/ZeEpgd) |
| Background Color Change | [Background Color Change](https://codepen.io/alexzaworski/pen/mEkvAG) |
| Background 1 | [Background 1](https://codepen.io/matth12377/pen/gwXBGy) |
| Animated Stars | [Animated Stars](https://codepen.io/shinkeo/pen/XgRqeR) |
| Parallax triangle figure | [Parallax triangle figure](https://codepen.io/semenchenko/pen/JpXVgG) |
| Parallax Mouse follow with stars bg | [Parallax Mouse follow with stars bg](https://codepen.io/ybprogrammer/pen/PGNBXJ) |
| Animated waves | [Animated waves](https://codepen.io/miguelog/pen/amoWgy) |
| Endless horizontal Loop of Image | [Endless horizontal Loop of Image](https://codepen.io/asfarmed/pen/cfslr) |
| Moving circles and squares | [Moving circles and squares](https://codepen.io/tokyoweb/pen/ZjdYVj) |
| Waves bottom | [Waves bottom](https://codepen.io/abelhancock/pen/aKxmLY) |
| Moving Logos on servers | [Moving Logos on servers](https://codepen.io/koshik-ojha/pen/LXzXyx) |
| Moving Circles | [Moving Circles](https://codepen.io/Nathanmc4pg/pen/GdKLdY) |
| Solar System | [Solar System](https://codepen.io/kowlor/pen/ZYYQoy) |
| Spread | [Spread](https://codepen.io/roboshoes/pen/ydipI) |
| Animated Person | [Animated Person](https://codepen.io/yahiarefaiea/pen/xyNWQq) |
| Animated stars fall down from sky | [Animated stars fall down from sky](https://codepen.io/chriscourses/pen/PzONKR) |
| Planet bg | [Planet bg](https://codepen.io/carsonf92/pen/pNWGXG) |
| Planet bg v2 | [Planet bg v2](https://codepen.io/MoodyBoles/pen/KVodmp) |
| Three.js mutating field | [Three.js mutating field](https://codepen.io/Samsy/pen/emWppX) |
| POV moving hills ride | [POV moving hills ride](https://codepen.io/ykob/pen/aBrjaR) |
| Infinite Falling Illusion | WebGL Shader **HOT** | [Infinite Falling Illusion | WebGL Shader **HOT**](https://codepen.io/pjkarlik/pen/mybEwjG) |

</details>

<details><summary> 🌐 WebGL Hintergründe</summary>

| Ressource | Link |
|---|---|
| WebGL Fluid Simulation | [WebGL Fluid Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) |
| Vanta.js **HOT** | [Vanta.js **HOT**](https://www.vantajs.com/?effect=trunk) |

</details>

<details><summary> 🎨 Canvas Hintergründe</summary>

| Ressource | Link |
|---|---|
| AmbientCanvasBackgrounds | [AmbientCanvasBackgrounds](https://github.com/crnacura/AmbientCanvasBackgrounds?tab=readme-ov-file) |

</details>

<details><summary> 🖼️ Hintergrund Bilder (cc0)</summary>

| Ressource | Link |
|---|---|
| Developer on bench | [Developer on bench](https://pixabay.com/photos/work-workaholic-writer-programmer-1627703/) |

</details>

<details><summary> 🌈 Animierte Gradient Hintergründe</summary>

```css
/* version 1 - multicolor*/
background: grey; /*fallback for older browsers*/
background: linear-gradient(-45deg, #f57f19, #e0366deb, #f57f19, #e0366deb, #195bf573, #000000, #00000073, #000000eb);
background-size: 400% 400%;
-webkit-animation: Gradient 43s ease infinite;
-moz-animation: Gradient 43s ease infinite;
animation: Gradient 43s ease infinite;

/* version 2 - transparent purple */
background: grey; /*fallback for older browsers*/
background: linear-gradient(-45deg, #72307aba, #000000, #000000, #000000, #72307aba, #0000007d, #000000, #000000);
background-size: 400% 400%;
-webkit-animation: Gradient 630s ease infinite;
-moz-animation: Gradient 630s ease infinite;
 animation: Gradient 630s ease infinite;

/*version 3 - grey to blue*/
background: grey; /*fallback for older browsers*/
background: linear-gradient(-45deg, #000000eb, #1d60d2f2, #000000, #383838, #000000f7, #383838);
background-size: 400% 400%;
-webkit-animation: Gradient 120s ease infinite;
-moz-animation: Gradient 120s ease infinite;
animation: Gradient 120s ease infinite;

/* version 4 - orange to purple to yellow - looks good with black bg */
 background: grey; /*fallback for older browsers*/
 background: linear-gradient(-45deg, #ef6706, #e2c70a, #ffc404, #f81a62, #e0366d, #f57f19, #f27a1c);
 background-size: 400% 400%;
 -webkit-animation: Gradient 63s ease infinite;
 -moz-animation: Gradient 63s ease infinite;
 animation: Gradient 63s ease infinite;


@-webkit-keyframes Gradient {
  0% {
    background-position: 0% 50%
  }
  50% {
    background-position: 100% 50%
  }
  100% {
    background-position: 0% 50%
  }
}

@-moz-keyframes Gradient {
  0% {
    background-position: 0% 50%
  }
  50% {
    background-position: 100% 50%
  }
  100% {
    background-position: 0% 50%
  }
}

@keyframes Gradient {
  0% {
    background-position: 0% 50%
  }
  50% {
    background-position: 100% 50%
  }
  100% {
    background-position: 0% 50%
  }
}
```

</details>

<br><br>

## 📝 Formulare & Authentifizierung

<details><summary> 📰 Newsletter</summary>

| Ressource | Link |
|---|---|
| Animation mailbox | [Animation mailbox](https://codepen.io/lerida/pen/BaoRRbp) |
| Newsletter 1 | [Newsletter 1](https://codepen.io/YarivFrd/pen/NXomOV) |

</details>

<details><summary> ⏱️ Timeline</summary>

| Ressource | Link |
|---|---|
| Animated timeline | [Animated timeline](https://codepen.io/vincebrown/pen/BNazqL) |

</details>

<details><summary> 🔑 Anmelden (Sign-in)</summary>

| Ressource | Link |
|---|---|
| Sign-in 1 | [Sign-in 1](https://codepen.io/marcobiedermann/pen/Fybpf) |
| Sign-in 2 | [Sign-in 2](https://codepen.io/mycnlz/details/aNNExj) |
| Sign-in 3 | [Sign-in 3](https://codepen.io/yildirimzlm/pen/aRjOGM) |
| Full page with bg | [Full page with bg](https://codepen.io/carsonf92/pen/pNWGXG) |
| Mobile | [Mobile](https://codepen.io/suez/pen/dPqxoM) |
| Perspective animation | [Perspective animation](https://codepen.io/jcoulterdesign/pen/azepmX) |
| 3D perspective | [3D perspective](https://codepen.io/jenning/pen/RVRYeb) |

</details>

<details><summary> 🔒 Passwort erstellen</summary>

| Ressource | Link |
|---|---|
| Create Password | [Create Password](https://codepen.io/davidkpiano/pen/WKvPBP) |

</details>

<details><summary> ✍️ Registrieren (Sign-up)</summary>

| Ressource | Link |
|---|---|
| Sign-up Button | [Sign-up Button](https://codepen.io/vineethtrv/pen/ZBpebQ) |

</details>

<details><summary> 🔄 Anmelden & Registrieren (Kombiniert)</summary>

| Ressource | Link |
|---|---|
| Sign-in & Sign-up 1 | [Sign-in & Sign-up 1](https://codepen.io/joshsorosky/pen/gaaBoB) |
| Sign-in & Sign-up 2 | [Sign-in & Sign-up 2](https://codepen.io/andytran/pen/GpyKLM) |
| Sign-in & Sign-up 3 | [Sign-in & Sign-up 3](https://codepen.io/hurick/pen/Kyrvrj) |

</details>

</details>

