<template>
    <main class="content">
        <div class="container-full">

            <div class="container">
                <div class="row">
                    <div class="col-auto">
                        <h2>current series</h2>
                    </div>
                </div>
                <div class="row">
                    comics
                </div>
                <div class="row">
                    <col-auto><button>load now</button></col-auto>
                </div>

            </div>

        </div>
    </main>
</template>

<script>
    export default{

    }
</script>

<style lang="scss" scoped>
    .content{
        -align-items: center;
        min-height: 100px;
        background-color: black;
        color: white;
        background-image:url("/img/jumbotron.jpg");
        background-size: cover;
        padding-top: 20rem;
    }


 

    .container-full{
        width: 100%;
        background-color: rgb(48, 48, 48);
    }
</style>