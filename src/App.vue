<script setup>
import SmithChart from "./components/SmithChart.vue"

</script>

<template>
  <div class="colum">
    <div ref="wrapper" class="wrapper">
      <SmithChart></SmithChart>
    </div>
  </div>
</template>

<style scoped>
.wrapper {

  border-radius: 2rem;
  padding: 1rem;
  display: flex;
  align-items: center;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  justify-content: center;
  width:50%;
  border:solid 1px;

}

.colum {
  height: 100%;
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
}


.wrapper svg {
  width: 100%;
  aspect-ratio:1/1;
}
</style>
