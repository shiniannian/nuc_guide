<template>
	<view>
		<view class="banner">
			<image class="banner-img" src="../../../static/iocn/news-detail2.jpg"></image>
			<view class="banner-title">我校与大同市新荣区签署省校合作框架协议</view>
		</view>
		<view class="article-meta">
			<text class="article-author">所念皆星河</text>
			<text class="article-text">发表于：</text>
			<text class="article-time">2021年08月06日</text>
		</view>
		<view class="article-content">
			<text>
				8月4日，我校与大同市新荣区深化省校合作共建“12大基地”签约仪式在云冈建国宾馆举行。此次合作签约，既是落实省委、省政府关于“深化省校合作、共建12大基地”部署要求，也是双方深化合作、共谋发展的重要成果，开启了双方深化合作、互利互惠、共谋发展的新篇章。校长熊继军，大同市委常委、组织部部长崔巍，市政府副市长马安全，市政府秘书长庞君，大同市新荣区委书记邓志蓉等见签，我校副校长苏铁熊、新荣区委常委、副区长刘玉巍代表双方签署省校合作框架协议。
			</text>
		</view>
	</view>
</template>

<script>

</script>

<style>
    .banner {
		height: 360rpx;
		overflow: hidden;
		position: relative;
		background-color: #ccc;
	}

	.banner-img {
		width: 100%;
	}

	.banner-title {
		max-height: 84rpx;
		overflow: hidden;
		position: absolute;
		left: 30rpx;
		bottom: 30rpx;
		width: 90%;
		font-size: 32rpx;
		font-weight: 400;
		line-height: 42rpx;
		color: white;
		z-index: 11;
	}

	.article-meta {
		padding: 20rpx 40rpx;
		display: flex;
		flex-direction: row;
		justify-content: flex-start;
		color: gray;
	}

	.article-text {
		font-size: 26rpx;
		line-height: 50rpx;
		margin: 0 20rpx;
	}

	.article-author,
	.article-time {
		font-size: 30rpx;
	}

	.article-content {
		padding: 0 30rpx;
		overflow: hidden;
		font-size: 30rpx;
		margin-bottom: 30rpx;
	}
</style>
