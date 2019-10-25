<template>
	<view class="content">
		<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
		    <swiper-item>
		        <image class="swiper-item"  src="../../static/banner/banner101.png"></image>
		    </swiper-item>
		    <swiper-item>
		        <image class="swiper-item"  src="../../static/banner/banner102.png"></image>
		    </swiper-item>
		    <swiper-item>
		        <image class="swiper-item"  src="../../static/banner/banner103.png"></image>
		    </swiper-item>
		</swiper>
		<view class="wrap">
			<view class="classed">
				<view class="classed-left">
					<image class="classed-left-img"  src="../../static/banner/banner101.png"></image>
				</view>
				<view class="classed-right">
					<view class="classed-right-title">
						创业精华班	
					</view>
					<view class="classed-right-con">
						学期：4天3夜 | 开学日期：即日
						起接受报名，可随到随学，也可
						直接参加系统培训班。
					</view>
				</view>
			</view>
			<view class="classed">
				<view class="classed-left">
					<image class="classed-left-img"  src="../../static/banner/banner101.png"></image>
				</view>
				<view class="classed-right">
					<view class="classed-right-title">
						大咖精华班	
					</view>
					<view class="classed-right-con">
						学期：3天2夜 | 开学日期：即日起
					</view>
				</view>
			</view>
			<view class="classed">
				<view class="classed-left">
					<image class="classed-left-img"  src="../../static/banner/banner101.png"></image>
				</view>
				<view class="classed-right">
					<view class="classed-right-title">
						高级开花炫彩密训班	
					</view>
					<view class="classed-right-con">
						学期：3天2夜，学会为止 | 开学日期：提前预约，随到随学
					</view>
				</view>
			</view>
			<text class="more">
				查看更多
			</text>
		</view>
		<view class="wrap">
			<text class="wrap-title">
				作品展示
			</text>
			<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration">
			    <swiper-item>
			        <image class="swiper-item"  src="../../static/banner/banner101.png"></image>
			    </swiper-item>
			    <swiper-item>
			        <image class="swiper-item"  src="../../static/banner/banner102.png"></image>
			    </swiper-item>
			    <swiper-item>
			        <image class="swiper-item"  src="../../static/banner/banner103.png"></image>
			    </swiper-item>
			</swiper>
			<view class="zp-title">
				纹绣
			</view>
			<view class="zp-con">
				纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣纹绣
			</view>
		</view>
		<view class="wrap">
			<text class="wrap-title">
				为什么选择我们
			</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Index',
				background: ['color1', 'color2', 'color3'],
				            indicatorDots: true,
				            autoplay: true,
				            interval: 2000,
				            duration: 500
			}
		},
		onLoad() {

		},
		methods: {
		}
	}
</script>

<style>
	.swiper{
		height: 400rpx;
		width: 100%;
	}
	.swiper-item{
		width: 100%;
		height: 100%;
	}
	.uni-bg-red{
		background: #007AFF;
	}
	.classed{
		border-bottom: 1rpx solid #EEEEEE;
		padding-bottom: 30rpx;
		margin-bottom: 30rpx;
		display: flex;
	}
	.classed-left{
		flex: 1;
	}
	.classed-left-img{
		width: 150rpx;
		height: 150rpx;
	}
	.classed-right{
		flex: 3;
		margin-left: 30rpx;
	}
	.classed-right-title{
		font-size: 32rpx;
		font-weight: 500;
		color: #333333;
		margin-bottom: 20rpx;
	}
	.classed-right-con{
		color: #999999;
		line-height: 1.2;
	}
	.more{
		width: 200rpx;
		height: 60rpx;
		line-height: 60rpx;
		text-align: center;
		border: 1rpx solid #f33;
		border-radius: 10rpx;
		margin: 0rpx auto;
		display: block;
		color: #f33;
	}
	.wrap-title{
		width: 240rpx;
		height: 60rpx;
		line-height: 60rpx;
		text-align: center;
		border-bottom: 1rpx solid #f33;
		margin: 0rpx auto;
		display: block;
		color: #f33;
		margin-bottom: 30rpx;
	}
	.zp-title{
		margin: 20rpx 0rpx;
		font-size: 32rpx;
		font-weight: 500;
		color: #333333;
		border-left: 6rpx solid #FF3333;
		padding-left: 10rpx;
	}
	.zp-con{
		text-indent: 60rpx;
		color: #999999;
		line-height: 1.2;
		height: 120rpx;
	}
</style>
