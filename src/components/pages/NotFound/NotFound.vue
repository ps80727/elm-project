<template>	
	<div  class="not-found">
		<article class="not-found-view">
			<div class="img-box">
				<img src="/static/img/not-found.jpg" width="100%">
			</div>
			<p>这个页面，神秘失踪了。。。</p>
			<p>
				<span>不如</span>
				<router-link to="/home-main">
					返回想吃吗首页
				</router-link>
				<span>吧！</span>
			</p>
		</article>
	</div>
</template>
<script type="text/javascript">
	export default{
		name : 'NotFound'
	}
</script>
<style type="text/css" lang="scss" scoped>
	.not-found{
		article{
			padding-top: 48px;
			display: flex;
			flex-flow: column;
			align-items:center;
			
			.img-box{
				width : 2.31rem; 
				height: 1.58rem; 
				margin-bottom: 10px;  
			}
			p{
				font-size: 16px; 
				color: #666; 
				line-height: 24px; 
				margin: 0 0 8px; 
				a{
					padding: 0 0.2em;
					color: #cb885e; 
					text-decoration: underline;
				}
			}
		}
	}
</style>