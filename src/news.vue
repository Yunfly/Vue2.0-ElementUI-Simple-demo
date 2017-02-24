<template>
	<div>
		<h1>我是新闻</h1>
		<ul>
			<li v-for='(val,index) in news'>
				{{index+1}}:{{val}}
			</li>
		</ul>
	</div>
</template>

<script>
	export default{
		name:'news',
		data(){
			return{
				news:['123123','123123','asdasd']
			}
		}
	}
</script>