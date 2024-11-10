<template>
	<view class="out">
		<image src="../../static/images/pic3.jpg" mode="" class="myimg"></image>
		<image src="../../static/images/pic1.jpg" mode="heightFix"></image>
		<view class="box"></view>
		<view class="block"></view>
		<icon type="success" size="26"/>
		<icon type="waiting" size="26"/>
		<view>uniapp</view>
		<view>web 前端開發</view>
		<text user-select selectable>node.js</text>
		<text space="ensp">vue &nbsp; &lt; &gt; &amp; &apos; &ensp; &emsp;.js</text>
		<scroll-view class="scroll" scroll-x scroll-y>
			<view class="group">
				<view class="item">
					111
				</view>
				<view class="item">
					111
				</view>
				<view class="item">
					111
				</view>
				<view class="item">
					111
				</view>
				<view class="item">
					111
				</view>
			</view>
		</scroll-view>
		
		<swiper class="swiper">
			<swiper-item class="item">111</swiper-item>
			<swiper-item class="item">222</swiper-item>
			<swiper-item class="item">333</swiper-item>
		</swiper>
		<swiper class="swiper" circular autoplay interval="3000" duration="1000"
		 indicator-dots="true" indicator-color="red" indicator-active-color="green">
			<swiper-item class="item">
				<image src="/static/images/pic1.jpg" mode=""></image>
			</swiper-item>
			<swiper-item class="item">
				<image src="/static/images/pic2.jpg" mode=""></image>
			</swiper-item>
			<swiper-item class="item">
				<image src="/static/images/pic3.jpg" mode=""></image>
			</swiper-item>
		</swiper>
	</view>
</template>

<script setup>
	
</script>

<style lang="scss">
	.myimg{
		width: 260rpx;
		height: 360rpx;
	}
	.mypic{

	}
	.out{
		.box{
			width: 200px;
			height: 200px;
			background-color: pink;
		}
		.block{
			width: 750rpx;
			height: 200rpx;
			background-color: green;
		}
	}
	.scroll{
		border: 1px solid red;
		box-sizing: border-box;
		height: 220rpx;
		height: 110rpx;
		.group{
			white-space: nowrap;
			.item{
				width: 220rpx;
				height: 220rpx;
				background-color: royalblue;
				display: inline-block;
				margin-right: 10rpx;
			}
		}
	}
	.swiper{
		.item{
			
		}
	}
</style>
