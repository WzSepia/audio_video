<template>
  <div class="hello">
		<ul>
			<li>
					<a>lvhaha</a>
					<video width="320" height="240" controls>
						<source src="../../resource/513a92358cf0238b597b90e812bc6853.mp4" type="video/mp4"></source>
						您的浏览器不支持 vedio 元素。
					</video>
			</li>
		</ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to My Form.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
