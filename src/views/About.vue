<template>
  <div class="about">
    <div id="chart"></div>
  </div>
</template>

<script>
import china from "../assets/china"

export default {
  data(){
    return{
      option:{}
    }
  },
  mounted(){
    this.$echarts.registerMap('china', china);
  }
}
</script>