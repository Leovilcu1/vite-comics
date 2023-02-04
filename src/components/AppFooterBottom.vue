<script>
export default{
    name: "AppFooterBottom",
}
</script>

<template>
    <div class="footerbottom">
        <div class="container">
            <div>
                <button>
                    SIGN-UP NOW!
                </button>
            </div>
            <div class="icons">
                <span>FOLLOW US</span>
                <ul>
                    <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                </ul>
                
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .footerbottom{
        background-color: #303030;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
            button{
                border:2px solid #0282f9 ;
                padding: 10px;
                background-color: transparent;
                color: white;
                }
            .icons{
                display: flex;
                align-items: center;
                span{
                    color: #0282f9;
                    padding-right: 10px;
                }
            }
            
            li{
                list-style: none;
                display: inline-block;
                padding: 0 5px;
            }
        }
    }
</style>