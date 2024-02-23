<script setup>
</script>

<template>
 
  <svg  ref="smithChart" class="svg" view-box="0 0 100% 100%">
   
    <text x="50%" y="50.5%" fill="black">1</text>
    <text x="83.34%" y="50.5%" fill="black">5</text>
    <text x="66.67%" y="50.5%" fill="black">2</text>
    <text x="33.33%" y="50.5%" fill="black">0.5</text>
    <text x="16.66%" y="50.5%" fill="black">0.2</text>
    <text x="0.2%" y="50.5%" fill="black">0</text>
    <circle class="axis circle" r="8.33%" cx="91.67%" cy="50%" />
    <circle class="axis circle" r="16.66%" cx="83.34%" cy="50%" />
    <circle class="axis circle" r="25%" cx="75%" cy="50%" />
    <circle class="axis circle" r="33.33%" cx="66.67%" cy="50%" />
    <circle class="axis circle" r="41.66%" cx="58.34%" cy="50%" />
    <circle class="axis circle" r="50%" cx="50%" cy="50%" />

    <circle class="mirror-translate-2 circle axis" r="200%" cx="100%" cy="250%" stroke="purple" />
    <circle class="circle axis" r="200%" cx="100%" cy="250%" stroke="purple" />
    <circle class=" circle mirror-translate axis" r="100%" cx="100%" cy="150%" stroke="purple" />
    <circle class="circle axis" r="100%" cx="100%" cy="150%" stroke="purple" />
    <circle class="axis circle" r="50%" cx="100%" cy="0%" stroke="purple" />
    <circle class="axis circle" r="50%" cx="100%" cy="100%" stroke="purple" />
    <circle class="axis circle" r="25%" cx="100%" cy="75%" stroke="purple" />
    <circle class="axis circle" r="25%" cx="100%" cy="25%" stroke="purple" />
    <circle class="axis circle" r="12.5%" cx="100%" cy="37.5%" stroke="purple" />
    <circle class="axis circle" r="12.5%" cx="100%" cy="62.5%" stroke="purple" />

    <line class="axis line" x1="0" y1="50%" x2="100%" y2="50%" stroke="black" />

  </svg>
</template>

<style scoped>
.svg {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 12px;
  border: solid 1px rgb(0, 0, 0, 0.2);
  aspect-ratio: 1/1;
  border-radius:100%;

  /* 
  background-image: radial-gradient(#000000 0.8px, transparent 0.8px);
  background-size: 1% 1%; */
  /*   background-image: linear-gradient(#444cf7 0.4px, transparent 0.4px), linear-gradient(to right, #444cf7 0.4px, transparent 0.4px);
  background-size: 1% 1%;
 */
}

.tint-circle {
  background-color: red;
}

.mirror-translate {
  transform: translateY(-200%);
}

.mirror-translate-2 {
  transform: translateY(-400%);
}

.infinite {
  font-size: 30px !important;
}

.axis {
  opacity: 0.2;
  stroke: black;
  stroke-width: 1px !important;
}

.line {
  opacity: 0.3;
}


.circle {
  height: 100%;
  stroke-width: 2px;
  width: 100%;
  fill: transparent;

}
</style>
