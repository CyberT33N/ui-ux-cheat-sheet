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

# Components


<details><summary>Click to expand..</summary>


# Code Snippets Cheat Sheet

## Third Party Collections

<details><summary>Click to expand..</summary>

### Material Design
- [Bootstrap 4 Collection](https://codepen.io/mdbootstrap/pen/LRNZBz)

### Full Websites
- [Website 1](https://codepen.io/veronicadev/details/YYvjzO)
- [Website 2](https://codepen.io/team/webflow/pen/pvydKd)

</details>

## Email Templates

<details><summary>Click to expand..</summary>

### How to send HTML Email
- **Gmail:** [How to send HTML email via Gmail](https://www.youtube.com/watch?v=MsMSqhMlfao)
- **AppScript:** [How to send HTML email via AppScript](https://codegena.com/send-mail-merge-html-emails-using-google-appscripts/)

    **AppScript Code Snippet:**
    ```javascript
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
    ```
    
### Supported CSS/HTML
- [Can I email](https://www.caniemail.com)

### Responsive Email Templates
- [Multi-layer ★ **HOT** - TESTED](https://codepen.io/rodriguezcommaj/pen/RNPzwr)
- [Responsive 1](https://codepen.io/rickygipson/pen/Aouhi)
- [Responsive 2](https://codepen.io/zavoloklom/pen/qEVqzx)
- [Responsive 3](https://github.com/konsav/email-templates/)
- [Responsive 4](https://codepen.io/raybeezdesign/pen/pHlLG)
- [Multi-layer ★ **HOT** ★](https://codepen.io/Mestika/pen/bEerrv)
- [Responsive layout](https://codepen.io/beeeees/pen/JEDms)
- [Multi-layer ★ **HOT** - TESTED](https://codepen.io/brucej/pen/BjdwVj)
- [Responsive 5](https://codepen.io/RyanHallMedia/pen/qRXBKW)
- [Multi-layer](https://codepen.io/reallygoodemails/pen/ZWqOBz)
- [Small clean 1](https://codepen.io/koca/pen/vjzyad)
- [Multi-layer ★ **HOT** - TESTED](https://codepen.io/maizzle/pen/WYjyvg)
- [Animated?](https://codepen.io/reallygoodemails/pen/yJagbN)
- [Small clean 2](https://codepen.io/shift-tech/pen/eMdePP)
- [Small clean 3](https://codepen.io/denner-rondinely/pen/qwdywa)
- [Small clean 4](https://codepen.io/dvomaks/pen/xedjBp)
- [Small clean 5](https://codepen.io/darcyturk/pen/XxdVbv)
- [Material Design](https://codepen.io/judecodes/pen/YBdMLZ)
- [Small clean 6](https://codepen.io/mtthlbg/pen/KVWggg)
- [Material Design Multi-layer ★ **HOT** - Doesn't work real emails..★](https://codepen.io/luong-quynh/pen/agBMbg)
- [Clean card with bg](https://codepen.io/faudau/pen/zJombX)
- [Product offer ★ **HOT** ★](https://codepen.io/reallygoodemails/pen/OMqpmN)
- [Small clean 7](https://codepen.io/MarcoZani/details/aRNQmQ)
- [Clean 1](https://codepen.io/koolkamalkishor/pen/ZEbgyrj)
- [Transition image](https://codepen.io/Romaric_aboule/pen/gOpywgG)
- [Clean card 2](https://codepen.io/saurya3579/pen/poJKdWP)
- [Clean 3](https://codepen.io/visionarymarketer/pen/rLqZqx)
- [Image transition](https://codepen.io/Mr_Rahul_Tiwari/pen/Wqzqpd)
- [Clean big image](https://codepen.io/reallygoodemails/pen/ELoOvj)

</details>

## Image Grid

<details><summary>Click to expand..</summary>

- [Grid 1](https://codepen.io/dtab428/pen/bRwMeq)
- [Grid 2](https://codepen.io/JohnRiordan/details/Xbjwqe)
- [Grid 3](https://codepen.io/tstoik/pen/qZEZJp)
- [Grid 4](https://codepen.io/team/keyframers/pen/EzMyQe)

</details>

## Text

<details><summary>Click to expand..</summary>

- [Shimmer Effect](https://codepen.io/redouglas/pen/gobsm)

### Multiple Shadows
- [Multiple Shadows](https://codepen.io/tommyho/pen/abejXMb)

</details>

## Lightbox

<details><summary>Click to expand..</summary>

- [Lightbox 1](https://codepen.io/ezra_siton/pen/XNpJaX)
- [PhotoSwipe](https://photoswipe.com/)
- [nanogallery2](https://nanogallery2.nanostudio.org/)
- [glightbox](https://biati-digital.github.io/glightbox/)
- [simplelightbox](https://simplelightbox.com/)
- [Lightgallery Plugin (commercial)](https://codepen.io/sachinchoolur/pen/QjLNMM)
- [Single Image 1](https://codepen.io/gschier/pen/HCoqh)
- [Single Image 2](https://codepen.io/ongtiffany/pen/BoOeQV)
- [Gallery 1](https://codepen.io/nsom/pen/VbqLew)
- [Animated Gallery](https://codepen.io/designcouch/pen/DEkcf)
- [Gallery 2](https://codepen.io/svelts/pen/VYxPWW)
- [Grid Gallery with animation to center](https://codepen.io/ademilter/pen/ByLwwV)

</details>

## Easing

<details><summary>Click to expand..</summary>

- [Easing Cheat Sheet](https://easings.net/) - [animejs](https://animejs.com/documentation/#pennerFunctions)

</details>

## Music Player

<details><summary>Click to expand..</summary>

- [Music Player 1](https://codepen.io/ecemgo/pen/vYPadZz)

</details>

## Contact Form

<details><summary>Click to expand..</summary>

- [Contact Form 1](https://codepen.io/jq/pen/rVVQXz)
- [Contact Form 2](https://codepen.io/rickyeckhardt/pen/rNVOrBL)
- [Animation in envelope 1](https://codepen.io/permanentinc/pen/muFxK)
- [Animation in envelope 2](https://codepen.io/asmaa-mohammed/pen/mmVaLE)
- [Contact Form 3](https://codepen.io/superguru/pen/aGJHA)
- [Contact Form 4](https://codepen.io/krisantuswanandi/pen/KxrgeZ)
- [Contact Form 5](https://codepen.io/mayurelbhar/pen/OPbZmy)
- [Contact Form 6](https://codepen.io/tutsplus/pen/ZNWQje)
- [Contact Form 7](https://codepen.io/melawire/pen/pGFvs)
- [Contact Form 8](https://codepen.io/lolwtf/pen/amVPYN)
- [Contact Form 9](https://codepen.io/sdras/pen/LEorev)

</details>

## Error Pages

<details><summary>Click to expand..</summary>

### 403 (Forbidden) Error Page
- [Typing Console](https://codepen.io/leenalavanya/pen/RYqvgK)
- [Perspective](https://codepen.io/pgalor/pen/dqQqqx)

### 404 (Not Found) Error Page
- [Lost Astronaut](https://codepen.io/eroxburgh/pen/zYYyEPg)
- [Jungle](https://codepen.io/uiswarup/pen/dyoyLOp)

### 500 (Internal Server) Error Page
- [500 Error Page](https://codepen.io/Souleste/pen/QWLxPPr)

</details>

## Hover

<details><summary>Click to expand..</summary>

- [Hover Plugin](https://github.com/IanLunn/Hover)

</details>

## UserAgent

<details><summary>Click to expand..</summary>

- [UserAgent Database](https://developers.whatismybrowser.com/useragents/explore/operating_platform/)

</details>

## Particle

<details><summary>Click to expand..</summary>

- [WebGL Particle Animation](https://codepen.io/kenjiSpecial/pen/vELOrM)

</details>

## Table

<details><summary>Click to expand..</summary>

- [Table 1](https://codepen.io/heypablete/pen/qdIsm)

</details>

## Sidebar

<details><summary>Click to expand..</summary>

- [Sidebar 1](https://codepen.io/azouaoui-med/pen/wpBadb)

</details>

## JSON

<details><summary>Click to expand..</summary>

- [JSON Viewer](http://jsonmaker.com/)

</details>

## Mouse Cursor

<details><summary>Click to expand..</summary>

- [CSS Cursors Guide](https://css-tricks.com/using-css-cursors/)
- [All available cursors](https://codepen.io/chriscoyier/pen/uCwfB)
- [Animation following cursor](https://codepen.io/tamm/pen/LIFam)
- [Sticky Cursor **HOT**](https://codepen.io/dev_loop/pen/abxJMxL)

</details>

## Mouse Cursor SVG Collection

<details><summary>Click to expand..</summary>

- [SVG Collection](https://mega.nz/file/y3pUUCZS#NPEm6f00U2VLweB0BXLL5yf5BUU53Ndd4f0b-TvW534)

</details>

## Spinner

<details><summary>Click to expand..</summary>

- [loading.io](https://loading.io/)
- [Spinner 1](https://codepen.io/ahmadbassamemran/pen/bXRPdr)
- [Spinner 2](https://codepen.io/akhil_001/pen/YqBZgL)
- [SpinKit](https://tobiasahlin.com/spinkit/)
- [Windows 10 Spinner](https://codepen.io/jenning/pen/rrkBbq)
- [Spinner 3](https://codepen.io/Godwin/pen/eWBzNX)
- [Big Circle 3d effect](https://codepen.io/mattbhenley/pen/gQgVxG)
- [Loader](https://codepen.io/PicturElements/pen/ZOwkwv)
- [Atom Loader](https://codepen.io/dmsanchez86/details/WxRovR)
- [Google Loader](https://codepen.io/AmineMohamed/pen/JZxyYm)
- [Spinner 4 **HOT**](https://codepen.io/grssam/details/nZyxQN)

</details>

## Tabs

<details><summary>Click to expand..</summary>

- [Tabs 1](https://codepen.io/RGonyeau/pen/Mvrzxx)
- [Tabs 2](https://codepen.io/jdniki/pen/PzZERJ)
- [Tabs 3](https://codepen.io/ejsado/pen/gPVgVv)
- [Tabs 4](https://codepen.io/creativetim/pen/EgVBXa)
- [Tabs 5](https://codepen.io/Danil89/pen/ONBoyG)
- [Vertical Tabs](https://codepen.io/juliepark/pen/pLMxoP)
- [Fullscreen Slideshow Tabs](https://codepen.io/pbutcher/pen/yLLKbNo)
- [Fullscreen Boxes Tabs](https://codepen.io/dtab428/pen/yYJKma)
- [Fullscreen Tabs](https://codepen.io/team/webflow/pen/dPeVaG)
- [Swipe Tabs](https://codepen.io/federico/pen/mRovqE)
- [Tabs 6](https://codepen.io/sean_codes/pen/QpoQMR)
- [Tabs 7](https://codepen.io/interstellar/pen/qaRJwm)

</details>

## Slider

<details><summary>Click to expand..</summary>

- [Gradient Slider](https://codepen.io/egrucza/pen/LEoOQZ)

</details>

## SVG Animation

<details><summary>Click to expand..</summary>

- [Lava Lamp](https://codepen.io/lukesmetham/pen/yJVwVr)
- [Developer with notebook](https://codepen.io/jeanoliveira/pen/ObWYmY)

</details>

## SVG Animations (Text)

<details><summary>Click to expand..</summary>

- [Text Animation 1](https://codepen.io/codecollective/pen/NqqENm)
- [Text Animation 2](https://codepen.io/gzmiraz/pen/XmqWWx)
- [Text Animation 3](https://codepen.io/mellis84/pen/JpVZNw)

</details>

## Buttons General

<details><summary>Click to expand..</summary>

- [3D Flip Glitch Buttons](https://codepen.io/cybert33n/pen/yXwZVx)
- [Button.css](https://codepen.io/kevinfan23/pen/BKbWxP)
- [Sci-fi Button](https://codepen.io/jeromefarnum/details/VLjxvW)
- [Hold to Verify Button](https://codepen.io/aaroniker/pen/WNNWQbM)
- [Button transition with 2 buttons](https://codepen.io/montechristos/pen/EPvOwJ)
- [Pulsing animated **HOT**](https://codepen.io/emileaublet/pen/PNvNma)
- [Call button **HOT**](https://codepen.io/get-web/pen/bGdVOWq)
- [General button **HOT**](https://codepen.io/simeydotme/pen/ZEgJoXB)
- [Pixel Canvas **HOT**](https://ryanmulligan.dev/blog/pixel-canvas/)
    -  [Github Repo](https://github.com/hexagoncircle/pixel-canvas)

</details>

## Dark/white Mode Button

<details><summary>Click to expand..</summary>

- [Dark/white Mode **HOT**](https://codepen.io/jh3y/pen/ByBjxrW)

</details>

## Text Verification

<details><summary>Click to expand..</summary>

- [Text Verification 1](https://codepen.io/AlikinVV/pen/WLpRdg)

</details>

## Success Button

<details><summary>Click to expand..</summary>

- [Confetti Button](https://codepen.io/aaroniker/pen/bGVGNrV)
- [With Loading](https://codepen.io/eliortabeka/pen/xOrQZA)
- [Success Button 1](https://codepen.io/colinhorn/pen/KXjYXr)
- [Success Button 2](https://codepen.io/guywald/details/AXwKqP)
- [Success Button 3](https://codepen.io/keenanpayne/details/YmKKer)
- [Success Button 4](https://codepen.io/ky0suke/pen/xwzNzp)

</details>

## Delete Button

<details><summary>Click to expand..</summary>

- [Delete Button 1](https://codepen.io/estrepitos/pen/JAtKr)

</details>

## Close Button

<details><summary>Click to expand..</summary>

- [Animated Close Buttons](https://codepen.io/JonasBadalic/pen/MYaMBz)

</details>

## Publish Button

<details><summary>Click to expand..</summary>

- [Hold to Verify](https://codepen.io/aaroniker/pen/BayaBpV)

</details>

## Download Button

<details><summary>Click to expand..</summary>

- [Download Button 1](https://codepen.io/aaroniker/pen/yRdoYN)
- [Download Button 2](https://codepen.io/lalit-mohan/pen/rrEzLp)
- [Download Button 3](https://codepen.io/thereyzer/pen/JqLdLr)
- [Download Button 4](https://codepen.io/aaroniker/pen/vYEmery)
- [Download Button 5](https://codepen.io/aaroniker/pen/KjJQER)

</details>

## Add to cart Button

<details><summary>Click to expand..</summary>

- [Add to cart Button](https://codepen.io/aaroniker/pen/QWWXKVP)

</details>

## Send Button

<details><summary>Click to expand..</summary>

- [Send Button](https://codepen.io/aaroniker/pen/BajabVN)

</details>

## Activate Button

<details><summary>Click to expand..</summary>

- [Activate Button](https://codepen.io/aaroniker/pen/ZVOrOZ)

</details>

## Upload Button

<details><summary>Click to expand..</summary>

- [Upload Button 1](https://codepen.io/balapa/pen/VYVedm)
- [With Pause](https://codepen.io/aaroniker/pen/QXxexJ)

</details>

## Order Placed Button

<details><summary>Click to expand..</summary>

- [Animation with truck 1](https://codepen.io/aaroniker/pen/eYOVrNa)
- [Animation with truck 2](https://codepen.io/aaroniker/pen/oNgPOwo)

</details>

## Chat UI

<details><summary>Click to expand..</summary>

- [Chat UI 1](https://codepen.io/Momciloo/pen/bEdbxY)

</details>

## Pagination

<details><summary>Click to expand..</summary>

- [Pagination 1](https://codepen.io/hakimel/details/gfIsk)
- [Pagination 2](https://codepen.io/netzzwerg/pen/hfutI)
- [Infinity Pagination](https://codepen.io/MarioD/pen/OmWaqz)
- [Svg Animated](https://codepen.io/chrisgannon/pen/xVOjZq)
- [Morphing Pagination](https://codepen.io/aaroniker/pen/pojXjrZ)

</details>

## Percentage Bar

<details><summary>Click to expand..</summary>

- [Animated Circle](https://codepen.io/like-a-boss/pen/pgqgKq)
- [Multiple Charts](https://codepen.io/FilipDanic/pen/xbgbaQ)

</details>

## Scroll Animation

<details><summary>Click to expand..</summary>

- [Scroll Animation](https://codepen.io/GreenXIII/pen/VKbNWV)

</details>

## One Page

<details><summary>Click to expand..</summary>

- [One Page 1](https://codepen.io/Cutcopy/pen/LpBPLe)

</details>

## Hamburger Menu Animation

<details><summary>Click to expand..</summary>

- [Hamburger Menu Animation](https://codepen.io/ahmadbassamemran/pen/abopOMY)

</details>

## Menubar Mobile

<details><summary>Click to expand..</summary>

- [Mobile Menubar 1](https://codepen.io/7ssan91/pen/dqLmpP)
- [Mobile Menubar 2](https://codepen.io/raffaele-filiberti/pen/mPQqVW)
- [Mobile Menubar 3](https://codepen.io/cateelderflower/pen/jwVPGd)

</details>

## Menubar Desktop

<details><summary>Click to expand..</summary>

- [Desktop Menubar 1](https://codepen.io/will627/pen/ehEpA)
- [Desktop Menubar 2](https://codepen.io/ejsado/pen/gPVgVv)
- [Desktop Menubar 3](https://codepen.io/littlesnippets/pen/BLjjVX)
- [Desktop Menubar 4](https://codepen.io/littlesnippets/pen/pjKeyq)
- [Desktop Menubar 5](https://codepen.io/jordiorriols/pen/OXbYKO)
- [Animated fullscreen](https://codepen.io/duchailu/pen/evprLy)
- [Fullscreen 1](https://codepen.io/fluxus/pen/gPWvZm)
- [Fullscreen 2](https://codepen.io/bosworthco/pen/RjBvgw)
- [3D Dropdown](https://codepen.io/soulwire/pen/EKmwC)
- [Desktop Menubar 6](https://codepen.io/littlesnippets/pen/gPGvLq)
- [Desktop Menubar 7](https://codepen.io/yasinburakkalkan/pen/jPaXgb)
- [Desktop Menubar 8](https://codepen.io/littlesnippets/pen/OMXYaG)

</details>

## Sidebar Menu

<details><summary>Click to expand..</summary>

- [Sidebar Menu 1](https://codepen.io/jcoulterdesign/pen/qdWxEm)

</details>

## Hover

<details><summary>Click to expand..</summary>

- [Button hover effects](https://codepen.io/giana/pen/BZaGyP)

</details>

## Social Media

<details><summary>Click to expand..</summary>

- [Social Media 1](https://codepen.io/nouribram/pen/WNQzoOd)
- [Social Media 2](https://codepen.io/daniel_wolf/pen/mJRmaQ)
- [Social Media 3](https://codepen.io/FrankieDoodie/pen/dqmKrb)
- [3D Cubes with Hover](https://codepen.io/gabriellewee/pen/Qdpgwx)
- [Hover with tooltip](https://codepen.io/kieranfivestars/pen/gbOWbM)

</details>

## Converter

<details><summary>Click to expand..</summary>

- [Google Fonts Offline Downloader](https://google-webfonts-helper.herokuapp.com)
- [Image Compressor](https://imagecompressor.com)
- [CSS Auto Prefixer](https://autoprefixer.github.io/)

</details>

## Anime.js

<details><summary>Click to expand..</summary>

- [Animated Letters](https://tobiasahlin.com/moving-letters/)
- [Staggering](https://codepen.io/juliangarnier/pen/XvjWvx)
- [Login Box](https://codepen.io/ainalem/pen/EQXjOR)
- [Submit Button](https://codepen.io/andrewmillen/pen/MoKLob)
- [Animated Hand Signature](https://codepen.io/mellis84/pen/JpVZNw)

</details>

## Animated Objects

<details><summary>Click to expand..</summary>

- [Animation Plugin](https://animate.style/)

</details>

## Cards

<details><summary>Click to expand..</summary>

- [Card 1](https://codepen.io/drehimself/pen/WwZrPR)
- [Card 2](https://codepen.io/iMax723/pen/aNKQyE)
- [Card 3](https://codepen.io/littlesnippets/pen/VvorBN)
- [With flip](https://codepen.io/keithpickering/pen/XJeJMv)
- [Profile card 1](https://codepen.io/team/jotform/details/XWmqoMp)
- [Profile card 2](https://codepen.io/littlesnippets/pen/VvOwbw)
- [Nice Border](https://codepen.io/HugoGiraudel/pen/FBbDd)
- [3d flip](https://codepen.io/kharrop/pen/zBjBLx)
- [Multilayer with animation](https://codepen.io/jebbles/pen/MKoYya)
- [Responsive card slider](https://codepen.io/JavaScriptJunkie/pen/WgRBxw)
- [Gradient **HOT**](https://codepen.io/kristen17/pen/NPKrxBd)
- [Gradien Border **HOT**](https://codepen.io/jh3y/pen/WNmQXyE)

</details>

## Typing

<details><summary>Click to expand..</summary>

- [Typing animation](https://codepen.io/Zhouzi/pen/JoRazP)

</details>

## Success

<details><summary>Click to expand..</summary>

- [Modal Box animated](https://codepen.io/hynden/pen/qlsJy)
- [Success 1](https://codepen.io/souporserious/pen/MwmXdg)
- [Success 2](https://codepen.io/ethanthompson/pen/vpWOmN)
- [Modal Box not animated](https://codepen.io/iheartkode/pen/yJBBZZ)
- [Success 3](https://codepen.io/wallaceho/details/vxLbRO)
- [Success 4](https://codepen.io/sawyer22/pen/bdOoGX)
- [Success 5](https://codepen.io/InaCarine/pen/RJoepK)
- [Success 6](https://codepen.io/zhangshupi88/pen/zvWEMm)
- [Success 7](https://codepen.io/petsto/pen/XaZRGZ)
- [Envelope](https://codepen.io/HamishMW/pen/XJogMg)

</details>

## Success & Error

<details><summary>Click to expand..</summary>

- [Animated characters](https://codepen.io/juliepark/pen/vjMOKQ)
- [Tooltips 1](https://codepen.io/veronicadev/pen/LrZaov)
- [Success & Error 1](https://codepen.io/MariamSalloum/pen/PBxKzd)
- [Tooltips 2](https://codepen.io/prallen/details/AsECw)

</details>

## Logo

<details><summary>Click to expand..</summary>

- [Logo 1](https://codepen.io/mkmueller/pen/dCEhA)
- [Orbit Logo](https://codepen.io/guerreiro/pen/obhzc)
- [Free Vector logos with backlink](https://www.freepik.com/search?format=search&page=2&query=search+engine)
- [Free Vector logos with backlink 2](pngtree.com)

</details>

## 3D

<details><summary>Click to expand..</summary>

- [Card with mouse follow](https://codepen.io/lembitk/pen/EVmqmY)
- [3D 1](https://codepen.io/yotman/pen/VEzXJp)
- [Image Carousel](https://codepen.io/hoanghien0410/pen/MMPaqm)
- [Glassomorphic logo](https://codepen.io/konstantindenerz/pen/VwoEJqP)
- [Three.js cards](https://codepen.io/smcnally000/pen/eYqXWyJ)

</details>

## Newsletter

<details><summary>Click to expand..</summary>

- [Animation mailbox](https://codepen.io/lerida/pen/BaoRRbp)
- [Newsletter 1](https://codepen.io/YarivFrd/pen/NXomOV)

</details>

## Timeline

<details><summary>Click to expand..</summary>

- [Animated timeline](https://codepen.io/vincebrown/pen/BNazqL)

</details>

## Sign-in

<details><summary>Click to expand..</summary>

- [Sign-in 1](https://codepen.io/marcobiedermann/pen/Fybpf)
- [Sign-in 2](https://codepen.io/mycnlz/details/aNNExj)
- [Sign-in 3](https://codepen.io/yildirimzlm/pen/aRjOGM)
- [Full page with bg](https://codepen.io/carsonf92/pen/pNWGXG)
- [Mobile](https://codepen.io/suez/pen/dPqxoM)
- [Perspective animation](https://codepen.io/jcoulterdesign/pen/azepmX)
- [3D perspective](https://codepen.io/jenning/pen/RVRYeb)

</details>

## Create password

<details><summary>Click to expand..</summary>

- [Create Password](https://codepen.io/davidkpiano/pen/WKvPBP)

</details>

## Sign-up

<details><summary>Click to expand..</summary>

- [Sign-up Button](https://codepen.io/vineethtrv/pen/ZBpebQ)

</details>

## Sign-in & Sign-up

<details><summary>Click to expand..</summary>

- [Sign-in & Sign-up 1](https://codepen.io/joshsorosky/pen/gaaBoB)
- [Sign-in & Sign-up 2](https://codepen.io/andytran/pen/GpyKLM)
- [Sign-in & Sign-up 3](https://codepen.io/hurick/pen/Kyrvrj)
- [Sign-in & Sign-up 4](https://codepen.io/kvaibhav01/pen/PgRgzv)
- [Sign-in & Sign-up 5](https://codepen.io/dpinnick/pen/LjdLmo)
- [Sign-in & Sign-up 6](https://codepen.io/GrandvincentMarion/pen/epEPjp)
- [Sign-in & Sign-up 7](https://codepen.io/dpinnick/pen/LjdLmo)
- [3d box with all forms together](https://codepen.io/nourabusoud/pen/BxJbjJ)
- [Fullscreen Sign-in & Sign-up](https://codepen.io/m2creates/pen/EEvGgW)
- [Sign-in & Sign-up 8](https://codepen.io/FlorinPop17/pen/vPKWjd)
- [Sign-in & Sign-up 9](https://codepen.io/andytran/pen/RPBdgM)
- [Material Design small **HOT**](https://codepen.io/rkpasia/pen/LNEQod)

</details>

## Footer

<details><summary>Click to expand..</summary>

- [Footer 1](https://codepen.io/z-/details/zYxdRQy)
- [Animated city](https://codepen.io/uiswarup/pen/oNNMedZ)
- [Parallax effect](https://codepen.io/maheshc/details/pCwxs)
- [Footer 2](https://codepen.io/Alioos_90/pen/VPbzpy)
- [Footer 3](https://codepen.io/magnusriga/pen/bKbWjx)

- [Footer 5](https://codepen.io/jilliannichols/pen/EVxLRm)
- [Footer 6](https://codepen.io/bhorsey/pen/PzPwBB)
- [Footer 7](https://codepen.io/abdelfattahbaraka/pen/rwbewP)
- [Footer 8](https://codepen.io/devdojo/pen/WNbepgJ)
- [Footer 9](https://codepen.io/Mohamed-Anwar97/pen/VwedNpR)
- [Footer 10](https://codepen.io/rhythm19/pen/RwWdKrL)
- [Footer 11](https://codepen.io/itaditya/pen/ejEYxd)
- [With Google Maps](https://codepen.io/maskit_jr/pen/EZzqYV)
- [Footer 12](https://codepen.io/nizamrobin/pen/WdoPbN)
- [Footer 13](https://codepen.io/ntoye/pen/XVGVPX)
- [Footer 14](https://codepen.io/beacrea/pen/rRWKjY)
- [Footer 15](https://codepen.io/marekzelinka/pen/VzZNVz)
- [Footer 16](https://codepen.io/salah-alden-alsalama/pen/BajWRqq)
- [Footer 17](https://codepen.io/niloydeysarkar/details/KOmbZV)
- [Footer 18](https://codepen.io/felipoliveira_/pen/WpoNgZ)
- [Footer 19](https://codepen.io/tsumetaieien/pen/rNxzgmK)
- [Footer 20](https://codepen.io/brusky/pen/yLNLMzd)

</details>

## Checkbox

<details><summary>Click to expand..</summary>

- [Checkbox 1](https://codepen.io/alexjoffroy/pen/ORXOmR)

</details>

## Testimonial

<details><summary>Click to expand..</summary>

- [Slider 1](https://codepen.io/shamim539/pen/GZPZBp)
- [Slider 2](https://codepen.io/Aashima/pen/WdQQMr)
- [Static 1](https://codepen.io/littlesnippets/pen/EVLJVa)
- [Static 2](https://codepen.io/littlesnippets/pen/yejzvR)
- [Static 3](https://codepen.io/littlesnippets/pen/yOvZPV)
- [Static 4](https://codepen.io/littlesnippets/pen/QjXVrV)

</details>

## Image Carousel

<details><summary>Click to expand..</summary>

- [Owl Carousel Plugin](https://owlcarousel2.github.io/OwlCarousel2/)
- [Carousel 1](https://codepen.io/ccallen001/pen/bEYByd)
- [3D Carousel](https://codepen.io/iamdavid/details/CDluy)
- [Carousel 2](https://codepen.io/lmgonzalves/details/djEgmv)
- [Fullscreen vertical](https://codepen.io/mxbck/pen/ERNwBy)
- [Fullscreen 1](https://codepen.io/Alca/pen/VByeJd)
- [Fullscreen vertical image distortion](https://codepen.io/ashthornton/details/KRQbMO)
- [Fullscreen 2](https://codepen.io/lmgonzalves/pen/djEgmv)

</details>

## Image Gallery

<details><summary>Click to expand..</summary>

- [Gallery 1](https://codepen.io/andata/pen/pEyAGj)
- [Responsive Vertical Scrolling Parallax Gallery **HOT**](https://codepen.io/noirsociety/pen/NWJvgZg)

</details>

## Image Transitions

<details><summary>Click to expand..</summary>

- [Image Transitions 1](https://codepen.io/sfi0zy/pen/OQOExE)

</details>

## Border Animation

<details><summary>Click to expand..</summary>

- [Border Animation 1](https://codepen.io/Rplus/pen/lEDBj)
- [Border Animation 2](https://codepen.io/uiswarup/pen/RBByzW)
- [Border Animation 3](https://codepen.io/littlesnippets/pen/oLajBa)
- [Gradient Border](https://codepen.io/mike-schultz/pen/NgQvGO)
- [Border Animation 4 **HOT**](https://codepen.io/pineappleSyrup/pen/gNdERJ)
- [Border Animation 5 **HOT**](https://codepen.io/ZachSaucier/pen/nMRbQN)
- [Border Animation 6 **HOT**](https://codepen.io/Huhtamaki/pen/GPzwPY)

</details>

## Text Animation

<details><summary>Click to expand..</summary>

- [Text Animation 1](https://codepen.io/team/keyframers/pen/vYNyWwQ)
- [Text Animation 2](https://codepen.io/KaioRocha/pen/YoEVvZ)

</details>

## Popup

<details><summary>Click to expand..</summary>

- [Popup 1](https://codepen.io/melnik909/pen/QModrM)

</details>

## Background

<details><summary>Click to expand..</summary>

- [Background Generator](https://loading.io/background/)
- [Bridge with clouds](coming soon)
- [Desert sun goes down svg](https://codepen.io/Unleashed-Design/pen/VNpjrW)
- [Gradient Collections](https://uigradients.com/#Mystic)
- [Animated Background](https://codepen.io/juliangarnier/pen/ZeEpgd)
- [Background Color Change](https://codepen.io/alexzaworski/pen/mEkvAG)
- [Background 1](https://codepen.io/matth12377/pen/gwXBGy)
- [Animated Stars](https://codepen.io/shinkeo/pen/XgRqeR)
- [Parallax triangle figure](https://codepen.io/semenchenko/pen/JpXVgG)
- [Parallax Mouse follow with stars bg](https://codepen.io/ybprogrammer/pen/PGNBXJ)
- [Animated waves](https://codepen.io/miguelog/pen/amoWgy)
- [Endless horizontal Loop of Image](https://codepen.io/asfarmed/pen/cfslr)
- [Moving circles and squares](https://codepen.io/tokyoweb/pen/ZjdYVj)
- [Waves bottom](https://codepen.io/abelhancock/pen/aKxmLY)
- [Moving Logos on servers](https://codepen.io/koshik-ojha/pen/LXzXyx)
- [Moving Circles](https://codepen.io/Nathanmc4pg/pen/GdKLdY)
- [Solar System](https://codepen.io/kowlor/pen/ZYYQoy)
- [Spread](https://codepen.io/roboshoes/pen/ydipI)
- [Animated Person](https://codepen.io/yahiarefaiea/pen/xyNWQq)
- [Animated stars fall down from sky](https://codepen.io/chriscourses/pen/PzONKR)
- [Planet bg](https://codepen.io/carsonf92/pen/pNWGXG)
- [Planet bg v2](https://codepen.io/MoodyBoles/pen/KVodmp)
- [Three.js mutating field](https://codepen.io/Samsy/pen/emWppX)
- [POV moving hills ride](https://codepen.io/ykob/pen/aBrjaR)
-  [Infinite Falling Illusion | WebGL Shader **HOT**](https://codepen.io/pjkarlik/pen/mybEwjG)

</details>

### WebGL Backgrounds

<details><summary>Click to expand..</summary>

- [WebGL Fluid Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation)
- [Vanta.js **HOT**](https://www.vantajs.com/?effect=trunk)

</details>

### Canvas Backgrounds

<details><summary>Click to expand..</summary>

- [AmbientCanvasBackgrounds](https://github.com/crnacura/AmbientCanvasBackgrounds?tab=readme-ov-file)

</details>

### Background Images (cc0)

<details><summary>Click to expand..</summary>

- [Developer on bench](https://pixabay.com/photos/work-workaholic-writer-programmer-1627703/)

</details>

### Animated Gradient Background

<details><summary>Click to expand..</summary>

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


</details>



</details>

