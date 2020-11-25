<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head>
   <header> <yo /></header>

<div class="wrapper">
  <div class="steve"><span>

<img><g-image src="https://res.cloudinary.com/winenot/image/upload/v1604714572/IMG_1509_efki4t.png"/>
			</img>

  </span>
  </div>

  <div class="intro"><span>
  
  <p>Welcome to the Frequently asked questions page. Here are the answers to them. In the chance that you have a question that is not frequently asked, please <mark><g-link to="/contact">gimme a holler over here.</g-link></mark>
			</p>
  
  </span>
  </div>
  
  <div class="object5"><span>

<div class="item item4">
			<section id="accordion">
			<div>
				<input type="checkbox" id="who-are-u"/>
				<label for="who-are-u" style="padding-bottom:0.67em;"><h4>WHO ARE YOU?</h4></label>
				<article>
				<p>
					I'm just a guy buying too many records. If not addiction, its gotta be defined as compulsion. My name is Evan Jordan. I'm an american guy, living in sweden. <br>
					<br>
					 I guess i've been collecting seriously for.. what year is it now? It's been almost 10 years now. I'd like to think i'm pretty knowledgable about all this stuff. Please drop me a line if you've got any questions, requests or just wanna chat.
				</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="what-is-this"/>
				<label for="what-is-this" style="padding-bottom:0.67em;"><h4>WHAT IS THIS PLACE ABOUT?</h4></label>
				<article>
				<p style="font-family:ABC Helveesti Trial;">
					Hope that this place becomes somewhere fun on the web. I'll be filing it with all sorts of records; the kind you like. All styles respected, but the stock is heavily weighted towards the lesser-known. It seems there is no end to the pool of '80s records. <br>
					<br>
					 In recent years, I'm leaning more and more towards do-it-yourself. Be it pop music, tropical, boogie, etc. so long as it hits right.
				</p>
				</article>
			</div>
			</section>
		</div>
		<div class="item item4" style="padding-bottom:0.67em;">
			<section id="accordion">
			<div>
				<input type="checkbox" id="what-prices"/>
				<label for="what-prices" style="padding-bottom:0.67em;"><h4>WHAT'S WITH THESE PRICES?</h4></label>
				<article>
				<p>
					Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br>
					<br>
					 If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br>
					<br>
					 I agree there is a sizeable speculativity, but I want to err on being conservative in my pricing.
				</p>
				</article>
			</div>
			</section>
			<section id="accordion">
			<div>
				<input type="checkbox" id="how-pay"/>
				<label for="how-pay" style="padding-bottom:0.67em;"><h4>HOW DO I PAY?</h4></label>
				<article>
				<p>
					Payments can be made either by Paypal or, in the case of Swedish residents, Swish.
				</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="shipping"/>
				<label for="shipping" style="padding-bottom:0.67em;"><h4>WHAT CAN YOU TELL ME ABOUT SHIPPING?</h4></label>
				<article>
				<p style="font-family:Learning Curve">
					In your paypal payment, a tracking number will be added and can be searched <mark><g-link to="https://www.postnord.se/en/our-tools/track-and-trace2">right here.</g-link></mark> PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.
				</p>
				</article>
			</div>
			</section>
		</div>

  </span>
  </div>
</div>


  </div>
</div></div>
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

@media (max-width:72em){
* {
  box-sizing: border-box;
}
.wrapper {
  display: flex;
  width: 74vw;
  flex-wrap: wrap;
  background-color: none
}
[class^="object"] {
  flex: 0 0 100%;
	display: flex;	
}
.steve {
  order: 3;
  flex: 0 0 30vw;
  background-color:none}

img {border-radius:25px; margin:0em; padding:0;}

.object2 {
  background-color: none;
  order: 1;}

.intro {
  order: 2;
  margin-left:0;
  margin-bottom:3vw;
  width:74vw;
  background-color:none;}

.object5 {
  order: 4;
  background-color:none;
  margin-left: 2vw;
  flex: 0 0 42vw
}

    h4 {font-family:"Arial Rounded MT Bold";
        -webkit-font-smoothing: antialiased;
        font-weight: 500;
        font-size: 2.34vw;
        margin:0}
    

    
    p {font-family:"ABC Helveesti Trial";
        -webkit-font-smoothing: antialiased;
        font-weight: 400;
        margin:0;
        line-height: 1.125;
        font-size: 2.34vw;}
     }

@media (max-width:48em){
* {
  box-sizing: border-box;
}
.wrapper {
  display: flex;
  width: 90vw;
  flex-wrap: wrap;
}
[class^="object"] {
  flex: 0 0 100%;
  display: flex;}
  
.steve {
  order: 3;
  flex: 0 0 40vw;}

img {border-radius:25px;}

.object2 {
  order: 1;}

.intro {
  order: 2;
  width:90vw;}

.object5 {
  order: 4; 
  background-color:none;
  flex: 0 0 48vw
}

    h4 {
        -webkit-font-smoothing: antialiased;
        font-weight: 500;
        font-size: 3.34vw;
        margin:0}
    

    
    p {font-family:"ABC Helveesti Trial";
        -webkit-font-smoothing: antialiased;
        font-weight: 400;
        line-height: 1.125;
        font-size: 3vw;}
     }

@media (max-width:33em){
* {
  box-sizing: border-box;
}
.wrapper {
  display: flex;
  width: 90vw;
  flex-wrap: wrap;
}
[class^="object"] {
  flex: 0 0 100%;
  display: flex;}
  
.steve {
  order: 3;
  flex: 0 0 90vw;}

img {border-radius:25px;}

.object2 {
  order: 1; }

.intro {
  order: 2;
  width:90vw;
  background-color: none;  
}

.object5 {
  order: 4;
  margin-top:6vw;
  margin-left:0;
  background-color: none;  
  flex: 0 0 90vw
}

    h4 {
        -webkit-font-smoothing: antialiased;
        font-weight: 400;
        font-size: 4vw;
        margin:0}
    

    
    p {font-family:"ABC Helveesti Trial";
        -webkit-font-smoothing: antialiased;
        font-weight: 400;
        line-height: 1.125;
        font-size: 3.34vw;}
}
</style>
