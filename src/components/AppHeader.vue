<script>
export default{
    name:"AppHeader",
    data (){
        return{
            links:[
                {
                    nome:"HARACTERS",
                    link:"#",
                    active: false
                },
                {
                    nome:"COMICS",
                    link:"#",
                    active: true
                },
                {
                    nome:"MOVIES",
                    link:"#",
                    active: false
                },
                {
                    nome:"TV",
                    link:"#",
                    active: false
                },
                {
                    nome:"GAMES",
                    link:"#",
                    active: false
                },
                {
                    nome:"COLLECTIBLES",
                    link:"#",
                    active: false
                },
                {
                    nome:"VIDEOS",
                    link:"#",
                    active: false
                },
                {
                    nome:"FANS",
                    link:"#",
                    active: false
                },
                {
                    nome:"NEWS",
                    link:"#",
                    active: false
                },
                {
                    nome:"SHOP",
                    link:"#",
                    active: false
                },
            ]
        }
    },
    methods:{
        addClass (link){
            return link.classList.add("active");

        }
    }
    
}
</script>

<template>
    <header>
        <div class="container">
            <div class="img">
                <img src="../assets/img/dc-logo.png" alt="">

            </div>

            <div >
                <ul>
                    <li v-for="link in links" >
                        <a :href="link.link" :class="{
                            active: link.active
                        }">{{link.nome}}</a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use "../styles/partials/mixins.scss" as *;
    .container {
        
        img{    
            padding: 20px 0;  
        }
        ul{
        display: flex;
        list-style: none;
        flex-wrap: wrap;
        li{
            @include listyle(5px);
             
            a{
                @include astyle(black);
                font-weight: bold;
                &.active{
                border-bottom: 4px solid  #0282f9;
                color: #0282f9;
             }
            }

        }
    }
    }
    
    
</style>