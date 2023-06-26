<template>
    <footer>
        <div class="container">
            <div class="content">
                <div class="big-part">
                    <h1>Let’s Make Things Happen</h1>
                    <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                    <hr>
                    <p class="sentence">“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”</p>

                    <p class="ceo-name">George Anderson</p>
                    <p class="role">Digitalbox CEO</p>
                </div>

                <div class="small-part">
                    <div class="form-container">
                        <div class="img">
                            <img src="../assets/img/marketing-consultant-expert.jpg" alt="marketing consultant expert">
                        </div>

                        <div class="text">
                            <h2>Richard Madsen</h2>
                            <p>Marketing Consultant Expert</p>
                            <p><a href="#" class="phone-number">(555) 802-1234</a></p>
                        </div>

                        <div class="form">
                            <input type="text" placeholder="Your Name*">
                            <input type="text" placeholder="Your Email*">
                            <input type="text" placeholder="Your Phone Number*">

                            <button class="form orange">Get A Callback</button>

                            <div class="bottom-text">
                                <p class="bottom-text">By submitting my data I agree to be contacted</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "AppFooter"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    footer{
        background-color: black;
        color: white;

        div.big-part{
            width: 55%;

            h1{
                font-size: 4rem;
            }

            p{
                font-size: 1.7rem;
                padding: 2rem 0;
            }

            p.sentence{
                font-style: italic;
            }

            p.ceo-name{
                padding-bottom: 0;
                font-size: 1.3rem;
            }

            p.role{
                font-size: .8rem;
                color: #cccccc;
                padding-top: 0;
            }

            hr{
                width: 15%;
            }
        }

        div.content{
            padding-top: 6rem;
            @include flex(row, normal, normal);
        }
    }
</style>