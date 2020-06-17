# AP-LabFile
# 1. Creating HTML Web Page Forms
Code is :
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
OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/1.%20HTML%20form/OP1.png)

# 2. Creating Home Page using HTML
Code is:
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
OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/2.%20HTML%20webPage/OP2.png)
# 3. Creating XHTML and CSS WebPage
Code is:
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
OUTPUT:
![](https://github.com/mnigam504/AP-LabFile/blob/master/3.%20XHTML%20and%20CSS/op.png)
# 4. Setting Up and Configure Apcahe Tomcat
# 5. Undersatanding Modification Of Web.XML
# 6. Creating website using PHP
# 7. Uderstanding JavaScript
Code is:
- index.html
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
- app.js
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
# 8. WebPage using JavaScript and PHP

