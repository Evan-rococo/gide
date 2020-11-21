<template>

<div class="footer">
		<footer>
		<div class="flex-container" style="background-color: yellow;margin-bottom:.67em;box-shadow: 0px 0px 0vw 0vw green;">
			<div class="flex-container1">
				<div class="flex-item-left1">
					<g-link to="/">INSTAGRAM</g-link>
				</div>
				<div class="flex-item-left2">
					<g-link to="/">BLOG</g-link>
				</div>
			</div>
			<div class="flex-container2">
				<div class="flex-item-right1">
					<g-link to="/">NEWSLETTER</g-link>
				</div>
				<div class="flex-item-right2">
					COPYRIGHT 2020
				</div>
			</div>
		</div>
		</footer></div>

</template>

<script>
export default {
  components: {
        name: 'footer'}
        }
</script>

<style>
* {
  box-sizing: border-box;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* On screens that are 992px wide or less, go from four columns to two columns */
@media screen and (max-width: 992px) {
  .column {
    width: 50%;
  }
}

/* On screens that are 600px wide or less, make the columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
