<template>
    <main class="content">
        <div class="container-full">

            <div class="container">
                <div class="row">
                    <div class="col-auto title">
                        <h2>current series</h2>
                    </div>
                </div>

                
                <div class="row cards">
                <Comics class="card"  v-for="(comic,i) in comics" :key="i" :thumb="comic.thumb" :description="comic.series" ></Comics>
                </div>

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
            return{
                comics:[
                    {  thumb: "https://pbs.twimg.com/media/DEns6v4V0AApDZN.jpg",
                        price: "$19.99",
                        series: "Action Comics",
                        type: "comic book"
                    },
                    {
                        thumb: "https://thumbs.dreamstime.com/b/horse-superhero-masked-cape-cartoon-confident-smiling-mask-54399226.jpg",
                        price: "$3.99",
                        series: "American Vampire 1976",
                        type: "comic book"
                    },
                    {
                        thumb: "https://www.thehorsetailor.com/gallery/superman-480-Readytoship.jpg",
                        price: "$16.99",
                        series: "Aquaman",
                        type: "graphic novel"
                    },
                    {
                        thumb: "https://img-9gag-fun.9cache.com/photo/av04jo5_460s.jpg",
                        price: "$2.99",
                        series: "Batgirl",
                        type: "comic book"
                    },
                    {
                        thumb: "https://i.pinimg.com/564x/00/b8/83/00b88372f534e2d7fd4190a60e3f319d.jpg",
                        price: "$3.99",
                        series: "Batman",
                        type: "comic book"
                    },
                    {
                        thumb: "https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/c0c6b86a-22e6-4642-8480-dbcd08fa1109/db6zprg-0ce715fa-96df-4774-8984-70138fa0749c.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2MwYzZiODZhLTIyZTYtNDY0Mi04NDgwLWRiY2QwOGZhMTEwOVwvZGI2enByZy0wY2U3MTVmYS05NmRmLTQ3NzQtODk4NC03MDEzOGZhMDc0OWMucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.X8PGnyHsBAs563VmgjkE4E9Hnee6eQ7VBFCw1XdCqDc",
                        price: "$2.99",
                        series: "Batman Beyond",
                        type: "comic book"
                    },
                    {
                        thumb: "https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/ef9094bc-4aaf-4e45-afcf-44cf17db80fa/dev766y-3084f5b1-4157-4fa1-aa39-b57f09e28be7.png/v1/fill/w_1024,h_1318,q_80,strp/dc_comics_comet_the_super_horse_by_donandron_dev766y-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTMxOCIsInBhdGgiOiJcL2ZcL2VmOTA5NGJjLTRhYWYtNGU0NS1hZmNmLTQ0Y2YxN2RiODBmYVwvZGV2NzY2eS0zMDg0ZjViMS00MTU3LTRmYTEtYWEzOS1iNTdmMDllMjhiZTcucG5nIiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.U7k1NX0DKrY4VVlar2yfYOHGLCvz1R6usLMmtjcnci4",
                        price: "$3.99",
                        series: "Batman/Superman",
                        type: "comic book"
                    },
                    {
                        thumb: "https://i.ytimg.com/vi/h5EBF_WN944/maxresdefault.jpg",
                        price: "$4.99",
                        series: "Batman/Superman Annual",
                        type: "comic book"
                    },
                    {
                        thumb: "https://i.ytimg.com/vi/scnTzGvAVsg/maxresdefault.jpg",
                        price: "$5.99",
                        series: "Batman: The Joker War Zone",
                        type: "comic book"
                    },
                    {
                        thumb: "https://comiclists.files.wordpress.com/2017/11/batman-horse17.jpg",
                        price: "$6.99",
                        series: "Batman: Three Jokers",
                        type: "comic book"
                    },
                    {
                        thumb: "https://i.pinimg.com/originals/99/b2/f0/99b2f0ef3888532238e57c615a89019a.jpg",
                        price: "$4.99",
                        series: "Batman: White Knight Presents: Harley Quinn",
                        type: "comic book"
                    },
                    {
                        thumb: "https://i.pinimg.com/originals/f2/1b/39/f21b39d4faf734bf010c5b90f7cc742c.jpg",
                        price: "$16.99",
                        series: "Catwoman",
                        type: "graphic novel"
                    }
]             
            }
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
    

    .cards{
        row-gap: 0.75rem;
        flex-wrap: wrap;
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