<template>
	<view>
		<view class="banner">
			<image class="banner-img" src="../../../static/iocn/news-detail5.jpg"></image>
			<view class="banner-title">第二十一届全国运动生物力学学术交流大会在我校举办</view>
		</view>
		<view class="article-meta">
			<text class="article-author">所念皆星河</text>
			<text class="article-text">发表于：</text>
			<text class="article-time">2021年08月05日</text>
		</view>
		<view class="article-content">
			<text>
				7月27-28日，第二十一届全国运动生物力学学术交流大会在我校举行。本次大会由中国体育科学学会运动生物力学分会主办、我校承办、北华博鳌体育投资（北京）有限公司协办。来自美国北卡罗来纳大学、英国拉夫堡大学、台湾师范大学、国家体育总局体育科学研究所、北京体育大学、上海体育学院等50余所国内外高校及科研院所的300余位专家、学者汇聚一堂，共同呈现了一场精彩的学术盛宴。
				
				我校副校长曾建潮出席开幕式并致欢迎词。中国体育科学学会运动生物力学分会主任委员王清代表分会致辞。山西省体育局科技教育处处长侯冰、我校科学技术研究院常务副院长桂志国等出席开幕式。大会主席、我校体育学院院长曹电康教授主持开幕式。
				
				本届大会共收录论文420余篇，创历届之最。美国北卡罗来纳大学于冰教授等10位专家做主题报告。举办专题分会场报告133场，墙报交流论文298篇。大会聚焦近年来奥运冠军运动模型、足踝扭伤的损伤机制及预防方法、惯性动作捕捉技术、特殊环境下人体运动、大数据与人工智能在运动生物力学中的应用、可穿戴设备在人体运动测量中的应用、运动生物力学对竞技运动水平的提升、运动生物力学在运动损伤和大众健身中的应用等热点问题，并进行了交流讨论。会议期间，诸多相关参展企业还展示了运动生物力学领域的先进仪器设备。
				
				本次学术交流大会加强了运动生物力学领域的学者、研究人员的深层次交流，促进了运动生物力学在人工智能、工程技术方面发挥更大的作用，为新形势下学科交叉与合作研究提供了平台。
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
