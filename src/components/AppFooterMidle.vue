<script>
export default{
    name: "AppFooterMidle",
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="slides">
                <div class="slide">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <div class="slide">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privasy policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="slide">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Unierse</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
            <div class="jumbotron">
                
            </div>
            <div>
                
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
  
    .container{
        display: flex;
        justify-content:space-between;
        .jumbotron{
            width:50%;
            height: 500px;
            background-image: url(../assets/img/dc-logo-bg.png);
            background-size: contain;
            background-repeat: no-repeat;
            
        }
    }
    .slides{
        display: flex;
        >*{
            padding: 20px;
        }

        h3{
            color: white;
            padding: 20px 0  }
    }
   
    li{
        list-style: none;
        padding: 5px 0;
        
        a{
        text-decoration: none;
        color: #8f8471;
    }
    }
    
</style>