<template>
	<div class="leftnav">
		<ul>
			 <li>
	            <i class="icon iconfont icon-zhuanzhang"></i>
	            <div>收银</div>
	        </li> 
	        <li>
	            <i class="icon iconfont icon-shouye2"></i>
	            <div>店铺</div>
	        </li>
	 
	        <li>
	            <i class="icon iconfont icon-shouye3"></i>
	            <div>商品</div>
	        </li>
	 
	         <li>
	            <i class="icon iconfont icon-shouye1"></i>
	            <div>会员</div>
	        </li>
	 
	 
	        <li>
	            <i class="icon iconfont icon-caiwu"></i>
	            <div>统计</div>
	        </li>
		</ul>
	</div>
</template>

<script>
	export default ({
		name: 'leftnav'
	})
</script>

<style>
	*{margin: 0;padding: 0;}
	.leftnav{
       color:#fff;
       font-size:10px;
       height:100%;
       background-color: #1D8ce0;
       float:left;
       width:5%;
    }
    .iconfont{
       font-size:24px;
    }
    .leftnav ul{
        padding:0px;
        margin: 0px;
    }
    .leftnav li{
        list-style: none;
        text-align: center;
        border-bottom:1px solid #EFF2F7;
        padding:10px;
    }
</style>