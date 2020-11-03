<html>
<head><meta charset="utf-8" />

<title>Python SMIC - Showcase</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h1>Python for Finance Showcase</h1></p>
<p><h4>Author(s): Omar Pelcastre</h4></p>
<p><h3>SMIC - 2020</h3></p>
<p><hr></p>
<p>In this tutorial we will be going over basic security analysis using simple linear regression to determine the historical beta of a security against is broad market benchmark. In addition, towards the end of the notebook you will find an introduction to basic sentiment anlysis methods used to get and analyze specific security headlines from FinViz.

<i>This is not a comprehensive tutorial that should be used as a basis for any investing activity. SMIC is not liable for any loses you may incur from implemeting this material.</i></p>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2>Security Anlysis</h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h2>Getting Our Data</h2></p>
<p><hr></p>
<p>We first import the necessary libraries needed to derive basic statistics of the following securities. This section of the notebook will look at the behavior of the securities. Finally we will compare the securitie with the overall market stock benchmark to derive the historical beta of the security. The following is a list of all the necessary libraries you will need to have installed in your current environment/machine to follow along with this notebook.
</p><ul>
<li><a href="https://www.statsmodels.org/stable/regression.html">statsmodel</a></li>
<li><a href="https://pandas.pydata.org/docs/user_guide/index.html">pandas</a></li>
<li><a href="https://matplotlib.org/tutorials/index.html">matplotlib</a></li>
<li><a href="https://seaborn.pydata.org/">seaborn</a></li>
<li><a href="https://pypi.org/project/yfinance/">yfinance</a> </li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[302]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#data</span>
<span class="kn">import</span> <span class="nn">yfinance</span> <span class="k">as</span> <span class="nn">yf</span>

<span class="c1">#mathematical &amp; stats libraries</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">statsmodels.api</span> <span class="k">as</span> <span class="nn">sm</span>

<span class="c1">#visualization libraries</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sn</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">matplotlib.dates</span> <span class="k">as</span> <span class="nn">mdates</span>
<span class="o">%</span><span class="k">matplotlib</span> inline
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[303]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">start_date</span> <span class="o">=</span> <span class="s2">&quot;2015-11-01&quot;</span>
<span class="n">end_date</span> <span class="o">=</span> <span class="s2">&quot;2020-11-01&quot;</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[304]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#AMAZON</span>
<span class="n">amzn_df</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span> <span class="o">=</span> <span class="s2">&quot;AMZN&quot;</span><span class="p">,</span> <span class="n">start</span> <span class="o">=</span> <span class="n">start_date</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="n">end_date</span><span class="p">)</span>

<span class="c1">#PROCTER GAMBLE</span>
<span class="n">pg_df</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span> <span class="o">=</span> <span class="s2">&quot;PG&quot;</span><span class="p">,</span> <span class="n">start</span> <span class="o">=</span> <span class="n">start_date</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="n">end_date</span><span class="p">)</span>

<span class="c1">#SP500</span>
<span class="n">spy_df</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span> <span class="o">=</span> <span class="s2">&quot;SPY&quot;</span><span class="p">,</span> <span class="n">start</span> <span class="o">=</span> <span class="n">start_date</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="n">end_date</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>[*********************100%***********************]  1 of 1 completed
[*********************100%***********************]  1 of 1 completed
[*********************100%***********************]  1 of 1 completed
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[305]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="p">(</span><span class="n">ax1</span><span class="p">,</span> <span class="n">ax2</span><span class="p">,</span> <span class="n">ax3</span><span class="p">)</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">16</span><span class="p">,</span><span class="mi">4</span><span class="p">))</span>

<span class="n">ax1</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">amzn_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">amzn_df</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">])</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">amzn_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">,</span> <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;AMZN 5-Year Data&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_major_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_minor_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>

<span class="n">ax2</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">pg_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">pg_df</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">],</span><span class="n">color</span><span class="o">=</span><span class="s2">&quot;red&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">pg_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">,</span> <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;PG 5-Year Data&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_major_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_minor_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>

<span class="n">ax3</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">spy_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">spy_df</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">],</span><span class="n">color</span><span class="o">=</span><span class="s2">&quot;green&quot;</span><span class="p">)</span>
<span class="n">ax3</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">spy_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">,</span> <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
<span class="n">ax3</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;SPY 5-Year Data&quot;</span><span class="p">)</span>
<span class="n">ax3</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_major_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>
<span class="n">ax3</span><span class="o">.</span><span class="n">xaxis</span><span class="o">.</span><span class="n">set_minor_formatter</span><span class="p">(</span><span class="n">mdates</span><span class="o">.</span><span class="n">DateFormatter</span><span class="p">(</span><span class="s2">&quot;%m-</span><span class="si">%d</span><span class="s2">-%Y&quot;</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h2>Visualizing Historical Metrics</h2></p>
<p><hr></p>
<h3>Moving Average</h3><p>The Moving Average makes the line smooth and showcase the increasing or decreasing trend of stocks price. Moving Average showcases increasing trend the upturn or downturn of stocks price.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[306]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">adj_close_amzn</span> <span class="o">=</span> <span class="n">amzn_df</span><span class="p">[</span><span class="s1">&#39;Adj Close&#39;</span><span class="p">]</span>
<span class="n">mavg_amzn</span> <span class="o">=</span> <span class="n">adj_close_amzn</span><span class="o">.</span><span class="n">rolling</span><span class="p">(</span><span class="n">window</span><span class="o">=</span><span class="mi">50</span><span class="p">)</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="n">adj_close_amzn</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">label</span><span class="o">=</span><span class="s2">&quot;AMZN&quot;</span><span class="p">)</span>
<span class="n">mavg_amzn</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">label</span><span class="o">=</span><span class="s2">&quot;Moving Average&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;AMZN Price vs 20-Day Moving Average&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h3>Returns</h3></p>
<p><hr></p>
<p>By looking at the mean we can derive one form of the expected return of a security. There are a few other ways you can produce an expected return. For the purposes of this showcase, we will be using the mean return as the a proxy for expected return for each security. The following is the Investopedia definition of expected return:

<i>Expected Return measures the mean, or expected value, of the probability distribution of investment returns. The expected return of a portfolio is calculated by multiplying the weight of each asset by its expected return and adding the values for each investment — Investopedia</i></p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[307]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">amzn_rets</span> <span class="o">=</span> <span class="n">adj_close_amzn</span> <span class="o">/</span> <span class="n">adj_close_amzn</span><span class="o">.</span><span class="n">shift</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span>
<span class="n">amzn_rets</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">label</span><span class="o">=</span><span class="s1">&#39;AMZN 5-Year Monthly Returns&#39;</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h3>Security Comparison</h3></p>
<p><hr></p>
<p>We will be comparing 5 different securities along with the ETF the the SP 500 index to see if there are any patterns among the securites. We will be looking at their returns, standard deviation, and correlation to one another. Finally, we will see how much of the individual securities' returns are correlated to market returns (beta).</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[308]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">stock_comp</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;AMZN&#39;</span><span class="p">,</span><span class="s1">&#39;AAPL&#39;</span><span class="p">,</span><span class="s1">&#39;TSLA&#39;</span><span class="p">,</span><span class="s1">&#39;XOM&#39;</span><span class="p">,</span><span class="s1">&#39;PG&#39;</span><span class="p">,</span><span class="s1">&#39;SPY&#39;</span><span class="p">],</span>
                        <span class="n">start</span> <span class="o">=</span> <span class="n">start_date</span><span class="p">,</span>
                        <span class="n">end</span> <span class="o">=</span> <span class="n">end_date</span><span class="p">,</span>
                        <span class="n">interval</span><span class="o">=</span><span class="s2">&quot;1mo&quot;</span><span class="p">)[</span><span class="s1">&#39;Adj Close&#39;</span><span class="p">]</span>
<span class="n">stock_comp</span> <span class="o">=</span> <span class="n">stock_comp</span><span class="p">[[</span><span class="s1">&#39;AMZN&#39;</span><span class="p">,</span><span class="s1">&#39;AAPL&#39;</span><span class="p">,</span><span class="s1">&#39;TSLA&#39;</span><span class="p">,</span><span class="s1">&#39;XOM&#39;</span><span class="p">,</span><span class="s1">&#39;PG&#39;</span><span class="p">,</span><span class="s1">&#39;SPY&#39;</span><span class="p">]]</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">stock_comp</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>[*********************100%***********************]  6 of 6 completed
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt output_prompt">Out[308]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>AMZN</th>
      <th>AAPL</th>
      <th>TSLA</th>
      <th>XOM</th>
      <th>PG</th>
      <th>SPY</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2015-11-01</th>
      <td>664.799988</td>
      <td>27.330675</td>
      <td>46.051998</td>
      <td>65.459343</td>
      <td>64.421349</td>
      <td>189.159454</td>
    </tr>
    <tr>
      <th>2015-12-01</th>
      <td>675.890015</td>
      <td>24.422157</td>
      <td>48.001999</td>
      <td>63.030098</td>
      <td>68.355156</td>
      <td>184.790527</td>
    </tr>
    <tr>
      <th>2016-01-01</th>
      <td>587.000000</td>
      <td>22.584578</td>
      <td>38.240002</td>
      <td>62.949226</td>
      <td>70.317757</td>
      <td>176.635452</td>
    </tr>
    <tr>
      <th>2016-02-01</th>
      <td>552.520020</td>
      <td>22.433773</td>
      <td>38.386002</td>
      <td>64.808998</td>
      <td>69.715042</td>
      <td>176.489532</td>
    </tr>
    <tr>
      <th>2016-03-01</th>
      <td>593.640015</td>
      <td>25.424799</td>
      <td>45.953999</td>
      <td>68.204041</td>
      <td>71.468987</td>
      <td>187.394791</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[309]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">stock_rets</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>

<span class="k">for</span> <span class="n">stock</span> <span class="ow">in</span> <span class="n">stock_comp</span><span class="p">:</span>
    <span class="n">col_name</span> <span class="o">=</span> <span class="n">stock</span> <span class="o">+</span> <span class="s1">&#39;_ret&#39;</span>
    <span class="n">stock_rets</span><span class="p">[</span><span class="n">col_name</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">stock_comp</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span> <span class="o">/</span> <span class="n">stock_comp</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span><span class="o">.</span><span class="n">shift</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span><span class="p">)</span>

<span class="n">stock_rets</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[309]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>AMZN_ret</th>
      <th>AAPL_ret</th>
      <th>TSLA_ret</th>
      <th>XOM_ret</th>
      <th>PG_ret</th>
      <th>SPY_ret</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2015-11-01</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2015-12-01</th>
      <td>0.016682</td>
      <td>-0.106420</td>
      <td>0.042343</td>
      <td>-0.037111</td>
      <td>0.061064</td>
      <td>-0.023097</td>
    </tr>
    <tr>
      <th>2016-01-01</th>
      <td>-0.131516</td>
      <td>-0.075242</td>
      <td>-0.203366</td>
      <td>-0.001283</td>
      <td>0.028712</td>
      <td>-0.044131</td>
    </tr>
    <tr>
      <th>2016-02-01</th>
      <td>-0.058739</td>
      <td>-0.006677</td>
      <td>0.003818</td>
      <td>0.029544</td>
      <td>-0.008571</td>
      <td>-0.000826</td>
    </tr>
    <tr>
      <th>2016-03-01</th>
      <td>0.074423</td>
      <td>0.133327</td>
      <td>0.197155</td>
      <td>0.052385</td>
      <td>0.025159</td>
      <td>0.061790</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[310]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">stock_rets</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[310]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>AMZN_ret</th>
      <th>AAPL_ret</th>
      <th>TSLA_ret</th>
      <th>XOM_ret</th>
      <th>PG_ret</th>
      <th>SPY_ret</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>59.000000</td>
      <td>59.000000</td>
      <td>59.000000</td>
      <td>59.000000</td>
      <td>59.000000</td>
      <td>59.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>0.029379</td>
      <td>0.027499</td>
      <td>0.051349</td>
      <td>-0.008980</td>
      <td>0.013642</td>
      <td>0.010230</td>
    </tr>
    <tr>
      <th>std</th>
      <td>0.083049</td>
      <td>0.088267</td>
      <td>0.186074</td>
      <td>0.073353</td>
      <td>0.041628</td>
      <td>0.043363</td>
    </tr>
    <tr>
      <th>min</th>
      <td>-0.202192</td>
      <td>-0.184045</td>
      <td>-0.224266</td>
      <td>-0.251261</td>
      <td>-0.087538</td>
      <td>-0.129987</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>-0.021182</td>
      <td>-0.028538</td>
      <td>-0.067316</td>
      <td>-0.045862</td>
      <td>-0.013406</td>
      <td>-0.002401</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>0.026182</td>
      <td>0.040315</td>
      <td>0.026777</td>
      <td>-0.002259</td>
      <td>0.021002</td>
      <td>0.014293</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>0.078568</td>
      <td>0.086114</td>
      <td>0.120746</td>
      <td>0.039328</td>
      <td>0.041988</td>
      <td>0.032168</td>
    </tr>
    <tr>
      <th>max</th>
      <td>0.268900</td>
      <td>0.214380</td>
      <td>0.741452</td>
      <td>0.223861</td>
      <td>0.096596</td>
      <td>0.133611</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[311]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">for</span> <span class="n">stock</span> <span class="ow">in</span> <span class="n">stock_rets</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">stock</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;=&quot;</span><span class="o">*</span><span class="mi">35</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Monthly Avg Return: &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">stock_rets</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span><span class="mi">2</span><span class="p">))</span><span class="o">+</span><span class="s2">&quot;%&quot;</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Monthly Standard Dev.: &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">stock_rets</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">()</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span><span class="mi">2</span><span class="p">))</span><span class="o">+</span><span class="s2">&quot;%&quot;</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Annualized Return: &quot;</span><span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="nb">round</span><span class="p">(((</span><span class="mi">1</span><span class="o">+</span><span class="n">stock_rets</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span><span class="o">**</span><span class="mi">12</span><span class="o">-</span><span class="mi">1</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span><span class="mi">2</span><span class="p">))</span><span class="o">+</span><span class="s2">&quot;%&quot;</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Annualized Standard Dev.: &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="nb">round</span><span class="p">((</span><span class="n">stock_rets</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">()</span><span class="o">*</span><span class="n">np</span><span class="o">.</span><span class="n">sqrt</span><span class="p">(</span><span class="mi">12</span><span class="p">))</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span><span class="mi">2</span><span class="p">))</span><span class="o">+</span><span class="s2">&quot;%&quot;</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;=&quot;</span><span class="o">*</span><span class="mi">35</span><span class="o">+</span><span class="s2">&quot;</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>AMZN_ret
===================================
Monthly Avg Return: 2.94%
Monthly Standard Dev.: 8.3%
Annualized Return: 41.55%
Annualized Standard Dev.: 28.77%
===================================

AAPL_ret
===================================
Monthly Avg Return: 2.75%
Monthly Standard Dev.: 8.83%
Annualized Return: 38.48%
Annualized Standard Dev.: 30.58%
===================================

TSLA_ret
===================================
Monthly Avg Return: 5.13%
Monthly Standard Dev.: 18.61%
Annualized Return: 82.37%
Annualized Standard Dev.: 64.46%
===================================

XOM_ret
===================================
Monthly Avg Return: -0.9%
Monthly Standard Dev.: 7.34%
Annualized Return: -10.26%
Annualized Standard Dev.: 25.41%
===================================

PG_ret
===================================
Monthly Avg Return: 1.36%
Monthly Standard Dev.: 4.16%
Annualized Return: 17.66%
Annualized Standard Dev.: 14.42%
===================================

SPY_ret
===================================
Monthly Avg Return: 1.02%
Monthly Standard Dev.: 4.34%
Annualized Return: 12.99%
Annualized Standard Dev.: 15.02%
===================================

</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[312]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cumulative_returns</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>

<span class="k">for</span> <span class="n">stock</span> <span class="ow">in</span> <span class="n">stock_rets</span><span class="p">:</span>
    <span class="n">col_name</span> <span class="o">=</span> <span class="n">stock</span>
    <span class="n">cumulative_returns</span><span class="p">[</span><span class="n">col_name</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">stock_rets</span><span class="p">[</span><span class="n">stock</span><span class="p">]</span>
                                    <span class="o">.</span><span class="n">fillna</span><span class="p">(</span><span class="mi">100</span><span class="p">)</span>
                                    <span class="o">.</span><span class="n">cumsum</span><span class="p">())</span>

<span class="n">cumulative_returns</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[312]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>AMZN_ret</th>
      <th>AAPL_ret</th>
      <th>TSLA_ret</th>
      <th>XOM_ret</th>
      <th>PG_ret</th>
      <th>SPY_ret</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2015-11-01</th>
      <td>100.000000</td>
      <td>100.000000</td>
      <td>100.000000</td>
      <td>100.000000</td>
      <td>100.000000</td>
      <td>100.000000</td>
    </tr>
    <tr>
      <th>2015-12-01</th>
      <td>100.016682</td>
      <td>99.893580</td>
      <td>100.042343</td>
      <td>99.962889</td>
      <td>100.061064</td>
      <td>99.976903</td>
    </tr>
    <tr>
      <th>2016-01-01</th>
      <td>99.885166</td>
      <td>99.818338</td>
      <td>99.838977</td>
      <td>99.961606</td>
      <td>100.089776</td>
      <td>99.932772</td>
    </tr>
    <tr>
      <th>2016-02-01</th>
      <td>99.826427</td>
      <td>99.811661</td>
      <td>99.842795</td>
      <td>99.991150</td>
      <td>100.081204</td>
      <td>99.931946</td>
    </tr>
    <tr>
      <th>2016-03-01</th>
      <td>99.900850</td>
      <td>99.944988</td>
      <td>100.039950</td>
      <td>100.043536</td>
      <td>100.106363</td>
      <td>99.993736</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[313]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span><span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="n">cumulative_returns</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">ax</span><span class="o">=</span><span class="n">ax</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Cumulative Returns - 5 years&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">hlines</span><span class="p">(</span><span class="mi">100</span><span class="p">,</span><span class="n">start_date</span><span class="p">,</span><span class="n">end_date</span><span class="p">,</span><span class="n">linestyle</span><span class="o">=</span><span class="s2">&quot;dashed&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2>Correlation</h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[314]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">stock_rets</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[314]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>AMZN_ret</th>
      <th>AAPL_ret</th>
      <th>TSLA_ret</th>
      <th>XOM_ret</th>
      <th>PG_ret</th>
      <th>SPY_ret</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>AMZN_ret</th>
      <td>1.000000</td>
      <td>0.511991</td>
      <td>0.373145</td>
      <td>0.378384</td>
      <td>0.124704</td>
      <td>0.665900</td>
    </tr>
    <tr>
      <th>AAPL_ret</th>
      <td>0.511991</td>
      <td>1.000000</td>
      <td>0.503821</td>
      <td>0.281455</td>
      <td>0.344651</td>
      <td>0.643977</td>
    </tr>
    <tr>
      <th>TSLA_ret</th>
      <td>0.373145</td>
      <td>0.503821</td>
      <td>1.000000</td>
      <td>0.159957</td>
      <td>0.255151</td>
      <td>0.447844</td>
    </tr>
    <tr>
      <th>XOM_ret</th>
      <td>0.378384</td>
      <td>0.281455</td>
      <td>0.159957</td>
      <td>1.000000</td>
      <td>0.280123</td>
      <td>0.712919</td>
    </tr>
    <tr>
      <th>PG_ret</th>
      <td>0.124704</td>
      <td>0.344651</td>
      <td>0.255151</td>
      <td>0.280123</td>
      <td>1.000000</td>
      <td>0.385781</td>
    </tr>
    <tr>
      <th>SPY_ret</th>
      <td>0.665900</td>
      <td>0.643977</td>
      <td>0.447844</td>
      <td>0.712919</td>
      <td>0.385781</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[315]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">stock_rets</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span><span class="o">.</span><span class="n">corr</span><span class="p">(),</span><span class="n">ax</span><span class="o">=</span><span class="n">ax</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2>Linear Regression</h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[331]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">statsmodels</span> <span class="kn">import</span> <span class="n">regression</span>

<span class="n">X</span> <span class="o">=</span> <span class="n">stock_rets</span><span class="p">[</span><span class="s1">&#39;AAPL_ret&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">Y</span> <span class="o">=</span> <span class="n">stock_rets</span><span class="p">[</span><span class="s1">&#39;SPY_ret&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>

<span class="n">model</span> <span class="o">=</span> <span class="n">regression</span><span class="o">.</span><span class="n">linear_model</span><span class="o">.</span><span class="n">OLS</span><span class="p">(</span><span class="n">X</span><span class="p">,</span><span class="n">Y</span><span class="p">)</span><span class="o">.</span><span class="n">fit</span><span class="p">()</span>
<span class="n">model</span><span class="o">.</span><span class="n">summary</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[331]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<table class="simpletable">
<caption>OLS Regression Results</caption>
<tr>
  <th>Dep. Variable:</th>        <td>AAPL_ret</td>     <th>  R-squared (uncentered):</th>      <td>   0.445</td>
</tr>
<tr>
  <th>Model:</th>                   <td>OLS</td>       <th>  Adj. R-squared (uncentered):</th> <td>   0.435</td>
</tr>
<tr>
  <th>Method:</th>             <td>Least Squares</td>  <th>  F-statistic:       </th>          <td>   46.50</td>
</tr>
<tr>
  <th>Date:</th>             <td>Mon, 02 Nov 2020</td> <th>  Prob (F-statistic):</th>          <td>5.90e-09</td>
</tr>
<tr>
  <th>Time:</th>                 <td>23:36:57</td>     <th>  Log-Likelihood:    </th>          <td>  74.593</td>
</tr>
<tr>
  <th>No. Observations:</th>      <td>    59</td>      <th>  AIC:               </th>          <td>  -147.2</td>
</tr>
<tr>
  <th>Df Residuals:</th>          <td>    58</td>      <th>  BIC:               </th>          <td>  -145.1</td>
</tr>
<tr>
  <th>Df Model:</th>              <td>     1</td>      <th>                     </th>              <td> </td>   
</tr>
<tr>
  <th>Covariance Type:</th>      <td>nonrobust</td>    <th>                     </th>              <td> </td>   
</tr>
</table>
<table class="simpletable">
<tr>
     <td></td>        <th>coef</th>     <th>std err</th>      <th>t</th>      <th>P>|t|</th>  <th>[0.025</th>    <th>0.975]</th>  
</tr>
<tr>
  <th>SPY_ret</th> <td>    1.3846</td> <td>    0.203</td> <td>    6.819</td> <td> 0.000</td> <td>    0.978</td> <td>    1.791</td>
</tr>
</table>
<table class="simpletable">
<tr>
  <th>Omnibus:</th>       <td> 6.447</td> <th>  Durbin-Watson:     </th> <td>   2.264</td>
</tr>
<tr>
  <th>Prob(Omnibus):</th> <td> 0.040</td> <th>  Jarque-Bera (JB):  </th> <td>   5.761</td>
</tr>
<tr>
  <th>Skew:</th>          <td>-0.573</td> <th>  Prob(JB):          </th> <td>  0.0561</td>
</tr>
<tr>
  <th>Kurtosis:</th>      <td> 4.015</td> <th>  Cond. No.          </th> <td>    1.00</td>
</tr>
</table><br/><br/>Warnings:<br/>[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1>Sentiment Analysis</h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h2>Getting Our Data</h2></p>
<p><hr></p>
<p>We must first import all the necessary libraries needed to perform sentiment analysis, scrap web data, and create compelling visuals that will aid in conveying our message. The following is a list of all the necessary libraries you will need to have install in your current environment to follow along with this notebook.
</p><ul>
<li><a href="https://docs.python.org/3/library/urllib.html">urllib</a></li>
<li><a href="https://pypi.org/project/beautifulsoup4/">bs4</a></li>
<li><a href="https://docs.python.org/3/library/os.html#module-os">os</a></li>
<li><a href="https://pandas.pydata.org/docs/user_guide/index.html">pandas</a></li>
<li><a href="https://matplotlib.org/tutorials/index.html">matplotlib</a></li>
<li><a href="https://www.nltk.org/api/nltk.html">nltk</a></li>
<li><a href="https://pypi.org/project/yfinance/">yfinance</a> </li>
</ul>
<p>Citation:

<b>NLTK VADER</b> - Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[332]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">urllib.request</span> <span class="kn">import</span> <span class="n">urlopen</span><span class="p">,</span> <span class="n">Request</span>
<span class="kn">from</span> <span class="nn">bs4</span> <span class="kn">import</span> <span class="n">BeautifulSoup</span>
<span class="kn">import</span> <span class="nn">os</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="o">%</span><span class="k">matplotlib</span> inline

<span class="c1">#Get Price Data</span>
<span class="kn">import</span> <span class="nn">yfinance</span> <span class="k">as</span> <span class="nn">yf</span>

<span class="c1"># NLTK VADER for sentiment analysis</span>
<span class="kn">from</span> <span class="nn">nltk.sentiment.vader</span> <span class="kn">import</span> <span class="n">SentimentIntensityAnalyzer</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[333]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Web URL for our securities</span>
<span class="n">finwiz_url</span> <span class="o">=</span> <span class="s1">&#39;https://finviz.com/quote.ashx?t=&#39;</span>
<span class="n">tickers</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;TSLA&#39;</span><span class="p">,</span><span class="s1">&#39;NIO&#39;</span><span class="p">,</span><span class="s1">&#39;F&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[334]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">news_tables</span> <span class="o">=</span> <span class="p">{}</span>

<span class="k">for</span> <span class="n">ticker</span> <span class="ow">in</span> <span class="n">tickers</span><span class="p">:</span>
    <span class="n">url</span> <span class="o">=</span> <span class="n">finwiz_url</span> <span class="o">+</span> <span class="n">ticker</span>
    <span class="n">req</span> <span class="o">=</span> <span class="n">Request</span><span class="p">(</span><span class="n">url</span><span class="o">=</span><span class="n">url</span><span class="p">,</span><span class="n">headers</span><span class="o">=</span><span class="p">{</span><span class="s1">&#39;user-agent&#39;</span><span class="p">:</span> <span class="s1">&#39;my-app/0.0.1&#39;</span><span class="p">})</span> 
    <span class="n">response</span> <span class="o">=</span> <span class="n">urlopen</span><span class="p">(</span><span class="n">req</span><span class="p">)</span>    
    <span class="c1"># Read the contents of the file into &#39;html&#39;</span>
    <span class="n">html</span> <span class="o">=</span> <span class="n">BeautifulSoup</span><span class="p">(</span><span class="n">response</span><span class="p">)</span>
    <span class="c1"># Find &#39;news-table&#39; in the Soup and load it into &#39;news_table&#39;</span>
    <span class="n">news_table</span> <span class="o">=</span> <span class="n">html</span><span class="o">.</span><span class="n">find</span><span class="p">(</span><span class="nb">id</span><span class="o">=</span><span class="s1">&#39;news-table&#39;</span><span class="p">)</span>
    <span class="c1"># Add the table to our dictionary</span>
    <span class="n">news_tables</span><span class="p">[</span><span class="n">ticker</span><span class="p">]</span> <span class="o">=</span> <span class="n">news_table</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[335]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Read one single day of headlines for &#39;TSLA&#39; </span>
<span class="n">tsla</span> <span class="o">=</span> <span class="n">news_tables</span><span class="p">[</span><span class="s1">&#39;TSLA&#39;</span><span class="p">]</span>
<span class="c1"># Get all the table rows tagged in HTML with &lt;tr&gt; into &#39;tsla_tr&#39;</span>
<span class="n">tsla_tr</span> <span class="o">=</span> <span class="n">tsla</span><span class="o">.</span><span class="n">findAll</span><span class="p">(</span><span class="s1">&#39;tr&#39;</span><span class="p">)</span>

<span class="k">for</span> <span class="n">i</span><span class="p">,</span> <span class="n">table_row</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="n">tsla_tr</span><span class="p">):</span>
    <span class="c1"># Read the text of the element &#39;a&#39; into &#39;link_text&#39;</span>
    <span class="n">a_text</span> <span class="o">=</span> <span class="n">table_row</span><span class="o">.</span><span class="n">a</span><span class="o">.</span><span class="n">text</span>
    <span class="c1"># Read the text of the element &#39;td&#39; into &#39;data_text&#39;</span>
    <span class="n">td_text</span> <span class="o">=</span> <span class="n">table_row</span><span class="o">.</span><span class="n">td</span><span class="o">.</span><span class="n">text</span>
    <span class="c1"># Print the contents of &#39;link_text&#39; and &#39;data_text&#39; </span>
    <span class="nb">print</span><span class="p">(</span><span class="n">a_text</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">td_text</span><span class="p">)</span>
    <span class="c1"># Exit after printing 4 rows of data</span>
    <span class="k">if</span> <span class="n">i</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
        <span class="k">break</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>What the election could mean for Tesla, Fisker and their EV rivals
Nov-02-20 11:07PM  
The $110 Trillion Trend That Bezos, Buffet And Musk Are Betting On
08:02PM  
Estonia&#39;s Skeleton Technologies raises $48 million to fuel growth
06:34PM  
Honda, Fiat Pool To Pay Tesla For European CO2 Compliance: Report
05:47PM  
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2>Parse Date, Time, and News Headline into List</h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[336]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">parsed_news</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># Iterate through the news</span>
<span class="k">for</span> <span class="n">file_name</span><span class="p">,</span> <span class="n">news_table</span> <span class="ow">in</span> <span class="n">news_tables</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
    <span class="c1"># Iterate through all tr tags in &#39;news_table&#39;</span>
    <span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="n">news_table</span><span class="o">.</span><span class="n">findAll</span><span class="p">(</span><span class="s1">&#39;tr&#39;</span><span class="p">):</span>
        <span class="c1"># read the text from each tr tag into text</span>
        <span class="c1"># get text from a only</span>
        <span class="n">text</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">a</span><span class="o">.</span><span class="n">get_text</span><span class="p">()</span> 
        <span class="c1"># splite text in the td tag into a list </span>
        <span class="n">date_scrape</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">td</span><span class="o">.</span><span class="n">text</span><span class="o">.</span><span class="n">split</span><span class="p">()</span>
        <span class="c1"># if the length of &#39;date_scrape&#39; is 1, load &#39;time&#39; as the only element</span>

        <span class="k">if</span> <span class="nb">len</span><span class="p">(</span><span class="n">date_scrape</span><span class="p">)</span> <span class="o">==</span> <span class="mi">1</span><span class="p">:</span>
            <span class="n">time</span> <span class="o">=</span> <span class="n">date_scrape</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
            
        <span class="c1"># else load &#39;date&#39; as the 1st element and &#39;time&#39; as the second    </span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">date</span> <span class="o">=</span> <span class="n">date_scrape</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span>
            <span class="n">time</span> <span class="o">=</span> <span class="n">date_scrape</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span>
        <span class="c1"># Extract the ticker from the file name, get the string up to the 1st &#39;_&#39;  </span>
        <span class="n">ticker</span> <span class="o">=</span> <span class="n">file_name</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">&#39;_&#39;</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span>
        
        <span class="c1"># Append ticker, date, time and headline as a list to the &#39;parsed_news&#39; list</span>
        <span class="n">parsed_news</span><span class="o">.</span><span class="n">append</span><span class="p">([</span><span class="n">ticker</span><span class="p">,</span> <span class="n">date</span><span class="p">,</span> <span class="n">time</span><span class="p">,</span> <span class="n">text</span><span class="p">])</span>
        
<span class="n">parsed_news</span><span class="p">[</span><span class="mi">1</span><span class="p">:</span><span class="mi">10</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[336]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[[&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;08:02PM&#39;,
  &#39;The $110 Trillion Trend That Bezos, Buffet And Musk Are Betting On&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;06:34PM&#39;,
  &#34;Estonia&#39;s Skeleton Technologies raises $48 million to fuel growth&#34;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;05:47PM&#39;,
  &#39;Honda, Fiat Pool To Pay Tesla For European CO2 Compliance: Report&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;04:04PM&#39;,
  &#39;Nio Doubles October Deliveries; Xpeng, Li Auto Continue Strong Run&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;03:28PM&#39;,
  &#39;Tesla to Unveil Updated Cybertruck Design in About a Month&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;03:19PM&#39;,
  &#39;BMW Sets Release Date For Unveiling Of Tesla Challenger iNext&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;03:05PM&#39;,
  &#39;Tesla Autopilot Could Prevent 80% Of Accidents, Says German Researcher&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;02:17PM&#39;,
  &#34;Is Nio Stock A Buy Right Now As Chinese EVs Boom? Here&#39;s What Earnings, Stock Chart Show&#34;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;02:17PM&#39;,
  &#39;China Targets Alternative-Fuel Vehicles Reaching 20% of Sales by 2025&#39;]]</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h2>Sentiment Analysis with VADER</h2></p>
<p><hr></p>
<p>The ‘compound’ column gives the sentiment scores. For positive scores, the higher the value, the more positive the sentiment is. Similarly for negative scores, the more negative the value, the more negative the sentiment is. The scores range from -1 to 1.

<i><b>NOTE</b></i><br>
No preprocessing was performed on the news headlines. This is just a showcase of how to extract web data and get a sentiment score using VADER for each security headline. There are more intensive methods; this simplifies much of the work but is not comprehensive.
</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[337]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Instantiate the sentiment intensity analyzer</span>
<span class="n">vader</span> <span class="o">=</span> <span class="n">SentimentIntensityAnalyzer</span><span class="p">()</span>

<span class="c1"># Set column names</span>
<span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;ticker&#39;</span><span class="p">,</span> <span class="s1">&#39;date&#39;</span><span class="p">,</span> <span class="s1">&#39;time&#39;</span><span class="p">,</span> <span class="s1">&#39;headline&#39;</span><span class="p">]</span>

<span class="c1"># Convert the parsed_news list into a DataFrame called &#39;parsed_and_scored_news&#39;</span>
<span class="n">parsed_and_scored_news</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">parsed_news</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="n">columns</span><span class="p">)</span>

<span class="c1"># Iterate through the headlines and get the polarity scores using vader</span>
<span class="n">scores</span> <span class="o">=</span> <span class="n">parsed_and_scored_news</span><span class="p">[</span><span class="s1">&#39;headline&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="n">vader</span><span class="o">.</span><span class="n">polarity_scores</span><span class="p">)</span><span class="o">.</span><span class="n">tolist</span><span class="p">()</span>

<span class="c1"># Convert the &#39;scores&#39; list of dicts into a DataFrame</span>
<span class="n">scores_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">scores</span><span class="p">)</span>

<span class="c1"># Join the DataFrames of the news and the list of dicts</span>
<span class="n">parsed_and_scored_news</span> <span class="o">=</span> <span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">scores_df</span><span class="p">,</span> <span class="n">rsuffix</span><span class="o">=</span><span class="s1">&#39;_right&#39;</span><span class="p">)</span>

<span class="c1"># Convert the date column from string to datetime</span>
<span class="n">parsed_and_scored_news</span><span class="p">[</span><span class="s1">&#39;date&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">date</span><span class="p">)</span><span class="o">.</span><span class="n">dt</span><span class="o">.</span><span class="n">date</span>

<span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[337]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ticker</th>
      <th>date</th>
      <th>time</th>
      <th>headline</th>
      <th>neg</th>
      <th>neu</th>
      <th>pos</th>
      <th>compound</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>11:07PM</td>
      <td>What the election could mean for Tesla, Fisker...</td>
      <td>0.000</td>
      <td>1.000</td>
      <td>0.000</td>
      <td>0.0000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>08:02PM</td>
      <td>The $110 Trillion Trend That Bezos, Buffet And...</td>
      <td>0.000</td>
      <td>1.000</td>
      <td>0.000</td>
      <td>0.0000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>06:34PM</td>
      <td>Estonia's Skeleton Technologies raises $48 mil...</td>
      <td>0.000</td>
      <td>0.755</td>
      <td>0.245</td>
      <td>0.3818</td>
    </tr>
    <tr>
      <th>3</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>05:47PM</td>
      <td>Honda, Fiat Pool To Pay Tesla For European CO2...</td>
      <td>0.123</td>
      <td>0.877</td>
      <td>0.000</td>
      <td>-0.1027</td>
    </tr>
    <tr>
      <th>4</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>04:04PM</td>
      <td>Nio Doubles October Deliveries; Xpeng, Li Auto...</td>
      <td>0.000</td>
      <td>0.732</td>
      <td>0.268</td>
      <td>0.5106</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[338]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">date</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">date</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[339]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">rcParams</span><span class="p">[</span><span class="s1">&#39;figure.figsize&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="mi">10</span><span class="p">,</span> <span class="mi">6</span><span class="p">]</span>

<span class="c1"># Group by date and ticker columns from scored_news and calculate the mean</span>
<span class="n">mean_scores</span> <span class="o">=</span> <span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">groupby</span><span class="p">([</span><span class="s1">&#39;ticker&#39;</span><span class="p">,</span><span class="s1">&#39;date&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="c1"># Unstack the column ticker</span>
<span class="n">mean_scores</span> <span class="o">=</span> <span class="n">mean_scores</span><span class="o">.</span><span class="n">unstack</span><span class="p">()</span>

<span class="c1"># Get the cross-section of compound in the &#39;columns&#39; axis</span>
<span class="n">mean_scores</span> <span class="o">=</span> <span class="n">mean_scores</span><span class="o">.</span><span class="n">xs</span><span class="p">(</span><span class="s1">&#39;compound&#39;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="s2">&quot;columns&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">transpose</span><span class="p">()</span>

<span class="c1"># Plot a bar chart with pandas</span>
<span class="n">mean_scores</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s1">&#39;bar&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[340]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">parsed_and_scored_news</span><span class="p">[</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">date</span> <span class="o">==</span> <span class="s1">&#39;2020-11-01&#39;</span><span class="p">][</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">ticker</span> <span class="o">==</span> <span class="s2">&quot;TSLA&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="p">;</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>&lt;ipython-input-340-c166ac01227d&gt;:1: UserWarning: Boolean Series key will be reindexed to match DataFrame index.
  parsed_and_scored_news[parsed_and_scored_news.date == &#39;2020-11-01&#39;][parsed_and_scored_news.ticker == &#34;TSLA&#34;].values;
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[341]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">f_mean_scores</span> <span class="o">=</span> <span class="n">mean_scores</span><span class="p">[</span><span class="s2">&quot;F&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[342]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">start_date1</span> <span class="o">=</span> <span class="nb">min</span><span class="p">(</span><span class="n">f_mean_scores</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>
<span class="n">end_date1</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">f_mean_scores</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">f_price</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span><span class="o">=</span><span class="s2">&quot;F&quot;</span><span class="p">,</span>
                         <span class="n">start</span><span class="o">=</span><span class="n">start_date1</span><span class="p">,</span>
                         <span class="n">end</span><span class="o">=</span><span class="n">end_date1</span><span class="p">)</span>
                         <span class="c1">#interval=&quot;1d&quot;)</span>

<span class="n">f_price_series</span> <span class="o">=</span> <span class="n">f_price</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">]</span>

<span class="n">f_price</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>[*********************100%***********************]  1 of 1 completed
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt output_prompt">Out[342]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Adj Close</th>
      <th>Volume</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2020-10-13</th>
      <td>7.82</td>
      <td>7.88</td>
      <td>7.63</td>
      <td>7.76</td>
      <td>7.76</td>
      <td>74562600</td>
    </tr>
    <tr>
      <th>2020-10-14</th>
      <td>7.73</td>
      <td>7.75</td>
      <td>7.55</td>
      <td>7.57</td>
      <td>7.57</td>
      <td>57808900</td>
    </tr>
    <tr>
      <th>2020-10-15</th>
      <td>7.42</td>
      <td>7.62</td>
      <td>7.37</td>
      <td>7.62</td>
      <td>7.62</td>
      <td>49336200</td>
    </tr>
    <tr>
      <th>2020-10-16</th>
      <td>7.71</td>
      <td>7.75</td>
      <td>7.61</td>
      <td>7.67</td>
      <td>7.67</td>
      <td>47509400</td>
    </tr>
    <tr>
      <th>2020-10-19</th>
      <td>7.68</td>
      <td>7.72</td>
      <td>7.57</td>
      <td>7.59</td>
      <td>7.59</td>
      <td>38960700</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[343]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">comparison_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">f_price_series</span><span class="p">,</span><span class="n">f_mean_scores</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">comparison_df</span><span class="p">[</span><span class="s1">&#39;F Returns&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">comparison_df</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">pct_change</span><span class="p">()</span>
<span class="n">comparison_df</span> <span class="o">=</span> <span class="n">comparison_df</span><span class="p">[[</span><span class="s2">&quot;F Returns&quot;</span><span class="p">,</span><span class="s2">&quot;F&quot;</span><span class="p">,</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">]]</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">comparison_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[343]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>F Returns</th>
      <th>F</th>
      <th>Adj Close</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2020-10-14</th>
      <td>-0.024485</td>
      <td>0.047889</td>
      <td>7.57</td>
    </tr>
    <tr>
      <th>2020-10-15</th>
      <td>0.006605</td>
      <td>0.085000</td>
      <td>7.62</td>
    </tr>
    <tr>
      <th>2020-10-16</th>
      <td>0.006562</td>
      <td>0.229229</td>
      <td>7.67</td>
    </tr>
    <tr>
      <th>2020-10-19</th>
      <td>-0.010430</td>
      <td>0.000000</td>
      <td>7.59</td>
    </tr>
    <tr>
      <th>2020-10-20</th>
      <td>0.019763</td>
      <td>0.085820</td>
      <td>7.74</td>
    </tr>
    <tr>
      <th>2020-10-21</th>
      <td>0.014212</td>
      <td>0.219633</td>
      <td>7.85</td>
    </tr>
    <tr>
      <th>2020-10-22</th>
      <td>0.045860</td>
      <td>0.000000</td>
      <td>8.21</td>
    </tr>
    <tr>
      <th>2020-10-23</th>
      <td>-0.006090</td>
      <td>0.372533</td>
      <td>8.16</td>
    </tr>
    <tr>
      <th>2020-10-26</th>
      <td>-0.015931</td>
      <td>0.189733</td>
      <td>8.03</td>
    </tr>
    <tr>
      <th>2020-10-27</th>
      <td>-0.013699</td>
      <td>0.000000</td>
      <td>7.92</td>
    </tr>
    <tr>
      <th>2020-10-28</th>
      <td>-0.027778</td>
      <td>0.373329</td>
      <td>7.70</td>
    </tr>
    <tr>
      <th>2020-10-29</th>
      <td>0.025974</td>
      <td>0.204131</td>
      <td>7.90</td>
    </tr>
    <tr>
      <th>2020-10-30</th>
      <td>-0.021519</td>
      <td>0.036271</td>
      <td>7.73</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[344]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax1</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>

<span class="n">ax2</span> <span class="o">=</span> <span class="n">ax1</span><span class="o">.</span><span class="n">twinx</span><span class="p">()</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;F Daily Returns compared to Mean Sentiment VADER Score&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s2">&quot;Day&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Returns&#39;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">comparison_df</span><span class="p">[</span><span class="s2">&quot;F Returns&quot;</span><span class="p">],</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;green&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">comparison_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">,</span> <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">comparison_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">comparison_df</span><span class="o">.</span><span class="n">F</span><span class="p">,</span><span class="n">alpha</span><span class="o">=.</span><span class="mi">2</span><span class="p">,</span><span class="n">color</span><span class="o">=</span><span class="s2">&quot;orange&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Mean Sentiment Score&#39;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="n">b</span> <span class="o">=</span> <span class="kc">False</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

    </div>
</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
