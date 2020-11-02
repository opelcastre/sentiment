<!DOCTYPE html>
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
<h2>Sentiment Analysis</h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h2>Getting Our Data</h2></p>
<p><hr></p>
<p>We must first import all the necessary libraries needed to perform sentiment analysis, scrap web data, and create compelling visuals that will aid in conveying our message. The following is a list of all the necessary libraries you will need to have install in your current environment to follow along with this notebook</p><ul>
<li><a href="https://docs.python.org/3/library/urllib.html">urllib</a></li>
<li><a href="https://pypi.org/project/beautifulsoup4/">bs4</a></li>
<li><a href="https://docs.python.org/3/library/os.html#module-os">os</a></li>
<li><a href="https://pandas.pydata.org/docs/user_guide/index.html">pandas</a></li>
<li><a href="https://matplotlib.org/tutorials/index.html">matplotlib</a></li>
<li><a href="https://www.nltk.org/api/nltk.html">nltk</a></li>
</ul>
<p>Citation:

<b>NLTK VADER</b> - Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.</p>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
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
<div class="prompt input_prompt">In&nbsp;[2]:</div>
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
<div class="prompt input_prompt">In&nbsp;[3]:</div>
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
<div class="prompt input_prompt">In&nbsp;[4]:</div>
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
<pre>Nio Doubles October Deliveries; Xpeng, Li Auto Continue Strong Run
Nov-02-20 04:04PM  
Tesla to Unveil Updated Cybertruck Design in About a Month
03:28PM  
Tesla Autopilot Could Prevent 80% Of Accidents, Says German Researcher
03:05PM  
Is Nio Stock A Buy Right Now As Chinese EVs Boom? Here&#39;s What Earnings, Stock Chart Show
02:17PM  
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
<div class="prompt input_prompt">In&nbsp;[12]:</div>
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

    <div class="prompt output_prompt">Out[12]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[[&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;03:28PM&#39;,
  &#39;Tesla to Unveil Updated Cybertruck Design in About a Month&#39;],
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
  &#39;Dow Jones Rallies, But Nasdaq Reverses On Election Eve; Big Gains For Nio, Li&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;12:32PM&#39;,
  &#39;Updated Tesla Cybertruck Pictures Could Come Next Month: Musk&#39;],
 [&#39;TSLA&#39;,
  &#39;Nov-02-20&#39;,
  &#39;12:00PM&#39;,
  &#39;Dow Jones Jumps 500 Points, But Apple Reverses; Tesla Rebounds, While Nio Soars 14% On Deliveries&#39;]]</pre>
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
<div class="prompt input_prompt">In&nbsp;[6]:</div>
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

    <div class="prompt output_prompt">Out[6]:</div>



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
      <td>04:04PM</td>
      <td>Nio Doubles October Deliveries; Xpeng, Li Auto...</td>
      <td>0.000</td>
      <td>0.732</td>
      <td>0.268</td>
      <td>0.5106</td>
    </tr>
    <tr>
      <th>1</th>
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
      <th>2</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>03:05PM</td>
      <td>Tesla Autopilot Could Prevent 80% Of Accidents...</td>
      <td>0.202</td>
      <td>0.702</td>
      <td>0.096</td>
      <td>-0.2960</td>
    </tr>
    <tr>
      <th>3</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>02:17PM</td>
      <td>Is Nio Stock A Buy Right Now As Chinese EVs Bo...</td>
      <td>0.000</td>
      <td>1.000</td>
      <td>0.000</td>
      <td>0.0000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>TSLA</td>
      <td>2020-11-02</td>
      <td>02:17PM</td>
      <td>China Targets Alternative-Fuel Vehicles Reachi...</td>
      <td>0.000</td>
      <td>0.833</td>
      <td>0.167</td>
      <td>0.2023</td>
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
<div class="prompt input_prompt">In&nbsp;[7]:</div>
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
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAlsAAAGjCAYAAAAb7NCYAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3de5hddX3v8feXSUyUSYIZMFwCJFWohoRLB8GK2kQNjXjBKiAVCdRDU44geAFE+3iSHqtFi0IBBcEosQI5lSpQoaJgwFLQAiFyNRAlhEAQEiHJBKJcvuePvTNMJnPfe2XW3nm/nmc9sy6/9Vm/PWvvPd9Za+21IzORJElSMbYb7g5IkiQ1M4stSZKkAllsSZIkFchiS5IkqUAWW5IkSQUaMdwd6MuOO+6YkyZN6rPNhg0b2H777WveljnmmGOOOeaYY04tOXfeeefqzNxpiwWZWdqhvb09+7No0aJ+2wyEOeaYY4455phjTi05wB3ZQz3jaURJkqQCWWxJkiQVyGJLkiSpQKW+QF6SJJXf888/z8qVK9m4cSPjxo3jgQceqDmzzDmjR49m4sSJjBw5ckDrWmxJkqSarFy5kjFjxjBp0iQ6OjoYM2ZMzZnr168vZU5msmbNGlauXMnkyZMHtK6nESVJUk02btxIW1sbETHcXSlcRNDW1sbGjRsHvI7FliRJqtm2UGhtMtjHarElSZJUIIstSZI0rJ555hm+8Y1vAPD4449zxBFH9Nl+0qRJrF69emt0rS4stiRJ0rDqWmztuuuuXHnllYVs54UXXigktz91KbYiYlZELI2IZRFxZi9tpkfEkoi4LyJursd2JUlS4zvzzDP5zW9+w/7778+RRx7J1KlTAXjxxRc57bTTmDZtGvvuuy/nn3/+Zus999xzzJo1i0suuYQNGzbw0Y9+lDe+8Y0ccMABXH311QBcdtllHHnkkbz3ve/l0EMP3eqPDepw64eIaAG+DswEVgK3R8Q1mXl/lzY7AN8AZmXmioh4Ta3blSRJzeGss87i3nvvZcmSJSxfvpz3vOc9AFx88cU8/PDD3HXXXYwYMYLf//73net0dHRw9NFHM3v2bGbPns3nPvc53v72t/Ptb3+bZ555hoMOOoh3vvOdANx2223cfffdjB8/flgeXz3us3UQsCwzfwsQEQuBw4H7u7T5MPCDzFwBkJlP1mG7kiSpid1www2ceOKJjBhRKVe6FkuHH344Z5xxBscccwwAP/nJT7jmmms4++yzgcrtKFasWAHAzJkzh63QAojKl1TXEBBxBJUjVidUp48FDs7Mk7u0ORcYCewDjAH+JTO/20veHGAOwIQJE9oXLlzY5/Y7OjpobW2t6TE0Zc6qJZWcUbvSOr72A4mleVzmmGOOOeaULmfcuHG87nWvAyqn/lpaWga1/iOPPMJRRx3FL3/5y87xW2+9ldmzZ3PCCScwY8aMzdpPnTqVmTNnsn79ei655BIigre97W3Mnz+fvfbaa7O2//qv/8qSJUv46le/OqTHtkn3x7Vs2TLWrl27WZsZM2bcmZkHbrFyZtY0AEcC3+oyfSxwfrc2FwC/ALYHdgQeAvbuL7u9vT37s2jRon7bDETT5cwdmzl3bC66/Jxy9Mccc8wxx5ymzbn//vs7x9etWzfo9VevXp177LFHZmY+/PDDuc8+++S6devywgsvzA9+8IP5/PPPZ2bmmjVrMjNzzz33zKeeeipPOeWUPPHEEzMz87Of/WyedNJJ+dJLL2Vm5uLFizMz88ILL8yTTjppyI+tt8fV9TFvAtyRPdQz9bhAfiWwe5fpicDjPbT5cWZuyMzVwM+B/eqwbUmS1ODa2to45JBDmDp1Kqeffnrn/BNOOIE99tiDfffdl/3224/LL798s/XOPfdcNm7cyBlnnMHnP/95nn/+efbdd1+mTp3K5z//+a39MHpVj2u2bgf2iojJwGPA0VSu0erqauCCiBgBvAI4GDinDtuWJElNoHshtX79ekaMGMHXvvY1vva1r222bPny5Z3j3/nOdzrHv/nNb26Re8wxx9TluxFrUXOxlZkvRMTJwPVAC/DtzLwvIk6sLr8oMx+IiB8DdwMvUTnteG+t25YkSSq7ehzZIjOvA67rNu+ibtP/DPxzPbYnSZLUKLyDvCRJUoEstiRJkgpksSVJklQgiy1JkqQC1eUCeUmSpE0mnXltXfOWn/Xuftu0tLQwbdq0zumrrrqKSZMm1bUfQ2WxJUmSGt4rX/lKlixZMtzd6JGnESVJkgrkkS1JktTwnnvuOfbff38AJk+ezA9/+MNh7tHLLLYkSVLD8zSiJEnSNspiS5IkqUCeRpQkSXU1kFs19Gf9+vWMGTOmDr0Zfh7ZkiRJDa+jo2O4u9Ariy1JkqQCWWxJkiQVyGJr3rjKsKqcHxeVJEmNzWJLkiSpQBZbkiRJBbLYkiRJKpD32ZIkSfU1b1zNEZvdYWve2n7bRwSf+tSn+OpXvwrA2WefTUdHB5/+9KeZN28era2tnHbaaWQmX/ziF1mwYAERwW677cYFF1zAPvvsU3Ofe+ORLUmS1PBGjRrFD37wA1avXt1nu69//evceuut/OpXv+LBBx/ks5/9LO973/vYuHFjYX2z2JIkSQ1vxIgRzJkzh3POOafPdl/+8pc5//zzedWrXgXAoYceypvf/GYuu+yywvpmsSVJkprCSSedxGWXXcbatT2fdly3bh0bNmzgta997WbzDzzwQO67777C+mWxJUmSmsLYsWOZPXs255133qDWy0wioqBeWWxJkqQm8olPfIL58+ezYcOGLZaNHTuW7bffnt/+9rebzV+8eDFTpkwprE8WW5IkqWmMHz+eo446ivnz5/e4/PTTT+eUU07hueeeA+CGG27glltu4cMf/nBhffLWD5Ikqb4GcKuG/qxfv54xY8b037AHn/70p7ngggt6XPbxj3+cp59+mmnTptHS0sLOO+/M1VdfzStf+cpautsniy1JktTwOjo6OscnTJjAs88+C1SKtnnz5nUuiwjmzp3L3Llzt1rfPI0oSZJUIIstSZKkAllsSZIkFchiS5IkqUAWW5IkSQWy2JJUnHnjKsOqJcPdE0kaNt76QZIk1dW0BdPqmnfPcff0uXzNmjW84x3vAOCJJ56gpaWFnXbaCYDDDjuMq6++mpaWFrbbbju++c1vcvDBBzN9+nTOPvtsDjzwwC3yfvjDH/KBD3yABx54gNe//vU1999iS5IkNbS2tjaWLKkcQZ83bx6tra2cdtpp3HbbbZx66qksXryYUaNGsXr1av74xz/2m3fFFVfwlre8hYULF252j66h8jSiJElqSqtWraKtrY1Ro0YBsOOOO7Lrrrv2uU5HRwf//d//zfz581m4cGFd+mGxJUmSmtKhhx7KY489xt57783HPvYxbr755n7Xueqqq5g1axZ7770348ePZ/HixTX3oy7FVkTMioilEbEsIs7so90bI+LFiDiiHtuVJEnqTWtrKz//+c+5+OKL2WmnnfjQhz7EpZde2uc6V1xxBUcffTQARx99NFdccUXN/aj5mq2IaAG+DswEVgK3R8Q1mXl/D+2+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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
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
<div class="prompt input_prompt">In&nbsp;[9]:</div>
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
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">comparison_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">f_price_series</span><span class="p">,</span><span class="n">f_mean_scores</span><span class="p">],</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">comparison_df</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[10]:</div>



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
      <th>Adj Close</th>
      <th>F</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2020-10-13</th>
      <td>7.76</td>
      <td>0.120400</td>
    </tr>
    <tr>
      <th>2020-10-14</th>
      <td>7.57</td>
      <td>0.047889</td>
    </tr>
    <tr>
      <th>2020-10-15</th>
      <td>7.62</td>
      <td>0.085000</td>
    </tr>
    <tr>
      <th>2020-10-16</th>
      <td>7.67</td>
      <td>0.229229</td>
    </tr>
    <tr>
      <th>2020-10-19</th>
      <td>7.59</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>2020-10-20</th>
      <td>7.74</td>
      <td>0.085820</td>
    </tr>
    <tr>
      <th>2020-10-21</th>
      <td>7.85</td>
      <td>0.219633</td>
    </tr>
    <tr>
      <th>2020-10-22</th>
      <td>8.21</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>2020-10-23</th>
      <td>8.16</td>
      <td>0.372533</td>
    </tr>
    <tr>
      <th>2020-10-26</th>
      <td>8.03</td>
      <td>0.189733</td>
    </tr>
    <tr>
      <th>2020-10-27</th>
      <td>7.92</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>2020-10-28</th>
      <td>7.70</td>
      <td>0.373329</td>
    </tr>
    <tr>
      <th>2020-10-29</th>
      <td>7.90</td>
      <td>0.204131</td>
    </tr>
    <tr>
      <th>2020-10-30</th>
      <td>7.73</td>
      <td>0.036271</td>
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
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax1</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>

<span class="n">ax2</span> <span class="o">=</span> <span class="n">ax1</span><span class="o">.</span><span class="n">twinx</span><span class="p">()</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;F Daily Price compared to Mean Sentiment VADER Score&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s2">&quot;Day&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Mean Sentiment Score&#39;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">comparison_df</span><span class="p">[</span><span class="s2">&quot;Adj Close&quot;</span><span class="p">],</span> <span class="n">color</span><span class="o">=</span><span class="s2">&quot;green&quot;</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">comparison_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">,</span> <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">comparison_df</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">comparison_df</span><span class="o">.</span><span class="n">F</span><span class="p">,</span><span class="n">alpha</span><span class="o">=.</span><span class="mi">2</span><span class="p">,</span><span class="n">color</span><span class="o">=</span><span class="s2">&quot;orange&quot;</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Price&#39;</span><span class="p">)</span>
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