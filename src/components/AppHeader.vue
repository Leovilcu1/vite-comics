<script>
export default{
    name:"AppHeader"
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
                    <li>
                        <a href="#">CHARACTERS</a>
                    </li>

                    <li>
                        <a href="#">COMICS</a>
                    </li>

                    <li>
                        <a href="#">MOOVIES</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a class="active" href="#">GAMES</a>
                    </li>
                    <li>
                        <a href="#">COLLECTIBLES</a>
                    </li>
                    <li>
                        <a href="#">VIDEOS</a>
                    </li>
                    <li>
                        <a href="#">FANS</a>
                    </li>
                    <li>
                        <a href="#">NEWS</a>
                    </li>
                    <li>
                        <a href="#">SHOP</a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        img{    
            padding: 20px 0; 
        }
        ul{
        display: flex;
        list-style: none;
        flex-wrap: wrap;
        li{
            padding: 5px;
             
            a{
                text-decoration: none;
                color: black;
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