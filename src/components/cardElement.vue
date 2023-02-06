<script>
export default{
    name:"cardElement",
    props:{
        title: String,
        src:String,
        type:String,
    }
}
</script>

<template>
    <div>
        <div>
            <img :src="src" :alt="title">
        </div>
        <div class="info">
            <h3>{{title}}</h3>
            <span>{{type}}</span>
        </div>
                
    </div>
</template>

<style lang="scss" scoped>
.info{
    height: 60px;
}
</style>