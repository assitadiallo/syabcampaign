<!-- 

Centaurs v.2 Theme 
Created by Modernise (modernise.tumblr.com)
Please leave at least ONE credit link. Do not delete this box.

Theme is best viewed on Google Chrome, with a resolution of 1280x800.

*~*~HOW TO INSTALL~*~*
1) Copy this entire code.
2) Open up the customise.
3) Click on Edit HTML
4) Delete the code already in there.
5) Replace it with this code.
6) Hit Update Preview, and then Save.
7) Refresh the page, and press Save again.
8) If it wont let you paste in the box, or if it still does not work, use classic customize. (http://tumblr.com/customize-classic/)

If you are experiencing any problems with this theme, please refer to the FAQ on modernisethemes. (http://modernisethemes.tumblr.com/faq)
Thank you for choosing Modernise Themes <3! 

-->

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<meta name="font:Text" content="Georgia"/>
<meta name="text:Font Size" content="9px"/>
<meta name="color:Text" content="#888"/>
<meta name="color:Background" content="#fff"/>
<meta name="color:Post" content="#fff"/>
<meta name="color:Borders" content="#cccccc"/>
<meta name="color:Blockquote" content="#f5f5f5"/>
<meta name="color:Links" content="#000056"/>
<meta name="color:Hover" content="#727292"/>
<meta name="image:Background" content=""/>
<meta name="image:Header" content=""/>
<meta name="if:Title Font" content="1"/>
<meta name="if:Image Fade" content="1">
<meta name="if:Rounded Corners" content="1">
<meta name="if:CustomLink1" content="1">
<meta name="if:CustomLink2" content="1">
<meta name="if:CustomLink3" content="1">
<meta name="if:CustomLink4" content="0">
<meta name="if:CustomLink5" content="0">
<meta name="text:Link 1 Title" content="custom link">
<meta name="text:Link 1" content="http://">
<meta name="text:Link 2 Title" content="custom link">
<meta name="text:Link 2" content="http://">
<meta name="text:Link 3 Title" content="custom link">
<meta name="text:Link 3" content="http://">
<meta name="text:Link 4 Title" content="custom link">
<meta name="text:Link 4" content="http://">
<meta name="text:Link 5 Title" content="custom link">
<meta name="text:Link 5" content="http://">
<meta name="if:Animated Post Load" content="0">
<meta name="if:Cross Cursor" content="1">
<meta name="if:Click Photo To Reblog" content="1">
<meta name="if:Infinite Scroll" content="1">
<meta name="if:Scroll To Top" content="1">


<link rel="shortcut icon" href="{Favicon}">
{block:Description}
<meta name="description" content="{MetaDescription}" />
{/block:Description}

<title>{Title}</title>

<script type="text/javascript" 
src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.1/jquery.min.js"></script> 
{block:IfScrollToTop}
<script type="text/javascript" src="scrolltopcontrol.js">
</script>

<script type="text/javascript" src="http://static.tumblr.com/iddq6cw/4Gum31dpt/modernise.js">
</script>

{/block:IfScrollToTop}
<style type="text/css">


/* Body Controls */
html {
    height:100%;
}


body {
    font-family:{font:Text};
    font-size:{text:Font Size};
    color:{color:Text};
    letter-spacing:0px;
    background-color:{color:background};
    background-image:url('{image:Background}');
    background-color:{color:Background};
    background-repeat: repeat;
    background-position: top center;
    background-attachment: fixed;
    text-align:justify;
    line-height:100%;
    height:100%;
    {block:IfCrossCursor}
cursor: crosshair, auto;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}
}


@font-face {
font-family:basket;
src: url('http://static.tumblr.com/iddq6cw/2qqm2zf39/lavanderia_sturdy.otf');
}

a {
    color:{color:Links};
    text-decoration: none;
    -webkit-transition-duration:1s;
    {block:IfCrossCursor}cursor:crosshair;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}
}

a:hover {
    color:{color:Hover};
    text-decoration: none;
    {block:IfCrossCursor}
cursor: crosshair, auto;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}

}

u { 
    border-bottom: 1px dashed #888; 
}

b, strong{
font-size: 9px; 
letter-spacing: 1px; 
color: #b1b1b1; 
font-family: georgia;
text-transform: none;
text-shadow: 1px 1px 2px #e1dad4;
text-decoration: none;
font-weight: normal;
}

iframe#tumblr_controls {
    right:3px !important; 
    position: fixed !important;
    -webkit-transition: opacity 0.7s linear;
    opacity: 0.5;
    -webkit-transition: all 0.8s ease-out;
    -moz-transition: all 0.8s ease-out;
    transition: all 0.8s ease-out;
}

iframe#tumblr_controls:hover {
    -webkit-transition: opacity 0.7s linear;
    opacity: 1;
    -webkit-transition: all 0.4s ease-out;
    -moz-transition: all 0.4s ease-out;
    transition: all 0.4s ease-out;
}

::-webkit-scrollbar-thumb:vertical { 
    background-color:{color:Links};
    height:auto;
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5);
    -webkit-border-radius:4px;
}

::-webkit-scrollbar-thumb:horizontal { 
    background-color:{color:Links};
    height:6px !important;
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5);
    -webkit-border-radius:4px;
}

::-webkit-scrollbar { 
    height:6px;
    width:6px; 
    background-color:{color:Background};
}

::-webkit-scrollbar-corner {
    background-color:{color:Background};
}

#content {
    width:100%; 
    margin-left:auto; 
    margin-right:auto;
    position: relative;
    {block:IfCrossCursor}cursor:crosshair;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}
}

.karkat {
    background-color:{color:Post};
    display:block;
    width:862px;
    height:100%;
    z-index:-1;
    margin-left:auto;margin-top:-10px;bottom:-10px;
    margin-right:auto;
    {block:IfCrossCursor}cursor:crosshair;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}
}

ul {
margin-left:-25px;
}




/* Header Controls */

.sidebar {
    width:862px;
    background-color:{color:Post};
    z-index:5;
    margin-right:auto;
    margin-left:auto;
    text-align:center;
    display:block;
    position:fixed;
    margin-bottom:25px;
    opacity:0.85;
    padding-top:10px;padding-bottom:10px;
    border-bottom:1px solid {color:Borders};
    {block:IfCrossCursor}cursor:crosshair;{/block:IfCrossCursor}
    {block:IfNotCrossCursor}cursor:default;{/block:IfNotCrossCursor}
}

.navigation  {
    font-size:{block:IfTitleFont}45px{/block:IfTitleFont}
    {block:IfNotTitleFont}30px{/block:IfNotTitleFont};
    color:{color:Links};
    letter-spacing:0px;
    -webkit-transition-duration:1.5s;
    font-family:{block:IfTitleFont}basket{/block:IfTitleFont}
    {block:IfNotTitleFont}{font:text}{/block:IfNotTitleFont};
    text-align:center;line-height:{block:IfTitleFont}45px{/block:IfTitleFont}
    {block:IfNotTitleFont}30px{/block:IfNotTitleFont};
}


/* Post Controls */

#content .posts { 
    {block:IndexPage}width:837px;{/block:IndexPage}
    {block:PermalinkPage}width:825px;{/block:PermalinkPage}
    padding-left:25px;
    margin-right:auto;
    margin-left:auto;padding-top:150px;
    position:relative;
    background-color:{color:Post};
}

#content .posts img {
    {block:IndexPage}
    max-width: 250px; 
    margin-top:-2px; 
    {/block:IndexPage}
    {block:PermalinkPage}
    max-width: 800px; 
    {/block:PermalinkPage}
    {block:IfRoundedCorners}
    -webkit-border-radius:4px;
    {/block:IfRoundedCorners}
}


#content .entry {
    {block:IndexPage}
    width:250px;
    float:left;
    position: relative;
    {/block:IndexPage}
    margin-right:25px; 
    margin-bottom:23px;
    padding:2px;
    z-index:1;
    {block:PermalinkPage}
    width:800px; 
    {/block:PermalinkPage} 
    {block:IfAnimatedPostLoad}
    -webkit-transition-duration:2s;
    {/block:IfAnimatedPostLoad}
} 

.heading {
    font-family:{font:Text};
    font-size:15px;
    text-decoration: none;
    letter-spacing:0px;
    font-weight:none;
    line-height:100%;
    margin-bottom:0px;
    text-align:left;
}

.chat ul {
    padding:0px 0px 0px 0px;
    margin:0px 0px 0px 0px;
}

.chat li {
    list-style-type: none;
    padding-left:0px;
    margin-right:0px;
}

.chat li.odd {
    color:{color:Text};
}

.chat li.even {
    color: {color:Text};
    background-color: {color:Blockquote};
}
.emp{
    }
.label {
font-size: 9px; 
letter-spacing: 1px;
font-family: trebuchet ms;
text-transform: uppercase;
text-shadow: 1px 1px 2px #e1dad4;
text-decoration: none;
font-weight: normal;
color:{color:links}
}

blockquote { 
    padding-left:5px;
    padding-top:3px;
    padding-right:5px;
    padding-bottom:3px;
    margin-left:5px; 
    margin-right:5px;
    border-left: 2px solid {color:Borders};
    border-right:none;
    background-color:{color:Blockquote};
}

.stan { 
    background-color:{color:Blockquote};
}

.kyle {
    font-style:italic;
    line-height:100%;
    margin-bottom:0px;
}

{block:IfImageFade}
.img {
    {block:IndexPage}
    opacity:0.8;
    filter:alpha(opacity=80);
    {/block:IndexPage}
    -webkit-transition-duration:0.4s;
}

.img:hover {
    opacity:1;
    filter:alpha(opacity=100);
}
{/block:IfImageFade}


.stoley img {
    {block:IndexPage}
    max-width:250px;
    overflow-y:auto;
    {/block:IndexPage}
}

.kenny {
    width:800px;
    opacity: 1;
    z-index: 10000;
    margin-top:10px;
    margin-bottom:10px;
    text-align:center;
    font-family:helvetica;
    font-size:8px;
    letter-spacing:1px;
    text-transform:uppercase;
}

.cartman {
    margin-top:0;
    margin-left:0px;
    margin-right:auto;
    margin-bottom:0px;
    width:800px;
    text-align:center;
    background-color:{color:Post};
}

.wendy {
    text-align:center;
    width:800px;
    margin-left:auto;
    margin-right:auto;
}

.video embed, .video object, .video iframe {
    {block:IndexPage}
    width:250px /**/ !important;
    {/block:IndexPage}
    {block:PermalinkPage}width:800px !important;
    {/block:PermalinkPage}
    height:auto !important;
}


.audioplayer {
    background-color:#e4e4e4;
    {block:IfRoundedCorners}
    border-radius:4px;
    -o-border-radius:4px;
    -moz-border-radius:4px;
    -webkit-border-radius:4px;
    padding-left:4px;
    {/block:IfRoundedCorners}
}

/* Permalink Controls */

.entry .permalink {
    padding-top:0px;
}

.tweek {
    font-size:15px;
    line-height:100%;
    padding:2px;
    color:#fff;
    z-index:987897978978999999;
}

#craig {
    color:#fff;
    font-size:10px;
    opacity: 0; 
    margin-top:0px;
    padding-left:5px;padding-right:5px;
    margin-left:5px;
    width:auto; 
    height:20px;
    background-color: #000; 
    padding-top:5px;
    float:left;display:block;
    text-align:center;
    font-family:helvetica;
    letter-spacing:1px;
    border-radius:4px;
    -o-border-radius:4px;
    -moz-border-radius:4px;
    -webkit-border-radius:4px;
}


#craig a {
    color:#fff;
}

#craig:hover {
    
    z-index:99933999;
}
.tweek:hover{
    z-index:999999;
}

.entry:hover #craig {
    opacity:0.5;
    z-index:999999;
}

#craig:hover .img {
    opacity:1;
}

.clear {
display: none;
}

ol.notes {
    padding: 0px;
    margin: 25px 0px;
    list-style-type: none;
    border-bottom: solid 1px #ccc;
}

ol.notes li.note {
    border-top: solid 1px #ccc;
    padding: 6px;
}


.mj {
    width: 21px;
    height: 20px;
    display: block;
    position: relative;
    opacity: 0;
    z-index: 1000000;
}

.mj a {
    width: 21px;
    height: 20px;
    margin-top:-25px;
    padding-left:5px;padding-right:5px;
    width:21px; 
    margin-left:5px;
    background-color: #000; 
    padding-top:5px;
    float:left;
    border-radius:4px;
    background-image: url("http://static.tumblr.com/uiqhh9x/BPnlzww8v/like.png");  
    background-repeat:no-repeat;
    background-position: 5px 4px;
    z-index: 1000000;
}

.mj:hover {
    opacity: 0.5;

}

.entry:hover .mj{
    opacity: 0.5;
}

{CustomCSS}

</style>


{block:IfInfiniteScroll}
<script src="http://static.tumblr.com/df28qmy/SHUlh3i7s/jquery.infinitescroll.js"></script>
{/block:IfInfiniteScroll}
    
<script src="http://static.tumblr.com/thpaaos/lLwkowcqm/jquery.masonry.js"></script>

<script type="text/javascript">
$(window).load(function () {
$('.posts').masonry(),
$('.masonryWrap').infinitescroll({
navSelector : "div#navigation",
// selector for the paged navigation (it will be hidden)
nextSelector : "div#navigation a#nextPage",
// selector for the NEXT link (to page 2)
itemSelector : ".entry, .clear",
// selector for all items you'll retrieve
bufferPx : 10000,
extraScrollPx: 10,
loadingImg : "http://static.tumblr.com/ejm8w78/KZjlxxt0d/ajax-loader.gif",
loadingText : "<em></em>",
},
// call masonry as a callback.
function() { $('.posts').masonry({ appendedContent: $(this) }); }
);
});
</script>



<script type="text/javascript">
$(window).load(function(){
$("p").remove(":contains('(Source:')");
$("p").remove(":contains('(via ')");
});
</script>

</head>

<body>

<div class="karkat"><div class="bk"></div>
<div id="content">
<div class="sidebar">
<div class="navigation"><a href="/">
{block:IfHeaderImage}<img src="{image:Header}" max-width="500">{/block:IfHeaderImage}{block:IfNotHeaderImage}{Title}{/block:IfNotHeaderImage}</a></div>
<div align="center">
<div style="max-width:500px;margin-left:auto;margin-right:auto;">
{Description}
</div>
<br>
<a href="/">home</a>
&nbsp;&nbsp;<a href="/ask">message</a>
&nbsp;&nbsp;<a href="/archive">history</a>
{block:SubmitEnabled}&nbsp;&nbsp;
<a href="/submit">submit</a>{/block:SubmitEnabled}
{block:HasPages}
{block:Pages}
<a href="{URL}">&nbsp;&nbsp;{Label}</a>
{/block:Pages}
{/block:HasPages}
{block:IfCustomLink1}
<a href="{text:Link 1}">&nbsp;&nbsp;{text:Link 1 Title}</a>
{/block:IfCustomLink1}
{block:IfCustomLink2}
<a href="{text:Link 2}">&nbsp;&nbsp;{text:Link 2 Title}</a>
{/block:IfCustomLink2}
{block:IfCustomLink3}
<a href="{text:Link 3}">&nbsp;&nbsp;{text:Link 3 Title}</a>
{/block:IfCustomLink3}
{block:IfCustomLink4}
<a href="{text:Link 4}">&nbsp;&nbsp;{text:Link 4 Title}</a>
{/block:IfCustomLink4}
{block:IfCustomLink5}
<a href="{text:Link 5}">&nbsp;&nbsp;{text:Link 5 Title}</a>
{/block:IfCustomLink5}
&nbsp;&nbsp;<a href="http://modernise.us">theme</a>

</div>
{block:IndexPage}
<div class="column navigation" id="navigation">
{block:Pagination}
{block:PreviousPage}<a href="{PreviousPage}" class="navigate">{/block:PreviousPage}{block:PreviousPage}</a>{/block:PreviousPage} 
{block:NextPage}<a href="{NextPage}" class="navigate" id="nextPage">{/block:NextPage}{block:NextPage}</a>{/block:NextPage}{/block:Pagination}
</div>
{/block:IndexPage}

<br>
<br>
</div>
<div class="posts">
{block:Posts} 
<div class="entry">


{block:Text}
{block:Title} <a href="{permalink}"><div class="heading">{title}</div></a> {/block:Title}
<div class="stoley">{Body}</div>

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}

{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Text}

{block:Photo}
<div class="img" {block:IndexPage}style="margin-bottom:-15px;"{/block:IndexPage}>
{block:IndexPage}{block:IfClickPhotoToReblog}<a href="{ReblogURL}">{/block:IfClickPhotoToReblog}{block:IfNotClickPhotoToReblog}<a href="{Permalink}">{/block:IfNotClickPhotoToReblog}{/block:IndexPage}
{block:PermalinkPage}<a href="{PhotoURL-HighRes}">{/block:PermalinkPage}
<img src="{PhotoURL-500}" alt="{PhotoAlt}" {block:IndexPage}width="250px"    {/block:IndexPage}{block:PermalinkPage}width="800"{/block:PermalinkPage}/>
</a>
</div>

{block:IndexPage}
<div class="tweek">

    <div style="margin-left:36px;"><div id="craig"><a href="{Permalink}">{NoteCount}</a></div>
    <div id="craig"><a href="{ReblogURL}">reblog</a></div></div>
<span class="mj"><a id="like{PostID}" href="javascript:likelink('{PostID}','{Permalink}','');"><img src="http://static.tumblr.com/lba83dv/OUUltd958/spacer.gif" width="21" height="20" id="likeimage{PostID}"/></a></span>
    
</div>


{/block:IndexPage}
{block:PermalinkPage}
{block:Caption}{Caption}{/block:Caption}<br>
<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}

{/block:Photo}


{block:Photoset}


{block:IndexPage}<center>{Photoset-250}</center><div class="tweek"><a href="{Permalink}"><div class="craig">{NoteCount}</div></a></div>{/block:IndexPage}

{block:PermalinkPage}
{Photoset-500}<br>{block:Caption}{Caption}<br><br>{/block:Caption}
{/block:PermalinkPage}

{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Photoset}


{block:Quote}
<a href="{permalink}"><div class="heading"><i>{Quote}</i></div></a>
{block:Source} <div align="right">― {Source}</div>{/block:Source}

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}

{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Quote}


{block:Link}
<div class="heading"><a href="{URL}"{Target}>&rarr; {Name}</a></div>
{block:Description} {Description}{/block:Description}

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}


{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Link}

{block:Video}
{block:PermalinkPage}<div class="video">{Video-500}
</div>{/block:PermalinkPage}

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}


{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Video}


{block:Chat}
{block:Title}
<div class="heading"><a href="{Permalink}">{Title}</a></div>
{/block:Title}
<div class="chat ul">
{block:Lines}
<li class="{Alt} user_{UserNumber}">
{block:Label}<span class="label">{Label}</span>{/block:Label} {Line}</li>
{/block:Lines}</div></li>

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}

{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date}
{block:RebloggedFrom}<Br>Reblogged from: <a href="{ReblogParentURL}">{ReblogParentName}</a><br>{/block:RebloggedFrom}
{block:RebloggedFrom}Originally posted by: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br>Tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Chat}



{block:Audio}{block:PermalinkPage}
{block:AlbumArt}
<img src="{AlbumArtURL}" style="width:500px;">{/block:AlbumArt}{/block:PermalinkPage}
<div class="audioplayer">{AudioPlayerGrey}</div>
{block:Caption}{Caption}{/block:Caption}
{block:PermalinkPage}
<br>{PlayCountWithLabel}{/block:PermalinkPage}

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}


{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Audio}


{block:Answer}
<div style="text-align:left;padding-left:5px;padding-right:5px;border-left: 2px solid {color:Borders};border-right: 2px solid {color:Borders};background-color:{color:blockquote};"><div class="stan">{Asker}: {Question}</div></div><div style="text-align:left;"><div class="kyle">{Answer}</div></div>

{block:IndexPage}<div style="font-size:8px;text-align:center;text-decoration:underline;">
    <a href="{Permalink}">{12Hour}:{Minutes}&nbsp;{AmPm}&nbsp;&nbsp;{/block:IfShowTimestamp}&bull;&nbsp;&nbsp;{DayOfMonth}&nbsp;{Month}&nbsp;{Year}{block:NoteCount}&nbsp;&nbsp;&bull;&nbsp;&nbsp;{NoteCountWithLabel}{/block:NoteCount}</a></div>
{/block:IndexPage}

{block:PermalinkPage}


<div class="kenny">
{block:Date}Posted on {DayOfWeek}, {Month} {DayOfMonth}{DayOfMonthSuffix} at {12HourWithZero}:{Minutes}{CapitalAmPm}{/block:Date} {block:NoteCount}with {NoteCountWithLabel}{/block:NoteCount}

{block:RebloggedFrom}<br>via: <a href="{ReblogParentURL}">{ReblogParentName}</a> , {/block:RebloggedFrom}
{block:RebloggedFrom}source: <a href="{ReblogRootURL}">{ReblogRootName}</a>{/block:RebloggedFrom}
{block:HasTags}<br><Br> tagged as: {block:Tags}<a href="{TagURL}">{Tag}</a>, {/block:Tags}{/block:HasTags}</div>
<div class="cartman">{block:PostNotes}{PostNotes}{/block:PostNotes}</div>
{/block:PermalinkPage}
{/block:Answer}


</div>

{/block:Posts}
</div>
    
    
{block:IfNotInfiniteScroll}
    <div style="padding-bottom:10px;">
<Center>
{block:Pagination}
            {block:PreviousPage}
                <a href="{PreviousPage}">-</a>
            {/block:PreviousPage}/
 
            {block:JumpPagination length="5"}
                {block:CurrentPage}
                    <span>{PageNumber}</span>
                {/block:CurrentPage}
 
                {block:JumpPage}
                    <a class="jump_page" href="{URL}">{PageNumber}</a>
                {/block:JumpPage}
            {/block:JumpPagination}
 
           /{block:NextPage}
                <a href="{NextPage}">+</a>
            {/block:NextPage}
        {/block:Pagination}</center>
       </div>
{/block:IfNotInfiniteScroll}
    
<div class="clear"></div>
</div>

</div>
</div>

</div>
<div style="display:block;bottom:5px;right:5px;font-size:12px;font-family:courier new;position:fixed;background-color:#ffffff;padding:3px;border-radius:4px;z-index:5;opacity:0.75;"><a href="http://modernise.us/">♏</a></div>


<script type="text/javascript" src="http://static.tumblr.com/iddq6cw/cz1m316ry/arny.js"></script>
<iframe id="likeiframe" style="display:none;"></iframe>

</body>



</html>
