<template>
    <div class="row cards">

        <div  class="card">
            <img class="card-image" :src="thumb" alt="pic">
            <h5 class="description">{{description}}</h5> 
        </div>


        <!-- <div class="card">
            <img class="card-image" :src="src" alt="pic">
            <h5 class="description">{{description}}</h5> 
        </div> -->
    </div>
</template>

<script>
    export default{
        props:{
            thumb: String,
            description: String
        },


    }
</script>
    
<style lang="scss" scoped>
        .cards{
        row-gap: 0.75rem;
        flex-wrap: wrap;
    }

    .card {
        flex-basis: 16%; 
        padding: .75rem ;
        display: flex;
        flex-direction: column;
        row-gap: 0;
        flex-wrap: wrap;
        align-content: start;
    }

    
   

    .card-image{
        
        max-height: 180px;
        flex-shrink: 0;
        margin-bottom: 1rem;
        aspect-ratio: 1;
        object-fit: cover;
    }

    .description{
        text-transform: uppercase;
    }
</style>