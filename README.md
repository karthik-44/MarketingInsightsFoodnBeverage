# MarketingInsightsFoodnBeverage  

**Domain:** F & B   
**Function:** Marketing  

**CodeX** is a German beverage company that is aiming to make its mark in the Indian market. A few months ago, they launched their energy drink in 10 cities in India. Their Marketing team is responsible for increasing
brand awareness,
market share,
product development.
Survey was conducted in 10 cities and received results from 10k respondents.
As a marketing data analyst we are tasked to convert these survey results to meaningful insights which the team can use to drive actions.

Check the link for rendered plotly images: https://nbviewer.org/github/karthik-44/MarketingInsightsFoodnBeverage/blob/main/MarketAnalysis.ipynb  

``` html
<html lang="en-US" data-theme="light" style="color-scheme: light;"><head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<style data-tippy-stylesheet="">.tippy-box[data-animation=fade][data-state=hidden]{opacity:0}[data-tippy-root]{max-width:calc(100vw - 10px)}.tippy-box{position:relative;background-color:#333;color:#fff;border-radius:4px;font-size:14px;line-height:1.4;white-space:normal;outline:0;transition-property:transform,visibility,opacity}.tippy-box[data-placement^=top]>.tippy-arrow{bottom:0}.tippy-box[data-placement^=top]>.tippy-arrow:before{bottom:-7px;left:0;border-width:8px 8px 0;border-top-color:initial;transform-origin:center top}.tippy-box[data-placement^=bottom]>.tippy-arrow{top:0}.tippy-box[data-placement^=bottom]>.tippy-arrow:before{top:-7px;left:0;border-width:0 8px 8px;border-bottom-color:initial;transform-origin:center bottom}.tippy-box[data-placement^=left]>.tippy-arrow{right:0}.tippy-box[data-placement^=left]>.tippy-arrow:before{border-width:8px 0 8px 8px;border-left-color:initial;right:-7px;transform-origin:center left}.tippy-box[data-placement^=right]>.tippy-arrow{left:0}.tippy-box[data-placement^=right]>.tippy-arrow:before{left:-7px;border-width:8px 8px 8px 0;border-right-color:initial;transform-origin:center right}.tippy-box[data-inertia][data-state=visible]{transition-timing-function:cubic-bezier(.54,1.5,.38,1.11)}.tippy-arrow{width:16px;height:16px;color:#333}.tippy-arrow:before{content:"";position:absolute;border-color:transparent;border-style:solid}.tippy-content{position:relative;padding:5px 9px;z-index:1}</style><link rel="profile" href="https://gmpg.org/xfn/11">
	<title>Marketing Insights of CodeX</title>
<meta name="robots" content="noindex, nofollow">
<link rel="dns-prefetch" href="//use.fontawesome.com">
<link rel="alternate" type="application/rss+xml" title=" » Feed" href="https://kvrkarthik.com/feed/">
<link rel="alternate" type="application/rss+xml" title=" » Comments Feed" href="https://kvrkarthik.com/comments/feed/">
<link rel="alternate" type="application/rss+xml" title=" » Marketing Insights of CodeX Comments Feed" href="https://kvrkarthik.com/marketing-insights-of-codex/feed/">
<script>
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/kvrkarthik.com\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.2.3"}};
/*! This file is auto-generated */
!function(e,a,t){var n,r,o,i=a.createElement("canvas"),p=i.getContext&&i.getContext("2d");function s(e,t){p.clearRect(0,0,i.width,i.height),p.fillText(e,0,0);e=i.toDataURL();return p.clearRect(0,0,i.width,i.height),p.fillText(t,0,0),e===i.toDataURL()}function c(e){var t=a.createElement("script");t.src=e,t.defer=t.type="text/javascript",a.getElementsByTagName("head")[0].appendChild(t)}for(o=Array("flag","emoji"),t.supports={everything:!0,everythingExceptFlag:!0},r=0;r<o.length;r++)t.supports[o[r]]=function(e){if(p&&p.fillText)switch(p.textBaseline="top",p.font="600 32px Arial",e){case"flag":return s("\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!s("\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!s("\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!s("\ud83e\udef1\ud83c\udffb\u200d\ud83e\udef2\ud83c\udfff","\ud83e\udef1\ud83c\udffb\u200b\ud83e\udef2\ud83c\udfff")}return!1}(o[r]),t.supports.everything=t.supports.everything&&t.supports[o[r]],"flag"!==o[r]&&(t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&t.supports[o[r]]);t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&!t.supports.flag,t.DOMReady=!1,t.readyCallback=function(){t.DOMReady=!0},t.supports.everything||(n=function(){t.readyCallback()},a.addEventListener?(a.addEventListener("DOMContentLoaded",n,!1),e.addEventListener("load",n,!1)):(e.attachEvent("onload",n),a.attachEvent("onreadystatechange",function(){"complete"===a.readyState&&t.readyCallback()})),(e=t.source||{}).concatemoji?c(e.concatemoji):e.wpemoji&&e.twemoji&&(c(e.twemoji),c(e.wpemoji)))}(window,document,window._wpemojiSettings);
</script><script src="https://kvrkarthik.com/wp-includes/js/wp-emoji-release.min.js?ver=6.2.3" type="text/javascript" defer=""></script>
<style>
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 0.07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link rel="stylesheet" id="bdt-uikit-css" href="https://kvrkarthik.com/wp-content/plugins/bdthemes-element-pack-lite/assets/css/bdt-uikit.css?ver=3.13.1" media="all">
<link rel="stylesheet" id="ep-helper-css" href="https://kvrkarthik.com/wp-content/plugins/bdthemes-element-pack-lite/assets/css/ep-helper.css?ver=5.1.3" media="all">
<link rel="stylesheet" id="bae-main-css" href="https://kvrkarthik.com/wp-content/plugins/document-embedder-addons-for-elementor/admin/assets/css/main.css?ver=6.2.3" media="all">
<link rel="stylesheet" id="wp-block-library-css" href="https://kvrkarthik.com/wp-includes/css/dist/block-library/style.min.css?ver=6.2.3" media="all">
<link rel="stylesheet" id="classic-theme-styles-css" href="https://kvrkarthik.com/wp-includes/css/classic-themes.min.css?ver=6.2.3" media="all">
<style id="global-styles-inline-css">
body{--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--duotone--dark-grayscale: url('#wp-duotone-dark-grayscale');--wp--preset--duotone--grayscale: url('#wp-duotone-grayscale');--wp--preset--duotone--purple-yellow: url('#wp-duotone-purple-yellow');--wp--preset--duotone--blue-red: url('#wp-duotone-blue-red');--wp--preset--duotone--midnight: url('#wp-duotone-midnight');--wp--preset--duotone--magenta-yellow: url('#wp-duotone-magenta-yellow');--wp--preset--duotone--purple-green: url('#wp-duotone-purple-green');--wp--preset--duotone--blue-orange: url('#wp-duotone-blue-orange');--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}body .is-layout-flow > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-flow > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-flow > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-constrained > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-constrained > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull)){max-width: var(--wp--style--global--content-size);margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignwide{max-width: var(--wp--style--global--wide-size);}body .is-layout-flex{display: flex;}body .is-layout-flex{flex-wrap: wrap;align-items: center;}body .is-layout-flex > *{margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
.wp-block-navigation a:where(:not(.wp-element-button)){color: inherit;}
:where(.wp-block-columns.is-layout-flex){gap: 2em;}
.wp-block-pullquote{font-size: 1.5em;line-height: 1.6;}
</style>
<link rel="stylesheet" id="menu-image-css" href="https://kvrkarthik.com/wp-content/plugins/menu-image/includes/css/menu-image.css?ver=3.10" media="all">
<link rel="stylesheet" id="dashicons-css" href="https://kvrkarthik.com/wp-includes/css/dashicons.min.css?ver=6.2.3" media="all">
<link rel="stylesheet" id="NbConvert-css" href="https://kvrkarthik.com/wp-content/plugins/nbconvert/css/nbconvert.css?ver=6.2.3" media="all">
<link rel="stylesheet" id="pafe-extension-style-free-css" href="https://kvrkarthik.com/wp-content/plugins/piotnet-addons-for-elementor/assets/css/minify/extension.min.css?ver=2.4.23" media="all">
<link rel="stylesheet" id="hello-elementor-css" href="https://kvrkarthik.com/wp-content/themes/hello-elementor/style.min.css?ver=2.8.0" media="all">
<link rel="stylesheet" id="hello-elementor-theme-style-css" href="https://kvrkarthik.com/wp-content/themes/hello-elementor/theme.min.css?ver=2.8.0" media="all">
<link rel="stylesheet" id="font-awesome-official-css" href="https://use.fontawesome.com/releases/v6.4.2/css/all.css" media="all" integrity="sha384-blOohCVdhjmtROpu8+CfTnUWham9nkX7P7OZQMst+RUnhtoY/9qemFAkIKOYxDI3" crossorigin="anonymous">
<link rel="stylesheet" id="elementor-icons-css" href="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/eicons/css/elementor-icons.min.css?ver=5.20.0" media="all">
<link rel="stylesheet" id="elementor-frontend-css" href="https://kvrkarthik.com/wp-content/plugins/elementor/assets/css/frontend-lite.min.css?ver=3.14.1" media="all">
<style id="elementor-frontend-inline-css">
.elementor-kit-4{--e-global-color-primary:#6EC1E4;--e-global-color-secondary:#54595F;--e-global-color-text:#7A7A7A;--e-global-color-2e6c5c0:#9FCE00;--e-global-color-58831fa:#44749D;--e-global-color-335a431:#373737;--e-global-color-b74c51b:#EFDECD;--e-global-color-20056cc:#F4F4F4;--e-global-color-7f5bc58:#068A97;--e-global-typography-primary-font-family:"Roboto";--e-global-typography-primary-font-weight:600;--e-global-typography-secondary-font-family:"Roboto Slab";--e-global-typography-secondary-font-weight:400;--e-global-typography-text-font-family:"Roboto";--e-global-typography-text-font-weight:400;--e-global-typography-accent-font-family:"Roboto";--e-global-typography-accent-font-weight:500;--e-global-typography-417d3d5-font-family:"Montserrat";--e-global-typography-417d3d5-font-size:48px;--e-global-typography-417d3d5-font-weight:600;--e-global-typography-417d3d5-text-transform:none;--e-global-typography-1337d5f-font-family:"Open Sans";--e-global-typography-1337d5f-font-size:36px;--e-global-typography-1337d5f-font-weight:600;--e-global-typography-01b754f-font-family:"Poppins";--e-global-typography-01b754f-font-size:20px;--e-global-typography-01b754f-font-weight:400;--e-global-typography-c33ed96-font-family:"Poppins";--e-global-typography-c33ed96-font-size:16px;--e-global-typography-c33ed96-font-weight:400;--e-global-typography-57f8d6f-font-family:"Montserrat";--e-global-typography-57f8d6f-font-size:16px;--e-global-typography-57f8d6f-font-weight:500;}.elementor-section.elementor-section-boxed > .elementor-container{max-width:1500px;}.e-con{--container-max-width:1500px;}.elementor-widget:not(:last-child){margin-bottom:20px;}.elementor-element{--widgets-spacing:20px;}{}h1.entry-title{display:var(--page-title-display);}.site-header .header-inner{width:1500px;max-width:100%;}.site-header{padding-inline-end:50px;padding-inline-start:50px;background-color:var( --e-global-color-58831fa );}.site-header .site-branding .site-logo img{width:22%;max-width:22%;}.site-header .site-navigation ul.menu li a{color:var( --e-global-color-20056cc );}.site-header .site-navigation-toggle i{color:var( --e-global-color-20056cc );}.site-header .site-navigation .menu li{font-family:var( --e-global-typography-c33ed96-font-family ), Sans-serif;font-size:var( --e-global-typography-c33ed96-font-size );font-weight:var( --e-global-typography-c33ed96-font-weight );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}.site-footer .footer-inner{width:1500px;max-width:100%;}.site-footer{background-color:var( --e-global-color-58831fa );}.site-footer .site-branding .site-logo img{width:60px;max-width:60px;}footer .footer-inner .site-navigation a{color:var( --e-global-color-20056cc );font-family:var( --e-global-typography-c33ed96-font-family ), Sans-serif;font-size:var( --e-global-typography-c33ed96-font-size );font-weight:var( --e-global-typography-c33ed96-font-weight );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}.site-footer .copyright p{color:var( --e-global-color-20056cc );font-family:var( --e-global-typography-c33ed96-font-family ), Sans-serif;font-size:var( --e-global-typography-c33ed96-font-size );font-weight:var( --e-global-typography-c33ed96-font-weight );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}@media(max-width:1024px){.elementor-section.elementor-section-boxed > .elementor-container{max-width:1024px;}.e-con{--container-max-width:1024px;}.site-header .site-navigation .menu li{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}footer .footer-inner .site-navigation a{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}.site-footer .copyright p{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}}@media(max-width:767px){.elementor-section.elementor-section-boxed > .elementor-container{max-width:767px;}.e-con{--container-max-width:767px;}.site-header .site-navigation .menu li{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}footer .footer-inner .site-navigation a{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}.site-footer .copyright p{font-size:var( --e-global-typography-c33ed96-font-size );line-height:var( --e-global-typography-c33ed96-line-height );letter-spacing:var( --e-global-typography-c33ed96-letter-spacing );word-spacing:var( --e-global-typography-c33ed96-word-spacing );}}
.elementor-3545 .elementor-element.elementor-element-cca3ade > .elementor-widget-container{margin:0px 0px 0px 0px;padding:0px 0px 0px 0px;}.elementor-3545 .elementor-element.elementor-element-cca3ade{width:var( --container-widget-width, 100.202% );max-width:100.202%;--container-widget-width:100.202%;--container-widget-flex-grow:0;}
</style>
<link rel="stylesheet" id="swiper-css" href="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/swiper/css/swiper.min.css?ver=5.3.6" media="all">
<link rel="stylesheet" id="font-awesome-5-all-css" href="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/font-awesome/css/all.min.css?ver=3.14.1" media="all">
<link rel="stylesheet" id="font-awesome-4-shim-css" href="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/font-awesome/css/v4-shims.min.css?ver=3.14.1" media="all">
<link rel="stylesheet" id="font-awesome-official-v4shim-css" href="https://use.fontawesome.com/releases/v6.4.2/css/v4-shims.css" media="all" integrity="sha384-IqMDcR2qh8kGcGdRrxwop5R2GiUY5h8aDR/LhYxPYiXh3sAAGGDkFvFqWgFvTsTd" crossorigin="anonymous">
<link rel="stylesheet" id="google-fonts-1-css" href="https://fonts.googleapis.com/css?family=Roboto%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CRoboto+Slab%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CMontserrat%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7COpen+Sans%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CPoppins%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic&amp;display=swap&amp;ver=6.2.3" media="all">
<link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin=""><script src="https://kvrkarthik.com/wp-includes/js/jquery/jquery.min.js?ver=3.6.4" id="jquery-core-js"></script>
<script src="https://kvrkarthik.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.0" id="jquery-migrate-js"></script>
<script src="https://kvrkarthik.com/wp-content/plugins/piotnet-addons-for-elementor/assets/js/minify/extension.min.js?ver=2.4.23" id="pafe-extension-free-js"></script>
<script src="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/font-awesome/js/v4-shims.min.js?ver=3.14.1" id="font-awesome-4-shim-js"></script>
<link rel="https://api.w.org/" href="https://kvrkarthik.com/wp-json/"><link rel="alternate" type="application/json" href="https://kvrkarthik.com/wp-json/wp/v2/posts/3545"><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://kvrkarthik.com/xmlrpc.php?rsd">
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://kvrkarthik.com/wp-includes/wlwmanifest.xml">
<meta name="generator" content="WordPress 6.2.3">
<link rel="canonical" href="https://kvrkarthik.com/marketing-insights-of-codex/">
<link rel="shortlink" href="https://kvrkarthik.com/?p=3545">
<link rel="alternate" type="application/json+oembed" href="https://kvrkarthik.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fkvrkarthik.com%2Fmarketing-insights-of-codex%2F">
<link rel="alternate" type="text/xml+oembed" href="https://kvrkarthik.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fkvrkarthik.com%2Fmarketing-insights-of-codex%2F&amp;format=xml">
<meta name="generator" content="Elementor 3.14.1; features: e_dom_optimization, e_optimized_assets_loading, e_optimized_css_loading, a11y_improvements, additional_custom_breakpoints; settings: css_print_method-internal, google_font-enabled, font_display-swap">
<link rel="icon" href="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg" sizes="32x32">
<link rel="icon" href="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg" sizes="192x192">
<link rel="apple-touch-icon" href="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg">
<meta name="msapplication-TileImage" content="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg">
		<style id="wp-custom-css">
			************** Jupyter Notebook CSS ************************/

div .dataframe {
  border:none;
  margin: 0 auto;
}
div.output_stdout pre {
  max-height:300px;
}

div.output_stderr pre
{
  background: #fdd;
  margin:0;
  max-height:300px;
}
div.hl-ipython3 pre {
  margin:0
}
.dataframe thead tr:only-child th {
  text-align: right;
  text-transform: capitalize;
}
.dataframe thead th {
  text-align: left;
}
.dataframe tbody tr th {
  vertical-align: top;
}

.rendered_html tbody tr:nth-child(odd),
.rendered_html tbody tr:nth-child(odd) td {
  background: #f5f5f5;
}
.rendered_html tr, .rendered_html th, .rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
div.highlight .kn, .n, .k, .nn, .s1, .ow, .p, .mi, .c, .mf, .nb, .kc, .sd, .nf {
  font-family: monospace;
  font-size:14px;
}
.input_prompt {
  color: #303F9F;
  font-weight: bold;
  float: left;
  margin-right: 5px;
  margin-top: 3px;
}
.input_area pre {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
  padding: 6px 3px 6px 6px;
}
.output_prompt{
  color:#cc0000;
  font-weight: bold;
}
.prompt{
  font-family: monospace;
  font-size: 14px;
}
.c, c1 {
  color: #408080;
  font-style: italic;
}
.k {
  color: #338822;
  font-weight: bold;
}
.kn {
  color: #338822;
  font-weight: bold;
}
.mi {
  color: #008800;
}
.mf {
  color: #008800;
}
.o {
  color: #9966ff;
}
.ow {
  color: #BA22FF;
  font-weight: bold;
}
.nb {
  color: #338822;
}
.n {
  color: #000000;
}
.s, .s1, .sd, .s2 {
  color: #cc2222;
}
.se {
  color: #cc2222;
  font-weight: bold;
}
.si {
  color: #C06688;
  font-weight: bold;
}
.nn {
  color: #4D00FF;
  font-weight: bold;
}
.output_area pre {
  background-color: #FFFFFF;
  padding-left: 5%;
}
.code_cell {
  padding-left: 1%;
}
.cell {
  margin-top: 10px;
  margin-bottom: 10px;
}
br {
  line-height: 2;
}
blockquote {
  font-size: 1em;
  text-align: left;
  font-weight: normal;
}
code {
  border: none;
  box-shadow: none;
  font-family: monospace;
}
div.rendered_html h1, h2, h3, h4 {
  margin-top: 30px;
  margin-bottom: 10px;
}
div.rendered_html p a {
  color: #4D00FF;
}		</style>
		<style>@import url(https://fonts.googleapis.com/css?family=Outfit);</style><style>/* FONT FAMILYS */
@font-face {
  font-family: "Trump Mediaeval Bold";
  font-weight: 900;
  src: local("Trump Mediaeval"), url(https://kvrkarthik.com/74413b127a87627a8fce.otf) format("opentype");
}

@font-face {
  font-family: "Trump Mediaeval Roman";
  src: local("Trump Mediaeval"), url(https://kvrkarthik.com/223f2af263aa0473b893.otf) format("opentype");
}
/* FONT FAMILIES END */

/* Hover state styling for buttons with a white svg icon  */
.wisdolia-white-icon-button:hover svg path {
  fill: #f7e1c6;
}

.wisdolia-white-icon-button:hover p {
  color: #f7e1c6;
}

/* Hover state styling for buttons with a white svg icon  */
.wisdolia-icon-button-hover-styling:hover svg path {
  fill: #434744;
}

.wisdolia-icon-button-hover-styling:hover p {
  color: #434744;
}

.wisdolia-secondary-action-button-hover-styling svg path {
  fill: rgba(106, 107, 106, 1);
}
/* Hover state styling for buttons with a white svg icon  */
.wisdolia-secondary-action-button-hover-styling:hover:enabled svg path {
  fill: #515251;
}
.wisdolia-secondary-action-button-hover-styling:hover:enabled svg g path {
  fill: black;
}

.wisdolia-secondary-action-button-hover-styling:hover:enabled p {
  color: #515251;
}
</style><style type="text/css">@keyframes spinners-react-infinity{0%{stroke-dasharray:1,347;stroke-dashoffset:75}25%,75%{stroke-dasharray:17,330}50%{stroke-dasharray:1,347}to{stroke-dasharray:1,347;stroke-dashoffset:423}}</style><style data-styled="active" data-styled-version="5.3.8"></style></head>
<body class="post-template-default single single-post postid-3545 single-format-standard wp-custom-logo elementor-default elementor-template-full-width elementor-kit-4 elementor-page elementor-page-3545 e--ua-blink e--ua-chrome e--ua-webkit chakra-ui-light" data-elementor-device-mode="mobile" cz-shortcut-listen="true">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-dark-grayscale"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0 0.49803921568627"></feFuncR><feFuncG type="table" tableValues="0 0.49803921568627"></feFuncG><feFuncB type="table" tableValues="0 0.49803921568627"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-grayscale"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0 1"></feFuncR><feFuncG type="table" tableValues="0 1"></feFuncG><feFuncB type="table" tableValues="0 1"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-purple-yellow"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0.54901960784314 0.98823529411765"></feFuncR><feFuncG type="table" tableValues="0 1"></feFuncG><feFuncB type="table" tableValues="0.71764705882353 0.25490196078431"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-blue-red"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0 1"></feFuncR><feFuncG type="table" tableValues="0 0.27843137254902"></feFuncG><feFuncB type="table" tableValues="0.5921568627451 0.27843137254902"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-midnight"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0 0"></feFuncR><feFuncG type="table" tableValues="0 0.64705882352941"></feFuncG><feFuncB type="table" tableValues="0 1"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-magenta-yellow"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0.78039215686275 1"></feFuncR><feFuncG type="table" tableValues="0 0.94901960784314"></feFuncG><feFuncB type="table" tableValues="0.35294117647059 0.47058823529412"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-purple-green"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0.65098039215686 0.40392156862745"></feFuncR><feFuncG type="table" tableValues="0 1"></feFuncG><feFuncB type="table" tableValues="0.44705882352941 0.4"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 0 0" width="0" height="0" focusable="false" role="none" style="visibility: hidden; position: absolute; left: -9999px; overflow: hidden;"><defs><filter id="wp-duotone-blue-orange"><feColorMatrix color-interpolation-filters="sRGB" type="matrix" values=" .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 .299 .587 .114 0 0 "></feColorMatrix><feComponentTransfer color-interpolation-filters="sRGB"><feFuncR type="table" tableValues="0.098039215686275 1"></feFuncR><feFuncG type="table" tableValues="0 0.66274509803922"></feFuncG><feFuncB type="table" tableValues="0.84705882352941 0.41960784313725"></feFuncB><feFuncA type="table" tableValues="1 1"></feFuncA></feComponentTransfer><feComposite in2="SourceGraphic" operator="in"></feComposite></filter></defs></svg>
<a class="skip-link screen-reader-text" href="#content">Skip to content</a>

<header id="site-header" class="site-header dynamic-header menu-dropdown-mobile" role="banner">
	<div class="header-inner">
		<div class="site-branding show-logo">
							<div class="site-logo show">
					<a href="https://kvrkarthik.com/" class="custom-logo-link" rel="home"><img width="888" height="799" src="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg" class="custom-logo" alt="" decoding="async"></a>				</div>
					</div>

					<nav class="site-navigation show">
				<div class="menu-main-menu-container"><ul id="menu-main-menu" class="menu"><li id="menu-item-2236" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home menu-item-2236"><a href="https://kvrkarthik.com/">Home</a></li>
<li id="menu-item-2235" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2235"><a href="https://kvrkarthik.com/about-me/">About Me</a></li>
<li id="menu-item-3509" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-3509"><a href="https://kvrkarthik.com/projects/">Blog</a></li>
</ul></div>			</nav>
			<div class="site-navigation-toggle-holder show">
				<div class="site-navigation-toggle" role="button" tabindex="0">
					<i class="eicon-menu-bar" aria-hidden="true"></i>
					<span class="screen-reader-text">Menu</span>
				</div>
			</div>
			<nav class="site-navigation-dropdown show">
				<div class="menu-main-menu-container"><ul id="menu-main-menu" class="menu"><li id="menu-item-2236" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home menu-item-2236"><a href="https://kvrkarthik.com/">Home</a></li>
<li id="menu-item-2235" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-2235"><a href="https://kvrkarthik.com/about-me/">About Me</a></li>
<li id="menu-item-3509" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-3509"><a href="https://kvrkarthik.com/projects/">Blog</a></li>
</ul></div>			</nav>
			</div>
</header>
		<div data-elementor-type="wp-post" data-elementor-id="3545" class="elementor elementor-3545">
									<section class="elementor-section elementor-top-section elementor-element elementor-element-36c9de4 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="36c9de4" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-13576df" data-id="13576df" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
								<div class="elementor-element elementor-element-7efa93d elementor-widget elementor-widget-text-editor" data-id="7efa93d" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
			<style>/*! elementor - v3.14.0 - 26-06-2023 */
.elementor-widget-text-editor.elementor-drop-cap-view-stacked .elementor-drop-cap{background-color:#69727d;color:#fff}.elementor-widget-text-editor.elementor-drop-cap-view-framed .elementor-drop-cap{color:#69727d;border:3px solid;background-color:transparent}.elementor-widget-text-editor:not(.elementor-drop-cap-view-default) .elementor-drop-cap{margin-top:8px}.elementor-widget-text-editor:not(.elementor-drop-cap-view-default) .elementor-drop-cap-letter{width:1em;height:1em}.elementor-widget-text-editor .elementor-drop-cap{float:left;text-align:center;line-height:1;font-size:50px}.elementor-widget-text-editor .elementor-drop-cap-letter{display:inline-block}</style>				<h2 style="text-align: center;">Marketing Insights of CodeX in Indian Market</h2><p>Do you regularly feel tired, drowsy, or easily drained after physical activities? What you do in these scenarios? Do you consider having an energy drink to improve the situation?</p><p>While you think about it, let me introduce you about the project I recently worked on which is related to this. This project is provided by <a href="https://codebasics.io/">Codebasics.io</a>. I thank Mr. Dhaval Patel and the Codebasics team for providing this opportunity. So, let’s get started.</p><h4>Context</h4><p><strong>CodeX</strong> is a company from Germany that makes drinks. They want to make their mark in India too. They started selling their energy drink in 10 Indian cities. They did a survey in these cities to find out if people like their brand. They got 10,000 responses to their survey questions.</p><h4 style="text-align: left;">Problem Statement</h4><p>As a Marketing Data Analyst the task is to convert these survey results to meaningful insights which can help the team with data driven business decisions.</p><p>Responsible for analysing and increasing:</p><ul><li>Brand awareness.</li><li>Market share.</li><li>Product development.</li><li>Insights to be communicated to the CEO of the company.</li></ul><h4>Data Description</h4><p>The data obtained is from three files:</p><p><strong>City</strong> – Details about the city.<br><strong>Respondents</strong> – Demographic details of the respondents.<br><strong>Survey Responses</strong> – Responses from the participants for the marketing survey questions.</p><p>After combining these our data has 10000 rows, 29 columns.</p><ul><li>Response_ID</li><li>Consume_frequency</li><li>Consume_time</li><li>Consume_reason</li><li>Heard_before</li><li>Brand_perception</li><li>General_perception</li><li>Tried_before</li><li>Taste_experience</li><li>Reasons_preventing_trying</li><li>Current_brands</li><li>Reasons_for_choosing_brands</li><li>Improvements_desired</li><li>Ingredients_expected</li><li>Health_concerns</li><li>Interest_in_natural_or_organic</li><li>Marketing_channels</li><li>Packaging_preference</li><li>Limited_edition_packaging</li><li>Price_range</li><li>Purchase_location</li><li>Typical_consumption_situations</li></ul><p>A sample of the survey questionnaire can be found <a href="https://github.com/karthik-44/MarketingInsightsFoodnBeverage/blob/main/Survey_Questions_and_Response_Options.pdf">here</a>.</p><h4>Data Cleaning</h4><p>A bit of data cleaning is necessary while doing analysis related to our brand. The reason for this is:</p><p><strong>For brand, logo, design:</strong><br>We should not consider the responses where people told that they haven’t heard about our brand but they prefer us.<br>Because they might not be aware of the design and logo.</p><p><strong>For product taste experience:</strong><br>We should consider the responses of people who have heard about us and tasted the product.<br>Because the responses from the people who haven’t tasted the product doesn’t make sense. For example, the rating given by someone who didn’t taste our energy drink doesn’t make sense as they might give just 1 or even high 5.</p><p><strong>For preference:</strong><br>For this we need to avoid the responses where people prefer our brand but have not heard about us<br>Because to improve our product we need to identity the responses where people who actually know us.</p><p>The analysis is done in the following order:</p><ul><li>Data Hierarchy</li><li>Present Situation</li><li>Demographic Insights</li><li>Consumer Preference</li><li>Competitors</li><li>Marketing Channels</li><li>Brand Penetration</li><li>Purchase Behavior</li><li>Product Development</li></ul>						</div>
				</div>
					</div>
		</div>
							</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-b328431 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="b328431" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-20079ae" data-id="20079ae" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
								<div class="elementor-element elementor-element-cca3ade elementor-widget__width-initial elementor-widget elementor-widget-text-editor" data-id="cca3ade" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
							<h4>Data Hierarchy</h4>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe width="800" height="500" frameborder="0" src="//plotly.com/~plotly_k/5.embed" scrolling="yes" class="iframe-class"></iframe>
<p><strong>Tier 1:</strong> <br>Bangalore, Chennai, Delhi, Hyderabad, Mumbai</p><p><strong>Tier 2:</strong> <br>Ahmedabad, Jaipur, Kolkata, Lucknow, Pune.</p><p><strong>Major Brands:</strong> <br>Cola-Coka, Bepsi, Gangster, Blue Bull, CodeX, Sky9</p><h4>Current Situation</h4>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/3.embed" scrolling="yes" class="iframe-class"></iframe>
<p>From this chart we can see that we are in the 5th position and less than 10% of people prefer our drink.</p><h4>Demographic Insights</h4><p><strong>Gender based</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/7.embed" scrolling="yes" class="iframe-class"></iframe>
<p>From this chart, we can see that all sections of gender have a preference for energy drink.<br>We have a sample of data where Males are in higher proportion who prefers to have energy drink.</p><p><strong>Age based</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/11.embed" scrolling="yes" class="iframe-class"></iframe>
<p>This plot suggests that energy drinks are popular in the age group of 19-30.<br>After that the energy drink preference reduces.<br>Youth (15-30) preference is higher.</p><p><strong>Popular Marketing Channel in Youth</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/13.embed" scrolling="yes" class="iframe-class"></iframe>
<p>As the data suggests, the best way to reach out is through Online ads followed by TV Commercials.</p><h4>Consumer Preference</h4><p><strong>Based on Ingredients</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="600" frameborder="0" src="//plotly.com/~plotly_k/15.embed" scrolling="yes" class="iframe-class"></iframe>
<p>This plot suggests that Caffeine and Vitamins are important ingredients and lots of people prefer to have organic ingredients with reduced sugar content.</p><p><strong>Based on Packaging</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="550" frameborder="0" src="//plotly.com/~plotly_k/17.embed" scrolling="yes" class="iframe-class"></iframe>
<p>This chart suggests Compact and portable cans are preferred better. This makes sense assuming youth and adults are busy with their colleges, work, gym, drive and prefer to have a handy design.</p><p>Limited Edition packaging might not a important contributing factor at present for the product development, but once we have a better product it can help. Lots of respondents didn’t consider Eco-friendly design (but its better to have this) along with the above.</p><h4>Competitors</h4><p><strong>Major Competitors</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/19.embed" scrolling="yes" class="iframe-class"></iframe>
<p>Cola-Coka and Bepsi are the leaders in terms of people’s preference.<br>Let us see why people prefer them.</p><p><strong>Customer Reasons for choosing</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="550" frameborder="0" src="//plotly.com/~plotly_k/21.embed" scrolling="yes" class="iframe-class"></iframe>
<p>Brand reputation and Taste/flavor preference are the top reasons people choose them.<br>This suggests improvement in the product taste is necessary.</p><h4>Marketing Channels</h4>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="400" height="550" src="//plotly.com/~plotly_k/23.embed" scrolling="yes" class="iframe-class" frameborder="0"></iframe>
<p>The digital media – Online ads and TV Commercials are top advertising channels.<br>In terms of marketing we are following the trend.</p>						</div>
				</div>
					</div>
		</div>
							</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-f395b0b elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="f395b0b" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-a16203d" data-id="a16203d" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
								<div class="elementor-element elementor-element-0c10704 elementor-widget elementor-widget-text-editor" data-id="0c10704" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
							<h4>Brand Penetration</h4><p><strong>Brand logo, design</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="400" frameborder="0" src="//plotly.com/~plotly_k/25.embed" scrolling="yes" class="iframe-class"></iframe>
<p>From this chart, majority are neutral to our brand.<br>It is clear that we have to improve the brand logo, design as it is one of the major factor for the product.</p><p><strong>Product taste experience</strong></p><p>In this star based rating system, values of 1, 2, 3, 4, 5 means poor, below average, average, good, excellent respectively.</p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" src="https://kvrkarthik.com/jupyter_notebooks/5_brandtaste.html" width="100%" height="715px" style="border:50px;" scrolling="yes" class="iframe-class" frameborder="0"></iframe>
<p>We have lot of 3 star ratings, a good number of 4 and 5 star ratings as well.<br>We should focus on increasing the taste quality of the product.</p><p><strong>CodeX preference in each city</strong></p>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="715" frameborder="0" src="https://kvrkarthik.com/jupyter_notebooks/5_brands_city.html" scrolling="yes" class="iframe-class"></iframe>
<p>This heatmap represents in each city how the people prefer a particular brand.<br>A higher shade of blue means the preference is better.<br>A higher shade of red indicates the preference is lower.<br>This suggests, we have to improve our product and we should focus of improvement should be more in Lucknow, Jaipur, Kolkata.</p><h4>Purchase Behavior</h4>
<!-- iframe plugin v.4.5 wordpress.org/plugins/iframe/ -->
<iframe loading="lazy" width="900" height="630" frameborder="0" src="//plotly.com/~plotly_k/31.embed" scrolling="yes" class="iframe-class"></iframe>
<p>This chart suggests that many people purchases energy drinks at supermarkets and top consumption situations are sports/exercise, to stay awake or focused.<br>So we have to ensure our product’s availability at not only supermarkets but also at gyms and fitness centers.<br>It is good to see that people are willing to pay more for the product that they think is better.</p><h4>Product Development&nbsp;</h4><p>The immediate improvements would be to improve the taste of the product, then improve the branding name, logo or design.<br>Once the above have been done we can focus to increase the availability of the product.<br>Regarding price we can start in the higher end of 50-99 range and once we are getting proper sales in most places we can raise the price to 100-150 range as people are willing to spend in that range.<br>Another strategy would be to change the price of the product depending on the demand and location of the product.<br>Once we improve upon our product taste we can give either BOGO offers, at least we have to try that in the cities where the performance is too bad (Lucknow, Jaipur).<br>Our major target group should be people who belongs to age group of 15 to 30, because as per our survey many people who responded belongs to this category who feel its not Dangerous to consume the energy drinks.<br>For choosing a brand ambassador for the product, a sports athlete who is admired by the youth age group will be a better option as per the survey analysis.</p>						</div>
				</div>
					</div>
		</div>
							</div>
		</section>
							</div>
		<footer id="site-footer" class="site-footer dynamic-footer footer-stacked footer-has-copyright" role="contentinfo">
	<div class="footer-inner">
		<div class="site-branding show-logo">
							<div class="site-logo show">
					<a href="https://kvrkarthik.com/" class="custom-logo-link" rel="home"><img width="888" height="799" src="https://kvrkarthik.com/wp-content/uploads/2021/11/kvrk_logo.svg" class="custom-logo" alt="" decoding="async"></a>				</div>
					</div>

					<nav class="site-navigation show">
				<div class="menu-social-container"><ul id="menu-social" class="menu"><li id="menu-item-3327" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3327"><a href="https://www.linkedin.com/in/vkanna01/"><span class="menu-image-title-hide menu-image-title">LinkedIn</span><span class="dashicons dashicons-linkedin hide-menu-image-icons"></span></a></li>
<li id="menu-item-3328" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-3328"><a href="https://github.com/karthik-44/" class="menu-image-title-hide menu-image-not-hovered"><span class="menu-image-title-hide menu-image-title">Github</span><img width="24" height="24" src="https://kvrkarthik.com/wp-content/uploads/2023/08/github-mark-white-24x24.png" class="menu-image menu-image-title-hide" alt="" decoding="async" loading="lazy"></a></li>
</ul></div>			</nav>
		
					<div class="copyright show">
				<p>©2023 kvrkarthik
</p>
			</div>
			</div>
</footer>

<script src="https://kvrkarthik.com/wp-content/themes/hello-elementor/assets/js/hello-frontend.min.js?ver=1.0.0" id="hello-theme-frontend-js"></script>
<script id="bdt-uikit-js-extra">
var element_pack_ajax_login_config = {"ajaxurl":"https:\/\/kvrkarthik.com\/wp-admin\/admin-ajax.php","language":"en","loadingmessage":"Sending user info, please wait...","unknownerror":"Unknown error, make sure access is correct!"};
var ElementPackConfig = {"ajaxurl":"https:\/\/kvrkarthik.com\/wp-admin\/admin-ajax.php","nonce":"b8c558d613","data_table":{"language":{"lengthMenu":"Show _MENU_ Entries","info":"Showing _START_ to _END_ of _TOTAL_ entries","search":"Search :","paginate":{"previous":"Previous","next":"Next"}}},"contact_form":{"sending_msg":"Sending message please wait...","captcha_nd":"Invisible captcha not defined!","captcha_nr":"Could not get invisible captcha response!"},"mailchimp":{"subscribing":"Subscribing you please wait..."},"elements_data":{"sections":[],"columns":[],"widgets":[]}};
</script>
<script src="https://kvrkarthik.com/wp-content/plugins/bdthemes-element-pack-lite/assets/js/bdt-uikit.min.js?ver=3.13.1" id="bdt-uikit-js"></script>
<script src="https://kvrkarthik.com/wp-content/plugins/elementor/assets/js/webpack.runtime.min.js?ver=3.14.1" id="elementor-webpack-runtime-js"></script>
<script src="https://kvrkarthik.com/wp-content/plugins/elementor/assets/js/frontend-modules.min.js?ver=3.14.1" id="elementor-frontend-modules-js"></script>
<script src="https://kvrkarthik.com/wp-content/plugins/elementor/assets/lib/waypoints/waypoints.min.js?ver=4.0.2" id="elementor-waypoints-js"></script>
<script src="https://kvrkarthik.com/wp-includes/js/jquery/ui/core.min.js?ver=1.13.2" id="jquery-ui-core-js"></script>
<script id="elementor-frontend-js-before">
var elementorFrontendConfig = {"environmentMode":{"edit":false,"wpPreview":false,"isScriptDebug":false},"i18n":{"shareOnFacebook":"Share on Facebook","shareOnTwitter":"Share on Twitter","pinIt":"Pin it","download":"Download","downloadImage":"Download image","fullscreen":"Fullscreen","zoom":"Zoom","share":"Share","playVideo":"Play Video","previous":"Previous","next":"Next","close":"Close","a11yCarouselWrapperAriaLabel":"Carousel | Horizontal scrolling: Arrow Left & Right","a11yCarouselPrevSlideMessage":"Previous slide","a11yCarouselNextSlideMessage":"Next slide","a11yCarouselFirstSlideMessage":"This is the first slide","a11yCarouselLastSlideMessage":"This is the last slide","a11yCarouselPaginationBulletMessage":"Go to slide"},"is_rtl":false,"breakpoints":{"xs":0,"sm":480,"md":768,"lg":1025,"xl":1440,"xxl":1600},"responsive":{"breakpoints":{"mobile":{"label":"Mobile Portrait","value":767,"default_value":767,"direction":"max","is_enabled":true},"mobile_extra":{"label":"Mobile Landscape","value":880,"default_value":880,"direction":"max","is_enabled":false},"tablet":{"label":"Tablet Portrait","value":1024,"default_value":1024,"direction":"max","is_enabled":true},"tablet_extra":{"label":"Tablet Landscape","value":1200,"default_value":1200,"direction":"max","is_enabled":false},"laptop":{"label":"Laptop","value":1366,"default_value":1366,"direction":"max","is_enabled":false},"widescreen":{"label":"Widescreen","value":2400,"default_value":2400,"direction":"min","is_enabled":false}}},"version":"3.14.1","is_static":false,"experimentalFeatures":{"e_dom_optimization":true,"e_optimized_assets_loading":true,"e_optimized_css_loading":true,"a11y_improvements":true,"additional_custom_breakpoints":true,"hello-theme-header-footer":true,"landing-pages":true},"urls":{"assets":"https:\/\/kvrkarthik.com\/wp-content\/plugins\/elementor\/assets\/"},"swiperClass":"swiper-container","settings":{"page":[],"editorPreferences":[]},"kit":{"active_breakpoints":["viewport_mobile","viewport_tablet"],"global_image_lightbox":"yes","lightbox_enable_counter":"yes","lightbox_enable_fullscreen":"yes","lightbox_enable_zoom":"yes","lightbox_enable_share":"yes","lightbox_title_src":"title","lightbox_description_src":"description","hello_header_logo_type":"logo","hello_header_menu_layout":"horizontal","hello_footer_logo_type":"logo"},"post":{"id":3545,"title":"Marketing%20Insights%20of%20CodeX","excerpt":"","featuredImage":"https:\/\/kvrkarthik.com\/wp-content\/uploads\/2023\/08\/juice-box-carton-25189-702x1024.png"}};
</script>
<script src="https://kvrkarthik.com/wp-content/plugins/elementor/assets/js/frontend.min.js?ver=3.14.1" id="elementor-frontend-js"></script><span id="elementor-device-mode" class="elementor-screen-only"></span>
<script src="https://kvrkarthik.com/wp-content/plugins/bdthemes-element-pack-lite/assets/js/common/helper.min.js?ver=5.1.3" id="element-pack-helper-js"></script>
<script src="https://kvrkarthik.com/wp-includes/js/underscore.min.js?ver=1.13.4" id="underscore-js"></script>
<script id="wp-util-js-extra">
var _wpUtilSettings = {"ajax":{"url":"\/wp-admin\/admin-ajax.php"}};
</script>
<script src="https://kvrkarthik.com/wp-includes/js/wp-util.min.js?ver=6.2.3" id="wp-util-js"></script>
<script id="wpforms-elementor-js-extra">
var wpformsElementorVars = {"captcha_provider":"recaptcha","recaptcha_type":"v2"};
</script>
<script src="https://kvrkarthik.com/wp-content/plugins/wpforms-lite/assets/js/integrations/elementor/frontend.min.js?ver=1.8.2.1" id="wpforms-elementor-js"></script>
<div data-pafe-ajax-url="https://kvrkarthik.com/wp-admin/admin-ajax.php"></div>


<div class="chakra-portal"><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-top" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; margin: 0px auto; top: env(safe-area-inset-top, 0px); right: env(safe-area-inset-right, 0px); left: env(safe-area-inset-left, 0px);"></div><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-top-left" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; top: env(safe-area-inset-top, 0px); left: env(safe-area-inset-left, 0px);"></div><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-top-right" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; top: env(safe-area-inset-top, 0px); right: env(safe-area-inset-right, 0px);"></div><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-bottom-left" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; bottom: env(safe-area-inset-bottom, 0px); left: env(safe-area-inset-left, 0px);"></div><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-bottom" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; margin: 0px auto; bottom: env(safe-area-inset-bottom, 0px); right: env(safe-area-inset-right, 0px); left: env(safe-area-inset-left, 0px);"></div><div role="region" aria-live="polite" aria-label="Notifications" id="chakra-toast-manager-bottom-right" style="position: fixed; z-index: var(--toast-z-index, 5500); pointer-events: none; display: flex; flex-direction: column; bottom: env(safe-area-inset-bottom, 0px); right: env(safe-area-inset-right, 0px);"></div></div><scribe-shadow id="crxjs-ext" style="position: fixed; width: 0px; height: 0px; top: 0px; left: 0px; z-index: 2147483647; overflow: visible;"></scribe-shadow><div></div><div id="general-snackbar-root"></div></body><div><div></div></div><div id="simplifyJobsContainer" style="position: absolute; top: 0px; left: 0px; width: 0px; height: 0px; overflow: visible; z-index: 2147483647;"><span></span></div></html>
```
