<template>
	<div id="app">
		<audio controls>
			<source src="../resource/shaolinyingxiong.mp3" />
			您的浏览器不支持 audio 元素。
		</audio>
		<video width="320" height="240" controls>
			<source src="../resource/513a92358cf0238b597b90e812bc6853.mp4" type="video/mp4"></source>
			您的浏览器不支持 vedio 元素。
		</video>
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
