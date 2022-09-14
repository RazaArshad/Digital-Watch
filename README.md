# Digital-Watch
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <title>World Time & Zone</title>
   
    <style> *{
      margin: 0px;
      padding: 0px;
  }
  #kk{
      text-align: center;
      margin: 4px;
  
  }</style>
   
  </head>
  <body>
    <nav class="navbar navbar-expand navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Digital Watch</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample02" aria-controls="navbarsExample02" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
  
        <div class="collapse navbar-collapse" id="navbarsExample02">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#Home">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.timeanddate.com/worldclock/" target="_blank">World Time!</a>
            </li>
          </ul>
          <form class="form-inline my-2 my-md-0">
            <input class="form-control" type="text" placeholder="Search">
          </form>
        </div>
      </nav>
      <div id="kk"><h1 style="text-align: center;">Welcome to My Digital Watch!</h1>
    <p>Here You will find out the world time shedule as well as Our Nation Time</p>
<h3 class="hk">Let! get started</h3>    
    </div >
    <div id="jumbotrone my-4"><div class="jumbotron" >
        <h1 class="display-4" class="text-center" >Current time Is:<span id="time"></span></h1>
        <p class="lead" >We have got you covered . <q>The two most powerful warriors are patience and time.</q> </p>
        <hr class="my-4">
        <p>We are here to show you the time for different countries.</p>
        <p class="lead">
          <a class="btn btn-primary btn-lg" href="#" role="button">Browse Times</a>
        </p>
      </div></div>
      
     <!-- <script src="project.js"></script> -->
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  
    <script>// myDate = new Date();



      // myDate.getHours() + " " + myDate.getMinutes() + " " + myDate.getSeconds();
      
      let a;
      let date;
      let time;
      setInterval(() => {
          a = new Date();
          date = a.toLocaleDateString();
          time =    a.getHours() + ":" + a.getMinutes() + ":" + a.getSeconds();
          document.getElementById('time').innerHTML = time + " on  " + date;
      }, 1000);</script>
  
  
  </body>
</html> 
