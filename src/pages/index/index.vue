<template>
	<view class="content">
        <image class="logo" src="../../static/logo.png"></image>
		<view>
            <div class="title">{{title}}</div>
            <text class="title">{{title}}</text>
            <div class="title">{{title}}</div>
            <text class="title">{{title}}</text>
        </view>
	</view>
</template>

<script lang="ts">
import { Component, Prop } from 'vue-property-decorator';
import Vue from 'vue';
// import { Getter, State } from 'vuex-class';

@Component
export default class index extends Vue {
	title =  'Hello'
}
</script>
  
<style scoped>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
