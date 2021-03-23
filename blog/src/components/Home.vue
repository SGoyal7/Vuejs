<template>
	<div>
		<h1>Hello from Home component</h1>
		<h1>{{ data }}</h1>
		<h1>{{ msg }}</h1>
		<button v-on:click="hello('data')">Call Hello Function</button>
	</div>
</template>

<script>
export default {
	name: "Home",
	props: {
		data: String,
		msg: String,
	},
};
</script>
