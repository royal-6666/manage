<template>
	<div>
		<el-menu  default-active="2" router class="el-menu-vertical-demo" background-color="#545c64"
		 text-color="#fff" active-text-color="#ffd04b">
			<el-submenu index="1">
				<template slot="title">
					<i class="el-icon-goods"></i>
					<span>商品管理</span>
				</template>
				<el-menu-item index="/goods/category">商品分类</el-menu-item>
				<el-menu-item index="/goods/release">发布商品</el-menu-item>
				<el-menu-item index="/goods/list">商品列表</el-menu-item>
			</el-submenu>
			<el-submenu index="2">
				<template slot="title">
					<i class="el-icon-files"></i>
					<span>订单管理</span>
				</template>
				<el-menu-item index="/order/list">订单列表</el-menu-item>
			</el-submenu>
			<el-submenu index="3">
				<template slot="title">
					<i class="el-icon-s-tools"></i>
					<span>账户设置</span>
				</template>
				<el-menu-item index="/user/info">账户信息</el-menu-item>
			</el-submenu>
			<el-submenu index="4">
				<template slot="title">
					<i class="el-icon-user"></i>
					<span>用户管理</span>
				</template>
				<el-menu-item index="/user/list">用户列表</el-menu-item>
			</el-submenu>
			<el-submenu index="5">
				<template slot="title">
					<i class="el-icon-set-up"></i>
					<span>权限设置</span>
				</template>
				<el-menu-item index="/auth/role">用户角色</el-menu-item>
				<el-menu-item index="/auth/menu">菜单权限</el-menu-item>
			</el-submenu>
		</el-menu>
	</div>
	
</template>

<script>
	export default {
		
	}
</script>

<style>
	.el-menu-vertical-demo{
		height: calc(100vh - 60px);
	}
	.el-aside{
		width: 200px!important;
		
	}
	
</style>
