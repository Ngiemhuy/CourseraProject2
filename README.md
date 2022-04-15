<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Responsive Layout</title>
<style>

/********** Base styles **********/
* {
  box-sizing: content-box;
}
h1 {
  margin-bottom: 15px;
}

p {
  font-family: Helvetica;
  color: white;
  margin-left:5px;
  width: 250px;
  height: 250px;

}

#p1 {width: 100%;background-color: #A52A2A;
  margin-top: 0%;
  margin-left: 0%;
  float: none;
  width: 70px;
  height: 20px;
  left: 196px; }
  #p2{ width: 100%;background-color: #a52a2a;
  margin-top: 0%;
  margin-left: 0%;
  float: none;
  width: 70px;
  height: 20px;
  left: 196px; }
  #p3{width: 100%;background-color: #A52A2A;
  margin-top: 0%;
  margin-left: 0%;
  float: none;
  width: 70px;
  height: 20px;
  left: 196px; }



/* Simple Responsive Framework. */
.row {
  width: 1500px;
  height: 250px;
}

/********** Large devices only **********/
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3 {
    float: left;
    border: 1px solid green;
    margin-left: 10px;
    margin-right: 20px;
    position: relative;
    margin-bottom: 10px;
  }
  .col-lg-1 {
    width: 8.33%; 

  }
  .col-lg-2 {
    width: 16.6%;
  }
  .col-lg-3 {
      width: 25%;
  }}


/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6,.col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12{
    float: left;
    border: 1px solid green;
    margin-left: 0px;
    margin-right: 20px;
    position: relative;
    margin-bottom: 10px;
  } 
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33%;
  }
  .col-md-5 {
    width: 42%;
  }
  .col-md-6 {
    width: 50%;}
  .col-md-7 {
    width: 58%;
  }
  .col-md-8 {
    width: 66%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-10 {
    width: 83%;
  }
  .col-md-11 {
    width: 91;
  }
  .col-md-12 {
    width: 100%;
  }
  
}
/********** Medium devices only **********/
@media  (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3,.col-sm-4, .col-sm-5, .col-sm-6,.col-sm-7, .col-sm-8, .col-sm-9,.col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
    border: 1px solid green;
    margin-left: 0px;
    margin-right: 20px;
    position: relative;
    margin-bottom: 10px;
  }
  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33%;
  }
  .col-sm-5 {
    width: 42%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58%;
  }
  .col-sm-8 {
    width: 66%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-10 {
    width: 83%;
  }
  .col-sm-11 {
    width: 91;
  }
  .col-sm-12 {
    width: 100%;
  }
  
}

</style>
</head>
<body>
<h1>menu</h1>

<div class="row ">
 <div id="container"><div class="col-lg-3 col-md-3 col-sm-4 "><p id="p1">chicken</p> zsnhdshjbdhjdhbfhfbhdbnsbndbsmmj
</div></div>
 <div id="container"><div class="col-lg-3 col-md-3 col-sm-4"><p id="p2">sheep</p>izsdnhshjbdhjdhbfhfhjdshgsfhsfgs
  hshshhshhhsjfgdsjfhsdgjfhjsjdsddjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjj</div></div>
  <div id="container"><div class="col-lg-3 col-md-6 col-sm-8"><p id="p3">Goat</p>zsnhshjbdhjdhbfhfbhdbnsbndbsmmj
    kkkkkkkkkkkkkkkkkkkkkkkkiiiuuuiiiiiii></div></div>
  
</div>

</body>
</html>
