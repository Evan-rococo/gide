<template>
<div>
      <div class="div-1">
    <div class="div div-menu">
<div class="sidebar">
		<div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%;">
      
      <div class="row">

      <div class="column-1"> 
      <div><div class="genres">
      <g-link to="/genre/">NEW STUFF</g-link><br>
			<g-link to="/boogie/">BOOGIE</g-link><br>
			<g-link to="/esoteric/">ESOTERIC</g-link><br>
			<g-link to="/pop/">POP MUSIC</g-link><br>
			<g-link to="/reggae/">REGGAE</g-link><br>
			<g-link to="/tropical/">TROPICAL</g-link></div></div></div>

			<div class="column-2">
      <div class="side-1">
			<g-link to="/faq/">FAQ</g-link><br>
			<g-link to="/contact/">CONTACT</g-link></div>
			<div class="side-2">
			<g-link to="/cart/">CART (0)</g-link><br>
			<g-link>SEARCH</g-link></div>

		
    </div></div></div></div>
		<div class="Hamburger" @click.prevent="toggleClass">
			<h2 style="height:1em">MENU</h2>
		</div></div>
	
    <div class="div div-logo"><g-link to="/"><h1>HOT REQUEST</h1></g-link></div><div class="blur"><div>
</div></div>
	</yo></div>
</div>
</template>

<script>
export default {
  components: {
        name: 'yo'}
        ,
data: () => ({
            isActive: false
        }),
        methods: {
           toggleClass: function(event){
       this.isActive = !this.isActive;
    }
        }
  
}
</script>

<style>
.blur {background-color: orange; height: 30em; top:0; border-radius: 25px; width: 120vw; margin-top: -34em; box-shadow: 0px 0px 23vw 120px green; z-index:0; position: fixed; margin-left: -2em;mix-blend-mode: multiply}

body {
  font-family:"ABC Helveesti Trial";
  background-color: none;
  margin:0;
  padding:0;
  line-height: 1.125;
}

.layout {
  max-width: 90vw;
  margin: 0 auto;
  margin-left: 5vw;
  margin-right: 5vw;
  background-color: none;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 1.67em;}



* {
  box-sizing: border-box;
}

.row {
  display: flex;
  flex-wrap: wrap;
  border-radius: 25px;
  background-color:none;
  padding: 3vw;
  padding-bottom: 4vw;
  padding-top: 3vw;
  box-shadow:none}

.column-1{ background-color: none;
  float: left;}

.column-2{ background-color:none;
  float: left;}
.side-1 {text-align: right;}
.side-2 {text-align: right;}

@media screen and (min-height: 33em) {
    .row {flex-direction: column;
      padding: 3vw;
      padding-top: 5vw;
      padding-bottom: 5vw;}

    .column-1{ background-color: none;
      float: left;}

    .column-2{ background-color:none;
      float: left;}

    .side-1 {text-align: left;}
    .side-2 {text-align: left;}

  
}





 @media(min-width: 72em) {
   .row {
  display: flex;
  flex-wrap: wrap;
  background-color:none;}

       .column-1 {
    font-size:calc(.5vw + 1.34em);
    font-family: "Arial Rounded MT Bold";
    line-height: 1.125;
    background-color: none;}

.column-2 {
  font-size:calc(.5vw + 1.34em);
  font-family: "Arial Rounded MT Bold";
  line-height: 1.125;
  background-color: crimson;}
  
         .Hamburger{
        position:fixed;
        margin-top:-9em;
        opacity:0;
        z-index:6;
        height:1em;
        margin-left:2.5vw
    }
    .Sidebar{
        position:fixed;
        top:8em;
        opacity:0%;
        z-index:0;
        line-height:1.125em;
        background-color:none}
  }


     @media(max-width: 72em) {
       .row{background-color: none;}

         .Hamburger{
        position:fixed;
        margin-top:-9em;
        opacity:0;
        z-index:6;
        height:1em;
        margin-left:2.5vw
    }
    .Sidebar{
        position:fixed;
        top:8em;
        opacity:0%;
        line-height:1.125em;
        background-color:none}
  }

  @media(max-width: 72em) {
  .row {
  display: flex;
  flex-wrap: wrap;
  border-radius: 25px;
  background-color:white;
  padding: 3vw;
  padding-bottom: 4vw;
  padding-top: 3vw;
  box-shadow:2px 6px 6px 0 #000}
  
  .genres {
    font-size:calc(1.67vw + .34em);
    font-family: "Arial Rounded MT Bold";
    line-height: 1.125;}

.column-2 {
  font-size:calc(1.67vw + .34em);
  font-family: "Arial Rounded MT Bold";
  line-height: 1.125;}

         .Hamburger{
        position:fixed;
        margin-top:-9em;
        opacity:0;
        z-index:6;
        height:1em;
        margin-left:2.5vw
    }
  }



@media(max-width: 48em) {
    .genres {
    font-size:calc(1.67vw + .67em);
    font-family: "Arial Rounded MT Bold";
    line-height: 1.125;}

.column-2 {
  font-size:calc(1.67vw + .67em);
  font-family: "Arial Rounded MT Bold";
  line-height: 1.125;}
  

  .Sidebar{
        transform:translate3d(-300%,0,0);
    }
    
    .Hamburger{
        opacity:100%;
        z-index:6;
        margin-top:0em;
        left:2.34vw;
        background-color: none;}

    .Sidebar.open{
        transform:translate3d(0,0,0);
        z-index:6;
        margin-top:0em}
  }
@media(min-width: 48em){
.row {
  display: flex;
  flex-wrap: wrap;
  border-radius: 25px;
  background-color: none;
  padding: 3vw;
  padding-bottom: 4vw;
  padding-top: 3vw;
  box-shadow:none;}
  }

 @media(max-height: 33em) {
   

  }
   

@media(max-width: 24em) {

       
      }
</style>
