<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="css/reset.css">
  <link rel="stylesheet" href="css/header.css">
  <link rel="stylesheet" href="css/footer.css">
  <link rel="stylesheet" href="css/about.css">
  <link rel="stylesheet" href="css/login.css">
  <link rel="stylesheet" href="css/css.css">
  <script src="js/login.js"></script>
</head>

<body>
  <!-- 头部 -->
  <div class="header">
    <div class="inner-1200">
      <div class="logo">
         <p style="color:#fff; margin-top:25px; font-size:20px; font-family:Tahoma, Geneva, sans-serif; ">The University of Sydney Dance</p>      </div>
      <div class="nav">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="About.html">About</a></li>
          <li><a href="Course.html">Course</a></li>
          <li><a href="Information.html"> Information</a></li>
          <li><a href="Address.html">Address</a></li>
          
        </ul>
      </div>
    </div>
  </div>
   <div class="banner"><img src="images/bj.png" alt="" height="149"></div>
<p>&nbsp;</p>
<p>&nbsp;</p>
<div class="main2">
<form onSubmit="return login()" action="index.html">
			<fieldset>
				<p class="big_title">Contact us</p>
				<ul class='ulist'>
					<li class="list">
						<span class="point">*</span>
						<span class="title">Email</span>
					  <input class="input1" type="text" id="mail" onBlur="check_mail_login()" required placeholder="example@mail.com">
						<span>@</span>
						<select class="option" id="option">
							<option value="wtu.edu">wtu.edu</option>
							<option value="163.com">163.com</option>
							<option value="qq.com">qq.com</option>
						</select>
						<span id="mailInfo"></span>
					</li>
					
					<li class="list">
						<span class="point">*</span>
						<span class="title">massage</span>
						<input class="input2" type="password" id="password" onBlur="check_psw_login()" required placeholder="6~16位字符">
						<span id="pswInfo"></span>
					</li>
					
					<li class="list">
						<span class="point">*</span>
						<span class="title">user</span>
						<input class="input2" type="password" id="password" onBlur="check_psw_login()" required placeholder="6~16位字符">
						<span id="pswInfo"></span>
					</li>
					
					
				</ul>
			  <input class="login" type="submit" value="contact us">
			  <input class="res" type="reset" value="reset" />
			</fieldset>
		</form>
</div>
 <div class="footer">
    <div class="inner-1200">
     
    </div>
   <div class="copyright inner-1200">
      <p>The University of Sydney Dance</p>
   </div>
</div>
</body>

</html>
