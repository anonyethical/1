# 1
<!DOCTYPE html >

<!--[if IE 7 ]><html class="ie ie7" lang="en"> <![endif]-->
<!--[if IE 8 ]><html class="ie ie8" lang="en"> <![endif]-->
<!--[if (gte IE 9)|!(IE)]><!-->

<html lang="en">
<!--<![endif]-->

<head>
<title> Welcome to Indiapost </title>

<!-- Basic Page Needs
  ================================================== -->
<meta charset="utf-8" http-equiv="X-UA-Compatible" />
<meta name="description" content="" />
<meta name="author" content="" />
<meta content="no-cache, no-store, must-revalidate" />
<meta content="no-cache" />

<!-- Mobile Specific Metas
  ================================================== -->
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

<!-- CSS ================================================== -->
<link href='images/favicon.ico' rel='icon' type='image/x-icon'/>
<!--[if lt IE 7]>
		<script src="js/html5.js"></script>
		<script src="js/css3-mediaqueries.js"></script>
	<![endif]-->

<script src="js/jquery.min.js"></script>
<script src="js/ddsmoothmenu.js"></script>
<script src="js/modernizr.js"></script>

<style>
body { font-family: 'Segoe UI'; font-size: 13px;}
#container { padding: 20px 0; }
#content { margin: 0 auto; margin-top: 60px; }
p, div, ol, ul { MARGIN-BOTTOM: 0px; MARGIN-TOP: 0px }
h2 { font-size: 18px; text-align: left; margin: 5px 0; }
h3 { font-size: 16px; margin: 0; color: #b52a25; }
h4 { font-size: 14px; margin: 0; }

a { color: #06F; text-decoration: none; }
a:hover { color: #333333; text-decoration: underline; }
ul { float: none; list-style: none; text-align: left }
ul.features_list { list-style-image: url(images/arrow.png); padding: 5px 15px; }
.features_list li { margin: 15px 0; }
.zerogrid { width: 1000px; position: relative; margin: 0 auto; padding: 0px; background-color: transparent; }
#header { }
#header .wrap-header { height: 112px; border: 0; }
#header #logo { top: 40px; width: 460px; border: 0; float: left }
#header #logo img { float: left; border: 0 }
#header #emblem { border: 0; float: right; margin: 0; }

.wpmd { FONT-SIZE: 18px; FONT-WEIGHT: normal; FONT-STYLE: normal }
.login { width: 1000px; height: 320px; border:0; margin: 0 auto; }
.login_box1 { float: left; margin: 22px 0; text-align: left; width: 630px; }
.login_box1 h3 { font-size: 24px; font-weight: normal; color: #b52a25; }
.login_box1 h4 { margin-top: 10px; line-height: 15px }
.login_box2 { width: 350px; border: 1px solid #aaa; float: right; margin: 20px 0px 0 0; padding: 0; background: #F7F7F7; }
.heading { text-align: left; margin: 0; color: #fff; background: #b52a25 url(images/login1.png) no-repeat 1% 50%; padding-left: 30px; font-size: 16px; line-height: 30px; font-weight: normal; }
.login_box2 label { float: left; width: 100px; font-size: 13px; }
.forgot_password { margin: 5px 25px 20px 10px; float: left; font-size: 12px; }
.login_font { font-size: 20px; float: left; padding: 0 0 0 160px; }

.error_msg { margin-bottom: 10px;float: left;}
.error_txt { font-size: 12px; color: #F00; text-align: left; margin-left: 110px; }

.block1 { width: 100%; height: 28px; margin: 0; }
box2_content { width: 200px; height: 300px; float: left; border: 10px solid #000; }
.box2_list { float: left; }
.red { font-family: 'Segoe UI'; font-size: 13px; height: 30px; color: #fff; border: 1px #980c10; background: #b52a25; background: -webkit-gradient(linear, left top, left bottom, from(#b62a26), to(#921311)); background: -moz-linear-gradient(top, #b62a26, #921311); -webkit-border-radius: .5em; -moz-border-radius: .5em; border-radius: .5em; filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#b62a26', endColorstr='#921311'); float:left;}
.button { font-family: 'Segoe UI'; height: 30px; font-size: 13px; height: 30px; color: #333; border: 1px solid #ccc; -webkit-border-radius: .5em; -moz-border-radius: .5em; border-radius: .5em; background: #ddd; background: -webkit-gradient(linear, left top, left bottom, from(#ddd), to(#eee)); background: -moz-linear-gradient(top, #ddd, #eee); background-image: linear-gradient(#ddd, #eee); filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#dddddd', endColorstr='#ffffff');
}
.new_ac { width: 350px; margin: 10px 0px 0px 0; text-align: center; float: right; clear: right; white-space: nowrap; border: 1px solid #aaa; padding-bottom: 10px; background: #f7f7f7 }
.new_ac .heading { margin-bottom: 10px; background: #666; padding-left: 10px; text-align: center; font-size: 13px }
.new_ac a { padding-right: 10px; }
.user-image { float: left; }
.mandatory { color: #DB0000; }
#text1, #text2 { OVERFLOW: hidden; line-height: 30px; margin-left: 30px; }
#text3 { margin-left: 8px }
.input_long { width: 200px; height:24px; line-height:25px; border:1px solid #ccc; padding-left:5px}
/* ------------------Footer------------------- */
#footer { position: absolute; bottom: 0; width: 100% }
#footer .copyright { margin-top: 100px; text-align: center; background-color: #b62a26; margin: 0; bottom: 0; }
#footer .copyright p { text-align: center; padding: 5px; color: #fff; margin: 0; font-size: 13px; }
</style>

<script type="text/javascript">
function resetCredFields()
{
  document.Login.PASSWORD.value = "";
}

function CheckForm(Login)
{

if(document.forms["Login"]["USER"].value == ""|| document.forms["Login"]["USER"].value == null || document.forms["Login"]["PASSWORD"].value == "" || document.forms["Login"]["PASSWORD"].value == null)
  {
  alert("UserName and Password Are Mandatory!!!!");
  document.forms["Login"]["USER"].focus();
  return false;
  }
else {
	submitForm();
	return	true;
		}
}

function submitForm()
{
     document.Login.submit();
}
</script>
<script type="text/javascript">
    function submitOnEnter(inputElement, event) {
        if (event.keyCode == 13) { // No need to do browser specific checks. It is always 13.
            submitForm();
        }
    }
</script>
<meta name=GENERATOR content="MSHTML 10.00.9200.16736">
</head>

<body>
<div id="container" role="banner" >
  <div style="border-bottom:2px solid #b62a26;width:100%" class="zerogrid">
    <div id="header" style="border-bottom:2px solid #fee600; width:100%">
      <div class="wrap-header zerogrid"> 
        <div id="logo" style="float:left"><a href="https://www.indiapost.gov.in/VAS/Pages/IndiaPosthome.aspx"><img src="./images/logo.png" alt="Logo"></a></div>
        <div id="emblem"><img src="./images/emblam.png" alt="Emblem"></div>
	
      </div>
    </div>
  </div>
  <!--------------Content--------------->
<br>
<fieldset>
<legend>Sign in</legend>
  <div id="content" class="zerogrid" role="main" >
 
    <form NAME="Login" METHOD="POST" autocomplete="off">
      <input TYPE=HIDDEN NAME="SMENC" VALUE="UTF-8">
      <input type=HIDDEN name="SMLOCALE" value="US-EN">
      <div class="login">
        <div class="login_box1" role="banner" aria-label="access a range of services" >
          <h3 aria-label="Sign in to your India Post account">Sign in to your India Post account</h3>
          <p style="font-size:16px">To access a range of services:  </p>
          <ul class="features_list">
            <li>
              <h4>Book Mails </h4>
              <p>Book to send your Letter, Parcel, Documents within India, manage your mails and view transaction history </p>
            </li>
            <li>
              <h4>Business solutions</h4>
              <p>Avail our business mailing services, book bulk mail, request a pickup, manage your account and track delivery status </p>
            </li>
            <li>
              <h4 aria-label="philately accounts">Philately</h4>
              <p>Open and manage philately accounts </p>
            </li>
	</ul>
        </div>
        <div class="login_box2" role="contentinfo">
          <h2 class="heading" aria-label="Sign in with username">Sign in</h2>
          <div id="text1">
            <div class="wpmd">

       
              <div style="float:left;margin-top:10px;" role="complementary" >
                <label for="USER" id="lbluser" title="User">User ID:<span class="mandatory">*</span></label>
                <input type="text" id="USER" name="user" aria-labelledby="lbluser" class="input_long" Value="" autocomplete="off">
              </div>
            </div>
          </div>
          <div id="text2">
            <div class="wpmd">
              <div style="float:left;margin-top:10px;" role="complementary" >
                <label for="password"  id="lblpassword" title="Password">Password/OTP#:<span class="mandatory">*</span></label>
                <input type="password" id="PASSWORD" name="password" aria-labelledby ="lblpassword" title="password" class="input_long" onkeypress="submitOnEnter(this, event);" autocomplete="off" >
              </div>
            </div>
          </div>
          <div id="text3" role="form" >
            <div class="wpmd" role="form" aria-label="Forgot Password page">
              <div>
                <input type=hidden name=target value="HTTPS://www.indiapost.gov.in:8080/affwebservices/public/wsfeddispatcher?wa=wsignin1.0&amp;wtrealm=urn%3asp_prod&amp;wctx=https%3a%2f%2fwww.indiapost.gov.in%2f_layouts%2f15%2fAuthenticate.aspx%3fSource%3d%252F&amp;wreply=https%3a%2f%2fwww.indiapost.gov.in%2f_trust%2fdefault.aspx">
                <input type=hidden name=smquerydata value="46q7PzyZ+6XhiN8uMgvWSIqv3GtCOkyP7hcew8yGso6TzeqY7v/XZG/cyHFTABjZv0kh6Z7wD+3Kfa/30ze2sZEAOhl/RYJyHjtxUnonUlBGaV7vnuceNCtOFfqyAQuRQZkxtHvjL6Cm7PmHdaXpQz1Y79aUmCQxQUkRiUxUkluYbre0JNKN0uzYU0WNiwEeaXJSXFJwSaEfClNelMTwsy6JE7Kd02+KCFJrNPJhDGeRfonLsb7PpcK000ait/IKi5nMlvNhIkODQH43sOYIh0UzwALGU+lEXpTlD6a7bRYpr2nM7/qxWo2InTj43F1QFp7qoDpsPPknhEJEKBn/mHdmrAVdeTvBD6sAKhPX3W0cjcdm4oHNwDzCDoY4yrNlZJWGO5u2l7SXcozPCD1JXtx/iPZXnJinYnmp0HWH0ceJHqm5SNlsWWr6V2sroxvOp1itVXGMxINCNWPpxGxhF0qL4z1Pu1AVYEb8m1JxK4PRQ+0ojrZeCKekJMOOBNqEmkIBoygV0SNAJG2brmzxCZYWH/NKXM8Up7Lwpj2WOHNHC+tdJ6p3vb1vhqldgCq/AtXCTDnliao5GgoIPAf4dEmA0AU6YafxNerBF3GvOsPwulMt6GRNUbue2dqs7S0yASY/VUhgA7gC6Mpxi8bSbN0/97Iytst2krQgNG/jzXNOdVxQcLTOk2s2MQaxc+7fcXApffHlEPgLS1KOF2LvKxKsnnsVibwgZwMob5sEJQfW5v8459OPjRyt7T0QKCum">
                <input type=hidden name=smauthreason value="0">
                <input type=hidden name=smagentname value="HHfgiZq0vHyQAcTltAij9eUotgzKxmDHjm8HYojD4/ooL+x1a+n7XzTFXifAuEWF">
                <input type=hidden name=postpreservationdata value="">
                <div style="margin: 10px 0 0 150px;" role="form" aria-label="Forgot Password link">
                  <input onClick="CheckForm(this.form)" type="button" class="red" value="Sign In">
                  <a href="https://www.indiapost.gov.in/VAS/Pages/ForgotPassword.aspx" class="forgot_password"><u>Forgot Password?</u></a> </div>
 <div style="margin: 5px;" role="form">
			  <h4>#OTP for first time users</h4>
             </div>
<div class="new_ac">
          <h2 class="heading">Don't have an account?</h2>
          <a href="https://www.indiapost.gov.in/vas/pages/userregistration.aspx"><u>  &nbsp; Create a new account &nbsp; </u></a> </div>
          </div>			  
          	  
              </div>
            </div>
          </div>          
        </div>
     </form>
       </div>
    <script type="text/javascript">
  document.forms["Login"].elements["USER"].focus();
</script> 
  
</fieldset>
    </div>
  <!--------------Footer--------------->
  <div id="footer" >
<div style="background:#555;height:30px;" role="contentinfo">
      <p style="margin-top: 5px;position: relative;">
<a title="Home" href="https://www.indiapost.gov.in/VAS/Pages/IndiaPosthome.aspx" style="color: white;margin: 190px;margin-right: 10px;" aria-label="Home_link"><u>Home</u></a> 
          <a title="Help" href="https://www.indiapost.gov.in/VAS/Pages/CustomerSupport/Help.aspx" style="color: white;margin-right: 10px;" aria-label="Help_Link"><u>Help</u></a>
           <a title="Sitemap" href="https://www.indiapost.gov.in/VAS/pages/sitemap.aspx" style="color: white;margin-right: 10px;" aria-label="Sitemap"><u>Sitemap</u></a>  
             <a title="Contact Us" href="https://www.indiapost.gov.in/VAS/Pages/content/ContactUs.aspx" style="color: white;" aria-label="Contact Us"><u>Contact Us</u></a>             </p>
    </div> 
    <div class="copyright" role="banner" >
	
      <p>

&#169; Content Owned by Department of Posts, Ministry of Communications, Government of India </p>
    </div>
  </div>

</body>
</html>
