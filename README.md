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

# 🧰 Collection of Web Elements and Design Resources

<details><summary>💡 Click to Expand - A curated list of code snippets, UI elements, and design resources</summary>

A curated list of code snippets, UI elements, and design resources to help you with development.

---
## 🚀 Basics & Inspiration

### 🎨 Material Design

| Resource | Link |
|---|---|
| Bootstrap 4 Collection | [Bootstrap 4 Collection](https://codepen.io/mdbootstrap/pen/LRNZBz) |

### 🌐 Complex Website Examples

| Resource | Link |
|---|---|
| Website 1 | [Website 1](https://codepen.io/veronicadev/details/YYvjzO) |
| Website 2 | [Website 2](https://codepen.io/team/webflow/pen/pvydKd) |

---


## 📧 Email Templates

<details><summary>Click to expand..</summary>

### ✉️ Basic HTML Email

| Platform | Resource | Link |
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

### ⚙️ CSS/HTML Compatibility in Emails

| Resource | Link |
|---|---|
| Can I email | [Can I email](https://www.caniemail.com) |









### 📱 Responsive Email Templates

| Category | Resource | Link |
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
| Other | Animated? | [Animated?](https://codepen.io/reallygoodemails/pen/yJagbN) |
| | Transition image | [Transition image](https://codepen.io/Romaric_aboule/pen/gOpywgG) |
| | Image transition | [Image transition](https://codepen.io/Mr_Rahul_Tiwari/pen/Wqzqpd) |
| | Clean big image | [Clean big image](https://codepen.io/reallygoodemails/pen/ELoOvj) |
| | Material Design | [Material Design](https://codepen.io/judecodes/pen/YBdMLZ) |

</details>









---
## 📊 🎨 Design & Styling


<details><summary>🎨 All</summary>

| Resource | Link |
|---|---|
| uiverse **HOT** | [uiverse](https://uiverse.io) |

</details>






<details><summary>🎨 Buttons</summary>

| Resource | Link |
|---|---|
| cssbuttons **HOT** | [cssbuttons](https://cssbuttons.io/) |

</details>




<details><summary>🎨 Neumorphism</summary>

| Resource | Link |
|---|---|
| Neumorphism Generator **HOT** | [Stock](https://neumorphism.io) |

</details>

















---
## 📊 Data Visualization

<details><summary>🎨 Stocks</summary>

| Resource | Link |
|---|---|
| Stock **HOT** | [Stock](https://github.com/aryanvichare/stocks) |

</details>




<details><summary>📊 Zoomable Chart</summary>

| Resource | Link |
|---|---|
| Zoomable Chart **HOT** | [Zoomable Chart](https://github.com/shelwinsunga/zoom-chart-demo) |

</details>




<details><summary>📊 Area Chart</summary>

| Resource | Link |
|---|---|
| Area Chart **HOT** | [Area Chart](https://tremor.so/docs/visualizations/area-chart) |

</details>





<details><summary>📊 Bar Chart</summary>

| Resource | Link |
|---|---|
| Bar Chart | [Bar Chart](https://tremor.so/docs/visualizations/bar-chart) |

</details>

<details><summary>📊 Combo Chart</summary>

| Resource | Link |
|---|---|
| Combo Chart **HOT** | [Combo Chart](https://tremor.so/docs/visualizations/combo-chart) |

</details>

<details><summary>📊 Bar List</summary>

| Resource | Link |
|---|---|
| Bar List | [Bar List](https://tremor.so/docs/visualizations/barlist) |

</details>

<details><summary>📊 Category Bar</summary>

| Resource | Link |
|---|---|
| Category Bar | [Category Bar](https://tremor.so/docs/visualizations/category-bar) |

</details>

<details><summary>📊 Donut Chart</summary>

| Resource | Link |
|---|---|
| Donut Chart | [Donut Chart](https://tremor.so/docs/visualizations/donut-chart) |

</details>

<details><summary>📊 Line Chart</summary>

| Resource | Link |
|---|---|
| Line Chart | [Line Chart](https://tremor.so/docs/visualizations/line-chart) |

</details>

<details><summary>📊 Progress Bar</summary>

| Resource | Link |
|---|---|
| Progress Bar | [Progress Bar](https://tremor.so/docs/visualizations/progress-bar) |

</details>

<details><summary>📊 Progress Circle</summary>

| Resource | Link |
|---|---|
| Progress Circle | [Progress Circle](https://tremor.so/docs/visualizations/progress-circle) |

</details>

<details><summary>📊 Spark Chart</summary>

| Resource | Link |
|---|---|
| Spark Chart | [Spark Chart](https://tremor.so/docs/visualizations/spark-chart) |

</details>


















---
## 🧱 Layout Elements

<details><summary>🖼️ Image Grids</summary>

| Resource | Link |
|---|---|
| Grid 1 **HOT** | [Grid 1](https://codepen.io/dtab428/pen/bRwMeq) |
| Grid 2 | [Grid 2](https://codepen.io/JohnRiordan/details/Xbjwqe) |
| Hexagon Grid | [Hexagon Grid](https://codepen.io/tstoik/pen/qZEZJp) |

</details>

<details><summary>🗂️ Tab Navigation</summary>

| Resource | Link |
|---|---|
| Tabs 1 **HOT** | [Tabs 1](https://codepen.io/RGonyeau/pen/Mvrzxx) |
| Tabs 2 **HOT** | [Tabs 2](https://codepen.io/jdniki/pen/PzZERJ) |
| Tabs 4 **HOT** | [Tabs 4](https://codepen.io/creativetim/pen/EgVBXa) |
| Frosted Glass Gooey Gravity Nav **HOT** | [Frosted Glass Gooey Gravity Nav](https://codepen.io/simeydotme/pen/qEBmggz) |


</details>

<details><summary> 🎢 Slider</summary>

| Resource | Link |
|---|---|
| Gradient Slider | [Gradient Slider](https://codepen.io/egrucza/pen/LEoOQZ) |
| Elastic Slider **HOT**| [Elastic Slider](https://www.reactbits.dev/components/elastic-slider) |

</details>






<details><summary> 🗄️ Sidebar</summary>

| Resource | Link |
|---|---|
| Sidebar 1 | [Sidebar 1](https://codepen.io/azouaoui-med/pen/wpBadb) |

</details>





<details><summary> ➖ Separators & Dividers</summary>

| Resource | Link |
|---|---|
| Seperator 1 **HOT** - shacdn | [ Seperator 1](https://ui.indie-starter.dev/docs/separator#separator) |

</details>
















---
## 🕹️ Interactive Elements



<details><summary>✒️ Text Effects</summary>

| Resource | Link |
|---|---|
| Shimmer Effect | [Shimmer Effect](https://codepen.io/redouglas/pen/gobsm) |
| Multiple Shadows | [Multiple Shadows](https://codepen.io/tommyho/pen/abejXMb) |
| Text Hover Effect **HOT** - shacdn | [Text Hover Effect](https://ui.aceternity.com/components/text-hover-effect) |
| Typewriter Effect **HOT** - shacdn | [Typewriter Effect](https://ui.aceternity.com/components/typewriter-effect) |
| Typing animation | [Typing animation](https://codepen.io/Zhouzi/pen/JoRazP) |
| Animated Shiny Text **HOT** - shacdn | [Animated Shiny Text](https://nyxbui.design/docs/components/animated-shiny-text) |
| Animated Gradient Text - shacdn | [Animated Gradient Text](https://nyxbui.design/docs/components/animated-gradient-text) |
| Blur in **HOT** - shacdn | [Blur in](https://ui.indie-starter.dev/docs/text-animation#blur-in) |
| Text Animate **HOT** | [Text Animate](https://magicui.design/docs/components/text-animate) |
| Line Shadow Text **HOT** | [Line Shadow Text](https://magicui.design/docs/components/line-shadow-text) |
| Animated Shiny Text **HOT** | [Animated Shiny Text](https://magicui.design/docs/components/animated-shiny-text) |
| Aurora Text **HOT** | [Aurora Text](https://magicui.design/docs/components/aurora-text) |
| code driven animation **HOT** | [code driven animation](https://codepen.io/creativeocean/pen/ByBogvj) |
| Animated Gradient Text | [Animated Gradient Text](https://magicui.design/docs/components/animated-gradient-text) |
| Animated Gradient Text #2 | [Animated Gradient Text #2](https://codepen.io/argyleink/pen/vEBmZNw) |








</details>




<details><summary>🖼️ Lightbox</summary>

| Resource | Link |
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
| rolling gallery | [rolling gallery](https://www.reactbits.dev/components/rolling-gallery) |

</details>

<details><summary>⏱️ Easing</summary>

| Resource | Link |
|---|---|
| Easing Cheat Sheet | [Easing Cheat Sheet](https://easings.net/) |
| animejs | [animejs](https://animejs.com/documentation/#pennerFunctions) |

</details>

<details><summary>🎵 Music Player</summary>

| Resource | Link |
|---|---|
| Music Player 1 | [Music Player 1](https://codepen.io/ecemgo/pen/vYPadZz) |

</details>

<details><summary>📧 Contact Form</summary>

| Resource | Link |
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

<details><summary>🚧 Error Pages</summary>

| Category | Resource | Link |
|---|---|---|
| ### 403 (Forbidden) Error Page | Typing Console | [Typing Console](https://codepen.io/leenalavanya/pen/RYqvgK) |
| | Perspective | [Perspective](https://codepen.io/pgalor/pen/dqQqqx) |
| ### 404 (Not Found) Error Page | Lost Astronaut | [Lost Astronaut](https://codepen.io/eroxburgh/pen/zYYyEPg) |
| | Jungle | [Jungle](https://codepen.io/uiswarup/pen/dyoyLOp) |

</details>

<details><summary>👆 Hover Effects</summary>

| Resource | Link |
|---|---|
| Hover Plugin | [Hover Plugin](https://github.com/IanLunn/Hover) |

</details>

<details><summary>ℹ️ UserAgent Infos</summary>

| Resource | Link |
|---|---|
| UserAgent Database | [UserAgent Database](https://developers.whatismybrowser.com/useragents/explore/operating_platform/) |

</details>

<details><summary>⚛️ Particle Effects</summary>

| Resource | Link |
|---|---|
| WebGL Particle Animation | [WebGL Particle Animation](https://codepen.io/kenjiSpecial/pen/vELOrM) |

</details>






<details><summary>📊 Tables</summary>

| Resource | Link |
|---|---|
| Table 1 | [Table 1](https://codepen.io/heypablete/pen/qdIsm) |
| Table 2 **HOT** - shacdn | [Table 1](https://github.com/sadmann7/shadcn-table) |

</details>






<details><summary>🔎 JSON Viewer</summary>

| Resource | Link |
|---|---|
| JSON Viewer | [JSON Viewer](http://jsonmaker.com/) |

</details>





<details><summary>🖱️ Mouse Cursor</summary>

| Resource | Link |
|---|---|
| CSS Cursors Guide | [CSS Cursors Guide](https://css-tricks.com/using-css-cursors/) |
| All available cursors | [All available cursors](https://codepen.io/chriscoyier/pen/uCwfB) |
| Animation following cursor | [Animation following cursor](https://codepen.io/tamm/pen/LIFam) |
| Sticky Cursor **HOT** | [Sticky Cursor **HOT**](https://codepen.io/dev_loop/pen/abxJMxL) |
| Canvas Cursor **HOT** | [Canvas Cursor](https://www.edilozi.pro/docs/components/canvas-cursor) |
| Fluid Cursor **HOT** | [Fluid Cursor](https://www.edilozi.pro/docs/components/fluid-cursor) |
| Ink Cursor **HOT** | [Ink Cursor](https://www.edilozi.pro/docs/components/ink-cursor) |
| Ribbons **HOT** | [Ribbons](https://www.reactbits.dev/animations/ribbons) |
| Blob Cursor **HOT** | [Blob Cursor](https://www.reactbits.dev/animations/blob-cursor) |



</details>






<details><summary>🖱️ Mouse Cursor SVG Collection</summary>

| Resource | Link |
|---|---|
| SVG Collection | [SVG Collection](https://mega.nz/file/y3pUUCZS#NPEm6f00U2VLweB0BXLL5yf5BUU53Ndd4f0b-TvW534) |

</details>





<details><summary>🔄 Loading Skeleton</summary>


| Resource | Link |
|---|---|
| Skeleton #1 **HOT** | [Skeleton #1](https://ui.indie-starter.dev/docs/skeleton#variant-1) |
| Skeleton #2 **HOT** | [Skeleton #2](https://ui.indie-starter.dev/docs/skeleton#variant-2) |


  
</details>









<details><summary>🔄 Loading Indicators (Spinners)</summary>

| Resource | Link |
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
| Dots #1 **HOT** - shacdn | [ Dots #1](https://ui.indie-starter.dev/docs/loader-dots#variant-1) |
| Dots #2 **HOT** - shacdn| [ Dots #2](https://ui.indie-starter.dev/docs/loader-dots#variant-3) |
| Qubes **HOT** | [ Qubes](https://uiverse.io/Nawsome/cold-liger-90) |
| Qubes 2 **HOT** | [ Qubes #2](https://uiverse.io/alexruix/white-cat-50) |
| Music Waves **HOT** | [Music Waves #2](https://uiverse.io/Nadabasuony/cowardly-lionfish-57) |
| Atomic **HOT** | [Music Waves #2](https://uiverse.io/Nawsome/purple-mule-73) |
| Domino **HOT** | [Domino](https://uiverse.io/vikramsinghnegi/swift-penguin-59) |




</details>


















---
## ✨ Animations & Effects

<details><summary>💫 SVG Animations</summary>

| Resource | Link |
|---|---|
| Lava Lamp | [Lava Lamp](https://codepen.io/lukesmetham/pen/yJVwVr) |
| Developer with notebook | [Developer with notebook](https://codepen.io/jeanoliveira/pen/ObWYmY) |

</details>







<details><summary>📝 SVG Animations (Text)</summary>

| Resource | Link |
|---|---|
| Text Animation 1 | [Text Animation 1](https://codepen.io/codecollective/pen/NqqENm) |
| Text Animation 2 | [Text Animation 2](https://codepen.io/gzmiraz/pen/XmqWWx) |
| Text Animation 3 | [Text Animation 3](https://codepen.io/mellis84/pen/JpVZNw) |

</details>







<details><summary>📜 Scroll Animation</summary>

| Resource | Link |
|---|---|
| Scroll Animation | [Scroll Animation](https://codepen.io/GreenXIII/pen/VKbNWV) |
| Tracing Beam **HOT** - shacdn | [https://ui.aceternity.com/components/tracing-beam) |
| Timeline - shacdn | [https://ui.aceternity.com/components/tracing-beam) |
| Container Scroll Animation **HOT** - shacdn | [https://ui.aceternity.com/components/container-scroll-animation) |
| Google Gemini Effect - shacdn | [https://ui.aceternity.com/components/google-gemini-effect) |
| Flying Posters **HOT** | [https://www.reactbits.dev/components/flying-posters) |
| Infiinity Scroll **HOT** | [https://www.reactbits.dev/components/infinite-scroll) |


</details>











<details><summary>🔲 Border Animation</summary>

| Resource | Link |
|---|---|
| Border Animation 1 | [Border Animation 1](https://codepen.io/Rplus/pen/lEDBj) |
| Border Animation 2 | [Border Animation 2](https://codepen.io/uiswarup/pen/RBByzW) |
| Border Animation 3 | [Border Animation 3](https://codepen.io/littlesnippets/pen/oLajBa) |
| Gradient Border | [Gradient Border](https://codepen.io/mike-schultz/pen/NgQvGO) |
| Border Animation 4 **HOT** | [Border Animation 4 **HOT**](https://codepen.io/pineappleSyrup/pen/gNdERJ) |
| Border Animation 5 **HOT** | [Border Animation 5 **HOT**](https://codepen.io/ZachSaucier/pen/nMRbQN) |
| Border Animation 6 **HOT** | [Border Animation 6 **HOT**](https://codepen.io/Huhtamaki/pen/GPzwPY) |
| Hover Border Gradient **HOT** - shacdn | [Hover Border Gradient](https://ui.aceternity.com/components/hover-border-gradient) |
| Moving Border **HOT** - shacdn | [Moving Border](https://ui.aceternity.com/components/moving-border) |
| Border Beam **HOT** - shacdn | [Border Beam](https://nyxbui.design/docs/components/border-beam) |
| Shine Border **HOT** - shacdn | [Shine Border](https://nyxbui.design/docs/components/shine-border) |
| Border Beam **HOT** | [Border Beam](https://magicui.design/docs/components/border-beam) |
| Shine Border **HOT** | [Shine Border](https://magicui.design/docs/components/shine-border) |
| Border Beam #2 **HOT** | [Border Beam #2](https://uiverse.io/dylanharriscameron/stupid-mole-90) |
| Border Beam #3 **HOT** | [Border Beam #3](https://uiverse.io/SelfMadeSystem/fluffy-eel-29) |
| Border Hover #1 **HOT** | [Border Hover #1](https://uiverse.io/themrsami/quick-cat-81) |
| Border Star **HOT** | [Border Star](https://www.reactbits.dev/animations/star-border) |


Border Beam #3 - raw:
<details><summary>Click to expand..</summary>
</details>

html:
```
<svg style="position: absolute; width: 0; height: 0;">
  <filter id="unopaq" y="-100%" height="300%" x="-100%" width="300%">
    <feColorMatrix
      values="1 0 0 0 0 
            0 1 0 0 0 
            0 0 1 0 0 
            0 0 0 5 0"
    ></feColorMatrix>
  </filter>
  <filter id="unopaq2" y="-100%" height="300%" x="-100%" width="300%">
    <feColorMatrix
      values="1 0 0 0 0 
            0 1 0 0 0 
            0 0 1 0 0 
            0 0 0 10 0"
    ></feColorMatrix>
  </filter>
  <filter id="unopaq3" y="-100%" height="300%" x="-100%" width="300%">
    <feColorMatrix
      values="1 0 0 1 0 
            0 1 0 1 0 
            0 0 1 1 0 
            0 0 0 2 0"
    ></feColorMatrix>
  </filter>
</svg>



<div class="card-container">
  <div class="spin spin-blur"></div>
  <div class="spin spin-intense"></div>
  <div class="backdrop"></div>
  <div class="card-border">
    <div class="spin spin-inside"></div>
  </div>
  <div class="card">
    

  </div>
</div>

```



css:

```
.card-container {
  position: relative;
  width: 400px;
  height: 300px;
  border-radius: 1em;
  margin: 0 2em;
}

.card-border {
  position: absolute;
  inset: 0;
  background: #0005;
  border-radius: inherit;
}

.card {
  position: absolute;
  inset: 0.125em;
  border-radius: 0.875em;
  background: #111215;
  display: flex;
  flex-direction: column;
  color: #fff;
  overflow: hidden;
}

.space {
  flex-grow: 1;
}


.backdrop {
  position: absolute;
  inset: -100%;
  background: radial-gradient(
    circle at 50% 50%,
    #0000 0,
    #0000 20%,
    #111111aa 50%
  );
  background-size: 3px 3px;
  z-index: -1;
}

.spin {
  position: absolute;
  inset: 0;
  z-index: -2;
  overflow: hidden;
}

.spin-blur {
  filter: blur(3em) url(#unopaq);
}

.spin-intense {
  inset: -0.125em;
  filter: blur(0.5em) url(#unopaq2);
  border-radius: 0.75em;
}

.spin-inside {
  inset: -2px;
  border-radius: inherit;
  filter: blur(2px) url(#unopaq3);
  z-index: 0;
}

.spin::before {
  content: "";
  position: absolute;
  inset: -30%;
  animation: speen 8s cubic-bezier(0.56, 0.15, 0.28, 0.86) infinite;
}

.spin-blur::before {
  background: linear-gradient(-45deg, #f50, #0000 46% 54%, #05f);
}

.spin-intense::before {
  background: linear-gradient(-45deg, #f95, #0000 35% 65%, #59f);
}

.spin-inside::before {
  background: linear-gradient(-45deg, #fc9, #0000 35% 65%, #9cf);
}

@keyframes speen {
  0% {
    rotate: 10deg;
  }
  50% {
    rotate: 190deg;
  }
  to {
    rotate: 370deg;
  }
}

.card input {
  display: none;
}
```

</details>












<details><summary>✍️ Text Animation</summary>

| Resource | Link |
|---|---|
| Text Animation 1 | [Text Animation 1](https://codepen.io/team/keyframers/pen/vYNyWwQ) |
| Text Animation 2 | [Text Animation 2](https://codepen.io/KaioRocha/pen/YoEVvZ) |
| Flip Words **HOT** - shacdn | [Flip Words](https://ui.aceternity.com/components/flip-words) |
| Circular Text **HOT** - react | [Circular Text](https://www.reactbits.dev/text-animations/circular-text) |
| Shiny Text **HOT** - react | [Shiny Text](https://www.reactbits.dev/text-animations/shiny-text) |
| Text pressure **HOT** - react | [text pressure](https://www.reactbits.dev/text-animations/text-pressure) |
| Gradient Text - react | [gradient text](https://www.reactbits.dev/text-animations/gradient-text) |
| Falling Text **HOT** - react | [falling text](https://www.reactbits.dev/text-animations/falling-text) |
| Focus Text **HOT** - react | [Focus text](https://www.reactbits.dev/text-animations/true-focus) |
| Scroll Float **HOT** - react | [Scroll float](https://www.reactbits.dev/text-animations/scroll-float) |
| Scroll Reveal **HOT** - react | [Scroll reveal](https://www.reactbits.dev/text-animations/scroll-reveal) |
| Rotating Text **HOT** - react | [Rotating text](https://www.reactbits.dev/text-animations/rotating-text) |
| Glitch Text **HOT** - react | [Glitch text](https://www.reactbits.dev/text-animations/glitch-text) |
| Scroll Velocity **HOT** - react | [Scroll Velocity](https://www.reactbits.dev/text-animations/scroll-velocity) |
| Count up **HOT** - react | [Count up](https://www.reactbits.dev/text-animations/count-up) |



</details>















<details><summary>🎬 Anime.js</summary>

| Resource | Link |
|---|---|
| Animated Letters | [Animated Letters](https://tobiasahlin.com/moving-letters/) |
| Staggering | [Staggering](https://codepen.io/juliangarnier/pen/XvjWvx) |
| Login Box | [Login Box](https://codepen.io/ainalem/pen/EQXjOR) |
| Submit Button | [Submit Button](https://codepen.io/andrewmillen/pen/MoKLob) |
| Animated Hand Signature | [Animated Hand Signature](https://codepen.io/mellis84/pen/JpVZNw) |

</details>

<details><summary>📦 Animated Objects</summary>

| Resource | Link |
|---|---|
| Animation Plugin | [Animation Plugin](https://animate.style/) |
| Button to Top | [Button to top](https://www.reactbits.dev/animations/animated-content) |
| Mouse Magnet | [Mouse Magnet](https://www.reactbits.dev/animations/magnet) |
| Metallic Transition **HOT** | [Metallic Transition](https://www.reactbits.dev/animations/metallic-paint) |



</details>




<details><summary>💫 Light & Beam Effects</summary>

| Resource | Link |
|---|---|
| Animated Beam | [Animated Beam](https://nyxbui.design/docs/components/animated-beam) |
| Animated Beam #2 | [Animated Beam #2](https://magicui.design/docs/components/animated-beam) |





</details>









<details><summary>🎬 Animated Lists</summary>

| Resource | Link |
|---|---|
| Animated List | [Animated List](https://magicui.design/docs/components/animated-list) |
| Animated List #2 | [Animated List #2](https://www.reactbits.dev/components/animated-list) |


</details>






---
## 🔘 Input Elements




<details><summary>⌨️ Input Fields</summary>
  
| Resource | Link |
|---|---|
| Base Inputs | [Base Inputs](https://www.edilozi.pro/docs/components/base-inputs) |
| Base Inputs #2 | [Base Inputs #2](https://ui.indie-starter.dev/docs/inputs) |
| Base Inputs #3 **HOT** | [Base Inputs #3](https://uiverse.io/Praashoo7/tame-sloth-39) |
| AI Generate **HOT** | [AI Generate](https://uiverse.io/Cobp/dangerous-dolphin-47) |

  
</details>







---
## 🔘 Buttons


<details><summary>⌨️ Select</summary>

# Multi Select
  
| Resource | Link |
|---|---|
| Multi Select **HOT** | [Multi Select](https://github.com/sersavan/shadcn-multi-select-component) |

  
</details>











<details><summary>🔘 Neumorphism Buttons</summary>

| Resource | Link |
|---|---|
| Black **HOT** | [Black](https://uiverse.io/marcelodolza/pretty-goose-7) |


</details>








<details><summary>🔘 General Buttons</summary>

| Resource | Link |
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
| Tailwind CSS buttons - shacdn | [Tailwind CSS buttons](https://ui.aceternity.com/components/tailwindcss-buttons) |
| Buttons **HOT** - shacdn | [Buttons](https://www.edilozi.pro/docs/components/buttons) |
| Shimmer Button **HOT** - shacdn | [Shimmer Button](https://nyxbui.design/docs/components/shimmer-button) |
| Variant 2 Shine **HOT** | [Variant 2 Shine](https://ui.indie-starter.dev/docs/buttons#variant-2-shine) |
| Shimmer Effect **HOT** | [Shimmer Effect](https://ui.indie-starter.dev/docs/eye-catching-buttons#variant-1---shimmer-effect) |
| Shiny Background **HOT** | [Shiny Background](https://ui.indie-starter.dev/docs/eye-catching-buttons#variant-2---shiny-background) |
| Animated Border Gradient **HOT** | [Animated Border Gradient](https://ui.indie-starter.dev/docs/eye-catching-buttons#variant-4---animated-border-gradient) |
| Animated Text Gradient **HOT** | [Animated Text Gradient](https://ui.indie-starter.dev/docs/eye-catching-buttons#variant-5---animated-text-gradient) |
| Shimmer Button **HOT** | [Shimmer Button](https://magicui.design/docs/components/shimmer-button) |
| Shiny Button **HOT** | [Shiny Button](https://magicui.design/docs/components/shiny-button) |
| Pulsating Button | [Pulsating Button](https://magicui.design/docs/components/pulsating-button) |
| Ripple Button **HOT** | [Ripple Button](https://magicui.design/docs/components/ripple-button) |
| White Hover **HOT** | [White Hover](https://uiverse.io/cssbuttons-io/friendly-dragon-76) |
| Shine Button **HOT** | [Shine Button](https://uiverse.io/Allyhere/strong-pug-22) |
| Hover Button **HOT** | [Hover Button](https://uiverse.io/SelfMadeSystem/weak-mole-88) |
| Glass Button **HOT** | [Glass Button](https://codepen.io/Petr-Knoll/pen/QwWLZdx) |



</details>









<details><summary>🌗 Dark/white Mode Button</summary>

| Resource | Link |
|---|---|
| Dark/white Mode **HOT** | [Dark/white Mode **HOT**](https://codepen.io/jh3y/pen/ByBjxrW) |

</details>

<details><summary>📝 Text Verification</summary>

| Resource | Link |
|---|---|
| Text Verification 1 | [Text Verification 1](https://codepen.io/AlikinVV/pen/WLpRdg) |

</details>

<details><summary>✅ Success Button</summary>

| Resource | Link |
|---|---|
| Confetti Button | [Confetti Button](https://codepen.io/aaroniker/pen/bGVGNrV) |
| With Loading | [With Loading](https://codepen.io/eliortabeka/pen/xOrQZA) |
| Success Button 1 | [Success Button 1](https://codepen.io/colinhorn/pen/KXjYXr) |
| Success Button 2 | [Success Button 2](https://codepen.io/guywald/details/AXwKqP) |
| Success Button 3 | [Success Button 3](https://codepen.io/keenanpayne/details/YmKKer) |
| Success Button 4 | [Success Button 4](https://codepen.io/ky0suke/pen/xwzNzp) |

</details>

<details><summary>🗑️ Delete Button</summary>

| Resource | Link |
|---|---|
| Delete Button 1 | [Delete Button 1](https://codepen.io/estrepitos/pen/JAtKr) |

</details>

<details><summary>❌ Close Button</summary>

| Resource | Link |
|---|---|
| Animated Close Buttons | [Animated Close Buttons](https://codepen.io/JonasBadalic/pen/MYaMBz) |

</details>

<details><summary>🚀 Publish Button</summary>

| Resource | Link |
|---|---|
| Hold to Verify | [Hold to Verify](https://codepen.io/aaroniker/pen/BayaBpV) |

</details>

<details><summary>⬇️ Download Button</summary>

| Resource | Link |
|---|---|
| Download Button 1 | [Download Button 1](https://codepen.io/aaroniker/pen/yRdoYN) |
| Download Button 2 | [Download Button 2](https://codepen.io/lalit-mohan/pen/rrEzLp) |
| Download Button 3 | [Download Button 3](https://codepen.io/thereyzer/pen/JqLdLr) |
| Download Button 4 | [Download Button 4](https://codepen.io/aaroniker/pen/vYEmery) |
| Download Button 5 | [Download Button 5](https://codepen.io/aaroniker/pen/KjJQER) |

</details>

<details><summary>🛒 Add to Cart Button</summary>

| Resource | Link |
|---|---|
| Add to cart Button | [Add to cart Button](https://codepen.io/aaroniker/pen/QWWXKVP) |

</details>

<details><summary>✉️ Send Button</summary>

| Resource | Link |
|---|---|
| Send Button | [Send Button](https://codepen.io/aaroniker/pen/BajabVN) |

</details>





<details><summary>✅ Activate Button</summary>

| Resource | Link |
|---|---|
| Activate Button | [Activate Button](https://codepen.io/aaroniker/pen/ZVOrOZ) |

</details>




<details><summary>✅ Subscribe Button</summary>

| Resource | Link |
|---|---|
| Subscribe Button **HOT** | [Subscribe Button](https://uiverse.io/marcelodolza/stupid-vampirebat-24) |

</details>









<details><summary>⬆️ Upload Button</summary>

| Resource | Link |
|---|---|
| Upload Button 1 | [Upload Button 1](https://codepen.io/balapa/pen/VYVedm) |
| With Pause | [With Pause](https://codepen.io/aaroniker/pen/QXxexJ) |

</details>






<details><summary>🚚 Place Order Button</summary>

| Resource | Link |
|---|---|
| Animation with truck 1 | [Animation with truck 1](https://codepen.io/aaroniker/pen/eYOVrNa) |
| Animation with truck 2 | [Animation with truck 2](https://codepen.io/aaroniker/pen/oNgPOwo) |

</details>







<details><summary>▶ Play Button</summary>

| Resource | Link |
|---|---|
| Play Button **HOT** | [Play Button](https://uiverse.io/MuhammadHasann/popular-seahorse-73) |

</details>






<details><summary>▶ Generate Button</summary>

| Resource | Link |
|---|---|
| Generate Button **HOT** | [Generate Button](https://uiverse.io/MuhammadHasann/mean-bird-62) |
| Generate Button #2 **HOT** | [Generate Button #2](https://uiverse.io/MuhammadHasann/mean-bird-62) |


</details>








<details><summary>☑️ Checkbox</summary>

| Resource | Link |
|---|---|
| Checkbox 1 | [Checkbox 1](https://codepen.io/alexjoffroy/pen/ORXOmR) |
| Checkbox 2 - **HOT** | [Checkbox 2](https://uiverse.io/Praashoo7/angry-starfish-78) |
| Checkbox 3 - **HOT** | [Checkbox 3](https://uiverse.io/00Kubi/hot-dragonfly-56) |
| Checkbox 4 - **HOT** | [Checkbox 4](https://uiverse.io/PriyanshuGupta28/tough-puma-94) |
| Checkbox 5 - **HOT** | [Checkbox 5](https://uiverse.io/adamgiebl/curly-lizard-40) |


</details>





<details><summary>☑️ Switch / Toggle</summary>

| Resource | Link |
|---|---|
| Toggle 1 **HOT** | [Toggle 1](https://uiverse.io/gharsh11032000/sour-vampirebat-66) |
| Toggle 2 **HOT** | [Toggle 2](https://uiverse.io/gharsh11032000/sour-vampirebat-66) |
| Toggle 3 **HOT** | [Toggle 3](https://uiverse.io/AbanoubMagdy1/fluffy-octopus-90) |
| Toggle 4 **HOT** | [Toggle 4](https://uiverse.io/G4b413l/giant-panther-83) |
| Toggle 5 **HOT** | [Toggle 5](https://uiverse.io/aboalsim114/clever-chipmunk-18) |
| Toggle 6  | [Toggle 6](https://uiverse.io/ICe1BotMaker/quick-goat-3) |



</details>





<details><summary>☑️ Dark/Light Mode Toggle</summary>

| Resource | Link |
|---|---|
| Toggle 1 **HOT** | [Toggle 1](https://uiverse.io/RiccardoRapelli/jolly-chicken-91) |


</details>












---
## 🧭 Navigation & UI




<details><summary>Stepper/summary>

| Resource | Link |
|---|---|
| Stepper **HOT** | [Stepper](https://www.reactbits.dev/components/stepper) |

</details>






<details><summary>💬 Chat UI</summary>

| Resource | Link |
|---|---|
| Chat UI 1 | [Chat UI 1](https://codepen.io/Momciloo/pen/bEdbxY) |

</details>




<details><summary>🔢 Pagination</summary>

| Resource | Link |
|---|---|
| Pagination 1 | [Pagination 1](https://codepen.io/hakimel/details/gfIsk) |
| Pagination 2 | [Pagination 2](https://codepen.io/netzzwerg/pen/hfutI) |
| Infinity Pagination | [Infinity Pagination](https://codepen.io/MarioD/pen/OmWaqz) |
| Svg Animated | [Svg Animated](https://codepen.io/chrisgannon/pen/xVOjZq) |
| Morphing Pagination | [Morphing Pagination](https://codepen.io/aaroniker/pen/pojXjrZ) |

</details>






<details><summary>Search</summary>

| Resource | Link |
|---|---|
| Placeholders And Vanish Input **HOT** - shacdn | [Placeholders And Vanish Input](https://ui.aceternity.com/components/placeholders-and-vanish-input) |
| Search #1 **HOT** | [Search #1](https://uiverse.io/Lakshay-art/curvy-earwig-22) |


</details>







<details><summary>☰ Menu Bar</summary>

<details><summary>🍔 Hamburger Menu Animation</summary>

| Resource | Link |
|---|---|
| Hamburger Menu Animation | [Hamburger Menu Animation](https://codepen.io/ahmadbassamemran/pen/abopOMY) |

</details>

<details><summary>📱 Menu Bar Mobile</summary>

| Resource | Link |
|---|---|
| Mobile Menubar 1 | [Mobile Menubar 1](https://codepen.io/7ssan91/pen/dqLmpP) |
| Mobile Menubar 2 | [Mobile Menubar 2](https://codepen.io/raffaele-filiberti/pen/mPQqVW) |
| Mobile Menubar 3 | [Mobile Menubar 3](https://codepen.io/cateelderflower/pen/jwVPGd) |

</details>



<details><summary>💻 Menu Bar Desktop</summary>

| Resource | Link |
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

<details><summary>🗄️ Sidebar Menu</summary>

| Resource | Link |
|---|---|
| Sidebar Menu 1 | [Sidebar Menu 1](https://codepen.io/jcoulterdesign/pen/qdWxEm) |

</details>

</details>


















---
## 🎛️ UI Components




<details><summary>📊 Product Tour</summary>

| Resource | Link |
|---|---|
| Onborda **HOT** | [Onborda](https://www.onborda.dev/) |


</details>







<details><summary>📊 Percentage Display</summary>

| Resource | Link |
|---|---|
| Animated Circle | [Animated Circle](https://codepen.io/like-a-boss/pen/pgqgKq) |
| Multiple Charts | [Multiple Charts](https://codepen.io/FilipDanic/pen/xbgbaQ) |

</details>










<details><summary>📂 Hierarchical Views</summary>

| Resource | Link |
|---|---|
| Tree View | [Tree View](https://shadcn-extension.vercel.app/docs/tree-view) |

</details>






<details><summary>📃 One Page Design</summary>

| Resource | Link |
|---|---|
| One Page 1 | [One Page 1](https://codepen.io/Cutcopy/pen/LpBPLe) |

</details>












<details><summary>🎴 Card Elements</summary>

| Resource | Link |
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
| Infinite Moving Cards **HOT** - shacdn | [Infinite Moving Cards **HOT**](https://ui.aceternity.com/components/infinite-moving-cards) |
| Evervault Card **HOT** - shacdn | [Evervault Card **HOT**](https://ui.aceternity.com/components/evervault-card) |
| 3D Card Effect **HOT** - shacdn | [3D Card Effect **HOT** ](https://ui.aceternity.com/components/3d-card-effect) |
| 3D Animated Pin **HOT** - shacdn | [3D Animated Pin **HOT**](https://ui.aceternity.com/components/3d-pin) |
| Background Gradient - shacdn | [Background Gradient(https://ui.aceternity.com/components/background-gradient) |
| Hover Effect - shacdn | [Hover Effect](https://ui.aceternity.com/components/card-hover-effect) |
| Magic Card **HOT** - shacdn | [Magic Card](https://nyxbui.design/docs/components/magic-card) |
| Magic Card #2 **HOT** - shacdn | [Magic Card #2](https://magicui.design/docs/components/magic-card) |
| 3d mouse follow card **HOT** | [3d mouse follow car](https://www.reactbits.dev/components/tilted-card) |
| pixel card **HOT** | [pixel card](https://www.reactbits.dev/components/pixel-card) |
| hover spotlight card **HOT** | [hover spotlight card](https://www.reactbits.dev/components/spotlight-card) |








### Simple Cards  

| Resource | Link |
|---|---|
| Variant 1 **HOT** | [Variant 1](https://ui.indie-starter.dev/docs/cards-simple#variant-1) |
| Variant 2 **HOT** | [Variant 2](https://ui.indie-starter.dev/docs/cards-simple#variant-2) |
| Variant 3 **HOT** | [Variant 3](https://ui.indie-starter.dev/docs/cards-simple#variant-3) |
| Variant 5 | [Variant 5](https://ui.indie-starter.dev/docs/cards-simple#variant-5) |
| Variant 6 (3D) **HOT** | [Variant 6 (3D)](https://ui.indie-starter.dev/docs/cards-simple#variant-6-3d) |
| Variant 7 **HOT** | [Variant 7](https://ui.indie-starter.dev/docs/cards-simple#variant-7) |
| Pattern - Lines **HOT** | [Variant 4 - Lines](https://ui.indie-starter.dev/docs/cards-with-pattern#variant-4-lines) |
| Pattern - Grid **HOT** | [Variant 8 - Grid](https://ui.indie-starter.dev/docs/cards-with-pattern#variant-8-grid) |



### Multi-Layer Cards  

| Resource | Link |
|---|---|
| Variant 1 **HOT** | [Variant 1](https://ui.indie-starter.dev/docs/cards-multi-layers#variant-1) |
| Variant 2 **HOT** | [Variant 2](https://ui.indie-starter.dev/docs/cards-multi-layers#variant-2) |
| Variant 3 **HOT** | [Variant 3](https://ui.indie-starter.dev/docs/cards-multi-layers#variant-3) |



### Animated Cards  

| Resource | Link |
|---|---|
| Variant 1 **HOT** | [Variant 1](https://uiverse.io/Spacious74/moody-owl-18) |




### Badge Cards  

| Resource | Link |
|---|---|
| Badge Card 1 **HOT** | [Badge Card](https://uiverse.io/mrhyddenn/massive-earwig-94) |




</details>















<details><summary>🪟 Popup</summary>

| Resource | Link |
|---|---|
| Popup 1 | [Popup 1](https://codepen.io/melnik909/pen/QModrM) |

</details>

<details><summary>🔔 Success Messages</summary>

| Resource | Link |
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

<details><summary>⚠️ Success Messages & Errors</summary>

| Resource | Link |
|---|---|
| Animated characters | [Animated characters](https://codepen.io/juliepark/pen/vjMOKQ) |
| Tooltips 1 | [Tooltips 1](https://codepen.io/veronicadev/pen/LrZaov) |
| Success & Error 1 | [Success & Error 1](https://codepen.io/MariamSalloum/pen/PBxKzd) |
| Tooltips 2 | [Tooltips 2](https://codepen.io/prallen/details/AsECw) |
| Animated Tooltip - shacdn **HOT** | [Animated Tooltip](https://ui.aceternity.com/components/animated-tooltip) |




</details>








<details><summary>🗣️ Testimonials</summary>

| Resource | Link |
|---|---|
| Slider 1 | [Slider 1](https://codepen.io/shamim539/pen/GZPZBp) |
| Slider 2 | [Slider 2](https://codepen.io/Aashima/pen/WdQQMr) |
| Static 1 | [Static 1](https://codepen.io/littlesnippets/pen/EVLJVa) |
| Static 2 | [Static 2](https://codepen.io/littlesnippets/pen/yejzvR) |
| Static 3 | [Static 3](https://codepen.io/littlesnippets/pen/yOvZPV) |
| Static 4 | [Static 4](https://codepen.io/littlesnippets/pen/QjXVrV) |

</details>







<details><summary>🛒 Pricing & Plans</summary>

| Resource | Link |
|---|---|
| Pricing - shacdn | [Pricing](https://github.com/m4nute/pricing-page-shadcn) |
| Pricing #2 - shacdn | [Pricing #2](https://shadcn-ui-blocks.vercel.app/blocks/pricing-sections) |


</details>





<details><summary>🖼️ Dropdown Menu</summary>

| Resource | Link |
|---|---|
| Dropdown menu - shacdn **HOT** | [Dropdown menu](https://tremor.so/docs/inputs/dropdown-menu) |

</details>





<details><summary>🖼️ Scroll-Text & Marquee</summary>

| Resource | Link |
|---|---|
| Marquee | [Marquee](https://magicui.design/docs/components/marquee) |

</details>





<details><summary>🎬 Video</summary>

| Resource | Link |
|---|---|
| Hero Video Dialog | [Hero Video Dialog](https://magicui.design/docs/components/hero-video-dialog) |

</details>




















---
## 🖼️ Image Elements

<details><summary>🎠 Image Carousel</summary>

| Resource | Link |
|---|---|
| Owl Carousel Plugin | [Owl Carousel Plugin](https://owlcarousel2.github.io/OwlCarousel2/) |
| Carousel 1 | [Carousel 1](https://codepen.io/ccallen001/pen/bEYByd) |
| 3D Carousel | [3D Carousel](https://codepen.io/iamdavid/details/CDluy) |
| Carousel 2 | [Carousel 2](https://codepen.io/lmgonzalves/details/djEgmv) |
| Fullscreen vertical | [Fullscreen vertical](https://codepen.io/mxbck/pen/ERNwBy) |
| Fullscreen 1 | [Fullscreen 1](https://codepen.io/Alca/pen/VByeJd) |
| Fullscreen vertical image distortion | [Fullscreen vertical image distortion](https://codepen.io/ashthornton/details/KRQbMO) |
| Fullscreen 2 | [Fullscreen 2](https://codepen.io/lmgonzalves/pen/djEgmv) |
| Carousel - shacdn **HOT** | [Carousel](https://shadcn-extension.vercel.app/docs/carousel) |




</details>

<details><summary>🏞️ Image Galleries</summary>

| Resource | Link |
|---|---|
| Gallery 1 | [Gallery 1](https://codepen.io/andata/pen/pEyAGj) |
| Responsive Vertical Scrolling Parallax Gallery **HOT** | [Responsive Vertical Scrolling Parallax Gallery **HOT**](https://codepen.io/noirsociety/pen/NWJvgZg) |

</details>






<details><summary>📸 Image Transitions</summary>

| Resource | Link |
|---|---|
| Image Transitions 1 | [Image Transitions 1](https://codepen.io/sfi0zy/pen/OQOExE) |

</details>











<details><summary>🖼️ Image Utilities</summary>

| 🖼️ **Resource** | 🔗 **Link** |
|---|---|
| 🪞 Image Compare | [Image Compare](https://ui.aceternity.com/components/compare) |

</details>  






<br><br>


---
## 🏢 Logo & Social Media

<details><summary>🏢 Logos</summary>

| Resource | Link |
|---|---|
| Logo 1 | [Logo 1](https://codepen.io/mkmueller/pen/dCEhA) |
| Orbit Logo | [Orbit Logo](https://codepen.io/guerreiro/pen/obhzc) |
| Free Vector logos with backlink | [Free Vector logos with backlink](https://www.freepik.com/search?format=search&page=2&query=search+engine) |
| Free Vector logos with backlink 2 | [Free Vector logos with backlink 2](pngtree.com) |

</details>

<details><summary>🌐 Social Media Links</summary>

| Resource | Link |
|---|---|
| Social Media 1 | [Social Media 1](https://codepen.io/nouribram/pen/WNQzoOd) |
| Social Media 2 | [Social Media 2](https://codepen.io/daniel_wolf/pen/mJRmaQ) |
| Social Media 3 | [Social Media 3](https://codepen.io/FrankieDoodie/pen/dqmKrb) |
| 3D Cubes with Hover | [3D Cubes with Hover](https://codepen.io/gabriellewee/pen/Qdpgwx) |
| Hover with tooltip | [Hover with tooltip](https://codepen.io/kieranfivestars/pen/gbOWbM) |

</details>














---
## 🔮 3D 

<details><summary>✨ 3D</summary>

| Resource | Link |
|---|---|
| Card with mouse follow | [Card with mouse follow](https://codepen.io/lembitk/pen/EVmqmY) |
| 3D 1 | [3D 1](https://codepen.io/yotman/pen/VEzXJp) |
| Image Carousel | [Image Carousel](https://codepen.io/hoanghien0410/pen/MMPaqm) |
| Glassomorphic logo | [Glassomorphic logo](https://codepen.io/konstantindenerz/pen/VwoEJqP) |
| Three.js cards | [Three.js cards](https://codepen.io/smcnally000/pen/eYqXWyJ) |
| Github Globe **HOT** - shacdn | [Github Globe](https://ui.aceternity.com/components/github-globe) |



</details>








---
## 🔮 Backgrounds

<details><summary>🌄 Interactive Backgrounds</summary>

| Resource | Link |
|---|---|
| Meta Balls **HOT** | [Meta Balls](https://www.reactbits.dev/animations/meta-balls) |

</details>







<details><summary>🌄 Backgrounds</summary>

| Resource | Link |
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
| Infinite Falling Illusion | WebGL Shader **HOT** | [Infinite Falling Illusion](https://codepen.io/pjkarlik/pen/mybEwjG) |
| Sparkles - shacdn | [Sparkles](https://ui.aceternity.com/components/sparkles) |
| Aurora Background **HOT** - shacdn | [Aurora Background](https://ui.aceternity.com/components/aurora-background) |
| Aurora Background #2 **HOT** - shacdn | [Aurora Background #2](https://www.reactbits.dev/backgrounds/aurora) |
| Hero Highlight - shacdn | [Hero Highlight](https://ui.aceternity.com/components/hero-highlight) |
| Dot Pattern **HOT** - shacdn | [Dot Pattern](https://nyxbui.design/docs/components/dot-pattern) |
| ibelick/background-snippet **HOT** - shacdn | [ibelick/background-snippet](https://bg.ibelick.com/) |
| Background Grid Beam **HOT** - shacdn | [Background Grid Beam](https://ui.lukacho.com/components/background-grid-beam) |
| Particles **HOT** | [Particles](https://magicui.design/docs/components/particles) |
| Ripple **HOT** | [Ripple](https://magicui.design/docs/components/ripple) |
| Dot Pattern **HOT** | [Dot Pattern](https://magicui.design/docs/components/dot-pattern) |
| Dot Gradient **HOT** - Generator here https://shenanigans.shoghisimon.ca/collection/css-blur-blob-bg/ | [Dot Gradient](https://uiverse.io/SelfMadeSystem/sweet-dolphin-36) |
| Lightning **HOT** | [Lightning](https://www.reactbits.dev/backgrounds/lightning) |
| Threads **HOT** | [Threads](https://www.reactbits.dev/backgrounds/threads) |
| Hyperspeed **HOT** | [Hyperspeed](https://www.reactbits.dev/backgrounds/hyperspeed) |
| iridescence **HOT** | [iridescence](https://www.reactbits.dev/backgrounds/iridescence) |
| ball pit **HOT** | [ball pit](https://www.reactbits.dev/backgrounds/ballpit) |
| orb **HOT** | [orb](https://www.reactbits.dev/backgrounds/orb) |
| liquid chhrome **HOT** | [liquid chrome](https://www.reactbits.dev/backgrounds/liquid-chrome) |
| particles **HOT** | [particles](https://www.reactbits.dev/backgrounds/particles) |
| waves **HOT** | [waves](https://www.reactbits.dev/backgrounds/waves) |






</details>









<details><summary>🌐 WebGL Backgrounds</summary>

| Resource | Link |
|---|---|
| WebGL Fluid Simulation | [WebGL Fluid Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) |
| Vanta.js **HOT** | [Vanta.js **HOT**](https://www.vantajs.com/?effect=trunk) |

</details>

<details><summary>🎨 Canvas Backgrounds</summary>

| Resource | Link |
|---|---|
| AmbientCanvasBackgrounds | [AmbientCanvasBackgrounds](https://github.com/crnacura/AmbientCanvasBackgrounds?tab=readme-ov-file) |

</details>

<details><summary>🖼️ Background Images (cc0)</summary>

| Resource | Link |
|---|---|
| Developer on bench | [Developer on bench](https://pixabay.com/photos/work-workaholic-writer-programmer-1627703/) |

</details>

<details><summary>🌈 Animated Gradient Backgrounds</summary>

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
<br><br>


### **🖍️ Syntax Highlight**  
<details><summary>💻 Code</summary>
  
| 📚 **Resource** | 🔗 **Link** |
|---|---|
| 📜 Code Block - shacdn | [Code Block](https://ui.aceternity.com/components/code-block) |
| ray - **HOT** | [ray](https://ray.so/) |




### Code Comparison  

| Resource | Link |
|---|---|
| Code Comparison | [Code Comparison](https://magicui.design/docs/components/code-comparison) |

### Script Copy Button  

| Resource | Link |
|---|---|
| Script Copy Button **HOT** | [Script Copy Button](https://magicui.design/docs/components/script-copy-btn) |







</details>













<br><br>


## File Handling

<details><summary>File Upload</summary>

| Resource | Link |
|---|---|
| File Upload | [File Upload](https://ui.aceternity.com/components/file-upload) |

  
</details>








<br><br>


## 🖼️ Mocks

<details><summary>📱 Devices</summary>

| Resource | Link |
|---|---|
| Safari | [Safari](https://magicui.design/docs/components/safari) |
| iPhone 15 Pro | [iPhone 15 Pro](https://magicui.design/docs/components/iphone-15-pro) |
| Android | [Android](https://magicui.design/docs/components/android) |
  
</details>







<br><br>


## 📝 Forms & Authentication

<details><summary>📰 Newsletter</summary>

| Resource | Link |
|---|---|
| Animation mailbox | [Animation mailbox](https://codepen.io/lerida/pen/BaoRRbp) |
| Newsletter 1 | [Newsletter 1](https://codepen.io/YarivFrd/pen/NXomOV) |

</details>

<details><summary>⏱️ Timeline</summary>

| Resource | Link |
|---|---|
| Animated timeline | [Animated timeline](https://codepen.io/vincebrown/pen/BNazqL) |

</details>

<details><summary>🔑 Sign-in</summary>

| Resource | Link |
|---|---|
| Sign-in 1 | [Sign-in 1](https://codepen.io/marcobiedermann/pen/Fybpf) |
| Sign-in 2 | [Sign-in 2](https://codepen.io/mycnlz/details/aNNExj) |
| Sign-in 3 | [Sign-in 3](https://codepen.io/yildirimzlm/pen/aRjOGM) |
| Full page with bg | [Full page with bg](https://codepen.io/carsonf92/pen/pNWGXG) |
| Mobile | [Mobile](https://codepen.io/suez/pen/dPqxoM) |
| Perspective animation | [Perspective animation](https://codepen.io/jcoulterdesign/pen/azepmX) |
| 3D perspective | [3D perspective](https://codepen.io/jenning/pen/RVRYeb) |

</details>








<details><summary>🔒 Create Password</summary>

| Resource | Link |
|---|---|
| Create Password | [Create Password](https://codepen.io/davidkpiano/pen/WKvPBP) |

</details>





<details><summary>🔒 Update Password</summary>

| Resource | Link |
|---|---|
| Update Password | [Update Password](https://gist.github.com/mjbalcueva/b21f39a8787e558d4c536bf68e267398) |

</details>





<details><summary>📱 Phone Input</summary>

| Resource | Link |
|---|---|
| Phone Input | [Phone Input](https://www.armand-salle.fr/post/phone-input-shadcn-ui/) |
| Phone Input #2 | [Phone Input  #2](https://github.com/damianricobelli/shadcn-phone-input) |
| Phone Input #3 | [Phone Input  #3](https://github.com/omeralpi/shadcn-phone-input) |



</details>















<details><summary>✍️ Sign-up</summary>

| Resource | Link |
|---|---|
| Signup Form - shacdn | [Signup Form](https://ui.aceternity.com/components/signup-form) |

</details>





<details><summary>🔄 Sign-in & Sign-up (Combined)</summary>

| Resource | Link |
|---|---|
| Sign-in & Sign-up 1 | [Sign-in & Sign-up 1](https://codepen.io/joshsorosky/pen/gaaBoB) |
| Sign-in & Sign-up 2 | [Sign-in & Sign-up 2](https://codepen.io/andytran/pen/GpyKLM) |
| Sign-in & Sign-up 3 | [Sign-in & Sign-up 3](https://codepen.io/hurick/pen/Kyrvrj) |

</details>

</details>
