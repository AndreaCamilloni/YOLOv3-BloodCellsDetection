
<html>
<head><meta charset="utf-8" />

<title>yolo-blood-cell</title>

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
 
<div align="center">
<br>
<div>

   <a href="https://www.kaggle.com/code/andreacamilloni/yolo-blood-cell/edit"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open Notebook in Kaggle"></a>
</div>
<br>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[57]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">7</span><span class="p">))</span>

<span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">1</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">image</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Labels&quot;</span><span class="p">)</span>

<span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">img</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Predictions&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[57]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0.5, 1.0, &#39;Predictions&#39;)</pre>
</div>

</div>

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
