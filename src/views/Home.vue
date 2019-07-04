<template>
  <div class="home">
    <button>{{messgae}}</button>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
export default class Home extends Vue {
  public messgae = '防抖测试';
  // timer = 0;

  // // 立即执行
  // public debounce (func:Function, delay:number) {
  //   const timeout:any = '';
  //   return function () {
  //     // const context:any = this;
  //     const args = arguments;
  //     callNow = !timeout;
  //   }
  // }
}
</script>
