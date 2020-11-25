<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head>
   <header> <yo /></header>

<div class="wrapper">
  <div class="image"><span><g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link></span>
  </div>


  <div class="tits"><span><h2>
      <div class="areola">"STAND UP FOR YOUR RIGHTS" LP</div>
			<div class="areola">FEEL IT</div>
			<div class="areola">CHARLIZ AG</div>
			<div class="areola">SOUTH AFRICA, '89</div>
			<div class="areola">VINYL VG+ SLEEVE VG</div></h2></span>
  </div>


  <div class="text"><div class="eso"></div><span><p>
				A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness.
        Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion..
			  Usually in a poignant but solemn manner.
			<br><br>
				Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.
			</p></span>
  </div>


  <div class="clips"><span><audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>LIBREVILLE (ROUGH MIX)</h3></a>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>EKWEGHELE</h3></a>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>NEW CASINO</h3></a></span>
  </div>


  <div class="cart"><span><div>
				<h2 style="font-family:Nocturne Serif; font-weight:900;">139€</h2>
				<input type="submit" style="border-radius: 25px; padding:.34em; padding-right:.8em; padding-left:.8em;" value="ADD TO CART">
			</div>
			<section id="accordion">
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
import footer from '~/components/footer.vue'
export default {
  components: {
    yo,
    footer
  }
}
</script>

<style>
* {
  box-sizing: border-box;}



* {box-sizing: border-box;}

.wrapper {
  display: flex;
  width: 76vw;
  margin-left: 21vw;
  flex-wrap: wrap;}

[class^="object"] {
  flex: 0 0 100%;
  text-align: center;
  display: flex;}
  
  .title, .product-img {
    flex: 100%;}







@media (min-width: 72em) {

}


@media (max-width: 72em) {

}



@media (max-width: 48em) {
  .wrapper {
    display: flex;
    width: 90vw;
    margin: auto;
    flex-wrap: wrap;}

  .image {
    order: 1;
    flex: 0 0 42vw;
    background-color: none;}

  .tits {
    order: 2;
    margin-left: 4vw;
    height: 22.67vw;
    background-color: none;
    flex: 0 0 44vw; }

  .text {
    order: 3;
    margin-left: 0;
    margin-top: -17vw;
    mix-blend-mode: darken;
    background-color: white;  
    flex: 0 0 100%;}

  .eso {
    shape-outside: inset(0px 0px 0px 0px);
    background-color: yellow; opacity: 0%;
  /* clip-path: inset(0 0 10px 0); */
  /* background-color: red; */
    width: 46vw;
    height: calc(12vw + 2em);
    float: left;
    margin-top:.34em;}

  p {margin-top: -.1vw;
    margin-bottom: -.1vw;}

  .clips {
    order: 4;
    margin-top: 2vw;
    background-color: none;
    flex: 0 0 100%;
    text-align: right;}

  .cart {
    order: 5;
    margin-top: 2vw;
    flex: 0 0 90vw;
    background-color: none;
    margin-left: 0%;} 
}


@media (max-width: 33em) {
  .areola { background-color: none;}
  
  h2{ background-color:none;}

  h3 {font-size: 4vw;}

  p {font-size: 3.67vw;
    line-height: 4vw;
    margin: 0;}

  input{
    background-color: red;
    font-size: 5vw;
    font-family:Arial Rounded MT Bold;
    border:0;
    margin-left:-.67vw;
    margin-bottom: 1vw;
    margin-top: 1vw;}

  .image {
    order: 1;
    flex: 0 0 100%;
    background-color:none;}

  .tits {
    order: 2;
    float: left;
    margin-left: 0;
    margin-top: 3vw;
    background-color: none;
    flex: 0 0 100%;
    height: 27vw;}

  .eso {
    shape-outside: inset(0px 0px 0px 0px);
    background-color: yellow; opacity: 0%;
  /* clip-path: inset(0 0 10px 0); */
  /* background-color: red; */
    width: 0;
    height: 0;
    float: left;
    margin-top:0em;}


  .text {
    order: 3;
    mix-blend-mode: darken;
    margin-top: 3vw;
    background-color: white;  
    flex: 0 0 100%;}

  .clips {
    order: 4;
    margin-top: 3vw;
    background-color: none;
    text-align: right;
    flex: 0 0 100%;}

  .cart {
    order: 5;
    margin-top: 3vw;
    background-color: none;  
    flex: 0 0 100%;}

 #accordion article{
    background: silver;
    border-radius:25px;
    height:0;
    margin-top: 0;
    overflow:hidden;
    margin-left:0vw;
    z-index:10;
    text-align:left}

  #accordion article p{
    padding-right: 3vw;
    padding-left: 3vw;
    padding-top: 3vw;
    padding-bottom: 3vw;
    text-align:left}

  #accordion input:checked~article{
    box-shadow:0 3px 3vw .67vw #000;
    height:auto;
    margin-top: 2vw;
    margin-bottom:6vw;
    text-align:left}

  input{
    background-color: red;
    font-size: 5vw;
    font-family:Arial Rounded MT Bold;
    border:0;
    margin-left:-3.67vw;
    margin-bottom: 1vw;
    margin-top: 1vw;}

}

@media (min-width: 23em) {

}

</style>
