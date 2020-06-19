# AP-LabFile
# 1. Creating HTML Web Page Forms
 ## Code is :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>HTML FORM</title>
</head>
<body>
  <form action="process.php">
    <!-- Text -->
    <div>
      <label for="name">Name</label><br>
      <input type="text" id="name" name="name" value="ABC XYZ">
    </div>
    <!-- Email -->
    <div>
      <label for="email">Email</label><br>
      <input type="email" name="email" id="email" placeholder="Enter an email">
    </div>
    <!-- Textarea -->
    <div>
      <label for="message">Message</label><br>
      <textarea name="message" id="message" cols="50" rows="5"></textarea>
    </div>
    <!-- Select -->
    <div>
      <label for="sex">Sex</label>
      <select name="sex" id="sex">
        <option value="male">Male</option>
        <option value="female" selected>Female</option>
        <option value="other">Other</option>
      </select>
    </div>
    <!-- Number -->
    <div>
      <label for="age">Age</label><br>
      <input type="number" name="age" id="age">
    </div>
    <!-- Date -->
    <div>
      <label for="bithdate">Birthdate</label><br>
      <input type="date" name="birthdate" id="birthdate">
    </div>
    <!-- Radio -->
    <div>
      <label for="membership">Membership</label>
      <input type="radio" name="membership" value="simple" id="membership"> Simple
      <input type="radio" name="membership" value="standard" id="membership" checked> Standard
      <input type="radio" name="membership" value="super" id="membership"> Super
    </div>
    <!-- Checkbox -->
    <div>
      <label for="membership">I Like..</label>
      <input type="checkbox" name="likes" value="bike" id="likes"> Bike
      <input type="checkbox" name="likes" value="car" id="likes"> Car
      <input type="checkbox" name="likes" value="boat" id="likes"> Boat
    </div>
    <!-- Input submit -->
    <input type="submit" value="Submit">
    <!-- Button submit -->
    <!-- <button type="submit">Submit</button> -->
    <button type="reset">Reset</button>
  </form>
</body>
</html>
```
## OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/1.%20HTML%20form/OP1.png)

# 2. Creating Home Page using HTML
 ## Code is:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>HTML5 HomePage</title>
  </head>
  <body>
    <!-- Header -->
    <header id="header" class="card">
      <h1>My Website</h1>
      <p>Just Another Website</p>
    </header>

    <!-- Main Content (left) -->
    <main id="main">
      <!-- Welcome Section -->
      <section id="welcome" class="card">
        <h2>Welcome To Our Website</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat
          cupiditate itaque possimus numquam corporis odit deserunt voluptas
          repellat ad ex earum magnam mollitia magni eaque nisi, excepturi nam
          temporibus! Sed. <br />
          <a href="#" class="text-center">Click For More</a>
        </p>
      </section>
      <!-- Blog Section -->
      <section id="blog">
        <h2>From Our Blog</h2>
        <!-- Article One -->
        <article class="article">
          <h3>Article One</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
            veniam adipisci necessitatibus quia quisquam? Eligendi vitae quia
            totam accusantium officiis!
          </p>
        </article>
        <!-- Article Two -->
        <article class="article">
          <h3>Article Two</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
            veniam adipisci necessitatibus quia quisquam? Eligendi vitae quia
            totam accusantium officiis!
          </p>
        </article>
      </section>
    </main>

    <!-- Sidebar (right) -->
    <aside id="sidebar" class="card">
      <h3>Navigation</h3>
      <!-- Navigation -->
      <nav>
        <ul id="main-nav">
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <hr />
      <h3>Contact Us</h3>
      <ul>
        <li><strong>Address:</strong> Himalaya</li>
        <li><strong>Phone:</strong> 123456789</li>
        <li><strong>Email:</strong> yes@bas.com</li>
      </ul>
    </aside>

    <div class="clr"></div>

    <!-- Footer -->
    <footer id="footer">
      <p class="text-center">Copyright &copy; My Website 2019</p>
    </footer>
  </body>
</html>
```
## OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/2.%20HTML%20webPage/OP2.png)
# 3. Creating XHTML and CSS WebPage
 ## Code is:
```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
  <head>
    <title>Form Styling</title>
    <link
      href="https://fonts.googleapis.com/css?family=Raleway"
      rel="stylesheet"
    />
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
      }

      body {
        font-family: 'Raleway', sans-serif;
        background: #344a72;
        color: rgb(195, 0, 255);
        line-height: 1.8;
      }

      a {
        text-decoration: none;
      }

      #container {
        margin: auto;
        max-width: 400px;
        padding: 20px;
      }

      .form-wrap {
        background: white;
        padding: 15px 25px;
        color: #333;
      }

      .form-wrap h1,
      .form-wrap p {
        text-align: center;
      }

      .form-wrap .form-group {
        margin-top: 15px;
      }

      .form-wrap .form-group label {
        display: block;
        color: #666;
      }

      .form-wrap .form-group input {
        width: 100%;
        padding: 10px;
        border: #ddd 1px solid;
        border-radius: 5px;
      }

      .form-wrap button {
        display: block;
        width: 100%;
        padding: 10px;
        margin-top: 20px;
        background-attachment: #123f34;
        color: rgb(49, 8, 77);
        cursor: pointer;
      }

      .form-wrap button:hover {
        background: #b5d4d2;
      }

      .form-wrap .bottom-text {
        font-size: 13px;
        margin-top: 20px;
      }

      footer {
        text-align: center;
        margin-top: 10px;
      }

      footer a {
        color: #49c1a2;
      }
    </style>
  </head>
  <body>
    <div id="container">
      <div class="form-wrap">
        <h1>Sign Up</h1>
        <p>It's free and only takes a minute</p>
        <form>
          <div class="form-group">
            <label for="first-name">First Name</label>
            <input type="text" name="firstName" id="first-name" />
          </div>
          <div class="form-group">
            <label for="last-name">Last Name</label>
            <input type="text" name="lastName" id="last-name" />
          </div>
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" name="email" id="email" />
          </div>
          <div class="form-group">
            <label for="password">Password</label>
            <input type="password" name="password" id="password" />
          </div>
          <div class="form-group">
            <label for="password2">Confirm Password</label>
            <input type="password" name="pasword2" id="password2" />
          </div>
          <button type="submit" class="btn">Sign Up</button>
          <p class="bottom-text">
            By clicking the Sign Up button, you agree to our
            <a href="#">Terms and Conditions</a> and
            <a href="#">Privacy Policy</a>
          </p>
        </form>
      </div>
      <footer>
        <p>Already have an account? <a href="#">Login Here</a></p>
      </footer>
    </div>
  </body>
</html>
```
## OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/3.%20XHTML%20and%20CSS/op.png)
# 4. Setting Up and Configure Apcahe Tomcat
- Downloading Tomcat Server
 1. Download the apache-tomcat 9.0.36 zip for required windows 32-bits or 64-bits zip file.( https://tomcat.apache.org/download-90.cgi)
 2. Unzip the file in c:// for ease of use.
 - Check for the following in tomcat folder:
   1. bin
   2. logs
   3. webapps
   4. work
   5. temp
   6. conf
   7. lib
 3. Install the java jdk and jre packages according to the system configuration.
 4. Create environment variable JAVA_HOME and provide variable path the java jdk (path).
 5. Create environment variable JRE_HOME and provide variable path the java jre (path).
 6. Check if the environment variable is set in command prompt:
  - set JAVA_HOME will return the variable path
  - set JRE_HOME will return the variable path if set.
 ![](https://github.com/mnigam504/AP-LabFile/blob/master/4.%20Setup%20and%20Config%20Apache%20TOMCAT/1.PNG)
 - Configuring Apache tomcat:
  1. Open the conf folder in tomcat directory.
  2. "conf\web.xml"; Enabling a Directory Listing
  Open the configuration file "web.xml". We shall enable the directory listing by changing
  "listings" from "false" to "true" for the "default" servlet.
  <param-value>true</param-value> like:
  3. "conf\server.xml file"; set the TCP Port Number
  <Connector port="9999" protocol="HTTP/1.1" Like -> You can set the port between 1024 and
  655555.
  4. "conf\context.xml"; Enabling Automatic Reload
  In that we set reloadable="true" to the <Context> element to enable automatic reload after
  code changes.
  Add reloadable="true" as in the following:
  <Context reloadable="true"> ...... </Context> Like
  5. (Optional) "conf\tomcat-users.xml"
  It is used to manage Tomcat by adding the highlighted lines, inside the <tomcat-users>
  elements. In that we can add a password and username as an optional step.
  6. Your Apache Tomcat Server is now configured.
  ![](https://github.com/mnigam504/AP-LabFile/blob/master/4.%20Setup%20and%20Config%20Apache%20TOMCAT/2.PNG)
 - Start Server
  1. Launch in command prompt by changing the directory(cd) to tomcat bin folder where all executable files exist.
  cd C:\Users\HP\apache-tomcat-9.0.36-windows-x64\apache-tomcat-9.0.36\bin
  2. Now add command (startup.bat) opens the tomcat server in another command window.
  3. Check for the port in tomcat window is set to 9999.
  ![](https://github.com/mnigam504/AP-LabFile/blob/master/4.%20Setup%20and%20Config%20Apache%20TOMCAT/3.PNG)
- Access the Server:
  1. Open a browser then enter the URL "http://localhost:9999" to access the Tomcat server's welcome page.
  2. Now try the URL http://localhost:9999/examples to view JSP and servlet examples.
  3. To shutdown the server use shutdown.bat in command prompt or simply apply ctrl+c in tomcat window.
  ![](https://github.com/mnigam504/AP-LabFile/blob/master/4.%20Setup%20and%20Config%20Apache%20TOMCAT/4.PNG)
  
# 5. Undersatanding Modification Of Web.XML
 ## 1. What is the Default Servlet ?
  The default servlet is the servlet which serves static resources as well as serves the directory listings (if directory listings are     enabled). It is declared globally in $CATALINA_BASE/conf/web.xml.
 ## 2. What is Web XML?
  The web .xml file is the deployment descriptor for a Servlet-based Java web application (which most Java web apps are). Among other     things, it declares which Servlets exist and which URLs they handle. The part you cite defines a Servlet Filter. Servlet filters can     do all kinds of preprocessing on requests.
 ## 3. Why we use web .xml?
  Generally speaking, this is the configuration file of web applications in java. It instructs the servlet container (tomcat for ex.)     which classes to load, what parameters to set in the context, and how to intercept requests coming from browsers.
  There you specify:
  - what servlets (and filters) you want to use and what URLs you want to map them to
  - listeners - classes that are notified when some events happen (context starts, session created, etc)
  - configuration parameters (context-params)
  - error pages, welcome files
  - security constraints
  In servlet 3.0 many of the web.xml parts are optional. These configurations can be done via annotations (@WebServlet, @WebListener).
 ## 4. How to modify web.xml to enable https?
  ### To modify the web.xml file to enable HTTPS
  1. Open the web.xml file usually located in the $CATALINA_HOME/webapps/moab/WEB-INF/ directory.
  2. Add a <security-constraint> section to cause all pages to be hosted with HTTPS.
  ### Code:
  ```
  <web-app>
    ...
      <security-constraint>
       <web-resource-collection>
         <web-resource-name>Viewpoint Secure URLs</web-resource-name>
         <url-pattern>/*</url-pattern>
       </web-resource-collection>
       <user-data-constraint>
        <transport-guarantee>CONFIDENTIAL</transport-guarantee>
       </user-data-constraint>
      </security-constraint>
  </web-app>
  ```
| Property | Description |
| --- | --- |
| Debug | Debugging level. It is not very useful unless you are a tomcat developer. As of this writing, useful values are 0, 1, 11, 1000. |
| Listings | If no welcome file is present, can a directory listing be shown? value may be true or false [false] Welcome files are part of the servlet api. WARNING: Listings of directories containing many entries are expensive. Multiple requests for large directory listings can consume significant proportions of server resources. |
| Precompressed | If a precompressed version of a file exists (a file with .br or .gz appended to the file name located alongside the original file), Tomcat will serve the precompressed file if the user agent supports the matching content encoding (br or gzip) and this option is enabled. [false] The precompressed file with the with .br or .gz extension will be accessible if requested directly so if the original resource is protected with a security constraint, the precompressed versions must be similarly protected. It is also possible to configure the list of precompressed formats. The syntax is comma separated list of [content-encoding]=[file-extension] pairs. For example: br=.br,gzip=.gz,bzip2=.bz2. If multiple formats are specified, the client supports more than one and the client does not express a preference, the order of the list of formats will be treated as the server preference order and used to select the format returned. |
| ReadmeFile | If a directory listing is presented, a readme file may also be presented with the listing. This file is inserted as is so it may contain HTML. |
| GlobalXsltFile | If you wish to customize your directory listing, you can use an XSL transformation. This value is a relative file name (to either $CATALINA_BASE/conf/ or $CATALINA_HOME/conf/) which will be used for all directory listings. This can be overridden per context and/or per directory. See contextXsltFile and localXsltFile below. The format of the xml is shown below. |
| contextXsltFile | You may also customize your directory listing by context by configuring contextXsltFile. This must be a context relative path (e.g.: /path/to/context.xslt) to a file with a .xsl or .xslt extension. This overrides globalXsltFile. If this value is present but a file does not exist, then globalXsltFile will be used. If globalXsltFile does not exist, then the default directory listing will be shown. |
| LocalXsltFile | You may also customize your directory listing by directory by configuring localXsltFile. This must be a file in the directory where the listing will take place to with a .xsl or .xslt extension. This overrides globalXsltFile and contextXsltFile. If this value is present but a file does not exist, then contextXsltFile will be used. If contextXsltFile does not exist, then globalXsltFile will be used. If globalXsltFile does not exist, then the default directory listing will be shown. |
| Input | Input buffer size (in bytes) when reading resources to be served. [2048] |
| Output | Output buffer size (in bytes) when writing resources to be served. [2048] |
| Readonly | Is this context "read only", so HTTP commands like PUT and DELETE are rejected? [true] |
| FileEncoding | File encoding to be used when reading static resources. [platform default] |
| UseBomIfPResent | If a static file contains a byte order mark (BOM), should this be used to determine the file encoding in preference to fileEncoding. [true] |
| SendfileSize | If the connector used supports sendfile, this represents the minimal file size in KB for which sendfile will be used. Use a negative value to always disable sendfile. |
| UseAcceptRanges | If true, the Accept-Ranges header will be set when appropriate for the response.[true] |
| ShowServerInfo | Should server information be presented in the response sent to clients when directory listing is enabled. [true] |
| SortListings | Should the server sort the listings in a directory. [false] |
| sortDirectoriesFirst | Should the server list all directories before all files. [false] |
| AllowPartialPut | Should the server treat an HTTP PUT request with a Range header as a partial PUT? Note that RFC 7233 clarified that Range headers are only valid for GET requests. [true] |
  
# 6. Creating website using PHP
 ## Code is:
 - ### formphp.html
 ```
 <!DOCTYPE html>
 <html lang="en" dir="ltr">
   <head>
     <meta charset="utf-8">
     <title></title>
   </head>
   <body>
     <h2>Registration Form</h2>

             <form action="formphp.php" method="POST">

                    First name:
                    <input type="text" name="firstname">

                     <br> Last name:
                     <input type="text" name="lastname">

                     <br> Agree to Terms of Service:
                     <input type="checkbox" name="agree">
                     <br>

                     <input type="hidden" name="form_submitted" value="1" />
                     
                     <input type="submit" value="Submit" >

              </form>
   </body>
 </html>
 ```
 - ### formphp.php
 ```
   
<?php
if(isset($_POST["form_submitted"]))
{
		if(!isset($_POST["agree"]))
		echo "You haven't agreed to the terms and services";
		else
		echo "Thank You !<br>".$_POST["firstname"]." ".$_POST["firstname"]." you have been successfully registered";
}
 ?>
 ```
 - ### registration.php
 ```
 <?php
  require_once "db.php";
    if (isset($_POST['signup'])) {
        $name = mysqli_real_escape_string($conn, $_POST['name']);
        $email = mysqli_real_escape_string($conn, $_POST['email']);
        $mobile = mysqli_real_escape_string($conn, $_POST['mobile']);
        $password = mysqli_real_escape_string($conn, $_POST['password']);
        $cpassword = mysqli_real_escape_string($conn, $_POST['cpassword']);
        if (!preg_match("/^[a-zA-Z ]+$/",$name)) {
            $name_error = "Name must contain only alphabets and space";
        }
        if(!filter_var($email,FILTER_VALIDATE_EMAIL)) {
            $email_error = "Please Enter Valid Email ID";
        }
        if(strlen($password) < 6) {
            $password_error = "Password must be minimum of 6 characters";
        }
        if(strlen($mobile) < 10) {
            $mobile_error = "Mobile number must be minimum of 10 characters";
        }
        if($password != $cpassword) {
            $cpassword_error = "Password and Confirm Password doesn't match";
        }
        if (!$error) {
            if(mysqli_query($conn, "INSERT INTO users(name, email, mobile ,password) VALUES('" . $name . "', '" . $email . "', '" . $mobile . "', '" . md5($password) . "')")) {
             header("location: registration.php");
             exit();
            } else {
               echo "Error: " . $sql . "" . mysqli_error($conn);
            }
        }
        mysqli_close($conn);
    }
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simple Registration Form in PHP with Validation | Tutsmake.com</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-lg-8 col-offset-2">
                <div class="page-header">
                    <h2>Registration Form in PHP with Validation</h2>
                </div>
                <p>Please fill all fields in the form</p>
                <form action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]); ?>" method="post">

                    <div class="form-group">
                        <label>Name</label>
                        <input type="text" name="name" class="form-control" value="" maxlength="50" required="">
                        <span class="text-danger"><?php if (isset($name_error)) echo $name_error; ?></span>
                    </div>

                    <div class="form-group ">
                        <label>Email</label>
                        <input type="email" name="email" class="form-control" value="" maxlength="30" required="">
                        <span class="text-danger"><?php if (isset($email_error)) echo $email_error; ?></span>
                    </div>

                    <div class="form-group">
                        <label>Mobile</label>
                        <input type="text" name="mobile" class="form-control" value="" maxlength="12" required="">
                        <span class="text-danger"><?php if (isset($mobile_error)) echo $mobile_error; ?></span>
                    </div>

                    <div class="form-group">
                        <label>Password</label>
                        <input type="password" name="password" class="form-control" value="" maxlength="8" required="">
                        <span class="text-danger"><?php if (isset($password_error)) echo $password_error; ?></span>
                    </div>

                    <div class="form-group">
                        <label>Confirm Password</label>
                        <input type="password" name="cpassword" class="form-control" value="" maxlength="8" required="">
                        <span class="text-danger"><?php if (isset($cpassword_error)) echo $cpassword_error; ?></span>
                    </div>

                    <input type="submit" class="btn btn-primary" name="signup" value="submit">
                    Already have a account?<a href="login.php" class="btn btn-default">Login</a>
                </form>
            </div>
        </div>
    </div>
</body>
</html>
 ```
 - ### db.php
 ```
 <?php
    $conn=mysqli_connect("localhost","yash","yash","registration");
      if(!$conn){
          die('Could not Connect MySql Server:' .mysql_error());
        }
?>
 ```
 ## OUTPUT :
 ![](https://github.com/mnigam504/AP-LabFile/blob/master/6.%20PHP%20Website/OP1.jpeg)
 ![](https://github.com/mnigam504/AP-LabFile/blob/master/6.%20PHP%20Website/OP2.jpeg)
# 7. Uderstanding JavaScript
 ## Code is:
- ### index.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Hello, world!</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
    <style>
      #loading, #results {
        display:none;
      }
    </style>
  </head>
  <body class="bg-dark">
    <div class="container">
      <div class="row">
        <div class="col-md-6 mx-auto">
          <div class="card card-body text-center mt-5">
            <h1 class="heading display-5 pb-3">Loan Calculator</h1>
            <form id="loan-form">
              <div class="form-group">
                <div class="input-group">
                  <span class="input-group-addon">$</span>
                  <input type="number" class="form-control" id="amount" placeholder="Loan Amount">
                </div>
              </div>
              <div class="form-group">
                <div class="input-group">
                  <span class="input-group-addon">%</span>
                  <input type="number" class="form-control" id="interest" placeholder="Interest">
                </div>
              </div>
              <div class="form-group">
                <input type="number" class="form-control" id="years" placeholder="Years To Repay">
              </div>
              <div class="forn-group">
                <input type="submit" value="Calculate" class="btn btn-dark btn-block">
              </div>
            </form>
            <!-- LOADER -->
            <div id="loading">
              <img src="img/loading.gif" alt="">
            </div>
            <!-- RESULTS -->
            <div id="results" class="pt-4">
              <h5>Results</h5>
              <div class="form-group">
                <div class="input-group">
                  <span class="input-group-addon">Monthly Payment</span>
                  <input type="number" class="form-control" id="monthly-payment" disabled>
                </div>
              </div>

              <div class="form-group">
                <div class="input-group">
                  <span class="input-group-addon">Total Payment</span>
                  <input type="number" class="form-control" id="total-payment" disabled>
                </div>
              </div>

              <div class="form-group">
                <div class="input-group">
                  <span class="input-group-addon">Total Interest</span>
                  <input type="number" class="form-control" id="total-interest" disabled>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
    <script src="app.js"></script>
  </body>
</html>
```
- ### app.js
```
// Listen for submit
document.getElementById('loan-form').addEventListener('submit', function(e){
  // Hide results
  document.getElementById('results').style.display = 'none';
  
  // Show loader
  document.getElementById('loading').style.display = 'block';

  setTimeout(calculateResults, 2000);

  e.preventDefault();
});

// Calculate Results
function calculateResults(){
  console.log('Calculating...');
  // UI Vars
  const amount = document.getElementById('amount');
  const interest = document.getElementById('interest');
  const years = document.getElementById('years');
  const monthlyPayment = document.getElementById('monthly-payment');
  const totalPayment = document.getElementById('total-payment');
  const totalInterest = document.getElementById('total-interest');

  const principal = parseFloat(amount.value);
  const calculatedInterest = parseFloat(interest.value) / 100 / 12;
  const calculatedPayments = parseFloat(years.value) * 12;

  // Compute monthly payment
  const x = Math.pow(1 + calculatedInterest, calculatedPayments);
  const monthly = (principal*x*calculatedInterest)/(x-1);

  if(isFinite(monthly)) {
    monthlyPayment.value = monthly.toFixed(2);
    totalPayment.value = (monthly * calculatedPayments).toFixed(2);
    totalInterest.value = ((monthly * calculatedPayments)-principal).toFixed(2);

    // Show results
    document.getElementById('results').style.display = 'block';

    // Hide loader
    document.getElementById('loading').style.display = 'none';

  } else {
    showError('Please check your numbers');
  }
}

// Show Error
function showError(error){
  // Hide results
  document.getElementById('results').style.display = 'none';
  
  // Hide loader
  document.getElementById('loading').style.display = 'none';

  // Create a div
  const errorDiv = document.createElement('div');

  // Get elements
  const card = document.querySelector('.card');
  const heading = document.querySelector('.heading');

  // Add class
  errorDiv.className = 'alert alert-danger';

  // Create text node and append to div
  errorDiv.appendChild(document.createTextNode(error));

  // Insert error above heading
  card.insertBefore(errorDiv, heading);

  // Clear error after 3 seconds
  setTimeout(clearError, 3000);
}

// Clear error
function clearError(){
  document.querySelector('.alert').remove();
}
```
## Output:
![](https://github.com/mnigam504/AP-LabFile/blob/master/7.%20Understanding%20JavaScript/OP1.png)
![](https://github.com/mnigam504/AP-LabFile/blob/master/7.%20Understanding%20JavaScript/OP2.png)
# 8. WebPage using JavaScript and PHP
 ## Code:
  ### index.html
  ```
  <!doctype html>
<html lang="en">
  <head>
    <title>Hello, world!</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-md-6 mx-auto">
          <h1>User Form</h1>
          <form name="myform" action="welcome.php" onsubmit="return validate()" method="POST">
            <div class="form-group">
              <label>Name</label>
              <input type="text" class="form-control" id="name" placeholder="Name" name="name">
              <div class="invalid-feedback">
                Name must be between 2 and 10 characters
              </div>
            </div>
            <div class="form-group">
              <label>Zipcode</label>
              <input type="text" class="form-control" id="zip" placeholder="Zipcode" name="zipcode">
              <div class="invalid-feedback">
                Enter a valid zipcode
              </div>
            </div>
            <div class="form-group">
              <label>Email</label>
              <input type="text" class="form-control" id="email" placeholder="Email" name="email">
              <div class="invalid-feedback">
                Enter a valid email
              </div>
            </div>
            <div class="form-group">
              <label>Phone Number</label>
              <input type="text" class="form-control" id="phone" placeholder="Phone Number" name="phoneNumber">
              <div class="invalid-feedback">
               Enter a valid phone
              </div>
            </div>
            <input type="submit" value="Submit" class="btn btn-primary btn-block">
          </form>
        </div>
      </div>
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
    <script src="app.js"></script>
  </body>
</html>
  ```
  ### app.js
  ```
  // Form Blur Event Listeners
document.getElementById('name').addEventListener('blur', validateName);
document.getElementById('zip').addEventListener('blur', validateZip);
document.getElementById('email').addEventListener('blur', validateEmail);
document.getElementById('phone').addEventListener('blur', validatePhone);

function validateName() {
  const name = document.getElementById('name');
  const re = /^[a-zA-Z]{2,10}$/;

  if(!re.test(name.value)){
    name.classList.add('is-invalid');
  } else {
    name.classList.remove('is-invalid');
  }
}

function validateZip() {
  const zip = document.getElementById('zip');
  const re = /^[0-9]{5}(-[0-9]{4})?$/;

  if(!re.test(zip.value)){
    zip.classList.add('is-invalid');
  } else {
    zip.classList.remove('is-invalid');
  }
}

function validateEmail() {
  const email = document.getElementById('email');
  const re = /^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$/;

  if(!re.test(email.value)){
    email.classList.add('is-invalid');
  } else {
    email.classList.remove('is-invalid');
  }
}

function validatePhone() {
  const phone = document.getElementById('phone');
  const re = /^\(?\d{3}\)?[-. ]?\d{3}[-. ]?\d{4}$/;

  if(!re.test(phone.value)){
    phone.classList.add('is-invalid');
  } else {
    phone.classList.remove('is-invalid');
  }
}
```
  ### welcome.php
  ```
  <h1>Welcome</h1>
Name : <?php echo $_POST["name"]; ?><br>
ZipCode : <?php echo $_POST["zicode"]; ?><br>
Email : <?php echo $_POST["email"]; ?><br>
Mobile : <?php echo $_POST["phoneNumber"]; ?><br>
  ```
![](https://github.com/mnigam504/AP-LabFile/blob/master/8.%20Javascript%20and%20PHP/op1.png)
