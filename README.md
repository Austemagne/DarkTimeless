NOTE: Using a CSS editor to "beautify" or "Apply source format" can mass edit the following css to be easier to read.


/* CSS placed here will affect users of the Timeless skin */
@import url('https://fonts.googleapis.com/css?family=Merriweather');
html {
	background: rgb(0,0,0) !important;
	height: 100%;
	font-size: 1.1em;
	filter: brightness(100%) contrast(100%) grayscale(0%) !important;
	-webkit-filter: brightness(100%) contrast(100%) grayscale(0%) !important;
	overflow-x: hidden;
}
body {
	margin: 0;
	background: #000;
	color: #ccccff;
	font-family: 'Merriweather', serif;
}
a {
	color: #cc6600;
}
a:hover, a:visited {
	color: #cc3300;
}
h1 {
	color: white;
	text-shadow: 1px 1px 1px #000;
	font-size: 40px !important;
}
h1, h2, h3, h4 {
	color: #6699ff;
	font-family: 'Merriweather', serif;
}
#personal .dropdown b {
	font-weight: normal;
}
b, strong {
	text-shadow: 1px 1px 1px #000;
}
#f-list {
	text-align: center;
	font-size: 14px;
}
div.editOptions {
	border: #222;
	background: #555;
}
#mw-header-nav-hack {
	border-top: solid 2px #333;
	background: #333;
}
#mw-site-navigation .sidebar-inner {
	background: #333;
	border: 0;
}
@media screen and (min-width: 851px) {
#p-logo-text a {
	position: fixed;
	right: 75vw;
}
}
@media screen and (max-width: 850px) {
#p-logo-text {
	margin-top: 0;
}
}
@media screen and (max-width: 1099px) and (min-width: 851px) {
#p-logo-text a.long {
	padding-left: 7px;
	float: left;
	font-size: 26px;
}
}
@media screen and (max-width: 1099px) and (min-width: 851px) {
#mw-related-navigation .sidebar-inner {
	background: #222 !important;
	border: solid #111;
}
}
@media screen and (max-width: 1099px) and (min-width: 851px) {
#mw-site-navigation .sidebar-inner {
	background: #222;
	border: solid #111;
}
}
#mw-site-navigation .sidebar-chunk {
	border: outset #222;
	background: #333;
	box-shadow: 2px 2px 1px rgba(0,0,0,0.5);
	border-radius: 3px;
}
@media screen and (max-width: 851px) {
#mw-site-navigation .sidebar-chunk {
	padding: 0 15px 5px 20px;
}
}
@media screen and (max-width: 1099px) and (min-width: 851px) {
#mw-site-navigation .sidebar-inner {
	background: #222 !important;
	border: solid #111 !important;
}
}
.mw-parser-output a.external {
	color: #ff9900;
}
#searchInput {
	padding: 0.2em 4.5em 0.2em 2em !important;
	margin: 0;
}
#searchInput-container {
	background: #333;
	height: 35px;
}
#simpleSearch {
	border: inset 1px #000;
	border-radius: 3px;
	background: #333;
	height: 35px;
	width: 48vw;
	position: absolute;
	left: 0;
	right: 0;
	margin-left: auto;
	margin-right: auto;
	top: 7px;
}
#user-tools {
	position: fixed;
	right: 86px;
}
@media screen and (min-width: 851px) {
#user-tools {
	left: 74vw;
	top: 5px;
}
}
.mw-notification {
	background: #222;
	border: #111;
	border-radius: 5px;
	color: #999;
	width: 200px;
}
.postedit-container {
	position: absolute;
	left: 0;
	right: 0;
	margin-left: auto;
	margin-right: auto;
	padding: 0;
	padding: 15px 0 15px 15px;
	text-align: right;
}
.postedit-icon {
	margin: auto;
	padding: 0;
}
.mw-wiki-logo {
	background: url("https://www.YOURDOMAIN/logo.png");
	background-size: contain;
}
#mw-header-container {
	background: #555;
}
#mw-header {
	width: 100%;
	max-width: 100%;
	padding: 0;
	position: static;
}
@media screen and (max-width: 850px) {
#menus-cover {
	background: #000;
}
}
@media screen and (max-width: 850px) {
#personal h2 {
	display: none;
}
}
#mw-content-container {
	background: #1d1d16;
}
@media screen and (max-width: 850px) {
#mw-content-block {
	background: #000;
}
}
@media screen and (max-width: 850px) {
#site-tools h2 {
	right: 3em;
	top: 0.9em;
	padding-bottom: 5px;
}
}
@media screen and (max-width: 850px) {
#p-logo-text a.long {
	width: 100%;
	top: 7px;
	text-align: center;
	font-size: 40px !important;
}
}
@media screen and (min-width: 851px) {
#p-logo-text {
	width: 29em;
}
}
@media screen and (min-width: 851px) {
#personal h2:after {
	width: 36px;
}
}
@media screen and (max-width: 850px) {
#p-logo-text {
	position: static;
	left: 0 !important;
	right: 0;
	margin-left: 0;
	margin-right: 0;
	width: 100%;
	top: 3.3em;
}
}
 @media only screen and (min-width: 992px) and (max-width:768p) {
 #p-logo-text {
 right:74vw;
}
}
@media only screen and (min-width: 900px) and (max-width:100px) {
#p-logo-text {
	right: 74vw;
	top: 3em;
}
}
@media screen and (max-width: 900px) and (min-width: 100px) {
#p-logo-text a.long {
	font-size: 43px !important;
}
}
@media screen and (max-width: 1700px) and (min-width: 800px) {
#p-logo-text {
	left: 12px !important;
}
}
@media screen and (max-width: 1700px) and (mix: 851px) {
#mw-site-navigation {
	background: #000;
}
}
#mw-content {
	background: #333;
	border: solid #946c20;
	-webkit-border-bottom-right-radius: 4px;
	-webkit-border-bottom-left-radius: 4px;
	-moz-border-radius-bottomright: 4px;
	-moz-border-radius-bottomleft: 4px;
	border-bottom-right-radius: 4px;
	border-bottom-left-radius: 4px;
}
#mw-page-header-links li.selected a {
	color: #cccc00;
}
#mw-related-navigation .sidebar-chunk {
	background: #333;
	border: outset #222;
	box-shadow: 2px 2px 1px rgba(0,0,0,0.5);
	border-radius: 3px;
}
@media screen and (max-width: 1099px) and (min-width: 851px) {
#mw-related-navigation .sidebar-chunk {
	background: #333;
	border: outset #222;
	box-shadow: 2px 2px 1px rgba(0,0,0,0.5);
	border-radius: 3px;
	padding: 0 15px 5px 20px;
}
}
.color-middle-container, .ts-inner {
	padding: 0;
}
#p-logo-text {
	left: 120px;
}
#p-logo-text a.long {
	padding-top: 5px;
	padding-left: 6px;
	font-size: 23px;
	text-shadow: 1px 1px 1px #222;
}
#p-search {
	width: 70em;
	padding-right: 33px;
}
#personal .dropdown h3 {
	line-height: 25px;
}
#personal h2 {
	text-shadow: 2px 2px 0 #333;
	padding-top: 7px;
	font-size: 24px;
	text-transform: lowercase;
}
#personal .dropdown {
	background: #222!important;
	border: solid #000;
}
.codeEditor-status {
	color: #000;
}
.oo-ui-labelElement-label {
	text-shadow: 1px 2px #333;
}
#iframeframe {
	height: 700px;
}
#wpSave {
	text-shadow: 2px 2px 2px #000 !important
}
#mw-footer-container {
	background: #000;
	padding-top: 1em;
}
fieldset {
	background: #222!important;
	border: solid #111;
}
input {
	background: #333;
	border: solid 1px #111!important;
	border-radius: 2px;
	padding-left: 5px;
	color: #999;
}
.mw-ui-button.mw-ui-progressive, .mw-ui-button.mw-ui-progressive:active, .mw-ui-button.mw-ui-progressive.mw-ui-checked, input[type='submit'], input[type='button'], button {
	border: solid 1px #333!important;
	border-bottom: 0!important;
	text-shadow: 0 0 0 #000 !important;
	border-bottom: solid 1px #333!important;
}
.oo-ui-flaggedElement-destructive {
	background: #111;
	border: 1px solid #444;
	color: #FF333 !important;
	padding-left: 15px !important;
	padding-right: 15px !important;
}
.oo-ui-flaggedElement-destructive:hover {
	background: #222;
	color: #CC0000 !important;
}
#searchInput {
	border: 0!important;
}
@media screen and (max-width: 850px) {
#searchInput {
	padding: 0 0 0 6px !important;
}
}
.oo-ui-textInputWidget input, .oo-ui-textInputWidget textarea {
	background-color: #333;
	color: #fff;
}
.oo-ui-textInputWidget > .oo-ui-labelElement-label {
	line-height: 0.5em;
}
#pagehistory li.selected {
	background-color: #555;
}
.warningbox {
	background: #1d1d16;
}
a.new:hover, .new a:hover, a.new:visited, .new a:visited {
	color: #FF3333;
}
.mw-plusminus-neg {
	color: #FF0000;
}
#searchButton, #mw-searchButton {
	border: 0 !important;
	left: 38vw;
	right: 0;
	margin-left: auto;
	margin-right: auto;
}
#mw-footer-container a:hover {
	color: #ffff33;
}
#mw-footer-container a:visited {
	color: #ffff66;
}
#mw-footer .footer-places li {
	float: right;
	display: block;
}
#mw-footer ul, #mw-footer li {
	margin: 0 auto;
}
#mw-footer #lastmod {
	float: left;
	left: 25px;
}
.diff-addedline .diffchange {
	background: #1d1d16;
	padding-left: 7px;
}
.oo-ui-buttonElement.oo-ui-labelElement > input.oo-ui-buttonElement-button, .oo-ui-buttonElement.oo-ui-labelElement > .oo-ui-buttonElement-button > .oo-ui-labelElement-label {
	text-shadow: 0 0 0 #000 !important;
}
.oo-ui-labelElement-label {
	text-shadow: 0 0 0 #000
}
.oo-ui-panelLayout-expanded {
	background: #222;
}
.oo-ui-messageDialog-message {
	color: #999;
}
.oo-ui-buttonElement-frameless.oo-ui-widget-enabled > .oo-ui-buttonElement-button {
	color: #999;
}
.oo-ui-messageDialog-actions-horizontal .oo-ui-actionWidget {
	border-right: 1px solid #111
}
.oo-ui-dialog-content > .oo-ui-window-body {
	outline: 1px solid #111;
}
.oo-ui-messageDialog-content > .oo-ui-window-foot {
	outline: 1px solid #111;
}
.wikiEditor-ui .wikiEditor-ui-view {
	border: 1px solid #000;
}
.wikiEditor-ui .wikiEditor-ui-top {
	border-bottom: 1px solid #000;
}
textarea[style] {
	background: #111 !important;
	color: #fff;
}
pre, .mw-code {
	background: #222;
	color: #B0B0B0;
	border: 1px solid #444;
}
.oo-ui-iconWidget.oo-ui-iconElement.oo-ui-iconElement-icon {
	background-color: #B0B0B0;
	border: 1px solid #333;
}
