<template>
  <div id="app">
	<v-card id="card-1">
		<v-img 
			src="https://static.boredpanda.com/blog/wp-content/uploads/2018/04/5acb63d83493f__700-png.jpg"
			aspect-ratio="1.75"
		></v-img>
		<v-card-title primary-title>
			<div>
				<h2>Cat Picture 1</h2>
				<h3>Two funny cats</h3>
			</div>
		</v-card-title>
		<v-card-actions>
			<v-btn color="red">Like</v-btn>
		</v-card-actions>
	</v-card>
	<v-card id="card-2">
		<v-img 
			src="http://www.catster.com/wp-content/uploads/2017/08/A-fluffy-cat-looking-funny-surprised-or-concerned.jpg"
			aspect-ratio="1.75"
		></v-img>
		<v-card-title primary-title>
			<div>
				<h2>Cat Picture 2</h2>
				<h3>A confused cat</h3>
			</div>
		</v-card-title>
		<v-card-actions>
			<v-btn color="red">Like</v-btn>
		</v-card-actions>
	</v-card>
  </div>
</template>

<script>
export default {
	name: 'app'
};
</script>

<style>
#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	grid-column-gap: 10px;
}

#card-1 {
	grid-column: 2 / 3;
}

#card-2 {
	grid-column: 3 / 4;
}
</style>
