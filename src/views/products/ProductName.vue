<template>
  <h1>Product name :{{name}}</h1>
</template>

<script>
export default {
    data(){
        return {
            name:this.$route.params.productName
        }
    }

}
</script>

<style>

</style>