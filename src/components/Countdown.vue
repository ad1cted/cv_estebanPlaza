<template>
  <vue-countdown v-slot="{ days}" :interval="300000" :time="time">
    Edad：{{ Math.trunc(days / 365) }} Años, {{ Math.trunc(days % 365 / 30) }} Meses.
  </vue-countdown>
</template>

<script>
import VueCountdown from '@chenfengyuan/vue-countdown';

export default {
  data() {


  }, components: {VueCountdown}
};
</script>