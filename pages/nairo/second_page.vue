<template>
  <div class="body">
    <nav id="documenter-nav" class="documenter-nav">
      <div id="tm-logo">
        <h3>Nairo</h3>
      </div>
      <br />
      <ul class="navigation">
        <li><a class="current_nav" href="#start">Start</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#html_structure">HTML Structure</a></li>
        <li><a href="#customization">Customization</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#css_files_and_structure">CSS Files and Structure</a></li>
        <li><a href="#sources_and_credits">Sources and Credits</a></li>
      </ul>
      <footer id="footer"></footer>
    </nav>
    <!-- Start Documenter Content -->
    <div id="documenter-content" class="documenter-content">
      <section id="start">
        <div class="heading">
          <h6>
            Nairo – Tailwind CSS Portfolio Template Documentation by pxdraft
          </h6>
          <h1>"Nairo – Tailwind CSS Portfolio Template"</h1>
        </div>
        <!--/ .heading-->
        <table class="table-description">
          <tr>
            <td class="desc-column-1">
              <span class="author-created"
                ><br />
                version:1.0 <br />
                By: pxdraft
              </span>
              <span class="author-link"
                ><a
                  href="https://themeforest.net/user/pxdraft/portfolio"
                  target="_blank"
                  >https://themeforest.net/user/pxdraft/portfolio</a
                ></span
              >
            </td>
            <td class="desc-column-2">
              <blockquote>
                <span>Thank you for purchasing my template.</span> If you have
                any questions that are beyond the scope of this help file,
                please feel free to contact me.<br />
                sage.kv4@gmail.com
                <br />
                <span>Thank you!</span>
              </blockquote>
            </td>
          </tr>
        </table>
        <!--/ .table-description-->
      </section>
      <!-- Start Installation -->
      <section id="installation">
        <h1>Installation</h1>
        <p>Follow the steps below to get started with your Site Template:</p>
        <ol>
          <li>
            Open the <code class="custom">Nairo</code> Folder to find all the
            Template Files
          </li>
          <li>
            You will need to Upload these files to your Web Server using FTP in
            order to use it on your Website.
          </li>
          <li>
            Make sure you upload the required files/folders listed below:
            <ul>
              <li>
                <code class="custom">index.html</code> - Index File/Homepage
              </li>
              <li><code class="custom">assets/css</code> - CSS Folder</li>
              <li><code class="custom">assets/img</code> - Images Folder</li>
              <li><code class="custom">assets/js</code> - Javacripts Folder</li>
              <li>
                <code class="custom">assets/vendor</code> - Pvendor Folder
              </li>
            </ul>
          </li>
          <li>
            You're now good to go..! Start adding your Content and show off your
            Beautiful Personal Website in style.
          </li>
        </ol>
      </section>
      <!-- End Installation -->
      <!-- Start Features -->
      <section id="features">
        <h1>Features</h1>
        Nairo is an awesome vCard, CV, Resume & Portfolio template. it is
        suitable for anyone who wants to have a personalized resume website with
        unique style, layout and colors. all code are well commented and super
        easy to customize. This flexible template uses fresh and clean design
        and allows to change it’s look to your liking in one click.<br />
        Here is the list of its features :
        <ul>
          <li>Responsive Layout</li>
          <li>SCSS included</li>
          <li>Smoooth Transitions</li>
          <li>Clean Code</li>
          <li>W3C Validated</li>
          <li>HTML5 & CSS3</li>
          <li>Cross Browser Compatible</li>
          <li>100% Customizable, all colors can be customized</li>
          <li>Font Awesome Icons</li>
          <li>Well-commented code</li>
        </ul>
      </section>
      <!-- End Features -->
      <!-- Start HTML Structure -->
      <section id="html_structure">
        <h1>HTML Structure</h1>
        <p>
          The template is based on Tailwind CSS-
          <a target="_blank" href="https://tailwindcss.com/"
            >https://tailwindcss.com/</a
          >
        </p>
        <hr />
        <img src="../../assets/second_page_images/code.png" title="" alt="">
        
        <hr />
      </section>
      <!-- End HTML Structure -->
      <!-- Start Customization -->
      <section id="customization">
        <h2>Setting up Dev Tools</h2>
        <p>
          Unzip the theme package to any folder and open a command line at that
          location.
        </p>
        <p>
          Please checkout Tailwind CSS official document for more details:
          <a
            href="https://tailwindcss.com/docs/installation/using-postcss"
            target="_blank"
            >https://tailwindcss.com/docs/installation/using-postcss</a
          >
        </p>
        <pre
          class="bg-gray-100 border rounded-lg p-3"
        ><code class="custom">npm install</code></pre>
        <pre
          class="bg-gray-100 border rounded-lg p-3"
        ><code class="custom">npm run dev</code></pre>
        <p></p>
        <p>
          While the npm run dev command is running, files in the
          <code class="custom">src/main.css</code> folders will be monitored for
          changes. Files from the
          <code class="custom">dist/assets/css/main.css</code> changes will
          generate injected CSS.
        </p>
        <p>
          Hit <code>CTRL+C</code> to terminate. This will stop the local server
          from running.
        </p>
      </section>
      <!-- End Customization -->
      <!-- Start Contact -->
      <section id="contact">
        <h1>Contact</h1>
        <p>
          In order to receive emails in your inbox, open
          <code class="custom">process_form.php</code> and go to Line 14 : and
          replace <code class="custom">youremail@mail.com</code> with your
          email, that's all !
        </p>
      </section>
      <!-- End Contact -->
      <!-- Start CSS Files and Structure -->
      <section id="css_files_and_structure">
        <h1>Folder Structure</h1>
        <pre class="brush: xml">
                |── templete-doc
                |  |── Document files
                |── templete
                |───|─ dist
                |───|─ src (Tailwind css file)
                |───|─ dist
                    |  |── assets
                    |  |  | css
                    |  |  | img
                    |  |  | js
                    |  |  | vendor
                    |  |── index.html
                |  |──postcss.config.js
                |  |──tailwind.config.js
                |  |──package.json
           </pre
        >
      </section>
      <!-- End CSS Files and Structure -->
      <!-- Start Sources and Credits -->
      <section id="sources_and_credits">
        <h1>Sources and Credits</h1>
        <ul>
          <li>
            <strong>font-awesome.min.css</strong> :
            <a target="_blank" href="https://fontawesome.com/"
              >https://fontawesome.com/</a
            >
          </li>
          <li>
            <strong>Tailwind CSS</strong> :
            <a target="_blank" href="https://tailwindcss.com/"
              >https://tailwindcss.com/</a
            >
          </li>
          <li>
            <strong>magnific</strong> :
            <a
              target="_blank"
              href="http://dimsemenov.com/plugins/magnific-popup/"
              >http://dimsemenov.com/plugins/magnific-popup/</a
            >
          </li>
          <li>
            <strong>owl-carousel</strong> :
            <a
              target="_blank"
              href="https://owlcarousel2.github.io/OwlCarousel2/"
              >https://owlcarousel2.github.io/OwlCarousel2/</a
            >
          </li>
          <li>
            <strong>themify-icons</strong> :
            <a target="_blank" href="https://themify.me/themify-icons"
              >https://themify.me/themify-icons</a
            >
          </li>
        </ul>
        <p>
          Thank you for stop and buy. I'd be glad to help you if you have any
          questions relating to this template. I will try to do my best to
          assist.
        </p>
        <p><strong>* * * * * Don't forget to rate * * * * *</strong></p>
      </section>
      <!-- End Sources and Credits -->
    </div>
    <!-- End Documenter Content
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
    <script>
    window.jQuery || document.write('<script src="js/jquery.min.js"><\/script>')
    </script>
    <script src="js/jquery.easing.1.3.min.js"></script>
    <script src="js/fancybox/jquery.fancybox.pack.js"></script>
    <script src="js/shCore.js"></script>
    <script src="js/shBrushCss.js"></script>
    <script src="js/shBrushXml.js"></script>
    <script src="js/shBrushJScript.js"></script>
    <script>
    SyntaxHighlighter.defaults['toolbar'] = false;
    SyntaxHighlighter.all();
    </script>
    <script src="js/custom.js"></script> -->
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped>
/* ---------------------------------------------------------------------- */
/*	Reset
/* ---------------------------------------------------------------------- */
/* ---------------------------------------------------------------------- */
/*	Reset
/* ---------------------------------------------------------------------- */
.body{
  color: #000 !important;
}
html,
body,
div,
span,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
abbr,
address,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
samp,
small,
strong,
sub,
sup,
var,
b,
i,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

nav ul,
nav ol {
  list-style: none;
  list-style-image: none;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

dt,
dd {
  display: inline-block;
}

a {
  margin: 0;
  padding: 0;
  font-size: 100%;
  outline: none;
  text-decoration: none;
  background: transparent;
  vertical-align: baseline;
}

a {
  color: #118ce7;
  text-decoration: underline;
}

section ul,
section ol {
  margin: 1.5em;
}

img {
  border: 0;
  height: auto;
  max-width: 100%;
  -ms-interpolation-mode: bicubic;
}

.not-ie img {
  -webkit-transition: all 0.25s linear;
  -moz-transition: all 0.25s linear;
  -ms-transition: all 0.25s linear;
  -o-transition: all 0.25s linear;
  transition: all 0.25s linear;
}
code.custom {
  background-color: #444444;
  color: #fff;
  padding: 0px 3px;
}
/* ---------------------------------------------------------------------- */
/*	Basic Elements
/* ---------------------------------------------------------------------- */

body {
  background-color: #fff;
 
  -webkit-font-smoothing: antialiased; /* Fix for webkit rendering */
  -webkit-text-size-adjust: 100%;
  font: 12px/1.5 Arial;
}

/* -------------------------------------------------- */
/*	Clearfix
	/* -------------------------------------------------- */

.clear {
  display: block;
  visibility: hidden;
  clear: both;
  overflow: hidden;
  width: 0;
  height: 0;
}

.clearfix:after {
  clear: both;
  display: block;
  visibility: hidden;
  height: 0;
  content: ".";
}

/* -------------------------------------------------- */
/*	General Classes
	/* -------------------------------------------------- */

.align-center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

.align-left {
  text-align: left;
}
.align-right {
  text-align: right;
}

.alignleft {
  float: left;
}
.alignright {
  float: right;
}

/* -------------------------------------------------- */
/*	Typography
	/* -------------------------------------------------- */

h1,
h2,
h3,
h4,
h5,
h6 {
  margin-bottom: 15px;
  color: #383838;
  font-weight: 300;
  line-height: 1.05;
  font-family: "Open Sans", sans-serif;
}

h1 {
  font-size: 36px;
}
h2 {
  font-size: 30px;
}
h3 {
  font-size: 24px;
}
h4 {
  font-size: 18px;
  margin-top: 20px;
}
h5 {
  font-size: 16px;
}
h6 {
  font-size: 14px;
  color: #828282;
  margin-top: 20px;
}

p {
  margin: 0 0 1.5em 0;
  padding: 0;
  line-height: 1.6em;
}

/* -------------------------------------------------- */
/*	Quotes
	/* -------------------------------------------------- */

blockquote {
  color: #a0a0a0;
  font-size: 18px;
  font-weight: 300;
  font-family: "Open Sans";
  font-style: italic;
}

blockquote span {
  color: #383838;
}

/* -------------------------------------------------- */
/*	Images
	/* -------------------------------------------------- */

.bordered {
  margin-top: 30px;
  margin-bottom: 45px;
  border: 5px solid #ddd;
}

/* -------------------------------------------------- */
/*	Dividers
	/* -------------------------------------------------- */

.separator {
  margin: 25px 0;
  width: 100%;
  height: 1px;
  background-color: #c9c9c9;
}

.divider {
  margin: 20px 0;
  width: 100%;
  height: 3px;
  background-color: #4c4c4c;
}

/* -------------------------------------------------- */
/*	Forms
	/* -------------------------------------------------- */

button,
input[type="button"],
input[type="reset"],
input[type="submit"] {
  cursor: pointer;
  -webkit-appearance: button;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  padding: 0;
  border: 0;
}

button,
input,
select,
textarea {
  margin: 0;
  border: none;
  vertical-align: baseline;
  font-size: 100%;
}

button {
  display: inline-block;
  margin-bottom: 15px;
  padding: 6px 13px;
  outline: none;
  background-color: #000;
  color: #fff;
  vertical-align: baseline;
  text-align: center;
  text-decoration: none;
  font: 11px/1.5 Arial;
  cursor: pointer;
}

label {
  display: inline-block;
  cursor: pointer;
}

p label {
  margin-left: 5px;
}

.not-ie input,
.not-ie textarea,
.not-ie select,
.not-ie button {
  -webkit-transition: all 0.25s linear;
  -moz-transition: all 0.25s linear;
  -ms-transition: all 0.25s linear;
  -o-transition: all 0.25s linear;
  transition: all 0.25s linear;
}

input[type="text"],
input[type="password"],
input[type="datetime"],
input[type="datetime-local"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="week"],
input[type="number"],
input[type="email"],
input[type="url"],
input[type="search"],
input[type="tel"],
input[type="color"],
textarea,
select {
  display: inline-block;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  border-radius: 0;
  padding: 9px 10px;
  width: 100%;
  outline: none;
  border-width: 1px;
  border-style: solid;
  border-color: #e1e1e1;
  background-color: #fdfdfd;
  color: #9f9f9f;
  font-size: 13px;
  font-weight: 100;
  font-family: "Oswald", sans-serif;
  -webkit-appearance: none;
}

input[type="text"]:hover,
input[type="password"]:hover,
input[type="datetime"]:hover,
input[type="datetime-local"]:hover,
input[type="date"]:hover,
input[type="month"]:hover,
input[type="time"]:hover,
input[type="week"]:hover,
input[type="number"]:hover,
input[type="email"]:hover,
input[type="url"]:hover,
input[type="search"]:hover,
input[type="tel"]:hover,
input[type="color"]:hover,
textarea:hover,
select:hover {
  border-color: #b4b4b4;
}

input[type="text"]:focus,
input[type="password"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="time"]:focus,
input[type="week"]:focus,
input[type="number"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="color"]:focus,
textarea:focus,
select:focus {
  border-color: #b4b4b4;
  -webkit-box-shadow: inset 2px 2px 1px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: inset 2px 2px 1px rgba(0, 0, 0, 0.1);
  box-shadow: inset 2px 2px 1px rgba(0, 0, 0, 0.1);
}

textarea {
  resize: both;
  min-height: 100px;
}

input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  line-height: normal;
}

input[type="image"],
input[type="submit"],
input[type="reset"],
input[type="button"],
input[type="radio"],
input[type="checkbox"] {
  width: auto;
}

/* Fix for Mobile Safari */
input[type="checkbox"] {
  -webkit-appearance: checkbox;
}
input[type="radio"] {
  -webkit-appearance: radio;
}

/* Chrome, Safari */
input::-webkit-input-placeholder,
textarea::-webkit-input-placeholder {
  color: #9f9f9f;
}

/* Firefox */
input:-moz-placeholder,
textarea:-moz-placeholder {
  color: #9f9f9f;
}

/* -------------------------------------------------- */
/*	Button
	/* -------------------------------------------------- */

.button {
  display: inline-block;
  margin-bottom: 15px;
  padding: 6px 13px;
  outline: none;
  color: #fff;
  vertical-align: baseline;
  text-align: center;
  text-decoration: none;
  font: 12px/1.5 Arial;
  cursor: pointer;

  -webkit-transition: all 0.25s linear;
  -moz-transition: all 0.25s linear;
  -ms-transition: all 0.25s linear;
  -o-transition: all 0.25s linear;
  transition: all 0.25s linear;
}

/* ---------------------------------------------------------------------- */
/*	Documenter Navigation
/* ---------------------------------------------------------------------- */

.documenter-nav {
  position: fixed;
  z-index: 100;
  top: 0;
  left: 0;
  padding-top: 10px;
  width: 232px;
  height: 100%;
  background-color: #f2f2f2;
  box-shadow: 1px 0 #ebebeb;
}

/* -------------------------------------------------- */
/*	Logo
	/* -------------------------------------------------- */

#tm-logo {
  display: block;
  padding: 15px 5px 50px 10px;
}

/* -------------------------------------------------- */
/*	Navigation
	/* -------------------------------------------------- */

.navigation li {
  position: relative;
  margin-top: -1px;
  border-top: 1px solid #ebebeb;
  border-right: 1px solid #ebebeb;
  border-bottom: 1px solid #ebebeb;
}

.navigation li {
  background: #f2f2f2;
}
.navigation {
  border-top: 1px solid #fff;
  padding-top: 1px;
}
.navigation li:after {
  position: absolute;
  bottom: 1px;
  width: 100%;
  left: -2px;
  height: 1px;
  -webkit-box-shadow: 2px 1px 0 #fff;
  -moz-box-shadow: 2px 1px 0 #fff;
  box-shadow: 2px 1px 0 #fff;
  content: "";
}

.navigation li:hover,
.navigation .current-nav {
  border-right-color: transparent;
}

.navigation a {
  position: relative;
  display: block;
  margin-top: 3px;
  margin-bottom: 3px;
  padding: 6px 32px 6px 10px;
  color: #383838;
  font-family: "Open Sans";
  text-decoration: none;
}

.navigation li:hover > a,
.navigation .current-nav a {
  background-color: #444444;
  color: #fff;
}

.navigation li a:after {
  position: absolute;
  top: 50%;
  right: 12px;
  margin-top: -6px;
  width: 12px;
  height: 12px;
  content: "";

  -webkit-transition: right 0.25s linear;
  -moz-transition: right 0.25s linear;
  -ms-transition: right 0.25s linear;
  -o-transition: right 0.25s linear;
  transition: right 0.25s linear;
}

.navigation a:hover:after,
.navigation .current-nav > a:after {
  right: 2px;
}

.navigation li:hover a:after,
.navigation .current-nav > a:after {
  background-position: 0 bottom;
}

/* -------------------------------------------------- */
/*	Footer
	/* -------------------------------------------------- */

#footer {
  padding: 10px 5px;
}

/* ---------------------------------------------------------------------- */
/*	Documenter Content
/* ---------------------------------------------------------------------- */

.documenter-content {
  position: absolute;
  right: 30px;
  left: 260px;
  padding: 0 10px 0 10px;
  z-index: 1;
  padding-bottom: 800px;
  padding-left: 20px;
  min-height: 100%;
  height: auto;
}

.documenter-content section {
  padding-top: 80px;
}

.documenter-content section:first-child {
  height: 800px;
  padding-top: 220px;
}

/* -------------------------------------------------- */
/*	Documenter Description
		/* -------------------------------------------------- */

.heading {
  display: block;
}

.heading h1 {
  margin-top: 45px;
  margin-bottom: 45px;
}

/* -------------------------------------------------- */
/*	Table Description
		/* -------------------------------------------------- */

.table-description {
  width: 100%;
  border-top: 3px solid #4c4c4c;
  border-bottom: 1px solid #c9c9c9;
}

.desc-column-1 {
  padding: 30px 20px 30px 0;
  width: 200px;
  border-right: 1px solid #c9c9c9;
}

.desc-column-1 .author-created {
  display: block;
  padding-top: 3px;
  padding-bottom: 16px;
  color: #828282;
  font-size: 11px;
}

.desc-column-1 .author-link {
  display: block;
  color: #ffb200;
  font-size: 11px;
}

.desc-column-2 {
  padding: 30px 45px 30px 40px;
}

.html_structure,
.html_logo,
.html_logo_css,
.html_navigation,
.html_cs,
.html_columns,
.html_sidebar,
.home_fullscreen,
.home_masonry,
.sub_blog,
.sub_image-post-slider,
.sub_video,
.feat_toggles,
.feat_info,
.feat_testimonials,
.feat_tooltips,
.feat_tabs,
.feat_block,
.feat_social,
.feat_list_or,
.feat_list_unor,
.feat_drop,
.feat_alert,
.feat_buttons,
.css_stuct,
.js_set {
  margin-bottom: 30px;
}

/* -------------------------------------------------- */
/*	Items Supports
	/* -------------------------------------------------- */

.items li {
  position: relative;
  display: inline-block;
  margin: 2px 1px 3px 1px;
  width: 107px;
  height: 48px;
  border-width: 1px;
  border-style: solid;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
  -webkit-box-shadow: 0 1px 0 1px rgba(0, 0, 0, 0.03),
    inset 0 1px rgba(255, 255, 255, 0.4);
  -moz-box-shadow: 0 1px 0 1px rgba(0, 0, 0, 0.03),
    inset 0 1px rgba(255, 255, 255, 0.4);
  box-shadow: 0 1px 0 1px rgba(0, 0, 0, 0.03),
    inset 0 1px rgba(255, 255, 255, 0.4);
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  line-height: 1;
}

.items .follow-twitter {
  border-color: #2b8bb8;
  text-shadow: -1px -1px 0 #439bc0;
  background: rgb(83, 189, 233); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(83, 189, 233, 1) 0%,
    rgba(67, 164, 209, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(83, 189, 233, 1)),
    color-stop(100%, rgba(67, 164, 209, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(83, 189, 233, 1) 0%,
    rgba(67, 164, 209, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(83, 189, 233, 1) 0%,
    rgba(67, 164, 209, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(83, 189, 233, 1) 0%,
    rgba(67, 164, 209, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(83, 189, 233, 1) 0%,
    rgba(67, 164, 209, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#53bde9', endColorstr='#43a4d1',GradientType=0 ); /* IE6-9 */
}

.items .follow-twitter:hover {
  background: rgb(67, 164, 209); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(67, 164, 209, 1) 0%,
    rgba(83, 189, 233, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(67, 164, 209, 1)),
    color-stop(100%, rgba(83, 189, 233, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(67, 164, 209, 1) 0%,
    rgba(83, 189, 233, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(67, 164, 209, 1) 0%,
    rgba(83, 189, 233, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(67, 164, 209, 1) 0%,
    rgba(83, 189, 233, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(67, 164, 209, 1) 0%,
    rgba(83, 189, 233, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#43a4d1', endColorstr='#53bde9',GradientType=0 ); /* IE6-9 */
}

.items .follow-facebook {
  border-color: #2c4480;
  text-shadow: -1px -1px 0 #3b589d;
  background: rgb(74, 109, 194); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(74, 109, 194, 1) 0%,
    rgba(60, 92, 167, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(74, 109, 194, 1)),
    color-stop(100%, rgba(60, 92, 167, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(74, 109, 194, 1) 0%,
    rgba(60, 92, 167, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(74, 109, 194, 1) 0%,
    rgba(60, 92, 167, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(74, 109, 194, 1) 0%,
    rgba(60, 92, 167, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(74, 109, 194, 1) 0%,
    rgba(60, 92, 167, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4a6dc2', endColorstr='#3c5ca7',GradientType=0 ); /* IE6-9 */
}

.items .follow-facebook:hover {
  background: rgb(60, 92, 167); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(60, 92, 167, 1) 0%,
    rgba(74, 109, 194, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(60, 92, 167, 1)),
    color-stop(100%, rgba(74, 109, 194, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(60, 92, 167, 1) 0%,
    rgba(74, 109, 194, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(60, 92, 167, 1) 0%,
    rgba(74, 109, 194, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(60, 92, 167, 1) 0%,
    rgba(74, 109, 194, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(60, 92, 167, 1) 0%,
    rgba(74, 109, 194, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#3c5ca7', endColorstr='#4a6dc2',GradientType=0 ); /* IE6-9 */
}

.items .subscribe-rss {
  border-color: #c37700;
  text-shadow: -1px -1px 0 #d89300;
  background: rgb(255, 174, 0); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(255, 174, 0, 1) 0%,
    rgba(228, 156, 0, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(255, 174, 0, 1)),
    color-stop(100%, rgba(228, 156, 0, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(255, 174, 0, 1) 0%,
    rgba(228, 156, 0, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(255, 174, 0, 1) 0%,
    rgba(228, 156, 0, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(255, 174, 0, 1) 0%,
    rgba(228, 156, 0, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(255, 174, 0, 1) 0%,
    rgba(228, 156, 0, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffae00', endColorstr='#e49c00',GradientType=0 ); /* IE6-9 */
}

.items .subscribe-rss:hover {
  background: rgb(228, 156, 0); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(228, 156, 0, 1) 0%,
    rgba(255, 174, 0, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(228, 156, 0, 1)),
    color-stop(100%, rgba(255, 174, 0, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(228, 156, 0, 1) 0%,
    rgba(255, 174, 0, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(228, 156, 0, 1) 0%,
    rgba(255, 174, 0, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(228, 156, 0, 1) 0%,
    rgba(255, 174, 0, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(228, 156, 0, 1) 0%,
    rgba(255, 174, 0, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#e49c00', endColorstr='#ffae00',GradientType=0 ); /* IE6-9 */
}

.items .get-support {
  border-color: #6d5152;
  text-shadow: -1px -1px 0 #7a5a5c;
  background: rgb(148, 109, 112); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(148, 109, 112, 1) 0%,
    rgba(128, 96, 98, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(148, 109, 112, 1)),
    color-stop(100%, rgba(128, 96, 98, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(148, 109, 112, 1) 0%,
    rgba(128, 96, 98, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(148, 109, 112, 1) 0%,
    rgba(128, 96, 98, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(148, 109, 112, 1) 0%,
    rgba(128, 96, 98, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(148, 109, 112, 1) 0%,
    rgba(128, 96, 98, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#946d70', endColorstr='#806062',GradientType=0 ); /* IE6-9 */
}

.items .get-support:hover {
  background: rgb(128, 96, 98); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(128, 96, 98, 1) 0%,
    rgba(148, 109, 112, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(128, 96, 98, 1)),
    color-stop(100%, rgba(148, 109, 112, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(128, 96, 98, 1) 0%,
    rgba(148, 109, 112, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(128, 96, 98, 1) 0%,
    rgba(148, 109, 112, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(128, 96, 98, 1) 0%,
    rgba(148, 109, 112, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(128, 96, 98, 1) 0%,
    rgba(148, 109, 112, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#806062', endColorstr='#946d70',GradientType=0 ); /* IE6-9 */
}

.items .support-tickets {
  border-color: #c54a2a;
  text-shadow: -1px -1px 0 #d05433;
  background: rgb(250, 104, 65); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(250, 104, 65, 1) 0%,
    rgba(235, 89, 50, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(250, 104, 65, 1)),
    color-stop(100%, rgba(235, 89, 50, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(250, 104, 65, 1) 0%,
    rgba(235, 89, 50, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(250, 104, 65, 1) 0%,
    rgba(235, 89, 50, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(250, 104, 65, 1) 0%,
    rgba(235, 89, 50, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(250, 104, 65, 1) 0%,
    rgba(235, 89, 50, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#fa6841', endColorstr='#eb5932',GradientType=0 ); /* IE6-9 */
}

.items .support-tickets:hover {
  background: rgb(235, 89, 50); /* Old browsers */
  background: -moz-linear-gradient(
    top,
    rgba(235, 89, 50, 1) 0%,
    rgba(250, 104, 65, 1) 100%
  ); /* FF3.6+ */
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(235, 89, 50, 1)),
    color-stop(100%, rgba(250, 104, 65, 1))
  ); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(
    top,
    rgba(235, 89, 50, 1) 0%,
    rgba(250, 104, 65, 1) 100%
  ); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(
    top,
    rgba(235, 89, 50, 1) 0%,
    rgba(250, 104, 65, 1) 100%
  ); /* Opera 11.10+ */
  background: -ms-linear-gradient(
    top,
    rgba(235, 89, 50, 1) 0%,
    rgba(250, 104, 65, 1) 100%
  ); /* IE10+ */
  background: linear-gradient(
    to bottom,
    rgba(235, 89, 50, 1) 0%,
    rgba(250, 104, 65, 1) 100%
  ); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#eb5932', endColorstr='#fa6841',GradientType=0 ); /* IE6-9 */
}

.items a {
  display: block;
  padding: 11px 6px 8px 37px;
  color: #fff;
  font-size: 13px;
}

.items .circle-logo {
  position: absolute;
  top: 50%;
  left: 6px;
  display: block;
  margin-top: -13px;
  width: 27px;
  height: 27px;
  background-image: url(../images/circle-logo.png);
  background-repeat: no-repeat;

  -webkit-backface-visibility: hidden;
  -webkit-perspective: 800px;
  -moz-perspective: 800px;
  -o-perspective: 800px;
  -ms-perspective: 800px;
  perspective: 800px;

  -webkit-transition: all 0.4s ease-in-out;
  -moz-transition: all 0.4s ease-in-out;
  -o-transition: all 0.4s ease-in-out;
  -ms-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
  -webkit-animation: rotateLeave 0.4s linear;
  -moz-animation: rotateLeave 0.4s linear;
  -ms-animation: rotateLeave 0.4s linear;
  -o-animation: rotateLeave 0.4s linear;
  animation: rotateLeave 0.4s linear;
}

.items li:hover .circle-logo {
  -webkit-animation: rotateEnter 0.4s linear;
  -moz-animation: rotateEnter 0.4s linear;
  -ms-animation: rotateEnter 0.4s linear;
  -o-animation: rotateEnter 0.4s linear;
  animation: rotateEnter 0.4s linear;
}

.items .get-support .circle-logo {
  background-position: 0 0;
}
.items .support-tickets .circle-logo {
  background-position: -27px 0;
}
.items .follow-twitter .circle-logo {
  background-position: -54px 0;
}
.items .follow-facebook .circle-logo {
  background-position: -81px 0;
}
.items .subscribe-rss .circle-logo {
  background-position: -108px 0;
}
.figure {
  border: 1px solid #ccc;
  padding: 3px;
}

/* -------------------------------------------------- */
/*	Animation
	/* -------------------------------------------------- */

/* MouseEnter */

@-webkit-keyframes rotateEnter {
  0% {
    -webkit-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -webkit-transform: rotate3d(0, 1, 0, 0);
  }
}

@-moz-keyframes rotateEnter {
  0% {
    -moz-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -moz-transform: rotate3d(0, 1, 0, 0);
  }
}

@-ms-keyframes rotateEnter {
  0% {
    -ms-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -ms-transform: rotate3d(0, 1, 0, 0);
  }
}

@-o-keyframes rotateEnter {
  0% {
    -o-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -o-transform: rotate3d(0, 1, 0, 0);
  }
}

@keyframes rotateEnter {
  0% {
    transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    transform: rotate3d(0, 1, 0, 0);
  }
}

/* MouseLeave */

@-webkit-keyframes rotateLeave {
  0% {
    -webkit-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -webkit-transform: rotate3d(0, 1, 0, 0);
  }
}

@-moz-keyframes rotateLeave {
  0% {
    -moz-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -moz-transform: rotate3d(0, 1, 0, 0);
  }
}

@-ms-keyframes rotateLeave {
  0% {
    -ms-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -ms-transform: rotate3d(0, 1, 0, 0);
  }
}

@-o-keyframes rotateLeave {
  0% {
    -o-transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    -o-transform: rotate3d(0, 1, 0, 0);
  }
}

@keyframes rotateLeave {
  0% {
    transform: rotate3d(0, 1, 0, 180deg);
  }
  50% {
    transform: rotate3d(0, 1, 0, 0);
  }
}
</style>
