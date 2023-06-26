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

    <section class="trusted">
        <div class="container">
            <div class="title">
                <h1>Trusted by Leading Organisations</h1>
            </div>

            <div class="images">
                <div class="img-left">
                    <a href="#"><img src="../assets/img/case-studies-1.jpg" alt="case studies 1 img"></a>
                    <p class="top-text">How Spaces attracted five million visitors by improving the content</p>
                    <p class="number">200%</p>
                    <p class="bottom-text">Higher revenue from digital</p>
                </div>

                <div class="img-center">
                    <a href="#"><img src="../assets/img/case-studies-4.jpg" alt="case studies 4 img"></a>
                    <p class="top-text">Creativity helped Hemisferio to increase their brand reach vertically</p>
                    <p class="number">10x</p>
                    <p class="bottom-text">Sales increase with the same ad spend</p>
                </div>

                <div class="img-right">
                    <a href="#"><img src="../assets/img/case-studies-6.jpg" alt="case studies 6 img"></a>
                    <p class="top-text">How DigitalBox used AI-powered data insight to boost sales</p>
                    <p class="number">3-year</p>
                    <p class="bottom-text">Partnership with Avada Consultant</p>
                </div>
            </div>

            <div class="button">
                <button class="orange">Read More Case Studies</button>
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
                margin: 3rem 0;

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

    section.trusted{
        div.title{
            h1{
                text-align: center;
                padding: 4rem 0;
            }
        }
        
        div.images{
            @include flex(row, normal, normal);

            img{
                width: 90%;
            }

            p.top-text{
                padding: 1rem 0 2rem;
                font-size: 1.8rem;
                font-weight: bold;
                width: 95%;
            }

            p.number{
                font-size: 3rem;
                font-weight: bold;
            }

            p.bottom-text{
                font-size: 1.2rem;
            }
        }

        div.button{
            @include flex();
            button.orange{
                margin: 4rem 0;
            }
        }
    }
</style>