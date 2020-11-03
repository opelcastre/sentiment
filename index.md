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
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2>Sentiment Analysis</h2>
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
<div class="prompt input_prompt">In&nbsp;[29]:</div>
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
<div class="prompt input_prompt">In&nbsp;[30]:</div>
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
<div class="prompt input_prompt">In&nbsp;[31]:</div>
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
<div class="prompt input_prompt">In&nbsp;[32]:</div>
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
<pre>Estonia&#39;s Skeleton Technologies raises $48 million to fuel growth
Nov-02-20 06:34PM  
Nio Doubles October Deliveries; Xpeng, Li Auto Continue Strong Run
04:04PM  
Tesla to Unveil Updated Cybertruck Design in About a Month
03:28PM  
BMW Sets Release Date For Unveiling Of Tesla Challenger iNext
03:19PM  
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
<div class="prompt input_prompt">In&nbsp;[45]:</div>
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

    <div class="prompt output_prompt">Out[45]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[[&#39;TSLA&#39;,
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
  &#39;China Targets Alternative-Fuel Vehicles Reaching 20% of Sales by 2025&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;01:51PM&#39;,
  &#39;Dow Jones Holds Gains Ahead Of Election Day; These Electric Car Stocks Rise&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;01:02PM&#39;,
  &#39;The $110 Trillion Trend That Bezos, Buffet And Musk Are Betting On&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;12:50PM&#39;,
  &#39;Dow Jones Rallies, But Nasdaq Reverses On Election Eve; Big Gains For Nio, Li&#39;]]</pre>
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
<div class="prompt input_prompt">In&nbsp;[46]:</div>
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

    <div class="prompt output_prompt">Out[46]:</div>



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
      <td>06:34PM</td>
      <td>Estonia's Skeleton Technologies raises $48 mil...</td>
      <td>0.000</td>
      <td>0.755</td>
      <td>0.245</td>
      <td>0.3818</td>
    </tr>
    <tr>
      <th>1</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>04:04PM</td>
      <td>Nio Doubles October Deliveries; Xpeng, Li Auto...</td>
      <td>0.000</td>
      <td>0.732</td>
      <td>0.268</td>
      <td>0.5106</td>
    </tr>
    <tr>
      <th>2</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>03:28PM</td>
      <td>Tesla to Unveil Updated Cybertruck Design in A...</td>
      <td>0.000</td>
      <td>1.000</td>
      <td>0.000</td>
      <td>0.0000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>03:19PM</td>
      <td>BMW Sets Release Date For Unveiling Of Tesla C...</td>
      <td>0.000</td>
      <td>0.857</td>
      <td>0.143</td>
      <td>0.1280</td>
    </tr>
    <tr>
      <th>4</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>03:05PM</td>
      <td>Tesla Autopilot Could Prevent 80% Of Accidents...</td>
      <td>0.202</td>
      <td>0.702</td>
      <td>0.096</td>
      <td>-0.2960</td>
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
<div class="prompt input_prompt">In&nbsp;[67]:</div>
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
<div class="prompt input_prompt">In&nbsp;[47]:</div>
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
<img src="data:image/png;base64,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iy1JkqQCWWxJkiQVyGJr3rjKsKqcHxeVJEmNzWJLkiSpQBZbkiRJBbLYkiRJKpD32ZIkSfU1b1zNEZvdYWve2n7bRwSf+tSn+OpXvwrA2WefTUdHB5/+9KeZN28era2tnHbaaWQmX/ziF1mwYAERwW677cYFF1zAPvvsU3Ofe+ORLUmS1PBGjRrFD37wA1avXt1nu69//evceuut/OpXv+LBBx/ks5/9LO973/vYuHFjYX2z2JIkSQ1vxIgRzJkzh3POOafPdl/+8pc5//zzedWrXgXAoYceypvf/GYuu+yywvpmsSVJkprCSSedxGWXXcbatT2fdly3bh0bNmzgta997WbzDzzwQO67777C+mWxJUmSmsLYsWOZPXs255133qDWy0wioqBeWWxJkqQm8olPfIL58+ezYcOGLZaNHTuW7bffnt/+9rebzV+8eDFTpkwprE8WW5IkqWmMHz+eo446ivnz5/e4/PTTT+eUU07hueeeA+CGG27glltu4cMf/nBhffLWD5Ikqb4GcKuG/qxfv54xY8b037AHn/70p7ngggt6XPbxj3+cp59+mmnTptHS0sLOO+/M1VdfzStf+cpautsniy1JktTwOjo6OscnTJjAs88+C1SKtnnz5nUuiwjmzp3L3Llzt1rfPI0oSZJUIIstSZKkAllsSZIkFchiS5IkqUAWW5IkSQWy2JJUnHnjKsOqJcPdE0kaNt76QZIk1dW0BdPqmnfPcff0uXzNmjW84x3vAOCJJ56gpaWFnXbaCYDDDjuMq6++mpaWFrbbbju++c1vcvDBBzN9+nTOPvtsDjzwwC3yfvjDH/KBD3yABx54gNe//vU1999iS5IkNbS2tjaWLKkcQZ83bx6tra2cdtpp3HbbbZx66qksXryYUaNGsXr1av74xz/2m3fFFVfwlre8hYULF252j66h8jSiJElqSqtWraKtrY1Ro0YBsOOOO7Lrrrv2uU5HRwf//d//zfz581m4cGFd+mGxJUmSmtKhhx7KY489xt57783HPvYxbr755n7Xueqqq5g1axZ7770348ePZ/HixTX3oy7FVkTMioilEbEsIs7so90bI+LFiDiiHtuVJEnqTWtrKz//+c+5+OKL2WmnnfjQhz7EpZde2uc6V1xxBUcffTQARx99NFdccUXN/aj5mq2IaAG+DswEVgK3R8Q1mXl/D+2+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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[81]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">parsed_and_scored_news</span><span class="p">[</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">date</span> <span class="o">==</span> <span class="s1">&#39;2020-11-01&#39;</span><span class="p">][</span><span class="n">parsed_and_scored_news</span><span class="o">.</span><span class="n">ticker</span> <span class="o">==</span> <span class="s2">&quot;TSLA&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>&lt;ipython-input-81-f6af5fa2b7c1&gt;:1: UserWarning: Boolean Series key will be reindexed to match DataFrame index.
  parsed_and_scored_news[parsed_and_scored_news.date == &#39;2020-11-01&#39;][parsed_and_scored_news.ticker == &#34;TSLA&#34;].values
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt output_prompt">Out[81]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>array([[&#39;TSLA&#39;, Timestamp(&#39;2020-11-01 00:00:00&#39;), &#39;05:45PM&#39;,
        &#34;Dow Jones Futures: After Worst Week Since March, Don&#39;t Feed The Bears! Here&#39;s What To Do Now&#34;,
        0.215, 0.785, 0.0, -0.6588]], dtype=object)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[48]:</div>
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
<div class="prompt input_prompt">In&nbsp;[49]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">start_date</span> <span class="o">=</span> <span class="nb">min</span><span class="p">(</span><span class="n">f_mean_scores</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>
<span class="n">end_date</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">f_mean_scores</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">f_price</span> <span class="o">=</span> <span class="n">yf</span><span class="o">.</span><span class="n">download</span><span class="p">(</span><span class="n">tickers</span><span class="o">=</span><span class="s2">&quot;F&quot;</span><span class="p">,</span>
                         <span class="n">start</span><span class="o">=</span><span class="n">start_date</span><span class="p">,</span>
                         <span class="n">end</span><span class="o">=</span><span class="n">end_date</span><span class="p">)</span>
                         <span class="c1">#interval=&quot;1d&quot;)</span>

<span class="n">f_price_series</span> <span class="o">=</span> <span class="n">f_price</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">]</span>
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

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[56]:</div>
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

    <div class="prompt output_prompt">Out[56]:</div>



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
<div class="prompt input_prompt">In&nbsp;[57]:</div>
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
    </div>
  </div>
</body>

 


</html>
