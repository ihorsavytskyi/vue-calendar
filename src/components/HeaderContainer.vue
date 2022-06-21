<template>
  <header class="v-calendar-header">
    <div class="v-calendar-actions">
        <button class="v-calendar-actions__button" :class="{isActive}">Today</button>
        <button class="v-calendar-actions__button">Back</button>
        <button class="v-calendar-actions__button">Next</button>
    </div>
    <div class="v-calendar-actions">
        <button class="v-calendar-actions__button">Month</button>
        <button class="v-calendar-actions__button">Week</button>
        <button class="v-calendar-actions__button">Day</button>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderContainer',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>