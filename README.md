<html lang="en">
<head>
    <meta charset="utf-8">
    <title>HomeTech Solutions</title>
    <meta name="description" content="HomeTech Solutions">
    <style>
        /* BASE */

        html { font-size:100%; }
        body { padding: 40px 0 20px; margin: 0; font: 13px/1.333 "lucida grande", tahoma, sans-serif; color: #333; background: #137DC5;}

        a, a:visited { color: #980905; }
        a:hover, a:focus, a:active { text-decoration: none; }

        h1 { margin: 0 0 0.5em; font-size: 28px;  font-weight: normal; }
        h2 { margin: 0 0 0.75em; font-size: 15px; }
        p { margin: 0 0 1.333em; }
        em { font-style: italic; }
        pre, code { font-family: monospace, sans-serif; font-size: 1em; color:#080; }
        pre { white-space: pre; white-space: pre-wrap; word-wrap: break-word; }
        th { font-weight: bold; }
        th, td { padding: 5px 25px 5px 5px; text-align: left; vertical-align: middle; }

        ul { list-style: square; margin: 1em 0 1em 0px; padding: 0; }

        /* TEMPLATE */

        .container { position:relative; overflow:hidden; max-width: 600px; _width: 600px; padding: 40px 60px; border: 1px solid #ccc; margin: 0 auto; background: #fff; }

        .container pre,
        .container .prettyprint { padding: 0; border: 0; margin: 0 0 20px; background: #fff; }

        .ribbon { position: absolute; top: -1px; right: -1px; opacity: 0.9; }
        .ribbon:hover, .ribbon:focus, .ribbon:active { opacity: 1; }
        .ribbon img { display: block; border: 0; }

        .header { padding-right: 80px; }
        .header p { font-size: 18px; color: #808080; }

        .section { margin: 40px 0 20px; }

        .example { padding: 20px; border: 1px solid #ccc; margin: 10px -20px 20px; }
        .example p { margin: 15px 0 0; }
        .example p:first-child { margin: 0; }

        .footer { margin: 20px 0 50px; font-size: 11px; color: #666; text-align: center; }
        .footer a { color: #666;}

        /* SMALL */

        @media (max-width: 500px) {
            body { padding: 0; }
            .container { padding: 20px 30px; }
            .footer { margin-bottom: 20px; }
        }
    </style>


</head>

<body onload="prettyPrint()">

<div class="container">

    <div class="header">
        <h1>HomeTech Solutions: Your Tech, Our Expertise</h1>
    </div>

    <div class="section">
        <h2>Who We Are</h2>
        <p>Are you tired of dealing with tech troubles at home? Look no further – we're here to assist you with a range of tech-related needs right at your doorstep! Whether you're looking to update your knowledge about your home PC or phone, need someone patient to walk you through issues, experiencing slow internet, or simply want help connecting a smart TV, we've got you covered. Call us or email us – we're your neighborhood geek squad, ready to simplify your tech world!</p>

        <div class="example">
            <pre class="prettyprint"><code>&lt;a class="btn-auth btn-[service]" href="#">
    Sign in with &lt;b>[service]&lt;/b>
&lt;/a></code></pre>
            <div>
                <img src="https://github.com/baldalbino/hometechomaha/blob/32eb0e9b409acbc9d9ab718633bb50cbc2023715/docs/1.png" alt="HomeTech logo" style="max-width: 100%;">
                <p><button class="btn-auth btn-twitter">Sign in with <b>Twitter</b></button></p>
                <p><a class="btn-auth btn-google" href="#button">Sign in with <b>Google</b></a></p>
                <p><button class="btn-auth btn-github">Sign in with <b>GitHub</b></button></p>
                <p><a class="btn-auth btn-yahoo" href="#button">Sign in with <b>Yahoo!</b></a></p>
                <p><a class="btn-auth btn-windows" href="#button">Sign in with <b>Windows Live ID</b></a></p>
                <p><a class="btn-auth btn-openid" href="#button">Sign in with <b>OpenID</b></a></p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Larger buttons</h2>
        <p>To create larger buttons include an additional class of <code>large</code>.</p>

        <div class="example">
            <pre class="prettyprint"><code>&lt;a class="btn-auth btn-[service] large" href="#">
    Sign in with &lt;b>[service]&lt;/b>
&lt;/a></code></pre>
            <div>
                <p><a class="btn-auth btn-facebook large" href="#button">Sign in with <b>Facebook</b></a></p>
                <p><a class="btn-auth btn-twitter large" href="#button">Sign in with <b>Twitter</b></a></p>
                <p><a class="btn-auth btn-google large" href="#button">Sign in with <b>Google</b></a></p>
                <p><a class="btn-auth btn-github large" href="#button">Sign in with <b>GitHub</b></a></p>
                <p><a class="btn-auth btn-yahoo large" href="#button">Sign in with <b>Yahoo!</b></a></p>
                <p><a class="btn-auth btn-windows large" href="#button">Sign in with <b>Windows Live ID</b></a></p>
                <p><a class="btn-auth btn-openid large" href="#button">Sign in with <b>OpenID</b></a></p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Supported services</h2>
        <ul>
            <li>Facebook
            <li>GitHub
            <li>Google
            <li>OpenID
            <li>Twitter
            <li>Windows Live ID
            <li>Yahoo!
        </ul>
    </div>

    <div class="section">
        <h2>Source code</h2>
        <p>Available on GitHub: <a href="http://github.com/necolas/css3-social-signin-buttons">necolas/css3-social-signin-buttons</a></p>
        <p>Download it in either <a href="http://github.com/necolas/css3-social-signin-buttons/zipball/master">zip</a> or <a href="http://github.com/necolas/css3-social-signin-buttons/tarball/master">tar</a> formats.</p>
        <p>Clone the project with Git by running:<br>
        <code>$ git clone git://github.com/necolas/css3-social-signin-buttons.git</code></p>
    </div>

    <div class="section">
        <h2>Browser compatibility</h2>
        <p>Full support: Google Chrome, Firefox 3.5+, Safari 4+, IE 10+, Opera 11.10+.</p>
        <p><strong>Note:</strong> Some CSS3 enhancements are not supported in older versions of Opera and IE. The use of icons is not supported in IE 6 or IE 7.</p>
    </div>

    <div class="section">
    </div>
</div>

<div class="footer">
</div>

</body>
</html>
