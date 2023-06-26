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
                    <div class="form-container">
                        <div class="img">
                            <img src="../assets/img/marketing-consultant-expert.jpg" alt="marketing consultant expert">
                        </div>

                        <div class="text">
                            <h2>Richard Madsen</h2>
                            <h2>Marketing Consultant Expert</h2>
                            <p><a href="#">(555) 802-1234</a></p>
                        </div>

                        <div class="form">
                            <input type="text" placeholder="Your Name*">
                            <input type="text" placeholder="Your Email*">
                            <input type="text" placeholder="Your Phone Number*">

                            <button class="form orange">Get A Callback</button>

                            <p>By submitting my data I agree to be contacted</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: "AppJumbo"
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
                height: 100%;
                width: 40%;
                background-color: pink;

                div.form-container{
                    @include flex(column, normal, center);
                    width: 100%;

                    div.img{
                        padding: 1rem 0;
                        
                        img{
                            height: 100px;
                            width: 100px;
                            border-radius: 50%;
                        }
                    }

                    div.text{
                        text-align: center;

                        h2{
                            padding-bottom: 1rem;
                        }
                    }

                    div.form{
                        @include flex(column, normal, normal);
                    }
                }
            }
        }
    }
</style>