<template>
    <section class="some-brands">
        <div class="container">
            <div class="text">
                <h1>Some Brands We Work With</h1>
                <p>Quisque aliquet, libero consequat elementum convallis.</p>
            </div>

            <div class="brands">
                <ul>
                    <li><a href="#"><img src="../assets/img/abstract.png" alt="abstract logo"></a></li>
                    <li><a href="#"><img src="../assets/img/cglobal.png" alt="cglobal logo"></a></li>
                    <li><a href="#"><img src="../assets/img/next.png" alt="next logo"></a></li>
                    <li><a href="#"><img src="../assets/img/hemisferio.png" alt="hemisferio logo"></a></li>
                    <li><a href="#"><img src="../assets/img/spaces.png" alt="spaces logo"></a></li>
                    <li><a href="#"><img src="../assets/img/digitalbox.png" alt="digitalbox logo"></a></li>
                </ul>
            </div>

            <div class="card">
                <div class="left-part">
                    <img src="../assets/img/marketing-expert-cta.png" alt="marketing expert">
                    <div class="name-role">
                        <h2 class="name">Sandy Reiff</h2>
                        <p class="role">Marketing Consultant Expert</p>
                    </div>
                </div>


                <div class="center-text">
                    <h2>Drive Leads and Sales with Avada</h2>
                </div>

                <div class="right-button">
                    <button class="light-orange">(555) 802-1234</button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "AppMiddleCenter"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    h1{
        font-size: 3.5rem;
    }
    section.some-brands{
        text-align: center;

        div.container{
            p{
                font-size: 1.5rem;
            }

            div.brands{
                ul{
                    padding: 4rem 0;
                    @include flex(row, space-between, normal);

                    li{
                        a{
                            img{
                                width: 70%;
                            }
                        }
                    }
                }
            }

            div.card{
                @include flex(row, space-between, center);
                text-align: left;
                border-radius: .8rem;
                padding: .8rem 2rem;

                box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
                
                div.left-part{
                    @include flex(row, normal, center);
                    img{
                        width: 80px;
                        height: 80px;
                        border-radius: 50%;
                    }
                    div.name-role{
                    padding-left: 2rem;

                        h2{
                            font-size: 1.5rem;
                        }

                        p.role{
                            font-size: 1rem;
                        }
                    }
                }

                div.center-text{
                    h2{
                        font-size: 1.8rem;
                    }
                }
            }
        }
    }
</style>