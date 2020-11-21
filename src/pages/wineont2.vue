<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head>
   <header> <yo /></header>

<div class="wrapper">
  <div class="image"><span><g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link></span>
  </div>


  <div class="tits"><span>
      <div class="areola">"STAND UP FOR YOUR RIGHTS" LP</div>
			<div class="areola">FEEL IT</div>
			<div class="areola">CHARLIZ AG</div>
			<div class="areola">SOUTH AFRICA, '89</div>
			<div class="areola">VINYL VG+ SLEEVE VG</div></span>
  </div>


  <div class="text"><span><p>
				 A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness.
			<br><br>
				Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion..
			<br><br>
				 Usually in a poignant but solemn manner.
			<br><br>
				Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.
			</p></span>
  </div>


  <div class="clips"><span><audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">LIBREVILLE (ROUGH MIX)</a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">EKWEGHELE</a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">NEW CASINO</a><br></span>
  </div>


  <div class="cart"><span><div>
				<h2>139€</h2>
				<input type="submit" style="border-radius: 25px; padding:.34em; padding-right:.8em; padding-left:.8em;" value="ADD TO CART">
			</div>
			<section id="accordion" style="margin-top:.67em;">
			<div>
				<input type="checkbox" id="conditions"/>
				<label for="conditions"><h3>CONDITIONS</h3></label>
				<article>
				<p>Hope that this place becomes somewhere fun on the web. I'll be filing it with all sorts of records; the kind you like. All styles respected, but the stock is heavily weighted towards the lesser-known. It seems there is no end to the pool of '80s records. <br>
					<br>
					 In recent years, I'm leaning more and more towards do-it-yourself. Be it pop music, tropical, boogie, etc. so long as it hits right.
				</p>
				</article>
			</div>
			</section>
			<section id="accordion">
			<div>
				<input type="checkbox" id="shipping"/>
				<label for="shipping"><h3>SHIPPING INFO</h3></label>
				<article>
				<p>Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br>
					<br>
					 If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br>
					<br>
				</p>
				</article>
			</div>
			</section>
		</span>
  </div>
</div>


  
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
  box-sizing: border-box;}
     input{
        background-color:red;
        font-size:1.67em;
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }


* {box-sizing: border-box;}

.wrapper {
  display: flex;
  width: 70vw;
  margin-left: 21vw;
  flex-wrap: wrap;}

[class^="object"] {
  flex: 0 0 100%;
  text-align: center;
  display: flex;}
  
  .title, .product-img {
    flex: 100%;}

  .image {
  order: 1;
  flex: 0 0 40%;
  background-color:white;    
}
.tits {
  order: 2;
  background-color: white;
  margin-left: 1vw;
  flex: 0 0 40.5vw;
  height: 10em;
  font-size:calc(1.67vw + .34em);
  font-family: "Arial Rounded MT Bold";
}

.areola {margin-bottom:1.34vw; line-height: .92;}
.text {
  order: 4;
  margin-left: 1vw;
  margin-top: -9em;
  background-color:white;  
  flex: 0 0 40.5vw;}

p {font-size:calc(.67vw + .67em);
  margin-top: -.1vw;}

.clips {
  order: 3;
  line-height: 1.34;
  background-color: white;
  flex: 0 0 40%;
  text-align: right;
  font-size:calc(1.67vw + .34em);
  font-family: "Arial Rounded MT Bold";
}
.cart {
  order: 5;
  background-color: white;  
  flex: 0 0 40.5vw;
  margin-left: 29vw;
}

@media (min-width: 72em) {

}


@media (max-width: 72em) {
  .wrapper {
    background-color: none;
    display: flex;
    width: 75vw;
    margin-left: 21vw;
    flex-wrap: wrap;}

  .image {
    order: 1;
    flex: 0 0 33vw;}

  .tits {
    order: 2;
    margin-left: 1.5vw;
    font-size:calc(2vw + .34em);
    font-family: "Arial Rounded MT Bold";
    flex: 0 0 40.5vw;
    background-color: white;}

  .text {
    order: 3;
    margin-top: 1.5vw;
    margin-left: 0; 
    flex: 0 0 100%;
    background-color: white;}

  p {font-size:calc(1.34vw + .67em);
    margin-top: -.1vw;
    margin-bottom: -.1vw;}

  .clips {
    order: 4;
    margin-top: 1.5vw;
    line-height: 1.67;
    font-size:calc(2vw + .34em);
    flex: 0 0 100%;
    text-align: right;}

  .cart {
    order: 5;
    margin-top: 1.5vw;
    background-color: white;  
    flex: 0 0 75vw;
    margin-left: 0%;}

  #accordion input{
    display:none}

  #accordion label{
    cursor:pointer;
    display:block;
    background:0 0;}

  #accordion input:checked+label{
    background:0 0;
    text-align:left}

  #accordion article{
    background:silver;
    border-radius:25px;
    height:0;
    overflow:hidden;
    margin-left:-16vw;
    z-index:10;
    text-align:left}

  #accordion article p{
    text-align:left;
    margin-top: -1vw;}

    #accordion input:checked~article{
      box-shadow:0 3px 3vw .67vw #000;
      height:auto;
      padding: 1vw;
      margin-bottom:3em;
      text-align:left}
}



@media (max-width: 48em) {
  .wrapper {
    display: flex;
    width: 90vw;
    margin: auto;
    flex-wrap: wrap;}

  .image {
    order: 1;
    flex: 0 0 44vw;
    background-color: none;}

  .tits {
    order: 2;
    margin-left: 1.5vw;
    font-size:3.34vw;
    background-color: white;
    flex: 0 0 44.5vw; }

  .text {
    order: 3;
    margin-top: 1.5vw;
    background-color: white;  
    flex: 0 0 100%;}

  p {font-size:calc(1.34vw + .67em);
    margin-top: -.1vw;
    margin-bottom: -.1vw;}

  .clips {
    order: 4;
    margin-top: 1.5vw;
    font-size: 3.34vw;
    background-color: white;
    flex: 0 0 100%;
    text-align: right;}

  .cart {
    order: 5;
    margin-top: 1.5vw; 
    font-size: 2vw; 
    flex: 0 0 90vw;
    background-color: white;
    margin-left: 0%;}

  #accordion input{
    display:none}

  #accordion label{
    cursor:pointer;
    display:block;
    background:0 0;}

  #accordion input:checked+label{
    background:0 0;
    text-align:left}

  #accordion article{
    background:silver;
    border-radius:25px;
    height:0;
    margin-top: 1.5vw;
    overflow:hidden;
    margin-left:0vw;
    z-index:10;
    text-align:left}

  #accordion article p{
    padding-right:.5em;
    padding-left:1em;
    padding-top:1em;
    padding-bottom:.5em;
    text-align:left}

  #accordion input:checked~article{
    box-shadow:0 3px 3vw .67vw #000;
    height:auto;
    margin-bottom:3em;
    text-align:left}
}


@media (max-width: 33em) {
  .image {
    order: 1;
    flex: 0 0 100%;
    background-color:white;}

  .tits {
    order: 2;
    float: left;
    margin-left: 0;
    font-size:calc(2.67vw + .67em);
    background-color:white;
    flex: 0 0 100%;
    margin-top: 3vw;
    height: 28vw;}


  .text {
    order: 3;
    margin-top: 3vw;
    background-color: white;  
    flex: 0 0 100%;}

  p {font-size:calc(1.67vw + .67em);
    margin-top: -.05vw;
    margin-bottom: -.05vw;}

  .clips {
    order: 4;
    margin-top: 3vw;
    line-height: 1.34;
    font-size:calc(2.67vw + .67em);
    background-color:white;
    text-align: right;
    flex: 0 0 100%;}

  .cart {
    order: 5;
    margin-top: 3vw;
    background-color: white;  
    flex: 0 0 100%;}

  #accordion article{
    background:silver;
    border-radius:25px;
    margin-top: 1.5vw;
    width:90vw;
    height:0;
    overflow:hidden;
    z-index:10;
    text-align:left}

}

@media (min-width: 23em) {

}

</style>
