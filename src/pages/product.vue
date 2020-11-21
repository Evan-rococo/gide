<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head><div>
  <header><yo /></header>


<div class="container">
	<div class="left">
		<div class="prod-img">
			<input class="native-hidden" type="checkbox"/>
		</div>

		<div class="clips">
			<div>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>LIBREVILLE (ROUGH MIX)</h3></a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>EKWEGHELE</h3></a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn"><h3>NEW CASINO</h3></a><br>
			</div>

			<div class="item blank">
			</div>

		</div>
	</div>


	<div class="right">
		<div class="title">
			<h2>"STAND UP FOR YOUR RIGHTS" LP</h2>
			<h2>FEEL IT</h2>
			<h2>CHARLIZ AG</h2>
			<h2>SOUTH AFRICA, '89</h2>
			<h2>VINYL VG+ SLEEVE VG</h2>
		</div>


		<div class="text">
			<p>
				 A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness.
			<br><br>
				Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion..
			<br><br>
				 Usually in a poignant but solemn manner.
			<br><br>
				Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.
			</p>
		</div>

		<div class="prix-etc">
			<div>
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
		</div>
	</div>
</div>
</div>



<div class="suggested"><h3>MORE GOOD RECORDS</h3></div>

<div class="sugg-container">
<div class="sugg-left">
	<div class="sugg-ind-flex">
		<div class="sugg-minor">
			<g-link to="/boogie/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link>
		</div>
		<div class="sugg-text">
			<h3 style="margin-bottom:.34em">"I KNOW YOU FEEL IT" LP</h3>
			<h3>KUMASI</h3>
		</div>
	</div>
</div>
<div class="sugg-right">
	<div class="sugg-ind-flex">
		<div class="sugg-minor">
			<g-link to="/boogie/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897448/p1_jy7ug9.png"/>
			</g-link>
		</div>
		<div class="sugg-text">
			<h3 style="margin-bottom:.34em">TENDER LOVER 7"</h3>
			<h3>EDDY ALIMANTE</h3>
		</div>
	</div>
</div>
</div>
</div>


</template>


<script>
import yo from '~/components/yo.vue'
import footer from '~/components/footer.vue'
export default {
  components: {
    yo, footer
  }
}
</script>

<style scoped>
.btn{
    cursor:pointer;
    display:inline-block;
    text-align:right;
    margin-right:0;
    padding:0;
    margin-bottom:.34em
}
.container{
    margin-left:5vw;
    margin-bottom:3em;
    width:90vw;
    background-color:none
}
.item{
    margin-bottom:0;
    text-align:left;
    background:0 0
}
.prod-img{
    padding-bottom:0;
    margin-bottom:0
}
.title{
    margin-top:.67em;
    background-color:none
}
h2{
    line-height:1
}
.clips{
    text-align:right;
    margin-bottom:1em;
    margin-right:0;
    background-color:none
}

.prix-etc{
    background-color:orange;
    margin-top:-.34em
}
.left{
    opacity:100%
}
.left,.right{
    display:contents
}
.prod-img,.title{
    order:1
}
.text,.blank{
    order:2
}
.clips,.prix-etc{
    order:3
}
.sugg-ind-flex{
    display:flex;
    flex-direction:column;
    text-align:left
}
.sugg-minor{
    background-color:none;
    flex:50%
}
.sugg-text{
    background-color:none;
    padding-left:.67em;
    text-align:left;
    flex:50%
}

@media (min-width:70em){
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:30vw;
        height:30vw;
        outline:0;
        margin-left:0
        
    }
    .left,.right{
        display:inline-block;
        vertical-align:top
    }
    .container{
        display:block;
        margin-left:25vw}
    

    .left{
        width:30vw;
        margin-right:1.34em;
        background-color:blue
    }
    .right{
        width:46vw;
        background-color:plum
    }
    .prod-img{}

    .title{
        margin-bottom:1em;
        width:41.5vw;
        background-color:none
    }
    .clips{
        text-align:right;
        background-color:none;}
        
    .text{
        margin-bottom:1.5em;
        margin-right:0;
        background-color:green
    }
    p{
        background-color:none
    }
    .btn{
        cursor:pointer;
        display:inline-block;
        text-align:right;
        margin-bottom:.34em
    }
    #accordion1 input{
        display:none
    }
    #accordion1 label{
        cursor:pointer;
        display:block;
        padding:.1725em 0;
        background:0 0
    }
    #accordion1 input:checked+label{
        background:0 0;
        margin-bottom:0
    }
    #accordion1 article{
        background:#f5f5f5;
        height:0;
        overflow:hidden;
        z-index:10
    }
    #accordion1 article p{
        padding:1em
    }
    #accordion1 input:checked~article{
        height:auto;
        margin-bottom:.125em
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    .native-hidden{
        -webkit-appearance:none;
        -moz-appearance:none;
        appearance:none
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        height:0;
        overflow:hidden;
        margin-left:0;
        z-index:10;
        text-align:left
    }
}



@media (max-width:70em){
        h2 {font-size: 1.67em;
        margin-bottom: .2em;
        margin-top: 0em;}

    h3 {font-size: 1.34em; line-height: .9;
        margin-bottom:.34em}

    
    img {width: 100%;}
 
    .sugg-container{
        background-color:none;
        border-radius:0;
        width:45vw;
        margin-bottom:6em
    }
    .sugg-ind-flex{
        display:contents;
        background-color:none;
        display:flex;
        flex-direction:column;
        text-align:left;
        padding:.34em
    }
    .sugg-minor{
        background-color:none;
        flex:50%;
        width:30vw;
        margin-bottom:.34em
    }
    .sugg-text{
        background-color:none;
        width: 100%;
        text-align:left;
        flex:50%
    }

    .suggested{
        background-color:#ff0;
        border-radius:25px;
        padding:.34em;
        width:8em;
        display:block;
        margin-left:calc(57vw + 1em);
        text-align:center;
        transform:rotate(-20deg)
    }

    p {font-size: 1.125em;}

    h2 {font-size: 1.67em;
        margin-bottom: .2em;
        margin-top: 0em;}

    h3 {font-size: 1.34em; line-height: .9;
        margin-bottom:.34em}

    input{
        background-color:red;
        font-size:1.67em;
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:30vw;
        height:30vw;
        outline:0;
        margin:0;
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    .btn{
        cursor:pointer;
        display:inline-block;
        text-align:right;
        margin-bottom:.34em
    }
    .left,.right{
        display:inline-block;
        vertical-align:top
    }
    .prod-img{
        margin-bottom:2vw;
    }
    .title{
        margin-bottom:.67em;
        width:40.4vw;
        background-color:none
    }
    .clips{
        text-align:right;
        background-color:none
    }
    .text{
        width: 40.4vw;
        margin-bottom:1.34em;
        background-color:plum
    }
    p{  width: 40.4vw;
        background-color:none;}

    .container{
        display:block;
        background-color:none;
        margin-left:25vw;
        margin-bottom:6em}

    .left{
        width:30vw;
        margin-right:2vw;
        background-color:none
    }
    .title{
        margin-top:0;}

    .right{
        width:45%;
        background-color:none
    }
    #accordion input{
        display:none
    }
    #accordion label{
        cursor:pointer;
        display:block;
        background:0 0;}

    #accordion input:checked+label{
        background:0 0;
        text-align:left
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        height:0;
        overflow:hidden;
        margin-left:-16vw;
        z-index:10;
        text-align:left
    }
    #accordion article p{
        padding-right:.5em;
        padding-left:1em;
        padding-top:1em;
        padding-bottom:.5em;
        text-align:left
    }
    #accordion input:checked~article{
        box-shadow:0 3px 3vw .67vw #000;
        height:auto;
        margin-bottom:3em;
        text-align:left
    }
}

@media (min-width:48em){
    .left {background-color:blue;
        width:36vw;
        left:0;
        margin-right:2.5vw}
    .right {
        background-color:yellow;
        width:34vw
    }
    .text {width:34vw}
    .title{background-color:green;width:34vw;margin-top:.34em}

    .container{background-color:orange;margin-left:25vw}
    .left,.right{
        display:inline-block;
        vertical-align: top;
    }


    .sugg-ind-flex{
        flex-direction:row}

    img {width: 100%;}

    .sugg-minor{
        background-color:green;
        padding:2vw;
        flex:50%
    }
    .sugg-text{
        background-color:none;
        padding:2vw;
        text-align:left;
        flex:50%
    }
    .sugg-container{
        background-color:none;
        margin-bottom:1.67em
    }
 
    .suggested{
        background-color:#ff0;
        border-radius:25px;
        padding:.34em;
        width:8em;
        display:block;
        margin:auto;
        text-align:center;
        transform:rotate(-20deg)
    }

    p{  width: 40vw;
        background-color:none;
        line-height:1.125;
        font-size:calc(1vw + .67em);}

    h2 {font-size:calc(1.67vw + .67em);
        margin-bottom: .2em;
        margin-top: 0em;}

    h3 {font-size:calc(1vw + .67em); line-height: .9;
        margin-bottom:.34em}
    
    input{
        background-color:red;
        font-size:calc(1.67vw + .67em);
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:36vw;
        height:36vw;
        outline:0
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
  
    .checkbox{
        background-color:none
    }
    #accordion input{
        display:none
    }
    #accordion label{
        cursor:pointer;
        display:block;
        background:0 0;}

    #accordion input:checked+label{
        background:0 0;
        text-align:left
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        width:90vw;
        height:0;
        overflow:hidden;
        z-index:10;
        text-align:left
    }
    #accordion article p{
        line-height:1.125;
        padding-right:3vw;
        padding-left:3vw;
        padding-top:0vw;
        padding-bottom:3vw;
        text-align:left
    }
    #accordion input:checked~article{
        margin-top:3vw;
        height:auto;
        box-shadow:0 3px 3vw .67vw #000;
        margin-bottom:6vw;
        margin-left:0;
        text-align:left
    }
}


@media (max-width:48em){
    .left {background-color:pink;
        width:45vw;
        margin-right:2.5vw}

    .right {background-color:yellow;
        width:42.5vw}

    .text {width:42.5vw;margin:0}

    .title{background-color:green;width:42.5vw;margin-top:.34em}

    .container{
        display:block;
        background-color:red;
        margin-left:5vw;
        margin-bottom:6em}

    .left,.right{
        display:inline-block;
        vertical-align:top;}


    .sugg-ind-flex{
        flex-direction:row}

    img {width: 100%;}

    .sugg-minor{
        background-color:green;
        padding:2vw;
        flex:50%
    }
    .sugg-text{
        background-color:none;
        padding:2vw;
        text-align:left;
        flex:50%
    }
    .sugg-container{
        background-color:none;
        margin-bottom:1.67em
    }
 
    .suggested{
        background-color:#ff0;
        border-radius:25px;
        padding:.34em;
        width:8em;
        display:block;
        margin:auto;
        text-align:center;
        transform:rotate(-20deg)
    }

    p{  width:42.5vw;
        background-color:none;
        line-height:1.125;
        font-size:calc(1vw + .67em);}

    h2 {font-size:calc(1.67vw + .67em);
        margin-bottom: .2em;
        margin-top: 0em;}

    h3 {font-size:calc(1vw + .67em); line-height: .9;
        margin-bottom:.34em}
    
    input{
        background-color:red;
        font-size:calc(1.67vw + .67em);
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:45vw;
        height:45vw;
        margin-left:0;
        outline:0;
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
  
    .checkbox{
        background-color:none;
    }
    #accordion input{
        display:none
    }
    #accordion label{
        cursor:pointer;
        display:block;
        background:0 0;}

    #accordion input:checked+label{
        background:0 0;
        text-align:left
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        width:42.5vw;
        height:0;
        overflow:hidden;
        z-index:10;
        text-align:left
    }
    #accordion article p{
        line-height:1.125;
        padding-right:3vw;
        padding-left:3vw;
        padding-top:0vw;
        padding-bottom:3vw;
        text-align:left
    }
    #accordion input:checked~article{
        margin-top:3vw;
        height:auto;
        box-shadow:0 3px 3vw .67vw #000;
        margin-bottom:6vw;
        margin-left:0;
        text-align:left
    }
}


@media (max-width:33em){
        input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:90vw;
        height:90vw;
        margin-left:0;
        outline:0
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    .text {width:90vw}
    .title {width:90vw}
    .clips {background-color:none} 
    .sugg-container{
        background-color:none;
        margin-bottom:1.67em
    }
    .sugg-ind-flex{
        display:flex;
        text-align:left
    }
    .sugg-minor{flex:50%}

    .sugg-text{
        padding:2vw;
        text-align:left;
        flex:50%
    }
    .suggested{
        display:block;
        margin-left:auto;
        text-align:center;
        margin-bottom:0}

    p {font-size: 1.34em;
        width:90vw;}

    h2 {font-size: 1.67em;
        margin-bottom: .2em;}

    h3 {font-size: 1.34em; line-height: .9;}


    input{
        background-color:red;
        font-size:1.34em;
        font-family:Arial Rounded MT Bold;
        border:0;
        left:0
    }
    .container{
        margin-left:5vw;
        background:0 0;
        margin-bottom:4em
    }
    .item{text-align:left;}

    .btn{
        width:90vw;
        margin-right:2.67vw;
        margin-bottom:1.5vw;
    }
    .title{
        margin-top:5vw;
        background-color:none}

    .text {margin-bottom:9vw}
    .left,.right{
        display:contents
    }
    .prod-img,.text{
        order:1
    }
    .text,.prix-etc{
        order:2
    }
    .clips,.blank{
        order:3
    }
    .suggested{
        margin-left:30%
    }

        #accordion article{
        background:silver;
        border-radius:25px;
        width:90vw;
        height:0;
        overflow:hidden;
        z-index:10;
        text-align:left
    }
}





@media (max-width:24em){
    p {font-size: 5vw;}

    h2 {font-size: 6.67vw;
        margin-bottom: .2em;
        margin-top: 0em;}

    h3 {font-size: 5vw; line-height:;
        margin-bottom:1vw}


    input{
        background-color:red;
        font-size:5vw;
        font-family:Arial Rounded MT Bold;
        border:0;
        left:0
    }
    .container{
        background:0 0;
        margin-bottom:4em
    }
    .item{
        margin-bottom:0;
        text-align:left;
        background:0 0;
        margin-bottom:0
    }
    .btn{
        width:90vw;
        background-color:none;
        border-radius:25px;
        padding-right:.67em;
        padding-left:.67em;
        margin-right:2.67vw;
        margin-bottom:.34em
    }
    .title{
        margin-top:5vw;
        background-color:none
    }
    .left,.right{
        display:contents
    }
    .prod-img,.title{
        order:1
    }
    .text,.prix-etc{
        order:2
    }
    .clips,.blank{
        order:3
    }
    .suggested{
        margin-left:30%
    }
}
.pointer {cursor: pointer;}
</style>