<template>
	<div class="pos"> 
		<el-row>
			<el-col :span="7">
				 <div class="hei order-list">24</div>
			</el-col>
			<el-col :span="17">
				<div class="hei project-list">24</div>
			</el-col> 
		</el-row> 
	</div>
</template>

<script>
	export default({
		name:'pos',
		mounted:function(){
			var orderListHeight = document.body.clientHeight;
			var hei = document.getElementsByClassName('hei');
			for(var i = 0;i < hei.length;i++){
				hei[i].style.height = orderListHeight+'px';
			} 
		}
	});
</script>

<style scoped>
	.pos{overflow: hidden;}
	.hei{width: 100%; background: #ddd;border: 1px solid red;} 
</style>