<template>
  <Calendar
  backgroundText
  class-name="select-mode"
  :remarks="remarks"
/>
</template>

<script>
  import { ref } from 'vue'
  import Calendar from 'mpvue-calendar'

  export default {
    components: {
      Calendar,
    },
    setup() {
      const remarks = ref({'2021-12-30': 'some tings'})

      return {
        remarks,
      }
    }
  }
</script>
