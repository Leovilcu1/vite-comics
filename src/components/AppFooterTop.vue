<script>

export default{
    name: "AppfooterTop",
    
}
</script>

<template>

    <main>
        <div class="container">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
            
        </div>
    </main>
</template>

<style lang="scss" scoped>
main{
    background-color: #0282f9;

    .container{
        padding: 30px 0;
        color: rgb(255, 255, 255); 
        > *{
            width: 20%;
            display: flex;
            align-items: center;
            >img {
                width: 30%;
                padding-right: 10px;
            }
        }
        
     }

}
    
</style>  