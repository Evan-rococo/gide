<template>
<div>
	<form action="/action_page.php">
		<div class="row2">
			<div class="col-25" style="margin-bottom:.34em;">
				<label for="name">NAME</label>
			</div>
			<div class="col-75" style="text-align:right;">
				<input type="text" id="name" name="name" style="text-align:right; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em; " placeholder="">
			</div>
		</div>
		<div class="row2">
			<div class="col-25" style="margin-bottom:.34em;">
				<label for="lname">EMAIL ADDRESS</label>
			</div>
			<div class="col-75" style="text-align:right;">
				<input type="text" id="email" name="email" style="text-align:right; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;" placeholder="">
			</div>
		</div>
		<div class="row2">
			<div class="col-25" style="text-align:right; margin-bottom:.34em;">
				<label for="topic">TOPIC</label>
			</div>
			<div class="col-75">
				<select id="topic" name="topic" style="padding-left:4vw; color:red; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:.34em;margin-bottom:.67em;-webkit-appearance: none;">
					<option value="request"></option>
					<option value="request">MAKE A REQUEST</option>
					<option value="before">BEFORE ORDER</option>
					<option value="after">AFTER ORDER</option>
				</select>
			</div>
		</div>
		<div class="row2">
			<div class="col-25" style="margin-bottom:.34em;">
				<label for="subject">ADDITIONAL INFO</label>
			</div>
			<div class="col-75">
				<textarea id="subject" name="subject" placeholder="" style="text-align:right; background-color:whitesmoke; height:6em;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;"></textarea>
			</div>
		</div>
		<div class="row2">
			<div class="col-26" style="text-align:center;">
				<input type="submit" style="background-color:green;border-radius: 25px; padding:.34em; padding-right:.8em; padding-left:.8em;" value="SUBMIT">
			</div>
		</div>
	</form>
</div>
</template>

<script>
export default {
    components: {
        name: 'Form'
    }
}
</script>
<style scoped>
	.col-25 {
		font-family:"Arial Rounded MT Bold";
	}

	.col-75 {
		font-family:"ABC Helveesti Trial";
		}
		



@media (max-width:33em) {
	form {
		background-color: none;
		width: 90vw;
		
	}
	.column {
		float:left;
		height:8em;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
	}
	.col-25 {
		text-align:right;
		color:black;
		font-size:1.34em;
		margin:0em;
		padding:0em;
		
	}
	.col-26 {
		margin-bottom:0em;
		margin:auto;
		font-size:1.34em;
		background-color:none;
	}
	.col-75 {
		text-align:right;
		color:black;
		padding:0em;
		font-size:1.34em;
		width: 90vw;
		
		}
		
	

	h3 {
		margin-top:4.8em;
		font-size:1.25em;
		margin-left:5vw;
		margin-right:5vw;
		padding:2vw;
	}
}
@media (max-width:48em) {
	
	form {
		background-color: none;
		width: 90vw;
		margin-left:5vw;
	}
	
	.col-25 {
		text-align:right;
		font-size: 1.34em;
		width: 88vw;
		margin-right:0em;
		padding:0em;
		background-color: none;
	}
	.col-26 {
		font-size:1.34em;
		background-color:green;
	}
	.col-75 {
		text-align:right;
		margin:0em;
		padding:0em;
		background-color:none;
	}
}
@media (min-width:48em) {
	.column {
		float:left;
		background-color:none;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
		margin-left:25vw;
		margin-right:2vw;
		background-color:none;
	}
	h3 {
		margin-top:1.5em;
		line-height: 1.125;
		margin-left:24.67vw;
		margin-right:2vw;
		background-color:none;
		padding:.67vw;
		font-size:1.25em;
	}
	.left,.right {
		display:inline-block;
		vertical-align:top;
	}
	.col-25 {
		text-align:right;
		width: 70vw;
		color:black;
		font-size:1.34em;
		background-color: none;
	}
	.col-26 {
		margin-bottom:9em;
		font-size:1.34em;
		background-color:green;
	}
	.col-75 {
		text-align:right;
		color:black;
		font-size:1.125em;
		border-radius:25px;
		margin-bottom:.34em;
	}
}
@media (min-width:70em) {
	.left,.right {
		display:inline-block;
		vertical-align:top;
	}
	.row {
		margin-right:0vw;
	}
	.col-25 {
		text-align:right;
		width: 98%;
		background-color: none;
		color:black;
		font-size:1.34em;
	}
	.col-26 {
		margin-bottom:9em;
		font-size:1.34em;
		background-color:green;
	}
	.col-75 {
		text-align:right;
		color:black;
		font-size:1.125em;
	}
}
mark {
	background-color:yellow;
	color:black;
}
* {
	box-sizing:border-box;
}
input[type=text],select,textarea {
	width:100%;
	padding-bottom:0em;
	border:0px;
	resize:vertical;
	font-family:'ABC Helveesti Trial';
	font-size:1em;
	outline:none;
	background-color:none;
}
label {
	display:inline-block;
	outline:none;
}
input[type=submit] {
	background-color:plum;
	font-size:1em;
	font-family:'Arial Rounded MT Bold';
	border:none;
	padding:0em;
	cursor:pointer;
	float:right;
	outline:none;
}
input[type=submit]:hover {
	background-color:orange;
	outline:none;
	padding: 0em;
}
/* Clear floats after the columns */
.row:after {
	content:"";
	display:table;
	clear:both;
}
@media (max-width:48em) {

	.column {
		float:left;
		height:calc(8em+5vw);
		width:100%;
		background-color: green;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
		background-color:none;
	}

	.col-26 {
		margin-bottom:6em;
		font-size: 1.34em;
	}
	.col-75 {
		text-align:right;
		width: 90vw;
		color:black;
		margin:0em;
		padding:0em;
		font-size:1.125em;
		background-color:none;
	}
	.left2 {
		width:calc(8em+5vw);
		height:2em;
	}
	h3 {
		margin-top:4.8em;
		font-size:1.25em;
		margin-left:2vw;
		margin-right:2vw;
		background-color:none;
		padding:2vw;
	}
}

@media (min-width:70em) {
	.column {
		float:left;
		height:2em;
		margin-top:3em;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
		margin-left:25vw;
		margin-right:2vw;
		background-color:none;
	}
	h3 {
		font-size:1.25em;
		margin-top:1.5em;
		margin-left:25vw;
		margin-right:2vw;
		background-color:none;
		padding: .67vw;
	}
}

label {
	margin-right: .125em;
}
input:-webkit-autofill,
  input:-webkit-autofill:hover,
  input:-webkit-autofill:focus textarea:-webkit-autofill,
  textarea:-webkit-autofill:hover textarea:-webkit-autofill:focus,
  select:-webkit-autofill,
  select:-webkit-autofill:hover,
  select:-webkit-autofill:focus {
    -webkit-box-shadow: 0 0 0px 1000px whitesmoke inset !important;
  }
</style>