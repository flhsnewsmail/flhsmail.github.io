<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- PAGE settings -->
  <link rel="icon" href="https://templates.pingendo.com/assets/Pingendo_favicon.ico">
  <title>Flhs News Mail</title>
  <meta name="description" content="Wireframe design of a landing page by Pingendo">
  <meta name="keywords" content="Pingendo bootstrap example template wireframe landing">
  <meta name="author" content="Pingendo">
  <!-- CSS dependencies -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css">
  <link rel="stylesheet" href="wireframe.css">
</head>

<body class="">
  <nav class="navbar navbar-expand-md navbar-dark bg-danger h-25" style="">
    <div class="container">
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbar2SupportedContent" aria-controls="navbar2SupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span> </button>
      <div class="collapse navbar-collapse text-center justify-content-between" id="navbar2SupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item text-light">
            <a class="nav-link mx-2" href="https://flhsnews.com/">FLHS NEWS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-2" href="https://www.francislewishs.org/">FRANCIS LEWIS&nbsp;</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="h-50 d-flex align-items-center">
    <div class="container">
      <div class="row py-5" style="">
        <div class="mx-auto text-center col-md-6 h-100">
          <h3 class="display-4" >&nbsp;<br>THE <a style="background-color: rgb(0,0,0)" href="https://flhsnews.com/" class="text-light"> FLHS NEWS</a><br>MAILING LIST</h3>
          <p class="lead text-body h-100 w-100"><a style="background-color: rgb(200,200,200)" class="text-body">WHY JOIN THE MAILING LIST?</a><br>STAY CONNECTED WITH FLHS THROUGH NEWS DELIVERED STRAIGHT TO YOUR INBOX.&nbsp;<a style="background-color: rgb(200,200,200)" class="text-body"><br><br>HOW DOES IT WORK?</a><br>ENTER YOUR NAME AND YOUR EMAIL. EVERYTIME A NEW ARTICLE IS POSTED, WE'LL SEND YOU A NOTIFICATION.&nbsp;<br><br></p><a style="background-color: rgb(0,0,0)" href="https://flhsnews.com/" class="text-light">
          </a>
        </div><a style="background-color: rgb(0,0,0)" href="https://flhsnews.com/" class="text-light">
        </a>
      </div><a style="background-color: rgb(0,0,0)" href="https://flhsnews.com/" class="text-light">
      </a>
    </div><a style="background-color: rgb(0,0,0)" href="https://flhsnews.com/" class="text-light">
    </a>
  </div><a style="background-color: rgb(0,0,0)" class="text-light">
    <div class="text-center py-5">
      <div class="container">
        <div class="row bg-light">
          <div class="mx-auto p-4 col-lg-7">
            <h3 class="text-dark display-4">NEWS LETTER SUBSCRIPTION</h3>
            <form name="submit-to-google-sheet" id="myForm">
              <input name="name" type="text" placeholder="Name" id="name" required="">
              <input name="email" type="email" placeholder="Email" id="email" required="">
              <button type="submit">Send</button>
            </form>
            <script>
              const scriptURL = 'https://script.google.com/macros/s/AKfycbwnHq6ceOCyxDUyyWuTxXqzImCtfQBXvLgtXshg5rtLnfgoiNrS/exec'
              const form = document.forms['submit-to-google-sheet']
              form.addEventListener('submit', e => {
                e.preventDefault()
                fetch(scriptURL, {
                  method: 'POST',
                  body: new FormData(form)
                }).then(response => console.log('Submitted!', response)).catch(error => console.error('Error!', error.message))
                document.getElementById('name').value = '';
                document.getElementById('email').value = '';
                alert("Success!");
              })
            </script>
          </div>
        </div>
      </div>
    </div>
  </a>
  <div class="py-5 bg-danger" style=""><a style="background-color: rgb(0,0,0)">
    </a>
    <div class="container"><a style="background-color: rgb(0,0,0)">
      </a>
      <div class="row"><a style="background-color: rgb(0,0,0)">
        </a>
        <div class="p-4 col-lg-8"><a style="background-color: rgb(0,0,0)">
            <h4 class="mb-3 text-white">THE FRANCIS LEWIS JOURNALISM ACADEMY</h4>
          </a>
          <div class="blockquote text-muted"><a style="background-color: rgb(0,0,0)">
              <p class="mb-0 text-white">If you're interested in developing multimedia skills and telling stories, then this is the academy for you!</p>
              <p class="mb-0 text-white">The Journalism Academy is open to all students who want to produce and write the news, and learn how tell stories through various forms of media.</p>
              <p class="mb-0 text-white">Using cutting-edge technology, you will gain real world skills in print, audio and video production. In addition, you will learn how to conduct interviews, report from the field, and produce engaging articles, websites, videos, and radio pieces.</p>
            </a>
            <p class="mb-0 text-white"><a>Please visit</a> <a href="https://flhsnews.com/" class="text-light">FLHS NEWS</a> to see our work!</p>
          </div>
        </div>
        <div class="col-md-4 align-self-center">
          <img class="img-fluid d-block" src="https://upload.wikimedia.org/wikipedia/en/b/b9/Flhslogo.jpg" style="	box-shadow: 0px 0px 4px  black, 0px 0px 4px  black;"> </div>
      </div>
    </div>
  </div>
  <div class="py-5">
    <div class="container">
      <div class="row mb-3">
        <div class="text-center mx-auto p-4 col-lg-6 col-md-10 bg-danger">
          <h4 class="text-white">WANT TO JOIN THE JOURNALISM ACADEMY?</h4>
          <h5 class="text-light">If you have any questions about the academy, please talk to: </h5>
          <p class="text-light">Mr. Coloneri | Journalism Adviser &amp; Teacher | ancolo@flhs.us</p>
          <p class="text-light">Ms. Linge | Journalism Adviser &amp; Teacher | jlinge@flhs.us </p>
          <p class="text-light">Ms. Huggins | AP English | cahugg@flhs.us </p>
        </div>
      </div>
      <div class="row">
        <div class="p-4 col-lg-4 bg-danger">
          <h4 class="mb-3">SKILLS LEARNED INCLUDE:</h4>
          <ul class="">
            <li class="my-1">Shooting with professional video and still cameras</li>
            <li class="my-1">Editing video and sound with Adobe Premiere Pro</li>
            <li class="my-1">Producing podcasts</li>
          </ul>
        </div>
        <div class="p-md-4 col-lg-8 text-warning">
          <h4 class="mb-3"><br></h4>
          <div class="carousel slide" data-ride="carousel">
            <div class="carousel-inner bg-light" role="listbox">
              <div class="carousel-item p-5 active text-danger">
                <div class="blockquote text-muted mb-0 px-2">
                  <p class="mb-0">What I like about this academy is that, you can choose to write about whatever you want. The students and teachers are very nice and fun to interact with, everyone gets along with each other. The teachers give good feedback and their lessons are made easy to understand. </p>
                  <div class="blockquote-footer">ELIANNY HEZHENG</div>
                </div>
              </div>
              <div class="carousel-item p-5">
                <div class="blockquote text-muted mb-0 px-">
                  <p class="mb-0">I like that we are basically one big family and we encourage and help each other on whatever we are working on on the moment, and you can write about topics you care about</p>
                  <div class="blockquote-footer">CRISTOPHER GARCIA</div>
                </div>
              </div>
              <div class="carousel-item p-5">
                <div class="blockquote text-muted mb-0 px-">
                  <p class="mb-0">The academy is so fun, and open to anything that we want to talk about.</p>
                  <div class="blockquote-footer">JADE CORA</div>
                </div>
              </div>
            </div> &gt; <span class="carousel-control-next-icon" aria-hidden="true"></span> <span class="sr-only">Next</span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="bg-dark py-3">
    <div class="container"></div>
  </div>

</body>

</html>
