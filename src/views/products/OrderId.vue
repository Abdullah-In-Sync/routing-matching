<template>
  <h1>Product Order No:{{orderNum}}</h1>
</template>

<script>
export default {
data(){
    return{
        orderNum:this.$route.params.orderId
    }
}
}
</script>

<style>

</style>