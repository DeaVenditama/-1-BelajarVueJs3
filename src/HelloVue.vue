<template>
    <h1>Hello World</h1>
    <h4>Project Vue Pertama Saya</h4>
    <h4>Nama Saya {{ nama }}</h4>
    <h4>Umur Saya {{ umur }} tahun</h4>
</template>

<script>
export default {
    data(){
        return{
            nama : "Dea Venditama",
            umur : 17   
        }
    },
    mounted(){
        this.umur = this.umur + 3;        
    }
}
</script>

<style scoped>

</style>