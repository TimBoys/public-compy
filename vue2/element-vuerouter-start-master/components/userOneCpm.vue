<template>
	<div id="firstCpm">
		<p>{{title}}</p>
<el-breadcrumb separator="/">
  <el-breadcrumb-item :to="{ path: '/' }">用户1管理</el-breadcrumb-item>
  <el-breadcrumb-item>活动管理</el-breadcrumb-item>
  <el-breadcrumb-item>活动列表</el-breadcrumb-item>
  <el-breadcrumb-item>活动详情</el-breadcrumb-item>
</el-breadcrumb>		
		
	</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{
				title:"userOneCpm"
			}
		},
		computed:{
			myTitle(){
				return this.title + this.data;
			}
		}
	}
</script>

<style type="text/css">
	
	
	
</style>