<template>
<div>
      <div class="div-1">
    <div class="div div-menu">
<div class="sidebar">
		<div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%;">
      <div><div class="genres">

			<g-link to="/genre/"><h3>NEW STUFF</h3></g-link>
			<g-link to="/boogie/"><h3>BOOGIE</h3></g-link>
			<g-link to="/esoteric/"><h3>ESOTERIC</h3></g-link>
			<g-link to="/pop/"><h3>POP MUSIC</h3></g-link>
			<g-link to="/reggae/"><h3>REGGAE</h3></g-link>
			<g-link to="/tropical/"><h3>TROPICAL</h3></g-link></div>

			<div class="side-1">
			<g-link to="/faq/"><h3>FAQ</h3></g-link>
			<g-link to="/contact/"><h3>CONTACT</h3></g-link></div>
			<div class="side-2">
			<g-link to="/cart/"><h3>CART (0)</h3></g-link>
			<g-link><h3>SEARCH</h3></g-link>

		
    </div></div></div></div>
		<div class="Hamburger" @click.prevent="toggleClass">
			<h2 style="height:1em">MENU</h2>
		</div></div>
	
    <div class="div div-logo"><h1>HOT REQUEST</h1></div>
</div>
	</yo>
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
  margin-top: 1.67em;

}
 @media(min-width: 98em) {
  
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
        opacity:100%;
        z-index:0;
        left:5vw;
        width:10em;
        line-height:1.125em;
        background-color:none}

        h3{
          font-size: 1.67em;
          margin: 0;
          line-height: 1.125;
        }
  }


     @media(max-width: 98em) {

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
        opacity:100%;
        z-index:0;
        left:7vw;
        width:10em;
        line-height:1.125em;
        background-color:none}

        h3{
          font-size: 1.67em;
          margin: 0;
          line-height: 1;
        }
  }

@media(max-width: 70em) {

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

  .Sidebar{
        transform:translate3d(-300%,0,0);
    }
    
    .Hamburger{
        opacity:100%;
        z-index:6;
        margin-top:0em;
        left:2.34vw;
        background-color: none;

    }
    .Sidebar.open{
        transform:translate3d(0,0,0);
        z-index:6;
        margin-top:0em
    }
  }

 @media(max-height: 33em) {


.Hamburger{
        opacity:100%;
        z-index:6;
        margin-top: 0em;
        left:2.34vw;
        background-color: none;}
  }
   

@media(max-width: 23em) {

       .Hamburger{
        opacity:100%;
        z-index:6;
        margin-top: 0em;
        left:2.34vw;
        background-color: none;}
      }
</style>
