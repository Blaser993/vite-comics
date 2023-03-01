<template>
    <footer>
        
        <section class="iconsection">
            <div class="container">
                <ul class="row list-menu">
                    <li class="row menu-item">
                        <img src="/img/buy-comics-digital-comics.png" alt="">
                        <h3>digital comics</h3>
                    </li>
                    <li class="row menu-item">
                        <img src="/img/buy-comics-merchandise.png" alt="">
                        <h3>dc merchandise</h3>
                    </li>
                    <li class="row menu-item">
                        <img src="/img/buy-comics-subscriptions.png" alt="">
                        <h3>subscription</h3>
                    </li>
                    <li class="row menu-item">
                        <img src="/img/buy-comics-shop-locator.png" alt="">
                        <h3>comic shop location</h3>
                    </li>
                    <li class="row menu-item">
                        <img src="/img/buy-dc-power-visa.svg" alt="">
                        <h3>dc power usa</h3>
                    </li>
                </ul>
            </div>
        </section>
        <section class="links">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <div class="row wrap col-6">
                            <ul class="col-4 list-menu">
                                <h3>dc comics</h3>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                            </ul>
                            <ul class="col-4 list-menu">
                                <h3>dc</h3>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                            </ul>
                            <ul class="col-4 list-menu">
                                <h3>sites</h3>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                            </ul>
                            <ul class="col-4 list-menu">
                                <h3>shop</h3>
                                <li class="menu-item">link</li>
                                <li class="menu-item">link</li>
                            </ul>
                        </div>
                    </div>

                    <div class="col-6 logo-bg">
                        <img src="/img/dc-logo-bg.png" alt="">
                    </div>

                </div>
            </div>
        </section>
        <section class="cta">
            <div class="container">

                <section class="row">

                    <button>sign-up now!</button>
                    <ul class="list-menu row">
                        <h4>follow us</h4>   
                        <li>
                            <img src="/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-youtube.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-periscope.png" alt="">
                        </li>
                    </ul>
                </section>
            </div>
        </section>
       
    </footer>
</template> 

<script>


    export default{

    }
</script>

<style lang="scss" scoped>
    section{
        min-height: 50px;
    }

    .list-menu{
        justify-content: space-between;
        align-items: center;
    }
 
    .iconsection{
        background-color: cornflowerblue;
        color: white;
        text-transform: uppercase;
        padding: 3rem;
    }
    
    .menu-item{
        align-items: center;
        flex-basis: 0;
        flex-grow: 1;
        justify-content: flex-start;
        margin: 0 1rem;
    }
    .menu-item img{
        max-height: 48px;
        margin-right: 1rem;
        
    }


    .links{
        background-image: url("/img/footer-bg.jpg");
        overflow: hidden;
        color: white;
    }

    .col-auto{
        min-height: 12px;
    }

    .logo-bg{
        margin: -5rem 0;
    }

    .links h3{
        font-size: 18px;
        margin: 0 1rem;
        text-transform: uppercase;
        margin-bottom: 1rem;
    }

    .links .row{
        padding: 1rem 0;
    }

    .links .list-menu{
        margin: 1rem 0;
    }

    .links .menu-item{
        color: grey;
    }


    .cta{
        background-color: rgb(49, 49, 49);
        padding: 3rem 0;
    }
    .cta li{
        margin: 0 0.5rem;
    }

    h4{
        text-transform: uppercase;
        color: cornflowerblue;
        font-size: 20px;
        margin-right: 2rem;
    }

    button{
        font-size: 20px;
        text-transform: uppercase;
        color: white;
        border-radius: 0px;
        border: cornflowerblue 4px solid;
        background-color: rgb(49, 49, 49);
    }

   


    



    
    
</style>