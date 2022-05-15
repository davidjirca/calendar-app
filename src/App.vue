<template>
  <Header />
      <div class="w-auto flex">
        <Calendar />
      </div>
</template>

<script>
import Calendar from "./components/Calendar";
import Header from "./components/Header";

export default {
  // eslint-disable-next-line vue/no-unused-components
  components: { Calendar, Header },

}
</script>

<style>

</style>
