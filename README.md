<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>star_wars</title>

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
<h1 id="Star-Wars"><span style="font-size: 3em;">Star Wars</span><a class="anchor-link" href="#Star-Wars">&#182;</a></h1><h3 id="The-team-of-FiveThirtyEight-bacame-interested-in-answering-some-questions-about-Star-Wars-fans.-In-particular,-they-wondered:-does-the-rest-of-America-realize-that-&#8220;The-Empire-Strikes-Back&#8221;-is-clearly-the-best-of-the-bunch?">The team of <a href="http://fivethirtyeight.com/" target="_blank">FiveThirtyEight</a> bacame interested in answering some questions about Star Wars fans. In particular, they wondered: <span style="font-size: 1.1em; font-weight: bold; color: red;">does the rest of America realize that &#8220;The Empire Strikes Back&#8221; is clearly the best of the bunch?</span><a class="anchor-link" href="#The-team-of-FiveThirtyEight-bacame-interested-in-answering-some-questions-about-Star-Wars-fans.-In-particular,-they-wondered:-does-the-rest-of-America-realize-that-&#8220;The-Empire-Strikes-Back&#8221;-is-clearly-the-best-of-the-bunch?">&#182;</a></h3><p><br /><br /></p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Load libraries</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>

<span class="o">%</span><span class="k">matplotlib</span> inline
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Load data</span>
<span class="n">star_wars</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;star_wars.csv&quot;</span><span class="p">,</span> <span class="n">encoding</span><span class="o">=</span><span class="s2">&quot;ISO-8859-1&quot;</span><span class="p">)</span>

<span class="n">star_wars</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[5]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(1187, 38)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">star_wars</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
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
      <th>RespondentID</th>
      <th>Have you seen any of the 6 films in the Star Wars franchise?</th>
      <th>Do you consider yourself to be a fan of the Star Wars film franchise?</th>
      <th>Which of the following Star Wars films have you seen? Please select all that apply.</th>
      <th>Unnamed: 4</th>
      <th>Unnamed: 5</th>
      <th>Unnamed: 6</th>
      <th>Unnamed: 7</th>
      <th>Unnamed: 8</th>
      <th>Please rank the Star Wars films in order of preference with 1 being your favorite film in the franchise and 6 being your least favorite film.</th>
      <th>...</th>
      <th>Unnamed: 28</th>
      <th>Which character shot first?</th>
      <th>Are you familiar with the Expanded Universe?</th>
      <th>Do you consider yourself to be a fan of the Expanded Universe?ÂÃ¦</th>
      <th>Do you consider yourself to be a fan of the Star Trek franchise?</th>
      <th>Gender</th>
      <th>Age</th>
      <th>Household Income</th>
      <th>Education</th>
      <th>Location (Census Region)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>NaN</td>
      <td>Response</td>
      <td>Response</td>
      <td>Star Wars: Episode I  The Phantom Menace</td>
      <td>Star Wars: Episode II  Attack of the Clones</td>
      <td>Star Wars: Episode III  Revenge of the Sith</td>
      <td>Star Wars: Episode IV  A New Hope</td>
      <td>Star Wars: Episode V The Empire Strikes Back</td>
      <td>Star Wars: Episode VI Return of the Jedi</td>
      <td>Star Wars: Episode I  The Phantom Menace</td>
      <td>...</td>
      <td>Yoda</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
      <td>Response</td>
    </tr>
    <tr>
      <th>1</th>
      <td>3.292880e+09</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>Star Wars: Episode I  The Phantom Menace</td>
      <td>Star Wars: Episode II  Attack of the Clones</td>
      <td>Star Wars: Episode III  Revenge of the Sith</td>
      <td>Star Wars: Episode IV  A New Hope</td>
      <td>Star Wars: Episode V The Empire Strikes Back</td>
      <td>Star Wars: Episode VI Return of the Jedi</td>
      <td>3</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>NaN</td>
      <td>High school degree</td>
      <td>South Atlantic</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3.292880e+09</td>
      <td>No</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>Bachelor degree</td>
      <td>West South Central</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3.292765e+09</td>
      <td>Yes</td>
      <td>No</td>
      <td>Star Wars: Episode I  The Phantom Menace</td>
      <td>Star Wars: Episode II  Attack of the Clones</td>
      <td>Star Wars: Episode III  Revenge of the Sith</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1</td>
      <td>...</td>
      <td>Unfamiliar (N/A)</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>High school degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3.292763e+09</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>Star Wars: Episode I  The Phantom Menace</td>
      <td>Star Wars: Episode II  Attack of the Clones</td>
      <td>Star Wars: Episode III  Revenge of the Sith</td>
      <td>Star Wars: Episode IV  A New Hope</td>
      <td>Star Wars: Episode V The Empire Strikes Back</td>
      <td>Star Wars: Episode VI Return of the Jedi</td>
      <td>5</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$100,000 - $149,999</td>
      <td>Some college or Associate degree</td>
      <td>West North Central</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 38 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Cleaning-data">Cleaning data<a class="anchor-link" href="#Cleaning-data">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Checking columns</span>
<span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[7]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Index([&#39;RespondentID&#39;,
       &#39;Have you seen any of the 6 films in the Star Wars franchise?&#39;,
       &#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;,
       &#39;Which of the following Star Wars films have you seen? Please select all that apply.&#39;,
       &#39;Unnamed: 4&#39;, &#39;Unnamed: 5&#39;, &#39;Unnamed: 6&#39;, &#39;Unnamed: 7&#39;, &#39;Unnamed: 8&#39;,
       &#39;Please rank the Star Wars films in order of preference with 1 being your favorite film in the franchise and 6 being your least favorite film.&#39;,
       &#39;Unnamed: 10&#39;, &#39;Unnamed: 11&#39;, &#39;Unnamed: 12&#39;, &#39;Unnamed: 13&#39;,
       &#39;Unnamed: 14&#39;,
       &#39;Please state whether you view the following characters favorably, unfavorably, or are unfamiliar with him/her.&#39;,
       &#39;Unnamed: 16&#39;, &#39;Unnamed: 17&#39;, &#39;Unnamed: 18&#39;, &#39;Unnamed: 19&#39;,
       &#39;Unnamed: 20&#39;, &#39;Unnamed: 21&#39;, &#39;Unnamed: 22&#39;, &#39;Unnamed: 23&#39;,
       &#39;Unnamed: 24&#39;, &#39;Unnamed: 25&#39;, &#39;Unnamed: 26&#39;, &#39;Unnamed: 27&#39;,
       &#39;Unnamed: 28&#39;, &#39;Which character shot first?&#39;,
       &#39;Are you familiar with the Expanded Universe?&#39;,
       &#39;Do you consider yourself to be a fan of the Expanded Universe?ÂÃ¦&#39;,
       &#39;Do you consider yourself to be a fan of the Star Trek franchise?&#39;,
       &#39;Gender&#39;, &#39;Age&#39;, &#39;Household Income&#39;, &#39;Education&#39;,
       &#39;Location (Census Region)&#39;],
      dtype=&#39;object&#39;)</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Remove all rows with ResponseId equal NaN</span>
<span class="n">star_wars</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;RespondentID&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">notnull</span><span class="p">()]</span>

<span class="n">star_wars</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[8]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(1186, 38)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Convert the columns to boolean</span>
<span class="n">yes_no</span> <span class="o">=</span> <span class="p">{</span><span class="s1">&#39;Yes&#39;</span><span class="p">:</span> <span class="kc">True</span><span class="p">,</span> <span class="s1">&#39;No&#39;</span><span class="p">:</span> <span class="kc">False</span><span class="p">}</span>

<span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Have you seen any of the 6 films in the Star Wars franchise?&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Have you seen any of the 6 films in the Star Wars franchise?&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">map</span><span class="p">(</span><span class="n">yes_no</span><span class="p">)</span>

<span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Have you seen any of the 6 films in the Star Wars franchise?&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[9]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>True     936
False    250
Name: Have you seen any of the 6 films in the Star Wars franchise?, dtype: int64</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">map</span><span class="p">(</span><span class="n">yes_no</span><span class="p">)</span>

<span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[10]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>True     552
False    284
Name: Do you consider yourself to be a fan of the Star Wars film franchise?, dtype: int64</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]]</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]]</span><span class="o">.</span><span class="n">fillna</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
<span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]]</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]]</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="s1">&#39;bool&#39;</span><span class="p">)</span>

<span class="n">star_wars</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[11]:</div>



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
      <th>RespondentID</th>
      <th>Have you seen any of the 6 films in the Star Wars franchise?</th>
      <th>Do you consider yourself to be a fan of the Star Wars film franchise?</th>
      <th>Which of the following Star Wars films have you seen? Please select all that apply.</th>
      <th>Unnamed: 4</th>
      <th>Unnamed: 5</th>
      <th>Unnamed: 6</th>
      <th>Unnamed: 7</th>
      <th>Unnamed: 8</th>
      <th>Please rank the Star Wars films in order of preference with 1 being your favorite film in the franchise and 6 being your least favorite film.</th>
      <th>...</th>
      <th>Unnamed: 28</th>
      <th>Which character shot first?</th>
      <th>Are you familiar with the Expanded Universe?</th>
      <th>Do you consider yourself to be a fan of the Expanded Universe?ÂÃ¦</th>
      <th>Do you consider yourself to be a fan of the Star Trek franchise?</th>
      <th>Gender</th>
      <th>Age</th>
      <th>Household Income</th>
      <th>Education</th>
      <th>Location (Census Region)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>3.292880e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>3</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>NaN</td>
      <td>High school degree</td>
      <td>South Atlantic</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3.292880e+09</td>
      <td>False</td>
      <td>NaN</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>NaN</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>Bachelor degree</td>
      <td>West South Central</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3.292765e+09</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>1</td>
      <td>...</td>
      <td>Unfamiliar (N/A)</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>High school degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3.292763e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>5</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$100,000 - $149,999</td>
      <td>Some college or Associate degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>5</th>
      <td>3.292731e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>5</td>
      <td>...</td>
      <td>Somewhat favorably</td>
      <td>Greedo</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$100,000 - $149,999</td>
      <td>Some college or Associate degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>6</th>
      <td>3.292719e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>1</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>Han</td>
      <td>Yes</td>
      <td>No</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$25,000 - $49,999</td>
      <td>Bachelor degree</td>
      <td>Middle Atlantic</td>
    </tr>
    <tr>
      <th>7</th>
      <td>3.292685e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>6</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>Han</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>NaN</td>
      <td>High school degree</td>
      <td>East North Central</td>
    </tr>
    <tr>
      <th>8</th>
      <td>3.292664e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>4</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>Han</td>
      <td>No</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>NaN</td>
      <td>High school degree</td>
      <td>South Atlantic</td>
    </tr>
    <tr>
      <th>9</th>
      <td>3.292654e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>5</td>
      <td>...</td>
      <td>Somewhat favorably</td>
      <td>Han</td>
      <td>No</td>
      <td>NaN</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>Some college or Associate degree</td>
      <td>South Atlantic</td>
    </tr>
    <tr>
      <th>10</th>
      <td>3.292640e+09</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>1</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$25,000 - $49,999</td>
      <td>Some college or Associate degree</td>
      <td>Pacific</td>
    </tr>
  </tbody>
</table>
<p>10 rows × 38 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Rename columns</span>

<span class="n">cols</span> <span class="o">=</span> <span class="p">{}</span>
<span class="n">pos</span> <span class="o">=</span> <span class="mi">4</span>
<span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">3</span><span class="p">:</span><span class="mi">6</span><span class="p">]:</span>
    <span class="n">cols</span><span class="p">[</span><span class="n">col</span><span class="p">]</span> <span class="o">=</span> <span class="s1">&#39;seen_movie_</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">pos</span><span class="p">)</span>
    <span class="n">pos</span> <span class="o">+=</span> <span class="mi">1</span>
    
<span class="n">pos</span> <span class="o">=</span> <span class="mi">1</span>
<span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">6</span><span class="p">:</span><span class="mi">9</span><span class="p">]:</span>
    <span class="n">cols</span><span class="p">[</span><span class="n">col</span><span class="p">]</span> <span class="o">=</span> <span class="s1">&#39;seen_movie_</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">pos</span><span class="p">)</span>
    <span class="n">pos</span> <span class="o">+=</span> <span class="mi">1</span>
    
<span class="n">star_wars</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span> <span class="o">=</span> <span class="n">cols</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="n">star_wars</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[13]:</div>



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
      <th>RespondentID</th>
      <th>Have you seen any of the 6 films in the Star Wars franchise?</th>
      <th>Do you consider yourself to be a fan of the Star Wars film franchise?</th>
      <th>seen_movie_4</th>
      <th>seen_movie_5</th>
      <th>seen_movie_6</th>
      <th>seen_movie_1</th>
      <th>seen_movie_2</th>
      <th>seen_movie_3</th>
      <th>Please rank the Star Wars films in order of preference with 1 being your favorite film in the franchise and 6 being your least favorite film.</th>
      <th>...</th>
      <th>Unnamed: 28</th>
      <th>Which character shot first?</th>
      <th>Are you familiar with the Expanded Universe?</th>
      <th>Do you consider yourself to be a fan of the Expanded Universe?ÂÃ¦</th>
      <th>Do you consider yourself to be a fan of the Star Trek franchise?</th>
      <th>Gender</th>
      <th>Age</th>
      <th>Household Income</th>
      <th>Education</th>
      <th>Location (Census Region)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>3.292880e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>3</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>NaN</td>
      <td>High school degree</td>
      <td>South Atlantic</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3.292880e+09</td>
      <td>False</td>
      <td>NaN</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>NaN</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>Bachelor degree</td>
      <td>West South Central</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3.292765e+09</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>1</td>
      <td>...</td>
      <td>Unfamiliar (N/A)</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$0 - $24,999</td>
      <td>High school degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3.292763e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>5</td>
      <td>...</td>
      <td>Very favorably</td>
      <td>I don't understand this question</td>
      <td>No</td>
      <td>NaN</td>
      <td>Yes</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$100,000 - $149,999</td>
      <td>Some college or Associate degree</td>
      <td>West North Central</td>
    </tr>
    <tr>
      <th>5</th>
      <td>3.292731e+09</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>5</td>
      <td>...</td>
      <td>Somewhat favorably</td>
      <td>Greedo</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>Male</td>
      <td>18-29</td>
      <td>$100,000 - $149,999</td>
      <td>Some college or Associate degree</td>
      <td>West North Central</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 38 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Convert rank columns to float data type and rename them</span>

<span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]]</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]]</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">float</span><span class="p">)</span>

<span class="n">cols</span> <span class="o">=</span> <span class="p">{}</span>
<span class="n">pos</span> <span class="o">=</span> <span class="mi">4</span>
<span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">9</span><span class="p">:</span><span class="mi">12</span><span class="p">]:</span>
    <span class="n">cols</span><span class="p">[</span><span class="n">col</span><span class="p">]</span> <span class="o">=</span> <span class="s1">&#39;ranking_movie_</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">pos</span><span class="p">)</span>
    <span class="n">pos</span> <span class="o">+=</span> <span class="mi">1</span>
    
<span class="n">pos</span> <span class="o">=</span> <span class="mi">1</span>
<span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">12</span><span class="p">:</span><span class="mi">15</span><span class="p">]:</span>
    <span class="n">cols</span><span class="p">[</span><span class="n">col</span><span class="p">]</span> <span class="o">=</span> <span class="s1">&#39;ranking_movie_</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">pos</span><span class="p">)</span>
    <span class="n">pos</span> <span class="o">+=</span> <span class="mi">1</span>
    
<span class="n">star_wars</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span> <span class="o">=</span> <span class="n">cols</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="n">star_wars</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span><span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[15]:</div>



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
      <th>ranking_movie_4</th>
      <th>ranking_movie_5</th>
      <th>ranking_movie_6</th>
      <th>ranking_movie_1</th>
      <th>ranking_movie_2</th>
      <th>ranking_movie_3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>3.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>4.0</td>
      <td>5.0</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1.0</td>
      <td>2.0</td>
      <td>3.0</td>
      <td>4.0</td>
      <td>5.0</td>
      <td>6.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5.0</td>
      <td>6.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>4.0</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5.0</td>
      <td>4.0</td>
      <td>6.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>3.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Find-the-highest-ranked-move"><span style="color: red;">Find the highest-ranked move</span><a class="anchor-link" href="#Find-the-highest-ranked-move">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">star_wars</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAWoAAAFDCAYAAAATe0QdAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAASAElEQVR4nO3df4xld13G8edhWahCG9CdBGMrK0jB8rPtCiomQiGhUMBIKoKWmILURCEgiLQEhYZEq5jGmEBIQQIKoRRoESi/SqFiLaXOtqU/qCSEbg0R0qkUS02olD7+ce/QYXq3M3XPuefz/c77lUxy77l3536ezeyz3zn3nHOdRACAuu439QAAgHtHUQNAcRQ1ABRHUQNAcRQ1ABR3/zG+6Z49e7J3794xvjUAdGn//v23JFlZ9NgoRb13716trq6O8a0BoEu2bzrYY+z6AIDiKGoAKI6iBoDiKGoAKI6iBoDiKGoAKI6iBoDiKGoAKI6iBoDiRjkzETvP3tMvXOrrHTjrpKW+HjAlVtQAUBxFDQDFUdQAUBxFDQDFUdQAUBxFDQDFUdQAUBxFDQDFUdQAUBxFDQDFUdQAUBzX+lgSroUB4P9r2ytq27tsX2X7E2MOBAD4cfdl18erJN0w1iAAgMW2VdS2j5R0kqR3jTsOAGCz7a6o/1bSn0q662BPsH2a7VXbq2tra4MMBwDYRlHbfq6km5Psv7fnJTknyb4k+1ZWVgYbEAB2uu2sqJ8q6fm2D0g6V9IJtt836lQAgB/ZsqiTnJHkyCR7Jb1I0ueTnDL6ZAAASZzwAgDl3acTXpJcIumSUSYBACzEihoAiqOoAaA4ihoAiqOoAaA4ihoAiqOoAaA4ihoAiiv1wQHLvLg+F9YH0ApW1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQHEUNAMVR1ABQXKlPIQeq2nv6hUt9vQNnnbTU10NtrKgBoDiKGgCKo6gBoDiKGgCKo6gBoDiKGgCKo6gBoDiKGgCKo6gBoLgti9r2YbavsP0V29fbPnMZgwEAZrZzCvkdkk5Icrvt3ZIutf2pJJePPBsADGKZlwAY4/T/LYs6SSTdPr+7e/6VwScBACy0rX3UtnfZvlrSzZIuSvLlBc85zfaq7dW1tbWh5wSAHWtbRZ3kh0meJOlISU+2/bgFzzknyb4k+1ZWVoaeEwB2rPt01EeS70q6RNKJo0wDALiH7Rz1sWL7IfPbPyHpmZL+fezBAAAz2znq42ckvdf2Ls2K/bwknxh3LADAuu0c9XGNpGOXMAsAYAHOTASA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4ihqACiOogaA4rbzUVwAOrf39AuX+noHzjppqa/XOlbUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxVHUAFAcRQ0AxW1Z1LaPsv0F2zfYvt72q5YxGABgZjufQn6npNcmudL24ZL2274oyVdHng0AoG2sqJN8K8mV89vfk3SDpJ8dezAAwMx92kdte6+kYyV9eYxhAAD3tO2itv1gSR+R9Ookty14/DTbq7ZX19bWhpwRAHa0bRW17d2alfT7k5y/6DlJzkmyL8m+lZWVIWcEgB1tO0d9WNLfS7ohydnjjwQA2Gg7K+qnSnqJpBNsXz3/es7IcwEA5rY8PC/JpZK8hFkAAAtwZiIAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFEdRA0BxFDUAFLdlUdt+t+2bbV+3jIEAAD9uOyvq90g6ceQ5AAAHsWVRJ/mipO8sYRYAwAKD7aO2fZrtVdura2trQ31bANjxBivqJOck2Zdk38rKylDfFgB2PI76AIDiKGoAKG47h+d9QNKXJD3a9jdtv2z8sQAA6+6/1ROSvHgZgwAAFmPXBwAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUR1EDQHEUNQAUt62itn2i7a/Z/rrt08ceCgBwty2L2vYuSW+T9GxJx0h6se1jxh4MADCznRX1kyV9Pck3kvyvpHMl/ca4YwEA1jnJvT/BPlnSiUl+f37/JZKekuQVm553mqTT5ncfLelrw4+70B5JtyzptaZAvraRr13LzvbwJCuLHrj/Nv6wF2y7R7snOUfSOfdxsENmezXJvmW/7rKQr23ka1elbNvZ9fFNSUdtuH+kpP8cZxwAwGbbKep/k/Qo2z9v+wGSXiTpY+OOBQBYt+WujyR32n6FpM9I2iXp3UmuH32y7Vv67pYlI1/byNeuMtm2fDMRADAtzkwEgOIoagAojqIGgOIoagAorouitn3c1DPgvrN9hO3jbT906lmAyporatvHbfo6XtLHbB/bQ2HbfumG20favtj2d21fZvvoKWc7VLbfZ3vP/PazJF0v6a8kXW37tyYdbmS2r516hkNl+yjb59r+F9tvsL17w2MfnXK2Idh+jO1P2b7Q9iNtv2f+b+8K27846WytHZ5n+y5Jl0u6Y8PmX55vS5ITJhlsILavTHLc/PZ5ki6W9E7NLoT1iiTPmHK+Q2H72iSPn9++TNLvJDkwL++Lkzxx2gkPje0XHOwhSe842HUcWmH7Ikkf0ezf2sskHS/peUn+y/ZVSY6ddMBDZPuLkt4q6cGSzpL0ekkflPRcSa+e8t/edq71Uc0LJb1S0luTfFKSbN+Y5OnTjjWKo5O8cH77Att/Puk0h+5+to9IcpukuyT9hyQlucV2iz+Lm31Q0vu14Fo4kg5b8ixjWEnyjvntV9o+RdIXbT9fizO35vAkH5ck229Jcu58+8dtnznhXO0VdZIP2/60pLfYPlXSa9XHD8m6I23/nWarsBXbu5P8YP7Y7nv5cy04U9IXbL9N0r9K+pDtf5J0gqRPTzrZMK6R9DdJrtv8gO1nTjDP0HbbPizJ9yUpyftsf1uzs5YfNO1og9i14fbZmx57wDIH2ay5opakJLdL+mPbT5L0Xs1+VenF6zbcXtUs2622H6bGr7GS5DzbV0p6uaSjNfv5+xVJH0jymUmHG8arJd12kMd+c5mDjORdkp4i6Z/XNyT53Pz9hb+ebKrhvM32g5PcnuTt6xtt/4Kkz004V3v7qDezbc1+Zblt0/YzkvzlRGONrud8PWeTyNe6KfI1d9THZplZtIrp+igC9Z2v52wS+Vq39HzNF/W9WPSBBz3pOV/P2STytW7p+Xou6rb36Wyt53w9Z5PI17ql5+u5qPlfvV09Z5PI1zpW1AP60NQDjKznfD1nk8jXuqXna7aobR89P736uvn9J9h+4/rjSf5iuukOXc/5es4mkY98w2u2qDU7rfoMST+QpCTXaPZ5jr3oOV/P2STyta5cvpaL+ieTXLFp252TTDKOnvP1nE0iX+vK5Wu5qG+x/UjN34G1fbKkb0070qB6ztdzNol8rSuXr9kzE20/QrNPCf5VSbdKulHSKUkOTDnXUHrO13M2iXytq5iv2aJeZ/tBku6X5HtTzzKGnvP1nE0iX+sq5WuuqG2fMr9q12sWPZ5k81WvmtJzvp6zSeQj33havHre+uUUD590ivH0nK/nbBL5Wlc2X3Mr6nW2V5KsTT3HWHrO13M2iXytq5iv5aM+LrP9Wdsvc58fjtpzvp6zSeRrXbl8zRZ1kkdJeqOkx0rab/sT848G6kLP+XrOJpGvdRXzNbvrYyPPPhz1bEm/m2TXVs9vTc/5es4mka91VfI1u6K2fYTt37P9KUmXaXZA+pMnHmswPefrOZtEvtZVzNfsitr2jZI+Kum8JF+aep6h9Zyv52wS+VpXMV/LRe0ksX24Zp/IdfvUMw2p53w9Z5PI17qK+Zrd9SHpsbavknSdpK/a3m/7cVMPNaCe8/WcTSJf6+rlS9Lkl2b7jp6+4f7TJF029Vzk29nZyNf+V8V8La+oH5TkC+t3klyiu88s6kHP+XrOJpGvdeXytXgK+bpv2P4zSf84v3+KZle56kXP+XrOJpGvdeXytbyifqmkFUnnS7pgfvvUSScaVs/5es4mka915fI1e9QHAOwUze76sL1P0hsk7dWGHEmeMNVMQ+o5X8/ZJPK1rmK+ZlfUtr8m6XWSrpV01/r2JDdNNtSAes7XczaJfK2rmK/ZFbWktSQfm3qIEfWcr+dsEvlaVy5fyyvqZ0h6saSLJd2xvj3J+ZMNNaCe8/WcTSJf6yrma3lFfaqkx0jarbt/PYlm79T2oOd8PWeTyNe6cvlaLuonJnn81EOMqOd8PWeTyNe6cvlaPo76ctvHTD3EiHrO13M2iXytK5ev5X3UN0h6pGZnDN0hyZpd6aqXQ4S6zddzNol8rauYr+Wifvii7euH0Nh+aJJblzvVcHrO13M2iXzkG2GmVot6K7avTHLc1HOMped8PWeTyNe6KfK1vI96K556gJH1nK/nbBL5Wrf0fD0XdZ+/Ktyt53w9Z5PI17ql5+u5qAGgCz0XNb9+tavnbBL5Wrf0fM2+mWj7pxZs/l6SH6w/nuQ7Sx5rMD3n6zmbRD7yjTBTw0V9QNJRkm7V7H+4h0j6lqSbJb08yf7ppjt0PefrOZtEPvINr+VdH5+W9Jwke5L8tKRnSzpP0h9Kevukkw2j53w9Z5PI17py+VpeUa8m2bdom+2rkzxpqtmG0HO+nrNJ5CPf8Fq+KNN3bL9e0rnz+78t6Vbbu7ThYt8N6zlfz9kk8rWuXL6WV9R7JL1J0q9pth/pUklnSvpvST+X5OsTjnfIes7XczaJfOQbYaZWixoAdopmd33YPlrSn+ieH0B5wlQzDannfD1nk8jXuor5ml1R2/6KpHdI2i/ph+vbWz80aF3P+XrOJpGvdRXztVzU+5McP/UcY+k5X8/ZJPK1rmK+lov6zZodgH6BfvwDKJs9I2qjnvP1nE0iX+sq5mu5qG9csDlJHrH0YUbQc76es0nka13FfM0WNQDsFM0d9WH7hCSft/2CRY8nafoj63vO13M2iXzkG09zRS3p1yV9XtLzFjwWSU3/sKjvfD1nk8hHvpE0u+vD9gOT3LFpW9OXV9yo53w9Z5PI17qK+Vq+et75tn/0G4Hth0m6aMJ5htZzvp6zSeRrXbl8LRf1RyV92PYu23slfVbSGZNONKye8/WcTSJf68rla3bXhyTZ/iNJJ2p2qucfJLls2omG1XO+nrNJ5GtdtXzNFbXt12y8K+klkq6VdJUkJTl7irmG0nO+nrNJ5CPfeFo86uPwTfcvOMj2VvWcr+dsEvlaVzZfcytqANhpWlxRS6p5KcIh9Zyv52wS+VpXMV+zK+qKlyIcUs/5es4mka91FfO1XNTlLkU4pJ7z9ZxNIl/rKuZruajfrGKXIhxSz/l6ziaRr3UV87Vc1OUuRTiknvP1nE0iX+sq5mu2qAFgp2j2qA9Jsv04ScdIOmx9W5J/mG6iYfWcr+dsEvlaVy1fsytq22+S9DTN/jI/KenZki5NcvKUcw2l53w9Z5PI17qK+Vq+KNPJkp4h6dtJTpX0REkPnHakQfWcr+dsEvlaVy5fy0X9/SR3SbrT9hGavUvbxZsZcz3n6zmbRL7WlcvX5D5q25Z0je2HSHqnZgem3y7pikkHG0jP+XrOJpGvdVXztbyP+kcHpc+vGXtEkmsmHWpAPefrOZtEvtZVzNfyro/Lbf+SJCU5MPVf5Ah6ztdzNol8rSuXr+UV9VclHS3pJkn/o9n1Y5PkCZMONpCe8/WcTSJf6yrma7moH75oe5Kblj3LGHrO13M2iXytq5iv2aIGgJ2i5X3UALAjUNQAUBxFDQDFUdQAUNz/AUKIXw2PubVXAAAAAElFTkSuQmCC
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
<h3 id="Ranking"><span style="color: blue;">Ranking</span><a class="anchor-link" href="#Ranking">&#182;</a></h3><h4 id="The-three-first-movies-are-the-highest-ranked.-Following-the-order-of-the-2sd,-1st,-and-3rd-movie.-Those-are-the-original-movies.">The three first movies are the highest-ranked. Following the order of the 2sd, 1st, and 3rd movie. Those are the original movies.<a class="anchor-link" href="#The-three-first-movies-are-the-highest-ranked.-Following-the-order-of-the-2sd,-1st,-and-3rd-movie.-Those-are-the-original-movies.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">star_wars</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:</span> <span class="p">,</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
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
<h3 id="Number-of-views"><span style="color: blue;">Number of views</span><a class="anchor-link" href="#Number-of-views">&#182;</a></h3><h4 id="The-first-two-movies-of-the-trilogy-have-had-more-seen-than-the-others-that-can-relate-to-why-they-have-a-better-ranking.-At-least-is-possible-to-say-that-the-second-movies-were-more-popular.">The first two movies of the trilogy have had more seen than the others that can relate to why they have a better ranking. At least is possible to say that the second movies were more popular.<a class="anchor-link" href="#The-first-two-movies-of-the-trilogy-have-had-more-seen-than-the-others-that-can-relate-to-why-they-have-a-better-ranking.-At-least-is-possible-to-say-that-the-second-movies-were-more-popular.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="What-are-the-number-of-views-and-the-rank-of-different-groups?-Analyzing-the-number-of-views-for-fans-vs-non-fans-and-gender."><span style="color: red;">What are the number of views and the rank of different groups? Analyzing the number of views for fans vs non-fans and gender.</span><a class="anchor-link" href="#What-are-the-number-of-views-and-the-rank-of-different-groups?-Analyzing-the-number-of-views-for-fans-vs-non-fans-and-gender.">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Gender"><span style="color: blue;">Gender</span><a class="anchor-link" href="#Gender">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[18]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">male</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Gender&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Male&#39;</span><span class="p">]</span>
<span class="n">female</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Gender&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Female&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">male</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>

<span class="n">female</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
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
<h3 id="Ranking"><span style="color: blue;">Ranking</span><a class="anchor-link" href="#Ranking">&#182;</a></h3><h4 id="The-ranking-per-gender-follows-the-same-as-the-ranking-in-general-and-the-first-movies-still-highest-ranked.">The ranking per gender follows the same as the ranking in general and the first movies still highest-ranked.<a class="anchor-link" href="#The-ranking-per-gender-follows-the-same-as-the-ranking-in-general-and-the-first-movies-still-highest-ranked.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[20]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">male</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>

<span class="n">female</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
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
<h3 id="Number-of-views"><span style="color: blue;">Number of views</span><a class="anchor-link" href="#Number-of-views">&#182;</a></h3><h4 id="Same-for-the-number-of-views.-The-first-movies-have-more-views-but-we-have-more-males-watching-the-trilogy-than-females.">Same for the number of views. The first movies have more views but we have more males watching the trilogy than females.<a class="anchor-link" href="#Same-for-the-number-of-views.-The-first-movies-have-more-views-but-we-have-more-males-watching-the-trilogy-than-females.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Fans"><span style="color: blue;">Fans</span><a class="anchor-link" href="#Fans">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[21]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fans</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="kc">True</span><span class="p">]</span>
<span class="n">non_fans</span> <span class="o">=</span> <span class="n">star_wars</span><span class="p">[</span><span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Do you consider yourself to be a fan of the Star Wars film franchise?&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="kc">False</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fans</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>

<span class="n">non_fans</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
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
<h3 id="Ranking"><span style="color: blue;">Ranking</span><a class="anchor-link" href="#Ranking">&#182;</a></h3><h4 id="The-fans-have-a-big-preference-for-the-first-three-movies-while-the-non-fans-ranked-them-at-the-same-level.-Even-to-non-fans,-the-4th-move-is-the-second-highest-ranked.">The fans have a big preference for the first three movies while the non-fans ranked them at the same level. Even to non-fans, the 4th move is the second highest-ranked.<a class="anchor-link" href="#The-fans-have-a-big-preference-for-the-first-three-movies-while-the-non-fans-ranked-them-at-the-same-level.-Even-to-non-fans,-the-4th-move-is-the-second-highest-ranked.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fans</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">();</span>

<span class="n">non_fans</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">();</span>
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
<h3 id="Number-of-views"><span style="color: blue;">Number of views</span><a class="anchor-link" href="#Number-of-views">&#182;</a></h3><h4 id="The-fans-have-almost-a-stable-number-of-views-to-all-movies-while-the-non-fans-dropped-the-views-violently-after-the-fourth-movie-and-the-first-was-not-popular-too.-The-difference-in-the-number-of-views-between-fans-and-non-fans-is-almost-double-for-the-fans.">The fans have almost a stable number of views to all movies while the non-fans dropped the views violently after the fourth movie and the first was not popular too. <br />The difference in the number of views between fans and non-fans is almost double for the fans.<a class="anchor-link" href="#The-fans-have-almost-a-stable-number-of-views-to-all-movies-while-the-non-fans-dropped-the-views-violently-after-the-fourth-movie-and-the-first-was-not-popular-too.-The-difference-in-the-number-of-views-between-fans-and-non-fans-is-almost-double-for-the-fans.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><br /><br /></p>
<h2 id="Are-the-household-income-and-education-level-correlated-with-be-a-fan-or-not-and-the-ranking-of-the-movies?"><span style="color: red;">Are the household income and education level correlated with be a fan or not and the ranking of the movies?</span><a class="anchor-link" href="#Are-the-household-income-and-education-level-correlated-with-be-a-fan-or-not-and-the-ranking-of-the-movies?">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Household-income"><span style="color: blue;">Household income</span><a class="anchor-link" href="#Household-income">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[37]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">income</span> <span class="o">=</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;Household Income&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">agg</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">)</span>

<span class="n">income</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">round</span><span class="p">(</span><span class="mi">2</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[37]:</div>



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
      <th>ranking_movie_5</th>
      <th>ranking_movie_6</th>
      <th>ranking_movie_1</th>
      <th>ranking_movie_2</th>
      <th>ranking_movie_3</th>
    </tr>
    <tr>
      <th>Household Income</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>$0 - $24,999</th>
      <td>3.96</td>
      <td>4.10</td>
      <td>3.17</td>
      <td>2.74</td>
      <td>3.20</td>
    </tr>
    <tr>
      <th>$100,000 - $149,999</th>
      <td>4.17</td>
      <td>4.40</td>
      <td>3.40</td>
      <td>2.40</td>
      <td>2.85</td>
    </tr>
    <tr>
      <th>$150,000+</th>
      <td>4.38</td>
      <td>4.57</td>
      <td>2.96</td>
      <td>2.32</td>
      <td>3.03</td>
    </tr>
    <tr>
      <th>$25,000 - $49,999</th>
      <td>3.87</td>
      <td>4.25</td>
      <td>3.65</td>
      <td>2.48</td>
      <td>3.28</td>
    </tr>
    <tr>
      <th>$50,000 - $99,999</th>
      <td>4.18</td>
      <td>4.34</td>
      <td>3.09</td>
      <td>2.45</td>
      <td>3.11</td>
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
<div class="prompt input_prompt">In&nbsp;[61]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">income</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="n">income</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s1">&#39;Household Income&#39;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">income</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">11</span><span class="p">:</span><span class="mi">17</span><span class="p">],</span> <span class="n">kind</span><span class="o">=</span><span class="s1">&#39;bar&#39;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">8</span><span class="p">));</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;center left&#39;</span><span class="p">,</span> <span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">1.0</span><span class="p">,</span> <span class="mf">0.5</span><span class="p">));</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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b4X/tv0XFxcfef/99ze0V3u8jIyM8Jvf/GZzCGFzR8YfTzAFAAA4D2zcuLHrLbfccnlLS0vo0qVL/PTTTzck3dO5IpgCAACcB0aPHv11XV3dtzYb2r59e2rChAlFx49dtmzZutO5VPZsue+++/q/+uqrOW2PXX/99Xuqq6u3n8m8gikAAMB5qn///s0d3Rn3XKiurt5+piG0PYIp0GHuhwEAoDN4XAwAAACJEkwBAABIlGAKAABAotxjCgAAnJfqikeWns35RtbXrT71qDMza9asvJ49ezY/+OCDO9oev/fee/MmTJhw4IYbbjjQ2T2ciYcffji3R48eLffcc8/u06l74403es6ePXvQ+vXre/z617/+5Pbbb997OvWCKQAAQDtaWlpCHMchlUqd8VyPP/741rPQUqebM2fOru9SN3z48CMLFy5smD9/fr/vUu9SXgAAgKPWrVvXdfjw4SW33Xbb4JKSkvTUqVOHjho1auSIESNKZs6cmdc6Lj8/f/TMmTPz0un0yMLCwvSaNWu6Hz/Xo48+2re8vLzg4MGDUWVl5dCFCxf2OVnt1q1bM6+66qqCdDo9sqqqakheXt7obdu2tbuYuG7duq7Dhg0rmTp16pCCgoKSioqKYa+88kr22LFji4cMGTLq3Xff7RFCCDt27Ehdc801lxcWFqbHjBlTvGLFiqzm5uaQn58/+vPPPz+WuAcPHjyqsbExc9asWXkPPPBAvxBCWLt2bberr766oKSkZGRpaWlRe39jq6KioiM/+tGPDmdkfLeIacUUgPOSxxMBkJSGhobuv/71rxt++9vf/mnHjh2pfv36NTc1NYWrrrqqaMWKFVk/+tGPDocQQt++fZtqa2vr5s+fnzt//vx+ixYt+qx1joceeih3yZIll7711lsbs7Ky4uPfo73a+++/P2/8+PEH5s2bt33x4sW9Xnzxxb4n67OxsbH7okWLPiktLf3sBz/4wciamprLVq1aVf+73/2u99y5cwf89V//9aY5c+bkjRkz5tCSJUs2/f73v8+eNm3asPr6+tprr712X01NTe+f//znu5cuXXrJwIEDjwwaNKip7fx33nnnkGeeeeaz0aNHf7106dJL7r777sF//OMf15+tz7ktK6YAAABtDBgw4MikSZO+DCGE559/PiedTo9Mp9PpDRs2dP/www+PrRpWVVXtDSGEsrKy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kbFmzZqeN9988+XFxcXpGTNmDNm5c2eXU312Tz31VM6HH37Y4x//8R+3n2psW+4xBQAAaKNHjx4tIYRQX1/f9cknn+y3evXqutzc3ObKysqhX3311bHFve7du8chhJCZmRk3NTVFrceLiooO19bW9vj000+7FBcXt7sBUHu1cdxuhj2hrl27HivIyMg4NmcqlQrNzc0nnDOKonjSpElfTp8+vdvWrVsz33zzzd5z58791j2wzc3NITs7u6m+vr62o/288sor2f/u3/27Ae+///66EwXyE7FiCgAA0I69e/emsrKyWnJycpobGxszly1bdmlH6q644opDCxYs+KyiomJEQ0PDKVcZW5WVlR184YUXckII4eWXX+61f//+M9516corrzywcOHCy0II4bXXXsvu06dPU05OTktGRkaYPHnyvhkzZgwaMWLE4f79+39rdTYnJ6dl4MCBR5599tk+IXyzEdQHH3yQ1d57hBDC8uXLs/7u7/5uyKuvvroxPz+/6UTjTsSKKQAAcF46F493OZlx48YdHjVq1KGCgoKSwYMHf11aWnqwo7XXXXfdwXnz5m2ePHlywdKlS9d3pGb+/Plbp0yZMjydTvcZN27cwdzc3D/37t37pJfznkp1dfXWqqqqoYWFhemsrKyW55577tPW12699dY948ePH/nEE080tFf74osvfnLXXXcNqa6uHtDU1BTdeOONe8aNG3e4vbF///d/P+jQoUOpm2+++fIQQsjLyzuydOnSjR3tUzAFAAA4qqio6MiGDRvWtv7+0ksvNbQ3bsuWLR+1/lxeXn5o5cqV60II4bHHHjt2SWxlZeX+ysrK2uPnOVFtTk5O83vvvbe+S5cuYcmSJZcsX748+0SXxJ6sz7av9evXr/mdd97Z1N4c5eXlh+I4/lb4b9t/cXHxkffff39De7XH+2//7b91KHyfiGAKAABwHti4cWPXW2655fKWlpbQpUuX+Omnn25IuqdzRTAFAAA4D4wePfrrurq6b202tH379tSECROKjh+7bNmydcffF3ou3Hffff1fffXVnLbHrr/++j3V1dWntQvv8QRTAACA81T//v2bT2dn3M5WXV29/UxDaHvsygsAAECiThlMoygaFEXRu1EU1UVRtDaKop+fi8YAAAC4OHTkUt6mEMLsOI7/RxRF2SGE1VEU/Zc4js+b5WQAAAC+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
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
<h3 id="Ranking"><span style="color: blue;">Ranking</span><a class="anchor-link" href="#Ranking">&#182;</a></h3><h4 id="For-all-household-income,-the-second-movie-is-the-highest-ranked-and-the-sixth-is-the-least-ranked.">For all household income, the second movie is the highest-ranked and the sixth is the least-ranked.<a class="anchor-link" href="#For-all-household-income,-the-second-movie-is-the-highest-ranked-and-the-sixth-is-the-least-ranked.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[122]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Porcentage of fans per household income</span>

<span class="n">ax</span> <span class="o">=</span> <span class="p">(</span>
        <span class="p">(</span><span class="n">fans</span><span class="p">[</span><span class="s1">&#39;Household Income&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span> <span class="o">/</span> <span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Household Income&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span> <span class="o">*</span> <span class="mi">100</span><span class="p">)</span>
        <span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="p">)</span>

<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">{}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">(),</span> <span class="mi">2</span><span class="p">)),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span> <span class="o">+</span> <span class="mf">0.1</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span> <span class="o">+</span> <span class="mf">1.1</span><span class="p">),</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">16</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;red&#39;</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span>

<span class="n">plt</span><span class="o">.</span><span class="n">tight_layout</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA+gAAALICAYAAADseNpmAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOzde5hcVYHv7++ScBOEcAkYUQwgICaCYriIZxQEAeWnIs9BhaDxgqAZuThwHFCRiNxHUWQU5YgSVFBgZGBAQUDR0QEkCIoEJI4CKgyJIkIg3Pfvj9V9Op10ks6NXna/7/P0U1W7dlUtM0/R8+m199ql67oAAAAAQ+s5Qz0AAAAAQKADAABAEwQ6AAAANECgAwAAQAMEOgAAADRg1LP5Yeuvv343bty4Z/MjAQAAoCk33XTTn7uuGzP/9mc10MeNG5fp06c/mx8JAAAATSml3D3Qdoe4AwAAQAMEOgAAADRAoAMAAEADBhXopZTRpZSLSil3lFJuL6W8upSybinlqlLKzJ7bdVb0YAEAAGC4GuwM+ulJrui67qVJtklye5KjklzTdd3mSa7peQwAAAAshcUGeillrSSvTXJ2knRd90TXdQ8meWuSaT27TUuy94oaJAAAwLB17bVJKQv+jB7dt8973jPwPqUkL33p4j/jL39JDjss2XTTZPXVk002ST784WT27P77Pfpo8pGPJBttlKy2WvLylyff+taC73feeclmmyXrrpt84APJ3Ln9n7/77mTNNZMbbljSf40RbTCXWds0yewkXy+lbJPkpiSHJdmw67r7kqTruvtKKRsM9OJSykFJDkqSjTfeeLkMGgAAYNj5wheS7bbrezxqnlw75pjkgx/sv/9ddyX77Ze85S2Lft+uq/vceWdy3HHJVlslM2bU97zppuS//quGfpLss09y3XXJ8ccnW26ZfPe7yQEHJM88k7zrXXWfO+9MJk+u7zV+fDJlSnLKKcnUqX2feeihyaRJyQ47LO2/xog0mEAflWTbJId0XXdDKeX0LMHh7F3XnZXkrCSZOHFit1SjBAAAGO622irZcceBn9tss/ozr6uuqreTJy/6fWfOrBH+la8kBx1Ut+28c/Kc5yQf+lAN7i23TH760+TKK5Ovf73O2CfJ7rsnf/xj8s//nOy/f7LSSvVzN988Ofrous+MGcnFF/cF+mWX1ci/444l/AdgMOeg/zHJH7uu6z024aLUYL+/lDI2SXpuZ62YIQIAALCAc89NXvWqOou9KE88UW/XWqv/9t5D6J95pt5ef329feMb+++3557Jfff1Pf/EE/Uw+V5rrJE89li9P3dunT0/9dR6+DtLZLGB3nXd/yT5Qylly55NuyaZkeTSJL1/qpmc5JIVMkIAAICRYNKkOkO93np1tvqeexa+789+lvz2t4ufPU9qwL/2tcmnP51Mn57MmZP8/Of1EPU3vrHO3Cf1s5NklVX6v37VVevtr39db3fYIfnlL+tM+r331hn33pn/E0+s568PZlwsYDCHuCfJIUm+VUpZJcnvkrw3Ne4vKKW8P8k9SfZdMUMEAAAYxtZeOzniiOR1r6uz3DffXEP31a+u9zcYYLmvc89NVl65noO+OKUk3/tePYd83nPc99orufDCvsdb9szJXn99/1n0666rtw88UG932qkuOLf77vXxNtvUw9tnzkw+97n6+t5z2lkipeuevdPCJ06c2E2fPv1Z+zwAAIC/S7/4RbL99slRR9UF2+b1+OPJ85+f7LJLXcRtMPbfv64Wf+yxdcb89tvr/Ve9KvmP/6jnoz/1VLL11smTT9Y/ALz0pfX9P/zhegj7ySfXc9F7/fnPyd/+VleGLyXZY4/6+n/5l+Q736nRPmtWsttuyZlnOuR9HqWUm7qumzj/9sFeBx0AAIBny7bbJltskdx444LPXXJJ8uCDgz+M/PLLk/PPT77xjeTgg+vh7gcfXB9/73s10JO6avxFF9VzynfaqQb1xz+enHRSfX7s2P7vu/76deG6UupM/IwZNfpvvz1597uTM86oK80/9FCdcWexBDoAAECLum7gQ8WnTatx/KY3De59br213s57eHtSZ+iTGtS9Xvay5JZbkt//vp5z/oc/9IX5a14z8PvPmVOvnX766fXa51dfnUyYUGfOn/e8ehm2K64Y3FhHOIEOAADQmunT6+XP5r+O+P33Jz/4QT1kfeWVB/dez39+vf35z/tvv6HnQl0bbbTga8aN61sd/l//tZ5vPv9l3npNnVoPbd9nn75tjzzSd3/OnPrHBhbLOegAAABDadKkZJNN6mHto0fXheFOOil57nPruejrr9+372mn1QXlbrqp7j+QUaPq4e9nn10fP/RQPe+865Jjjqnnlt9xR/KpT9UV22fMqDPfSf3cF784ecEL6iryX/xivf3Zz+q55vO77ba6mN0tt/Q9f9ttNdiPPbbO0h9xRF1I7rzzlt+/2d+5hZ2DPthV3AEAAFgRJkyo54ifcUby6KN1xnuffWpAzxvnST28fcKEhcd5kjz9dP3ptdZadWX1qVPr9cnvu68etv7mN9dtvXGe1Jnvj3+8Xj5t9Oh6DfSLLkpe9KKBP2vKlOTII/vH+/jxyTnn1Pf+zGeSXXeth7+zWGbQAQAA4FlkFXcAAABomEAHAACABgh0AAAAaIBABwAAgAYIdAAAAGiAQAeAoXbttUkpC/6MHr3gvtdfXy95M3p0ssYayctfnnz724v/jGeeqde2HTcuWW21ej3af/u3Bfd773vrtXLXWqtedmebbeplf+a9XE9Sr2W72WbJuusmH/hAMndu/+fvvru+/oYbBvuvAAAjnuugA0ArvvCFZLvt+h6Pmu/X9OWXJ297W7L//jWQV1klmTEjeeyxxb/3McfUa9GecELyqlfVqN933+Syy5I3valvv7lzk0MOqfFdSnLllclhhyW//W3fNWzvvDOZPDk57rh6rdspU5JTTqnXu+116KHJpEnJDjss9T8HAIw0roMOAEPt2muTXXZJrroq2W23gfd5+OEazfvvn3z+80v2/rNmJS96UXLUUcmnPtW3fdddk9mzk1/9atGv32+/GvIPP1wff/GL9WfGjPr45JOTiy/umy2/7LLkfe9L7rijzrADAP24DjoA/D278MIa00ccseSvvfLK5IknkgMO6L/9gAOSW29Nfv/7Rb9+vfX6z+Y/8USy+up9j9dYo28Wf+7cOnt+6qniHACWkEPcAaAVkyYlf/5zPb98jz3qzPTGG9fnfvrTGry33loPSb/99mTs2OTAA5NPfCJZaaWFv+9ttyWrrpq85CX9t48fX29nzEg22aRve9fVc87nzEmuuSaZNi356Ef7nt9hh+T//J864z9+fPL1ryc77lifO/HEZKON6iHwAMPUuKMuH+ohjGh3nbzXUA9hhRHoADDU1l67zoy/7nV1cbabb66h++pX1/sbbJDce2/y6KP1EPdjjqnnkV99dfLpTycPPph87nMLf/8HHqjRX0r/7b0z3A880H/75Zcnb35zvV9KPTT+mGP6nt9pp3pe+u6718fbbFPPP585s47j+usX/CwAYLEEOgAMtVe+sv70et3rkte+Ntl++7pw3PHH11XYH3usLvL2T/9U99t55+Qvf6nng0+dWkN/IF03cDAvbB2af/iH5MYbk7/9rc6gf+Yz9fUnnNC3z2c/mxx9dN1n003r83vskXzoQ8mECcl3vlPHNGtWPa/+zDMd8g4Ai+EcdABo0bbbJltsUUM5qeeBJ8kb3tB/v913T558sh7GvjDrrpv89a8LBvlf/9r3/LzWXjuZOLEuInfiicnHPlYPt//Tn/rvt/76fau9X3hhPVT+2GPr4ffvfne9PNtddyUPPVRn3AGARRLoANCqeWe+e88Xn38mvDe6n7OIX+njxyePP57893/33967CvvLXrbocUycWGfwF7aY3Jw5yUc+Ui/Dtuaa9dD7CRPqzPnznlcvw3bFFYv+DABAoANAk6ZPr9cb772O+N5719v5Q/fKK5PVVqtBvDB77lmvmf6tb/Xf/s1v1tfNu0DcQH784/qHgU03Hfj5qVOTrbdO9tmnb9sjj/TdnzNn4YfTAwD/j3PQAWCoTZpUI3nbbetibjffnJx0Ul0N/ZBD6j4TJiTveU/yyU/W2extt60z1V/9al3Abc01+95v1Ki6ivrZZ9fHG2xQZ7hPOqnOaG+7bT1H/Ic/TC65pO91l19eV2R/85vr6vEPP5x8//vJWWclBx+cvOAFC479ttvq87fc0rft9a9PDj88Oe64eh798cf3LSgHACyUQAeAoTZhQnL++fWc7UcfTZ7//Dob/alP1fO8e33lKzXazzgjuf/+ZNy45LTTFjy/++mn68+8TjihRvzppyf/8z/JllsmF1zQt1p7Us8nf+aZetm2WbPqHws23zw599xkv/0GHvuUKcmRR/afXR8/PjnnnDqz/pnP1HPZTz99Gf6BAGBkKN2zeMjZxIkTu+nTpz9rnwcAALC8uQ760BoO10EvpdzUdd3E+bc7Bx0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGjBqqAcAAH9Pxh11+VAPYcS76+S9hnoIALBCmEEHAACABgh0AAAAaIBABwAAgAYIdAAAAGiAQAcAAIAGCHQAAABogEAHAACABgh0AAAAaIBABwAAgAYIdAAAAGiAQAcAAIAGCHQAAABogEAHAACABgj0oXbttUkpC/6MHt23zzXXJAcckGy2WbL66vX2Qx9KZs1a/Ps//HDy9rcnL3lJssYa9X132CH55jcX3HfnnQcey+c/33+/886rY1h33eQDH0jmzu3//N13J2uumdxww5L+awAAAIxYo4Z6APT4wheS7bbrezxqnv/TfPnLyZw5ySc+kWy6aTJzZnLsscmVVya/+lWN4YV54on6XkcfnYwblzz+ePKd7yTvelcye3bykY/033/rrZOvfKX/tnHj+u7feWcyeXJy3HHJ+PHJlCnJKackU6f27XPoocmkSfUPAQAAAAyKQG/FVlslO+448HNf+lIyZkzf49e9Ltlii3p7wQXJ+9638Pddb7064z2vN72phvbXvrZgoD/veQsfR5JcdVWy+eY1+JNkxozk4ov7Av2yy5LrrkvuuGPh7wEAAMACHOL+92DeOO/VO9v+pz8t3Xuut16y8spL/ronnqiH2fdaY43kscfq/blz6+z5qafWw98BAAAYNIHeikmTkpVWquG8//7JPfcsev8f/7jebrXV4N6/65Knnkr+8pfkrLPq4fGHH77gfjffnKy9do33rbdOzj67//M77JD88pd1Jv3ee5Ovf71vxv3EE5ONNqqHwAMAALBEHOI+1NZeOzniiHq4+lpr1UA+8cTk1a+u9zfYYMHXPPxwjeuttkr23ntwn/PFLyaHHFLvr7xycvrpybvf3X+f1762/qFgiy2SBx9Mzj03OfDA5L776vnvSbLTTslhhyW7714fb7NNPbx95szkc59Lrr++LiwHAADAEhHoQ+2Vr6w/vV73uhrK229fF447/vj++z/1VLLffvXQ9p/9rP9icovyjnfUme4//zm59NIa6yutlBx8cN8+xx3X/zVvfWvytrclJ5xQ/yDQuxjdZz9bz0H/29/qonWlJHvsUVeWnzChLkI3dWpdZX633ZIzz3TIOwAAwGI4xL1F225bZ7FvvLH/9meeqYePX3118u//Xg9BH6wxY5KJE5M996yLzr3rXcmRRyZPPrno1+23Xz3H/NZb+29ff/16qbVSkgsvrIvFHXtscvvtdWb+jDOSu+5KHnqozrgDAACwSAK9VV234KHiH/xgnZ3+9reTXXddtvefOLFeuu3++xc/jmThh63PmVNXgj/99DrDfvXVdRZ9t93qivBTpiRXXLFsYwUAABgBBHqLpk+vl0Gb9zriRxyRfPWrdVG2wZ53vig//nEN6oHOcZ/XeefVVdtf/vKBn586tc7k77NP37ZHHum7P2dOX+QDAACwUM5BH2qTJiWbbFIPax89ui4Md9JJdTX03kXdTjklOe20er3zzTevC7H1GjOmHmrea9Soehh87+rrX/lK3X+33ZIXvrCu4n7BBclFFyUnn5ysskrd7z//sz7eZ59k3Lh6fvm0afV89ZNPrpdTm99tt9UV4W+5pW/b619fz1c/7rh6Hv3xx/ctKAcAAMBCCfShNmFCcv759ZztRx9Nnv/8Gsmf+lQ9zztJvv/9evu1r9WfeU2enJxzTt/jp5+uP71e/vLkkkvq+eYPPFDfc6utkssuS/baq2+/sWPrOe6f/GRdSK73MmvnnVfPQx/IlCn1fTfdtG/b+PF1PFOnJp/5TD0U//TTl/IfBwAAYOQo3bN4+PHEiRO76dOnP2ufBwDL27ijLh/qIYx4d5281+J3AliB/C4YWsPh90Ap5aau6ybOv9056AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQgFFDPYC/J+OOunyohzDi3XXyXkM9BAAAgBXCDDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADRg1mp1LKXUkeTvJ0kqe6rptYSlk3yXeSjEtyV5K3d1331xUzTAAAABjelmQGfZeu617Rdd3EnsdHJbmm67rNk1zT8xgAAABYCstyiPtbk0zruT8tyd7LPhwAAAAYmQYb6F2SH5RSbiqlHNSzbcOu6+5Lkp7bDVbEAAEAAGAkGNQ56Ele03XdvaWUDZJcVUq5Y7Af0BP0ByXJxhtvvBRDBAAAgOFvUDPoXdfd23M7K8nFSbZPcn8pZWyS9NzOWshrz+q6bmLXdRPHjBmzfEYNAAAAw8xiA72UskYp5Xm995PsnuTXSS5NMrlnt8lJLllRgwQAAIDhbjCHuG+Y5OJSSu/+53Vdd0Up5cYkF5RS3p/kniT7rrhhAgAAwPC22EDvuu53SbYZYPtfkuy6IgYFAAAAI82yXGYNAAAAWE4EOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAPt2XPPpJTkE5/o23bXXXXbQD8PPrj49zzttOTNb07Gjq2vmTp14fv+9a/J4YcnG2+crLpq8sIXJu95T/99zjsv2WyzZN11kw98IJk7t//zd9+drLlmcsMNg/wfDQDASDdqqAcA0M/55ye//OXCnz/66OQtb+m/7XnPW/z7/t//m6y1VrL33smXv7zw/f761+R//a8a8ccfn4wbl9x7b/Kzn/Xtc+edyeTJyXHHJePHJ1OmJKec0j/6Dz00mTQp2WGHxY8NAAAi0IGWPPhg8pGPJJ/7XLL//gPvs+mmyY47Lvl733Zb8pznJE89tehAP/roZM6c5NZba9D3euc7++5fdVWy+eZ13ySZMSO5+OK+QL/ssuS665I77ljycQIAMGI5xB1ox0c/Wmek99tv+b/3cwbxn7tHHknOPTc58MD+cT6/J55IVl+97/EaaySPPVbvz51bZ89PPbUe/g4AAIMk0IE2/PSnNY6/9KVF73f00cmoUcnaa9dD3W+9dfmN4aabamBvuGHyv/93jfA116yHxf/+93377bBDPQz/qqvq4e9f/3rfrP6JJyYbbVQPgQcAgCUg0IGh9+STycEHJ0cemWy55cD7rLpq3ecrX0l+9KPkM5+pcb7TTsntty+fcdx7b7098shkpZWSSy9NzjorufnmZOedk4cfrs/vtFNy2GHJ7rvXGH/mmXp4+8yZ9fD8M8+s57ADAMASEOjA0DvllDpz/fGPL3yfsWPrueP77JP8wz/UldN/8pMawiecsHzG8cwz9XaTTZJvfzt5wxvqufAXXJDcc0/yzW/27fvZzyazZye//W0N+LFjkw9/OPnQh5IJE5LvfCfZaqtkvfWSd7wjeeCB5TNGAACGLYEODK177qmB/elPJ48/XheK671sWu/jp58e+LUvelFdcf3GG5fPWNZbr97utlv/GfAddqjnpN98c//911+/XmqtlOTCC+ticcceW2f03/3u5Iwz6uXhHnqozrgDAMAiCHRgaP3ud3WBtQMOSNZZp+8nqYexr7POos8z77rldzj5+PH1dmHvt7CF5ubMqavPn356PWf96qvrLPpuu9VLwE2ZklxxxfIZIwAAw5ZAB4bWK15Rzymf/yep0f6jHyUvecnAr73nnnp98uV1rfEXvjCZODH5wQ9q+Pe67ro6C77ddgO/burUZOut6+H3vR55pO/+nDn93w+ARdtzz/rH0k98YuH7HHxw3eeAAxb/fnfeWY9k2nrr+ofUsWPrQqO//OWC+372s/X3wYYb1oVJe09/6nXDDfWPr3ffvWT/mwAGwXXQgaE1enRdgG0gL35x33NHHFH/n6RXvzoZMyb5zW+Sk06qs9of+1j/140aVVdRP/vsvm3Tp9fDzXv/H60ZM5KLLqr33/Sm5LnPrfdPPjnZY4+6ivuBB9bzzD/+8eSlLx342uy33VYXkrvllr5tr399cvjhyXHHJdtvnxx/fF1QDoDFO//8gcN5Xv/1X8m3vrXoS2LO6wc/qH/wnTw52XbbevrUqafWP/D+7GfJq15V9/vhD5Ojjkq++MUa4QcfXBcvfc976vNPP13XGvnYx+rvKIDlzAw68Pdh/Ph6KbaDD66Lt02dmrzmNXUmY/6V359+esHz1v/1X5N9960LtiX1nPF9960/s2b17bfrrsl//EednX/b2+qh67vsklx7bf9rn/eaMqWu+r7ppv3Hes45ybRpydvfnmyxRT38HYBFe/DB+t/d005b+D5PPpkcdFD942nvKVGL88531ug/4oj63/S3va2eerT66v3/+/z979ffMQcdlOy3X/3D7Pe/3/f8l75UT8s68sil+98HsBhm0IE2zX9I+PveV3+W5rVJDeZzzhnc69/4xvozGD/+8cDb3/Wu+gPA4H30o/WPnL1xPJB/+Zf6R9gjjqiX3hyM9ddfcNvaa9c/oP7pT33bnnii/x9j11gjue++ev/++5NPfjL57neTlVce3OcCLCEz6AAADL2f/jQ599w6S70w//3f9bShL30pWWWVZfu8Bx5Ifv3reknMXjvsUBf6/MUv6mU0L7ww2XHH+tyRRyZ77VVn4AFWEDPoAAAMrSefrKcwHXnkgqctzeuDH6wLci6PSD7kkHrE1eGH9217xzuSf//3vnPSd9klOfTQerTUZZcld9yx7J8LsAhm0AEAGFqnnJLMnVvPK1+Yb34zufHGegnOZXXSScl559X1Sea9UshKKyUXXFAPe7/rrrpo3CqrJP/4j3XmfsMN6znrm26abLBB/YPB3LnLPh6AHgIdAIChc889yQknJJ/+dPL443WhuAcfrM/1Pv7b35J/+qfkn/85WW21vn2eeabOvj/4YL0djC9/ua7CfvzxC1/b5AUv6Ful/fOfr5/5oQ8lV12VHHNMPQ/9ttuSn/88OfHEZf83AOgh0AEAGDq/+11dGf2AA+qq7L0/SZ0tX2ed5Pe/r5e9/NjH+u/zhz/UGe911kkuv3zxn/WNb9SrbxxxxKJn63v98Y815M88s17W84or6irvr3hFveTne99btwEsJ85BBwBg6LziFfUa5fPbZZca7e9/fz0MfaB93vnO5OUvr7E9YcKiP+fii2tQH3jg4A+TP/zwZNKkZLvt+rY98kjf/TlzBr5yCMBSEugAAAyd0aOTnXce+LkXv7jvuYH2WW21el74/M+NGpVMnpycfXZ9/JOf1Eu3bb118p73JNdf37fvqqsmr3zlgu995ZXJf/5n8pvf9G3bbbd6DvqXvlQPgz/jjPp+AMuJQAcAYHh5+un60+uHP6zns998c/Ka1/Tf98UvrgvCzevxx5MPf7hec3306L7tb3xjPef8xBOTRx9N9t47+cQnVtj/DGDkEegAALRnMIeOzx/WC3vt1Kn1Z7BWXTWZOXPg5z760foDsAIIdGCJjDtqEIvwsMLcdfJeQz0EAABWEKu4AwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRg1FAPAACAvx/jjrp8qIcw4t118l5DPQRgBTGDDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0YdKCXUlYqpdxcSrms5/G6pZSrSikze27XWXHDBAAAgOFtSWbQD0ty+zyPj0pyTdd1mye5pucxAAAAsBQGFeillBcm2SvJV+fZ/NYk03ruT0uy9/IdGgAAAIwcg51B/3ySjyZ5Zp5tG3Zdd1+S9NxuMNALSykHlVKml1Kmz549e5kGCwAAAMPVYgO9lPL/JZnVdd1NS/MBXded1XXdxK7rJo4ZM2Zp3gIAAACGvVGD2Oc1Sd5SSnlTktWSrFVK+WaS+0spY7uuu6+UMjbJrBU5UAAAABjOFjuD3nXd0V3XvbDrunFJ3pnkh13XHZDk0iSTe3abnOSSFTZKAAAAGOaW5TroJyd5QyllZpI39DwGAAAAlsJgDnH/f7quuzbJtT33/5Jk1+U/JAAAABh5lmUGHQAAAFhOBDoAAAA0QKADAFYjEEAAAB0hSURBVABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMEOgAAADRAoAMAAEADBDoAAAA0QKADAABAAwQ6AAAANECgAwAAQAMWG+illNVKKT8vpfyylHJbKeVTPdvXLaVcVUqZ2XO7zoofLgAAAAxPg5lBfzzJ67uu2ybJK5LsWUrZMclRSa7pum7zJNf0PAYAAACWwmIDvavm9DxcueenS/LWJNN6tk9LsvcKGSEAAACMAIM6B72UslIp5ZYks5Jc1XXdDUk27LruviTpud1gIa89qJQyvZQyffbs2ctr3AAAADCsDCrQu657uuu6VyR5YZLtSykTBvsBXded1XXdxK7rJo4ZM2ZpxwkAAADD2hKt4t513YNJrk2yZ5L7Syljk6TndtZyHx0AAACMEINZxX1MKWV0z/3Vk+yW5I4klyaZ3LPb5CSXrKhBAgAAwHA3ahD7jE0yrZSyUmrQX9B13WWllOuSXFBKeX+Se5LsuwLHCQAAAMPaYgO967pfJXnlANv/kmTXFTEoAAAAGGmW6Bx0AAAAYMUQ6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQAIEOAAAADRDoAAAA0ACBDgAAAA0Q6AAAANAAgQ4AAAANEOgAAADQgMUGeinlRaWUH5VSbi+l3FZKOaxn+7qllKtKKTN7btdZ8cMFAACA4WkwM+hPJTmi67qtkuyY5B9LKS9LclSSa7qu2zzJNT2PAQAAgKWw2EDvuu6+rut+0XP/4SS3J9koyVuTTOvZbVqSvVfUIAEAAGC4W6Jz0Esp45K8MskNSTbsuu6+pEZ8kg0W8pqDSinTSynTZ8+evWyjBQAAgGFq0IFeSlkzyb8lObzruocG+7qu687qum5i13UTx4wZszRjBAAAgGFvUIFeSlk5Nc6/1XXdd3s2319KGdvz/Ngks1bMEAEAAGD4G8wq7iXJ2Ulu77rutHmeujTJ5J77k5NcsvyHBwAAACPDqEHs85ok70pyaynllp5tH0tycpILSinvT3JPkn1XzBABAABg+FtsoHdd99MkZSFP77p8hwMAAAAj0xKt4g4AAACsGAIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABAh0AAAAaINABAACgAQIdAAAAGiDQAQAAoAECHQAAABog0AEAAKABiw30UsrXSimzSim/nmfbuqWUq0opM3tu11mxwwQAAIDhbTAz6Ock2XO+bUcluabrus2TXNPzGAAAAFhKiw30rut+kuSB+Ta/Ncm0nvvTkuy9nMcF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
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
<h3 id="Fans-per-household-income"><span style="color: blue;">Fans per household income</span><a class="anchor-link" href="#Fans-per-household-income">&#182;</a></h3><h4 id="The-percentage-of-fans-per-household-income-is-bigger-for-the-highest-income.">The percentage of fans per household income is bigger for the highest income.<a class="anchor-link" href="#The-percentage-of-fans-per-household-income-is-bigger-for-the-highest-income.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Education"><span style="color: blue;">Education</span><a class="anchor-link" href="#Education">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[129]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">education</span> <span class="o">=</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;Education&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">agg</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">)</span>

<span class="n">education</span><span class="o">.</span><span class="n">iloc</span><span class="p">[:,</span> <span class="mi">9</span><span class="p">:</span><span class="mi">15</span><span class="p">]</span><span class="o">.</span><span class="n">round</span><span class="p">(</span><span class="mi">2</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[129]:</div>



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
      <th>ranking_movie_5</th>
      <th>ranking_movie_6</th>
      <th>ranking_movie_1</th>
      <th>ranking_movie_2</th>
      <th>ranking_movie_3</th>
    </tr>
    <tr>
      <th>Education</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Bachelor degree</th>
      <td>4.29</td>
      <td>4.52</td>
      <td>3.11</td>
      <td>2.31</td>
      <td>2.93</td>
    </tr>
    <tr>
      <th>Graduate degree</th>
      <td>4.23</td>
      <td>4.50</td>
      <td>3.20</td>
      <td>2.32</td>
      <td>2.92</td>
    </tr>
    <tr>
      <th>High school degree</th>
      <td>3.75</td>
      <td>4.13</td>
      <td>3.21</td>
      <td>2.87</td>
      <td>3.24</td>
    </tr>
    <tr>
      <th>Less than high school degree</th>
      <td>5.33</td>
      <td>3.67</td>
      <td>2.67</td>
      <td>1.00</td>
      <td>3.33</td>
    </tr>
    <tr>
      <th>Some college or Associate degree</th>
      <td>3.89</td>
      <td>4.10</td>
      <td>3.50</td>
      <td>2.78</td>
      <td>3.17</td>
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
<div class="prompt input_prompt">In&nbsp;[141]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">education</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="n">education</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s1">&#39;Education&#39;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">income</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">8</span><span class="p">:</span><span class="mi">14</span><span class="p">],</span> <span class="n">kind</span><span class="o">=</span><span class="s1">&#39;bar&#39;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">8</span><span class="p">));</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;center left&#39;</span><span class="p">,</span> <span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">1.0</span><span class="p">,</span> <span class="mf">0.5</span><span class="p">));</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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tMU1n0z6pBU6AaA1WTEFAAAgUYIpAAAAiRJMAQAASJRgCgAAQKIEUwAAABIlmAIAAJAowRQAAIBECaYAAAAkKiPpBgAA4HT6Pvxui2s2ZbZCI0CrsGIKAABAogRTAAAAEmUrLwAAnIHKgYNaXDOoqrIVOoG/XlZMAQAASJRgCgAAQKIEUwAAABIlmAIAAJAowRQAAIBEuSovAABwXlixYsXfZGRkvBRCGBIsol1o6kMIn9bW1t41YsSIL058UTAFAADOCxkZGS917959UG5u7p60tLQ46X44e+rr66OdO3emtm/f/lIIYfyJr/tXCAAA4HwxJDc3d79QeuFJS0uLc3Nz94VvVsP/8vVz3A8AAMDJpAmlF65j/982mUEFUwAAABLlHFMAAOC81Pfhd0eczfk2zfrXK87mfE2ZNm1azw4dOtQ9+uijOxoff+CBB3pec801B37yk58caO0ezsTjjz+e2759+/r7779/13epnzNnTpfJkyf3//DDDytHjRp1qLl1gikAAEAT6uvrQxzHIT09/YzneuaZZ2rOQkutbvr06Tu/a+2ePXvSZs+e/Tff+973vmppra28AAAAx6xZs6Zt//79B99+++35gwcPTt122219hwwZMmjAgAGDp06d2rNhXF5e3tCpU6f2TKVSgwoLC1MrV67MPHGuJ598suuoUaMKDh48GJWUlPSdM2dOl1PV1tTUZFx99dUFqVRqUGlpaZ+ePXsO3bZtW5OLiWvWrGnbr1+/wbfddlufgoKCwePHj+/31ltvZQ8fPnxgnz59hvz+979vH0IIO3bsSL/22msvKywsTA0bNmzg0qVLs+rq6kJeXt7QL7/88njizs/PH1JdXZ0xbdq0no888ki3EEJYvXp1ux/84AcFgwcPHjRixIiipn7Hxh588MG8Bx98cHu7du1afJ6wFVMAgO/gydt+3OKaB+e90wqdAGfbpk2bMn/1q19t+vWvf/35jh070rt161ZXW1sbrr766qKlS5dmXXnllYdDCKFr1661FRUVlbNmzcqdNWtWt3nz5m1umOOxxx7LXbhwYaf58+evz8rK+oug1lTtww8/3HP06NEHZs6cuf3111/v+Nprr3U9VZ/V1dWZ8+bN2zhixIjN3/ve9waVl5dfunz58qrf/OY3nWfMmNHjhz/84Ybp06f3HDZs2KGFCxdu+O1vf5s9adKk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QghPPfXU8S2xJSUl+0tKSipOnOdktTk5OXUfffTR2jZt2oSFCxdesmTJkuyTnaN6qj4bv9atW7e6Dz74YENTc4waNepQHMffWpVu3P/AgQOPfvzxx+uaqj3R6NGjD+3YseP/NGdsUwRTAACA88D69evb3nrrrZfV19eHNm3axC+88MKmpHs6VwRTAACA88DQoUO/rqys/NbFhrZv355+zTXXFJ04dvHixWtOPC/0XHjooYe6v/322zmNj9144427y8rKtp/JvIIpAADAeap79+515+rKuM1RVla2/UxDaFNc/AgAAIBECaYAAAAkSjAFAAAgUc4xBQAAzkuzf7poxNmc777/PGbF6UeRBCumAAAAZ8m0adN6PvLII91OPP7AAw/0fOutt7KT6KklHn/88dznnnvu0pbW/eIXv+h22WWXDS4sLEyNHDmycO3atW1bUm/FFAAAoAn19fUhjuOQnp5+xnM988wzNWehpVY3ffr0nd+lbsSIEYcefPDByuzs7PqysrLcqVOn9nr33Xc3NrfeiikAAMAxa9asadu/f//Bt99+e/7gwYNTt912W98hQ4YMGjBgwOCpU6f2bBiXl5c3dOrUqT1TqdSgwsLC1MqVKzNPnOvJJ5/sOmrUqIKDBw9GJSUlfefMmdPlVLU1NTUZV199dUEqlRpUWlrap2fPnkO3bdvW5GLimjVr2vbr12/wbbfd1qegoGDw+PHj+7311lvZw4cPH9inT58hv//979uHEMKOHTvSr7322ssKCwtTw4YNG7h06dKsurq6kJeXN/TLL788nrjz8/OHVFdXZzRe8V29enW7H/zgBwWDBw8eNGLEiKKmfscGN9xww4Hs7Oz6EEL427/924Pbtm1r0YqpYAoAANDIpk2bMu+4445dlZWVFbNnz67+9NNPK6uqqlYvWbIke+nSpVkN47p27VpbUVFROXny5J2zZs361vbdxx57LPfdd9/tPH/+/PUdOnSIT3yPpmoffvjhnqNHjz5QUVFRefPNN+85Xbirrq7OfPDBB7+oqqpavWHDhszy8vJLly9fXjVjxowtM2bM6BFCCNOnT+85bNiwQ2vXrq345S9/uXXSpEn90tPTw3XXXbe3vLy8cwghLFq06JJevXod7d27d23j+e+6664+zz///OerV6+ufOKJJ7bce++9+c35/F544YXca6+9dl9zxjYQTAEAABrp0aPH0bFjx34VQgivvPJKTiqVGpRKpVLr1q3LXLVq1fFVw9LS0j0hhFBcXHyourq6XcPxefPmXbpgwYJO77333oasrKy/CKUnq122bFmHSZMm7Q4hhAkTJuzv2LFj3an6zMvL+7q4uPhwenp6KCwsPDxmzJj9aWlpYfjw4Ye2bNnSMGf2nXfeuSuEEMaPH39g7969Gbt27UovLS3d/frrr+eEEEJ5eXlOSUnJ7sZz79u3L23lypUdbrnllssGDhyYmjJlSp8vvviizek+u+effz5n1apV7f/jf/yP2083tjHnmAIAADTSvn37+hBCqKqqavvcc891W7FiRWVubm5dSUlJ3yNHjhxf3MvMzIxDCCEjIyOura2NGo4XFRUdrqioaP/ZZ5+1GThw4NGm3qOp2jhuMsOeVNu2bY8XpKWlHZ8zPT091NXVnXTOKIrisWPHfnXnnXe2q6mpyXj//fc7z5gx41vnwNbV1YXs7Ozaqqqqiub289Zbb2X/p//0n3p8/PHHa04WyE9GMAUAAM5LSd/eZc+ePelZWVn1OTk5ddXV1RmLFy/uNHr06AOnq7v88ssP3XfffTvHjx8/YMGCBev69u375+a8X3Fx8cFXX301Z8aMGdvffPPNjvv37z/jqy5dddVVB+bMmXPpE088se2dd97J7tKlS21OTk59CCGMGzdu75QpU3oPGDDgcPfu3b+1OpuTk1Pfq1evoy+//HKXyZMn76mvrw9Lly7NGjly5OGm3mfJkiVZ//bf/ts+v/vd79bl5eXVNjXmVARTAACAJowcOfLwkCFDDhUUFAzOz8//esSIEQebW3v99dcfnDlz5pZx48YVLFq0aG1zambNmlUzYcKE/qlUqsvIkSMP5ubm/rlz586n3M57OmVlZTWlpaV9CwsLU1lZWfVz5879rOG1iRMn7h49evSgZ599dlNTta+99trGu+++u09ZWVmP2tra6Kabbtp9smD67//9v+996NCh9FtuueWyEELo2bPn0UWLFq1vbp+CKQAAwDFFRUVH161bt7rh+RtvvLGpqXFbt279pOHxqFGjDi1btmxNCCE89dRTx7fElpSU7C8pKak4cZ6T1ebk5NR99NFHa9u0aRMWLlx4yZIlS7JPtiX2VH02fq1bt251H3zwwYam5hg1atShOI6/tSrduP+BAwce/fjjj9c1VXui//W//lezwvfJCKYAAADngfXr17e99dZbL6uvrw9t2rSJX3jhhU1J93SuCKYAAADngaFDh35dWVn5rYsNbd++Pf2aa64pOnHs4sWL15x4Xui58NBDD3V/++23cxofu/HGG3eXlZW16Cq8JxJMAQAAzlPdu3eva8mVcVtbWVnZ9jMNoU1xH1MAAAASJZgCAACQKMEUAACARDnHFAAAOC89eduPR5zN+R6c986K048iCVZMAQAAzpJp06b1fOSRR7qdePyBBx7o+dZbb2Un0VNLPP7447nPPffcpd+lrrCwMDVw4MDUiBEjilasWJHZknorpkCzzf7poqRbAAA4Z+rr60McxyE9Pf2M53rmmWdqzkJLrW769Ok7v0vdXXfdtauhtry8vNMDDzzQ++OPP17X3HrB9K+coAAAAGfPmjVr2o4bN67g6quvPrBixYoOgwcPPlRVVZV15MiRtBtuuGHP008/XRNCCHl5eUNvvfXWXfPnz+9UW1sbzZs3b+P3v//9I43nevLJJ7u+/fbbXX73u9+tnzRpUp8f//jH++644449J6utqanJmDBhQr+9e/dmXH755YcWL17cccWKFZU9evSobarPH/3oRwXFxcUH//SnP3UYNGjQocmTJ3/56KOP5u3atStj7ty5G3/4wx8e2rFjR/rEiRP7fv755+2ysrLqX3zxxc1XXHHF4fz8/KGrVq2q6Nq1a10IIeTn5w9ZsmRJ1dNPP/03HTp0qHv00Ud3rF69ut1Pf/rT/N27d2dkZmbWv/TSS5tP/B0b5OTk1Dc8PnjwYHoURS363G3lBQAAaGTTpk2Zd9xxx67KysqK2bNnV3/66aeVVVVVq5csWZK9dOnSrIZxXbt2ra2oqKicPHnyzlmzZn1r++5jjz2W++6773aeP3/++g4dOsQnvkdTtQ8//HDP0aNHH6ioqKi8+eab92zbtq3tqfqsrq7OfPDBB7+oqqpavWHDhszy8vJLly9fXjVjxowtM2bM6BFCCNOnT+85bNiwQ2vXrq345S9/uXXSpEn90tPTw3XXXbe3vLy8cwghLFq06JJevXod7d2797cC8F133dXn+eef/3z16tWVTzzxxJZ77703/1T9zJw5M7d3795Dfv7zn/eaPXv256f7nBsTTAEAABrp0aPH0bFjx34VQgivvPJKTiqVGpRKpVLr1q3LXLVq1fFzJ0tLS/eEEEJxcfGh6urqdg3H582bd+mCBQs6vffeexuysrL+IpSerHbZsmUdJk2atDuEECZMmLC/Y8eOdafqMy8v7+vi4uLD6enpobCw8PCYMWP2p6WlheHDhx/asmVLw5zZd955564QQhg/fvyBvXv3ZuzatSu9tLR09+uvv54TQgjl5eU5JSUluxvPvW/fvrSVK1d2uOWWWy4bOHBgasqUKX2++OKLNqfq5x/+4R92VldXf/qLX/xiy89//vMepxp7IsEUAACgkfbt29eHEEJVVVXb5557rtuHH364du3atRVjxozZd+TIkeMZKjMzMw4hhIyMjLi2tvb43tWioqLDW7ZsaffZZ5+dNMg1VRvHTWbYk2rbtu3xgrS0tONzpqenh7q6upPOGUVRPHbs2K82b97crqamJuP999/vPHHixD2Nx9TV1YXs7OzaqqqqioafjRs3rm5OX3fffffuf/mXf+nckt/FOaYAAMB5Kenbu+zZsyc9KyurPicnp666ujpj8eLFnUaPHn3gdHWXX375ofvuu2/n+PHjByxYsGBd3759/9yc9ysuLj746quv5syYMWP7m2++2XH//v1nfNWlq6666sCcOXMufeKJJ7a988472V26dKltOB903Lhxe6dMmdJ7wIABh7t37/6t1dmcnJz6Xr16HX355Ze7TJ48eU99fX1YunRp1siRIw839T6ffPJJu6FDh34dQgjz5s3r1KdPn69b0qdgCgAA0ISRI0ceHjJkyKGCgoLB+fn5X48YMeJgc2uvv/76gzNnztwybty4gkWLFq1tTs2sWbNqJkyY0D+VSnUZOXLkwdzc3D937tz5lNt5T6esrKymtLS0b2FhYSorK6t+7ty5nzW8NnHixN2jR48e9Oyzz25qqva1117bePfdd/cpKyvrUVtbG9100027TxZMn3rqqb/5+OOPO2ZkZMSdOnWqbfw+zSGYAgAAHFNUVHR03bp1x7esvvHGG5uaGrd169ZPGh6PGjXq0LJly9aEEMJTTz11/LYwJSUl+0tKSipOnOdktTk5OXUfffTR2jZt2oSFCxdesmTJkuyTnaN6qj4bv9atW7e6Dz74YENTc4waNepQHMffWpVu3P/AgQOPNveWL3PmzKluzriTEUwBAADOA+vXr2976623XlZfXx/atGkTv/DCC5uS7ulcEUwBAADOA0OHDv26srKyovGx7du3p19zzTVFJ45dvHjxmhPPCz0XHnrooe5vv/12TuNjN9544+6ysrLtZzKvYAoAAJwv6uvr66O0tLSWXZ72Ata9e/e6qqqqitOPPDfKysq2f9cQWl9fH4UQ6pt6ze1iAACA88WnO3fu7HQswHABqa+vj3bu3NkphPBpU69bMQUAAM4LtbW1d23fvv2l7du3DwkW0S409SGET2tra+9q6kXBFAAAOC+MGDHiixDC+KT74NzzrxAAAAAkSjAFAAAgUYIpAAAAiRJMAQAASJRgCgAAQKIEUwAAABIlmAIAAJAowRQAAIBEnTaYRlHUO4qi30dRVBlF0eooin52LhoDAADg4pDRjDG1IYQH4zj+UxRF2SGEFVEU/UscxxWt3BsAAAAXgdOumMZxvC2O4z8de3wghFAZQshr7cYAAAC4OLToHNMoivqGEL4fQljaxGv3RFG0PIqi5Tt37jw73QEAAHDBa3YwjaKoQwjhjRDCA3Ec7z/x9TiOX4zj+Io4jq/Izc09mz0CAABwAWtWMI2iqE34JpSWx3H8Zuu2BAAAwMWkOVfljUII/yWEUBnH8VOt3xIAAAAXk+asmP6rEMLfhxDGRFH0v4/9/D+t3BcAAAAXidPeLiaO4/8ZQojOQS8AAABchFp0VV4AAAA42wRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgESdNphGUfRyFEVfRFH06bloCAAAgItLc1ZM54YQftTKfQAAAHCROm0wjeP4oxDC7nPQCwAAABch55gCAACQqIyzNVEURfeEEO4JIYT8/PyzNS0AQKub/dNFSbcAcFE7ayumcRy/GMfxFXEcX5Gbm3u2pgUAAOACZysvAAAAiWrO7WJeCyH8IYRQFEXRliiK7mz9tgAAALhYnPYc0ziO/+5cNAIAAMDFyVZeAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRgikAAACJEkwBAABIlGAKAABAogRTAAAAEiWYAgAAkCjBFAAAgEQJpgAAACRKMAUAACBRzQqmURT9KIqiNVEUrY+i6OHWbgoAAICLx2mDaRRF6SGE2SGEcSGEVAjh76IoSrV2YwAAAFwcmrNiWhxCWB/H8cY4jo+GEP5bCOHG1m0LAACAi0UUx/GpB0TRhBDCj+I4vuvY878PIVwZx/H9J4y7J4Rwz7GnRSGENWe/3Qte1xDCl0k3wUXD941zyfeNc8n3jXPNd+676RPHcW7STXB+yGjGmKiJY3+RZuM4fjGE8OIZd3QRi6JoeRzHVyTdBxcH3zfOJd83ziXfN8413zk4c83ZyrslhNC70fNeIYSa1mkHAACAi01zgun/F0IoiKKoXxRFbUMI/yaE8NvWbQsAAICLxWm38sZxXBtF0f0hhPkhhPQQwstxHK9u9c4uTrZCcy75vnEu+b5xLvm+ca75zsEZOu3FjwAAAKA1NWcrLwAAALQawRQAAIBECaYAAAAkSjBNUPSN26MoeuTY8/woioqT7osLVxRFfxtF0R3HHudGUdQv6Z64MEVR1C2Kov8SRdF7x56noii6M+m+uDBFUdQ+iqJ/jKLoV8eeF0RR9OOk++LC5W8cnH2CabKeDyGMDCH83bHnB0IIs5NrhwtZFEU/DyE8FEL4h2OH2oQQfp1cR1zg5oZvrube89jztSGEBxLrhgvdnBDC1+Gb/6aG8M092P8puXa4CMwN/sbBWSWYJuvKOI7vCyEcCSGEOI73hBDaJtsSF7CbQgjjQwhfhRBCHMc1IYTsRDviQtY1juN/DiHUh/DNrcdCCHXJtsQF7LI4jh8PIfw5hBDiOD4cQoiSbYkLnL9xcJYJpsn6cxRF6SGEOIRvtlaGY3/goBUcjb+5P1TD9+2ShPvhwvZVFEWXhv/7fbsqhLAv2Za4gB2Noigr/N/v22XhmxVUaC3+xsFZlpF0Axe5Z0MI/z2E0C2KohkhhAkhhP832Za4gP1zFEUvhBA6R1F0dwhhcgjhVwn3xIVrWgjhtyGEy6IoWvL/t3fnUZZV5fnHv08DMjaT4CxjQKIINIgiIKJGoq6AEQyKcYgoKHFFRcUx+aEkximSGI0KGlmIxihOEUwAmRrRAGFoBhUEQTRGQ5CpRWRo3t8f55QWbdPQzb13e099P2vVqjr7VFc/wOHceu/e+z3AxnT3OGkcDgdOAh6d5LPAbsCfNU2kofMeJ41YugkUtZJkG+AZdEuOTquq7zWOpAFL8kxgL7rr7eSq+kbjSBqwJKsCj6G73q6oqjsbR9KA9bNXu9Bdb+dU1fWNI2ngvMdJo+VS3vY2An5ZVR8BrrdLqsbs+3QF6ZuAbyVxj6nGIslawFuB11fVZcBmdknVuCQJ8Gxgp6o6EVjLLvcaJ+9x0uhZmDZkl1RNUr9894vAUf3QI4GvtkukgTsGuAO7pGoy7HKvSfMeJ42YhWlbdknVJL2Gbt/VLQBVdSXwkKaJNGR2SdUk2eVek+Y9ThoxC9O27JKqSbq9qu6YOej3xrjJXONil1RNkl3uNWne46QRszBta+kuqadil1SNz8IkbwfW7JsgHQ+c0DiThmvpLqmnAW9uG0kDNtPl/iF9l/uzgb9tG0kD5z1OGjG78jbSN2p4FLANdknVBPTX3CuZdb0BnyxvAhqxJPPoHptwGnZJ1Zj119suwA3Y5V4T4D1OGg8L04aSXFBVO7XOoeHrX0QvqaptW2fR3JDkrKrao3UOzQ1J/rOqnnzf3ymNhvc4afRcytvWOUl2bh1Cw1dVdwMXJ9mkdRbNGd9I8qYkj06y4cxH61AarFOS7NevDJEmwXucNGLOmDaU5LvA1sC1dJ15A1RVbdc0mAYpyenAzsB59J2gAapqn2ahNFhJrlnGcFXVFhMPo8FLshhYG7iLrjPvzOvpuk2DabC8x0mjZ2HaUJJNlzVeVddOOouGL8lTlzVeVQsnnUWSJEmazcK0oXtZ8rG4qu6ceBhJGqEk+y5j+Gbg0qq6btJ5NGxJdlzG8M3AtVV116TzaPi8x0mjZ2HaUJIfAo8GbqRbdrQ+8FPgOuCgqrqgXToNTb/Uben/4W8GzgfeWFVXTz6VhirJ14EnA2f0Q3sC59BtXziiqo5rFE0DlOQcYEfg0n7o8cDFwIOBV1fVKa2yaZi8x0mjZ/Ojtk4CnlNVG1XVg4FnA18A/hz4aNNkGqIjgcOAR9I9quhNdM/N/VfgUw1zaZjuBn6/qvarqv2Ax9I9fP5JwFuaJtMQ/RBYUFU79d3udwAuA/4AeH/LYBos73HSiFmYtvWEqjp55qB/R3ePqjoHWL1dLA3Us6rqqKpaXFW3VNXRdG+MfB7YoHU4Dc5mVfW/s46vA7auqhsAtyto1Lapqu/MHFTVd+kKVVeCaFy8x0kjtmrrAHPcDUneQjdjBfAC4MYkq9C9EyeN0t1J9ge+2B8/f9Y51/Rr1L6Z5ETg+P74+cBZSdYGbmoXSwN1RZKPcc/X0+8nWR2LBI2H9zhpxNxj2lCSjYDDgd37obOBI+j2/W1SVVe1yqbhSbIF8CG6PTFFtxfmUOAnwE5VdXbDeBqY/nmS+9Ld30J3f/tS+aKjMUiyJt02mNnX20fpHh2zVlX9omE8DZD3OGn0LEx/ByRZxxdNSUPTPxJrq6o6NclawCpVtbh1Lg1TX5xuUlVXtM6iucF7nDRa7jFtKMmuSb4LfLc/3j6JTY80Fkm2TnJaksv64+2S/GXrXBqmJAfRLRs/qh96JPDVdok0ZEn2ARbRNRUkyQ5JvtY2lYbMe5w0ehambf098IfAzwGq6mJgj6aJNGSfAN5Gv9+qqi4BXtg0kYbsNcBuwC0AVXUl8JCmiTRkhwNPpN/bV1WLgM1aBtLgeY+TRszCtLGq+vFSQ0uaBNFcsFZVnbfUmA+e17jcXlV3zBwkWRWbbGl87qqqm1uH0JziPU4aMQvTtn6cZFegkjwoyZuA77UOpcG6PsmW9C+cSZ4P/LRtJA3YwiRvB9ZM8ky6zpUnNM6k4bosyYuAVZJsleTDwLdbh9KgeY+TRszmRw31XXk/RPcA8ACnAK+rqp83DaZB6rvyHg3sCtwIXAO8uKp+2DKXhinJPOAVwF5097eTgU/asVLj0DeeeQf3vN7+uqp+1TSYBst7nDR6FqbSHNM/Y22enQMlSZL0u8LCtIF+idG9/ouvqtdOMI4GLskblne+qo6cVBYNX5JLWf79bbsJxtHAJTmB5V9v+0wwjuYA73HS+KzaOsAcdX7/eTfgscDn++M/AS5oXTOmGQAAG0lJREFUkkhDNr///BhgZ2DmEQp7A2c1SaQh+6P+82v6z8f1n/8U+OXk42jg/q7/vC/wMOAz/fEBwA9bBNLgeY+TxsQZ04aSnAHsVVV39serAadU1dPaJtMQJTkF2G9mCW+S+cDxVfWstsk0REm+VVW73deYNApJzqqqPe5rTBoV73HS6NmVt61H8JvZLIB1+jFpHDYB7ph1fAc+50/js3aS3WcO+g7kazfMo2HbuG/wBkCSzYGNG+bR8HmPk0bMpbxtvRe4qJ85BXgq8M52cTRwxwHnJfkK3f6Y5wHHto2kAXsF8Kkk69FdbzcDB7aNpAE7FDgzydX98WbAwe3iaA7wHieNmEt5G0vyMOBJ/eG5VfWzlnk0bEl2BJ7SH55VVRe1zKPhS7Iu3WvNza2zaNiSrA5s0x9eXlW3t8yjucF7nDQ6FqaSJEmSpKbcYypJkiRJasrCVJIkSZLUlM2PGkkyD7ikqrZtnUVzR5JNga2q6tQkawKrzjw+RhqFJPsu73xVfXlSWTR8/b75e1VVF04qi+aWJGsBbwQ2qaqDkmwFPKaqTmwcTZpaFqaNVNXdSS5OsklV/ah1Hg1fkoPoulRuCGwJPAr4OPCMlrk0OHsv51wBFqYapQ8u51wBT59UEM05xwAXAE/uj/8bOB6wMJVWks2PGkpyOrAzcB5w68x4Ve3TLJQGK8ki4Il03Z8X9GOXVtXj2yaTJGm6JDm/qp6Q5KJZr6kXV9X2rbNJ08oZ07be1TqA5pTbq+qOJAAkWZVuRkEauf7ZfocDe/RDC4EjfKSCxiHJasAh/OZ6OxM4qqrubBZKQ3dHvyWmAJJsCfiIIukBsPlRQ1W1ELgcmN9/fK8fk8ZhYZK3A2smeSbdkqMTGmfScH0KWAzs33/cQrf0TRqHjwE7AR/tP3bqx6RxeSdwEvDoJJ8FTgPe0jSRNOVcyttQkv2BD9C9sxvgKcBhVfXFlrk0TH3DrVcAe9FdbydX1SfaptJQJVlUVTvc15g0CstaQumySo1bkgcDu9C9pp5TVdc3jiRNNZfytvUOYOequg4gycbAqYCFqcbhL6rqQ8Cvi9Ekr+vHpFG7LcnuVXU2QJLdgNsaZ9JwLUmyZVX9ACDJFsCSxpk0YElOq6pnAF9fxpiklWBh2ta8maK093NcXq3xeRmwdBH6Z8sYk0bhEODYfq9pgBvorkFpHA4DzkhyNd31tinw8raRNERJ1gDWAjZKsgHd9QawLvCIZsGkAbAwbeukJCcDn+uPXwD8e8M8GqAkBwAvAjZP8rVZp+bTvRkijVxVLQK2T7Juf3xL40gasKo6beY5knSFwuVVZSMajcOrgNfTFaEX8JvC9Bbgn1qFkobAPaaNJdkP2I3uxnZWVX2lcSQNTJJNgc2B9wBvnXVqMXBJVd3VJJgGza68miS78mrSkvxFVX24dQ5pSCxMJUkjl+RLwGXAsf3QS4Dtq2rfdqk0VEk+CazGPa+3JVX1ynapNHRJtgUeC6wxM1ZVn26XSJpuFqYNJFnMsp8fGaCqat0JR9IckGQX4MPA7wMPAlYBbvV60zjYlVeTZFdeTVqSw4E96QrTfweeDZxdVc9vmUuaZjbaaaCq5lfVusv4mG+RoDH6CHAAcCWwJvBKukJVGofbkuw+c2BXXo3ZkiRbzhzYlVcT8HzgGcDPqurlwPbA6m0jSdPN5keN9b+4bVVVxyTZCJhfVde0zqVhqqqrkqxSVUuAY5J8u3UmDdargU8v1ZX3z5om0pDZlVeTdltV3Z3krr7J23XAFq1DSdPMwrShfhnIE+i6CB5Dt7zyM3TNkKRR+2WSBwGLkrwf+CmwduNMGqiquhi78mpC7MqrBs5Psj7ds8EvAH4BnNc2kjTd3GPaUJJFwALgwqpa0I9dUlXbtU2mIeq7815H1yDkUGA94KNVdVXTYBqkJKsD+wGbMetN0Ko6olUmDVuSXfnt681GNBq7JJsB61bVJY2jSFPNGdO27qiqSlIASZy90thU1bX9l7cB72qZRXPCvwE3080kOHOlsUpyHLAlsIjf7C0twMJUI5Vkm6q6PMmOyzi3Y1Vd2CKXNAQWpm19IclRwPpJDgIOpFsSIo1ckmtYRjfoqnJPjMbhUVX1rNYhNGc8AXhsuQxM4/cG4GDgg8s4V8DTJxtHGg4L04aq6u+SPBO4hW5fzP+rqm80jqXhesKsr9cA/gTYsFEWDd+3kzy+qi5tHURzwmXAw+j2zktjU1UH95+f1jqLNDTuMZXmsCRnV9Xu9/2d0v2T5FK6WYNVga2Aq+mW8s48p9k99BqZJCfQXW/zgR3oms/8eul4Ve3TKJoGLslrgM9W1U398QbAAVX10bbJpOllYdpQkn2B9wEPofulbeYXN59lqpFbaj/MPLoZ1EN8AL1GqW+yda9m7XWWHrAkT13e+apaOKksmluSLKqqHZYau2immaWkFedS3rbeD+xdVd9rHURzwuz9MHcBPwT2bxNFQzVTeCbZBfhOVS3uj+cDjwUsTDUyM4Vnks2Bn1bVr/rjNYGHtsymwZuXJDP7mpOsQvfYP0kryRnThpJ8q6p8ZqmkwUlyEbDjrF/a5gHnV9VvdbKUHqgk5wO7VtUd/fGDgG9V1c5tk2moknyA7vFEH6dbTv5q4MdV9caWuaRp5oxpA/0SXugezvx54Kvcc0/Ml5sE0yAlecPyzlfVkZPKojnl1zMJAFV1dxJfczQuq84UpQBVdUdfnErj8hbgVcAhdFuxTgE+2TSRNOX8JaGNvWd9/Utgr1nHBViYapTm958fA+wMfK0/3hs4q0kizQVXJ3kt8LH++M/pGiFJ4/B/Sfapqq8BJHkucH3jTBqw/s22fwbOpvvd7YqqWnIff0zScriUV5ojkpwC7LfUnr/jfdakxiHJQ4B/pHumXwGnAa+vquuaBtMgJdkS+CzwCLrZqx8DL62qq5oG02Al2RM4lq5fQ4BHAy+rKt/wlVaShWlDSY4FXrdUq/EPVtWBbZNpiJJcDmxfVbf3x6sDF1fVNm2TSdJoJFmH7nebxa2zaNiSXAC8qKqu6I+3Bj5XVTu1TSZNr3mtA8xx280UpQBVdSNgm3GNy3HAeUnemeRw4Fzg040zaaCSvD/JuklWS3JakuuTvLh1Lg1TktclWRe4Ffj7JBcm2eu+/pz0AKw2U5QCVNX3gdUa5pGmnoVpW/P6WVIAkmyI+341JlX1buBA4EbgJuDlVfW3bVNpwPaqqluAPwL+G9gaOKxtJA3Ygf31thfds8FfDry3bSQN3PlJ/jnJnv3HJ4ELWoeSpplFUFsfBL6d5Iv98Z8A726YRwNXVRck+TGwBkCSTarqR41jaZhmZg6eQ7e87YYkLfNo2GYurucAx1TVxfGC03gdArwGeC3d9XcW8NGmiaQp5x7TxpI8Dnga3U3ttKr6buNIGqgk+9C9GfII4DpgE+Dyqnpc02AapCTvBf4YuA14IrA+cGJVPalpMA1SkmOARwKbA9sDqwBnut9Pk9CveHtUVV3SOos0zSxMfwf03SvXmDl2BkvjkORiug6pp1bVgiRPAw6oqoMbR9NA9VsVbqmqJUnWBuZX1c9a59LwJJkH7ABcXVU3JXkw8EgLBY1LkjOBfehWHy4C/g9YWFXLfXa4pHvnHtOGkuyT5ErgGmAhXcvx/2gaSkN2Z1X9nG5v87yqOoPuFzlpLKrqxpnn+lXVrRalGpequruqLpxpKFhVP7co1Zit1+9r3pdu+fhOwB80ziRNNQvTtv4a2AX4flVtDjwD+FbbSBqwm/pHKZwFfDbJh4C7GmeSJGkarZrk4cD+wImtw0hDYGHaljNYmqTnAr8EDgVOAn4A7N00kSRJ0+kI4GTgqqr6ryRbAFc2ziRNNfeYNpTkVLrmIO8BNqJrSLNzVe3aNJgGJ8kqwMlV5TIjTUySRwKbMqsDfFWd1S6Rhqy/zz2Ue15v9myQpClhYdpQ3wzkNrqZ6z8F1gM+28+iSiOV5GvAS6rq5tZZNHxJ3ge8APgusKQfrqrap10qDVWSvwAOB/4XuLsfrqrarl0qDVmS9wN/Q/d73El03aBfX1WfaRpMmmIWpr8jkmwE/Lz8D6IxSfIFuj3N3wBunRmvqtc2C6XBSnIFsF1V3d46i4YvyVXAk3xjV5OSZFFV7ZDkeXSr3w4Fzqiq7RtHk6bWqvf9LRq1JLsA7wVuoGuAdBzdUt55SV5aVSe1zKfB+nr/IU3C1cBqgIWpJuHHgKtBNEmr9Z+fA3yuqm5I0jKPNPUsTNv4CPB2uqW7pwPPrqpzkmwDfI5uSYg0UlV1bOsMGr4kHwaKrtHWoiSnMas4dYZeo5Rk5pmRVwNnJvk697zejmwSTHPBCUkup1vK++dJNgZ+1TiTNNVcytvAzPKP/uvvVdXvzzp3UVUtaJdOQ5PkucCjquqf+uNzgY3702+uqi82C6fBSfKy5Z33DRKNUpLDl3e+qt41qSyae5JsANxSVUuSrAU8uKp+3DqXNK2cMW3j7llf37bUOd8p0Ki9GXjhrOPVgZ2BtYFjAAtTjYyFpybJwlMtVdWN6TwdeBHdI9ge2jiWNLUsTNvYPsktQIA1+6/pj9doF0sD9aCl3sE9u28Q8vO+M7Q0ckku5bffaLsZOB/4G5vUaJSSnMC9X29HVZVLLDVSSZ5EV4w+D9gQeA1wWNNQ0pRzKa80cEmuqqrfu5dzP6iqLSedScPXP0phCfAv/dAL6d58uxnYvar2bpVNw5PkQ3RbFD7XD70A+BmwJrBuVb2kVTYNS5J3A/sDP6K73r4CnF9VmzcNJg2AM6bS8J2b5KCq+sTswSSvAs5rlEnDt1tV7Tbr+NIk36qq3ZK8uFkqDdWCqtpj1vEJSc6qqj2SfKdZKg3RwcAVwMeAE6vqV0mc5ZFGwMJUGr5Dga8meRFwYT+2E91e0z9ulkpDt06SJ1XVuQBJngis05+7q10sDdTGSTapqh8BJNmE7jFsAHe0i6UBehiwF3AA8A9JzqDblrVqVXlvkx4AC1Np4KrqOmDXvjnD4/rhr1fV6Q1jafheCXwqyTp0S3hvAV7Z72t+T9NkGqI3Amcn+QHd9bY53SM81gZsyKWRqaolwH8A/5FkDeCPgLWAnyQ5rape1DSgNMXcYypJGpsk69G91tzUOouGLcnqwDZ0henlNjzSJCVZF3iencmllWdhKkkamSQvrqrPJHnDss5X1ZGTzqThSvL0qjo9yb7LOl9VX550JknSynEpryRplGYeQTS/aQrNFU8FTqd7fuTSCrAwlaQp4YypJEmSdD8lmQfsUlXfbp1FGhILU0nSyCT5x+Wdr6rXTiqL5o5+f+l+wGbMWg1WVUe0yqRhS/KfVfXk1jmkIXEpryRplC6Y9fW7gMNbBdGc8m/AzXTX3+2Ns2huOCXJfsCXy1keaSScMZUkjUWSi6pqQescGr4kl1XVtq1zaO5IsphuT/0S4Da6btBVVes2DSZNMWdMJUnj4jufmpRvJ3l8VV3aOojmhqqywZs0YhamkiRpKiW5lO4NkFWBlye5mm4p78zs1XYt82nYkuwD7NEfnllVJ7bMI007l/JKkkamX94288KyFvDLmVO4zE0jlmTT5Z2vqmsnlUVzS5L3AjsDn+2HDgAuqKq3tkslTTcLU0mSJGkFJLkE2KGq7u6PVwEucpZeWnnzWgeQJEmSptD6s75er1kKaSDcYypJkiStmPcAFyU5g26rwh7A29pGkqabS3klSZKkFZTk4XT7TAOcW1U/axxJmmoWppIkaaol2Rd4H/AQuiLBZluSNGUsTCVJ0lRLchWwd1V9r3UWSdLKsfmRJEmadv9rUSpJ080ZU0mSNNWSfAh4GPBV4PaZ8ar6crNQGrwkuwNbVdUxSTYG1qmqa1rnkqaVhakkSZpqSY5ZxnBV1YETD6M5IcnhwBOAx1TV1kkeARxfVbs1jiZNLQtTSZIkaQUkWQQsAC6sqgX92CVVtV3bZNL08jmmkiRpqiVZA3gF8DhgjZlxZ0w1RndUVSUpgCRrtw4kTTubH0mSpGl3HN0e0z8EFgKPAhY3TaSh+0KSo4D1kxwEnAp8onEmaaq5lFeSJE21JBdV1YKZpZRJVgNOrqqnt86m4UryTGAvuufmnlxV32gcSZpqLuWVJEnT7s7+801JtgV+BmzWLo7mgr4QtRiVRsTCVJIkTbujk2wA/BXwNWAd4P+1jaQhS7IYWHrZ4c3A+cAbq+rqyaeSpptLeSVJkqQVkORdwP8A/0K3lPeFdPucrwAOqao926WTppOFqSRJmmpJVgf2o1u+++vVYFV1RKtMGrYk51bVk5YaO6eqdklycVVt3yqbNK3syitJkqbdvwHPBe4Cbp31IY3L3Un2TzKv/9h/1jlnfaSV4IypJEmaakkuq6ptW+fQ3JFkC+BDwJPpCtFzgEOBnwA7VdXZDeNJU8nCVJIkTbUkRwMfrqpLW2eRJK0cC1NJkjSVklxKN1u1KrAVcDVwO10zmqqq7RrG04Al2Rr4GPDQqto2yXbAPlX1N42jSVPLwlSSJE2lJJsu73xVXTupLJpbkiwEDgOOqqoF/ZhLyqUHwOeYSpKkqTRTeCY5rqpeMvtckuOAlyzzD0oP3FpVdV6S2WN3tQojDYFdeSVJ0rR73OyDJKsAOzXKornh+iRb0nfgTfJ84KdtI0nTzRlTSZI0lZK8DXg7sGaSW2aGgTuAo5sF01zwGrprbJskPwGuAV7cNpI03dxjKkmSplqS91TV21rn0NyTZG1gXlUtbp1FmnYWppIkSdL9kOQNyztfVUdOKos0NC7llSRJku6f+a0DSEPljKkkSZIkqSlnTCVJ0lTru6P+d1XdnmRPYDvg01V1U9tkGpok/7i881X12kllkYbGwlSSJE27LwFPSPJ7wD8DXwP+BXhO01QaogtaB5CGyqW8kiRpqiW5sKp2THIY8Kuq+nCSi6pqQetsGrYk84Gqql+0ziJNu3mtA0iSJD1AdyY5AHgZcGI/tlrDPBq4JNsmuQi4DPhukguSPK51LmmaWZhKkqRp93LgycC7q+qaJJsDn2mcScN2NPCGqtq0qjYB3gh8onEmaaq5lFeSJA1Gkg2AR1fVJa2zaLiSXFxV29/XmKT7zxlTSZI01ZKcmWTdJBsCFwPHJDmydS4N2tVJ/irJZv3HXwLXtA4lTTMLU0mSNO3Wq6pbgH2BY6pqJ+APGmfSsB0IbAx8uf/YiG5JuaSV5ONiJEnStFs1ycOB/YF3tA6j4auqGwGfWSqNkDOmkiRp2h0BnAz8oKr+K8kWwJWNM2nAknwjyfqzjjdIcnLLTNK0s/mRJEmStAKW9Zxcn50rPTDOmEqSpKmWZOskpyW5rD/erm9GI43L3Uk2mTlIsingbI/0ADhjKkmSplqShcBhwFEzM1ZJLquqbdsm01AleRbds0wX9kN7AAdXlct5pZVk8yNJkjTt1qqq85LMHrurVRgNX1WdlGRHYBcgwKFVdX3jWNJUszCVJEnT7vokW9IvpUzyfOCnbSNp6PpC9MTWOaShcCmvJEmaan0X3qOBXYEbgWuAP62qa5sGkyTdbxamkiRpEJKsDcyrqsVJXl9V/9A6kyTp/rEwlSRJg5PkR1W1yX1/p7RykuwObFVVxyTZGFinqq5pnUuaVj4uRpIkDVHu+1uklZPkcOAtwNv6odWAz7RLJE0/C1NJkjRELgnTOD0P2Ae4FaCq/geY3zSRNOXsyitJkqZSksUsuwANsOaE42huuaOqKslMJ+i1WweSpp2FqSRJmkpV5QyVWvlCkqOA9ZMcBBwIfKJxJmmq2fxIkiRJWkFJngnsRTdDf3JVfaNxJGmqWZhKkiRJKyHJusxagVhVNzSMI001l/JKkiRJKyDJq4AjgNuAu+lmTQvYomUuaZo5YypJkiStgCRXAk+uqutbZ5GGwsfFSJIkSSvmB8AvW4eQhsQZU0mSJGkFJFkAHAOcC9w+M15Vr20WSppy7jGVJEmSVsxRwOnApXR7TCU9QBamkiRJ0oq5q6re0DqENCTuMZUkSZJWzBlJDk7y8CQbzny0DiVNM/eYSpIkSSsgyTXLGK6q8nEx0kqyMJUkSZIkNeUeU0mSJGkFJFkNOATYox86Eziqqu5sFkqacs6YSpIkSSsgySeB1YBj+6GXAEuq6pXtUknTzcJUkiRJWgFJLq6q7e9rTNL9Z1deSZIkacUsSbLlzEGSLYAlDfNIU889ppIkSdKKOYzukTFXAwE2BV7eNpI03VzKK0mSJK2gJKsDj6ErTC+vqtsbR5Kmmkt5JUmSpPshyc5JHgbQF6I7AEcAH0iyYdNw0pSzMJUkSZLun6OAOwCS7AG8F/g0cDNwdMNc0tRzj6kkSZJ0/6xSVTf0X78AOLqqvgR8KcmihrmkqeeMqSRJknT/rJJkZmLnGcDps8454SM9AP4PJEmSJN0/nwMWJrkeuA34JkCS36NbzitpJdmVV5IkSbqfkuwCPBw4papu7ce2BtapqgubhpOmmIWpJEmSJKkp95hKkiRJkpqyMJUkSZIkNWVhKkkiyZIki2Z9vHUZ37NnkhNH/PfumWTXWcevTvLSUf4dkiTpd59deSVJALdV1Q4N/t49gV8A3waoqo83yCBJkhpzxlSSdK+SPCvJ5UnOBvadNf7OJG+adXxZks36r1+a5JIkFyc5rh/bO8m5SS5KcmqSh/bf/2rg0H6W9imzf26SHZKc0/+sryTZoB8/M8n7kpyX5PtJnjKhfx2SJGlMLEwlSQBrLrWU9wVJ1gA+AewNPAV42H39kCSPA94BPL2qtgde1586G9ilqhYA/wq8uap+CHwc+Puq2qGqvrnUj/s08Jaq2g64FDh81rlVq+qJwOuXGpckSVPIpbySJFjGUt4kOwDXVNWV/fFngIPv4+c8HfhiVV0PUFU39OOPAj6f5OHAg4BrlvdDkqwHrF9VC/uhY4HjZ33Ll/vPFwCb3UcmSZL0O84ZU0nS8tzbw67v4p6vIWv0n3Mvf+bDwEeq6vHAq2Z9/8q6vf+8BN9klSRp6lmYSpLuzeXA5km27I8PmHXuh8COAEl2BDbvx08D9k/y4P7chv34esBP+q9fNuvnLAbmL/0XV9XNwI2z9o++BFi49PdJkqRhsDCVJMFv7zF9b1X9im7p7tf75kfXzvr+LwEbJlkEHAJ8H6CqvgO8G1iY5GLgyP773wkcn+SbwPWzfs4JwPNmmh8tlellwAeSXALsABwxyn9gSZL0uyNV97ZKS5IkSZKk8XPGVJIkSZLUlIWpJEmSJKkpC1NJkiRJUlMWppIkSZKkpixMJUmSJElNWZhKkiRJkpqyMJUkSZIkNWVhKkmSJElq6v8Dl2KSs4kmRUYAAAAASUVORK5CYII=
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
<h3 id="Ranking"><span style="color: blue;">Ranking</span><a class="anchor-link" href="#Ranking">&#182;</a></h3><h4 id="For-all-education-level,-the-second-movie-is-the-highest-ranked.">For all education level, the second movie is the highest-ranked.<a class="anchor-link" href="#For-all-education-level,-the-second-movie-is-the-highest-ranked.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[142]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Porcentage of fans per education level</span>

<span class="n">ax</span> <span class="o">=</span> <span class="p">(</span>
        <span class="p">(</span><span class="n">fans</span><span class="p">[</span><span class="s1">&#39;Education&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span> <span class="o">/</span> <span class="n">star_wars</span><span class="p">[</span><span class="s1">&#39;Education&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span> <span class="o">*</span> <span class="mi">100</span><span class="p">)</span>
        <span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
<span class="p">)</span>

<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">{}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">(),</span> <span class="mi">2</span><span class="p">)),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span> <span class="o">+</span> <span class="mf">0.1</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span> <span class="o">+</span> <span class="mf">1.1</span><span class="p">),</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">16</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;red&#39;</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span>

<span class="n">plt</span><span class="o">.</span><span class="n">tight_layout</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA+gAAALICAYAAADseNpmAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOzde9zmc50/8NenmbJymjAOSzWIEkvZyaCWQqh+nWzZROlAh9kOWrbYakkStsPqnE1IKeRnsySh2K1FjUVCmX6FLbZRDhkp4fP743Pfe8/JzD1j5r4+c9/P5+NxPa7r+7m+1/d6d/e4XPO6PqdSaw0AAAAwWI8ZdAEAAACAgA4AAABdENABAACgAwI6AAAAdEBABwAAgA5MHss3W3fddeu0adPG8i0BAACgK1ddddVvaq1TF2wf04A+bdq0zJo1ayzfEgAAALpSSrllUe2GuAMAAEAHBHQAAADogIAODNallyalLHybMmXknJtvXvQ5pSR337346990U/LOdybbbJOsvnqy4YbJS16SXHvt6OoYvl1xxci5p5+ebLZZsvbayUEHJfffP/+1brmlvdeVVz6KPwwAABPNmM5BB3hEn/hE8qxnjRxPXsR/ng4/vIXrea2xxuKv++1vJ9/9bnLAAcl227VAf/zxyYwZyfe/n/zlX7bzttsuufzyhV//xjcmd945UttNN7VrHXVUstVWycyZyXHHJUceOfKad7wj2W+/9h4AADBKAjrQhy23THbYYfHnbLrpks9Z0Ktelfzt37Ze8GG77ppMm5accELypS+1tjXXXPjat9yS3HhjcsghyaRJre2ii5LNN28/FiTJDTck55wzEtDPO68F/Z/8ZOnqBABgwhPQgfFt3XUXbltrrWSLLZJf/Wrxrz3ttKTW1mM+7IEHklVXHTlebbXkD39oj++/v/WeH398G/4OAABLwRx0oA/77dd6qddZJ3n1q5Nbb134nMMPb0Pf11qrDXW/7rple68770x+/OPWa784X/pSG/q+9dYjbTNmtPnrF12U3HZbcvLJIz3vxxyTbLTR/IEeAABGSQ86MFhrrdWGkO+ySxtmfvXVLejuuGN7vN56ySqrJG9+c7LHHsnUqW34+DHHJDvtlPzgB0sO2gt6+9tbz/jBBz/yOZdfnsye3YbBz2unndqic3vs0Y633bYNb589O/n4x9ticvMOpwcAgFEqtdYxe7Pp06fXWbNmjdn7ASup//qvZPvtk8MOS44+etHn/Pd/t0XaXvKS5MtfHv21P/zh5B/+ITnppOQNb3jk897yluSLX2y95IsaJv+b3yT33NPmxZeS7LlnWyn+n/4pOeOMFtrnzEl23z357GcNeQcA4H+VUq6qtU5fsN0Qd6A/223X5oj/8IePfM4Tn5g85zmLP2dBn/tcC+dHH734cP7HPyZnnpm86EWLDudJa99ssxbOzzqrLRZ3xBFtUbnXvjb55Cfb9nC/+13rcQcAgCUQ0IE+1brkoeKjOWfYaae1LdEOOSR573sXf+655yZ33TW6ueRz5ybvelcbCr/66snFF7c567vv3raAmzkz+da3RlcjAAATmoAO9GfWrLbf+OL2Eb/11raP+Wj2Gj/nnOT1r08OPDD5yEeWfP6pp7bF6l70oiWfe+SRbWj73nuPtN1338jjuXPbDwkAALAEFokDBmu//ZJNNmnD2qdMaQvDffjDbTX0t7+9nXPIIcnDD7eF46ZOTX7603bOYx7ThqzPa/Lk1vN90knt+N//Pdl33xaiX/e6tojbsFVWSZ75zPlfP2dOcuGFyVvfmjz2sYuv/frrkxNPTK65ZqRt113b4nNHHdXm0R999MiCcgAAsBgCOjBYW2+dfPWrbc7273+fbLBB643+wAdG5n9vtVVbaO2UU5J7723tu+7a5nw/9anzX++hh9pt2He+0+aUX3118uxnz3/uk5/c5onP6ytfSR58cHTD22fOTA49tC0UN2yrrVqdRx7Zeut3223hleABAGARrOIOAAAAY8gq7gAAANAxAR0AAAA6IKAP2qWXtm2iFrxNmTJyzlVXJXvt1RbN+rM/a3N0X/jC5PLLR/ce06Yt+j3+9V/nP+/3v29zerfYIll11bbP9Gtfu/Ac3dNPb/s/r712ctBByf33z//8Lbe07aauvHIp/xgAAAATl0XievGJTyTPetbI8eR5/q+5++7kKU9pK1BvuGFbZfrjH0922SX53vfaStFLsueebdGqeS24uNaBB7bQ/oEPJNOnt22sjjiiLXJ17bUtdN90U1s866ij2mJYM2cmxx03/7Xf8Y62Mvdotr8CAAAgiYDejy23THbYYdHP7bZbu81rr73aStannTa6gL7uuo98/aT1gp95ZvLudyd///cj7euvn7zgBW2/6T33TC66KNl88+Tww9vzN9zQ9pgeDujnndd69n/ykyXXBAAAwP8yxH1ltdpqbQ/nJe3TPFoPPti2plpzzfnbh4faP/xwu3/ggTb8fd46/vCH9vj++1vv+fHHt+HvAAAAjJqA3ov99ksmTUrWWSd59avb8PIFPfxw8qc/tefe9rbWduCBo7v+v/1b8vjHt1C/ww4Lzz9fY43kNa9pQ+2/+91k7tzk+utbb/q224704M+Y0Ya7X3RRctttycknj/TMH3NMmyc/mv2jAQAAmI8h7oO21lrJIYe0+eRrrplcfXULujvu2B6vt97Iufvsk5x9dnu83nrJN7+ZPP3pS36PF7+4zW/fZJPk179OPvWp5OUvb8Pj999/5LyTT2494LvuOtI2Y0YL4497XDveaafkne9M9tijHW+7bRvePnt2mxd/xRVtAToAAACWSqm1jtmbTZ8+vc6aNWvM3m+l9V//1eaVH3ZYcvTRI+0//3ny298m//3fyac/3VZ3v/jitqDb0njoodbr/T//06417PDDk898JvnHf2yB/tZb24Jxa62VXHZZG84+7De/Se65J9l00xbI99wz2Wab5J/+KTnjjBba58xJdt89+exnDXkfR6Yddv6gS5jQbj72RYMuAQCAR6mUclWtdaEgZ4h7j7bbrm119sMfzt++6aYtOO+9d3LBBa0X/X3vW/rrT5qUvPKVyS9/mdx+e2u7/vrk2GOTj32s9ejvvHPrXf/mN9sPAV/4wvzXWHfdttVaKclZZ7XF4o44IrnxxrY12yc/2bZn+93vWo87AAAAiyWg96rWxQ8Vf9zjWo/1z3627NdPRt7juuva/bxbvSVtxfYpU1rwXpS5c5N3vSs54YS2DdvFFydbb916ztdYo23D9q1vLVuNAAAAE4iA3qNZs9p+44vbR/z3v2/nbbbZ0l//wQdbr/eTnpRssEFrG77/wQ/mP/emm9o+7BtttOhrHXlk+6Fg771H2u67b+Tx3LkjPwYAAADwiCwSN2j77dcWb9tuu9ZTffXVyYc/3ALx29/eznnzm9sc7unT29DyW25pC73dfntb6G1ekye3VdRPOqkdf/WryTe+kbzwhckTn9gWiRuev/7Vr4687q/+qi34dsghyV13tfe69dY2B36ttRa9Mvv11ycnnphcc81I2667JgcfnBx1VJtHf/TRIwvKAQAA8IgE9EHbeusWlD/5ydYrvsEGrTf6Ax9oYTxpPelf+EILw/fd18L7jBkthP/FX8x/vYceardhm2zSFmv7+79P7ryzbbX2rGe1Yed77jly3qRJySWXtBXkTzyxLRS37rpt1fajjmq97QuaOTM59NA2N37YVlslp5zSetY/8pG2PdsJJyyvvxYAAMC4ZRV3YKlYxX2wrOIOALDys4o7AABAjy69tC3evOBtypSRcy65pO2ytNlmyaqrtvu3vrWNlh2Nj30sefGLkw03bNc+8shFn/f61ydbbpmsuWZbBHrbbdto33lH6SbJ6ae3GtZeOznooOT+++d//pZb2uuvvHK0fwViiDsAAEAfPvGJ+XdVmjxPXPvc59oCzO97X5tiOnt22+b4wguTH/2oheHF+Zd/aaH7ZS9r13ok99/f1sIa3lL5wgvbtsk/+9nI1NWbbmprVB11VJviOnNmctxx84f+d7yjrbe1uIWvWYiADgAA0IMtt0x22GHRz33mM8nUqSPHu+ySbLFFuz/zzOQNb1j8ta+/PnnMY9qOTosL6F/72vzHe+yR3HZb8sUvjgT0iy5q2zEffng7vuGG5JxzRgL6eecll1+e/OQni6+JhRjiDgAA0Lt5w/mw4d72X/1qya9/zKOIfuusM39v/gMPtGH2w1ZbLfnDH9rj++9vvefHH9+Gv7NUBHQAAIAe7Ldf211pnXWSV7+6bXu8OJdd1u633HL51lFr62m/++7k7LOTU09N/u7vRp6fMSO59trWk37bbcnJJ4/0/B9zTNt1alHbNLNEhrgDAAAM0lprJYcc0oarr7lmcvXVLejuuGN7vN56C7/m3nuTgw9u4fxlL1u+9Zx/fltQLmnz0A87LHn/+0ee32mnNi99jz3a8bbbtuHts2cnH/94csUV7XUsNQEdAABgkJ75zHYbtssuyc47J9tv3xaOO/ro+c9/8MFk333b0Pbvf3/+4efLw1/9VfLDHyb33NNWj//IR1rg/tCHRs756EfbHPR77mmL1pWS7LlnW1l+662TM85ooX3OnGT33ZPPftaQ91EQ0AEAAHqz3XZtEbgf/nD+9ocfbsPHL7649XRvs83yf++11kqmD23RvdtuyeMel3zwg2219o02Gjlv3XXbLUnOOqstFnf22cmNNyavfW2rb8aMZJ99Wo/7aact/1rHGQF9KUw77PxBlzDh3XzsiwZdAgAAjI1aFx4q/pa3tN7pr3+9heexMH16+2HgF7+YP6APmzs3ede7Wm//6qu3Hw+23rr1nCct2C9plXmSWCQOAACgP7Nmtf3G591H/JBDki98oS3KtrznnS/OZZe1Hwo23XTRzx95ZOvJ33vvkbb77ht5PHdu+7GBJdKDDgAAMEj77Zdsskkb1j5lSlsY7sMfbr3Vb397O+e445KPfaz1RG++eVuIbdjUqclmm40cT57chsGfdNJI26xZyc03t57wpA1H//rX2+MXvjB5/OPbkPSTT24LxD3pSW0hugsuSE48MXnzm5M///OFa7/++vb8NdeMtO26a1vA7qij2jz6o48eWVCOxRLQAQAABmnrrZOvfjX55CeT3/8+2WCD1hv9gQ+MzPG+4IJ2/8Uvttu8DjggOeWUkeOHHmq3eX3qU227tGFnndVuSRu6Pm1aC/kPP5y8731tcbcpU9qPAV/6UluUblFmzkwOPXT+3vWttmr1HHlkW2But92SE05Yur/JBFXqGA41mD59ep01a9aYvd/yZg764JmDPng+B4PlMwAAsPIrpVxVa52+YLs56AAAANABAR0AAAA6IKADAABABwR0AAAA6ICADgAAAB0Q0AEAAKADAjoAAAB0QEAHAACADkwedAEAAAArk2mHnT/oEia0m4990aBLWGH0oAMAAEAHBHQAAADogIAOAAAAHRDQAQAAoAMCOgAAAHRAQAcAAIAOCOgAAADQAQEdAAAAOiCgAwAAQAcEdAAAAOiAgA4AAAAdENABAACgAwI6AAAAdEBABwAAgA4I6AAAANCByaM5qZRyc5J7kzyU5MFa6/RSytpJzkgyLcnNSfaptd61YsoEAACA8W1petCfV2t9Rq11+tDxYUkuqbVunuSSoWMAAABgGTyaIe4vTXLq0ONTk7zs0ZcDAAAAE9NoA3pN8u1SylWllDcNta1fa709SYbu11sRBQIAAMBEMKo56EmeXWu9rZSyXpKLSik/Ge0bDAX6NyXJk570pGUoEQAAAMa/UfWg11pvG7qfk+ScJNsn+XUpZcMkGbqf8wivPbHWOr3WOn3q1KnLp2oAAAAYZ5YY0Espq5VS1hh+nGSPJD9Ocm6SA4ZOOyDJN1ZUkQAAADDejWaI+/pJzimlDJ9/eq31W6WUHyY5s5TyxiS3JnnliisTAAAAxrclBvRa68+TbLuI9t8m2W1FFAUAAAATzaPZZg0AAABYTgR0AAAA6ICADgAAAB0Q0AEAAKADAjoAAAB0QEAHAACADgjoAAAA0AEBHQAAADogoAMAAEAHBHQAAADogIAOAAAAHRDQAQAAoAMCOgAAAHRAQAcAAIAOCOgAAADQAQEdAAAAOiCgAwAAQAcEdAAAAOiAgA4AAAAdENABAACgAwI6AAAAdEBABwAAgA4I6AAAANABAR0AAAA6IKADAABABwR0AAAA6ICADgAAAB0Q0AEAAKADAjoAAAB0QEAHAACADgjoAAAA0AEBHQAAADogoAMAAEAHBHQAAADogIAOAAAAHRDQAQAAoAMCOgAAAHRAQAcAAIAOCOgAAPRlr72SUpL3vW+k7ZJLkv33TzbbLFl11Xb/1rcmc+aM7pq//W3yzncmm27aXr/JJsnb3pbcccfC5951V3LwwcmTnpSsskqy8cbJ6143/zmnn95qWHvt5KCDkvvvn//5W25JVl89ufLKpfqfDkxskwddAAAA/K+vfjW59tqF2z/3uWTu3BbaN900mT07OeKI5MILkx/9qIXhR1Jr8pKXJDfdlBx1VLLllskNNyTvf39y1VXJf/5n+0EgaeH8Oc9px0cfnUybltx2W/L9749c76abkgMOaNfaaqtk5szkuOOSI48cOecd70j22y+ZMWN5/FWACUJABwCgD3ffnbzrXcnHP568+tXzP/eZzyRTp44c77JLssUW7f7MM5M3vOGRrzt7dgvhn/988qY3tbbnPjd5zGNaL/xNNyVPfWprP/zw9kPAddcla645co1XvWrk8UUXJZtv3s5NWtg/55yRgH7eecnllyc/+cmy/BWACcwQdwAA+vDud7ce6X33Xfi5ecP5sGc9q93/6leLv+4DD7T7eQN3kkyZ0u4ffrjd33df8qUvJQceuPC5C15v1VVHjldbLfnDH9rj++9vvefHH9+GvwMsBQEdAIDB+973Wjj+zGdG/5rLLmv3W265+PO22irZeefkgx9MZs1qPeQ/+EEbov6CF4y8/qqrWsBef/3kFa9oIXz11ZOXvSz5xS9GrjdjRhuGf9FFbfj7yScnO+zQnjvmmGSjjdoQeIClJKADADBYf/pT8uY3J4ceOjLUfEnuvbct5Lblli1AL04pyTe/2a79rGcla6zRQvammyZnnz1y3m23tftDD00mTUrOPTc58cTk6qvbkPh7723P77RTW3Bujz1aGH/44Ta8ffbsNjz/s58dmdMOsBQEdAAABuu441rP9XvfO7rzH3ywDYP/1a+Sr30tmTyKZZUOOii54oq22Nxll7X7WbNaT/nwEPfh+002add9/vPbXPgzz0xuvTX58pdHrvfRj7YV4H/2sxbgN9ywrQr/1rcmW2+dnHFG+/FgnXWSv/mb5M47l+5vAkxIFokDAGBwbr01+dCHki98IfnjH9tt2B//2BaOW2ON1qOdtBB9wAHJxRcn55+fbLPNkt/j/PPb6vAXX5zstltr23nn1oO+xx7Jv/1b8tKXtjCdJLvvPn8P+IwZbU761VfPf9111223JDnrrLZY3NlnJzfemLz2te19Z8xI9tmn9bifdtqy/Y2ACUMPOgAAg/Pzn7cF1vbfP3nCE0ZuSfKRj7TH1103cv5b3tJ6p7/2tZGwvSTDrx9eVG7Y9tu3+xtvbPdbbdXuH2l4+mMe4Z/Oc+e21edPOKHNWb/44taLvvvu7ceFmTOTb31rdLUCE5oedAAABucZz0i++92F25/3vBba3/jG5ClPaW2HHNJ62k89dcnzzue1wQbt/gc/aKF52JVXtvuNNmr3G2+cTJ+efPvbbe/04aB++eXJ7363cMAfduSRrSd/771H2u67b+Tx3LntegBLIKADADA4U6a0BdgW5clPHnnuuOOSj32s7Xe++eZtPvmwqVOTzTYbOZ48uQ2DP+mkdrz33m1++2tfm7z//cnTntb2KP/AB5InPjF5+ctHXnvsscmee7a56Qce2OaZv/e97TUL7s2eJNdf3xaSu+aakbZdd20L2B11VOulP/roNpQeYAkMcQcAoH8XXNDuv/jFZMcd57998IPzn/vQQ+02bM01W6B/wQva/uTD9y9+cesdX331kXN3263NSb/11hbc3/Wu1pt/6aXz730+bObMtur7ppuOtG21VXLKKa2nf599ki22aMPfAZZADzoAAP1ZcEj4pZcu+2uT1lM+3KO+JC94QbuNxvBe7At6zWvaDWAp6EEHAACADgjoAAAA0AEBHQAAADogoAMAAEAHBHQAAADogIAOAAAAHRDQAQAAoAMCOgAAAHRg8qALAABg5THtsPMHXcKEd/OxLxp0CcAKogcdAAAAOiCgAwAAQAcEdAAAAOiAgA4AAAAdENABAACgAwI6AAAAdEBABwAAgA4I6AAAANABAR0AAAA6IKADAABABwR0AAAA6ICADgAAAB0Q0AFgkC68MNl112SDDZJVVkk23jjZZ5/khhvmP++aa5K99kpWXz1Zc83kJS9Jfvaz0b3Hww8nH/5wMm1a8md/lmy7bXL22Quf99znJqUsfPvnf57/vNNPTzbbLFl77eSgg5L775//+VtuaXVeeeVo/woAQAR0ABisO+9M/vIvk099Kvn2t1uQvv76ZIcdWtBNktmzk7/6q+See5KvfCU5+eTk5puTnXdO5sxZ8nu8//3JkUcmb3tbcsEF7dqvfGXyzW8ufO422ySXXz7/7VWvGnn+ppuSAw5IDjwwOeWUdr3jjpv/Gu94R7LffsmMGcv4RwGAiWnyoAsAgAlt333bbV7bb5887WnJ17+eHHJIC8CTJrUwPGVKO2fGjOQpT0k+8pHk+OMf+fpz5rRzDjssOfTQ1va857Xe98MOS174wvnPX2ONFuAfyUUXJZtvnhx+eDu+4YbknHPaDwBJct55LdT/5Cej/hMAAI0edADozTrrtPvHPrbdX3FFsuOOI+E8aUPht966hePFufDC5IEHkv33n799//2T665LfvGLpavtgQeSVVcdOV5tteQPf2iP77+/9Z4ff3wb/g4ALBUBHQB68NBDLfzOnp28+c1tTvrw0PJJk5LHPW7h16yySvL//t9IQF6U669v5z3lKfO3b7VVu19wrvvVVydrrdV+HNhmm+Skk+Z/fsaM5NprW0/6bbe14fbDPe7HHJNstFEbAg8ALDVD3AGgBzNmJFdd1R4/5SnJd76TrLdeO37qU5P//M/kT38a6VW/994WvmtN7ror2XDDRV/3zjtbz3sp87cP93DfeedI2847t7njW2yR3H138qUvtbnmt9+evO997Zyddkre+c5kjz3a8bbbtuHts2cnH/946+1f8L0AgFHRgw4APTjttBZuTz+9rdL+/Oe3heCSFoh/9avkLW9p97fckrz+9cncue35xyzm67zWRQfmWhduO+qotir7LrskL31pW+n9ZS9LPvShkfdKko9+NLnjjjaP/eqr248Db3tb8ta3tmH3Z5yRbLllG6r/N38z/48AAMAjEtABoAdbbtl60ffdN7nkkhaIjz22PffsZyef/nRbNG7jjdt2aXff3YaSP+5xi5/vvfbarYd9wUB+110jzy/Ovvu2IfTXXTd/+7rr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
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
<h3 id="Fans-per-education-level"><span style="color: blue;">Fans per education level</span><a class="anchor-link" href="#Fans-per-education-level">&#182;</a></h3><h4 id="The-percentage-of-fans-per-education-level-is-bigger-for-the-graduate-degree.">The percentage of fans per education level is bigger for the graduate degree.<a class="anchor-link" href="#The-percentage-of-fans-per-education-level-is-bigger-for-the-graduate-degree.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><br /><br /></p>
<h2 id="Is-the-number-of-views-related-to-age?"><span style="color: red;">Is the number of views related to age?</span><a class="anchor-link" href="#Is-the-number-of-views-related-to-age?">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[147]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">age</span> <span class="o">=</span> <span class="n">star_wars</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;Age&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">agg</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">)</span>

<span class="n">age</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">age</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s1">&#39;Age&#39;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="n">income</span><span class="o">.</span><span class="n">columns</span><span class="p">[</span><span class="mi">2</span><span class="p">:</span><span class="mi">8</span><span class="p">],</span> <span class="n">kind</span><span class="o">=</span><span class="s1">&#39;bar&#39;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">14</span><span class="p">,</span><span class="mi">8</span><span class="p">));</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;center left&#39;</span><span class="p">,</span> <span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">1.0</span><span class="p">,</span> <span class="mf">0.5</span><span class="p">));</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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wsGDB+8pKCjwgNTPofb29rR79+6LfvnLXy6LiKs76+O/IAAAAGeSbw0ePHifEPr5VVBQkA0ePHhvHN617rxPjvUAAACcrAIh9PPvyP9HXeZNQRQAAIBc+Y4oAABwxhr+w59N6s35dv74O5t6c77Ps4ULF369srKy5dprr235LOP/5E/+5Dd+9KMflb/77rt/f95557X2ZKwgCgAA8AX04IMPvvtZx7722mt9fvGLX3z5vPPOO/RZxjuaCwAA0AP79u0rqKysvGDUqFEXjRgxYszjjz8+cP369edMmTJl1JgxYy685JJLRrz55pt9IiLq6ur6XXrppSPGjBlz4aRJk0bV1tYWR0RUVVUNv+WWW4ZOmDBhdHl5+dgnnnhiYFfrrVmzpmTKlCmjrrrqqm8MHz78W/Pnzy9bunTpoLFjx144cuTIi+rq6vpFRNTX1/edNm3ayJEjR140bdq0kQ0NDX2bmpoKy8rKxra1tUVEREtLS8GQIUPGHTx4MFVVVQ0/um5X9Xfl+9///tDFixfvSil9pvdQEAUAAOiBZ5999stDhgz5aMeOHVsbGhrqrr/++n0LFiyoWL169et1dXXb5syZ895dd91VFhFx2223DVuyZMlbdXV12xYvXryrurq64ug8jY2NfWpqaravXr264Z577in7tDW3b9/ef+nSpW9v27at7plnnimtr68v3rJly7bZs2e/98ADD3wtImLevHkVN910U1N9ff3WWbNmNVVXVw8tLS1tGz169P61a9eWRESsXLlywGWXXba3X79+xx74dPDgwdRV/Z356U9/OuC88877aNq0aQc+63voaC4AAEAPTJw48cCiRYuGVldXl11zzTV7S0tLWxsaGvpffvnlIyMi2tvbY/DgwR/t3bu3oLa29kszZ8785tGxhw4dOraFePXVV79fWFgYkyZN+rCpqelTdyDHjh37wbBhwz6KiKioqDh45ZVX7o2IGD9+/IF169aVRETU1tae+/zzz78eEVFdXd187733lkdEzJw5c8+KFSsGzpgxo+Xpp58eNH/+/N0d5968eXO/zurvrI6WlpaC+++//7z//t//e0PP37lfE0QBAAB6YNy4cQdffvnlratWrRqwaNGissrKyn0XXHDBgVdeeWV7x37Nzc0FJSUlrdu3b9/a2TzFxcXHdiWz7NN/kabjDmZBQcGxsQUFBdHW1vap52NvvPHG9++7776yxsbGwldfffWcGTNm7Ot4P8uy1Fn9ndm2bVu/Xbt29Rs3btxFERGNjY19J06ceOH//t//e1tFRUW3H1jkaC4AAEAP7Ny5s09JSUn7/PnzmxcuXNhYU1NzbnNzc9ELL7xwbsTho641NTXFgwYNai8vLz+0fPnygRGHdxpffPHF/qeqrgkTJnywbNmygRERjz766KDJkyf/KiJiwIAB7ePHj//gjjvuqLjiiiv2FhV9fD9y3LhxH3ZWf2drTJ069UBzc/Pfv/POO1veeeedLb/xG79x6OWXX+5RCI2wIwoAAJzBTsfPrWzatKn/3XffXV5QUBBFRUXZkiVL3iwqKsoWLFhQ0dLSUtjW1paqq6sbJ0+e/OGKFSveuP3224fdf//957W2tqbrrruu+WS+W/lpli5d+tacOXOGP/TQQ0NKS0tbn3zyyZ1H791www17br311m+sWbNmx/HjiouLs5UrV77eWf2nos4IQRQAAKBHqqqq9lVVVX3iuG1NTc0nQt7o0aMPrV+//hPfp1y1atXOjtf79++v7Wq96dOnt0yfPv3Yb31u2LBhR2f3Ro0adeill16q72yOuXPn7pk7d+7HQnvHGi6++OIDndV/Iu+8886Wno6JcDQXAACAnNkRBQAA+BzYsGFD/5tvvvn8jm19+/Zt37x58wkfInQqzJ49u2Ljxo1f6thWXV3deOeddzad7NyCKAAAwOfA1KlTD3T1hN3T4amnnnrrVM3taC4AAAC5EkQBAADIlSAKAABArgRRAAAAcuVhRQAAwJnrTwdM6t359m46caezw8KFC79eWVnZcu2117acuPev/eAHP/j6f/yP//GrgwYNao2IuPfee9+ZNWvW3p7MIYgCAAB8AT344IPvftax8+bNa7zvvvsaP+t4R3MBAAB6YN++fQWVlZUXjBo16qIRI0aMefzxxweuX7/+nClTpowaM2bMhZdccsmIN998s09ERF1dXb9LL710xJgxYy6cNGnSqNra2uKIiKqqquG33HLL0AkTJowuLy8f+8QTTwzsar01a9aUTJkyZdRVV131jeHDh39r/vz5ZUuXLh00duzYC0eOHHlRXV1dv4iI+vr6vtOmTRs5cuTIi6ZNmzayoaGhb1NTU2FZWdnYtra2iIhoaWkpGDJkyLiDBw+mqqqq4UfX7ar+U0UQBQAA6IFnn332y0OGDPlox44dWxsaGuquv/76fQsWLKhYvXr163V1ddvmzJnz3l133VUWEXHbbbcNW7JkyVt1dXXbFi9evKu6urri6DyNjY19ampqtq9evbrhnnvuKfu0Nbdv395/6dKlb2/btq3umWeeKa2vry/esmXLttmzZ7/3wAMPfC0iYt68eRU33XRTU319/dZZs2Y1VVdXDy0tLW0bPXr0/rVr15ZERKxcuXLAZZddtrdfv37Z0bkPHjyYuqq/K3/2Z3/2tZEjR140c+bM4bt37y7s6XvoaC4AAEAPTJw48cCiRYuGVldXl11zzTV7S0tLWxsaGvpffvnlIyMi2tvbY/DgwR/t3bu3oLa29kszZ8785tGxhw4dSkdfX3311e8XFhbGpEmTPmxqavrUHcixY8d+MGzYsI8iIioqKg5eeeWVeyMixo8ff2DdunUlERG1tbXnPv/8869HRFRXVzffe++95RERM2fO3LNixYqBM2bMaHn66acHzZ8/f3fHuTdv3tyvs/q7quWf//N//k//9t/+23dTSrFw4cKy+fPnD/3Lv/zLnT15DwVRAACAHhg3btzBl19+eeuqVasGLFq0qKyysnLfBRdccOCVV17Z3rFfc3NzQUlJSev27du3djZPcXHxsV3JLMs663JMxx3MgoKCY2MLCgqira0tdT0y4sYbb3z/vvvuK2tsbCx89dVXz5kxY8a+jvezLEud1d+VoUOHth59/f3vf3/39OnTR3RnXEeO5gIAAPTAzp07+5SUlLTPnz+/eeHChY01NTXnNjc3F73wwgvnRhw+6lpTU1M8aNCg9vLy8kPLly8fGHF4p/HFF1/sf6rqmjBhwgfLli0bGBHx6KOPDpo8efKvIiIGDBjQPn78+A/uuOOOiiuuuGJvUdHH9yPHjRv3YWf1d7VOx++Prly58iujRo060NNa7YgCAABnrtPwcyubNm3qf/fdd5cXFBREUVFRtmTJkjeLioqyBQsWVLS0tBS2tbWl6urqxsmTJ3+4YsWKN26//fZh999//3mtra3puuuua542bVqPg1t3LF269K05c+YMf+ihh4aUlpa2PvnkkzuP3rvhhhv23Hrrrd9Ys2bNjuPHFRcXZytXrny9s/o7W+fOO+8s37p1a/+IiPLy8kNPPPHEmz2tVRAFAADogaqqqn1VVVWfOG5bU1PziZA3evToQ+vXr284vn3VqlU7O17v37+/tqv1pk+f3jJ9+vRjv/W5YcOGHZ3dGzVq1KGXXnqpvrM55s6du2fu3LkfC+0da7j44osPdFZ/Z/76r//6H7rT79M4mgsAAECu7IgCAAB8DmzYsKH/zTfffH7Htr59+7Zv3ry5Ww8R6m2zZ8+u2Lhx45c6tlVXVzfeeeedTSc7tyAKAADwOTB16tQDXT1h93R46qmn3jpVczuaCwAAQK4EUQAAAHIliAIAAJArQRQAAIBceVgRAABwxhr7F2Mn9eZ8W+Zs2XTiXmeHhQsXfr2ysrLl2muvbTlx74/71//6X3/t8ccf/1pRUVH227/923sfeeSRXT0ZL4gCAAB8AT344IPvfpZx/+W//JeSn/3sZ1/Ztm1bXf/+/bN33nmnx7nS0VwAAIAe2LdvX0FlZeUFo0aNumjEiBFjHn/88YHr168/Z8qUKaPGjBlz4SWXXDLizTff7BMRUVdX1+/SSy8dMWbMmAsnTZo0qra2tjgioqqqavgtt9wydMKECaPLy8vHPvHEEwO7Wm/NmjUlU6ZMGXXVVVd9Y/jw4d+aP39+2dKlSweNHTv2wpEjR15UV1fXLyKivr6+77Rp00aOHDnyomnTpo1saGjo29TUVFhWVja2ra0tIiJaWloKhgwZMu7gwYOpqqpq+NF1u6q/M0uXLh38R3/0R//Yv3//LCKirKystafvoSAKAADQA88+++yXhwwZ8tGOHTu2NjQ01F1//fX7FixYULF69erX6+rqts2ZM+e9u+66qywi4rbbbhu2ZMmSt+rq6rYtXrx4V3V1dcXReRobG/vU1NRsX716dcM999xT9mlrbt++vf/SpUvf3rZtW90zzzxTWl9fX7xly5Zts2fPfu+BBx74WkTEvHnzKm666aam+vr6rbNmzWqqrq4eWlpa2jZ69Oj9a9euLYmIWLly5YDLLrtsb79+/bKjcx88eDB1VX9n3njjjeJ169aVjBs3bvSUKVNGrVu37pyevoeO5gIAAPTAxIkTDyxatGhodXV12TXXXLO3tLS0taGhof/ll18+MiKivb09Bg8e/NHevXsLamtrvzRz5sxvHh176NChdPT11Vdf/X5hYWFMmjTpw6ampi53ICMixo4d+8GwYcM+ioioqKg4eOWVV+6NiBg/fvyBdevWlURE1NbWnvv888+/HhFRXV3dfO+995ZHRMycOXPPihUrBs6YMaPl6aefHjR//vzdHefevHlzv87q76qWtra2tGfPnsJXXnll+7p168656aabvvn2229vKSjo/j6nIAoAANAD48aNO/jyyy9vXbVq1YBFixaVVVZW7rvgggsOvPLKK9s79mtubi4oKSlp3b59+9bO5ikuLj62K5llWWddjum4g1lQUHBsbEFBQbS1taWuR0bceOON7993331ljY2Nha+++uo5M2bM2NfxfpZlqbP6uzJkyJBDv/d7v/d+QUFB/NZv/db+goKC7Je//GXR17/+9W4f0XU0FwAAoAd27tzZp6SkpH3+/PnNCxcubKypqTm3ubm56IUXXjg34vBR15qamuJBgwa1l5eXH1q+fPnAiMM7jS+++GL/U1XXhAkTPli2bNnAiIhHH3100OTJk38VETFgwID28ePHf3DHHXdUXHHFFXuLij6+Hzlu3LgPO6u/q3VmzJjx/gsvvFAScXg39aOPPioYMmRIj74n2q0d0ZTStyPioYgojIhlWZb9uIt+UyLipYiYlWXZMz0pBAAAoKdOx8+tbNq0qf/dd99dXlBQEEVFRdmSJUveLCoqyhYsWFDR0tJS2NbWlqqrqxsnT5784YoVK964/fbbh91///3ntba2puuuu6552rRpB05FXUuXLn1rzpw5wx966KEhpaWlrU8++eTOo/duuOGGPbfeeus31qxZs+P4ccXFxdnKlStf76z+ztZZsGDBe7NmzRo+YsSIMX369Gl/7LHH/qEnx3IjuhFEU0qFEfFwRPxOROyKiI0ppeeyLNvaSb/7I+LnPaoAAADgDFJVVbWvqqrqE8dta2pqPhHyRo8efWj9+vUNx7evWrVqZ8fr/fv313a13vTp01umT59+7Lc+N2zYsKOze6NGjTr00ksv1Xc2x9y5c/fMnTv3Y6G9Yw0XX3zxgc7q70xxcXG2evXqf+hO3650J7ZOjYjXsix7I8uyQxGxMiKu6aTfH0TEqoj4p5MpCAAAgLNbd47mlkXE2x2ud0XE/9GxQ0qpLCKui4jLI2JKr1UHAADwBbFhw4b+N9988/kd2/r27du+efPmbj1EqLfNnj27YuPGjV/q2FZdXd145513Np3s3N0Jop09gen4Rzo9GBF/nGVZW0pdP7AppfS9iPheRERFRUWX/QAAAL5opk6deqCrJ+yeDk899dRbp2ru7gTRXRExtMN1eUS8e1yfyRGx8kgI/WpEXJVSas2y7K87dsqy7LGIeCwiYvLkyZ/+fGIAAADOSt0JohsjYkRK6fyIeCcivhsRN3XskGXZse3jlNKfR8Sa40MoAAAARHQjiGZZ1ppS+n4cfhpuYUQsz7KsLqU078j9R05xjQAAfNH86YCTHL+3d+oATolu/Y5olmVrI2LtcW2dBtAsy245+bIAAAA4W3UriAIAAHwebRt94aTenO/C7ds2nbjX2WHhwoVfr6ysbLn22mtbTtz715YvXz7w3/ybf/P1N954o/hv//Zvt/2zf/bP9vd0bUEUAADgC+jBBx88/iG03fKbv/mbB1atWvXa7bffPvyzri2IAgBAJ7aNvvDkJqh8uHcK4XNn3759BVdfffU3/vEf/7Fve3t7+qM/+qN3R48effAHP/jB0P379xcMHDiw9ac//enOYcOGfVRXV9dv3rx5Fc3NzUXFxcXty5Yte3PChAkfVlVVDS8pKWn7+7//+3N3797d50c/+tGuuXPn7ulsvTVr1pTce++9Xx88ePBHW7duPeeqq67aM3bs2ANLliz5jYMHD6a/+qu/en3MmDEH6+vr+86ZM2d4U1NTUWlpaeuTTz65c9CgQW3jxo276K233tpSWFgYLS0tBSNGjPjWm2++ueWmm24aNn369L1z587ds379+nM6q7+zeiZOnPjhyb6HBSc7AQAAwBfJs88+++UhQ4Z8tGPHjq0NDQ11119//b4FCxZUrF69+vW6urptc+bMee+uu+4qi4i47bbbhi1ZsuSturq6bYsXL95VXV1dcXSexsbGPjU1NdtXr17dcM8995R92prbt2/vv3Tp0re3bdtW98wzz5TW19cXb9myZdvs2bPfe+CBB74WETFv3ryKm266qam+vn7rrFmzmqqrq4eWlpa2jR49ev/atWtLIiJWrlw54LLLLtvbr1+/Yz+nefDgwdRV/aeKHVEAAIAemDhx4oFFixYNra6uLrvmmmv2lpaWtjY0NPS//PLLR0ZEtLe3x+DBgz/au3dvQW1t7Zdmzpz5zaNjDx06lI6+vvrqq98vLCyMSZMmfdjU1NTn09YcO3bsB0d3KCsqKg5eeeWVeyMixo8ff2DdunUlERG1tbXnPv/8869HRFRXVzffe++95RERM2fO3LNixYqBM2bMaHn66acHzZ8/f3fHuTdv3tyvs/p7473qiiAKAADQA+PGjTv48ssvb121atWARYsWlVVWVu674IILDrzyyivbO/Zrbm4uKCkpad2+ffvWzuYpLi4+tiuZZVlnXY7puINZUFBwbGxBQUG0tbWlrkdG3Hjjje/fd999ZY2NjYWvvvrqOTNmzNjX8X6WZamz+k8lR3MBAAB6YOfOnX1KSkra58+f37xw4cLGmpqac5ubm4teeOGFcyMOH3WtqakpHjRoUHt5efmh5cuXD4w4vNP44osv9j9VdU2YMOGDZcuWDYyIePTRRwdNnjz5VxERAwYMaB8/fvwHd9xxR8UVV5ywwpQAAB7zSURBVFyxt6jo4/uR48aN+7Cz+k9VnRF2RAEAgDPY6fi5lU2bNvW/++67ywsKCqKoqChbsmTJm0VFRdmCBQsqWlpaCtva2lJ1dXXj5MmTP1yxYsUbt99++7D777//vNbW1nTdddc1T5s27cCpqGvp0qVvzZkzZ/hDDz005OjDio7eu+GGG/bceuut31izZs2O48cVFxdnK1eufL2z+jtb58knn/zKH/7hH1bs2bOn6Lrrrhtx4YUX7v+7v/u7hp7UKogCAAD0QFVV1b6qqqpPHLetqan5RMgbPXr0ofXr138ipK1atWpnx+v9+/fXdrXe9OnTW6ZPn37stz43bNiwo7N7o0aNOvTSSy/VdzbH3Llz98ydO/djob1jDRdffPGBzurvzM033/z+zTff/H53+nbF0VwAAAByZUcUAICzzti/GHvSczzdC3VAT2zYsKH/zTfffH7Htr59+7Zv3rw5t4cIdTR79uyKjRs3fqljW3V1deOdd97ZdLJzC6IAAACfA1OnTj3Q1RN2T4ennnrqrVM1t6O5AAAA5EoQBQAAIFeCKAAAALkSRAEAAMiVhxUBAABnrIfn/WJSb873+49cvunEvc4OCxcu/HplZWXLtdde23Li3r92xx13lP/N3/zNgD59+mTDhg07uGLFip1f/epX23oyhx1RAACAL6AHH3zw3Z6G0IiI3/3d391XX19fV19fv/WCCy748F/9q381pKdzCKIAAAA9sG/fvoLKysoLRo0addGIESPGPP744wPXr19/zpQpU0aNGTPmwksuuWTEm2++2Scioq6urt+ll146YsyYMRdOmjRpVG1tbXFERFVV1fBbbrll6IQJE0aXl5ePfeKJJwZ2td6aNWtKpkyZMuqqq676xvDhw781f/78sqVLlw4aO3bshSNHjryorq6uX0REfX1932nTpo0cOXLkRdOmTRvZ0NDQt6mpqbCsrGxsW9vhDcuWlpaCIUOGjDt48GCqqqoafnTdrurvzPXXX7+vT5/Dt6dNm/bBO++807en76EgCgAA0APPPvvsl4cMGfLRjh07tjY0NNRdf/31+xYsWFCxevXq1+vq6rbNmTPnvbvuuqssIuK2224btmTJkrfq6uq2LV68eFd1dXXF0XkaGxv71NTUbF+9enXDPffcU/Zpa27fvr3/0qVL3962bVvdM888U1pfX1+8ZcuWbbNnz37vgQce+FpExLx58ypuuummpvr6+q2zZs1qqq6uHlpaWto2evTo/WvXri2JiFi5cuWAyy67bG+/fv2yo3MfPHgwdVX/ifz5n//5V7/97W/v7el76DuiAAAAPTBx4sQDixYtGlpdXV12zTXX7C0tLW1taGjof/nll4+MiGhvb4/Bgwd/tHfv3oLa2tovzZw585tHxx46dCgdfX311Ve/X1hYGJMmTfqwqampyx3IiIixY8d+MGzYsI8iIioqKg5eeeWVeyMixo8ff2DdunUlERG1tbXnPv/8869HRFRXVzffe++95RERM2fO3LNixYqBM2bMaHn66acHzZ8/f3fHuTdv3tyvs/pP9D788R//8ZDCwsJs3rx5zd17535NEAUAAOiBcePGHXz55Ze3rlq1asCiRYvKKisr911wwQUHXnnlle0d+zU3NxeUlJS0bt++fWtn8xQXFx/blcyyrLMux3TcwSwoKDg2tqCgINra2lLXIyNuvPHG9++7776yxsbGwldfffWcGTNm7Ot4P8uy1Fn9n+YnP/lJ6c9//vOvrF+/vr6goOcHbR3NBQAA6IGdO3f2KSkpaZ8/f37zwoULG2tqas5tbm4ueuGFF86NOHzUtaampnjQoEHt5eXlh5YvXz4w4vBO44svvtj/VNU1YcKED5YtWzYwIuLRRx8dNHny5F9FRAwYMKB9/PjxH9xxxx0VV1xxxd6ioo/vR44bN+7Dzurvap1nnnnmyw8++OCQtWvXvlZSUtL+WWq1IwoAAJyxTsfPrWzatKn/3XffXV5QUBBFRUXZkiVL3iwqKsoWLFhQ0dLSUtjW1paqq6sbJ0+e/OGKFSveuP3224fdf//957W2tqbrrruuedq0aQdORV1Lly59a86cOcMfeuihIaWlpa1PPvnkzqP3brjhhj233nrrN9asWbPj+HHFxcXZypUrX++s/s7W+cEPflBx6NChgqNHeSdOnPir//Sf/tNbPalVEAUAAOiBqqqqfVVVVZ84bltTU/OJkDd69OhD69evbzi+fdWqVTs7Xu/fv7+2q/WmT5/eMn369GM/s7Jhw4Ydnd0bNWrUoZdeeqm+sznmzp27Z+7cuR8L7R1ruPjiiw90Vn9n3nrrrVe70+/TOJoLAABAruyIAgAAfA5s2LCh/80333x+x7a+ffu2b968udsPEepNs2fPrti4ceOXOrZVV1c33nnnnU0nO7cgCgAA8DkwderUA109Yfd0eOqpp3r0vc+ecDQXAACAXAmiAAAA5EoQBQAAIFeCKAAAALnysCIAAOCM9cCs6ZN6c75/8Z/XbDpxr7PDwoULv15ZWdly7bXXtpy496/deeedX3/++ee/UlBQEKWlpR/99Kc/3Tl8+PCPejKHHVEAAIAvoAcffPDdnobQiIh77rnnl/X19Vu3b9++9corr9z7L//lvzyvp3MIogAAAD2wb9++gsrKygtGjRp10YgRI8Y8/vjjA9evX3/OlClTRo0ZM+bCSy65ZMSbb77ZJyKirq6u36WXXjpizJgxF06aNGlUbW1tcUREVVXV8FtuuWXohAkTRpeXl4994oknBna13po1a0qmTJky6qqrrvrG8OHDvzV//vyypUuXDho7duyFI0eOvKiurq5fRER9fX3fadOmjRw5cuRF06ZNG9nQ0NC3qampsKysbGxbW1tERLS0tBQMGTJk3MGDB1NVVdXwo+t2VX9nBg0a1H709QcffFCQUurxeyiIAgAA9MCzzz775SFDhny0Y8eOrQ0NDXXXX3/9vgULFlSsXr369bq6um1z5sx576677iqLiLjtttuGLVmy5K26urptixcv3lVdXV1xdJ7GxsY+NTU121evXt1wzz33lH3amtu3b++/dOnSt7dt21b3zDPPlNbX1xdv2bJl2+zZs9974IEHvhYRMW/evIqbbrqpqb6+fuusWbOaqqurh5aWlraNHj16/9q1a0siIlauXDngsssu29uvX7/s6NwHDx5MXdXflT/4gz8oGzJkyLhnnnmmdPHixe/29D30HVEAAIAemDhx4oFFixYNra6uLrvmmmv2lpaWtjY0NPS/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
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
<h3 id="Views-per-age"><span style="color: blue;">Views per age</span><a class="anchor-link" href="#Views-per-age">&#182;</a></h3><h4 id="It-is-possible-to-note-that-for-younger-people-we-have-more-stable-views-for-all-movies.">It is possible to note that for younger people we have more stable views for all movies.<a class="anchor-link" href="#It-is-possible-to-note-that-for-younger-people-we-have-more-stable-views-for-all-movies.">&#182;</a></h4>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Answer:"><span style="color: blue;">Answer:</span><a class="anchor-link" href="#Answer:">&#182;</a></h1><h2 id="Yes,-&#8220;The-Empire-Strikes-Back&#8221;-is-clearly-the-best-of-the-bunch.-The-movie-number-two-is-highest-ranked-and-has-more-views.">Yes, &#8220;The Empire Strikes Back&#8221; is clearly the best of the bunch. The movie number two is highest-ranked and has more views.<a class="anchor-link" href="#Yes,-&#8220;The-Empire-Strikes-Back&#8221;-is-clearly-the-best-of-the-bunch.-The-movie-number-two-is-highest-ranked-and-has-more-views.">&#182;</a></h2>
</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
