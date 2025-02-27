<template>
  <div class="text-2xl" v-if="visible">Hello {{name}}</div>
</template>

<script>
export default {
  data:()=>({
    visible:false,
    name:''
  }),
}
</script>

<style>

</style>