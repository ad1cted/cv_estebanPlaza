<template>
  <vue-countdown v-slot="{ days}" :interval="300000" :time="time">
    Edad：{{ Math.trunc(days / 365) }} Años, {{ Math.trunc(days % 365 / 30) }} Meses.
  </vue-countdown>
</template>

<script>
import VueCountdown from '@chenfengyuan/vue-countdown';

export default {
  data() {
    const birth_day = new Date(1994, 3, 1);
    const now = new Date();

    return {
      time: now - birth_day,
    };

  }, components: {VueCountdown}
};
</script>