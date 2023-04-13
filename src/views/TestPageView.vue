<template>
  <div class="about">
    <h1>測試 ga4 pageview</h1>
    <button>測試用Click</button>
  </div>
</template>
<script>
export default {
    mounted(){
        console.log('test')
        this.$gtag.pageview("/about");
    }
}
</script>