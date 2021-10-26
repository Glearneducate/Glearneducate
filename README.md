
<!DOCTYPE html>
<html lang="en" class="clickfunnels-com wf-proximanova-i4-active wf-proximanova-i7-active wf-proximanova-n4-active wf-proximanova-n7-active wf-active bgRepeat wf-proximanova-i3-active wf-proximanova-n3-active elFont_lato wf-proximanovasoft-n4-active wf-proximanovasoft-n7-active wf-proximasoft-n4-active wf-proximasoft-i4-active wf-proximasoft-i6-active wf-proximasoft-n6-active wf-proximasoft-i7-active wf-proximasoft-n7-active js-focus-visible avcHn2VQJenBvoR5hilPG " style="overflow: initial; background-color: rgb(255, 255, 255);">
<head data-next-url="" data-this-url="https://easy.12minuteaffiliate.com/main">
<meta charset="UTF-8">
<script>window.NREUM||(NREUM={});NREUM.info={"beacon":"bam-cell.nr-data.net","errorBeacon":"bam-cell.nr-data.net","licenseKey":"NRJS-fc902efb332119fff33","applicationID":"367981416","transactionName":"dFZWTENWVQ9QExdNRlJLSFlWXEpMRQBfXUYYSU1aXVBKC1AF","queueTime":0,"applicationTime":1174,"agent":""}</script>
<script>(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam-cell.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={licenseKey:"NRJS-fc902efb332119fff33",applicationID:"367981416"};window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var i=e[n]={exports:{}};t[n][0].call(i.exports,function(e){var i=t[n][1][e];return r(i||e)},i,i.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var i=0;i<n.length;i++)r(n[i]);return r}({1:[function(t,e,n){function r(){}function i(t,e,n){return function(){return o(t,[u.now()].concat(f(arguments)),e?null:this,n),e?void 0:this}}var o=t("handle"),a=t(8),f=t(9),c=t("ee").get("tracer"),u=t("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var d=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],p="api-",l=p+"ixn-";a(d,function(t,e){s[e]=i(p+e,!0,"api")}),s.addPageAction=i(p+"addPageAction",!0),s.setCurrentRouteName=i(p+"routeName",!0),e.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(t,e){var n={},r=this,i="function"==typeof e;return o(l+"tracer",[u.now(),t,n],r),function(){if(c.emit((i?"":"no-")+"fn-start",[u.now(),r,i],n),i)try{return e.apply(this,arguments)}catch(t){throw c.emit("fn-err",[arguments,this,t],n),t}finally{c.emit("fn-end",[u.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(t,e){m[e]=i(l+e)}),newrelic.noticeError=function(t,e){"string"==typeof t&&(t=new Error(t)),o("err",[t,u.now(),!1,e])}},{}],2:[function(t,e,n){function r(t){if(NREUM.init){for(var e=NREUM.init,n=t.split("."),r=0;r<n.length-1;r++)if(e=e[n[r]],"object"!=typeof e)return;return e=e[n[n.length-1]]}}e.exports={getConfiguration:r}},{}],3:[function(t,e,n){function r(){return f.exists&&performance.now?Math.round(performance.now()):(o=Math.max((new Date).getTime(),o))-a}function i(){return o}var o=(new Date).getTime(),a=o,f=t(10);e.exports=r,e.exports.offset=a,e.exports.getLastTimestamp=i},{}],4:[function(t,e,n){function r(t){return!(!t||!t.protocol||"file:"===t.protocol)}e.exports=r},{}],5:[function(t,e,n){function r(t,e){var n=t.getEntries();n.forEach(function(t){"first-paint"===t.name?d("timing",["fp",Math.floor(t.startTime)]):"first-contentful-paint"===t.name&&d("timing",["fcp",Math.floor(t.startTime)])})}function i(t,e){var n=t.getEntries();n.length>0&&d("lcp",[n[n.length-1]])}function o(t){t.getEntries().forEach(function(t){t.hadRecentInput||d("cls",[t])})}function a(t){if(t instanceof m&&!g){var e=Math.round(t.timeStamp),n={type:t.type};e<=p.now()?n.fid=p.now()-e:e>p.offset&&e<=Date.now()?(e-=p.offset,n.fid=p.now()-e):e=p.now(),g=!0,d("timing",["fi",e,n])}}function f(t){"hidden"===t&&d("pageHide",[p.now()])}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var c,u,s,d=t("handle"),p=t("loader"),l=t(7),m=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){c=new PerformanceObserver(r);try{c.observe({entryTypes:["paint"]})}catch(v){}u=new PerformanceObserver(i);try{u.observe({entryTypes:["largest-contentful-paint"]})}catch(v){}s=new PerformanceObserver(o);try{s.observe({type:"layout-shift",buffered:!0})}catch(v){}}if("addEventListener"in document){var g=!1,h=["click","keydown","mousedown","pointerdown","touchstart"];h.forEach(function(t){document.addEventListener(t,a,!1)})}l(f)}},{}],6:[function(t,e,n){function r(t,e){if(!i)return!1;if(t!==i)return!1;if(!e)return!0;if(!o)return!1;for(var n=o.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var i=null,o=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var f=navigator.userAgent,c=f.match(a);c&&f.indexOf("Chrome")===-1&&f.indexOf("Chromium")===-1&&(i="Safari",o=c[1])}e.exports={agent:i,version:o,match:r}},{}],7:[function(t,e,n){function r(t){function e(){t(a&&document[a]?document[a]:document[i]?"hidden":"visible")}"addEventListener"in document&&o&&document.addEventListener(o,e,!1)}e.exports=r;var i,o,a;"undefined"!=typeof document.hidden?(i="hidden",o="visibilitychange",a="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",o="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",o="webkitvisibilitychange",a="webkitVisibilityState")},{}],8:[function(t,e,n){function r(t,e){var n=[],r="",o=0;for(r in t)i.call(t,r)&&(n[o]=e(r,t[r]),o+=1);return n}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],9:[function(t,e,n){function r(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,i=n-e||0,o=Array(i<0?0:i);++r<i;)o[r]=t[e+r];return o}e.exports=r},{}],10:[function(t,e,n){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(t,e,n){function r(){}function i(t){function e(t){return t&&t instanceof r?t:t?u(t,c,a):a()}function n(n,r,i,o,a){if(a!==!1&&(a=!0),!l.aborted||o){t&&a&&t(n,r,i);for(var f=e(i),c=v(n),u=c.length,s=0;s<u;s++)c[s].apply(f,r);var p=d[w[n]];return p&&p.push([b,n,r,f]),f}}function o(t,e){y[t]=v(t).concat(e)}function m(t,e){var n=y[t];if(n)for(var r=0;r<n.length;r++)n[r]===e&&n.splice(r,1)}function v(t){return y[t]||[]}function g(t){return p[t]=p[t]||i(n)}function h(t,e){l.aborted||s(t,function(t,n){e=e||"feature",w[n]=e,e in d||(d[e]=[])})}var y={},w={},b={on:o,addEventListener:o,removeEventListener:m,emit:n,get:g,listeners:v,context:e,buffer:h,abort:f,aborted:!1};return b}function o(t){return u(t,c,a)}function a(){return new r}function f(){(d.api||d.feature)&&(l.aborted=!0,d=l.backlog={})}var c="nr@context",u=t("gos"),s=t(8),d={},p={},l=e.exports=i();e.exports.getOrSetContext=o,l.backlog=d},{}],gos:[function(t,e,n){function r(t,e,n){if(i.call(t,e))return t[e];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:r,writable:!0,enumerable:!1}),r}catch(o){}return t[e]=r,r}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(t,e,n){function r(t,e,n,r){i.buffer([t],r),i.emit(t,e,n)}var i=t("ee").get("handle");e.exports=r,r.ee=i},{}],id:[function(t,e,n){function r(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:a(t,o,function(){return i++})}var i=1,o="nr@id",a=t("gos");e.exports=r},{}],loader:[function(t,e,n){function r(){if(!R++){var t=M.info=NREUM.info,e=v.getElementsByTagName("script")[0];if(setTimeout(u.abort,3e4),!(t&&t.licenseKey&&t.applicationID&&e))return u.abort();c(E,function(e,n){t[e]||(t[e]=n)});var n=a();f("mark",["onload",n+M.offset],null,"api"),f("timing",["load",n]);var r=v.createElement("script");0===t.agent.indexOf("http://")||0===t.agent.indexOf("https://")?r.src=t.agent:r.src=l+"://"+t.agent,e.parentNode.insertBefore(r,e)}}function i(){"complete"===v.readyState&&o()}function o(){f("mark",["domContent",a()+M.offset],null,"api")}var a=t(3),f=t("handle"),c=t(8),u=t("ee"),s=t(6),d=t(4),p=t(2),l=p.getConfiguration("ssl")===!1?"http":"https",m=window,v=m.document,g="addEventListener",h="attachEvent",y=m.XMLHttpRequest,w=y&&y.prototype,b=!d(m.location);NREUM.o={ST:setTimeout,SI:m.setImmediate,CT:clearTimeout,XHR:y,REQ:m.Request,EV:m.Event,PR:m.Promise,MO:m.MutationObserver};var x=""+location,E={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1211.min.js"},O=y&&w&&w[g]&&!/CriOS/.test(navigator.userAgent),M=e.exports={offset:a.getLastTimestamp(),now:a,origin:x,features:{},xhrWrappable:O,userAgent:s,disabled:b};if(!b){t(1),t(5),v[g]?(v[g]("DOMContentLoaded",o,!1),m[g]("load",r,!1)):(v[h]("onreadystatechange",i),m[h]("onload",r)),f("mark",["firstbyte",a.getLastTimestamp()],null,"api");var R=0}},{}],"wrap-function":[function(t,e,n){function r(t,e){function n(e,n,r,c,u){function nrWrapper(){var o,a,s,p;try{a=this,o=d(arguments),s="function"==typeof r?r(o,a):r||{}}catch(l){i([l,"",[o,a,c],s],t)}f(n+"start",[o,a,c],s,u);try{return p=e.apply(a,o)}catch(m){throw f(n+"err",[o,a,m],s,u),m}finally{f(n+"end",[o,a,p],s,u)}}return a(e)?e:(n||(n=""),nrWrapper[p]=e,o(e,nrWrapper,t),nrWrapper)}function r(t,e,r,i,o){r||(r="");var f,c,u,s="-"===r.charAt(0);for(u=0;u<e.length;u++)c=e[u],f=t[c],a(f)||(t[c]=n(f,s?c+r:r,i,c,o))}function f(n,r,o,a){if(!m||e){var f=m;m=!0;try{t.emit(n,r,o,e,a)}catch(c){i([c,n,r,o],t)}m=f}}return t||(t=s),n.inPlace=r,n.flag=p,n}function i(t,e){e||(e=s);try{e.emit("internal-error",t)}catch(n){}}function o(t,e,n){if(Object.defineProperty&&Object.keys)try{var r=Object.keys(t);return r.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(o){i([o],n)}for(var a in t)l.call(t,a)&&(e[a]=t[a]);return e}function a(t){return!(t&&t instanceof Function&&t.apply&&!t[p])}function f(t,e){var n=e(t);return n[p]=t,o(t,n,s),n}function c(t,e,n){var r=t[e];t[e]=f(r,n)}function u(){for(var t=arguments.length,e=new Array(t),n=0;n<t;++n)e[n]=arguments[n];return e}var s=t("ee"),d=t(9),p="nr@original",l=Object.prototype.hasOwnProperty,m=!1;e.exports=r,e.exports.wrapFunction=f,e.exports.wrapInPlace=c,e.exports.argsToArray=u},{}]},{},["loader"]);</script>
<meta content="text/html;charset=utf-8" http-equiv="Content-Type">
<meta content="utf-8" http-equiv="encoding">
<meta name="viewport" content="initial-scale=1">
<title>12 Minute Affiliate (With Sleep-Sales Technology)</title>
<meta class="metaTagTop" name="description" content="The World's #1 Easiest Affiliate Marketing System">
<meta class="metaTagTop" name="keywords" content="12 Minute Affiliate, Affiliate Marketing">
<meta class="metaTagTop" name="author" content="Devon Brown">
<meta class="metaTagTop" property="og:image" content="" id="social-image">
<meta property="og:title" content="12 Minute Affiliate (With Sleep-Sales Technology)">
<meta property="og:description" content="The World's #1 Easiest Affiliate Marketing System">
<meta property="og:url" content="https://easy.12minuteaffiliate.com/main">
<meta property="og:type" content="website">
<link rel="stylesheet" media="screen" href="//easy.12minuteaffiliate.com/assets/lander.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.9.0/css/all.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.9.0/css/v4-shims.css">
<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700%7COswald:400,700%7CDroid+Sans:400,700%7CRoboto:400,700%7CLato:400,700%7CPT+Sans:400,700%7CSource+Sans+Pro:400,600,700%7CNoto+Sans:400,700%7CPT+Sans:400,700%7CUbuntu:400,700%7CBitter:400,700%7CPT+Serif:400,700%7CRokkitt:400,700%7CDroid+Serif:400,700%7CRaleway:400,700%7CInconsolata:400,700" rel="stylesheet" type="text/css">
<meta property="cf:funnel_id" content="UEhIZXU4d3hJaEQwNGJLQm03bzhTZz09LS1lMnZPalFOM2RwODVQOTRtcjdIa3FRPT0=--a0786029f48e452e4ddf583e132c8c2fca6038f6">
<meta property="cf:page_id" content="YzJQQkpNVC9VK2F4akdyM0xydjNIUT09LS1qTno0WlcwNk04Nk5MNlpsZ1g3bFpBPT0=--33521b12435edd3af736ab9f1358e7de31516308">
<meta property="cf:funnel_step_id" content="MTFPdkRlOHR0Z010Uk0wUHdENVNXUT09LS1TaFk0MEVqYXk4amVSSlBsT3YyOVlBPT0=--54992bf2c922041a42727afe57365d8615a26da4">
<meta property="cf:user_id" content="aS9Rbmx1WHJiOEx1anJNbVNsVmJFdz09LS1QQmJoSG9DeDVYMEtVa3NYVU4wQ0RBPT0=--249d9950c97082e45fe312c34044a49e25402b48">
<meta property="cf:account_id" content="MHlQMGhxN0RPbjRzdjlncWNESG1SZz09LS05NS9MSEgydHlnWTIrazNtTzcwaDBRPT0=--03cfb2c13a7a799579d98df0ce3bd3f0f23ac192">
<meta property="cf:page_code" content="NDQ4OTE4OTU=">
<meta property="cf:mode_id" content="1">
<meta property="cf:time_zone" content="UTC">
<meta property="cf:app_domain" content="app.clickfunnels.com">
<script src="//easy.12minuteaffiliate.com/assets/userevents/application.js"></script>
<style>
    [data-timed-style='fade']{display:none}[data-timed-style='scale']{display:none}
  </style>
<link rel='icon' type='image/png' href='https://esev2.s3.amazonaws.com/images/12minaffclock.png'></link>
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-P79RNGH');</script>


<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '379561523122070');
  fbq('init', '269642074569720');
  fbq('init', '217520045575309');
  fbq('init', '613135099843888');
  fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
  src="https://www.facebook.com/tr?id=379561523122070&ev=PageView&noscript=1"
/></noscript>

<script src='https://cbtb.clickbank.net/?vendor=easiest123'></script><script>window.onload=function() {   document.getElementById('cfAR').onsubmit=function(e) {      e.preventDefault();     var formData = {                                    email:document.getElementById('cf_contact_email').value,       								name: document.getElementById('cf_contact_name').value,                                    listname:55,                                    eseid:"",                                    accountId: "274066",                                    listId: "none",                                    mailChimp: "3b3868d7b0",                                    form: "none"                                };                        $.ajax({                                url: "https://www.easiestsystemever.com/api/go/autoresponder",                                data: formData,                                type: 'POST',                                success: function(data){                                //$('form:first').submit();                                console.log(data.status);                                if (data.status == "success"){                                    console.log('you go');                                    document.getElementById("cfAR").submit();                                }                            }                        });   } }</script>
<script>!function () { if (window.t4hto4) console.log("WiserNotify pixel installed multiple time in this page"); else { window.t4hto4 = !0; var t = document, e = window, n = function () { var e = t.createElement("script"); e.type = "text/javascript", e.async = !0, e.src = "https://pt.wisernotify.com/pixel.js?ti=6e21rkhqgpktd", document.body.appendChild(e) }; "complete" === t.readyState ? n() : window.attachEvent ? e.attachEvent("onload", n) : e.addEventListener("load", n, !1) } }();</script>
</head>
<body data-affiliate-param="affiliate_id" data-show-progress="true">
<svg xmlns="http://www.w3.org/2000/svg" style="display: none !important">
<filter id="grayscale">
<fecolormatrix type="matrix" values="0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0"></fecolormatrix>
</filter>
</svg>
<div class="containerWrapper">
<textarea id="tracking-body-top" style="display: none !important"></textarea>
<input id="submit-form-action" value="redirect-url" data-url="#" data-ar-service="API" data-ar-list="12MASleepSalesOptins" data-webhook="" type="hidden" wtx-context="6457BBDF-C4D7-4826-AB70-9AD8BB490883" data-ar-list-id="5830507,awlist5830507">
<div class="nodoHiddenFormFields hide">
<input id="elHidden1" class="elInputHidden elInput" name="ad" type="hidden" wtx-context="D78C1B4C-0930-4B12-86D2-1B13A90C7E8D">
<input id="elHidden2" class="elInputHidden elInput" name="tag" type="hidden" wtx-context="59DDF6A7-AC10-4FF9-88CB-A3B1F34E3808">
<input id="elHidden3" class="elInputHidden elInput" name="" type="hidden" wtx-context="230A9F76-FFEB-4DDC-867F-ECCFF95F56EE">
<input id="elHidden4" class="elInputHidden elInput" name="" type="hidden" wtx-context="01FD0AAE-D0EF-49AD-8B6D-491EEDBDB189">
<input id="elHidden5" class="elInputHidden elInput" name="" type="hidden" wtx-context="424C0A16-2E96-4807-A93A-B2B98D31792E">
</div>
<div class="nodoCustomHTML hide"></div>
<div class="modalBackdropWrapper" style="background-color: rgba(0, 0, 0, 0.4); height: 100%; display: none;"></div>
<div class="container containerModal midContainer noTopMargin padding40-top padding40-bottom padding40H borderSolid cornersAll radius10 shadow0 bgNoRepeat emptySection borderLight border5px noBounce" id="modalPopup" data-title="Modal" data-block-color="0074C7" style="margin-top: 15px; padding-top: 15px; padding-bottom: 10px; border-color: rgb(28, 28, 28); outline: none; position: fixed; background-color: rgb(13, 55, 95); display: none;" data-trigger="none" data-animate="top" data-delay="0">
<div class="containerInner ui-sortable" style="">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--11067" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px; outline: none;" data-hide-on="desktop">
<div id="col-full-163" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-44251" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 48px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b><u>STEP 1:</u> GET STARTED RISK FREE!</b></h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--29547" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 0px; margin: 0px; outline: none;" data-hide-on="desktop">
<div id="col-left-122" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-44149" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/d8/53b18e8d104106a82e78537463b26a/12--Minute-Box-Render.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-165" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-25061" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 18px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"> <b>Enter Your First Name &amp; Best Email Below, </b><div><b>Then Click The "Continue" Button!</b></div>
</h2>
</div>
<div class="de elInputWrapper de-input-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_input-83167-137" data-de-type="input" data-de-editing="false" data-title="input" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" type="first_name" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<input type="first_name" placeholder="Your First Name Here..." name="first_name" class="elInput elInput100 elAlign_left elInputMid elInputStyl0 elInputBG1 elInputBR5 elInputI0 elInputIBlack elInputIRight ceoinput required1" data-type="extra" wtx-context="1E83FEA1-3DB8-494A-8F42-EDA1B5B5B9C8">
</div>
<div class="de elInputWrapper de-input-block elAlign_center elMargin0 ui-droppable de-editable" id="input-97042-123" data-de-type="input" data-de-editing="false" data-title="input" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" type="email" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<input type="email" placeholder="Your Best Email Address Here..." name="email" class="elInput elInput100 elAlign_left elInputMid elInputStyl0 elInputBG1 elInputBR5 elInputI0 elInputIBlack elInputIRight ceoinput required1" data-type="extra" wtx-context="02F24AF9-AB34-4C9A-839C-41AA6168A1BE">
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-69735-131" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#submit-form" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elBtnHP_25 elBTN_b_1 elButtonShadowN1 elButtonTxtColor1 elButtonCorner10 mfs_30" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 24px;" rel="noopener noreferrer" id="undefined-1009">
<span class="elButtonMain">CONTINUE TO NEXT STEP &gt;&gt;</span>
<span class="elButtonSub"></span>
</a>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98385" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 0px; padding-bottom: 20px; margin: 0px; outline: none;" data-hide-on="desktop">
<div id="col-full-128" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-47719" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 15px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">YES!! I'm ready to test-drive  the 12 Minute Affiliate System <i>(with Sleep-Sales Technology)</i> for a full 14 days for just $9.95.  I understand that I'm locking in my 76% DISCOUNT, and will pay only <strike>$197/month</strike> $47/month thereafter!
  I understand that I can ca<span style="font-family: inherit;">ncel at any time, and that I get a FREE VACATION just for giving the system an honest try!</span>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39432-146" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 0px; padding-bottom: 10px; margin: 0px auto; outline: none; width: 90%; max-width: 100%;" data-hide-on="mobile">
<div id="col-full-148-101" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-83583-152" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One" data-hide-on="">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 36px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b><u>STEP 1:</u> GET STARTED </b></h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39432-140-157" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone - Clone" style="padding-top: 0px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 85%; max-width: 100%;" data-hide-on="mobile">
<div id="col-full-148-127-144" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-22848-145" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_16" style="text-align: center; font-size: 18px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"> <b>Enter Your First Name &amp; Best Email Below Then Click  "Continue"</b>
</h2>
</div>
<div class="de elInputWrapper de-input-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_input-83167-137-119" data-de-type="input" data-de-editing="false" data-title="input" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" type="first_name" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<input type="first_name" placeholder="Your First Name Here..." name="first_name" class="elInput elInput100 elAlign_left elInputMid elInputStyl0 elInputBG1 elInputBR5 elInputI0 elInputIBlack elInputIRight ceoinput required1" data-type="extra" style="font-size: 14px;" wtx-context="D4FB5F7E-0C89-441D-A60C-74A2C35D0A2D">
</div>
<div class="de elInputWrapper de-input-block elAlign_center elMargin0 ui-droppable de-editable" id="input-97042-123-176" data-de-type="input" data-de-editing="false" data-title="input" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" type="email" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<input type="email" placeholder="Your Best Email Address Here..." name="email" class="elInput elInput100 elAlign_left elInputMid elInputStyl0 elInputBG1 elInputBR5 elInputI0 elInputIBlack elInputIRight ceoinput required1" data-type="extra" style="font-size: 14px;" wtx-context="51447FDF-9C95-43E4-AD6B-16E561086E9A">
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-69735-131-100" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#submit-form" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elBtnHP_25 elBTN_b_1 elButtonShadowN1 elButtonTxtColor1 elButtonCorner10 mfs_34" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 34px;" rel="noopener noreferrer" id="undefined-1009-622">
<span class="elButtonMain">CONTINUE &gt;&gt;</span>
<span class="elButtonSub"></span>
</a>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--95268-109" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 0px; padding-bottom: 0px; margin: 0px; outline: none;" data-hide-on="mobile">
<div id="col-left-104-142" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-95280" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 13px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>YES!</b> I'm ready to try the 1<i><b>2 Minute Affiliate System (with Sleep-Sales Technology)</b></i> for a full 14 days for just $9.95, lock in my 76% DISCOUNT,  and pay only <strike>$197/month </strike> $47/month thereafter!</h2>
</div>
</div>
</div>
<div id="col-right-158-108" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
</div>
<div class="closeLPModal"><img src="https://assets.clickfunnels.com/images/closemodal.png" alt=""></div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<style id="bold_style_tmp_headline1-90167">#tmp_headline1-90167 .elHeadline b{color:rgb(230,51,51);}</style>
<style id="button_style_tmp_button-94931">#tmp_button-94931 .elButtonFlat:hover{background-color:#0564a9!important;}#tmp_button-94931 .elButtonBottomBorder:hover{background-color:#0564a9!important;}#tmp_button-94931 .elButtonSubtle:hover{background-color:#0564a9!important;}#tmp_button-94931 .elButtonGradient{background-image:-webkit-gradient(linear,left top,left bottom,color-stop(0,rgb(6,124,209)),color-stop(1,#0564a9));background-image:-o-linear-gradient(bottom,rgb(6,124,209) 0%,#0564a9 100%);background-image:-moz-linear-gradient(bottom,rgb(6,124,209) 0%,#0564a9 100%);background-image:-webkit-linear-gradient(bottom,rgb(6,124,209) 0%,#0564a9 100%);background-image:-ms-linear-gradient(bottom,rgb(6,124,209) 0%,#0564a9 100%);background-image:linear-gradient(to bottom,rgb(6,124,209) 0%,#0564a9 100%);}#tmp_button-94931 .elButtonGradient:hover{background-image:-webkit-gradient(linear,left top,left bottom,color-stop(1,rgb(6,124,209)),color-stop(0,#0564a9));background-image:-o-linear-gradient(bottom,rgb(6,124,209) 100%,#0564a9 0%);background-image:-moz-linear-gradient(bottom,rgb(6,124,209) 100%,#0564a9 0%);background-image:-webkit-linear-gradient(bottom,rgb(6,124,209) 100%,#0564a9 0%);background-image:-ms-linear-gradient(bottom,rgb(6,124,209) 100%,#0564a9 0%);background-image:linear-gradient(to bottom,rgb(6,124,209) 100%,#0564a9 0%);}#tmp_button-94931 .elButtonBorder{border:3px solid rgb(6,124,209)!important;color:rgb(6,124,209)!important;}#tmp_button-94931 .elButtonBorder:hover{background-color:rgb(6,124,209)!important;color:#FFF!important;}</style>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H borderSolid border3px cornersAll radius0 shadow0 emptySection noBorder bgCover101" id="container-96056" data-title="Section" data-block-color="0074C7" style='padding-top: 20px; padding-bottom: 75px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/ab/ecc07374424b78b74c16cc057a4543/hero-bg-blue.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row-164" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding: 5px 0px 20px; margin: 0px; outline: none;" col-array="3,9">
<div id="col-left-182-180" class="innerContent col_left ui-resizable col-md-3" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de elImageWrapper de-image-block elMargin0 ui-droppable elAlign_left de-editable" id="tmp_image-98023-138" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/e2/307840e79911e89c65696d4197a49d/12min-logo.png" class="elIMG ximg imgGrey0" alt="" width="175">
</div></div></div>
<div id="col-right-153-127" class="innerContent col_right ui-resizable col-md-9" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-33678-136" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: right; font-size: 23px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<a href="#open-popup" id="link-3238-435" class="" target="_self" rel="noopener noreferrer" style="color: rgb(238, 238, 238);">SIGN UP</a>  |  <a href="https://www.12minuteaffiliate.com/signin" id="link-1179-465" class="" target="_self" rel="noopener noreferrer" style="color: rgb(238, 238, 238);">LOG IN</a>
</div>
</div></div></div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--38202" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-full-104" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-21669" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; background-color: rgba(66, 185, 159, 0); font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 60px; color: rgb(255, 255, 255); background-color: rgba(66, 185, 159, 0);" data-bold="inherit" data-gramm="false" contenteditable="false">Breakthrough Software Uses Proprietary "<b><u>Sleep-Sales Technology</u></b>" To Generate Sales While You’re Tucked Comfortably In Bed.</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-37994" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 23px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">No  Experience  -  No Technical Skills  -   No Hosting  -  &amp; No Product Creation Required</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--55765" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 0px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 75%; max-width: 100%;">
<div id="col-left-109" class="innerContent col_left ui-resizable col-md-1" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de eliconelementWrapper ui-droppable de-editable" id="tmp_iconelement-45623" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(255, 227, 0); text-align: center; font-size: 50px; line-height: 1em; display: block;">
<i class=" fas fa-arrow-down"></i>
</a>
</div>
</div>
</div>
<div id="col-center-152" class="innerContent col_right ui-resizable col-md-10" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-94785" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-htype="content">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow2" style="text-align: center; color: rgb(255, 255, 255); font-size: 32px;" data-bold="inherit" data-gramm="false" data-opacity="1" contenteditable="false"><font color="#2d2d2d"><b>Click The Play Button Below To Find Out More</b></font></h2>
</div>
</div>
</div>
<div id="col-right-110" class="innerContent col_right ui-resizable col-md-1" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de eliconelementWrapper ui-droppable de-editable" id="iconelement-52014" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(255, 227, 0); text-align: left; font-size: 50px; line-height: 1em; display: block;" id="undefined-983">
<i class=" fas fa-arrow-down"></i>
</a>
</div></div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover101" id="row--71914" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style='padding: 15px 100px 85px; margin: 0px auto; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/88/ba2f551e1043e78bcac1cbcf1f1a07/macbookfront_1768x1070.png"); width: 100%; max-width: 100%;'>
<div id="col-full-141" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elMargin0 ui-droppable padding0 elVideoWidth100 hiddenElementTools de-editable" id="tmp_video-64932" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="scale" data-delay="500" data-video-type="custom" style="outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false" data-youtube-autoplay="yes" data-youtube-controls="no" data-youtube-branding="no" data-vimeo-autoplay="no" data-vimeo-url="https://vimeo.com/317166953" data-vimeo-unmute-label="true">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo" style="display: none;">
<script src="https://fast.wistia.com/embed/medias/0f6xpclr5t.jsonp" async=""></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async=""></script><div class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_0f6xpclr5t videoFoam=true wistia_embed_initialized" style="height:100%;position:relative;width:100%" id="wistia-0f6xpclr5t-1">
<div class="wistia_swatch" style="height: 100%; left: 0px; opacity: 1; overflow: hidden; position: absolute; top: 0px; transition: opacity 200ms ease 0s; width: 100%;"><img src="https://fast.wistia.com/embed/medias/0f6xpclr5t/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;"></div>
<div id="wistia_chrome_41" class="w-chrome" tabindex="-1" style="display: inline-block; height: 100%; line-height: normal; margin: 0px; padding: 0px; position: relative; vertical-align: top; width: 100%; zoom: 1; outline: none; overflow: hidden; box-sizing: content-box;"><div id="wistia_grid_66_wrapper" style="display: block;">
<div id="wistia_grid_66_above"></div>
<div id="wistia_grid_66_main">
<div id="wistia_grid_66_behind"></div>
<div id="wistia_grid_66_center">
<div class="w-video-wrapper w-css-reset" style="clip: rect(0px, 0px, 0px, 0px); height: 100%; position: absolute; top: 0px; width: 100%; opacity: 1; background-color: rgb(0, 0, 0);"></div>
<div class="w-ui-container" style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%; opacity: 1;"></div>
</div>
<div id="wistia_grid_66_front"></div>
<div id="wistia_grid_66_top_inside"><div id="wistia_grid_66_top"></div></div>
<div id="wistia_grid_66_bottom_inside"><div id="wistia_grid_66_bottom"></div></div>
<div id="wistia_grid_66_left_inside"><div id="wistia_grid_66_left"></div></div>
<div id="wistia_grid_66_right_inside"><div id="wistia_grid_66_right"></div></div>
</div>
<div id="wistia_grid_66_below"></div>
<style id="wistia_67_style" type="text/css" class="wistia_injected_style">#wistia_grid_66_wrapper{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box;font-family:Arial,sans-serif;font-size:14px;height:100%;position:relative;text-align:left;width:100%;}
#wistia_grid_66_wrapper *{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box;}
#wistia_grid_66_above{position:relative;}
#wistia_grid_66_main{display:block;height:100%;position:relative;}
#wistia_grid_66_behind{height:100%;left:0;position:absolute;top:0;width:100%;}
#wistia_grid_66_center{height:100%;overflow:hidden;position:relative;width:100%;}
#wistia_grid_66_front{display:none;height:100%;left:0;position:absolute;top:0;width:100%;}
#wistia_grid_66_top_inside{position:absolute;left:0;top:0;width:100%;}
#wistia_grid_66_top{width:100%;position:absolute;bottom:0;left:0;}
#wistia_grid_66_bottom_inside{position:absolute;left:0;bottom:0;width:100%;}
#wistia_grid_66_bottom{width:100%;position:absolute;top:0;left:0;}
#wistia_grid_66_left_inside{height:100%;position:absolute;left:0;top:0;}
#wistia_grid_66_left{height:100%;position:absolute;right:0;top:0;}
#wistia_grid_66_right_inside{height:100%;right:0;position:absolute;top:0;}
#wistia_grid_66_right{height:100%;left:0;position:absolute;top:0;}
#wistia_grid_66_below{position:relative;}</style>
</div></div>
</div></div></div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H borderSolid border3px cornersAll radius0 shadow0 emptySection noBorder containerWithVisibleOverflow bgNoRepeat" id="container-96056-103" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 20px; padding-bottom: 75px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/ab/ecc07374424b78b74c16cc057a4543/hero-bg-blue.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row-164-104" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding: 5px 0px 20px; margin: 0px; outline: none;" col-array="3,9">
<div id="col-left-182-180-104" class="innerContent col_left ui-resizable col-md-3" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de elImageWrapper de-image-block elMargin0 ui-droppable elAlign_left de-editable" id="tmp_image-98023-138-105" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/e2/307840e79911e89c65696d4197a49d/12min-logo.png" class="elIMG ximg imgGrey0" alt="" width="175">
</div></div></div>
<div id="col-right-153-127-162" class="innerContent col_right ui-resizable col-md-9" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-33678-136-143" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 23px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<a href="#open-popup" id="link-3238-435-604" class="" target="_self" rel="noopener noreferrer" style="color: rgb(238, 238, 238);">SIGN UP</a>  |  <a href="https://www.12minuteaffiliate.com/signin" id="link-1179-465-982" class="" target="_self" rel="noopener noreferrer" style="color: rgb(238, 238, 238);">LOG IN</a>
</div>
</div></div></div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--38202-167" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-full-104-144" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-21669-127" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; background-color: rgba(66, 185, 159, 0); font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255); background-color: rgba(66, 185, 159, 0);" data-bold="inherit" data-gramm="false" contenteditable="false">Breakthrough Software Uses Proprietary "<b><u>Sleep-Sales Technology</u></b>" To Generate Sales While You’re Tucked Comfortably In Bed.</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-37994-161" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 23px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">No  Experience  -  No Technical Skills  -   No Hosting  -  &amp; No Product Creation Required</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-94785-117" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false" data-htype="content">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow2" style="text-align: center; color: rgb(255, 255, 255); font-size: 25px;" data-bold="inherit" data-gramm="false" data-opacity="1" contenteditable="false"><font color="#2d2d2d"><b>Click The Play Button Below To Find Out More</b></font></h2>
</div>
</div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover101" id="row--71914-128" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style='padding: 0px 0px 10px; margin: 0px auto; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/88/ba2f551e1043e78bcac1cbcf1f1a07/macbookfront_1768x1070.png"); width: 100%; max-width: 100%;'>
<div id="col-full-141-147" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elMargin0 ui-droppable elVideoWidth100 padding20 de-editable" id="tmp_video-64932-107" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="scale" data-delay="500" data-video-type="custom" style="outline: none; margin-top: -12px; cursor: pointer;" data-element-theme="customized" aria-disabled="false" data-youtube-autoplay="yes" data-youtube-controls="no" data-youtube-branding="no" data-vimeo-autoplay="no" data-vimeo-url="https://vimeo.com/317166953" data-vimeo-unmute-label="true">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo" style="display: none;">
<script src="https://fast.wistia.com/embed/medias/0f6xpclr5t.jsonp" async=""></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async=""></script><div class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_0f6xpclr5t videoFoam=true wistia_embed_initialized" style="height:100%;position:relative;width:100%" id="wistia-0f6xpclr5t-2">
<div class="wistia_swatch" style="height: 100%; left: 0px; opacity: 1; overflow: hidden; position: absolute; top: 0px; transition: opacity 200ms ease 0s; width: 100%;"><img src="https://fast.wistia.com/embed/medias/0f6xpclr5t/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;"></div>
<div id="wistia_chrome_44" class="w-chrome" tabindex="-1" style="display: inline-block; height: 100%; line-height: normal; margin: 0px; padding: 0px; position: relative; vertical-align: top; width: 100%; zoom: 1; outline: none; overflow: hidden; box-sizing: content-box;"><div id="wistia_grid_61_wrapper" style="display: block;">
<div id="wistia_grid_61_above"></div>
<div id="wistia_grid_61_main">
<div id="wistia_grid_61_behind"></div>
<div id="wistia_grid_61_center">
<div class="w-video-wrapper w-css-reset" style="clip: rect(0px, 0px, 0px, 0px); height: 100%; position: absolute; top: 0px; width: 100%; opacity: 1; background-color: rgb(0, 0, 0);"></div>
<div class="w-ui-container" style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%; opacity: 1;"></div>
</div>
<div id="wistia_grid_61_front"></div>
<div id="wistia_grid_61_top_inside"><div id="wistia_grid_61_top"></div></div>
<div id="wistia_grid_61_bottom_inside"><div id="wistia_grid_61_bottom"></div></div>
<div id="wistia_grid_61_left_inside"><div id="wistia_grid_61_left"></div></div>
<div id="wistia_grid_61_right_inside"><div id="wistia_grid_61_right"></div></div>
</div>
<div id="wistia_grid_61_below"></div>
<style id="wistia_62_style" type="text/css" class="wistia_injected_style">#wistia_grid_61_wrapper{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box;font-family:Arial,sans-serif;font-size:14px;height:100%;position:relative;text-align:left;width:100%;}
#wistia_grid_61_wrapper *{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box;}
#wistia_grid_61_above{position:relative;}
#wistia_grid_61_main{display:block;height:100%;position:relative;}
#wistia_grid_61_behind{height:100%;left:0;position:absolute;top:0;width:100%;}
#wistia_grid_61_center{height:100%;overflow:hidden;position:relative;width:100%;}
#wistia_grid_61_front{display:none;height:100%;left:0;position:absolute;top:0;width:100%;}
#wistia_grid_61_top_inside{position:absolute;left:0;top:0;width:100%;}
#wistia_grid_61_top{width:100%;position:absolute;bottom:0;left:0;}
#wistia_grid_61_bottom_inside{position:absolute;left:0;bottom:0;width:100%;}
#wistia_grid_61_bottom{width:100%;position:absolute;top:0;left:0;}
#wistia_grid_61_left_inside{height:100%;position:absolute;left:0;top:0;}
#wistia_grid_61_left{height:100%;position:absolute;right:0;top:0;}
#wistia_grid_61_right_inside{height:100%;right:0;position:absolute;top:0;}
#wistia_grid_61_right{height:100%;left:0;position:absolute;top:0;}
#wistia_grid_61_below{position:relative;}</style>
</div></div>
</div></div></div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container midWideContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgNoRepeat emptySection" id="container-10743" data-title="Section" data-block-color="0074C7" style="padding-top: 15px; padding-bottom: 40px; outline: none; margin-top: 0px;" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--70037-132" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-full-156-136" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-92440" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 36px;" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>A System With <u>EVERYTHING</u> You Need To Succeed</b>
</h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--86772" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-123" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elBullet elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_list-80369" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgb(71, 71, 71);" contenteditable="false">
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>100% Done-For-You Affiliate Sales Funnels</li>
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>​Build An Email List AND Generate Sales At The Same Time<br>
</li>
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>ZERO Website or Product Creation</li>
</ul>
</div>
</div>
</div>
<div id="col-right-144" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"><div class="de elBullet elMargin0 ui-droppable de-editable" id="list-27912" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgb(71, 71, 71);" contenteditable="false">
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>100% Newbie-Friendly</li>
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>Easy Push-Button Traffic Solution &amp; Done-For-You Opt-In Pages</li>
<li style="font-size: 20px;">
<i class="fa-fw far fa-arrow-alt-circle-right" contenteditable="false"></i>Your OWN Internet Business For About The Price of a Cup of Coffee A Day</li>
</ul>
</div></div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!<div>Keep The System For LESS THAN $1.60/Day!</div>
</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 35px;" rel="noopener noreferrer">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily clearfix hide cdLabelBold cdBlack cdStyleCircleLine wideCountdownSize4 cdLabelBlack" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold cdBlack cdStyleCircleLine wideCountdown-demo is-countdown wideCountdownSize4 cdLabelBlack" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-107" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 100px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-147" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-158" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-142" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-143" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-167" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 20px;" rel="noopener noreferrer" id="undefined-298">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-183" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-179" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_countdown_daily-64585-139" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily  clearfix hide cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine wideCountdown-demo is-countdown" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover101" id="container-20060" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/33/53c585ed444023b20046a9e5a9efaf/12min-Proposal-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-65824" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Launch Your <b>BRAND NEW</b> Internet Business Before You Go To Bed Tonight...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IN JUST 3 SIMPLE STEPS
</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--31386" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 10px; margin: 0px; outline: none;">
<div id="col-left-174" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-74835" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="300" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/d8/53b18e8d104106a82e78537463b26a/12--Minute-Box-Render.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-189" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_headline1-18899" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #1:</b> ACTIVATE YOUR SYSTEM
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-62224" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">Create your account today, and follow the simple steps to activate your system and initiate our “Sleep-Sales Technology” process. Or, you can just have us set everything up for you!</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-49396" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 25px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #2: </b>GET DONE-FOR-YOU “PIZZA TRAFFIC”
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-32685" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">Normally, getting traffic (website visitors) is difficult. But not anymore! With our system, you just order as much or as little traffic as you want. It’s literally as easy as ordering a pizza. That’s why we call it “pizza traffic”.</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-45492" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 25px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #3: </b>MAKE SALES WHILE YOU SLEEP
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-41347" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">As traffic starts to come, your system will follow-up with people and offer them multiple products to buy, AUTOMATICALLY. This happens 24/7/365… <b>EVEN WHILE YOU’RE ASLEEP!</b>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgNoRepeat" id="container-20060-110" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 10px; padding-bottom: 40px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/33/53c585ed444023b20046a9e5a9efaf/12min-Proposal-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865-175" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125-165" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-65824-166" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Launch Your <b>BRAND NEW</b> Internet Business Before You Go To Bed Tonight...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324-148" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 50px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IN JUST 3 SIMPLE STEPS
</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--31386-111" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 10px; margin: 0px; outline: none;">
<div id="col-left-174-155" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-74835-131" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="300" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/d8/53b18e8d104106a82e78537463b26a/12--Minute-Box-Render.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-189-174" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-18899-101" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #1:</b> ACTIVATE YOUR SYSTEM
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-62224-112" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">Create your account today, and follow the simple steps to activate your system and initiate our “Sleep-Sales Technology” process. Or, you can just have us set everything up for you!</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-49396-181" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 25px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #2: </b>GET DONE-FOR-YOU “PIZZA TRAFFIC”
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-32685-138" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">Normally, getting traffic (website visitors) is difficult. But not anymore! With our system, you just order as much or as little traffic as you want. It’s literally as easy as ordering a pizza. That’s why we call it “pizza traffic”.</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-45492-152" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 25px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>STEP #3: </b>MAKE SALES WHILE YOU SLEEP
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-41347-187" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 18px;" data-gramm="false" contenteditable="false">As traffic starts to come, your system will follow-up with people and offer them multiple products to buy, AUTOMATICALLY. This happens 24/7/365… <b>EVEN WHILE YOU’RE ASLEEP!</b>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover101" id="container-37492" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/21/f38a05941b4f9e8f0f80e3acb7fd4c/12min-Proposal-Background-03.jpg"); outline: none; margin-top: -5px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 60px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>PROOF THIS SYSTEM WORKS</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-71059" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">(Actual Commissions From Just ONE Of <b>My Accounts</b>)</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-75746" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: center; color: rgb(255, 255, 255);" data-gramm="false" contenteditable="false"><i>**Testimonials &amp; case study pictures, while 100% real, are NOT a guarantee of income! Results will Vary!</i></div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--76261" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 90%; max-width: 100%;">
<div id="col-full-168" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elCustomJs elMargin0 ui-droppable de-editable" id="customjs-97473" data-de-type="customjs" data-de-editing="false" data-title="Custom JS / HTML" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elCustomJSBg">CUSTOM JAVASCRIPT / HTML</div>
<div class="elCustomJS_code" data-custom-js='<!-- Add images to <div class="fotorama"></div> -->
&lt;div class="fotorama" data-autoplay="true" data-loop="true" data-arrows="false"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/9b/e3a67c5e334e169a7fe42dff5d4277/System-Proof.png"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/de/dce949f10d458698eba520e46bf915/Daily-Affiliate-Commissions-tilt3.jpg"&gt;
&lt;img src="//easy.12minuteaffiliate.com/hosted/images/2c/c8fee6b838429e8a146771ae5766ed/System-Proof-2.png"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/19/c46238e96b428bbf8431deb7912799/Daily-Affiliate-Commissions.jpg"&gt;
&lt;/div&gt;' data-displaytype="htmlregular"></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgNoRepeat" id="container-37492-168" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/21/f38a05941b4f9e8f0f80e3acb7fd4c/12min-Proposal-Background-03.jpg"); outline: none; margin-top: -5px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-112" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-157" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-188" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>PROOF THIS SYSTEM WORKS</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-71059-112" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">(Actual Commissions From Just ONE Of <b>My Accounts</b>)</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-75746-113" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: center; color: rgb(255, 255, 255);" data-gramm="false" contenteditable="false"><i>**Testimonials &amp; case study pictures, while 100% real, are NOT a guarantee of income! Results will Vary!</i></div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--76261-179" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 90%; max-width: 100%;">
<div id="col-full-168-143" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elCustomJs elMargin0 ui-droppable de-editable" id="customjs-97473-146" data-de-type="customjs" data-de-editing="false" data-title="Custom JS / HTML" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elCustomJSBg">CUSTOM JAVASCRIPT / HTML</div>
<div class="elCustomJS_code" data-custom-js='<!-- Add images to <div class="fotorama"></div> -->
&lt;div class="fotorama" data-autoplay="true" data-loop="true" data-arrows="false"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/9b/e3a67c5e334e169a7fe42dff5d4277/System-Proof.png"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/de/dce949f10d458698eba520e46bf915/Daily-Affiliate-Commissions-tilt3.jpg"&gt;
&lt;img src="//easy.12minuteaffiliate.com/hosted/images/2c/c8fee6b838429e8a146771ae5766ed/System-Proof-2.png"&gt;
  &lt;img src="//easy.12minuteaffiliate.com/hosted/images/19/c46238e96b428bbf8431deb7912799/Daily-Affiliate-Commissions.jpg"&gt;
&lt;/div&gt;' data-displaytype="htmlregular"></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="container-37492-105" data-title="Section - Clone" data-block-color="0074C7" style="padding-top: 55px; padding-bottom: 70px; outline: none; margin-top: -5px; background-color: rgba(45, 131, 166, 0.15);" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865-141" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125-104" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-65824-153" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">This  System Doesn't Just Work For  Me....</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324-109" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 60px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>LOOK AT THESE RESULTS FROM <u>ACTUAL USERS!</u> </b></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-75746-147" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: center; font-size: 18px;" data-gramm="false" contenteditable="false"><i>**Testimonials &amp; case study pictures, while <u>100% real &amp; from REAL users</u>, are NOT a guarantee of income! Results will Vary!</i></div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--93601" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-164" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-73267" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/ab/5cc58cf6da460b9aed35d398eb5e6a/12matestimonialoct5.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="img-61688" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/d2/12c99ead66404585c4aa07cacc4567/12matestimonialoct24.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-118" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-34319" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/6e/98ddd72ffc4a429d85c4ab8bdd007a/12matestimonialoct10.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-88081" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/35/65e674708e405db3f6bd0f5f990c67/12matestimonialoct7.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-48623" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/17/231d255d874e3f9dc1e9259bfb4241/12matestimonialoct16.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--30178" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-149" class="col-md-4 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-87590" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/df/89e7102e5b4bcda44db7331a441518/12matestimonialoct9.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-center-163" class="col-md-4 innerContent col_right ui-resizable" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-47714" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/46/14703c1ab349368f181444114cae94/Inc042.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-95636" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/91/ee196b642b46a9927cf09c46da30b5/12matestimonialoct1.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-147" class="col-md-4 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-81551" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/d2/a8e1c7f0a547d1b02a154e7dd6a9e3/Inc056.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-99521" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/21/57bfc4ed8c4ba68d65cc2ba9af8131/12matestimonialoct17.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--68345" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-137" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-95888" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/03/44eb71fda5456a91d0967e3047e279/Inc020.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-65479" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/ab/12bb5efe9848f5a8984fdc52840e49/Inc062.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-166" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-70052" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/c2/7d52a57f0c48c19a82fad5dc492304/Inc019.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-15842" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/3a/1d2c2319e2477c984ad012bac0e53b/12matestimonialoct18.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--40561" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-187" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-19600" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/98/d1c05bbe2b4141b89be7fb8709a753/Inc049.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-45981" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/b6/e39b70e54e44a9bb89ce31d7c695ad/12matestimonialoct22.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-179" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-99445" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/36/0261eeaea540a5b8bb15144bfbc3ff/12matestimonialoct12.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="img-38105" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/2a/ea1ed6f8b3433bb34637ebca1db4ba/12matestimonialoct27.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--22378" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-125" class="col-md-4 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-69233" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/dc/3969ad6d074f19a11f866ebb191fad/Inc017.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="img-86175" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/e3/902fb9eb144cc88437aa8275e0bcf3/12matestimonialoct26.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-center-108" class="col-md-4 innerContent col_right ui-resizable" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-83319" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/e1/3395b36802466bb011e01049aede62/Inc101.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-78131" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/51/ec8e1378b14c639aa5a54913a48def/12matestimonialoct15.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-104" class="col-md-4 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-74778" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/11/fdbb8ba7b445b7a3393872357be8bd/Inc114.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-37076" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/fd/708418cb34459a95088871f4f0e557/Inc021.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-52123" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/03/4cda2ff5b448138f5f748824b92ec8/12matestimonialoct20.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--42134" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-100" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-83481" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/c4/c3a7db2ff04807b76de574bf4e7084/Inc086.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-37609" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/0c/26c1824ceb47ddabce10cb43658f4b/Inc004.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="img-31499" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/27/d77fe89f124c83bbf834287aea4b0e/12matestimonialoct6.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-167" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-29985" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/2f/10c38dc00f4509a5e76aeabf815ec5/12matestimonialoct25.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-57988" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/e6/28085ee1a24a3ab4a87b84fa96f225/12matestimonialoct4.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--16329" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-139" class="col-md-4 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-93425" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/9b/3cfa9aff7a41db85144e5bf46c88e6/Inc076.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-center-142" class="col-md-4 innerContent col_right ui-resizable" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-77790" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/b4/f404fcb48347b7a0ac9d5f065b1807/Inc056.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-42152" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/b8/5e22288b674e848d551f78ab22f6ff/12matestimonialoct19.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-168" class="col-md-4 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-99124" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/57/e18b9d09854fc98fad52a056638aee/Inc062.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-48594" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/4e/769d7ea04a42c5a1ef699b38fcb366/12matestimonialoct21.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer bgCover" id="container-37492-105-131-158-170-164-155-169" data-title="Section - Clone - Clone - Clone - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 80px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-110" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-142" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-96557" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px;" data-bold="inherit" data-gramm="false" contenteditable="false">Take About <b><u>4 Quick Minutes</u></b> And Check Out...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-105" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<font color="#0174c7"><b>"SLEEP-SALES TECHNOLOGY" Explained...</b></font>
</h1>
</div>
</div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover100" id="row--55129" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style='padding: 25px 0px 275px; margin: 0px auto; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/87/4c0f7415f3461fb1a48ad8b179cfea/imacfront_1268x1068.png"); width: 85%; max-width: 100%;'>
<div id="col-full-109" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elVideoWidth100 elMargin0 ui-droppable de-editable" id="tmp_video-66566" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" data-video-type="wistia" style="margin-top: 0px; outline: none; cursor: pointer;" data-wistia-url="https://devonbrown.wistia.com/medias/efxca63ka3" aria-disabled="false">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo" style="display: none;"><iframe width="640" height="360" src="https://fast.wistia.net/embed/iframe/efxca63ka3?autoplay=0&amp;wmode=transparent" allowtransparency="true" frameborder="0" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen="" mozallowfullscreen="" webkitallowfullscreen="" oallowfullscreen="" msallowfullscreen="" wmode="opaque"></iframe></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer bgCover activeSection innerToolsTop" id="container-37492-105-131-158-170-164-155-169-113" data-title="Section - Clone - Clone - Clone - Clone - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 80px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-110-159" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-142-120" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-96557-156" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 25px;" data-bold="inherit" data-gramm="false" contenteditable="false">Take About <b><u>4 Quick Minutes</u></b> And Check Out...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-105-176" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase" style="text-align: center; font-size: 45px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<font color="#0174c7"><b>"SLEEP-SALES TECHNOLOGY" Explained...</b></font>
</h1>
</div>
</div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover101" id="row--55129-180" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding: 0px 0px 10px; margin: 0px auto; outline: none; width: 100%; max-width: 100%;">
<div id="col-full-109-158" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elVideoWidth100 elMargin0 ui-droppable padding20 effect1 elVideoSkin1 de-editable" id="tmp_video-66566-152" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" data-video-type="wistia" style="outline: none; cursor: pointer;" data-wistia-url="https://devonbrown.wistia.com/medias/efxca63ka3" aria-disabled="false" data-element-theme="customized" data-wistia-width="">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo" style="display: none;"><iframe width="" height="360" src="https://fast.wistia.net/embed/iframe/efxca63ka3?autoplay=0&amp;wmode=transparent" allowtransparency="true" frameborder="0" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen="" mozallowfullscreen="" webkitallowfullscreen="" oallowfullscreen="" msallowfullscreen="" wmode="opaque"></iframe></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-159" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-103" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-122" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-164" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-138" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!<div>Keep The System For LESS THAN $1.60/Day!</div>
</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-115" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 35px;" rel="noopener noreferrer" id="undefined-494">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-119" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-150" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585-109" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily clearfix hide cdLabelBold cdBlack cdStyleCircleLine wideCountdownSize4 cdLabelBlack" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold cdBlack cdStyleCircleLine wideCountdown-demo is-countdown wideCountdownSize4 cdLabelBlack" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-107-165" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 100px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-147-120" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-158-169" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-142-117" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-143-138" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-167-108" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 20px;" rel="noopener noreferrer" id="undefined-298-594">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-183-139" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-179-100" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585-139-181" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily  clearfix hide cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine wideCountdown-demo is-countdown" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer noBorder bgCover" id="container-42198" data-title="Section" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 50px; margin-top: -5px; outline: none; background-color: rgba(255, 255, 255, 0); background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable"> <div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row-131" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;"> <div id="col-left-107-172-106" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;"> <div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"> <div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-97540-180-145" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false"> <img src="//easy.12minuteaffiliate.com/hosted/images/8a/42af9198ec4e4a8ed086ce4da2969d/Standing-arms-folded3.jpg" class="elIMG ximg" alt="">
</div>
</div> </div> <div id="col-right-130-130-188" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;"> <div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-59650-160-182-126" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 26px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>From:</b>  7 Figure Earner, </h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-46405-152-111" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 48px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Devon Brown</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-66842-141-119" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 26px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><div>
<b>To: </b>Frustrated Beginner who has failed to make sustainable income online. </div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-78655-179-109" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 26px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><div>
<b style="font-family: inherit; background-color: rgba(255, 255, 255, 0);">Subject: </b><span style="font-family: inherit; background-color: rgba(255, 255, 255, 0);">Why you've  failed to succeed online</span><br>
</div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-69006-147-102-107" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 23px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">This is a very personal message from me to you. <div>
<br><div></div>
<div>Your struggle to make money online is about to end forever. </div>
<div><br></div>
<div><span style="font-family: inherit;">But before we begin to solve your problem, let me ask you a few quick questions:</span></div>
<div></div>
<div><b><br></b></div>
<div>
<b><u>Question-1:</u></b> Have you been trying to make money online without success?</div>
<div></div>
<div><b><br></b></div>
<div>
<b><u>Question-2:</u></b> Do you feel like something was missing from the software, courses, and products that you have purchased in the past?</div>
<div></div>
<div><b><br></b></div>
<div>
<b><u>Question-3:</u></b> Do you think making money online is just a scam and you are about to give up?<span style="background-color: initial; color: inherit; font-family: inherit;">​ </span>
</div>
<div></div>
<div><br></div>
<div>If you have answered “yes” to any or all the questions above, then read this page carefully.</div>
</div>
</h2>
</div>
</div> </div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover fullContainer" id="container-37492-105-131" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 55px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/be/215cfca6964828a0b894598385959e/12-min-vector-background.jpg"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-71059-102-111" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>With Everything Going On In The World…</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 55px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>INTERNET-BASED BUSINESSES ARE EXPLODING!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25913" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-155" class="col-md-4 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-89483" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/ec/50cc60ed0f42b6a79277516858bb1a/Mark-Zukerberg-in-business-Magazine-cover.jpg" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-center-119" class="col-md-4 innerContent col_right ui-resizable" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-67855" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="250" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/ef/ea200862754485be782733c6589dbf/Forbes-news-about-Jeff-Bezos-business.jpg" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-188" class="col-md-4 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-73497" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="fade" data-delay="400" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/d9/39ce07432a443fb48993bb16d8a289/Jack-Ma-in-business-Magazine-cover.jpg" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer bgCover" id="container-37492-105-131-158" data-title="Section - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 55px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>BEFORE YOU GO ANY FURTHER, READ THIS...</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98223" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 35px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-119" class="innerContent col_left ui-resizable col-md-5" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-67727" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; color: rgba(0, 0, 0, 0.96); font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>In Order To Make Money Online From The Comfort Of Your Home... At The <u>Absolute Least,</u> You'll Need To Have:</b></div></h2>
</div>
<div class="de elBullet elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_list-46188" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgba(0, 0, 0, 0.96);" contenteditable="false">
<li style="font-size: 20px;">
<i class="fa-fw fas fa-cart-plus" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b> A Quality Product (or Products) To Sell</b>
</li>
<li style="font-size: 20px;">
<i class="fa-fw fas fa-users" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>A Way To Find The Interested People To Buy The Product (or Products)</b>
</li>
<li style="font-size: 20px;">
<i class="fa-fw fas fa-laptop" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>Website Pages (A Sales Funnel) &amp; Copywriting For Each Page</b>
</li>
<li style="font-size: 20px;">
<i class="fa-fw fas fa-align-justify" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>​A Follow Up Series Of Emails For Your Prospects<br></b>
</li>
<li style="font-size: 20px;">
<i class="fa-fw fas fa-server" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>​Domain Name &amp; Website Hosting</b><br>
</li>
</ul>
</div>
</div>
</div>
<div id="col-right-123" class="innerContent col_right ui-resizable col-md-7" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-40247" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/5c/c71955ca954220a25e10d220ac891a/12MINAFFIMG1.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgNoRepeat emptySection" id="container-87540-147" data-title="Section - Clone" data-block-color="0074C7" style="padding-top: 40px; padding-bottom: 40px; background-color: rgba(0, 0, 0, 0.04); outline: none;" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--11464" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-112" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-75276" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Lato">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false"> If You Can Get All of This Functioning Properly By Yourself, GREAT! However...</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-87953" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<font color="#0174c7"><b>FOR MOST, THERE'S A HUGE PROBLEM!</b></font>
</h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--21089" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-140" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-22649" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="left" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/63/a928197c9e43d396ec55201f986381/12MINAFFIMG2.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-181" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-13871" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 22px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">It is NOT easy getting all these things set up and positioned in the proper order, but it has to be done.
<div><span style="font-family: inherit; background-color: initial;"><br></span></div>
<div>For most people, it’s extremely difficult to not only know all of the right ingredients, but to also have all of those ingredients perfectly mixed in a way that allows your online business to<b> generate sales 24/7 (even while you’re sleeping).</b>
</div>
<div><span style="background-color: initial; font-family: inherit;"><br></span></div>
<div><span style="background-color: initial; font-family: inherit;">If just ONE of the ingredients is incorrect, you'll never make a dime.</span></div>
<div><span style="background-color: initial; font-family: inherit;"><br></span></div>
<div><span style="background-color: initial; font-family: inherit;">This is why most people fail before they even turn on their computer.</span></div>
</h2>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="container-87540" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-80093" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#2d2d2d">You Could Try To Do It All By Yourself (Which Is VERY Hard). Or Maybe...</font></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>YOU COULD OUTSOURCE EVERYTHING</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98223-159" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-119-189" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-48205" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 22px; color: rgba(0, 0, 0, 0.96);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>...BUT YOU BETTER BE PREPARED TO COUGH UP THOUSANDS OF DOLLARS TO AFFORD EVERYTHING YOU NEED!</b><div><b><br></b></div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-29596-184" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; color: rgba(0, 0, 0, 0.96); font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">Let’s break it all down in a real world scenario where we assume that you hire professionals to get the job done for you.
 <div><br></div>
<div>Professional copywriters, website developers, digital product creators, the whole 9 yards.</div>
</h2>
</div>
</div>
</div>
<div id="col-right-123-168" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-40247-118" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/c6/4c77398ab04b6a97ea75c18d6a98b5/12MINAFFIMG3.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-36301" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 45px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/1f/b921baf599499c9537a8fd17209f72/Blue-Texture-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--17729" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-149" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-58857-113" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>This is a rough estimate of what IT WOULD COST to MAKE THIS HAPPEN:
</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81899" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 85%; max-width: 100%;">
<div id="col-left-179" class="innerContent col_left ui-resizable col-md-2" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de eliconelementWrapper ui-droppable de-editable" id="tmp_iconelement-56903" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="250" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(232, 138, 23); text-align: center; font-size: 110px; line-height: 1em; display: block;">
<i class=" fas fa-shopping-bag"></i>
</a>
</div>
</div>
</div>
<div id="col-center-120" class="innerContent col_right ui-resizable col-md-7" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-70991" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 28px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>A QUALITY PRODUCT (in a hungry niche market) for which interested prospects will gladly hand over money
</b></h2>
</div>
</div>
</div>
<div id="col-right-135" class="innerContent col_right ui-resizable col-md-3" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-23058" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Patua One", Helvetica, sans-serif !important;' data-google-font="Patua+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 60px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false">
$2,000
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-48787" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 20px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">+30-45 Days To Create
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81899-177" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 85%; max-width: 100%;">
<div id="col-left-179-132" class="innerContent col_left ui-resizable col-md-2" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de eliconelementWrapper ui-droppable hiddenElementTools de-editable" id="tmp_iconelement-38706" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="250" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(232, 138, 23); text-align: center; font-size: 110px; line-height: 1em; display: block;">
<i class=" fas fa-mail-bulk"></i>
</a>
</div>
</div>
</div>
<div id="col-center-120-134" class="innerContent col_right ui-resizable col-md-7" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-70991-110" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 28px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Professionally written FOLLOW-UP MESSAGES (because it takes the average person seeing an offer several times before they're likely to buy)
</b></h2>
</div>
</div>
</div>
<div id="col-right-135-188" class="innerContent col_right ui-resizable col-md-3" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-23058-101" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Patua One", Helvetica, sans-serif !important;' data-google-font="Patua+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 60px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false">
$800</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-48787-165" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 20px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">For 20 follow-up messages
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81899-179" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 85%; max-width: 100%;">
<div id="col-left-179-188" class="innerContent col_left ui-resizable col-md-2" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de eliconelementWrapper ui-droppable hiddenElementTools de-editable" id="tmp_iconelement-53743" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="250" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(232, 138, 23); text-align: center; font-size: 110px; line-height: 1em; display: block;">
<i class=" fas fa-users-cog"></i>
</a>
</div>
</div>
</div>
<div id="col-center-120-173" class="innerContent col_right ui-resizable col-md-7" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-70991-107" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 28px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Technical Stuff: Fully set up and integrated AUTORESPONDER, HOSTING, DOMAIN, etc...</b></h2>
</div>
</div>
</div>
<div id="col-right-135-139" class="innerContent col_right ui-resizable col-md-3" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_headline1-23058-154" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Patua One", Helvetica, sans-serif !important;' data-google-font="Patua+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 60px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false">
$400</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-48787-121" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 20px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Only For Help Setting This Up
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81899-118" data-trigger="none" data-animate="fade" data-delay="500" data-title="3 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px auto; outline: none; width: 85%; max-width: 100%;">
<div id="col-left-179-116" class="innerContent col_left ui-resizable col-md-2" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de eliconelementWrapper ui-droppable hiddenElementTools de-editable" id="tmp_iconelement-42322" data-de-type="iconelement" data-de-editing="false" data-title="Icon" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="250" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<a class="eliconelement elMargin0 elBGStyle0 hsTextShadow0" style="padding: 0px; margin: 0px; color: rgb(232, 138, 23); text-align: center; font-size: 110px; line-height: 1em; display: block;">
<i class=" fas fa-funnel-dollar"></i>
</a>
</div>
</div>
</div>
<div id="col-center-120-155" class="innerContent col_right ui-resizable col-md-7" data-col="center" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-70991-184" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 28px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>A high-converting SALES FUNNEL that first turns traffic into opt-ins, AND THEN turns those opt-ins into buyers
</b></h2>
</div>
</div>
</div>
<div id="col-right-135-134" class="innerContent col_right ui-resizable col-md-3" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="3rd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-23058-111" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Patua One", Helvetica, sans-serif !important;' data-google-font="Patua+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 60px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false">
$1,497
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-48787-120" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 20px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Including Copywriting
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--24840" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 20px 0px 0px; outline: none;">
<div id="col-full-108" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-27583" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 55px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>That's A Total Of</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-77424" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Patua One", Helvetica, sans-serif !important;' data-google-font="Patua+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_55" style="text-align: center; font-size: 100px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false">
$4,697.00</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-45273" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: center; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Just To Get OTHER PEOPLE To Help You Set Everything Up… This Doesn’t Even Include Traffic!
</b></h2>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer bgCover" id="container-37492-105-131-158-170-164" data-title="Section - Clone - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 55px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-34911-179-164-100-156-141" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>WHO ON EARTH HAS THAT KIND OF MONEY JUST LAYING AROUND?!?</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98223-159-155" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-119-189-118" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-48205-147" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(46, 194, 254);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>The Answer?</b></div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-29596-184-180" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; color: rgba(0, 0, 0, 0.96); font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">Not that many people, and this is where another problem comes into play.
 <div><br></div>
<div>If regular, everyday people are aspiring to have their very own, online money-making sales funnels up and running, they can’t even afford the out of pocket cost to get everything set up. </div>
<div><span style="background-color: initial; font-family: inherit;"><br></span></div>
<div><span style="background-color: initial; font-family: inherit;">With that in mind, there has GOT to be a smarter, more effective and much more cost-efficient way of doing things…</span></div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-87917" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>And There Is...</b></font></h1>
</div>
</div>
</div>
<div id="col-right-123-168-170" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-40247-118-113" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/40/07c6af107f4e39a8c8d7a1582d209c/12MINAFFIMG4.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgNoRepeat emptySection" id="section--56115-145" data-title="Section - Clone" data-block-color="0074C7" style="padding-top: 40px; padding-bottom: 40px; outline: none; background-color: rgba(0, 0, 0, 0.04);" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--11464-137" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-112-152" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-93171" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Many People Consider <b>Affiliate
Marketing</b> To Be...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-16841" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>THE EASIEST WAY TO MAKE MONEY ONLINE</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--21089-161" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-140-120" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-22649-147" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="left" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/cd/8386f9c85f475e93d7578ac8a42a88/12MINAFFIMG5.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-181-134" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34985" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(46, 194, 254);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>But Why?</b></div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-13871-119" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 22px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Well, when put up against all of the other make money online methods, Affiliate Marketing is the one that tends to overcome most, if not all, of these obstacles. 
<div><br></div>
<div>In a nutshell, Affiliate Marketing is simply the process by which an individual earns money by marketing the product of another individual.</div>
</h2>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="section--56115-145-150" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 65px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--40819-123" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-161-163" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-23506-101-105" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>HERE'S HOW IT WORKS...</b></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-22191-131" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">1. Someone else creates the product &amp; sales process…
<div>2. You just send people who might be interested to their site…
</div>
<div>3. You earn commissions every time someone purchases!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover borderSolid shadow0 P0-top P0-bottom P0H noTopMargin radius25 cornersBottom borderLightTopBottom border5px" id="row--41089-183-121" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding: 35px 25px; margin: 25px auto 0px; background-color: rgb(238, 238, 238); outline: none; width: 65%; max-width: 100%; border-color: rgb(73, 102, 180); color: rgba(0, 0, 0, 0.11);">
<div id="col-full-158-108-102" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-31490-111" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: left; font-size: 35px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>No</b> Making your own product
<div>
<b>No</b> Building your own websites
</div>
<div>
<b>No</b> Techie stuff
</div>
<div>
<b>No</b> Taking weeks to get started
</div>
<div>
<b>No</b> Huge barriers to entry
</div>
<div>
<b>No</b> Prior experience needed
</div>
<div>
<b>No</b> Customer support
</div>
<div>
<b>No</b> Figuring Out Payment processing</div>
</h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-36301-167" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 45px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/1f/b921baf599499c9537a8fd17209f72/Blue-Texture-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--17729-136" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-149-189" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-58857-113-101" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font style="font-family: inherit; background-color: initial;" color="#0174c7"><b>BUT IF IT'S SO EASY... WHY DOESN'T IT WORK FOR MOST PEOPLE WHO TRY IT?</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--21089-161-124-111-131" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-140-120-128-137-124" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-96672-132-105" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">The answer is because there's ONE FATAL FLAW with affiliate marketing. No one wants to tell you this secret, but I will.<div><br></div>
<div>The problem is that it takes the average person seeing an offer SEVERAL times before they're likely to purchase.
The truth is that  <span style="font-family: inherit; background-color: initial;">99.5% of people who see a product you're trying to sell, WON'T buy it the first time they see it.  </span>
</div>
<div><span style="font-family: inherit; background-color: initial;"><br></span></div>
<div>Therefore, if you don't have a way to automatically follow-up with people (while you sleep), then your chances of making sales is pretty much zero.</div>
<div><div><br></div></div>
</h2>
</div>
</div>
</div>
<div id="col-right-181-134-149-166-133" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-22649-147-115-118-155" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/3b/4f7d2a095a4899bc314d0bb609d59e/once-chance-to-make-a-sale-v2.png" class="elIMG ximg" alt="">
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="img-28742" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/25/0eab0fc9ad4147bdf8f0d8c3e642ce/Problem-with-Afilliate-Marketing.gif" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--24840-125" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 20px 0px 0px; outline: none;">
<div id="col-full-108-179" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-45273-173" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: center; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Being Able To Solve This ONE PROBLEM Is The Secret To Pocketing Commissions While You Sleep!</b></h2>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgNoRepeat emptySection" id="section--56115-145-150-188-108" data-title="Section - Clone - Clone - Clone - Clone" data-block-color="0074C7" style="padding-top: 30px; padding-bottom: 40px; outline: none; background-color: rgba(0, 0, 0, 0.04);" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-124" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 5px; padding-bottom: 20px; margin: 25px 0px 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-158" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-19677-157" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Because I Discovered How To Automate The Sales Process...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-162" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>I FINALLY STARTED MAKING MONEY!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--21089-161-124-111-131-111" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-140-120-128-137-124-143" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-96672-132-105-164" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">After YEARS of trial and error and trying to “make it” online, I finally learned how to create a system for myself that generates affiliate sales for me...<div><br></div>
<div>WHILE I SLEEP!<br><div><br></div>
<div>It took a while to figure out, but once I did, I started sharing my process with other people!</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-181-134-149-166-133-104" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-22649-147-115-118-155-113" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="right" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/ab/92c6487c82480cbb3630179cabeb0a/12MINAFFIMG6.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="section--56115" data-title="Section" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-125" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-133" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-19677-115" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Over The Years, We've Gotten Our System To The  Point Where Any Random Person Off The Street Can Get Up, Running, &amp; Seeing Results In As Little As 48 Hours.</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-187" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>WE'VE PERFECTED THE PROCESS...</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98223-159-155-155" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-119-189-118-175" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-40247-118-113-143" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="left" data-delay="100" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/40/07c6af107f4e39a8c8d7a1582d209c/12MINAFFIMG4.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-123-168-170-129" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-86100" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Merriweather, Helvetica, sans-serif !important;" data-google-font="Merriweather" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgb(0, 0, 0);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>We created a system that was so easy &amp; effective, that it turned the internet marketing world on it's head!</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-48205-147-137" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(46, 194, 254);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>It's a System That:
</b></div></h2>
</div>
<div class="de elBullet elMargin0 ui-droppable de-editable" id="tmp_list-33379" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>Has been tried, battle-tested and PROVEN...</b>
</li>
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>Is simple (especially for beginners)...</b>
</li>
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>Can allow you to pocket affiliate commissions on a daily basis...</b>
</li>
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>​Can make you as much as you want (no income cap)...<br></b>
</li>
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>​Will allow you to earn from multiple streams of income…<br></b>
</li>
<li style="font-size: 18px;">
<i class="fa-fw fas fa-award" style="color: rgb(232, 138, 23);" contenteditable="false"></i><b>​And much, much more...<br></b>
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--98919-174" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-131-169" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-91950" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">
<div>
<b>So… </b><b style="font-family: inherit; background-color: initial;">Are You Ready To Get Off The Home-Business Hamster Wheel?</b>
</div>
</h2>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 emptySection bgCover shadow0" id="container-20060-143" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 60px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/aa/73de4f01cb4edca5fac029ddecf82c/Blue-Texture-Background-03.png"); outline: none; background-color: rgb(0, 166, 255);' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865-139" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125-158" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-86361" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 55px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>Introducing...
</b></div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324-133" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; color: rgb(255, 255, 255); font-size: 83px;" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>THE 12 MINUTE AFFILIATE SYSTEM</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-87138" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 5px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_22" style="text-align: center; font-size: 24px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">12 Minute Affiliate System Is A Revolutionary New  Online Marketing System That  Utilizes<div>  <b><u>SLEEP-SALES TECHNOLOGY </u></b> To Simplify The Entire Money-Making Process .  Now, Even The Newest Internet Entrepreneur Can Get EVERYTHING Set-up BEFORE You Go To Bed Tonight. </div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--31386-116" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 10px; margin: 0px; outline: none;">
<div id="col-left-174-103" class="innerContent col_left ui-resizable col-md-6" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-74835-176" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="200" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/d8/53b18e8d104106a82e78537463b26a/12--Minute-Box-Render.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-189-157" class="innerContent col_right ui-resizable col-md-6" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elBullet elMargin0 ui-droppable mfs_22 hiddenElementTools de-editable" id="tmp_list-51178" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgb(255, 255, 255);" contenteditable="false">
<li style="font-size: 25px;">
<i class="fa-fw fas fa-calendar-check" style="color: rgb(232, 138, 23);" contenteditable="false"></i>100% Newbie friendly</li>
<li style="font-size: 25px;">
<i class="fa-fw fas fa-calendar-check" style="color: rgb(232, 138, 23);" contenteditable="false"></i>Designed to Generate Both Leads &amp; Affiliate Sales on Autopilot!</li>
<li style="font-size: 25px;">
<i class="fa-fw fas fa-calendar-check" style="color: rgb(232, 138, 23);" contenteditable="false"></i>You NEVER Have to Create Your Own Product</li>
<li style="font-size: 25px;">
<i style="color: rgb(232, 138, 23);" class="fa-fw fas fa-calendar-check" contenteditable="false"></i>​There is Absolutely NO PRIOR EXPERIENCE NEEDED!<br>
</li>
<li style="font-size: 25px;">
<i style="color: rgb(232, 138, 23);" class="fa-fw fas fa-calendar-check" contenteditable="false"></i>​A COMPLETE Online Affiliate Business in A Million (or even BILLION) Dollar Niche Market For About The Price Of A Cup Of Coffee A Day.<br>
</li>
<li style="font-size: 25px;">
<i style="color: rgb(232, 138, 23);" class="fa-fw fas fa-calendar-check" contenteditable="false"></i>​Earn Money AND Build Your List At The Same Time!<br>
</li>
<li style="font-size: 25px;">
<i style="color: rgb(232, 138, 23);" class="fa-fw fas fa-calendar-check" contenteditable="false"></i>​Completely Done-For-You Affiliate Sales Funnels<br>
</li>
</ul>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-20060-143-189-147" data-title="Section - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 70px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-125-128" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone - Clone" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-133-155" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-19677-115-153" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Want To See Just How Easy The System Is? Just Press Play And...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-187-182" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>WATCH THIS QUICK VIDEO!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover101" id="row--29235-139" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style='padding: 15px 100px 90px; margin: 0px auto; outline: none; width: 100%; max-width: 100%; background-image: url("//easy.12minuteaffiliate.com/hosted/images/88/ba2f551e1043e78bcac1cbcf1f1a07/macbookfront_1768x1070.png");'>
<div id="col-full-182-184" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elVideoWidth100 elMargin0 ui-droppable padding0 hiddenElementTools de-editable" id="tmp_video-35456" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" data-video-type="vimeo" style="outline: none; cursor: pointer;" data-vimeo-url="https://vimeo.com/320644622" data-vimeo-autoplay="yes" data-element-theme="customized" aria-disabled="false" data-vimeo-unmute-label="true">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo iframeunmuted" style="display: none;"><iframe width="640" height="360" allow="autoplay" src="https://player.vimeo.com/video/320644622?muted=1&amp;autoplay=1&amp;&amp;title=0&amp;byline=0&amp;wmode=transparent&amp;autopause=0" frameborder="0" allowfullscreen="" wmode="opaque"></iframe></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100 containerWithVisibleOverflow" id="container-20060-143-189-147-129" data-title="Section - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 70px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-161-135-176-133-103-150-125-128-141" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone - Clone" style="padding-top: 5px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-152-151-120-128-153-113-133-155-147" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-19677-115-153-189" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px; color: rgb(71, 71, 71);" data-bold="inherit" data-gramm="false" contenteditable="false">Want To See Just How Easy The System Is? Just Press Play And...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-179-164-100-156-141-182-187-182-127" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Oswald">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>WATCH THIS QUICK VIDEO!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin bgCover101" id="row--29235-139-104" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style='padding: 0px 100px 10px; margin: 0px auto; outline: none; width: 100%; max-width: 100%; background-image: url("//easy.12minuteaffiliate.com/hosted/images/88/ba2f551e1043e78bcac1cbcf1f1a07/macbookfront_1768x1070.png");'>
<div id="col-full-182-184-129" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elVideoWrapper de-video-block elVideoWidth100 elMargin0 ui-droppable padding20 de-editable" id="tmp_video-35456-148" data-de-type="video" data-de-editing="false" data-title="video" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" data-video-type="vimeo" style="outline: none; cursor: pointer; margin-top: -12px;" data-vimeo-url="https://vimeo.com/320644622" data-vimeo-autoplay="yes" data-element-theme="customized" aria-disabled="false" data-vimeo-unmute-label="true">
<div class="elVideoplaceholder">
<div class="elVideoplaceholder_inner"></div>
</div>
<div class="elVideo iframeunmuted" style="display: none;"><iframe width="640" height="360" allow="autoplay" src="https://player.vimeo.com/video/320644622?muted=1&amp;autoplay=1&amp;&amp;title=0&amp;byline=0&amp;wmode=transparent&amp;autopause=0" frameborder="0" allowfullscreen="" wmode="opaque"></iframe></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-159-116" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-103-161" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-122-185" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-164-148" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-138-151" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!<div>Keep The System For LESS THAN $1.60/Day!</div>
</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-115-185" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 35px;" rel="noopener noreferrer" id="undefined-494-681">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-119-130" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-150-178" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_countdown_daily-64585-109-100" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily clearfix hide cdLabelBold cdBlack cdStyleCircleLine wideCountdownSize4 cdLabelBlack" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold cdBlack cdStyleCircleLine wideCountdown-demo is-countdown wideCountdownSize4 cdLabelBlack" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-107-165-185" data-title="Section - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 100px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 0px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-147-120-123" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-158-169-173" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-142-117-189" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-143-138-134" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-167-108-162" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 20px;" rel="noopener noreferrer" id="undefined-298-594-170">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-183-139-102" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_headline1-68268-179-100-122" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585-139-181-157" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily  clearfix hide cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine wideCountdown-demo is-countdown" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-63278" data-title="Section" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 50px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/1f/b921baf599499c9537a8fd17209f72/Blue-Texture-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-165" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_30" style="text-align: center; font-size: 45px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>What makes 12 Minute Affiliate...</b></div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-44568" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>The Easiest Way To Succeed Online</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover borderSolid border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius50 borderLight" id="row--89385" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 15px; padding-bottom: 15px; margin: 0px auto; background-color: rgb(46, 194, 254); width: 90%; max-width: 100%; outline: none; color: rgb(255, 255, 255);">
<div id="col-full-151" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-67832" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>HERE’S EVERYTHING YOU’RE GETTING</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/4e/0c636983a14adfac0b0b86bdd3e10b/laptoprt_1369x746-4-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>DFY FUNNELS (Value: $2,240)</b>
</h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_divider-12998" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Done-For-You Affiliate Funnels in the HOTTEST Niche Markets:
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">No HTML, no coding, no hosting, and no techie stuff! The 12 Minute Affiliate System includes ready-to-go affiliate funnels in the hottest and MOST PROFITABLE niche markets (like 'making money from home', 'weight loss', and 'personal development').  <div><br></div>
<div>Just personalize the system so that the leads go onto YOUR email list, and affiliate commissions go to YOUR bank account!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-109" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>DFY EMAILS (Value: $3,200)</b>
</h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Professionally Written Follow-Up Messages (Done-For-You)
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-102" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">The fortune is in the follow-up! That's why the 12 Minute Affiliate system includes MONTHS worth of professionally written done-for-you follow up messages! <div><br></div>
<div>No hiring expensive copywriters, and nothing for you to write yourself. You'd EASILY pay a professional copywriter $40 -$50 or more (per email). But with 12 Minute Affiliate, it's all included!
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-112" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/8f/476f2323114f51a6fc4eded09b8caa/12ma---laptom-for-emails.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-157" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-168" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-111" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/74/7faa51282048b1b1ded1c6678583cc/laptoprt_1369x746-3-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148-164" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-122" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>12 MINUTE SETUP
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-144" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-131" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Copy/Paste Simple Instructions
<div>(No Tech Skills Needed)</div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-111" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Our simple step-by-step instructions make it easy for even the newest online marketer to have the system set up QUICKLY. The fastest we've ever seen someone set the system up is 12 short minutes! But even if it takes you a little longer, you can still have it all set up BEFORE you go to bed tonight!<div><b style="font-family: inherit; background-color: initial;"><br></b></div>
<div><b style="font-family: inherit; background-color: initial;">There's even an option for us to set it up FOR YOU!!</b></div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105-124" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130-164" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-109-167" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>E-Z FUNNEL WIZARD <br>(Value: $97/Month)</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133-103" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142-166" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Create CUSTOM "On Demand" Funnels In Minutes
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-102-147" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Similar funnel-building systems cost $97/month or more! And they're not as easy to use as the 12 Minute Affiliate funnel Wizard
. <div>
<br><div>With Funnel Wizard, you can create your own custom affiliate funnels in as little as 5 MINUTES! No coding or copy-writing needed!</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103-131" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-112-137" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/cd/4cdd48711f46249c385103a4294b94/laptoplt_1369x746-3-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-157-134" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-168-106" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-59823-111-122" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/46/cbe31296e043718c71061c3cfedccc/Laptop-3D-Image.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148-164-160" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-122-152" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>PRIVATE COMMUNITY <br>(Value: $97/Month)</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-144-116" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-131-177" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Private Facebook Community &amp; Free Private Training
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-111-108" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">The free monthly trainings alone are easily worth $97/month. But when you add in access to a mastermind of members who are already crushing it, this feature alone is worth more than the price of the system! <div>
<br><div>Now you can be in business FOR yourself, but not BY yourself!
</div>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105-124-120" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130-164-167" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-109-167-173" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>DONE-FOR-YOU TRAFFIC!</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133-103-131" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142-166-130" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Done-For-You Traffic Solution -
<div>As Easy As Ordering A Pizza</div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-102-147-145" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Traffic is the life-blood of your online business. And we've just made it EASIER THAN ORDERING A PIZZA!  Our easy traffic solution allows you to get targeted niche traffic in MINUTES (based on YOUR BUDGET). <div>
<br><div>Just choose how much traffic you want, and we’ll take care of it for you!</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103-131-137" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-59823-112-137-178" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/97/f3c384c952462fa8b60f94d88ada65/laptoplt-traffic_1369x746-2-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379-103" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 20px 0px 0px; outline: none;">
<div id="col-full-165-147" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041-105" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_35" style="text-align: center; font-size: 45px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>BUT THAT'S NOT ALL! WE'RE ALSO GIVING YOU...</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-44568-126" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_50" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>over $1,590 IN <u>FREE BONUSES</u>!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover borderSolid border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius50 borderLight" id="row--89385-115" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 15px; padding-bottom: 15px; margin: 0px auto; background-color: rgb(46, 194, 254); width: 90%; max-width: 100%; outline: none; color: rgb(255, 255, 255);">
<div id="col-full-151-160" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-67832-127" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>FOR A LIMITED TIME: HERE'S WHAT YOU'RE GETTING...</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-178" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/7e/a261b2127b489f9aaa9a9f0af8daee/Magazine-Stack-Bonus-1.png" class="elIMG ximg" alt="" width="450">
</div>
</div>
</div>
<div id="col-right-148-143" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #1: The Success Library <br><i>(a $497 Value)</i></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-168" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Instant access to a library of personal development training! Discover how to unlock your true potential, balance your life, end procrastination, and MUCH MUCH MORE! Over 15 titles in all!</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128-143" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116-178" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elMargin0 ui-droppable elAlign_center de-editable" id="tmp_image-59823-178-137" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/ee/802b44ddc64ba2ae253645ff5ffd2e/Ring-Spiral-Binder_-Bonus-2.png" class="elIMG ximg" alt="" width="350">
</div>
</div>
</div>
<div id="col-right-148-143-153" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134-146" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #2: The Free Traffic Guide <font style="" color="#e43b2c"><i style="color: rgb(232, 138, 23);">(a $97 Value)</i></font></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142-126" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-168-101" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Discover 16 ways to get FREE TRAFFIC to your website! Including: How to get free traffic from Twitter &amp; Facebook, how to get traffic from other people's blogs, and how to get traffic just by posting pictures online! </h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128-110" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116-169" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-178-188" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/62/9764a89d0d4bdebddd5a339b5fa95c/modernsoftwarebox_506x599-2-.png" class="elIMG ximg" alt="" width="400">
</div>
</div>
</div>
<div id="col-right-148-143-103" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134-167" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #3: Hot Product Promos<br><font color="#e43b2c"><i style="color: rgb(232, 138, 23);">( a $997/Year Value)</i></font></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142-161" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-168-140" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">We continually partner with the creators of some of the HOTTEST selling products on the internet. Normally, these offers are off-limits to new affiliate marketers.  But because you're part of 12 Minute Affiliate, you'll be able to promote these offers and pocket HUGE commissions!</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937-182" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137-139" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114-165" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-189-152" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 80px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>THAT'S A TOTAL VALUE OF $7,031!
</b>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-41518" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 58px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>(PLUS AN ADDITONAL $194/MONTH)</b>
</h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-63278-140" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 50px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/1f/b921baf599499c9537a8fd17209f72/Blue-Texture-Background-02.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379-173" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-165-141" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041-169" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_30" style="text-align: center; font-size: 45px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>What makes 12 Minute Affiliate...</b></div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-44568-120" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_40" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>The Easiest Way To Succeed Online</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover borderSolid border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius50 borderLight" id="row--89385-114" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 15px; padding-bottom: 15px; margin: 0px auto; background-color: rgb(46, 194, 254); width: 90%; max-width: 100%; outline: none; color: rgb(255, 255, 255);">
<div id="col-full-151-108" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-67832-163" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>HERE’S EVERYTHING YOU’RE GETTING</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-165" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-156" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-157" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/4e/0c636983a14adfac0b0b86bdd3e10b/laptoprt_1369x746-4-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148-172" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-26625-155" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>DFY FUNNELS (Value: $2,240)</b>
</h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_divider-12998-111" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-170" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Done-For-You Affiliate Funnels in the HOTTEST Niche Markets:
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-165" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">No HTML, no coding, no hosting, and no techie stuff! The 12 Minute Affiliate System includes ready-to-go affiliate funnels in the hottest and MOST PROFITABLE niche markets (like 'making money from home', 'weight loss', and 'personal development').  <div><br></div>
<div>Just personalize the system so that the leads go onto YOUR email list, and affiliate commissions go to YOUR bank account!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105-163" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130-120" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-112-106" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/8f/476f2323114f51a6fc4eded09b8caa/12ma---laptom-for-emails.png" class="elIMG ximg" alt="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-109-172" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>DFY EMAILS (Value: $3,200)</b>
</h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133-121" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142-152" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Professionally Written Follow-Up Messages (Done-For-You)
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-102-139" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">The fortune is in the follow-up! That's why the 12 Minute Affiliate system includes MONTHS worth of professionally written done-for-you follow up messages! <div><br></div>
<div>No hiring expensive copywriters, and nothing for you to write yourself. You'd EASILY pay a professional copywriter $40 -$50 or more (per email). But with 12 Minute Affiliate, it's all included!
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103-143" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-157-160" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-168-142" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-111-175" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/74/7faa51282048b1b1ded1c6678583cc/laptoprt_1369x746-3-.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148-164-158" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-122-149" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>12 MINUTE SETUP
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-144-114" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-74877-131-122" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Copy/Paste Simple Instructions
<div>(No Tech Skills Needed)</div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-111-134" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Our simple step-by-step instructions make it easy for even the newest online marketer to have the system set up QUICKLY. The fastest we've ever seen someone set the system up is 12 short minutes! But even if it takes you a little longer, you can still have it all set up BEFORE you go to bed tonight!<div><b style="font-family: inherit; background-color: initial;"><br></b></div>
<div><b style="font-family: inherit; background-color: initial;">There's even an option for us to set it up FOR YOU!!</b></div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105-124-102" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130-164-158" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-112-137-126" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/cd/4cdd48711f46249c385103a4294b94/laptoplt_1369x746-3-.png" class="elIMG ximg" alt="">
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-26625-109-167-119" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>E-Z FUNNEL WIZARD <br>(Value: $97/Month)</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133-103-117" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142-166-114" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Create CUSTOM "On Demand" Funnels In Minutes
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-102-147-109" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Similar funnel-building systems cost $97/month or more! And they're not as easy to use as the 12 Minute Affiliate funnel Wizard
. <div>
<br><div>With Funnel Wizard, you can create your own custom affiliate funnels in as little as 5 MINUTES! No coding or copy-writing needed!</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103-131-130" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-157-134-188" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-168-106-179" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-111-122-184" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/46/cbe31296e043718c71061c3cfedccc/Laptop-3D-Image.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-148-164-160-156" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-122-152-151" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>PRIVATE COMMUNITY <br>(Value: $97/Month)</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-144-116-165" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-131-177-132" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Private Facebook Community &amp; Free Private Training
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-111-108-187" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">The free monthly trainings alone are easily worth $97/month. But when you add in access to a mastermind of members who are already crushing it, this feature alone is worth more than the price of the system! <div>
<br><div>Now you can be in business FOR yourself, but not BY yourself!
</div>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-105-124-120-111" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-130-164-167-144" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-59823-112-137-178-154" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/97/f3c384c952462fa8b60f94d88ada65/laptoplt-traffic_1369x746-2-.png" class="elIMG ximg" alt="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-109-167-173-118" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>DONE-FOR-YOU TRAFFIC!</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-133-103-131-110" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-142-166-130-148" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Done-For-You Traffic Solution -
<div>As Easy As Ordering A Pizza</div>
</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-102-147-145-178" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 20px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Traffic is the life-blood of your online business. And we've just made it EASIER THAN ORDERING A PIZZA!  Our easy traffic solution allows you to get targeted niche traffic in MINUTES (based on YOUR BUDGET). <div>
<br><div>Just choose how much traffic you want, and we’ll take care of it for you!</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-103-131-137-155" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937-150" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137-131" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114-105" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379-103-117" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 20px 0px 0px; outline: none;">
<div id="col-full-165-147-118" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041-105-144" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_35" style="text-align: center; font-size: 45px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>BUT THAT'S NOT ALL! WE'RE ALSO GIVING YOU...</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-44568-126-136" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_50" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>over $1,590 IN <u>FREE BONUSES</u>!</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover borderSolid border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius50 borderLight" id="row--89385-115-157" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 15px; padding-bottom: 15px; margin: 0px auto; background-color: rgb(46, 194, 254); width: 90%; max-width: 100%; outline: none; color: rgb(255, 255, 255);">
<div id="col-full-151-160-184" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-67832-127-146" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>FOR A LIMITED TIME: HERE'S WHAT YOU'RE GETTING...</b></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128-112" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116-122" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-178-167" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/7e/a261b2127b489f9aaa9a9f0af8daee/Magazine-Stack-Bonus-1.png" class="elIMG ximg" alt="" width="450">
</div>
</div>
</div>
<div id="col-right-148-143-137" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134-172" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #1: The Success Library <br><i>(a $497 Value)</i></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142-122" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-168-188" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Instant access to a library of personal development training! Discover how to unlock your true potential, balance your life, end procrastination, and MUCH MUCH MORE! Over 15 titles in all!</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128-143-113" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116-178-133" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elMargin0 ui-droppable elAlign_center hiddenElementTools de-editable" id="tmp_image-59823-178-137-188" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/ee/802b44ddc64ba2ae253645ff5ffd2e/Ring-Spiral-Binder_-Bonus-2.png" class="elIMG ximg" alt="" width="350">
</div>
</div>
</div>
<div id="col-right-148-143-153-184" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134-146-144" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #2: The Free Traffic Guide <font style="" color="#e43b2c"><i style="color: rgb(232, 138, 23);">(a $97 Value)</i></font></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142-126-102" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-168-101-130" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">Discover 16 ways to get FREE TRAFFIC to your website! Including: How to get free traffic from Twitter &amp; Facebook, how to get traffic from other people's blogs, and how to get traffic just by posting pictures online! </h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-128-110-123" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-116-169-176" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-59823-178-188-122" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/62/9764a89d0d4bdebddd5a339b5fa95c/modernsoftwarebox_506x599-2-.png" class="elIMG ximg" alt="" width="400">
</div>
</div>
</div>
<div id="col-right-148-143-103-102" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-74877-134-167-116" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 42px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>BONUS #3: Hot Product Promos<br><font color="#e43b2c"><i style="color: rgb(232, 138, 23);">( a $997/Year Value)</i></font></b>
</h2>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-142-161-157" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-168-140-188" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 30px; color: rgba(255, 255, 255, 0.75);" data-bold="inherit" data-gramm="false" contenteditable="false">We continually partner with the creators of some of the HOTTEST selling products on the internet. Normally, these offers are off-limits to new affiliate marketers.  But because you're part of 12 Minute Affiliate, you'll be able to promote these offers and pocket HUGE commissions!</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937-182-129" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137-139-102" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114-165-153" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-189-152-174" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_50" style="text-align: center; font-size: 80px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>THAT'S A TOTAL VALUE OF $7,031!
</b>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-41518-162" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 58px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>(PLUS AN ADDITONAL $194/MONTH)</b>
</h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection nosticky bgCover" id="container-20060-143-111" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 80px; outline: none; background-image: url("//easy.12minuteaffiliate.com/hosted/images/3e/02439d53f142d79ae757a890635284/beach-coastline-daylight-1268871.jpg");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865-139-136" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125-158-147" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-78513" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow2" style="text-align: center; font-size: 30px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>
And Check This Out! Just For Giving The System An Honest Try, We'll Give You...</b></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324-133-184" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>A <u>FREE VACATION</u> TO ONE OF OVER A DOZEN EXOTIC LOCATIONS!</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-87138-151" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 30px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 28px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">Here’s how it works…</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-71719" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 30px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_25" style="text-align: left; font-size: 30px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<div>
</div>
<div>
<b>FIRST: </b>Join the 12 Minute Affiliate System.</div>
<div>
<b>NEXT: </b>Complete your quick-start checklist, and order some done-for-you traffic.</div>
<div>
<b>THEN:</b> P<span style="font-family: inherit; background-color: initial;">ost in our members-only Facebook group where you’d like us to send you!</span>
</div>
<div><span style="font-family: inherit; background-color: initial;"><br></span></div>
<div><span style="font-family: inherit; background-color: initial;">THAT'S IT!!</span></div>
</h2>
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-96629" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/4c/5a302745da48d89c99f39ce5a9a8fb/Vacations-Wide.jpg" class="elIMG ximg" alt="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-15798" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 23px" data-bold="inherit" data-gramm="false" contenteditable="false"><i>
(More Vacation Choices Available In Your Member's Area - No, This Is Not A Time-Share)</i></h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--93017" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding: 20px 0px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-181" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-18220" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow3 mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>ACTUAL MEMBERS GETTING <u>REAL VACATIONS</u></b></font></h1>
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-49355" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 5px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/a5/e0c7504a38454799494516d6232a2f/Testimonial-Map-18-transparent.png" class="elIMG ximg noborder" alt="">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-159-116-107" data-title="Section - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 40px; color: rgb(255, 255, 255); background-color: rgba(0, 0, 0, 0); outline: none; margin-top: -80px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/b6/d9504534fd4d44ac568bc618d40b9d/12-ma-bg.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-103-161-158" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-122-185-130" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-164-148-133" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-138-151-138" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!<div>Keep The System For LESS THAN $1.60/Day!</div>
</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-115-185-133" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 35px;" rel="noopener noreferrer" id="undefined-494-681-148">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-119-130-157" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-150-178-114" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585-109-100-114" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily clearfix hide cdLabelBold cdBlack cdStyleCircleLine wideCountdownSize4 cdLabelBlack" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold cdBlack cdStyleCircleLine wideCountdown-demo is-countdown wideCountdownSize4 cdLabelBlack" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover100" id="container-29504-107-165-185-123" data-title="Section - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 100px; color: rgb(255, 255, 255); background-color: rgb(0, 0, 0); outline: none; margin-top: 75px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/f1/dd1f1cca0747e899ad2aedfa6e7771/12ma-Background2-02.png");' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--12494-147-120-123-143" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; width: 100%; max-width: 100%; outline: none;">
<div id="col-left-181-158-169-173-178" class="innerContent col_left ui-resizable col-md-7" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-94574-142-117-189-176" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 35px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-91865-143-138-134-103" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="tmp_button-34128-167-108-162-122" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elButtonCorner60 elBtnHP_20" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 20px;" rel="noopener noreferrer" id="undefined-298-594-170-212">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
</div>
</div>
<div id="col-right-153-183-139-102-138" class="innerContent col_right ui-resizable col-md-5" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-68268-179-100-122-189" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center;font-size: 32px" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Try The System In The Next:</b>
</h1>
</div>
<div class="de elCountdownEvergreenDaily elAlign_center elMargin0 ui-droppable de-editable" id="tmp_countdown_daily-64585-139-181-157-174" data-de-type="countdown-daily" data-de-editing="false" data-title="Daily Countdown (evergreen)" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 10px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<div class="wideCountdownEvergreenDaily  clearfix hide cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine" data-time="23" data-minutes="30" data-seconds="0" data-tz="America/New_York" data-url="#" data-lang="eng" style="">countdown</div>
<div class="wideCountdownEvergreenDaily clearfix cdLabelBold wideCountdownSize2 cdWhite cdLabelWhite cdStyleCircleLine wideCountdown-demo is-countdown" style="" data-time="23"><span class="countdown-row countdown-show3"><span class="countdown-section"><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Hours</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Minutes</span></span><span class="countdown-section"><span class="countdown-amount">00</span><span class="countdown-period">Seconds</span></span></span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-63278-158" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 50px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/14/5dfaa514864e7abc80aefc7e8f5f9b/12-min-main-cover-6.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="desktop">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379-137" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-165-150" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041-150" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_30" style="text-align: center; font-size: 50px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><div>
<b>WHY YOU MUST GRAB
</b>
</div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-44568-121" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>THE 12 MINUTE AFFILIATE SYSTEM TODAY...
</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/71/ceffa0ef274db8b8ead701ece0c575/Easy-Icon-2.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
<div id="col-right-148-145" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT'S SIMPLE - EVEN FOR BEGINNERS!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Most systems created to help you profit online are NOT as simple (or as easy) as they claim. There's usually loads of 'techie" stuff to do, and you start to hit speed-bumps and get frustrated 5 minutes in.<div><br></div>
<div>But with 12 Minute Affiliate, even the newest newbie can start getting results with the system their very first week!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>YOU CAN PROFIT DAILY!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_divider-12998-107-116" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Once you've got everything up and running, it's not uncommon to earn online commissions multiple times a week (or even multiple times a day). <div>
<br>And while there's no way to know exactly how much you'll make, we'll tell you that our TOP members regularly make online affiliate commissions
on an almost DAILY basis!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/82/f6f4b454bb4b7f87283eddc2f64301/Easy-Money-2.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-163" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/62/3ea1086b784425a6549e85e7d54333/Multiple-Streams-of-Income-Icon.png" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
<div id="col-right-148-145-134" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT CREATES MULTIPLE STREAMS OF INCOME!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Imagine you had a system that AUTOMATICALLY promotes multiple different affiliate products FOR YOU, simultaneously!
<div>This means that you could earn commissions from more than one product the same day! </div>
<div><br></div>
<div>Again, this is quite a common occurrence for our TOP members. And who knows.. it could be for you too!!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>FAST AND EASY SET-UP!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_divider-12998-107-116-149" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Even if you're not very tech savvy and it takes you longer than 12 minutes, there's a 90% chance you'll be able to have the ENTIRE system up and running BEFORE you go to bed tonight!<div> <div>Heck, there's even an option to have our team set your entire system up FOR YOU!!
</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/59/de5e2fd5dc4373a7c3046f5d40bddf/Fast-Easy-Set-Up.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-163-166" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/76/ab07acc3254c649ac44721dc9d533c/Quick-Results.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
<div id="col-right-148-145-134-188" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>YOU CAN SEE RESULTS QUICKLY!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Once the system is set-up, and you've gotten your done-for-you traffic, (both of which can be done today) seeing results shouldn't take very long!<div><br></div>
<div>Most members start seeing their email list grow within the first<div>
<div>several days, and it's not uncommon for members to see their
</div>
<div>first commissions not long after that!</div>
</div>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>WORK FROM ANYWHERE - (LAPTOP LIFESTYLE)
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">You only need 3 things to get results with 12 Minute Affiliate:
<div>1. A Desktop or Laptop computer
</div>
<div>2. An internet connection
</div>
<div>3. A willingness to follow simple instructions consistently!
</div>
<div><br></div>
<div>Therefore, you can LITERALLY work from anywhere in the world!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133-187" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/68/612e9a217b4024a5aea34cdef4c41f/Work-Anywhere.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181-157" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142-134" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-163-166-142" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/1b/d46c92b06541eda75047a95e3a6ad3/Easy-Money.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
<div id="col-right-148-145-134-188-171" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163-153" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT'S THE PERFECT SIDE BUSINESS!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108-120" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129-157" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Still have a full-time job and a packed schedule? That's no problem!
You can literally grow your affiliate marketing business <div>(using the 12 Minute Affiliate System) using whatever spare time you've got! </div>
<div>
<br><span style="font-family: inherit; background-color: initial;">Only have 5 hours a week on a Sunday evening? Cool! Only have about an hour each night before you go to bed? That works too!</span>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119-161" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143-177" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167-132" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>THE MONEY IS IN THE LIST</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179-132" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167-140" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">If you've been trying to make money online for more than 5 minutes, then you've probably heard the saying "The Money Is In Your List".<div><br></div>
<div>Having a niche-specific email list that you can offer affiliate products to is the life-blood of your business &amp; the #1 secret of $100K earners! </div>
<div><span style="font-family: inherit; background-color: initial;"><br></span></div>
<div><span style="font-family: inherit; background-color: initial;">With 12 Minute Affiliate, building your list is a breeze!</span></div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135-159" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-66512-152-133-187-164" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/18/5a45a3cd6b478681e3ad77264a17ec/Grow-Email-List.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181-157-130" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142-134-135" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-66512-163-166-142-152" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/64/0b2083efd242c385cc244b80e76242/Automatic-Email-Followup.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
<div id="col-right-148-145-134-188-171-183" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163-153-132" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>THE FORTUNE IS IN THE FOLLOW-UP</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108-120-108" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129-157-116" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">You've probably heard the saying "The Fortune Is In The Follow-Up".
Well if you have, you know it's 100% TRUE! But following up with your leads can be VERY time consuming. <div>
<br>That's why 12 Minute Affiliate comes with MONTHS of done-for- you follow up emails built into the system! Just let the system follow up FOR YOU while you're sleeping or with your family!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119-161-179" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143-177-104" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167-132-129" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>NO CREATING YOUR OWN PRODUCTS OR WEBSITES!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179-132-182" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167-140-151" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">One of the biggest challenges most people face when trying to start their own online business is knowing WHAT to sell, and HOW to sell it!
With affiliate marketing, knowing WHAT to sell is easy because someone else has already created the product. <div><br></div>
<div>And with the 12 Minute Affiliate System, knowing HOW to sell it has already been taken care of!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135-159-102" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133-187-164-155" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/79/906fdf27dc4e1a8b58dcfea91eda46/No-Coding.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="300" height="300">
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937-182-161" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137-139-106" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114-165-102" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-189-152-127" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>AND OH YEAH, ONE MORE THING...</b></font></h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgCover emptySection" id="container-63278-158-173" data-title="Section - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 50px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/14/5dfaa514864e7abc80aefc7e8f5f9b/12-min-main-cover-6.jpg"); outline: none;' data-trigger="none" data-animate="fade" data-delay="500" data-hide-on="mobile">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--81379-137-142" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-165-150-172" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-63041-150-135" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 10px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_30" style="text-align: center; font-size: 50px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><div>
<b>WHY YOU MUST GRAB
</b>
</div></h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-44568-121-141" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>THE 12 MINUTE AFFILIATE SYSTEM TODAY...
</b></font></h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-119" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-165" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-151" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/71/ceffa0ef274db8b8ead701ece0c575/Easy-Icon-2.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
</div>
</div>
<div id="col-right-148-145-174" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-105" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT'S SIMPLE - EVEN FOR BEGINNERS!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-189" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-120-127" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Most systems created to help you profit online are NOT as simple (or as easy) as they claim. There's usually loads of 'techie" stuff to do, and you start to hit speed-bumps and get frustrated 5 minutes in.<div><br></div>
<div>But with 12 Minute Affiliate, even the newest newbie can start getting results with the system their very first week!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-129" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-160" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-135" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/82/f6f4b454bb4b7f87283eddc2f64301/Easy-Money-2.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-160" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>YOU CAN PROFIT DAILY!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_divider-12998-107-116-169" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-120-185-136" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Once you've got everything up and running, it's not uncommon to earn online commissions multiple times a week (or even multiple times a day). <div>
<br>And while there's no way to know exactly how much you'll make, we'll tell you that our TOP members regularly make online affiliate commissions
on an almost DAILY basis!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-161" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-150" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-188" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-163-128" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/62/3ea1086b784425a6549e85e7d54333/Multiple-Streams-of-Income-Icon.png" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
</div>
</div>
<div id="col-right-148-145-134-154" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-152" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT CREATES MULTIPLE STREAMS OF INCOME!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-143" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-162" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Imagine you had a system that AUTOMATICALLY promotes multiple different affiliate products FOR YOU, simultaneously!
<div>This means that you could earn commissions from more than one product the same day! </div>
<div><br></div>
<div>Again, this is quite a common occurrence for our TOP members. And who knows.. it could be for you too!!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-140" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-109" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133-170" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/59/de5e2fd5dc4373a7c3046f5d40bddf/Fast-Easy-Set-Up.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-151" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>FAST AND EASY SET-UP!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-163" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_subheadline-80200-120-185-132-124" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Even if you're not very tech savvy and it takes you longer than 12 minutes, there's a 90% chance you'll be able to have the ENTIRE system up and running BEFORE you go to bed tonight!<div> <div>Heck, there's even an option to have our team set your entire system up FOR YOU!!
</div>
</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-117" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181-162" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142-156" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-163-166-172" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/76/ab07acc3254c649ac44721dc9d533c/Quick-Results.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
</div>
</div>
<div id="col-right-148-145-134-188-123" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163-149" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>YOU CAN SEE RESULTS QUICKLY!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108-141" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129-122" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Once the system is set-up, and you've gotten your done-for-you traffic, (both of which can be done today) seeing results shouldn't take very long!<div><br></div>
<div>Most members start seeing their email list grow within the first<div>
<div>several days, and it's not uncommon for members to see their
</div>
<div>first commissions not long after that!</div>
</div>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119-108" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143-136" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-66512-152-133-187-100" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/68/612e9a217b4024a5aea34cdef4c41f/Work-Anywhere.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167-107" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>WORK FROM ANYWHERE - (LAPTOP LIFESTYLE)
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179-108" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167-173" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">You only need 3 things to get results with 12 Minute Affiliate:
<div>1. A Desktop or Laptop computer
</div>
<div>2. An internet connection
</div>
<div>3. A willingness to follow simple instructions consistently!
</div>
<div><br></div>
<div>Therefore, you can LITERALLY work from anywhere in the world!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135-133" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181-157-143" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142-134-175" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-66512-163-166-142-164" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/1b/d46c92b06541eda75047a95e3a6ad3/Easy-Money.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
</div>
</div>
<div id="col-right-148-145-134-188-171-129" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163-153-134" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>IT'S THE PERFECT SIDE BUSINESS!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108-120-139" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129-157-126" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">Still have a full-time job and a packed schedule? That's no problem!
You can literally grow your affiliate marketing business <div>(using the 12 Minute Affiliate System) using whatever spare time you've got! </div>
<div>
<br><span style="font-family: inherit; background-color: initial;">Only have 5 hours a week on a Sunday evening? Cool! Only have about an hour each night before you go to bed? That works too!</span>
</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119-161-115" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143-177-172" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133-187-164-109" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/18/5a45a3cd6b478681e3ad77264a17ec/Grow-Email-List.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167-132-131" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>THE MONEY IS IN THE LIST</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179-132-123" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167-140-169" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">If you've been trying to make money online for more than 5 minutes, then you've probably heard the saying "The Money Is In Your List".<div><br></div>
<div>Having a niche-specific email list that you can offer affiliate products to is the life-blood of your business &amp; the #1 secret of $100K earners! </div>
<div><span style="font-family: inherit; background-color: initial;"><br></span></div>
<div><span style="font-family: inherit; background-color: initial;">With 12 Minute Affiliate, building your list is a breeze!</span></div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135-159-178" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-175-181-157-130-165" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-115-142-134-135-182" class="innerContent col_left ui-resizable col-md-4" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-66512-163-166-142-152-126" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/64/0b2083efd242c385cc244b80e76242/Automatic-Email-Followup.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
</div>
</div>
<div id="col-right-148-145-134-188-171-183-123" class="innerContent col_right ui-resizable col-md-8" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-138-163-153-132-145" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>THE FORTUNE IS IN THE FOLLOW-UP</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-170-108-120-108-138" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-147-129-157-116-137" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">You've probably heard the saying "The Fortune Is In The Follow-Up".
Well if you have, you know it's 100% TRUE! But following up with your leads can be VERY time consuming. <div>
<br>That's why 12 Minute Affiliate comes with MONTHS of done-for- you follow up emails built into the system! Just let the system follow up FOR YOU while you're sleeping or with your family!</div>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--66610-152-144-135-119-161-179-105" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row - Clone - Clone - Clone - Clone - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-left-171-157-121-178-143-177-104-163" class="innerContent col_left ui-resizable col-md-8" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-66512-152-133-187-164-155-134" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" data-element-theme="customized" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/79/906fdf27dc4e1a8b58dcfea91eda46/No-Coding.jpg" class="elIMG ximg el_media_theme9 noborder" alt="" style="" width="200" height="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-150-127-180-167-132-129-108" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 15px; outline: none; cursor: pointer; font-family: Oswald, Helvetica, sans-serif !important;" data-google-font="Oswald" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: left; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>NO CREATING YOUR OWN PRODUCTS OR WEBSITES!
</b></h1>
</div>
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="tmp_divider-12998-107-116-149-179-132-182-154" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-80200-120-185-132-167-140-151-181" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: left; font-size: 25px; color: rgba(255, 255, 255, 0.9);" data-bold="inherit" data-gramm="false" contenteditable="false">One of the biggest challenges most people face when trying to start their own online business is knowing WHAT to sell, and HOW to sell it!
With affiliate marketing, knowing WHAT to sell is easy because someone else has already created the product. <div><br></div>
<div>And with the 12 Minute Affiliate System, knowing HOW to sell it has already been taken care of!</div>
</h2>
</div>
</div>
</div>
<div id="col-right-148-145-132-178-135-159-102-171" class="innerContent col_right ui-resizable col-md-4" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px"></div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--25937-182-161-174" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row - Clone" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-137-139-106-182" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elSeperator elMargin0 ui-droppable de-editable" id="divider-99114-165-102-130" data-de-type="divider" data-de-editing="false" data-title="Divider" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="elDivider elDividerStyle1 padding10-top padding10-bottom">
<div class="elDividerInner" data-align="center" data-height-border="3" data-style="dashed" style="border-color: rgb(46, 194, 254);"></div>
</div>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26625-189-152-127-154" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#4966b4"><b>AND OH YEAH, ONE MORE THING...</b></font></h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="container-20060-143-189-147-111" data-title="Section - Clone - Clone - Clone - Clone" data-block-color="0074C7" style='padding-top: 50px; padding-bottom: 70px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: 0px;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--39865-139-142-161-159" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-125-158-183-119-114" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-27846" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 30px;" data-bold="inherit" data-gramm="false" contenteditable="false">
There Is Absolutely NO RISK On Your Part With Our...</h2>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-45324-133-179-107-187" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<font color="#0174c7"><b>60-Day </b></font><b style="font-family: inherit; background-color: initial;">100% Money Back Guarantee</b>
</h1>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius50" id="row--66233" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding: 30px 20px; margin: 15px 0px 0px; outline: none; background-color: rgba(1, 116, 199, 0.1);">
<div id="col-left-156" class="innerContent col_left ui-resizable col-md-5" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-37095" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="75" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false" data-timed-style="no-action">
<img src="//easy.12minuteaffiliate.com/hosted/images/dc/301a7e98c14e86b8e1983bc63bdd5c/60-Day-Money-Back--TRANSPARANT.png" class="elIMG ximg" alt="">
</div>
</div>
</div>
<div id="col-right-125" class="innerContent col_right ui-resizable col-md-7" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_paragraph-26889" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgb(71, 71, 71); font-size: 22px;" data-gramm="false" contenteditable="false">For a full 60 days, and for less than 10 measly bucks, you can give the 12 Minute Affiliate System a test drive and put it to work for you.
<div>
<br><div>There aren’t too many systems out there online that are willing to put their money where their mouth is. . . but WE ARE!</div>
<div><br></div>
<div>We will let you test drive the entire system for the price of a Starbucks coffee and donut and if you like it, you get to keep it!!! </div>
<div><br></div>
<div>But, if for some bizarre reason you don’t like the 12 Minute Affiliate System, just let us know within the refund period, and we’ll cancel your account and refund every penny…</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--78372" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-107" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-30789" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_40" style="text-align: center; font-size: 65px; color: rgb(73, 102, 180);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>~ NO QUESTIONS ASKED!!! ~</b></h1>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection fullContainer bgCover containerWithVisibleOverflow" id="container-60142" data-title="Buying Section" data-block-color="0074C7" style='padding-top: 60px; padding-bottom: 50px; margin-top: 0px; outline: none; background-color: rgba(255, 255, 255, 0); background-image: url("//easy.12minuteaffiliate.com/hosted/images/be/215cfca6964828a0b894598385959e/12-min-vector-background.jpg");' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row-159" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 10px; padding-bottom: 10px; margin: 0px auto; outline: none; width: 90%; max-width: 100%;">
<div id="col-full-130-169" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-67400-116" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: center; font-size: 40px; color: rgb(232, 138, 23);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>Now That You Have <u>NO RISK</u>, You Also Have <u>NO EXCUSES!</u></b></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-26835-161" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 0px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' data-google-font="Fjalla+One" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><div><b>HERE'S EVERYTHING YOU'RE GETTING...</b></div></h1>
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable hiddenElementTools de-editable" id="tmp_image-92320-166" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="scroll" data-animate="scale" data-delay="100" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/fa/70c512c6fa4a5886bb3a0a752136bd/12MA-Bundle-.png" class="elIMG ximg" alt="" width="">
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-42698-160" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: -20px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" data-google-font="Lato" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: center; font-size: 38px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<div><b>SPECIAL OFFER:</b></div>
<div>WHEN YOU ACTIVATE YOUR SYSTEM TODAY!</div>
</h1>
</div>
</div></div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row-120" data-trigger="none" data-animate="fade" data-delay="500" data-title="Buy 12 Min Affiliate Conditions" style="padding: 25px 40px 60px; margin: 0px auto; outline: none; background-color: rgba(255, 255, 255, 0.65); width: 80%; max-width: 100%; color: rgb(255, 255, 255);">
<div id="col-full-105-129-141" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;"><div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_headline1-10937-147" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_35" style="text-align: center; font-size: 38px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>I UNDERSTAND THAT:</b></h1> 
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_22 hiddenElementTools de-editable" id="tmp_list-14856-177" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-margin-top="15px">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgb(45, 45, 45);" contenteditable="false">
<li style="font-size: 25px;">
<i class="fa fa-fw fa-check" style="color: rgb(73, 102, 180);" contenteditable="false"></i>I'll get access to DONE-FOR-YOU AFFILIATE SALES FUNNELS  in the hottest niche markets! <i><b>(a $2,240 value)</b></i>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​I'll have PROFESSIONAL EMAIL FOLLOW-UPS written for me and ready to <u>make sales while I sleep</u>! <i><b>(a $3,200 value)</b></i>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i class="fa fa-fw fa-check" style="color: rgb(73, 102, 180);" contenteditable="false"></i>Setting up the system is as easy as copy &amp; paste <b><i>(or I can just have the support staff set everything up FOR ME)</i></b>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​I’ll be able to create CUSTOM AFFILIATE FUNNELS on demand in a matter of minutes <b><i>(a $97/month value)</i></b><br>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​I will get access to REAL SUPPORT from people based in the USA, and access to the PRIVATE FACEBOOK GROUP! <b>(a $97/month value)</b><br>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​I understand that getting traffic to the system is based on MY budget and is LITERALLY AS EASY AS ORDERING A PIZZA <b><i>(PRICELESS)</i></b><br>
</li>
</ul>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_22 de-editable" id="list-62596-175" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false" data-margin-top="15px">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" style="color: rgb(45, 45, 45);" contenteditable="false">
<li style="font-size: 25px;">
<i class="fa fa-fw fa-check" style="color: rgb(73, 102, 180);" contenteditable="false"></i><u>BONUS #1:</u> I'll get instant access to the ULTIMATE SUCCESS LIBRARY of personal development training! <i style="color: rgb(73, 102, 180);"><b>(a $497 value)</b></i>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​<u>BONUS #2:</u> I'll get access to the FREE TRAFFIC guide that shows me 16 ways to get free traffic to any website <i style="color: rgb(73, 102, 180);"><b>(a $97 value)</b></i>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i class="fa fa-fw fa-check" style="color: rgb(73, 102, 180);" contenteditable="false"></i><u>BONUS #3:</u> I'll be getting to promote EXCLUSIVE "HOT PRODUCTS" that are typically "off limits" to newbies! <b><i style="color: rgb(73, 102, 180);">(a $997 value)</i></b>
</li>
<li style="font-size: 25px; margin-top: 15px;">
<i style="color: rgb(73, 102, 180);" class="fa fa-fw fa-check" contenteditable="false"></i>​<u>BONUS #4:</u> I'll be getting a <u>FREE VACATION</u> just for giving the system an HONEST try! <i><b>(a $997 value)</b></i> <br>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-37517-104" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 30px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_45" style="text-align: center; font-size: 58px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><b>THAT'S A TOTAL VALUE OF $8,222!</b></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-19241-150" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 40px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-36272-107" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days <u>RISK FREE</u> For Just $9.95!<br>(Keep The System For As Little As $47/Month - Cancel At Any Time)</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="button-44465-121" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elBtnHP_20 elButtonCorner10 mfs_30" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 52px;" rel="noopener noreferrer" id="undefined-114-172"><span class="elButtonMain">Yes! I Want To Try The System</span><span class="elButtonSub mfs_14" style="font-size: 18px;">If You Like It - Keep The System For LESS Than The Price of a Cup of Coffee a Day!</span></a>
</div>
</div></div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<style id="bold_style_tmp_headline1-67400">#tmp_headline1-67400 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26835">#headline-26835 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-42698">#tmp_headline1-42698 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-10937">#tmp_headline1-10937 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-37517">#headline-37517 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-19241">#headline-19241 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_button-44465">#button-44465 .elButtonFlat:hover{ background-color: #c37413 !important;} #button-44465 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}#button-44465 .elButtonSubtle:hover{ background-color: #c37413 !important;}#button-44465 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }#button-44465 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }#button-44465 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }#button-44465 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }#button-44465 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }#button-44465 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }</style>
<style id="bold_style_headline-86361">#headline-86361 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-45324-133">#tmp_headline1-45324-133 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-87138">#headline-87138 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 emptySection bgCover" id="container-37492-129" data-title="Section - Clone" data-block-color="0074C7" style='padding-top: 40px; padding-bottom: 45px; background-image: url("//easy.12minuteaffiliate.com/hosted/images/52/856359dd5143e181d2a3152c212614/background-Cover-4.png"); outline: none; margin-top: -5px;' data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--83332-188" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-101-136" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-34911-138" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style='margin-top: 15px; outline: none; cursor: pointer; font-family: "Fjalla One", Helvetica, sans-serif !important;' aria-disabled="false" data-google-font="Fjalla+One">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 deUppercase mfs_45" style="text-align: center; font-size: 65px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false"><font color="#0174c7"><b>Still HAVE A FEW QUESTIONS?
</b></font></h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-71059-170" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer; font-family: Lato, Helvetica, sans-serif !important;" aria-disabled="false" data-google-font="Lato">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0 mfs_30" style="text-align: center; font-size: 35px; color: rgb(45, 45, 45);" data-bold="inherit" data-gramm="false" contenteditable="false">
<b>Check Out The Answers To These 12 Minute Affiliate FAQ's</b>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover border3px cornersAll shadow0 P0-top P0-bottom P0H noTopMargin radius25 borderLight borderDashed" id="row--20755" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding: 40px 25px; margin: 35px 0px 0px; outline: none; background-color: rgba(255, 255, 255, 0); border-color: rgb(73, 102, 180);">
<div id="col-left-115" class="col-md-6 innerContent col_left ui-resizable" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="tmp_list-32609" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b> What is 12 Minute Affiliate?
</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-45497" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">12 Minute Affiliate is a revolutionary new system that simplifies the process of making online commissions with affiliate marketing.<div><span style="color: inherit; background-color: rgba(255, 255, 255, 0);"><br></span></div>
<div><span style="color: inherit; background-color: rgba(255, 255, 255, 0);">With 12 Minute Affiliate there are no products to create, websites to host, copy to write, or techie stuff to figure out!</span></div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-60104" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Do I Need Prior Experience or Training?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-73797" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>NO - The 12 Minute Affiliate System is 100% newbie-friendly. So, even if you're a complete newbie, you can use this system with ease.</div>
<div><span style="color: inherit; background-color: rgba(255, 255, 255, 0);"><br></span></div>
<div><span style="color: inherit; background-color: rgba(255, 255, 255, 0);">But just in case you’re nervous, we also have a private Facebook community, ongoing trainings (for FREE), and you can even get private 1-on-1 coaching!</span></div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-81424" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>What Makes 12-Minute Affiliate Different From The Rest?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-97479" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>The #1 difference that separates 12 Minute Affiliate System from everything else is the simplicity of the process. All of the websites, funnels, emails, etc... are already done for you. You just have to personalize the system so that YOU get the affiliate commissions. The system answers the #1 question that keeps most people from ever getting results: <i>“What do I do next?”
</i>
</div>
<div><i><br></i></div>
<div>
</div>
<div>Most other systems claim to be easy and “non-techie”... but they’re not! 12 Minute Affiliate really is! Heck, we even provide a done-for-you traffic service (based on your budget) so that you don’t have to figure out how to get targeted traffic to your new affiliate funnels.</div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-68237" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>But What About Traffic, Copywriting, Finding Products, And All The Other Stuff I’ll Need To Do.</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-46704" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>You don’t have to worry about any of that stuff, because we’ve got you covered. We’ve been helping people succeed online for more than 11 years, so we know the challenges and obstacles in your way better than you know them yourself.</div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"><br></span></div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;">All we ask it that you trust that we’ve removed the obstacles for you, and give the system a try TODAY!</span></div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-93110" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Is This A "Get Rich-Quick" Program?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-90468" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false"><div>NO! This is “Get Everything Up and Running QUICK”. Ultimately, your success will be based on your consistency. But you already know that.</div></div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-94381" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Are You Really Giving Me A Free Vacation Just For Trying The System? Why Would You Do That?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="headline-13785" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>YES! We're really giving you a FREE VACATION, and no, it's not a time-share or anything like that. All you have to do to get your vacation is give the system an <u>HONEST</u> try. Get everything set up, get a little bit of traffic, and then choose from our list of exotic locations.</div>
<div><br></div>
<div>Here's why we do it...</div>
<div><br></div>
<div>I know that if you give the system an HONEST try, then you're going to love it. So I'm willing to ethically bribe you with a free vacation just to get you to give the system a real shot. </div>
<div><br></div>
<div>Once you start getting the results you've always wanted, I know you'll be with us for a long time. </div>
</div>
</div>
</div>
</div>
<div id="col-right-124" class="col-md-6 innerContent col_right ui-resizable" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elBullet elMargin0 ui-droppable mfs_25 hiddenElementTools de-editable" id="list-11769" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Exactly How Does 12-Minute Affiliate Work?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_paragraph-53569" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div><b>It’s Easy...</b></div>
<div><b style="color: inherit;"><br></b></div>
<div>
<b style="color: inherit;">STEP 1:</b><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"> Click the “get started” button on this page to start your no-risk trial for just a few dollars. If you like the system, you can keep it for less than the price of a cup of coffee per day. </span>
</div>
<div><b style="color: inherit;"><br></b></div>
<div>
<b style="color: inherit;">STEP 2:</b><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"> Follow the simple QUICK-START CHECKLIST to get your system up and running (or choose to have us set the system up for you). </span>
</div>
<div><b style="color: inherit;"><br></b></div>
<div>
<b style="color: inherit;">STEP 3:</b><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"> Order some done-for-you traffic to your system based on your budget (it’s literally as easy as ordering a pizza) and from there,  the system builds your list and promotes affiliate products for you while you sleep.</span>
</div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"><br></span></div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;">Every time someone buys one of the affiliate products your system is promoting, YOU keep 100% of the commissions paid to you!</span></div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-30703" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>What Type of Results Can I Expect From
12-Minute Affiliate?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-16783" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>I have no earthly idea. The FASTEST we’ve ever seen someone make their first commission with this system is 48 hours. But that’s not typical.</div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;"><br></span></div>
<div><span style="background-color: rgba(255, 255, 255, 0); color: inherit;">That being said, it’s not uncommon for our members to start seeing people on their email list their very first week, and even see their first affiliate sale shortly thereafter. Ultimately your results are based 100% on YOUR efforts and your ability to follow exact instructions.</span></div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-24158" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>What Are All The Costs Involved?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-24634" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>Great question. As you already know, getting everything set up by yourself would easily cost thousands of dollars. But you won't have to pay anything close to that with our system. </div>
<div><br></div>
<div>Here's a Breakdown</div>
<div>- You try the system for just $9.95<br>- You keep the system for as little as $47/month </div>
<div>- Your auto-responder (which allows you to make sales while you sleep), is only about $0.63 cents a day</div>
<div>- And then your traffic is based on YOUR budget!</div>
</div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-62660" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Is There A Money-Back Guarantee?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-70854" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false"><div>YES! - We offer a 60-Day, Ironclad Money Back Guarantee. If for ANY reason you feel that we didn’t deliver everything that we claimed on this page, or if you're just not happy with the results you are getting from 12 Minute Affiliate, simply submit a refund request within the refund period, and we will return every single penny to you.</div></div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-35913" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>Is There Anything Else I Have To Do Once My System Is Set Up?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-19749" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false"><div>That depends on how much money you want to make and how much success you want to have. If you want to be able to create commissions on demand, the most important thing you can do is join our free trainings and hang out with us in our private Facebook group. Once your system is up and running, I'll show you how to 3X... 5X... or even 10X your results by learning a few key skills you can complete in about 5 hours a week!</div></div>
</div>
<div class="de elBullet elMargin0 ui-droppable mfs_25 de-editable" id="list-10815" data-de-type="list" data-de-editing="false" data-title="icon bullet list" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 25px; outline: none; cursor: pointer;" aria-disabled="false">
<ul class="ne elBulletList elBulletListNew elBulletList2 listBorder0" data-bold="inherit" data-gramm="false" contenteditable="false">
<li style="font-size: 30px;">
<i class="fa-fw fas fa-question-circle" style="color: rgb(73, 102, 180);" contenteditable="false"></i><b>How Do I Get Started?</b>
</li>
</ul>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-33084" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; font-size: 20px;" data-gramm="false" contenteditable="false">
<div>IT'S EASY! </div>
<div><br></div>
<div>STEP 1. Click the button on this page to activate your system test-drive for just $9.95</div>
<div><br></div>
<div>STEP 2. Follow super easy instructions. THAT'S IT!</div>
</div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--44995-140" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 30px 0px 0px; outline: none;">
<div id="col-full-187-131" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-39642-137" data-de-type="headline" data-de-editing="false" data-title="headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<h1 class="ne elHeadline hsSize3 lh4 elMargin0 elBGStyle0 hsTextShadow0 mfs_45" style="text-align: center; font-size: 50px; color: rgba(0, 0, 0, 0.96);" data-bold="inherit" data-gramm="false" contenteditable="false">REGULAR PRICE: <strike style=""><b>$197/Month</b></strike>
</h1>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-79336-169" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 15px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 22px;" data-bold="inherit" data-gramm="false" contenteditable="false">TODAY: Try The System For A FULL 14 Days RISK FREE!<div>Keep The System For LESS THAN $1.60/Day!</div>
</h2>
</div>
<div class="de elBTN elAlign_center elMargin0 ui-droppable de-editable" id="button-75827-164" data-de-type="button" data-de-editing="false" data-title="button" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false" data-elbuttontype="1">
<a href="#open-popup" class="elButton elButtonSize1 elButtonColor1 elButtonRounded elButtonPadding2 elBtnVP_10 elButtonFluid elButtonShadowN1 elButtonTxtColor1 elBTN_b_none elBtnHP_20 elButtonCorner10 mfs_30" style="color: rgb(255, 255, 255); font-weight: 600; background-color: rgb(232, 138, 23); font-size: 35px;" rel="noopener noreferrer" id="undefined-114-780">
<span class="elButtonMain">Try The System For Just $9.95</span>
<span class="elButtonSub mfs_14">If You Like It - Keep The System &amp; LOCK IN A 76% DISCOUNT FOREVER!</span>
</a>
</div>
<div class="de elHeadlineWrapper ui-droppable de-editable" id="headline-44806" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 30px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: center; font-size: 24px;" data-bold="inherit" data-gramm="false" contenteditable="false">
<b><u>ACTIVATE YOUR SYSTEM TODAY</u> </b>AND GET EVERYTHING YOU NEED TO START WINNING!</h2>
</div>
<div class="de elImageWrapper de-image-block elAlign_center elMargin0 ui-droppable de-editable" id="tmp_image-19506" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 40px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/fa/70c512c6fa4a5886bb3a0a752136bd/12MA-Bundle-.png" class="elIMG ximg" alt="" width="550">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<div class="container fullContainer noTopMargin padding20-top padding20-bottom padding40H noBorder borderSolid border3px cornersAll radius0 shadow0 bgNoRepeat emptySection" id="container-80579" data-title="Section" data-block-color="0074C7" style="padding-top: 40px; padding-bottom: 40px; outline: none; background-color: rgb(13, 55, 95);" data-trigger="none" data-animate="fade" data-delay="500">
<div class="containerInner ui-sortable">
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--68318" data-trigger="none" data-animate="fade" data-delay="500" data-title="2 column row" style="padding-top: 0px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-left-167" class="innerContent col_left ui-resizable col-md-3" data-col="left" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elImageWrapper de-image-block elMargin0 elAlign_left ui-droppable de-editable" id="tmp_image-42744" data-de-type="img" data-de-editing="false" data-title="image" data-ce="false" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<img src="//easy.12minuteaffiliate.com/hosted/images/51/2d8d1a71434e96a1a93ed79f81da8e/12min-logo-big.png" class="elIMG ximg" alt="" width="200">
</div>
</div>
</div>
<div id="col-right-175" class="innerContent col_right ui-resizable col-md-9" data-col="right" data-trigger="none" data-animate="fade" data-delay="500" data-title="2nd column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_subheadline-20580" data-de-type="headline" data-de-editing="false" data-title="sub-headline" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" data-gramm="false" style="margin-top: 20px; outline: none; cursor: pointer;" aria-disabled="false">
<h2 class="ne elHeadline hsSize2 lh3 elMargin0 elBGStyle0 hsTextShadow0" style="text-align: right; font-size: 22px; color: rgb(255, 255, 255);" data-bold="inherit" data-gramm="false" contenteditable="false">
<a href="https://www.12minuteaffiliate.com/income-disclaimer" id="link-59922" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(255, 255, 255);">DISCLAIMER</a> | <a href="https://www.12minuteaffiliate.com/affiliates" id="link-20997" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(255, 255, 255);">AFFILIATES</a> | <a href="https://www.12minuteaffiliate.com/privacy-policy" id="link-16147" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(255, 255, 255);">PRIVACY POLICY</a> | <a href="https://www.12minuteaffiliate.com/contact" id="link-67563" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(255, 255, 255);">CONTACT US</a> | <a href="https://www.12minuteaffiliate.com/signin" id="link-76154" class="" target="_self" rel="noopener noreferrer" style="color: rgb(255, 255, 255);">LOG IN</a>
</h2>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--11011" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 0px; outline: none;">
<div id="col-full-135" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable hiddenElementTools de-editable" id="tmp_paragraph-34582" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: left; color: rgba(255, 255, 255, 0.75); font-size: 15px;" data-gramm="false" contenteditable="false">For Product Support, please contact the vendor <b><a href="http://easysupportnow.com" id="link-89289" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(51, 122, 183);">HERE.</a>
</b><div>For Order Support, please contact ClickBank <a href="https://www.clkbank.com/#!/" id="link-78515" class="" target="_blank" rel="noopener noreferrer" style="color: rgb(51, 122, 183);">HERE.</a>
</div>
<div></div>
<div><br></div>
<div>
Earnings Disclaimer: Every effort has been made to accurately represent this product and it's potential. Even though this industry is one of the few where one can write their own check in terms of earnings, there is no guarantee that you will earn any money using the techniques and ideas in this product. </div>
<div><br></div>
<div>Examples in these materials are not to be taken as a promise or guarantee of earnings. Earning potential is entirely dependent on the person using our product, ideas, techniques and most importantly the effort put forth. We do not purport this as a "get rich scheme", and nor should you view it as such. </div>
<div></div>
<div><br></div>
<div>
The content of this message has been created by the applicable Vendor and not by ClickBank. Accordingly, ClickBank is not responsible for any information contained in this message, including, but not limited to, any product information, promotions, incentives, expected returns or other information contained herein. In addition, ClickBank is not responsible for any links to third party websites contained in this message. Such links do not imply any endorsement by ClickBank of such websites or the content, products or services available from such websites. By clicking on or accessing a third party website listed in this message, you acknowledge sole responsibility for and assume all risk arising from your use of any such websites. </div>
<div></div>
<div><br></div>
<div>
ClickBank is the retailer of products on this site. CLICKBANK is a registered trademark of Click Sales Inc., a Delaware corporation located at 1444 S. Entertainment Ave., Suite 410 Boise, ID 83709, USA and used by permission. ClickBank's role as retailer does not constitute an endorsement, approval or review of these products or any claim, statement or opinion used in promotion of these products.</div>
</div>
</div>
</div>
</div>
</div>
<div class="row bgCover noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" id="row--47394" data-trigger="none" data-animate="fade" data-delay="500" data-title="1 column row" style="padding-top: 20px; padding-bottom: 20px; margin: 25px 0px 0px; outline: none;">
<div id="col-full-123" class="col-md-12 innerContent col_left" data-col="full" data-trigger="none" data-animate="fade" data-delay="500" data-title="1st column" style="outline: none;">
<div class="col-inner bgCover  noBorder borderSolid border3px cornersAll radius0 shadow0 P0-top P0-bottom P0H noTopMargin" style="padding: 0 10px">
<div class="de elHeadlineWrapper ui-droppable de-editable" id="tmp_paragraph-99136" data-de-type="headline" data-de-editing="false" data-title="Paragraph" data-ce="true" data-trigger="none" data-animate="fade" data-delay="500" style="margin-top: 0px; outline: none; cursor: pointer;" aria-disabled="false">
<div class="ne elHeadline hsSize1 lh5 elMargin0 elBGStyle0 hsTextShadow0" data-bold="inherit" style="text-align: center; font-size: 14px; color: rgb(255, 255, 255);" data-gramm="false" contenteditable="false">Copyright © 2020 - 2021  |  12 Minute Affiliate All Rights Reserved.</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="dropZoneForSections ui-droppable" style="display: none;"><div class="dropIconr"><i class="fa fa-plus"></i></div></div>
<style id="button_style_tmp_headline1-21669">#tmp_headline1-21669 .elButtonFlat:hover{ background-color: #379b85 !important;} 
#tmp_headline1-21669 .elButtonBottomBorder:hover{ background-color: #379b85 !important;}
#tmp_headline1-21669 .elButtonSubtle:hover{ background-color: #379b85 !important;}
#tmp_headline1-21669 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgba(66, 185, 159, 0)), color-stop(1, #379b85));                                                 background-image: -o-linear-gradient(bottom, rgba(66, 185, 159, 0) 0%, #379b85 100%);                                                 background-image: -moz-linear-gradient(bottom, rgba(66, 185, 159, 0) 0%, #379b85 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgba(66, 185, 159, 0) 0%, #379b85 100%);                                                 background-image: -ms-linear-gradient(bottom, rgba(66, 185, 159, 0) 0%, #379b85 100%);                                                 background-image: linear-gradient(to bottom, rgba(66, 185, 159, 0) 0%, #379b85 100%);                                             }
#tmp_headline1-21669 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgba(66, 185, 159, 0)), color-stop(0, #379b85));                                                 background-image: -o-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 0%);                                                 background-image: -moz-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 0%);                                                 background-image: -ms-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 0%);                                                 background-image: linear-gradient(to bottom, rgba(66, 185, 159, 0) 100%, #379b85 0%);                                             }
#tmp_headline1-21669 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgba(66, 185, 159, 0)), color-stop(1, #379b85));     background-image: -o-linear-gradient(bottom, rgba(66, 185, 159, 0) 30%, #379b85 80%);     background-image: -moz-linear-gradient(bottom, rgba(66, 185, 159, 0) 30%, #379b85 80%);     background-image: -webkit-linear-gradient(bottom, rgba(66, 185, 159, 0) 30%, #379b85 80%);     background-image: -ms-linear-gradient(bottom, rgba(66, 185, 159, 0) 30%, #379b85 80%);     background-image: linear-gradient(to bottom, rgba(66, 185, 159, 0) 30%, #379b85 80%); }
#tmp_headline1-21669 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgba(66, 185, 159, 0)), color-stop(0, #379b85));     background-image: -o-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 30%);     background-image: -moz-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 30%);     background-image: -webkit-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 30%);     background-image: -ms-linear-gradient(bottom, rgba(66, 185, 159, 0) 100%, #379b85 30%);     background-image: linear-gradient(to bottom, rgba(66, 185, 159, 0) 100%, #379b85 30%); }
#tmp_headline1-21669 .elButtonBorder{                        border: 3px solid rgba(66, 185, 159, 0) !important;                         color: rgba(66, 185, 159, 0) !important;                     }
#tmp_headline1-21669 .elButtonBorder:hover{                          background-color:rgba(66, 185, 159, 0) !important;                          color: #000 !important;                       }
</style>
<style id="bold_style_tmp_list-44863">#tmp_list-44863 .elBulletList b{ color: rgb(1, 116, 199);}</style>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Fjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CPatua+One%7CLato+sans-serif%7CPatua+One%7CLato+sans-serif%7CPatua+One%7CLato+sans-serif%7CPatua+One%7CLato+sans-serif%7CFjalla+One%7CPatua+One%7CLato%7CFjalla+One%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7COswald%7CLato+sans-serif%7CLato%7COswald%7CLato+sans-serif%7CMerriweather%7COswald%7CLato+sans-serif%7CLato%7COswald%7CFjalla+One%7CLato%7CLato+sans-serif%7CLato%7COswald%7CLato+sans-serif%7CLato%7COswald%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato%7CFjalla+One%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7CFjalla+One%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CFjalla+One%7CLato%7CFjalla+One%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7COswald%7CLato+sans-serif%7COswald%7CLato+sans-serif%7CHelvetica+Neue+Helvetica+Arial+sans-serif%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CLato%7CLato+sans-serif%7CFjalla+One%7CLato+sans-serif%7CFjalla+One%7CLato%7CLato+sans-serif%7C%7C" id="custom_google_font">
<style id="bold_style_headline-39642-148">#headline-39642-148 .elHeadline b{ color: rgb(1, 116, 199);}#headline-39642-148 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-39642-148"></style>
<style id="button_style_button-75827-121">
    #button-75827-121 .elButtonFlat:hover {
      background-color: #0b72a1 !important;
    }
    #button-75827-121 .elButtonBottomBorder:hover {
      background-color: #0b72a1 !important;
    }
    #button-75827-121 .elButtonSubtle:hover {
      background-color: #0b72a1 !important;
    }
    #button-75827-121 .elButtonGradient {
      background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, rgb(14, 141, 199)), color-stop(1, #0b72a1));
      background-image: -o-linear-gradient(bottom, rgb(14, 141, 199) 0%, #0b72a1 100%);
      background-image: -moz-linear-gradient(bottom, rgb(14, 141, 199) 0%, #0b72a1 100%);
      background-image: -webkit-linear-gradient(bottom, rgb(14, 141, 199) 0%, #0b72a1 100%);
      background-image: -ms-linear-gradient(bottom, rgb(14, 141, 199) 0%, #0b72a1 100%);
      background-image: linear-gradient(to bottom, rgb(14, 141, 199) 0%, #0b72a1 100%);
    }
    #button-75827-121 .elButtonGradient:hover {
      background-image: -webkit-gradient(linear, left top, left bottom, color-stop(1, rgb(14, 141, 199)), color-stop(0, #0b72a1));
      background-image: -o-linear-gradient(bottom, rgb(14, 141, 199) 100%, #0b72a1 0%);
      background-image: -moz-linear-gradient(bottom, rgb(14, 141, 199) 100%, #0b72a1 0%);
      background-image: -webkit-linear-gradient(bottom, rgb(14, 141, 199) 100%, #0b72a1 0%);
      background-image: -ms-linear-gradient(bottom, rgb(14, 141, 199) 100%, #0b72a1 0%);
      background-image: linear-gradient(to bottom, rgb(14, 141, 199) 100%, #0b72a1 0%);
    }
    #button-75827-121 .elButtonBorder {
      border: 3px solid rgb(14, 141, 199) !important;
      color: rgb(14, 141, 199) !important;
    }
    #button-75827-121 .elButtonBorder:hover {
      background-color: rgb(14, 141, 199) !important;
      color: #FFF !important;
    }
  </style>
<style id="bold_style_headline-25639-141">#headline-25639-141 .elHeadline b{ color: rgb(1, 116, 199);}#headline-25639-141 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-25639-141"></style>
<style id="bold_style_tmp_subheadline-53773">#tmp_subheadline-53773 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467">#headline-44467 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-137">#tmp_subheadline-53773-137 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-137"></style>
<style id="bold_style_headline-44467-108">#headline-44467-108 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467-108"></style>
<style id="bold_style_tmp_subheadline-53773-137-172">#tmp_subheadline-53773-137-172 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-137-172"></style>
<style id="bold_style_headline-44467-108-113">#headline-44467-108-113 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467-108-113"></style>
<style id="bold_style_tmp_headline1-94574-166">#tmp_headline1-94574-166 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_headline1-94574-166"></style>
<style id="bold_style_tmp_subheadline-53951-109">#tmp_subheadline-53951-109 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53951-109"></style>
<style id="bold_style_tmp_subheadline-53773-142">#tmp_subheadline-53773-142 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-142 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-142"></style>
<style id="bold_style_headline-44467-145">#headline-44467-145 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-145 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467-145"></style>
<style id="bold_style_tmp_subheadline-53773-137-107">#tmp_subheadline-53773-137-107 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-107 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-107 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-107 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-137-107"></style>
<style id="bold_style_headline-44467-108-125">#headline-44467-108-125 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-125 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-125 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-125 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467-108-125"></style>
<style id="bold_style_tmp_subheadline-53773-137-172-149">#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53773-137-172-149 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53773-137-172-149"></style>
<style id="bold_style_headline-44467-108-113-116">#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}#headline-44467-108-113-116 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-44467-108-113-116"></style>
<style id="bold_style_headline-71059-102-111-161">#headline-71059-102-111-161 .elHeadline b{ color: rgb(255, 255, 255);}#headline-71059-102-111-161 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-71059-102-111-161"></style>
<style id="bold_style_tmp_list-46188">#tmp_list-46188 .elBulletList b{ color: rgba(0, 0, 0, 0.96);}</style>
<style id="bold_style_headline-76686">#headline-76686 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_list-46188-175">#tmp_list-46188-175 .elBulletList b{ color: rgba(0, 0, 0, 0.96);}</style>
<style id="bold_style_headline-15304">#headline-15304 .elHeadline b{ color: rgba(0, 0, 0, 0.96);}</style>
<style id="bold_style_tmp_subheadline-70991">#tmp_subheadline-70991 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-184">#tmp_subheadline-70991-184 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-184 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-184"></style>
<style id="bold_style_tmp_subheadline-70991-107">#tmp_subheadline-70991-107 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-107 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-107"></style>
<style id="bold_style_tmp_subheadline-70991-110">#tmp_subheadline-70991-110 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-110 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-110"></style>
<style id="bold_style_headline-34985-111">#headline-34985-111 .elHeadline b{ color: rgb(228, 59, 44);}#headline-34985-111 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-34985-111"></style>
<style id="bold_style_headline-41389">#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}#headline-41389 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-53635">#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}#headline-53635 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-91950">#headline-91950 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_tmp_subheadline-65824-165">#tmp_subheadline-65824-165 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-165 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-65824-165"></style>
<style id="bold_style_tmp_headline1-59498-110">#tmp_headline1-59498-110 .elHeadline b{ color: rgb(66, 185, 159);}#tmp_headline1-59498-110 .elHeadline b{ color: rgb(66, 185, 159);}</style>
<style id="bold_style_tmp_headline1-59498-110"></style>
<style id="bold_style_headline-30907-161">#headline-30907-161 .elHeadline b{ color: rgb(1, 116, 199);}#headline-30907-161 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-30907-161"></style>
<style id="bold_style_headline-29189-153">#headline-29189-153 .elHeadline b{ color: rgb(255, 80, 0);}#headline-29189-153 .elHeadline b{ color: rgb(255, 80, 0);}</style>
<style id="bold_style_headline-29189-153"></style>
<style id="bold_style_tmp_list-51178">#tmp_list-51178 .elBulletList b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_list-51178-182">#tmp_list-51178-182 .elBulletList b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-45324-144-147-110">#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-45324-144-147-110 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_headline1-45324-144-147-110"></style>
<style id="bold_style_tmp_subheadline-65824-142-169-181">#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-181 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-65824-142-169-181"></style>
<style id="bold_style_tmp_headline1-94574-166-154">#tmp_headline1-94574-166-154 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_headline1-94574-166-154"></style>
<style id="bold_style_tmp_subheadline-53951-109-101">#tmp_subheadline-53951-109-101 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53951-109-101"></style>
<style id="bold_style_headline-74877">#headline-74877 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142">#headline-74877-142 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142"></style>
<style id="bold_style_headline-74877-131">#headline-74877-131 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131"></style>
<style id="bold_style_headline-74877-142-166">#headline-74877-142-166 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166"></style>
<style id="bold_style_headline-74877-131-177">#headline-74877-131-177 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131-177"></style>
<style id="bold_style_headline-74877-142-166-130">#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166-130"></style>
<style id="bold_style_tmp_subheadline-80200-111">#tmp_subheadline-80200-111 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-72181">#headline-72181 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-12463">#headline-12463 .elHeadline b{ color: rgb(228, 59, 44);}#headline-12463 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-72181-140">#headline-72181-140 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-140 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-140 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-140 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-72181-140"></style>
<style id="bold_style_tmp_headline1-94574-166-154-152">#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_headline1-94574-166-154-152"></style>
<style id="bold_style_tmp_subheadline-53951-109-101-123">#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53951-109-101-123"></style>
<style id="bold_style_headline-48205-147-137-136">#headline-48205-147-137-136 .elHeadline b{ color: rgb(228, 59, 44);}#headline-48205-147-137-136 .elHeadline b{ color: rgb(228, 59, 44);}#headline-48205-147-137-136 .elHeadline b{ color: rgb(228, 59, 44);}#headline-48205-147-137-136 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-48205-147-137-136"></style>
<style id="bold_style_headline-91950-173">#headline-91950-173 .elHeadline b{ color: rgb(45, 45, 45);}#headline-91950-173 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-91950-173"></style>
<style id="bold_style_headline-87917-142-144">#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}#headline-87917-142-144 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-87917-142-144"></style>
<style id="bold_style_headline-38730">#headline-38730 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-38730-119">#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}#headline-38730-119 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-38730-119"></style>
<style id="bold_style_tmp_list-51178-145">#tmp_list-51178-145 .elBulletList b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-65824-142-169-183">#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-65824-142-169-183 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-65824-142-169-183"></style>
<style id="bold_style_tmp_headline1-94574-166-154-152-114">#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_headline1-94574-166-154-152-114 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_headline1-94574-166-154-152-114"></style>
<style id="bold_style_tmp_subheadline-53951-109-101-123-178">#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-109-101-123-178 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53951-109-101-123-178"></style>
<style id="bold_style_headline-74877-150">#headline-74877-150 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-150 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-150"></style>
<style id="bold_style_headline-26625-109-149">#headline-26625-109-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-149 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-26625-109-149"></style>
<style id="bold_style_headline-74877-142-116">#headline-74877-142-116 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-116 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-116 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-116 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-116"></style>
<style id="bold_style_headline-26625-122-149">#headline-26625-122-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-149 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-149 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-122-149 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122-149"></style>
<style id="bold_style_headline-74877-131-168">#headline-74877-131-168 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-168 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-168 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-168 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131-168"></style>
<style id="bold_style_tmp_subheadline-80200-111-152">#tmp_subheadline-80200-111-152 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-80200-111-152 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-80200-111-152"></style>
<style id="bold_style_headline-26625-109-167-118">#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-118 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-26625-109-167-118"></style>
<style id="bold_style_headline-74877-142-166-122">#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-122 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166-122"></style>
<style id="bold_style_headline-26625-122-152-110">#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-122-152-110 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-26625-122-152-110"></style>
<style id="bold_style_headline-74877-131-177-155">#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-155 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131-177-155"></style>
<style id="bold_style_headline-26625-109-167-173-143">#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-109-167-173-143 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-26625-109-167-173-143"></style>
<style id="bold_style_headline-74877-142-166-130-106">#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-106 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166-130-106"></style>
<style id="bold_style_headline-26625-189-120">#headline-26625-189-120 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-189-120 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-189-120 .elHeadline b{ color: rgb(228, 59, 44);}#headline-26625-189-120 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-26625-189-120"></style>
<style id="bold_style_headline-72181-170">#headline-72181-170 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-170 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-170 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-170 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-72181-170"></style>
<style id="bold_style_headline-74877-134-182">#headline-74877-134-182 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-182 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-74877-134-182"></style>
<style id="bold_style_headline-74877-134-146-142">#headline-74877-134-146-142 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-146-142 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-146-142 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-146-142 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-74877-134-146-142"></style>
<style id="bold_style_headline-74877-134-167-155">#headline-74877-134-167-155 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-167-155 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-167-155 .elHeadline b{ color: rgb(228, 59, 44);}#headline-74877-134-167-155 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-74877-134-167-155"></style>
<style id="button_style_tmp_button-34128-159">#tmp_button-34128-159 .elButtonFlat:hover{ background-color: #08223b !important;} 
#tmp_button-34128-159 .elButtonBottomBorder:hover{ background-color: #08223b !important;}
#tmp_button-34128-159 .elButtonSubtle:hover{ background-color: #08223b !important;}
#tmp_button-34128-159 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                             }
#tmp_button-34128-159 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                             }
#tmp_button-34128-159 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 30%, #08223b 80%); }
#tmp_button-34128-159 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 30%); }
#tmp_button-34128-159 .elButtonBorder{                        border: 3px solid rgb(13, 55, 95) !important;                         color: rgb(13, 55, 95) !important;                     }
#tmp_button-34128-159 .elButtonBorder:hover{                          background-color:rgb(13, 55, 95) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-159-143">#tmp_button-34128-159-143 .elButtonFlat:hover{ background-color: #08223b !important;} 
#tmp_button-34128-159-143 .elButtonBottomBorder:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143 .elButtonSubtle:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                             }
#tmp_button-34128-159-143 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                             }
#tmp_button-34128-159-143 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 30%, #08223b 80%); }
#tmp_button-34128-159-143 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 30%); }
#tmp_button-34128-159-143 .elButtonBorder{                        border: 3px solid rgb(13, 55, 95) !important;                         color: rgb(13, 55, 95) !important;                     }
#tmp_button-34128-159-143 .elButtonBorder:hover{                          background-color:rgb(13, 55, 95) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-159-143-169">#tmp_button-34128-159-143-169 .elButtonFlat:hover{ background-color: #08223b !important;} 
#tmp_button-34128-159-143-169 .elButtonBottomBorder:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143-169 .elButtonSubtle:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143-169 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                             }
#tmp_button-34128-159-143-169 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                             }
#tmp_button-34128-159-143-169 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 30%, #08223b 80%); }
#tmp_button-34128-159-143-169 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 30%); }
#tmp_button-34128-159-143-169 .elButtonBorder{                        border: 3px solid rgb(13, 55, 95) !important;                         color: rgb(13, 55, 95) !important;                     }
#tmp_button-34128-159-143-169 .elButtonBorder:hover{                          background-color:rgb(13, 55, 95) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-159-143-169-160">#tmp_button-34128-159-143-169-160 .elButtonFlat:hover{ background-color: #08223b !important;} 
#tmp_button-34128-159-143-169-160 .elButtonBottomBorder:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143-169-160 .elButtonSubtle:hover{ background-color: #08223b !important;}
#tmp_button-34128-159-143-169-160 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                             }
#tmp_button-34128-159-143-169-160 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                             }
#tmp_button-34128-159-143-169-160 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 30%, #08223b 80%); }
#tmp_button-34128-159-143-169-160 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 30%); }
#tmp_button-34128-159-143-169-160 .elButtonBorder{                        border: 3px solid rgb(13, 55, 95) !important;                         color: rgb(13, 55, 95) !important;                     }
#tmp_button-34128-159-143-169-160 .elButtonBorder:hover{                          background-color:rgb(13, 55, 95) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-30907">#headline-30907 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-29189">#headline-29189 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_tmp_headline1-59498">#tmp_headline1-59498 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-42698">#tmp_headline1-42698 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-10937">#tmp_headline1-10937 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_list-80369">#tmp_list-80369 .elBulletList b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_list-27912">#list-27912 .elBulletList b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-34911">#headline-34911 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-39642-103">#headline-39642-103 .elHeadline b{ color: rgb(1, 116, 199);}#headline-39642-103 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_headline-39642-103"></style>
<style id="bold_style_headline-25639">#headline-25639 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-34911-179-164">#headline-34911-179-164 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-34911-179-164">#headline-34911-179-164 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="button_style_tmp_button-64492">#tmp_button-64492 .elButtonFlat:hover{ background-color: #3d5697 !important;} 
#tmp_button-64492 .elButtonBottomBorder:hover{ background-color: #3d5697 !important;}
#tmp_button-64492 .elButtonSubtle:hover{ background-color: #3d5697 !important;}
#tmp_button-64492 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                             }
#tmp_button-64492 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                             }
#tmp_button-64492 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 30%, #3d5697 80%); }
#tmp_button-64492 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 30%); }
#tmp_button-64492 .elButtonBorder{                        border: 3px solid rgb(73, 102, 180) !important;                         color: rgb(73, 102, 180) !important;                     }
#tmp_button-64492 .elButtonBorder:hover{                          background-color:rgb(73, 102, 180) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-142-142-178">#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-94574-142-142-178 .elHeadline b{ color: rgb(13, 55, 95);}</style>
<style id="bold_style_tmp_headline1-94574-142-142-178"></style>
<style id="button_style_tmp_button-34128-113-187-131">#tmp_button-34128-113-187-131 .elButtonFlat:hover{ background-color: #08223b !important;} 
#tmp_button-34128-113-187-131 .elButtonBottomBorder:hover{ background-color: #08223b !important;}
#tmp_button-34128-113-187-131 .elButtonSubtle:hover{ background-color: #08223b !important;}
#tmp_button-34128-113-187-131 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 0%, #08223b 100%);                                             }
#tmp_button-34128-113-187-131 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));                                                 background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                                 background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 0%);                                             }
#tmp_button-34128-113-187-131 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(13, 55, 95)), color-stop(1, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 30%, #08223b 80%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 30%, #08223b 80%); }
#tmp_button-34128-113-187-131 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(13, 55, 95)), color-stop(0, #08223b));     background-image: -o-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -moz-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -webkit-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: -ms-linear-gradient(bottom, rgb(13, 55, 95) 100%, #08223b 30%);     background-image: linear-gradient(to bottom, rgb(13, 55, 95) 100%, #08223b 30%); }
#tmp_button-34128-113-187-131 .elButtonBorder{                        border: 3px solid rgb(13, 55, 95) !important;                         color: rgb(13, 55, 95) !important;                     }
#tmp_button-34128-113-187-131 .elButtonBorder:hover{                          background-color:rgb(13, 55, 95) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-53951-139-119-178">#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}#tmp_subheadline-53951-139-119-178 .elHeadline b{ color: rgb(1, 116, 199);}</style>
<style id="bold_style_tmp_subheadline-53951-139-119-178"></style>
<style id="bold_style_tmp_subheadline-65824">#tmp_subheadline-65824 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324">#tmp_headline1-45324 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144">#tmp_headline1-45324-144 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144">#tmp_headline1-45324-144 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-65824-142">#tmp_subheadline-65824-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-65824-142">#tmp_subheadline-65824-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-71059">#headline-71059 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-39642">#headline-39642 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_button-75827">#button-75827 .elButtonFlat:hover{ background-color: #3d5697 !important;} 
#button-75827 .elButtonBottomBorder:hover{ background-color: #3d5697 !important;}
#button-75827 .elButtonSubtle:hover{ background-color: #3d5697 !important;}
#button-75827 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                             }
#button-75827 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                             }
#button-75827 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 30%, #3d5697 80%); }
#button-75827 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 30%); }
#button-75827 .elButtonBorder{                        border: 3px solid rgb(73, 102, 180) !important;                         color: rgb(73, 102, 180) !important;                     }
#button-75827 .elButtonBorder:hover{                          background-color:rgb(73, 102, 180) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-34911-179">#headline-34911-179 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179">#headline-34911-179 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-71059-102">#headline-71059-102 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-71059-102">#headline-71059-102 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_subheadline-53951-139">#tmp_subheadline-53951-139 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-139">#tmp_subheadline-53951-139 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_tmp_button-34128-113">#tmp_button-34128-113 .elButtonFlat:hover{ background-color: #3d5697 !important;} 
#tmp_button-34128-113 .elButtonBottomBorder:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113 .elButtonSubtle:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                             }
#tmp_button-34128-113 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                             }
#tmp_button-34128-113 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 30%, #3d5697 80%); }
#tmp_button-34128-113 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 30%); }
#tmp_button-34128-113 .elButtonBorder{                        border: 3px solid rgb(73, 102, 180) !important;                         color: rgb(73, 102, 180) !important;                     }
#tmp_button-34128-113 .elButtonBorder:hover{                          background-color:rgb(73, 102, 180) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-34911-179-164-100">#headline-34911-179-164-100 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100">#headline-34911-179-164-100 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156">#headline-34911-179-164-100-156 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156">#headline-34911-179-164-100-156 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-27583">#headline-27583 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141">#headline-34911-179-164-100-156-141 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141">#headline-34911-179-164-100-156-141 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-48205-147">#headline-48205-147 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-34985">#headline-34985 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-23506-101">#tmp_headline1-23506-101 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-23506-101">#tmp_headline1-23506-101 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-75276-171">#headline-75276-171 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-75276-171">#headline-75276-171 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182">#headline-34911-179-164-100-156-141-182 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182">#headline-34911-179-164-100-156-141-182 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-87917-142">#headline-87917-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-87917-142">#headline-87917-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144-147">#tmp_headline1-45324-144-147 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144-147">#tmp_headline1-45324-144-147 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-50746">#headline-50746 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-16841">#headline-16841 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-65824-142-169">#tmp_subheadline-65824-142-169 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_subheadline-65824-142-169">#tmp_subheadline-65824-142-169 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361-100">#headline-86361-100 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361-100">#headline-86361-100 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-45324-133-179">#tmp_headline1-45324-133-179 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-133-179">#tmp_headline1-45324-133-179 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_tmp_button-34128-113-187">#tmp_button-34128-113-187 .elButtonFlat:hover{ background-color: #3d5697 !important;} 
#tmp_button-34128-113-187 .elButtonBottomBorder:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113-187 .elButtonSubtle:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113-187 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                             }
#tmp_button-34128-113-187 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                             }
#tmp_button-34128-113-187 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 30%, #3d5697 80%); }
#tmp_button-34128-113-187 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 30%); }
#tmp_button-34128-113-187 .elButtonBorder{                        border: 3px solid rgb(73, 102, 180) !important;                         color: rgb(73, 102, 180) !important;                     }
#tmp_button-34128-113-187 .elButtonBorder:hover{                          background-color:rgb(73, 102, 180) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-142-142">#tmp_headline1-94574-142-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-142-142">#tmp_headline1-94574-142-142 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-139-119">#tmp_subheadline-53951-139-119 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-139-119">#tmp_subheadline-53951-139-119 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-133-179-107">#tmp_headline1-45324-133-179-107 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-133-179-107">#tmp_headline1-45324-133-179-107 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-26625-189">#headline-26625-189 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-26625-189">#headline-26625-189 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105">#headline-34911-179-164-100-156-141-182-105 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105">#headline-34911-179-164-100-156-141-182-105 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144-147-115">#tmp_headline1-45324-144-147-115 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-144-147-115">#tmp_headline1-45324-144-147-115 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_tmp_button-34128-113-187-131-151">#tmp_button-34128-113-187-131-151 .elButtonFlat:hover{ background-color: #3d5697 !important;} 
#tmp_button-34128-113-187-131-151 .elButtonBottomBorder:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113-187-131-151 .elButtonSubtle:hover{ background-color: #3d5697 !important;}
#tmp_button-34128-113-187-131-151 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 0%, #3d5697 100%);                                             }
#tmp_button-34128-113-187-131-151 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));                                                 background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                                 background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 0%);                                             }
#tmp_button-34128-113-187-131-151 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(73, 102, 180)), color-stop(1, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 30%, #3d5697 80%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 30%, #3d5697 80%); }
#tmp_button-34128-113-187-131-151 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(73, 102, 180)), color-stop(0, #3d5697));     background-image: -o-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -moz-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -webkit-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: -ms-linear-gradient(bottom, rgb(73, 102, 180) 100%, #3d5697 30%);     background-image: linear-gradient(to bottom, rgb(73, 102, 180) 100%, #3d5697 30%); }
#tmp_button-34128-113-187-131-151 .elButtonBorder{                        border: 3px solid rgb(73, 102, 180) !important;                         color: rgb(73, 102, 180) !important;                     }
#tmp_button-34128-113-187-131-151 .elButtonBorder:hover{                          background-color:rgb(73, 102, 180) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-142-142-178-119">#tmp_headline1-94574-142-142-178-119 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-142-142-178-119">#tmp_headline1-94574-142-142-178-119 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-139-119-178-145">#tmp_subheadline-53951-139-119-178-145 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-139-119-178-145">#tmp_subheadline-53951-139-119-178-145 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-63041-150">#headline-63041-150 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-63041-150">#headline-63041-150 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-45324-133-179-107-187">#tmp_headline1-45324-133-179-107-187 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-133-179-107-187">#tmp_headline1-45324-133-179-107-187 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-30789">#headline-30789 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-39552">#headline-39552 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-138">#headline-34911-138 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-138">#headline-34911-138 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-39642-137">#headline-39642-137 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-39642-137">#headline-39642-137 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-86361-128">#headline-86361-128 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361-128">#headline-86361-128 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361-100-136-177">#headline-86361-100-136-177 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361-100-136-177">#headline-86361-100-136-177 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-94574-143">#tmp_headline1-94574-143 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-143"></style>
<style id="bold_style_tmp_subheadline-53951-126">#tmp_subheadline-53951-126 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-126"></style>
<style id="bold_style_tmp_headline1-94574-143-177">#tmp_headline1-94574-143-177 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-143-177"></style>
<style id="bold_style_tmp_subheadline-53951-126-166">#tmp_subheadline-53951-126-166 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-126-166"></style>
<style id="bold_style_tmp_headline1-23506">#tmp_headline1-23506 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-93171">#headline-93171 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-38231">#headline-38231 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-94574-143-177-169">#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-143-177-169"></style>
<style id="bold_style_tmp_subheadline-53951-126-166-173">#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-126-166-173"></style>
<style id="bold_style_tmp_headline1-94574-143-177-169-172">#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-143-177-169-172 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-94574-143-177-169-172"></style>
<style id="bold_style_tmp_subheadline-53951-126-166-173-141">#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-53951-126-166-173-141 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-53951-126-166-173-141"></style>
<style id="bold_style_headline-25639-105">#headline-25639-105 .elHeadline b{ color: rgba(0, 0, 0, 0.96);}</style>
<style id="bold_style_headline-47597">#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}#headline-47597 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-80093">#headline-80093 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-19677">#headline-19677 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-71059-170">#headline-71059-170 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-71059-170">#headline-71059-170 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-71059-102-111">#headline-71059-102-111 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-71059-102-111">#headline-71059-102-111 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-63041">#headline-63041 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625">#headline-26625 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109">#headline-26625-109 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109">#headline-26625-109 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122">#headline-26625-122 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122">#headline-26625-122 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167">#headline-26625-109-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167">#headline-26625-109-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122-152">#headline-26625-122-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122-152">#headline-26625-122-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167-173">#headline-26625-109-167-173 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167-173">#headline-26625-109-167-173 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134">#headline-74877-134 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134">#headline-74877-134 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-146">#headline-74877-134-146 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-146">#headline-74877-134-146 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-167">#headline-74877-134-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-167">#headline-74877-134-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150">#headline-26625-150 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150">#headline-26625-150 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127">#headline-26625-150-127 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127">#headline-26625-150-127 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138">#headline-26625-150-138 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138">#headline-26625-150-138 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180">#headline-26625-150-127-180 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180">#headline-26625-150-127-180 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163">#headline-26625-150-138-163 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163">#headline-26625-150-138-163 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167">#headline-26625-150-127-180-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167">#headline-26625-150-127-180-167 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153">#headline-26625-150-138-163-153 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153">#headline-26625-150-138-163-153 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132">#headline-26625-150-127-180-167-132 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132">#headline-26625-150-127-180-167-132 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153-132">#headline-26625-150-138-163-153-132 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153-132">#headline-26625-150-138-163-153-132 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132-129">#headline-26625-150-127-180-167-132-129 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132-129">#headline-26625-150-127-180-167-132-129 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-67400">#tmp_headline1-67400 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-31490">#headline-31490 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="button_style_tmp_button-34128">#tmp_button-34128 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-183">#tmp_button-34128-183 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-183 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-183 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-183 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-183 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-183 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-183 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-183-152">#tmp_button-34128-183-152 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-183-152 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-183-152 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-183-152 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-183-152 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-183-152 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-183-152 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-183-152-150">#tmp_button-34128-183-152-150 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-183-152-150 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152-150 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152-150 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-183-152-150 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-183-152-150 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-183-152-150 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-183-152-150 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-183-152-150 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_tmp_button-34128-183-152-150-133">#tmp_button-34128-183-152-150-133 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-183-152-150-133 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152-150-133 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-183-152-150-133 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-183-152-150-133 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-183-152-150-133 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-183-152-150-133 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-183-152-150-133 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-183-152-150-133 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_button-44465">#button-44465 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#button-44465 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#button-44465 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#button-44465 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#button-44465 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#button-44465 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#button-44465 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#button-44465 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#button-44465 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="button_style_button-75827-164">#button-75827-164 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#button-75827-164 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#button-75827-164 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#button-75827-164 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#button-75827-164 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#button-75827-164 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#button-75827-164 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#button-75827-164 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#button-75827-164 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-18899">#tmp_headline1-18899 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-49396">#headline-49396 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-45492">#headline-45492 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-58857">#headline-58857 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_subheadline-84035">#tmp_subheadline-84035 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-93171-125">#headline-93171-125 .elHeadline b{ color: rgb(45, 45, 45);}#headline-93171-125 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-93171-125"></style>
<style id="bold_style_headline-16841-173">#headline-16841-173 .elHeadline b{ color: rgb(73, 102, 180);}#headline-16841-173 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-16841-173"></style>
<style id="bold_style_headline-34985-132">#headline-34985-132 .elHeadline b{ color: rgb(46, 194, 254);}#headline-34985-132 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-34985-132"></style>
<style id="bold_style_headline-31490-111">#headline-31490-111 .elHeadline b{ color: rgb(232, 138, 23);}#headline-31490-111 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-31490-111"></style>
<style id="bold_style_headline-38231-123">#headline-38231-123 .elHeadline b{ color: rgb(46, 194, 254);}#headline-38231-123 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-38231-123"></style>
<style id="bold_style_headline-93171-125-149">#headline-93171-125-149 .elHeadline b{ color: rgb(45, 45, 45);}#headline-93171-125-149 .elHeadline b{ color: rgb(45, 45, 45);}#headline-93171-125-149 .elHeadline b{ color: rgb(45, 45, 45);}#headline-93171-125-149 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-93171-125-149"></style>
<style id="bold_style_headline-16841-173-156">#headline-16841-173-156 .elHeadline b{ color: rgb(73, 102, 180);}#headline-16841-173-156 .elHeadline b{ color: rgb(73, 102, 180);}#headline-16841-173-156 .elHeadline b{ color: rgb(73, 102, 180);}#headline-16841-173-156 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-16841-173-156"></style>
<style id="bold_style_headline-34985-132-136">#headline-34985-132-136 .elHeadline b{ color: rgb(46, 194, 254);}#headline-34985-132-136 .elHeadline b{ color: rgb(46, 194, 254);}#headline-34985-132-136 .elHeadline b{ color: rgb(46, 194, 254);}#headline-34985-132-136 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-34985-132-136"></style>
<style id="bold_style_tmp_headline1-23506-101-105-172">#tmp_headline1-23506-101-105-172 .elHeadline b{ color: rgb(46, 194, 254);}#tmp_headline1-23506-101-105-172 .elHeadline b{ color: rgb(46, 194, 254);}#tmp_headline1-23506-101-105-172 .elHeadline b{ color: rgb(46, 194, 254);}#tmp_headline1-23506-101-105-172 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-23506-101-105-172"></style>
<style id="bold_style_headline-31490-111-159">#headline-31490-111-159 .elHeadline b{ color: rgb(232, 138, 23);}#headline-31490-111-159 .elHeadline b{ color: rgb(232, 138, 23);}#headline-31490-111-159 .elHeadline b{ color: rgb(232, 138, 23);}#headline-31490-111-159 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-31490-111-159"></style>
<style id="bold_style_headline-38231-123-103">#headline-38231-123-103 .elHeadline b{ color: rgb(46, 194, 254);}#headline-38231-123-103 .elHeadline b{ color: rgb(46, 194, 254);}#headline-38231-123-103 .elHeadline b{ color: rgb(46, 194, 254);}#headline-38231-123-103 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-38231-123-103"></style>
<style id="bold_style_headline-26625-189-155">#headline-26625-189-155 .elHeadline b{ color: rgb(73, 102, 180);}#headline-26625-189-155 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-26625-189-155"></style>
<style id="bold_style_headline-72181-159">#headline-72181-159 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-159 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-159 .elHeadline b{ color: rgb(255, 255, 255);}#headline-72181-159 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-72181-159"></style>
<style id="bold_style_headline-26835">#headline-26835 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-94574">#tmp_headline1-94574 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_subheadline-53951">#tmp_subheadline-53951 .elHeadline b{ color: rgb(0, 0, 0);}</style>
<style id="bold_style_tmp_headline1-94574-178">#tmp_headline1-94574-178 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-178"></style>
<style id="button_style_tmp_button-34128-148">#tmp_button-34128-148 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-148 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-148 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-148 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-148 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-148 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-148 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-53951-110">#tmp_subheadline-53951-110 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110 .elHeadline b{ color: rgb(0, 0, 0);}</style>
<style id="bold_style_tmp_subheadline-53951-110"></style>
<style id="bold_style_tmp_headline1-94574-178-178">#tmp_headline1-94574-178-178 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-178-178"></style>
<style id="button_style_tmp_button-34128-148-145">#tmp_button-34128-148-145 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-148-145 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-148-145 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-148-145 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-148-145 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-148-145 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-148-145 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-53951-110-140">#tmp_subheadline-53951-110-140 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140 .elHeadline b{ color: rgb(0, 0, 0);}</style>
<style id="bold_style_tmp_subheadline-53951-110-140"></style>
<style id="bold_style_tmp_headline1-94574-178-178-140">#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-178-178-140"></style>
<style id="button_style_tmp_button-34128-148-145-120">#tmp_button-34128-148-145-120 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-148-145-120 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145-120 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145-120 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-148-145-120 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-148-145-120 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-148-145-120 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-148-145-120 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-148-145-120 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-53951-110-140-152">#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152 .elHeadline b{ color: rgb(0, 0, 0);}</style>
<style id="bold_style_tmp_subheadline-53951-110-140-152"></style>
<style id="bold_style_tmp_headline1-94574-178-178-140-152">#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-178-178-140-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-178-178-140-152"></style>
<style id="button_style_tmp_button-34128-148-145-120-153">#tmp_button-34128-148-145-120-153 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-148-145-120-153 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145-120-153 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-148-145-120-153 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-148-145-120-153 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-148-145-120-153 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-148-145-120-153 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-148-145-120-153 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-148-145-120-153 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-53951-110-140-152-175">#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}#tmp_subheadline-53951-110-140-152-175 .elHeadline b{ color: rgb(0, 0, 0);}</style>
<style id="bold_style_tmp_subheadline-53951-110-140-152-175"></style>
<style id="bold_style_tmp_headline1-94574-130">#tmp_headline1-94574-130 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-130"></style>
<style id="button_style_tmp_button-34128-186">#tmp_button-34128-186 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-186 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-186 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-186 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-186 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-186 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-186 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-130-154">#tmp_headline1-94574-130-154 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-130-154"></style>
<style id="button_style_tmp_button-34128-186-133">#tmp_button-34128-186-133 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-186-133 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186-133 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186-133 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-186-133 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-186-133 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-186-133 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-186-133 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-186-133 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-130-154-133">#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-130-154-133 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-130-154-133"></style>
<style id="button_style_tmp_button-34128-186-133-164">#tmp_button-34128-186-133-164 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-186-133-164 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186-133-164 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-186-133-164 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-186-133-164 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-186-133-164 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-186-133-164 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-186-133-164 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-186-133-164 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-164">#tmp_headline1-94574-164 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-164"></style>
<style id="button_style_tmp_button-34128-115">#tmp_button-34128-115 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-115 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-115 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-115 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-115 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-115 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-115 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-164-148">#tmp_headline1-94574-164-148 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-164-148"></style>
<style id="button_style_tmp_button-34128-115-185">#tmp_button-34128-115-185 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-115-185 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115-185 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115-185 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-115-185 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-115-185 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-115-185 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-115-185 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-115-185 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-164-148-133">#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-164-148-133 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-164-148-133"></style>
<style id="button_style_tmp_button-34128-115-185-133">#tmp_button-34128-115-185-133 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-115-185-133 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115-185-133 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-115-185-133 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-115-185-133 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-115-185-133 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-115-185-133 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-115-185-133 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-115-185-133 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-65824-153">#tmp_subheadline-65824-153 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-65824-153 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-65824-153"></style>
<style id="bold_style_tmp_headline1-45324-109">#tmp_headline1-45324-109 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-45324-109 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-109"></style>
<style id="bold_style_headline-82086">#headline-82086 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_list-14856">#tmp_list-14856 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_list-62596">#list-62596 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-19241">#headline-19241 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-37517">#headline-37517 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-87953">#headline-87953 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-75276">#headline-75276 .elHeadline b{ color: rgb(71, 71, 71);}</style>
<style id="bold_style_headline-87917">#headline-87917 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-34985-149">#headline-34985-149 .elHeadline b{ color: rgb(46, 194, 254);}#headline-34985-149 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-34985-149"></style>
<style id="bold_style_tmp_headline1-23506-101-105">#tmp_headline1-23506-101-105 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-23506-101-105">#tmp_headline1-23506-101-105 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187">#headline-34911-179-164-100-156-141-182-187 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187"></style>
<style id="bold_style_headline-19677-115">#headline-19677-115 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-19677-115"></style>
<style id="bold_style_headline-53304">#headline-53304 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-44806">#headline-44806 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-94785">#headline-94785 .elHeadline b{ color: rgb(255, 227, 0);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105-100">#headline-34911-179-164-100-156-141-182-105-100 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-105-100 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105-100"></style>
<style id="bold_style_headline-53304-119">#headline-53304-119 .elHeadline b{ color: rgb(232, 138, 23);}#headline-53304-119 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-53304-119"></style>
<style id="bold_style_tmp_headline1-21669">#tmp_headline1-21669 .elHeadline b{ color: rgb(13, 55, 95);}</style>
<style id="bold_style_tmp_subheadline-37994">#tmp_subheadline-37994 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-58857-113">#headline-58857-113 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-58857-113">#headline-58857-113 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-19677-157">#headline-19677-157 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-157 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-19677-157"></style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-162">#headline-34911-179-164-100-156-141-182-162 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-162 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-162"></style>
<style id="bold_style_headline-58857-113-101">#headline-58857-113-101 .elHeadline b{ color: rgb(232, 138, 23);}#headline-58857-113-101 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-58857-113-101"></style>
<style id="bold_style_tmp_subheadline-70991-130">#tmp_subheadline-70991-130 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-130 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-130"></style>
<style id="bold_style_tmp_subheadline-70991-110-165">#tmp_subheadline-70991-110-165 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-110-165 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-110-165 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-110-165 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-110-165"></style>
<style id="bold_style_tmp_subheadline-70991-107-171">#tmp_subheadline-70991-107-171 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-107-171 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-107-171 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-107-171 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-107-171"></style>
<style id="bold_style_tmp_subheadline-70991-184-118">#tmp_subheadline-70991-184-118 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-184-118 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-184-118 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-70991-184-118 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-70991-184-118"></style>
<style id="bold_style_headline-27583-106">#headline-27583-106 .elHeadline b{ color: rgb(73, 102, 180);}#headline-27583-106 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-27583-106"></style>
<style id="bold_style_headline-81222">#headline-81222 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-87138">#headline-87138 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-45324-133">#tmp_headline1-45324-133 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-45324-133">#tmp_headline1-45324-133 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-86361">#headline-86361 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-86361-100-136">#headline-86361-100-136 .elHeadline b{ color: rgb(71, 71, 71);}</style>
<style id="bold_style_headline-86361-100-136">#headline-86361-100-136 .elHeadline b{ color: rgb(71, 71, 71);}</style>
<style id="bold_style_headline-57652">#headline-57652 .elHeadline b{ color: rgb(228, 59, 44);}</style>
<style id="bold_style_headline-19677-115-153">#headline-19677-115-153 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-19677-115-153"></style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187-182">#headline-34911-179-164-100-156-141-182-187-182 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187-182"></style>
<style id="bold_style_headline-44568">#headline-44568 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-63041-105">#headline-63041-105 .elHeadline b{ color: rgb(232, 138, 23);}#headline-63041-105 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-63041-105"></style>
<style id="bold_style_headline-44568-126">#headline-44568-126 .elHeadline b{ color: rgb(255, 255, 255);}#headline-44568-126 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-44568-126"></style>
<style id="bold_style_headline-26625-189-152">#headline-26625-189-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-189-152">#headline-26625-189-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-189-152-127">#headline-26625-189-152-127 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-26625-189-152-127">#headline-26625-189-152-127 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-44568-121">#headline-44568-121 .elHeadline b{ color: rgb(49, 158, 215);}</style>
<style id="bold_style_headline-44568-121">#headline-44568-121 .elHeadline b{ color: rgb(49, 158, 215);}</style>
<style id="bold_style_headline-86361-182">#headline-86361-182 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-45324-133-142">#tmp_headline1-45324-133-142 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_headline-87138-167">#headline-87138-167 .elHeadline b{ color: rgb(46, 194, 254);}</style>
<style id="bold_style_tmp_headline1-67400-155">#tmp_headline1-67400-155 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-67400-155 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-67400-155"></style>
<style id="bold_style_headline-26835-141">#headline-26835-141 .elHeadline b{ color: rgb(255, 255, 255);}#headline-26835-141 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-26835-141"></style>
<style id="bold_style_tmp_headline1-10937-149">#tmp_headline1-10937-149 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_headline1-10937-149 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-10937-149"></style>
<style id="bold_style_tmp_list-14856-109">#tmp_list-14856-109 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_list-62596-189">#list-62596-189 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-37517-114">#headline-37517-114 .elHeadline b{ color: rgb(73, 102, 180);}#headline-37517-114 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-37517-114"></style>
<style id="bold_style_headline-19241-157">#headline-19241-157 .elHeadline b{ color: rgb(73, 102, 180);}#headline-19241-157 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-19241-157"></style>
<style id="button_style_button-44465-172">#button-44465-172 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#button-44465-172 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#button-44465-172 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#button-44465-172 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#button-44465-172 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#button-44465-172 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#button-44465-172 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#button-44465-172 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#button-44465-172 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-67400-116">#tmp_headline1-67400-116 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26835-161">#headline-26835-161 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-42698-160">#tmp_headline1-42698-160 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-10937-147">#tmp_headline1-10937-147 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-37517-104">#headline-37517-104 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-19241-150">#headline-19241-150 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="button_style_button-44465-121">#button-44465-121 .elButtonFlat:hover{ background-color: #c37413 !important;} #button-44465-121 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}#button-44465-121 .elButtonSubtle:hover{ background-color: #c37413 !important;}#button-44465-121 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }#button-44465-121 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }#button-44465-121 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }#button-44465-121 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }#button-44465-121 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }#button-44465-121 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }</style>
<style id="bold_style_headline-92564">#headline-92564 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-35398">#headline-35398 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_tmp_list-14856-177">#tmp_list-14856-177 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-133-184">#tmp_headline1-45324-133-184 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_headline1-45324-133-184">#tmp_headline1-45324-133-184 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-18220">#headline-18220 .elHeadline b{ color: rgb(255, 126, 0);}</style>
<style id="button_style_tmp_button-69735-131">#tmp_button-69735-131 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-69735-131 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-69735-131 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-69735-131 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-69735-131 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-69735-131 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-69735-131 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-69735-131 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-69735-131 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-22848">#headline-22848 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-41518">#headline-41518 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_list-62596-175">#list-62596-175 .elBulletList b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-21669-127">#tmp_headline1-21669-127 .elHeadline b{ color: rgb(13, 55, 95);}#tmp_headline1-21669-127 .elHeadline b{ color: rgb(13, 55, 95);}</style>
<style id="bold_style_tmp_headline1-21669-127"></style>
<style id="bold_style_tmp_subheadline-37994-161">#tmp_subheadline-37994-161 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-37994-161 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-37994-161"></style>
<style id="bold_style_headline-94785-117">#headline-94785-117 .elHeadline b{ color: rgb(255, 227, 0);}#headline-94785-117 .elHeadline b{ color: rgb(255, 227, 0);}</style>
<style id="bold_style_headline-94785-117"></style>
<style id="bold_style_tmp_headline1-94574-142"></style>
<style id="bold_style_tmp_headline1-94574-142"></style>
<style id="button_style_tmp_button-34128-167">#tmp_button-34128-167 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-167 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-167 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-167 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-167 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-167 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-167 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_subheadline-65824-166">#tmp_subheadline-65824-166 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_subheadline-65824-166 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_subheadline-65824-166"></style>
<style id="bold_style_tmp_headline1-45324-148">#tmp_headline1-45324-148 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-45324-148 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_tmp_headline1-45324-148"></style>
<style id="bold_style_tmp_headline1-18899-101">#tmp_headline1-18899-101 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-18899-101 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-18899-101"></style>
<style id="bold_style_headline-49396-181">#headline-49396-181 .elHeadline b{ color: rgb(232, 138, 23);}#headline-49396-181 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-49396-181"></style>
<style id="bold_style_headline-45492-152">#headline-45492-152 .elHeadline b{ color: rgb(232, 138, 23);}#headline-45492-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-45492-152"></style>
<style id="bold_style_headline-34911-188">#headline-34911-188 .elHeadline b{ color: rgb(255, 255, 255);}#headline-34911-188 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-34911-188"></style>
<style id="bold_style_headline-71059-112">#headline-71059-112 .elHeadline b{ color: rgb(73, 102, 180);}#headline-71059-112 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-71059-112"></style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105-176">#headline-34911-179-164-100-156-141-182-105-176 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-105-176 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-105-176"></style>
<style id="bold_style_tmp_headline1-94574-142-117">#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-142-117"></style>
<style id="button_style_tmp_button-34128-167-108">#tmp_button-34128-167-108 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-167-108 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-167-108 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-167-108 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-167-108 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-167-108 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-167-108 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-19677-115-153-189">#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}#headline-19677-115-153-189 .elHeadline b{ color: rgb(45, 45, 45);}</style>
<style id="bold_style_headline-19677-115-153-189"></style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187-182-127">#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}#headline-34911-179-164-100-156-141-182-187-182-127 .elHeadline b{ color: rgb(73, 102, 180);}</style>
<style id="bold_style_headline-34911-179-164-100-156-141-182-187-182-127"></style>
<style id="bold_style_tmp_headline1-94574-142-117-189">#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-142-117-189"></style>
<style id="button_style_tmp_button-34128-167-108-162">#tmp_button-34128-167-108-162 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-167-108-162 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108-162 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108-162 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-167-108-162 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-167-108-162 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-167-108-162 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-167-108-162 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-167-108-162 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-63041-169">#headline-63041-169 .elHeadline b{ color: rgb(232, 138, 23);}#headline-63041-169 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-63041-169"></style>
<style id="bold_style_headline-44568-120">#headline-44568-120 .elHeadline b{ color: rgb(255, 255, 255);}#headline-44568-120 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-44568-120"></style>
<style id="bold_style_headline-26625-155">#headline-26625-155 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-155 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-155"></style>
<style id="bold_style_headline-74877-170">#headline-74877-170 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-170 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-170"></style>
<style id="bold_style_headline-26625-109-172">#headline-26625-109-172 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-109-172 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-172"></style>
<style id="bold_style_headline-74877-142-152">#headline-74877-142-152 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-152 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-152 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-152 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-152"></style>
<style id="bold_style_headline-26625-122-149"></style>
<style id="bold_style_headline-26625-122-149"></style>
<style id="bold_style_headline-74877-131-122">#headline-74877-131-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-122 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-122 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131-122"></style>
<style id="bold_style_tmp_subheadline-80200-111-134">#tmp_subheadline-80200-111-134 .elHeadline b{ color: rgb(255, 255, 255);}#tmp_subheadline-80200-111-134 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-80200-111-134"></style>
<style id="bold_style_headline-26625-109-167-119">#headline-26625-109-167-119 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-109-167-119 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167-119"></style>
<style id="bold_style_headline-74877-142-166-114">#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-114 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166-114"></style>
<style id="bold_style_headline-26625-122-152-151">#headline-26625-122-152-151 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-122-152-151 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-122-152-151"></style>
<style id="bold_style_headline-74877-131-177-132">#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-131-177-132 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-131-177-132"></style>
<style id="bold_style_headline-26625-109-167-173-118">#headline-26625-109-167-173-118 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-109-167-173-118 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-109-167-173-118"></style>
<style id="bold_style_headline-74877-142-166-130-148">#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}#headline-74877-142-166-130-148 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-74877-142-166-130-148"></style>
<style id="bold_style_headline-63041-105-144">#headline-63041-105-144 .elHeadline b{ color: rgb(232, 138, 23);}#headline-63041-105-144 .elHeadline b{ color: rgb(232, 138, 23);}#headline-63041-105-144 .elHeadline b{ color: rgb(232, 138, 23);}#headline-63041-105-144 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-63041-105-144"></style>
<style id="bold_style_headline-44568-126-136">#headline-44568-126-136 .elHeadline b{ color: rgb(255, 255, 255);}#headline-44568-126-136 .elHeadline b{ color: rgb(255, 255, 255);}#headline-44568-126-136 .elHeadline b{ color: rgb(255, 255, 255);}#headline-44568-126-136 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-44568-126-136"></style>
<style id="bold_style_headline-74877-134-172">#headline-74877-134-172 .elHeadline b{ color: rgb(232, 138, 23);}#headline-74877-134-172 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-172"></style>
<style id="bold_style_headline-74877-134-146-144">#headline-74877-134-146-144 .elHeadline b{ color: rgb(232, 138, 23);}#headline-74877-134-146-144 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-146-144"></style>
<style id="bold_style_headline-74877-134-167-116">#headline-74877-134-167-116 .elHeadline b{ color: rgb(232, 138, 23);}#headline-74877-134-167-116 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-74877-134-167-116"></style>
<style id="bold_style_headline-26625-189-152-174">#headline-26625-189-152-174 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-189-152-174 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-189-152-174"></style>
<style id="bold_style_headline-41518-162">#headline-41518-162 .elHeadline b{ color: rgb(232, 138, 23);}#headline-41518-162 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-41518-162"></style>
<style id="bold_style_tmp_headline1-94574-142-117-189-176">#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(73, 102, 180);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}#tmp_headline1-94574-142-117-189-176 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_tmp_headline1-94574-142-117-189-176"></style>
<style id="button_style_tmp_button-34128-167-108-162-122">#tmp_button-34128-167-108-162-122 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-34128-167-108-162-122 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108-162-122 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-34128-167-108-162-122 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-34128-167-108-162-122 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-34128-167-108-162-122 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-34128-167-108-162-122 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-34128-167-108-162-122 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-34128-167-108-162-122 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_headline-63041-150-135">#headline-63041-150-135 .elHeadline b{ color: rgb(255, 255, 255);}#headline-63041-150-135 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-63041-150-135"></style>
<style id="bold_style_headline-44568-121-141">#headline-44568-121-141 .elHeadline b{ color: rgb(49, 158, 215);}#headline-44568-121-141 .elHeadline b{ color: rgb(49, 158, 215);}</style>
<style id="bold_style_headline-44568-121-141"></style>
<style id="bold_style_headline-26625-150-105">#headline-26625-150-105 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-105 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-105"></style>
<style id="bold_style_headline-26625-150-127-160">#headline-26625-150-127-160 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-127-160 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-160"></style>
<style id="bold_style_headline-26625-150-138-152">#headline-26625-150-138-152 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-138-152 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-152"></style>
<style id="bold_style_headline-26625-150-127-180-151">#headline-26625-150-127-180-151 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-127-180-151 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-151"></style>
<style id="bold_style_headline-26625-150-138-163-149">#headline-26625-150-138-163-149 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-138-163-149 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-149"></style>
<style id="bold_style_headline-26625-150-127-180-167-107">#headline-26625-150-127-180-167-107 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-127-180-167-107 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-107"></style>
<style id="bold_style_headline-26625-150-138-163-153-134">#headline-26625-150-138-163-153-134 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-138-163-153-134 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153-134"></style>
<style id="bold_style_headline-26625-150-127-180-167-132-131">#headline-26625-150-127-180-167-132-131 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-127-180-167-132-131 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132-131"></style>
<style id="bold_style_headline-26625-150-138-163-153-132-145">#headline-26625-150-138-163-153-132-145 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-138-163-153-132-145 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-138-163-153-132-145"></style>
<style id="bold_style_headline-26625-150-127-180-167-132-129-108">#headline-26625-150-127-180-167-132-129-108 .elHeadline b{ color: rgb(232, 138, 23);}#headline-26625-150-127-180-167-132-129-108 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-26625-150-127-180-167-132-129-108"></style>
<style id="bold_style_headline-26625-189-152-127-154">#headline-26625-189-152-127-154 .elHeadline b{ color: rgb(255, 255, 255);}#headline-26625-189-152-127-154 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-26625-189-152-127-154"></style>
<style id="bold_style_headline-22848-145">#headline-22848-145 .elHeadline b{ color: rgb(232, 138, 23);}#headline-22848-145 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<style id="bold_style_headline-22848-145"></style>
<style id="button_style_tmp_button-69735-131-100">#tmp_button-69735-131-100 .elButtonFlat:hover{ background-color: #c37413 !important;} 
#tmp_button-69735-131-100 .elButtonBottomBorder:hover{ background-color: #c37413 !important;}
#tmp_button-69735-131-100 .elButtonSubtle:hover{ background-color: #c37413 !important;}
#tmp_button-69735-131-100 .elButtonGradient{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 0%, #c37413 100%);                                             }
#tmp_button-69735-131-100 .elButtonGradient:hover{                                                background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));                                                 background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                                 background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 0%);                                             }
#tmp_button-69735-131-100 .elButtonGradient2{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(0, rgb(232, 138, 23)), color-stop(1, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 30%, #c37413 80%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 30%, #c37413 80%); }
#tmp_button-69735-131-100 .elButtonGradient2:hover{    background-image: -webkit-gradient( linear, left top, left bottom, color-stop(1, rgb(232, 138, 23)), color-stop(0, #c37413));     background-image: -o-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -moz-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -webkit-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: -ms-linear-gradient(bottom, rgb(232, 138, 23) 100%, #c37413 30%);     background-image: linear-gradient(to bottom, rgb(232, 138, 23) 100%, #c37413 30%); }
#tmp_button-69735-131-100 .elButtonBorder{                        border: 3px solid rgb(232, 138, 23) !important;                         color: rgb(232, 138, 23) !important;                     }
#tmp_button-69735-131-100 .elButtonBorder:hover{                          background-color:rgb(232, 138, 23) !important;                          color: #FFF !important;                       }
</style>
<style id="bold_style_tmp_headline1-94574-142">#tmp_headline1-94574-142 .elHeadline b{ color: rgb(255, 121, 2);}</style>
<style id="bold_style_tmp_headline1-94574-142">#tmp_headline1-94574-142 .elHeadline b{ color: rgb(255, 121, 2);}</style>
<style id="bold_style_tmp_subheadline-95280">#tmp_subheadline-95280 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_tmp_subheadline-44251">#tmp_subheadline-44251 .elHeadline b{ color: rgb(255, 255, 255);}</style>
<style id="bold_style_headline-25061">#headline-25061 .elHeadline b{ color: rgb(232, 138, 23);}</style>
<input type="hidden" name="cf-state-county-dropdown-feature-enabled" value="true">
</div>
<style id="custom-css"></style>
<input type="hidden" value="44891895" id="page-id">
<input type="hidden" value="44891895" id="root-id">
<input type="hidden" value="core" id="variant-check">
<input type="hidden" value="1021965" id="user-id">
<input type="hidden" value="" id="cf-cid">
<script type="text/javascript">
    window.CFAppDomain = "app.clickfunnels.com"
    window.domainIsCFInternal = "false" == "true"
  </script>
<script src="//easy.12minuteaffiliate.com/assets/lander.js"></script>
<div id="fb-root"></div>
<script>
window.addEventListener('load', function(){
	(function(d, s, id){
	  if($('.fbCommentsPlaceholder').size()>0){
	   var js, fjs = d.getElementsByTagName(s)[0];
	   if (d.getElementById(id)) {return;}
	   js = d.createElement(s); js.id = id;
	   js.src = "https://connect.facebook.net/en_US/sdk.js";
	   fjs.parentNode.insertBefore(js, fjs);
	  }
	 }(document, 'script', 'facebook-jssdk'));
});
 </script>
<script>
  window.cfFacebookInitOptions = {
    appId            : 246441615530259,
    autoLogAppEvents : false,
    status           : true,
    xfbml            : true,
    version          : "v3.3"
  };
  window.fbAsyncInit = function() {
    FB.init(window.cfFacebookInitOptions);
  
    // Iterates over all .fb-comments elements on the page, and renders them using the FB SDK.
    // It only runs if we have not told the FB.init() to render XFBML on page load
    var renderFacebookComments = function(renderXFBMLAtLoadTime) {
      // If we have already marked XFBML to render at page load time, do not proceed.
      if(renderXFBMLAtLoadTime) { return; }
  
      var comments = document.getElementsByClassName('fb-comments');
      var i = 0;
      var len = comments.length;
      var comment = null;
      for(; i < len; i++) {
        comment = comments[i];
        FB.XFBML.parse(comment.parentElement); // comments need to be rendered/parsed from their parent element.
      }
    }
  
    renderFacebookComments(true);
  };
</script>
<!--[if lt IE 9]>
<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7/html5shiv.min.js"></script>
<![endif]-->
<form target="_parent" data-cf-form-action="true" action="https://easy.12minuteaffiliate.com/main" method="post" id="cfAR" style="display:none">
<span data-cf-form-fields="true"></span>
<input id="cf_contact_name" name="contact[name]" data-cf-form-field="name" placeholder="name" data-stripe="name">
<input id="cf_contact_first_name" name="contact[first_name]" data-cf-form-field="first_name" placeholder="first_name" data-recurly="first_name">
<input id="cf_contact_last_name" name="contact[last_name]" data-cf-form-field="last_name" placeholder="last_name" data-recurly="last_name">
<input id="cf_contact_email" name="contact[email]" data-cf-form-field="email" placeholder="email">
<input id="cf_contact_phone" name="contact[phone]" data-cf-form-field="phone" placeholder="phone" data-recurly="phone">
<input id="cf_contact_address" name="contact[address]" data-cf-form-field="address" placeholder="address" data-stripe="address_line1" data-recurly="address1">
<input id="cf_contact_city" name="contact[city]" data-cf-form-field="city" placeholder="city" data-stripe="address_city" data-recurly="city">
<input id="cf_contact_state" name="contact[state]" data-cf-form-field="state" placeholder="state" data-stripe="address_state" data-recurly="state">
<input id="cf_contact_country" name="contact[country]" data-cf-form-field="country" placeholder="country" data-stripe="address_country" data-recurly="country">
<input id="cf_contact_zip" name="contact[zip]" data-cf-form-field="zip" placeholder="ZIP" data-stripe="address_zip" data-recurly="postal_code">
<input id="cf_contact_shipping_address" name="contact[shipping_address]" data-cf-form-field="shipping_address" placeholder="shipping_address" data-stripe="shipping_address">
<input id="cf_contact_shipping_city" name="contact[shipping_city]" data-cf-form-field="shipping_city" placeholder="shipping_city" data-stripe="shipping_city">
<input id="cf_contact_shipping_state" name="contact[shipping_state]" data-cf-form-field="shipping_state" placeholder="shipping_state" data-stripe="shipping_state">
<input id="cf_contact_shipping_country" name="contact[shipping_country]" data-cf-form-field="shipping_country" placeholder="shipping_country" data-stripe="shipping_country">
<input id="cf_contact_shipping_zip" name="contact[shipping_zip]" data-cf-form-field="shipping_zip" placeholder="shipping_ZIP" data-stripe="shipping_zip">
<input id="cf_contact_vat_number" name="contact[vat_number]" data-cf-form-field="vat_number" data-recurly="vat_number">
<input id="cf_contact_affiliate_id" name="contact[affiliate_id]" data-cf-form-field="affiliate_id" data-param="affiliate_id">
<input id="cf_contact_cf_affiliate_id" name="contact[cf_affiliate_id]" data-cf-form-field="cf_affiliate_id" data-param="cf_affiliate_id">
<input id="cf_cf_affiliate_id" name="cf_affiliate_id" data-param="cf_affiliate_id">
<input id="cf_contact_affiliate_aff_sub" name="contact[aff_sub]" data-cf-form-field="aff_sub" data-param="aff_sub">
<input id="cf_contact_affiliate_aff_sub2" name="contact[aff_sub2]" data-cf-form-field="aff_sub2" data-param="aff_sub2">
<input id="cf_contact_time_zone" name="time_zone" data-cf-form-field="time_zone" placeholder="time_zone">
<input id="utm_source" name="utm_source" data-cf-form-field="utm_source" data-param="utm_source">
<input id="utm_medium" name="utm_medium" data-cf-form-field="utm_medium" data-param="utm_medium">
<input id="utm_campaign" name="utm_campaign" data-cf-form-field="utm_campaign" data-param="utm_campaign">
<input id="utm_term" name="utm_term" data-cf-form-field="utm_term" data-param="utm_term">
<input id="utm_content" name="utm_content" data-cf-form-field="utm_content" data-param="utm_content">
<input id="cf_uvid" name="cf_uvid" data-cf-form-field="cf_uvid">
<input type="text" name="webinar_delay" id="webinar_delay" placeholder="Webinar Delay">
<span data-cf-product-template="true">
<input type="radio" name="purchase[product_id]" value="" data-storage="false">
<input type="checkbox" name="purchase[product_ids][]" value="" data-storage="false">
</span>
<span data-cf-product-variations-template="true">
<input type="checkbox" class="pvPurchaseProductName" name="purchase[product_variants][][product_id]" value="" data-storage="false">
<input type="checkbox" class="pvPurchaseProductVariantName" name="purchase[product_variants][][product_variant_id]" value="" data-storage="false">
<input type="input" class="pvPurchaseProductVariantQuantity" name="purchase[product_variants][][quantity]" value="" data-storage="false">
</span>
<input id="cf_contact_number" data-stripe="number" data-storage="false" data-recurly="number">
<input id="cf_contact_month" data-stripe="exp-month" data-storage="" data-recurly="month">
<input id="cf_contact_year" data-stripe="exp-year" data-storage="" data-recurly="year">
<input id="cf_contact_month_year" data-stripe="exp" data-storage="">
<input id="cf_contact_cvc" data-stripe="cvc" data-storage="false" data-recurly="cvv">
<input type="hidden" name="purchase[payment_method_nonce]" data-storage="false">
<input type="hidden" name="purchase[order_saas_url]" data-storage="false">
<input type="submit">
<input name="contact[cart_affiliate_id]" value="" type="hidden" style="display:none;" data-param="affiliate">
</form>
<span class="countdown-time" style="display:none;"></span>
<span class="webinar-last-time" style="display:none;"></span>
<span class="webinar-ext" style="display:none;"></span>
<span class="webinar-ot" style="display:none;"></span>
<span class="contact-created" style="display:none;"></span>
<script>
  </script>
<div class="otoloading" style="display: none;">
<div class="otoloadingtext">
<h2>Working...</h2>
<div><i class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
<script type="text/javascript">
    document.createElement('video');document.createElement('audio');document.createElement('track');
  </script>
<style>
    #IntercomDefaultWidget {
      display:none;
    }
    .selectAW-date-demo, .elTicketAddToCalendar, .elTicketAddToCalendarV2 {
      display:none;
    }
    .video-js {
      padding-top:56.25%;
    }
    .vjs-big-play-button,.vjs-control-bar {
      z-index: 10 !important;
    }
    .vjs-fullscreen {
      padding-top:0;
    }
  </style>
<script type="text/html" id="cfx_all_canada">
    <option value="">Select Province</option>
    <option value="">------------------------------</option>
    <option value="AB">Alberta</option>
    <option value="BC">British Columbia</option>
    <option value="MB">Manitoba</option>
    <option value="NB">New Brunswick</option>
    <option value="NL">Newfoundland and Labrador</option>
    <option value="NS">Nova Scotia</option>
    <option value="ON">Ontario</option>
    <option value="PE">Prince Edward Island</option>
    <option value="QC">Quebec</option>
    <option value="SK">Saskatchewan</option>
    <option value="NT">Northwest Territories</option>
    <option value="NU">Nunavut</option>
    <option value="YT">Yukon</option>
</script>
<script type="text/html" id="cfx_all_states">
    <option value="">Select State</option>
    <option value="">------------------------------</option>
    <option value="AL">Alabama</option>
    <option value="AK">Alaska</option>
    <option value="AZ">Arizona</option>
    <option value="AR">Arkansas</option>
    <option value="CA">California</option>
    <option value="CO">Colorado</option>
    <option value="CT">Connecticut</option>
    <option value="DE">Delaware</option>
    <option value="DC">District Of Columbia</option>
    <option value="FL">Florida</option>
    <option value="GA">Georgia</option>
    <option value="HI">Hawaii</option>
    <option value="ID">Idaho</option>
    <option value="IL">Illinois</option>
    <option value="IN">Indiana</option>
    <option value="IA">Iowa</option>
    <option value="KS">Kansas</option>
    <option value="KY">Kentucky</option>
    <option value="LA">Louisiana</option>
    <option value="ME">Maine</option>
    <option value="MD">Maryland</option>
    <option value="MA">Massachusetts</option>
    <option value="MI">Michigan</option>
    <option value="MN">Minnesota</option>
    <option value="MS">Mississippi</option>
    <option value="MO">Missouri</option>
    <option value="MT">Montana</option>
    <option value="NE">Nebraska</option>
    <option value="NV">Nevada</option>
    <option value="NH">New Hampshire</option>
    <option value="NJ">New Jersey</option>
    <option value="NM">New Mexico</option>
    <option value="NY">New York</option>
    <option value="NC">North Carolina</option>
    <option value="ND">North Dakota</option>
    <option value="OH">Ohio</option>
    <option value="OK">Oklahoma</option>
    <option value="OR">Oregon</option>
    <option value="PA">Pennsylvania</option>
    <option value="RI">Rhode Island</option>
    <option value="SC">South Carolina</option>
    <option value="SD">South Dakota</option>
    <option value="TN">Tennessee</option>
    <option value="TX">Texas</option>
    <option value="UT">Utah</option>
    <option value="VT">Vermont</option>
    <option value="VA">Virginia</option>
    <option value="WA">Washington</option>
    <option value="WV">West Virginia</option>
    <option value="WI">Wisconsin</option>
    <option value="WY">Wyoming</option>
</script>
<script type="text/html" id="cfx_all_countries">
    <option value="">Select Country</option>
    <option value="">------------------------------</option>
    <option value="United States of America">United States</option>
    <option value="Canada">Canada</option>
    <option value="United Kingdom">United Kingdom</option>
    <option value="Ireland">Ireland</option>
    <option value="Australia">Australia</option>
    <option value="New Zealand">New Zealand</option>
    <option value="">------------------------------</option>
    <option value="Afghanistan">Afghanistan</option>
    <option value="Albania">Albania</option>
    <option value="Algeria">Algeria</option>
    <option value="American Samoa">American Samoa</option>
    <option value="Andorra">Andorra</option>
    <option value="Angola">Angola</option>
    <option value="Anguilla">Anguilla</option>
    <option value="Antarctica">Antarctica</option>
    <option value="Antigua and Barbuda">Antigua and Barbuda</option>
    <option value="Argentina">Argentina</option>
    <option value="Armenia">Armenia</option>
    <option value="Aruba">Aruba</option>
    <option value="Australia">Australia</option>
    <option value="Austria">Austria</option>
    <option value="Azerbaijan">Azerbaijan</option>
    <option value="Bahamas">Bahamas</option>
    <option value="Bahrain">Bahrain</option>
    <option value="Bangladesh">Bangladesh</option>
    <option value="Barbados">Barbados</option>
    <option value="Belarus">Belarus</option>
    <option value="Belgium">Belgium</option>
    <option value="Belize">Belize</option>
    <option value="Benin">Benin</option>
    <option value="Bermuda">Bermuda</option>
    <option value="Bhutan">Bhutan</option>
    <option value="Bolivia">Bolivia</option>
    <option value="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
    <option value="Botswana">Botswana</option>
    <option value="Bouvet Island">Bouvet Island</option>
    <option value="Brazil">Brazil</option>
    <option value="British Indian Ocean Territory">British Indian Ocean Territory</option>
    <option value="Brunei Darussalam">Brunei Darussalam</option>
    <option value="Bulgaria">Bulgaria</option>
    <option value="Burkina Faso">Burkina Faso</option>
    <option value="Burundi">Burundi</option>
    <option value="Cambodia">Cambodia</option>
    <option value="Cameroon">Cameroon</option>
    <option value="Canada">Canada</option>
    <option value="Cape Verde">Cape Verde</option>
    <option value="Cayman Islands">Cayman Islands</option>
    <option value="Central African Republic">Central African Republic</option>
    <option value="Chad">Chad</option>
    <option value="Chile">Chile</option>
    <option value="China">China</option>
    <option value="Christmas Island">Christmas Island</option>
    <option value="Cocos (Keeling) Islands">Cocos (Keeling) Islands</option>
    <option value="Colombia">Colombia</option>
    <option value="Comoros">Comoros</option>
    <option value="Congo">Congo</option>
    <option value="Congo, The Democratic Republic of The">Congo, The Democratic Republic of The</option>
    <option value="Cook Islands">Cook Islands</option>
    <option value="Costa Rica">Costa Rica</option>
    <option value="Cote D'ivoire">Cote D'ivoire</option>
    <option value="Croatia">Croatia</option>
    <option value="Cuba">Cuba</option>
    <option value="Cyprus">Cyprus</option>
    <option value="Czech Republic">Czech Republic</option>
    <option value="Denmark">Denmark</option>
    <option value="Djibouti">Djibouti</option>
    <option value="Dominica">Dominica</option>
    <option value="Dominican Republic">Dominican Republic</option>
    <option value="Ecuador">Ecuador</option>
    <option value="Egypt">Egypt</option>
    <option value="El Salvador">El Salvador</option>
    <option value="Equatorial Guinea">Equatorial Guinea</option>
    <option value="Eritrea">Eritrea</option>
    <option value="Estonia">Estonia</option>
    <option value="Ethiopia">Ethiopia</option>
    <option value="Falkland Islands (Malvinas)">Falkland Islands (Malvinas)</option>
    <option value="Faroe Islands">Faroe Islands</option>
    <option value="Fiji">Fiji</option>
    <option value="Finland">Finland</option>
    <option value="France">France</option>
    <option value="French Guiana">French Guiana</option>
    <option value="French Polynesia">French Polynesia</option>
    <option value="French Southern Territories">French Southern Territories</option>
    <option value="Gabon">Gabon</option>
    <option value="Gambia">Gambia</option>
    <option value="Georgia">Georgia</option>
    <option value="Germany">Germany</option>
    <option value="Ghana">Ghana</option>
    <option value="Gibraltar">Gibraltar</option>
    <option value="Greece">Greece</option>
    <option value="Greenland">Greenland</option>
    <option value="Grenada">Grenada</option>
    <option value="Guadeloupe">Guadeloupe</option>
    <option value="Guam">Guam</option>
    <option value="Guatemala">Guatemala</option>
    <option value="Guinea">Guinea</option>
    <option value="Guinea-bissau">Guinea-bissau</option>
    <option value="Guyana">Guyana</option>
    <option value="Haiti">Haiti</option>
    <option value="Heard Island and Mcdonald Islands">Heard Island and Mcdonald Islands</option>
    <option value="Holy See (Vatican City State)">Holy See (Vatican City State)</option>
    <option value="Honduras">Honduras</option>
    <option value="Hong Kong">Hong Kong</option>
    <option value="Hungary">Hungary</option>
    <option value="Iceland">Iceland</option>
    <option value="India">India</option>
    <option value="Indonesia">Indonesia</option>
    <option value="Iran, Islamic Republic of">Iran, Islamic Republic of</option>
    <option value="Iraq">Iraq</option>
    <option value="Ireland">Ireland</option>
    <option value="Israel">Israel</option>
    <option value="Italy">Italy</option>
    <option value="Jamaica">Jamaica</option>
    <option value="Japan">Japan</option>
    <option value="Jordan">Jordan</option>
    <option value="Kazakhstan">Kazakhstan</option>
    <option value="Kenya">Kenya</option>
    <option value="Kiribati">Kiribati</option>
    <option value="Korea, Democratic People's Republic of">Korea, Democratic People's Republic of</option>
    <option value="Korea, Republic of">Korea, Republic of</option>
    <option value="Kuwait">Kuwait</option>
    <option value="Kyrgyzstan">Kyrgyzstan</option>
    <option value="Lao People's Democratic Republic">Lao People's Democratic Republic</option>
    <option value="Latvia">Latvia</option>
    <option value="Lebanon">Lebanon</option>
    <option value="Lesotho">Lesotho</option>
    <option value="Liberia">Liberia</option>
    <option value="Libyan Arab Jamahiriya">Libyan Arab Jamahiriya</option>
    <option value="Liechtenstein">Liechtenstein</option>
    <option value="Lithuania">Lithuania</option>
    <option value="Luxembourg">Luxembourg</option>
    <option value="Macao">Macao</option>
    <option value="Macedonia, The Former Yugoslav Republic of">Macedonia, The Former Yugoslav Republic of</option>
    <option value="Madagascar">Madagascar</option>
    <option value="Malawi">Malawi</option>
    <option value="Malaysia">Malaysia</option>
    <option value="Maldives">Maldives</option>
    <option value="Mali">Mali</option>
    <option value="Malta">Malta</option>
    <option value="Marshall Islands">Marshall Islands</option>
    <option value="Martinique">Martinique</option>
    <option value="Mauritania">Mauritania</option>
    <option value="Mauritius">Mauritius</option>
    <option value="Mayotte">Mayotte</option>
    <option value="Mexico">Mexico</option>
    <option value="Micronesia, Federated States of">Micronesia, Federated States of</option>
    <option value="Moldova, Republic of">Moldova, Republic of</option>
    <option value="Monaco">Monaco</option>
    <option value="Mongolia">Mongolia</option>
    <option value="Montserrat">Montserrat</option>
    <option value="Morocco">Morocco</option>
    <option value="Mozambique">Mozambique</option>
    <option value="Myanmar">Myanmar</option>
    <option value="Namibia">Namibia</option>
    <option value="Nauru">Nauru</option>
    <option value="Nepal">Nepal</option>
    <option value="Netherlands">Netherlands</option>
    <option value="Netherlands Antilles">Netherlands Antilles</option>
    <option value="New Caledonia">New Caledonia</option>
    <option value="New Zealand">New Zealand</option>
    <option value="Nicaragua">Nicaragua</option>
    <option value="Niger">Niger</option>
    <option value="Nigeria">Nigeria</option>
    <option value="Niue">Niue</option>
    <option value="Norfolk Island">Norfolk Island</option>
    <option value="Northern Mariana Islands">Northern Mariana Islands</option>
    <option value="Norway">Norway</option>
    <option value="Oman">Oman</option>
    <option value="Pakistan">Pakistan</option>
    <option value="Palau">Palau</option>
    <option value="Palestinian Territory, Occupied">Palestinian Territory, Occupied</option>
    <option value="Panama">Panama</option>
    <option value="Papua New Guinea">Papua New Guinea</option>
    <option value="Paraguay">Paraguay</option>
    <option value="Peru">Peru</option>
    <option value="Philippines">Philippines</option>
    <option value="Pitcairn">Pitcairn</option>
    <option value="Poland">Poland</option>
    <option value="Portugal">Portugal</option>
    <option value="Puerto Rico">Puerto Rico</option>
    <option value="Qatar">Qatar</option>
    <option value="Reunion">Reunion</option>
    <option value="Romania">Romania</option>
    <option value="Russian Federation">Russian Federation</option>
    <option value="Rwanda">Rwanda</option>
    <option value="Saint Helena">Saint Helena</option>
    <option value="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
    <option value="Saint Lucia">Saint Lucia</option>
    <option value="Saint Pierre and Miquelon">Saint Pierre and Miquelon</option>
    <option value="Saint Vincent and The Grenadines">Saint Vincent and The Grenadines</option>
    <option value="Samoa">Samoa</option>
    <option value="San Marino">San Marino</option>
    <option value="Sao Tome and Principe">Sao Tome and Principe</option>
    <option value="Saudi Arabia">Saudi Arabia</option>
    <option value="Senegal">Senegal</option>
    <option value="Serbia and Montenegro">Serbia and Montenegro</option>
    <option value="Seychelles">Seychelles</option>
    <option value="Sierra Leone">Sierra Leone</option>
    <option value="Singapore">Singapore</option>
    <option value="Slovakia">Slovakia</option>
    <option value="Slovenia">Slovenia</option>
    <option value="Solomon Islands">Solomon Islands</option>
    <option value="Somalia">Somalia</option>
    <option value="South Africa">South Africa</option>
    <option value="South Georgia and The South Sandwich Islands">South Georgia and The South Sandwich Islands</option>
    <option value="Spain">Spain</option>
    <option value="Sri Lanka">Sri Lanka</option>
    <option value="Sudan">Sudan</option>
    <option value="Suriname">Suriname</option>
    <option value="Svalbard and Jan Mayen">Svalbard and Jan Mayen</option>
    <option value="Swaziland">Swaziland</option>
    <option value="Sweden">Sweden</option>
    <option value="Switzerland">Switzerland</option>
    <option value="Syrian Arab Republic">Syrian Arab Republic</option>
    <option value="Taiwan, Province of China">Taiwan, Province of China</option>
    <option value="Tajikistan">Tajikistan</option>
    <option value="Tanzania, United Republic of">Tanzania, United Republic of</option>
    <option value="Thailand">Thailand</option>
    <option value="Timor-leste">Timor-leste</option>
    <option value="Togo">Togo</option>
    <option value="Tokelau">Tokelau</option>
    <option value="Tonga">Tonga</option>
    <option value="Trinidad and Tobago">Trinidad and Tobago</option>
    <option value="Tunisia">Tunisia</option>
    <option value="Turkey">Turkey</option>
    <option value="Turkmenistan">Turkmenistan</option>
    <option value="Turks and Caicos Islands">Turks and Caicos Islands</option>
    <option value="Tuvalu">Tuvalu</option>
    <option value="Uganda">Uganda</option>
    <option value="Ukraine">Ukraine</option>
    <option value="United Arab Emirates">United Arab Emirates</option>
    <option value="United Kingdom">United Kingdom</option>
    <option value="United States">United States</option>
    <option value="United States Minor Outlying Islands">United States Minor Outlying Islands</option>
    <option value="Uruguay">Uruguay</option>
    <option value="Uzbekistan">Uzbekistan</option>
    <option value="Vanuatu">Vanuatu</option>
    <option value="Venezuela">Venezuela</option>
    <option value="Viet Nam">Viet Nam</option>
    <option value="Virgin Islands, British">Virgin Islands, British</option>
    <option value="Virgin Islands, U.S.">Virgin Islands, U.S.</option>
    <option value="Wallis and Futuna">Wallis and Futuna</option>
    <option value="Western Sahara">Western Sahara</option>
    <option value="Yemen">Yemen</option>
    <option value="Zambia">Zambia</option>
    <option value="Zimbabwe">Zimbabwe</option>
</script>
<script>
      var page_key = 'gk2zi8virfg6clke';
      var fid = '4021313';
      var fspos = '1';
      var fvrs = '45';
      var cf_tracker = cf_tracker || [];
      (function() {
        cf_key = 'ji6517yr';
        page_key = 'gk2zi8virfg6clke';
        serverUrl = '//easy.12minuteaffiliate.com/images/background.png';
        var cf = document.createElement('script');
        cf.type = 'text/javascript';
        cf.async = true;
        cf.src = '//easy.12minuteaffiliate.com/vendor.js';
        var s = document.getElementsByTagName('script')[0];
        s.parentNode.insertBefore(cf, s);
      })();
    </script>
<script type="text/javascript" src="https://app.clickfunnels.com/mailcheck.min.js" async="async"></script><script type="text/javascript">window.addEventListener("load",function(){for(var e=["ar","at","au","be","br","ca","ch","cl","cn","cz","de","dk","es","eu","fi","fr","hk","hu","in","it","jp","kr","mx","nl","no","nz","pl","pt","ru","se","tk","tr","tw","uk","us"],i=0;i<e.length;i++){var a=e[i];Mailcheck.defaultTopLevelDomains.push(a),Mailcheck.defaultTopLevelDomains.push("com."+a)}var t=Mailcheck.defaultDomains.slice();for(i=0;i<t.length;i++)for(var s=t[i],l=0;l<e.length;l++){a=e[l];Mailcheck.defaultDomains.push(s+"."+a)}Mailcheck.defaultDomains.push("clickfunnels.com"),$('input[name="email"]').on("blur",function(){_this=this,$(this).mailcheck({suggested:function(e,i){$(".email_suggestion").remove(),$(e).parent().append('<div class="email_suggestion">Did you mean <a href="#">'+i.full+"</a>?</div>")},empty:function(){$(".email_suggestion").remove()}}),$.each("chenowith52@gmail.com, test@test.com, test@gmail.com, test@mail.com".split(","),function(e,i){0<=$(_this).val().search(i.trim())&&($(".email_suggestion").remove(),$(_this).val(""),$(_this).after('<div class="email_suggestion">Please use real email.</div>'))})}),$("body").on("click",".email_suggestion a",function(){$('input[name="email"]').val($(this).text())})});</script><script type="text/javascript">function getURLParameter(e){return decodeURIComponent((RegExp(e+"=(.+?)(&|$)").exec(location.search)||[,null])[1])}function getURLParameterExact(e){for(var t=window.location.search.substring(1).split("&"),n=0;n<t.length;n++){var r=t[n].split("=");if(r[0]==e)return r[1]}}</script><script type="text/javascript">window.addEventListener("load",function(){$(function(){"null"!=getURLParameter("email")&&($('input[name="contact[email]"]').val(getURLParameterExact("email")),$("[name=email]").val(getURLParameterExact("email"))),"null"!=getURLParameter("name")&&($('input[name="contact[name]"]').val(getURLParameterExact("name")),$("[name=name]").val(getURLParameterExact("name"))),"null"!=getURLParameter("first_name")&&($('input[name="contact[first_name]"]').val(getURLParameter("first_name")),$("[name=first_name]").val(getURLParameter("first_name"))),"null"!=getURLParameter("last_name")&&($('input[name="contact[last_name]"]').val(getURLParameter("last_name")),$("[name=last_name]").val(getURLParameter("last_name"))),"null"!=getURLParameter("address_1")&&($('input[name="contact[address_1]"]').val(getURLParameter("address")),$("[name=address_1]").val(getURLParameter("address_1"))),"null"!=getURLParameter("address_2")&&($('input[name="contact[address_1]"]').val(getURLParameter("address")),$("[name=address_2]").val(getURLParameter("address_2"))),"null"!=getURLParameter("city")&&($('input[name="contact[city]"]').val(getURLParameter("city")),$("[name=city]").val(getURLParameter("city"))),"null"!=getURLParameter("state")&&($('input[name="contact[state]"]').val(getURLParameter("state")),$("[name=state]").val(getURLParameter("state"))),"null"!=getURLParameter("zip")&&($('input[name="contact[zip]"]').val(getURLParameter("zip")),$("[name=zip]").val(getURLParameter("zip"))),"null"!=getURLParameter("phone")&&($('input[name="contact[phone]"]').val(getURLParameter("phone")),$("[name=phone]").val(getURLParameter("phone")))})});</script>
<script type="text/javascript" src="https://app.clickfunnels.com/assets/pushcrew.js" async="async"></script><meta name='can_calculate_taxes' content='false'>
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-P79RNGH"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

<link href="https://cdnjs.cloudflare.com/ajax/libs/fotorama/4.6.4/fotorama.css" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/fotorama/4.6.4/fotorama.js"></script>
<script src='https://www.clickfunnels.com/assets/cf_modal.js' type='text/javascript'></script><script defer src="https://static.cloudflareinsights.com/beacon.min.js" data-cf-beacon='{"rayId":"6a40823840fe5533","token":"405b708a9b0242e88fda34dc27903686","version":"2021.10.0","si":100}'></script>
<script defer src="https://static.cloudflareinsights.com/beacon.min.js" data-cf-beacon='{"rayId":"6a40823818e75533","token":"405b708a9b0242e88fda34dc27903686","version":"2021.10.0","si":100}'></script>
</body>
</html>
