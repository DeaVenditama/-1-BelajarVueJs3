<template>
    <h1>Penggunaan V Model</h1>   
    <h4>{{ messages }}</h4>
    <input v-model="messages" />    
</template>

<script>
export default {
    data(){
        return{
            messages : ''
        }
    }    
}
</script>

<style scoped>

</style>