<template>
  <div>
    <h1>This Is Devtools! {{ now }} </h1>
  </div>
</template>

<script lang="ts">
export default {
  computed: {
    now: () => {
      const hoge: string = 'abc';
      return new Date() + hoge;
    }
  }
}
</script>