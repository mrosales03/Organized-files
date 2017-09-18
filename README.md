<!DOCTYPE html>
<html>
<head>
    <title>Welcome to my survey</title>
    <style>
    body {
  background-color: #FFF;
  margin: 0;
  padding: 0px 60px;
}

.header {
  background-color: #466995;
  border-bottom: 1px solid #466995;
  overflow-y: auto;
  width: 100%;
  position: absolute;
  top: 0px;
  left: 0px;
  position: fixed;
  z-index: 1000;
}

ul {
  margin: 30px auto;
  text-align: center;
}

li {
  color: #FFF;
  display: inline-block;
  font-family: 'Oswald', sans-serif;
  font-size: 16px;
  text-align: left;
  font-weight: 300;
  text-transform: uppercase;
  padding: 0 40px;
}

li:hover {
  color: #DBE9EE;
}

h1 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 32px;
  font-weight: 300;
  text-transform: uppercase;
}

h2 {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 26px;
  font-weight: 100;
  margin: 0 auto 40px auto;
}

h3 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  text-align: center;
  font-weight: 700;
  text-transform: uppercase;
}

h4 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  font-weight: 300;
  letter-spacing: 2px;
  text-align: center;
  text-transform: uppercase;
}

p {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 18px;
}

.welcome {
    background-color: #DBE9EE;
    box-sizing: border-box;
    padding: 40px;
    position: fixed;
    left: 0;
    top: 80px;
    text-align: center;
    width: 100%;
    z-index: 999;
}

.question {
    margin: 120px auto;
    text-align: center;
    position: relative;
    top: 240px;
}

.answer {
    border: 1px solid #466995;
    display: inline-block;
    height: 100px;
    margin: 20px;
    padding-top: 40px;
    width: 220px;
}

.answer:hover {
    background: #C0D6DF;
    color: #FFF;
}
    </style>
</head>
    <body>
        
        <div class="header">
            <ul>
                <li>Question 1</li>
                <li>Question 2</li>
                <li>Question 3</li>
                <li>Question 4</li>
                <li>Question 5</li>
                <li>Question 6</li>
            </ul>
            </div>

            <div class="welcome">
                <h1>Welcome to my survey!</h1>
                <p>Hello, my name is Miguel. I created this survey using mark up languages like Html and Css.</p>
            </div>

            <div class="question">
                <h4>Question 1</h4>
                <h2>How many days a week do you use social media?</h2>

                <div class="answer">
                    <h3>1-2 Days</h3> 
                </div>

                <div class="answer">
                    <h3>2-5 Days</h3>
                </div>

                <div class="answer">
                    <h3>5-7 Days</h3>
                </div>
            </div>

            <div class="question">
                <h4>Question 2</h4>
                <h2>Which social media platform do you prefer?</h2>

                <div class="answer">
                    <h3>Facebook</h3>
                </div>

                <div class="answer">
                    <h3>Instagram</h3>
                </div>

                <div class="answer">
                    <h3>Twitter</h3>
                </div>
            </div>

            <div class="question">
                <h4>Question 3</h4>
                <h2>Do you consider social media to be addictive?</h2>

                <div class="answer">
                    <h3>Yes</h3>
                </div>

                <div class="answer">
                    <h3>No</h3>
                </div>

                <div class="answer">
                    <h3>Undecided</h3>
                </div>

            <div class="Question">
                 <h4>Question 4</h4>
                 <h2>Do you think Social media should disappear completely?</h2>

                 <div class="answer">
                     <h3>Yes</h3>
                 </div>

                 <div class="answer">
                     <h3>No</h3>
                 </div>

                 <div class="answer">
                     <h3>maybe</h3>
                 </div>
            </div>

            <div class="question">
                <h4>Question 5</h4>
                <h2>Are you addicted to social media?</h2>

                <div class="answer">
                    <h3>Yes</h3>
                </div>

                <div class="answer">
                    <h3>No</h3>
                </div>

                <div class="answer">
                    <h3>Absolutely</h3>
                </div>
            </div>

               <div class="question">
                    <h4>Question 6</h4>
                    <h2>Have you ever wondered how social media apps are create it?</h2>

                    <div class="answer">
                         <h3>Yes</h3>
                    </div>

                    <div class="answer">
                          <h3>No</h3>
                    </div> 

                    <div class="answer">
                          <h3>Not Interested</h3>
                    </div>
                </div>       
    </body>
</html>
