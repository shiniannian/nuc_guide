<template>
	<view>
		<view class="banner">
			<image class="banner-img" src="../../../static/iocn/news-detail3.jpg"></image>
			<view class="banner-title">金奖及奖牌总数居首位！我校在第七届山西省“互联网+”大学生创新创业大赛获佳绩</view>
		</view>
		<view class="article-meta">
			<text class="article-author">所念皆星河</text>
			<text class="article-text">发表于：</text>
			<text class="article-time">2021年08月04日</text>
		</view>
		<view class="article-content">
			<text>
				7月27日，第七届中国国际“互联网+”大学生创新创业大赛省赛在太原理工大学举行。全省高教主赛道共有207个项目入围决赛，我校入围项目数达48项位列全省第一。最终获得省级金奖22项、银奖26项，金奖及奖牌总数居山西省首位。在冠亚军争夺赛中，我校“星海航天”项目团队获得亚军。同时学校获优秀组织奖。
				“互联网+”创新创业大赛由教育部和政府、地方高校共同主办，是目前我国高等教育领域含金量最高的大学生学科竞赛之一。本届大赛于3月份启动，我校参赛项目达1044项，参赛学生达9859人次，参赛学生比例达29%。参赛项目数量及参与人数创历史新高，在省内名列前茅。
				为全面提升师生创新创业能力，我校以大赛为契机，成立了中北大学第二届创新创业学生精英班，举办了创新创业沙龙活动，进行了创新创业学生及老师的培训，营造了良好的创新创业氛围，真正做到以赛促教、以赛促学、以赛促改。
				预祝我校学子在即将到来的国赛中取得优异成绩。
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
