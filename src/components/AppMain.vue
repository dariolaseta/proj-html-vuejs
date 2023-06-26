<template>
    <main>
        <div class="jumbo">
            <div class="container">
                <div class="big-part">
                    <h1>Unlock Your Online Growth Potential</h1>
                    <p>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
                    <button class="jumbo-button">Our Services &rarr;</button>
                </div>

                <div class="small-part">

                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: "AppMain"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;
    div.jumbo{
        width: 100%;
        background-image: url("../assets/img/marketing-intro.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        div.container{
            background-color: blue;
            width: 100%;
            height: 500px;
            color: white;

            @include flex(row, normal, center);

            div.big-part{
                width: 60%;
                background-color: green;

                button.jumbo-button{
                    background-color: white;
                    border: 2px solid black;
                }

                h1{
                    font-size: 4rem;
                }

                p{
                    font-size: 2rem;
                    margin: 2rem 0;
                }
            }

            div.small-part{
                height: 200px;
                width: 40%;
                background-color: pink;
            }
        }
    }
</style>