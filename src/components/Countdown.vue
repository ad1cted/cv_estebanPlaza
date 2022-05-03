<template>
  <vue-countdown v-slot="{ days}" :interval="300" :time="time">
    {{$t("message.age")}}：{{ Math.trunc(days / 365) }} {{$t("message.years")}}, {{ Math.trunc(days % 365 / 30) }} {{$t("message.months")}}.
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
