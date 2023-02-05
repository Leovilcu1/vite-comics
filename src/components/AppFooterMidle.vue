<script>
// import { url } from 'inspector';

export default{
    name: "AppFooterMidle",
    data(){
        return{
            dCComics:[
                {
                    nome:"Characters",
                    url:"#"
                },
                {
                    nome:"Comics",
                    url:"#"
                },
                {
                    nome:"Movies",
                    url:"#"
                },
                {
                    nome:"TV",
                    url:"#"
                },
                {
                    nome:"Games",
                    url:"#"
                },
                {
                    nome:"Videos",
                    url:"#"
                },
                {
                    nome:"News",
                    url:"#"
                },
            ],
            shop:[
                {
                    nome:"Shop DC",
                    url:"#"
                },
                {
                    nome:"Shop DC Collectibles",
                    url:"#"
                }
            ],
            dc:[
                {
                    nome:"Terms Of Use",
                    url:"#"
                },
                {
                    nome:"Privacy policy (New)",
                    url:"#"
                },
                {
                    nome:"Ad Choices",
                    url:"#"
                },
                {
                    nome:"Advertising",
                    url:"#"
                },
                {
                    nome:"Jobs",
                    url:"#"
                },
                {
                    nome:"Subscription",
                    url:"#"
                },
                {
                    nome:"Talent Workshops",
                    url:"#"
                },
                {
                    nome:"CPSC Certificates",
                    url:"#"
                },
                {
                    nome:"Ratings",
                    url:"#"
                },
                {
                    nome:"Shop Help",
                    url:"#"
                },
                {
                    nome:"Contact Us",
                    url:"#"
                },
            ],
            site:[
                {
                    nome:"DC",
                    url:"#"
                },
                {
                    nome:"MAD Magazine",
                    url:"#"
                },
                {
                    nome:"DC Kids",
                    url:"#"
                },
                {
                    nome:"DC Universe",
                    url:"#"
                },
                {
                    nome:"DC Power Visa",
                    url:"#"
                },
            ]


        }
    }
}
</script>

<template>
    <div class="middle">
        <div class="container">
            <div class="slides">
                <div class="slide">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li v-for="link in dCComics">
                            <a :href="link.url">{{link.nome}}</a>
                        </li>
                        
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li v-for="link in shop">
                            <a :href="link.url">{{ link.nome }}</a>
                        </li>
                        
                    </ul>
                </div>

                <div class="slide">
                    <h3>DC</h3>
                    <ul>
                        <li v-for="link in dc">
                            <a :href="link.url">{{link.nome}}</a>
                        </li>
                       
                    </ul>
                </div>
                <div class="slide">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li v-for="link in site">
                            <a :href="link.url">{{link.nome}}</a>
                        </li>
                        
                    </ul>
                </div>
            </div>

            
        </div>
    </div>
       
</template>

<style lang="scss" scoped>
  @use "../styles/partials/mixins.scss" as *;
    .middle{
        height: 400px;
    }
    .container{
        .slides{
            display: flex;
            .slide {
                padding: 10px;
                h3{
                    color: white;
                }
                ul {
                    padding: 0;
                    li{
                        @include listyle ( 3px 0);

                        a{
                            @include astyle (gray);
                        }
                    }
                    
                }
            }
        }
        
        
    }
    
   
    
    
</style>