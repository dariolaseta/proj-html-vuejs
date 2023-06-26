<template>
    <main>
        <div class="jumbo">
            <div class="container">
                <div class="big-part">
                    <h1>Unlock Your Online Growth Potential</h1>
                    <p>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
                    <button class="jumbo-button">Our Services <i class="fa-solid fa-arrow-right"></i></button>
                </div>

                <div class="small-part">
                    <div class="form-container">
                        <div class="img">
                            <img src="../assets/img/marketing-consultant-expert.jpg" alt="marketing consultant expert">
                        </div>

                        <div class="text">
                            <h2>Richard Madsen</h2>
                            <h2>Marketing Consultant Expert</h2>
                            <p><a href="#" class="phone-number"> <i class="fa-solid fa-phone"></i> (555) 802-1234</a></p>
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

        <div class="icons-right">
            <a href="#"><i class="fa-solid fa-folder-closed"></i></a>
            <p>Prebuilts</p>
        </div>
        <div class="icons-right-bottom">
            <a href="#"><i class="fa-solid fa-cart-shopping"></i></a>
            <p>Buy now</p>
        </div>

        <div class="icon-bottom">
            <a href="#"><i class="fa-solid fa-message"></i></a>
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

    div.icons-right{
        box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

        height: 80px;
        width: 80px;
        border-radius: .5rem;
        position: fixed;
        z-index: 1;
        right: 15px;
        top: 150px;

        cursor: pointer;

        @include flex(column, center, center);

        font-size: 2rem;

        background-color: white;

        p{
            font-size: .8rem;
        }
    }

    div.icons-right-bottom{
        box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

        cursor: pointer;

        height: 80px;
        width: 80px;
        border-radius: .5rem;
        position: fixed;
        z-index: 1;
        right: 15px;
        top: 250px;

        @include flex(column, center, center);

        font-size: 2rem;

        background-color: white;

        p{
            font-size: .8rem;
        }
    }

    div.icon-bottom{
        box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

        cursor: pointer;

        height: 80px;
        width: 80px;
        border-radius: 50%;
        position: fixed;
        z-index: 1;
        right: 15px;
        bottom: 30px;

        @include flex(column, center, center);

        font-size: 2rem;

        background-color: #f55e10;

        i{
            color: white;
        }
    }
    div.jumbo{
        margin-top: 99px;
        width: 100%;
        background-image: url("../assets/img/marketing-intro.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        div.container{
            width: 100%;
            height: 660px;
            color: white;

            @include flex(row, normal, center);

            div.big-part{
                width: 60%;

                button.jumbo-button{
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
            }

            div.form-container{
                margin: 3rem;
            }

            
        }
    }
</style>