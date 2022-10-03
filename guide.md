Create a card container with two divs
The first div with class card-top
The second div with class card-bottom
Another two divs inside card-bottom
The two divs should have classes named
card-bottom-left and card-bottom-right

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Pricing Card</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="card">
      <div class="card-top">
        <h2>Join Our Community</h2>
        <h4>30-day, hassle-free money back guarantee</h4>
        <p>
          Gain access to our full library of tutorials along with expert code
          reviews. Perfect for any developers who are serious about honing their
          skills
        </p>
      </div>
      <div class="card-bottom">
        <div class="card-bottom-left">
          <h4>Monthly Subscription</h4>
          <div>
            <div>$29</div>
            <div>per month</div>
          </div>
          <p>Full Access for less than $1 a day</p>
          <button>Sign Up</button>
        </div>
        <div class="card-bottom-right">
          <h4>Why Us</h4>
          <ul>
            <li>Tuutorials by industry expert</li>
            <li>Peer and expert code review</li>
            <li>Coding excercise</li>
            <li>Access to our Github repo</li>
            <li>Community forum</li>
            <li>Flashcard desks</li>
            <li>New videos every week</li>
          </ul>
        </div>
      </div>
    </div>
  </body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.card {
  width: 700px;
  height: 350px;
  border: 3px solid red;
}
.card-top {
  width: 100%;
  height: 40%;
  border: 2px solid green;
}
.card-bottom {
  width: 100%;
  height: 60%;
  border: 2px solid blue;
}
.card-bottom-left {
  display: inline-block;
  width: 50%;
  height: 100%;
  border: 2px solid orange;
}
.card-bottom-right {
  display: inline-block;
  width: 50%;
  height: 100%;
  border: 2px solid orangered;
}