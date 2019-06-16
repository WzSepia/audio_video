<template>
  <div class="hello">
		<ul>
			<li>
				<a href="https://www.baidu.com">One,One,One,One.</a>
				<video width="320" height="240" controls>
					<source src="../../resource/d16437f1eaecb6434cc482643a154d12.mp4" type="video/mp4"></source>
					您的浏览器不支持 vedio 元素。
				</video>
			</li>
		</ul>
  </div>
</template>

<script>
export default {
  name: 'One',
  data () {
    return {
      msg: 'One.'
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
a {
  color: #42b983;
}
</style>
