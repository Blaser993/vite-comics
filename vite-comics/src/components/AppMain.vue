<template>
    <main class="content">
        <div class="container-full">

            <div class="container">
                <div class="row">
                    <div class="col-auto title">
                        <h2>current series</h2>
                    </div>
                </div>

                <Comics></Comics>

                <div class="row">
                    <col-auto class="cta">
                        <button>load now</button>
                    </col-auto>
                </div>

            </div>

        </div>
    </main>
</template>

<script>
    import Comics from './Comics.vue'

    export default{
        components:{
            Comics
        },

        data() {

        }
    }
</script>

<style lang="scss" scoped>
    .content{
        align-items: center;
        min-height: 100px;
        background-color: black;
        color: white;
        background-image:url("/img/jumbotron.jpg");
        background-size: cover;
        padding-top: 24rem;
    }

    .title{
        font-size: 20px;
        text-transform: uppercase;
        background-color: cornflowerblue;
        max-width: fit-content;
        padding: 0.5rem 2.5rem;
        margin-top: -2rem;
        margin-bottom: 1rem;
    }
    


 

    .container-full{
        width: 100%;
        background-color: rgb(48, 48, 48);
    }


    .cta{
        text-align: center;
        align-items: center;
        align-content: center;
        align-self: center;
        justify-self: center;
    }
</style>