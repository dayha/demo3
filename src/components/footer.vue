<template>
	<div class="footer fiexd">
		<ul>
			<li><router-link to='/'>首页</router-link></li>
			<li><router-link to='/manage'>我的</router-link></li>
		</ul>
	</div>
</template>
<style scoped>
	li a{
		display:inline-block;width: 100%;height: 100%;
	}
	.footer{
		width: 100%;height:50px;bottom: 0;
	}
	ul{
		display: flex;height: 100%;line-height: 50px;
	}
	ul li{
		flex: 1;background: #f1f1f1;
	}
	.isIndex li:first-child{
		background: #d3d3d3;
	}
	.isIndex li a:first-child{
		color: #41b833;
	}
	.isManage li:first-child{
		background: #d3d3d3;
	}
	.isManage li a:first-child{
		color: #41b833;
	}

</style>