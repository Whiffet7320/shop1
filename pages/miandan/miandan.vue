<template>
	<view class="index">
		<view class="banner">
			<!-- <u-icon name="arrow-left" color="#2979ff" size="28"></u-icon>
			123 -->
			<image src="../../static/hongbaobanner.png" class="nav-banner"></image>
			<image src="../../static/fanhui.png" class="fanhui"></image>
		</view>
		<view class="center">
			<image src="../../static/矩形147.png" class="juxin"></image>
			<image src="../../static/Group.png" class="pic"></image>
			<text class="tit1">周州粥发出的红包</text>
			<text class="tit2">恭喜发财，大吉大利</text>
			<text class="tit3">0.04元</text>
			<text class="tit4">已存入余额，可直接提现></text>
		</view>
		<view class="footer">
			<view class="tit1">领取5/5个</view>
			<view class="items">
				<view class="item">
					<view class="pic">
						<image src="../../static/Group1.png" mode=""></image>
					</view>
					<view class="tit">
						<view class="tit1">
							JAY Jone
						</view>
						<view class="tit2">
							13:28
						</view>
					</view>
					<view class="tit3">
						0.04元
					</view>
					<view class="mian">
						<image src="../../static/免.png"></image>
					</view>
				</view>
				<view class="item">

				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		// created() {
		// 	console.log(uni.upx2px(750 / 414) + 'px')
		// },
		methods: {

		}
	}
</script>

<style scoped lang="scss">
	.index {
		.banner {
			width: calc(1.82 * 414rpx);
			height: calc(1.82 * 172rpx);
			opacity: 1;
			position: relative;

			.nav-banner {
				width: 100%;
				height: 100%;
				position: absolute;
			}

			.fanhui {
				height: calc(1.82 * 18rpx);
				width: calc(1.82 * 11rpx);
				margin-top: calc(1.82 * 48rpx);
				margin-left: calc(1.82 * 27rpx);
				opacity: 1;
			}
		}

		.center {
			position: relative;
			margin-top: calc(-1.82 * 33rpx);

			.juxin {
				left: 50%;
				transform: translateX(-50%);
				// margin-top: calc(-1.82 * 33rpx);
				position: absolute;
				top: 0;
				width: calc(1.82 * 380rpx);
				height: calc(1.82 * 233rpx);
				opacity: 1;
			}

			.pic {
				position: absolute;
				top: calc(1.82 * 22rpx);
				left: calc(1.82 * 193rpx);
				width: calc(1.82 * 29rpx);
				height: calc(1.82 * 29rpx);
				opacity: 1;
			}

			.tit1 {
				position: absolute;
				top: calc(1.82 * 61rpx);
				left: 50%;
				transform: translateX(-50%);
				opacity: 1;
				font-size: calc(1.82 * 19rpx);
				font-family: PingFang SC, PingFang SC-Bold;
				font-weight: 700;
				text-align: left;
				color: #121314;
				line-height: calc(1.82 * 42rpx);
				letter-spacing: 1.82px;
			}

			.tit2 {
				position: absolute;
				top: calc(1.82 * 101rpx);
				left: 50%;
				transform: translateX(-50%);
				opacity: 1;
				font-size: calc(1.82 *10rpx);
				font-family: SourceHanSansCN-Regular;
				color: #9b9b9b;
				line-height: calc(1.82 * 17rpx);
				letter-spacing: 0px;
			}

			.tit3 {
				position: absolute;
				top: calc(1.82 * 127rpx);
				left: 50%;
				transform: translateX(-50%);
				opacity: 1;
				font-size: calc(1.82 * 42rpx);
				font-family: SourceHanSansCN-Regular;
				text-align: center;
				color: #af0000;
				line-height: calc(1.82 * 36rpx);
				letter-spacing: 0px;
			}

			.tit4 {
				position: absolute;
				top: calc(1.82 * 179rpx);
				left: 50%;
				transform: translateX(-50%);
				opacity: 1;
				font-size: calc(1.82 *10rpx);
				font-family: SourceHanSansCN-Regular;
				text-align: center;
				color: #af0000;
				line-height: calc(1.82 *17rpx);
				letter-spacing: 0px;
			}
		}

		.footer {
			margin-left: 50%;
			transform: translateX(-50%);
			margin-top: calc(1.82 * 233rpx);
			// border: 1px solid red;
			width: calc(1.82 * 374rpx);
			height: calc(1.82 * 458rpx);
			opacity: 1;
			background: #ffffff;
			border-radius: calc(1.82 * 20rpx);
			box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.16);
			display: inline-block; //解决margin塌陷

			.tit1 {
				opacity: 1;
				margin-top: calc(1.82 * 15rpx);
				margin-left: calc(1.82 * 23rpx);
				font-size: calc(1.82 *10rpx);
				font-family: SourceHanSansCN-Regular;
				color: #9b9b9b;
				line-height: calc(1.82 *17rpx);
				letter-spacing: 0px;
			}

			.items {
				margin-top: calc(1.82 * 11rpx);

				.item {
					margin: 0 calc(1.82 * 23rpx);
					display: flex;
					align-items: center;
					border: 1px solid red;
					height: calc(1.82 * 53rpx);

					.pic {
						width: calc(1.82 * 33rpx);
						height: calc(1.82 * 33rpx);
						opacity: 1;

						image {
							height: 100%;
							width: 100%;
						}
					}

					.tit {
						display: flex;
						flex-direction: column;
						// justify-content: center;
						align-items: center;
						transform: translateY(-12rpx);

						.tit1 {
							opacity: 1;
							font-size: calc(1.82 * 10rpx);
							font-family: SourceHanSansCN-Regular;
							text-align: center;
							color: #000000;
							line-height: calc(1.82 * 17rpx);
							letter-spacing: 0px;
						}

						.tit2 {
							opacity: 1;
							font-size: calc(1.82 * 10rpx);
							font-family: SourceHanSansCN-Regular;
							text-align: center;
							color: #9b9b9b;
							line-height: calc(1.82 * 17rpx);
							letter-spacing: 0px;
						}
					}
					.tit3{
						opacity: 1;
						margin-left: calc(1.82 * 150rpx);
						font-size: calc(1.82 * 10rpx);
						font-family: SourceHanSansCN-Regular;
						text-align: right;
						color: #000000;
						line-height: calc(1.82 * 17rpx);
						letter-spacing: 0px;
					}
					.mian{
						width: calc(1.82 * 54rpx);
						height: calc(1.82 * 54rpx);
						opacity: 1;
						image{
							width: 100%;
							height: 100%;
						}
					}
				}
			}
		}
	}
</style>
