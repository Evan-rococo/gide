<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head>
   <header> <yo /></header>
 
<div class="row">
  <div class="column">
    <div class="app">

      <g-image src="https://res.cloudinary.com/winenot/image/upload/v1604715482/IMG_1332_povddi.jpg"/>
      <h4>PATIENCE IS BITTER, BUT IT'S FRUIT IS REAL SWEET.</h4>

     </div>
  </div>
  <div class="column">
    <p>A frattura del pene o peniena, anche denominata sindrome del chiodo rotto, è un raro trauma del pene che consiste nell'improvvisa e dolorosa <br>rottura della tonaca albuginea dei corpi cavernosi, dovuta a un colpo violento verificatosi durante l'erezione. Traumi simili, se avvenuti a pene flaccido ad esempio durante l'attività sportiva o per l'utilizzo di armi da fuoco, non vengono invece definiti fratture, ma semplici traumi penieni.</p>
  </div>
</div>
 <iframe src="https://open.spotify.com/embed/playlist/7hh5ZtxuXTt1ar4XoFDLCN" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
</div>
</template>

<script>
import yo from '~/components/yo.vue'
export default {
  components: {
    yo
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */

.home-links a {
  margin-right: 1em;}


@media (min-width: 48em){
  img {
    width: 100%;
  }

  .column {
    width: 96%;
    background-color: none;
  }
   iframe {
    width: 70vw;
    height: 50vw;
    border-radius: 25px;
    margin-left:26vw;
    margin-bottom: 9em;
    box-shadow: 0px 0px 6vw 7px green;
  }


.app{
  margin-bottom: .67em;
  width: 100%;
  text-align: center;
  background-color: none;
}

.row {
  margin-top:2em;
  margin-left: 25vw;
}

h3{
  margin-top: .34em;
  font-size: 2.67vw;
  line-height: 1.125;
  font-style: normal;
  text-align: center;
}

}



@media (max-width: 48em){
  img {width: 90vw;}

  iframe {width: 90vw;
    height: 66vw;
    border-radius: 25px;
    margin-left:5vw;
    margin-bottom: 9em;
    box-shadow: 0px 0px 6vw 7px green;}

.app{display: grid;
    background-color: red;
    margin-bottom:0em;
    width: 90vw;}

  h4 {font-size: 3.75vw;
    margin: 0;}

  .row:after {
  content: "";
  display: table;
  clear: both;
}

  .row {background-color: none;
    top:0;
    width: 90vw;}

.left, .right{display: contents;}

h4 {
  font-size: 3.75vw;
  margin: 0;
  margin-top: .67vw;}

.column {
    float: left;
    width: 50%;
    width: 90vw;
    margin-top: 0vw;
    margin-bottom: 1.67em;
    margin-left: 5vw;
    background-color: silver;}
}



@media (max-width: 33em){
  img {width: 90vw;}

.row {background-color: none;
  margin-left: 5vw;
  width: 90vw;}

.app{display: grid;
  margin: auto;}

h4 {
  font-size: 3.75vw;
  margin: 0;
  margin-top: .67vw;}

.column {width: 90vw;
    margin:auto;
    margin-top: 0vw;
    margin-bottom: 5.67vw;
    background-color: orange;}

p {font-size: 4vw;}
}


@media (max-width: 24em){
  img {width: 90vw;}

.row {background-color: none;
  width: 90vw;}

.app{display: grid;
    text-align: center;}

iframe {width: 90vw;
    height: 98vw;
    border-radius: 25px;
    margin-left:5vw;
    margin-bottom: 9em;
    box-shadow: 0px 0px 6vw 7px green;}

  h4 {
  font-size: 3.75vw;
  margin: 0;
  margin-top: .67vw;}

  p {font-size: 5vw;}

}
</style>
