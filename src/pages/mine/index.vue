<template>
  <view class="mine-container">
    <view class="mine-header">
      <view>1</view>
    </view>
    <view class="mine-order" />
    <view class="navigate-cell-container" />
  </view>
</template>

<script>
export default {
  data() {
    return {}
  },
  onLoad() { },
  methods: {}
}
</script>

<style lang="scss" scoped>
page {
  background: url("../../static/mine/bg-mine.png");
  background-repeat: no-repeat;
  background-size: 100% auto;
}

.mine-header {
  margin: 50rpx 0 0 0;
  padding: 0 20rpx;
  height: 200rpx;
  background-color: aquamarine;
}
</style>
