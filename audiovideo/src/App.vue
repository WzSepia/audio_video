<template>
	<div id="app">
		<img src="./assets/logo.png" />
		<audio controls>
			<source src="../resource/shaolinyingxiong.mp3" />
			您的浏览器不支持 audio 元素。
		</audio>
		<router-view />
	</div>
</template>

<script>
export default {
	name: 'App'
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
}
</style>
