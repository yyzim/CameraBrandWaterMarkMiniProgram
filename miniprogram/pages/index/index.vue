<template>
	<view class="container">
		<view class="item1">
			<image src="../../static/lena.jpg" mode="widthFix"></image>
		</view>
		<view class="item2">
			B
		</view>
		<view class="item3">
			<button class="select" size="mini">选择图片</button>
			<button class="save" size="mini">保存图片</button>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.container {
		display: flex;
		flex-direction: column;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: stretch;

		position: fixed;
		width: 100%;
		height: 100%;
	}

	.item1 {
		flex-grow: 8;
		background-color: red;
		border: 1rpx solid red;
		
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.item2 {
		flex-grow: 2;
		background-color: yellow;
		border: 1rpx solid red;
	}

	.item3 {
		flex-grow: 2;
		background-color: blue;
		border: 1rpx solid red;

		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
	}

	button {}

	image {
		flex-shrink: 0;
		height: 100%;
	}
</style>
