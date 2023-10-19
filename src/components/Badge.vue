<script setup>
 const props = defineProps(['type']);
</script>

<template>
  <span :class="props.type">
    <slot></slot>
  </span>
</template>

<style scoped>
  span {
    font-weight: bold;
    display: flex;
    padding: 2px 6px;
    border-radius: 7px;
    transform: skewX(-12deg);
  }

  .classic {
    background: linear-gradient(-20deg, rgba(5, 5, 5, 0.89), #9a9a9a, #fdfdfd)
  }

  .bronze {
    background: linear-gradient(-20deg, #7c5e31, #de8859, #d79c61)
  }

  .silver {
    background: linear-gradient(-20deg, #3e5359, #6e8496, #b1deee)
  }

  .gold {
    background: linear-gradient(-20deg, #776005, #f6b125, #eee15a)
  }

  .platinum {
    background: linear-gradient(-20deg, #113659, #3195be, #0ae7c6)
  }

  .diamond {
    background: linear-gradient(-20deg, #3f1159, #9b31be, #ca0ae7)
  }

  .funk-1 {
    background: linear-gradient(-20deg, #e1d49e, #94e8c2, #d39ade);
    color: #1a1a1a;
  }
</style>