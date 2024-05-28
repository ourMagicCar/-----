<template>
	<view class="container">
		<view class="divided"></view><view class="divided"></view><view class="divided"></view>
		<view class="card">
			<view class="logo">
				<img src="/static/driver.png" class="png">
			</view>
			<view class="list">
				<text class="info">我是司机，进入</text>
				<button class="driver">司机入口</button>
			</view>
		</view>
		<view class="dividedLine"></view>
		<view class="card">
			<view class="logo">
				<img src="/static/dispatcher.png" class="png">
			</view>
			<view class="list">
				<text class="info">我是调度员，进入</text>
				<button class="dispatcher">班次管理页</button>
			</view>
		</view>
		<view class="dividedLine"></view>
		<view class="card">
			<view class="logo">
				<img src="/static/manger.png" class="png">
			</view>
			<view class="list">
				<text class="info">我是经理，进入</text>
				<button class="manger">基础管理页</button>
				<button class="manger">规则管理页</button>
				<button class="manger">查询统计页</button>
			</view>
		</view>
	</view>
</template>



<style>
	.container{
		height: 100%;
		justify-content: center;
		background: linear-gradient(to bottom, #829BF7, #FEFEFE);
		display: flex;
		flex-direction: column;
	}
	.divided{
		height: 20px;
	}
	.dividedLine{
		height: 2px;
		width: 95%;
		background-color: #B8C0D7;
		margin-top: 40px;
		margin-bottom: 40px;
	}
	.card{
		display: flex;
	}
	.list{
		display: flex;
		flex-direction: column;
	}
	.logo{
		display: flex;
		justify-content: center; 
		width: 35%;
	}
	.png{
		width: 60px;
		height: 65px;
	}
	.info{
		display: flex;
		width: 150%;
		font-size: 20px;
		font-weight: 700;
		margin-bottom: 10px;
	}
	.driver{
		display: grid;
		place-items: center; 
		background-color: #4095E5;
		color: #FEFEFE;
		font-weight: 900;
		height: 40px;
		width: 200px;
		margin-bottom: 10px;
		border-radius: 8px;
		border: 2px solid #C7C9CB; 
	}
	.dispatcher{
		display: grid;
		place-items: center; 
		background-color: #BD3124;
		color: #FEFEFE;
		font-weight: 900;
		height: 40px;
		width: 200px;
		margin-bottom: 10px;
		border-radius: 8px;
		border: 2px solid #C7C9CB; 
	}
	.manger{
		display: grid;
		place-items: center; 
		background-color: #81B337;
		color: #FEFEFE;
		font-weight: 900;
		height: 40px;
		width: 200px;
		margin-bottom: 10px;
		border-radius: 8px;
		border: 2px solid #C7C9CB; 
	}
</style>
