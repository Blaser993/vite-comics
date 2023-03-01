<template>
    <header>
        <div class="container">
            <nav class="row">
                <img class="col-auto" src="/img/dc-logo.png" alt="">
                <ul class="col-auto main-menu">
                    <li class="menu-item active">characters</li>
                    <li class="menu-item">comics</li>
                    <li class="menu-item">movies</li>
                    <li class="menu-item">tv</li>
                    <li class="menu-item">games</li>
                    <li class="menu-item">collectibles</li>
                    <li class="menu-item">videos</li>
                    <li class="menu-item">fans</li>
                    <li class="menu-item">news</li>
                    <li class="menu-item">shop</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
    export default{

    }
</script>

<style lang="scss" scoped>

    nav{
        align-items: center;
        justify-content: space-between;
    }
    .main-menu{
        display: flex;
        justify-content: flex-end;
    }
    .menu-item{
        margin: 0 1rem;
        line-height: 108px;
        text-transform: uppercase;
        font-weight: 700;

        &.active{
            color: cornflowerblue;
            border-bottom: 8px solid cornflowerblue;
        }
    }

    img{
        max-width: 80px;
    }
</style>