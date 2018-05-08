<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js" integrity="sha384-cs/chFZiN24E4KMATLdqdvsezGxaGsi4hLGOzlXwp5UZB1LY//20VyM2taTB4QvJ" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>

<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">


<link rel="stylesheet" type="text/css" href="css/main.css">


<script type="text/javascript">
  $('.carousel').carousel({
    interval: 800
  });

  function prevCard() {
    $('.carousel').carousel('prev');
  }

  function nextCard() {
    $('.carousel').carousel('next');
  }

</script>

Home
--------------

In an effort to mitigate confirmation bias, we (<a href="https://amitshankar97.github.io" target="_blank">Amit Shankar</a> and <a href="https://itechnoguy.com" target="_blank">Issac Kim</a>) built Real News. Real News is an app that gathers headlines across various top sources and presents them through an intuitive dialog.

You can get news about specific topics or even by categories such as health, business and sports. It is also possible to get news by specific sources. If you ask to hear about an article in greater detail, Real News can optionally send you a link to the article in an email digest once you exit the app.

This is an open-source project, powered by [NewsAPI.org](https://newsapi.org).
<hr />


### Alexa

<a href="https://www.amazon.com/dp/B07CKSZR3N/?ref-suffix=ss_copy" target="_blank">Click here to view the skill on Amazon.com</a>

##### To invoke the Alexa skill, you can say
> Alexa, launch real news

<br />
Once in the skill, you can say,

<div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">

    <div class="col-sm-2">
      
    </div>

    <div class="carousel-item active">
      <div class="card d-block w-80">
        <div class="card-body">
          <blockquote class="blockquote">
            <p>Give me the headlines</p>
          </blockquote>
          <p class="lead">to get the headlines</p>
        </div>
      </div>
    </div>


    <div class="carousel-item">
      <div class="card d-block w-80">
        <div class="card-body">
          <blockquote class="blockquote">
            <p>Give me news about <span class="text-primary">Bitcoin</span></p>
          </blockquote>

          <p class="lead">to get the news about a <span class="text-primary">topic</span></p>
        </div>
      </div>
    </div>


    <div class="carousel-item">
      <div class="card d-block w-80">
        <div class="card-body">
          <blockquote class="blockquote">
            <p>Give me news from <span class="text-primary">CNN</span></p>
          </blockquote>

          <p class="lead">to get the headlines from a <span class="text-primary">source</span></p>
        </div>
      </div>
    </div>



    <div class="carousel-item">
      <div class="card d-block w-80">
        <div class="card-body">
          <blockquote class="blockquote">
            <p>Give me <span class="text-primary">technology</span> news</p>
          </blockquote>

          <p class="lead">to get news by <span class="text-primary">category</span></p>
        </div>
      </div>
    </div>



    <div class="carousel-item">
      <div class="card d-block w-80">
        <div class="card-body">
          <blockquote class="blockquote">
            <p>Alexa, <span class="text-primary">help</span></p>
          </blockquote>

          <p class="lead">to get a list of commands</p>
        </div>
      </div>
    </div>


    <a class="btn" onclick="prevCard()"  style="float: left;" role="button" data-slide="prev">
    <span class="fa fa-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="btn" onclick="nextCard()" role="button" style="float: right;" data-slide="next">
    <span class="fa fa-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>

  </div>
</div>

<div style="margin-top: 20px;">
<a href="/alexa.html" target="_blank">Click here for more</a>
</div>
<hr />


### Google Assistant

Coming soon...
<hr />


### Contact Us

<form action="https://formspree.io/realnewsapp@gmail.com"
      method="POST">

  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" class="form-control" id="name" placeholder="Name">
  </div>

  <div class="form-group">
    <label for="email_address">Email address:</label>
    <input type="email" class="form-control" id="email_address" name="_replyto" placeholder="Email">
  </div>

  <div class="form-group">
  	<label for="message">Message:</label>
  	<textarea class="form-control" rows="5" id="message" name="message" placeholder="Message"></textarea>
  </div>

  
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
