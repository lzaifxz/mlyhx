<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	body{
		background: #F5F5F5;
		font-size: 28rpx;
		line-height: 1.0;
	}
	*{
		box-sizing: border-box;
	}
	uni-page-body{
		height: 100%;
	}
	.content{
		height: 100%;
		overflow: auto;
	}
	.wrap{
		width: 690rpx;
		height: auto;
		padding: 30rpx;
		background: #FFFFFF;
		margin: 30rpx auto;
		border-radius: 10rpx;
		box-shadow: #EEEEEE 10rpx 10rpx 20rpx;
	}
</style>
