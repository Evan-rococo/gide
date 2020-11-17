<template><div>
<head>
  <link rel="stylesheet" href="main.css"></head>
  <header> <yo /></header>


	
	<section class="products">

	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image style="width:100%" src="https://res.cloudinary.com/winenot/image/upload/v1601897504/z8_v2hh9u.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"ICH TRÄUME" LP
			<br>
				BECKER, STEGMANN, LASKER-SCHULER
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876539/p3.png"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				MR. MAC 12"
			<br>
				STEVE WILLIAMS
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897501/z6_ffdulq.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				SKETCHES OF ANDERLAND 7"
			<br>
				ANGELO VANOTTI
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"I KNOW YOU FEEL IT" LP
			<br>
				KUMASI
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897497/hrb7_ixwoxu.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"STAND UP FOR YOUR RIGHTS" LP
			<br>
				FEEL IT
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897510/z5_lxwfqq.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				TENDER LOVER 7"
			<br>
				EDDY ALIMANTE
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897477/hrb19_maeaud.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"CELIAS" LP
			<br>
				SOLO & NAMANA
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897485/z3_jmlxdd.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				MY NAME IS BOND 12"
			<br>
				BEAT CONTROL
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897549/z2_cd3q6o.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				FEELING NICE 12"
			<br>
				JAM-MASTER KING
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028557/p4.png"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"JAZZ MAIDEN" EP
			<br>
				ACCURA
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897499/hrb8_rsbwri.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"BÖHÖBÉ SPIRITS MUSIC" LP
			<br>
				NORBERTO DO NÖAH
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897453/s3_pffkyo.jpg" width=450em; height="450em;"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				U GOT THE CHARM 12"
			<br>
				AMBILEKA
			</p>
		</div>
	</div>
	</section>

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

<style scoped>

p{font-family: "Arial Rounded MT Bold";}

.products{
    display:flex;
    flex-wrap:wrap;
    margin-top:6em;
    margin-left:5vw;
    margin-bottom:3em;
    width:98vw;
    background-color:none;
}
.product-card{
    display:flex;
    flex-direction:column;
    flex:1 30%;
    padding-left:0;
    padding-right:0
}
.product-info{
	  background-color: none;
    margin-top:auto;
    text-align:right;}

@media (max-width:48em){

		
		.product-info{
    padding-bottom:.67em;
	padding-top: .34em;
    text-align:right;
    font-size:calc(.34em+1.34vw)
}

  .products{
        align-items:baseline;
        display:flex;
        flex-wrap:wrap;
        margin-top:0;
        margin-left:25vw;
        width:44.2vw;
        flex:1 36%;
        margin-bottom:6em;
        background-color:none;}
   
    .product-card{
        flex:1 46%;
        margin-right:2.5vw
    }

    .sticky{
        background-color:white;
        padding:.34em;
        border-radius:25px;
        margin-top:-3em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}

    .products .product-card:first-child,.products .product-card:nth-child(2){
        flex:2 20%
    }
    .overlay{
        position:absolute;
        top:0;
        left:0;
        height:1%;
        width:1%;
        z-index:10}
}
@media (min-width:48em){

	.product-info{
    padding-bottom:1em;
	padding-top: .34em;
    text-align:right;
    font-size:calc(.34em+1.34vw)}



    .sticky{
        background-color:white;
        
        border-radius:25px;
        margin-top:-3em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}


    .products{
        align-items:baseline;
        display:flex;
        flex-wrap:wrap;
        margin-top:2.34em;
        margin-left:25vw;
        width:74.2vw;
        flex:1 36%;
        margin-bottom:6em;
        background-color:none;}
   
    .product-card{
        flex:1 46%;
        margin-right:2.5vw
    }
    .overlay{
        position:absolute;
        top:0;
        left:0;
        height:1%;
        width:1%;
        z-index:10
    }
   .sticky{
        background-color:blue;
        border-radius:25px;
        margin-top:-7em;
        padding: .67em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}

      h2{
        margin: 0;}

       p{font-size: 1.67vw;
        margin-top: 0;
        margin-bottom: .67em;
        }
}

@media (min-width:70em){
	

		.product-info{
      background-color: none;
      padding-bottom:.34em;
	    padding-top: 0em;
      text-align:right;}

    .products{
        align-items:baseline;
        display:flex;
        flex-wrap:wrap;
        margin-top:2.34em;
        width:73.67vw;
        flex:1 36%;
        background-color:none}

    .product-card{
        flex:1 26%;
        margin-right:1.67vw;}

      p{font-size: 1.34vw;
        margin-top: 0;
        margin-bottom: .67em;
        }
}
.pointer {cursor: pointer;}


@media (max-width:48em){
    .product-info{
      width: 46vw;
      background-color: none;
    }
    .product-card{
        flex:2 45%;
        
        background-color: none;
	    }

    .products{
        display:flex;
        flex-wrap:wrap;
        margin-top:6em;
        margin-left:2vw;
        margin-right:2vw;
        width:98vw;
        flex:1 99%;
        background-color: none;}

      p{font-size: 2.67vw;
        margin-top: 0;}

       .sticky{
        background-color:red;
        padding: .67em;
        border-radius:25px;
        margin-top:-7em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}

      h2{
        margin: 0;
      }
}


@media screen and (max-width:33em){
	.product-info{
    width: 46vw;
      padding-bottom:.67em;
      background-color: none;
      text-align:right;}

    .p{background-color: none;
        margin: 0;
        font-size:calc(1.34em + 1vw)}

    .product-card{
        flex:2 47%;
		    background-color: none;}
    
    .products{
        display:flex;
        flex-wrap:wrap;
        margin-top:6em;
        margin-left:2vw;
        width:98vw;
        flex:2 36%;
        background-color:none;}
        
     .sticky{
        background-color: none;
        border-radius:25px;
        margin-top:-7em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}

      h2{
        margin: 0;}
}

  @media screen and (max-width:24em){
	.product-info{
      padding-bottom:4vw;
      margin: 0;
      width: 90vw;
      background-color: ;
      text-align:right;}

    .product-card{
        flex:2 99%;
        margin: 0;
        padding: 0;
		    background-color: none;}
    
    .products{
        display:flex;
        flex-wrap:wrap;
        margin-top:9vw;
        margin:auto;
        width:90vw;
        flex:2 46%;
        background-color:none;}
        
     .sticky{
        background-color: none;
        padding: 2.34vw;
        border-radius:25px;
        margin-top:-28vw;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 3vw .67vw #000}

       p {font-size: 5vw;
          margin:0;}

      h2{
        margin: 0;}
}
</style>
