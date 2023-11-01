# FrontEndMentor
results challenge
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Results</title>
    <link rel="stylesheet" href="./index.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@500&display=swap"
      rel="stylesheet"
    />
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
  </head>
<body>
    <div class="container">
    <div class="box1">
      <h3 class="title">Your Result</h3>
      <div class="circle">
        <h1 style="font-size: 45px">76</h1>
        <p style="opacity: .5;">of 100</p>
      </div>
      <div class="content">
        <h3 style="padding-bottom: 10px;">Great</h3>
        <p style="opacity: 0.75;">
          You scored higher than 65% of the people who have taken these tests.
        </p>
      </div>
    </div>
    <div class="box2">
        <h3 style="padding-bottom: 10px;">Summary</h3>
        <div class="grid">
            <div class="col" id="one">
                <i class='bx bxs-zap'></i>
                <p>Reaction</p>
                <p style="color: black;padding-left: 60px;">80<span style="opacity: .5;">/100</span></p>
            </div>
            <div class="col"  id="two">
                <i class='bx bx-brain' ></i>
                <p>Memory</p>
                <p style="color: black;padding-left: 62px;">92<span style="opacity: .5;">/100</span></p>
            </div>
            <div class="col"id="three" >
                <i class='bx bx-message-square-minus'></i>
                <p>Verbal</p>
                <p style="color: black;padding-left: 74px;">61<span style="opacity: .5;">/100</span></p>
            </div>
            <div class="col" id="four">
                <i class='bx bx-show-alt' ></i>
                <p>Visual</p>
                <p style="color: black;padding-left: 74px;">72<span style="opacity: .5;">/100</span></p>
            </div>
            <button  class="continue" type="submit">Continue</button>
        </div>
    </div>
    </div>
  </body>
