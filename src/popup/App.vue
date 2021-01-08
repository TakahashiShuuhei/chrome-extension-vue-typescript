<template>
  <div>
    <h1>This Is Popup! {{ now }} </h1>
  </div>
</template>

<script lang="ts">
export default {
  computed: {
    now: () => {
      return new Date();
    }
  }
}
</script>