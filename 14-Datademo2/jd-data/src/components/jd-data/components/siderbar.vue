<template>
  <div class="block">
    <el-slider
      v-model="value"
      range
      show-stops
      :max="2022"
      :min="2013" 
      :marks="marks"
      >
    </el-slider>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        value: [2019, 2020],
        marks:{
            2014: '2014 年',
            2015: '2015 年',
            2016: '2016 年',
            2017: '2017 年',
            2018: '2018 年',
            2019: '2019 年',
            2020: '2020 年',
            2021: '2021 年',
        }
      }
    }
  }
</script>