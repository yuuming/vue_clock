<template>
  <div>
    <Clock class="clock" location="TOKYO" :diff="0"/>
    <Clock class="clock" location="Vancouver" :diff="-17"/>
  </div>
</template>

<script>
import Clock from "@/components/Clock";
export default {
  components: {
    Clock
  }
};
</script>

