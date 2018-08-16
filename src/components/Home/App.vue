<template>
  <div>
    <Header />
    <DonateNow />
  </div>
</template>

<script>
import Header from './Header';
import DonateNow from './DonateNow';

export default {
  data() {
    return {}
  },

  components: {
    Header,
    DonateNow
  }
}
</script>

<style>
body {
  margin: 0 auto;
}
</style>
