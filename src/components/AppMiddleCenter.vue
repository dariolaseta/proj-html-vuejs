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

    <section class="client-boost">
        <div class="container">
            <div class="top-section">
                <div class="text-part">
                <div class="text">
                    <h1>We Boost Our Clients’ Bottom Line by Optimizing Their Growth Potential.</h1>
                    <p>Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.</p>
                    <button class="orange">Why Work With Us</button>
                </div>
            </div>

                <div class="image-part">
                    <img src="../assets/img/we-boost-our-clients.jpg" alt="We boost our clients">
                </div>
            </div>

            <div class="middle-section">
                <div class="text-part left">
                    <div class="top">
                        <h2>We Build Relationships</h2>
                        <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                    </div>
                    
                    <div class="bottom">
                        <h2>Proprietary Processes</h2>
                        <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                    </div>
                </div>

                <div class="text-part right">
                    <div class="accountability flex">
                        <div class="box">
                            <!-- fontawesome -->
                        </div>
                        <div class="text">
                            <h2>Accountability</h2>
                            <p>Curabitur ac leo nunc vestibulum</p>
                        </div>
                    </div>

                    <div class="transparency flex">
                        <div class="box">
                            <!-- fontawesome -->
                        </div>
                        <div class="text">
                            <h2>Transparency</h2>
                            <p>Curabitur ac leo nunc vestibulum</p>
                        </div>
                    </div>

                    <div class="investment flex">
                        <div class="box">
                            <!-- fontawesome -->
                        </div>
                        <div class="text">
                            <h2>Investment</h2>
                            <p>Curabitur ac leo nunc vestibulum</p>
                        </div>
                        
                    </div>
                </div>
            </div>

            <div class="awards">
                <div class="title">
                    <h2>Awards</h2>
                </div>

                <div class="logos">
                    <div class="imgs">
                        <img src="../assets/img/award-a.png" alt="Winner Seo Master">
                        <p>Winner Seo Master MAGT Smart Start Award 2017</p>
                    </div>

                    <div class="imgs">
                        <img src="../assets/img/award-b.png" alt="Top Social Media Agencies">
                        <p>Top Social Media Agencies Next Partner 2018</p>
                    </div>

                    <div class="imgs">
                        <img src="../assets/img/award-c.png" alt="Fastest Growing Abstract Solution Providers">
                        <p>10 Fastest Growing Abstract Solution Providers 2019</p>
                    </div>

                    <div class="imgs">
                        <img src="../assets/img/award-d.png" alt="National Excellence Agencie Award Winner">
                        <p>National Excellence Agencie Award Winner 2020</p>
                    </div>
                </div>
            </div>

            <div class="testimonials">
                <div class="image-part">
                    <img src="../assets/img/large-testimonial.jpg" alt="testimonial">
                </div>

                <div class="text-part">
                    <h2>“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”</h2>

                    <p>Kate Schadler</p>
                    <p class="subtext">Marketing Consultant – Abstract</p>
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
        padding-bottom: 7rem;
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

    section.client-boost{

        // aggiungere linear gradient
        margin-top: 7rem;
        div.container{
            
            div.top-section{
                @include flex(row, normal, normal);
                padding-bottom: 2rem;

                div.text-part{
                width: 50%;

                    div.text{
                        width: 80%;

                        h1{
                            font-size: 3rem;
                        }

                        p{
                            font-size: 1.4rem;
                            padding: 2rem 0;
                        }
                    }
                }
                div.image-part{
                    width: 50%;
                    img{
                        width: 100%;
                        border-radius: .5rem;
                    }
                }
            }

            div.middle-section{
                @include flex(row, normal, normal);

                padding: 5rem 0;
                div.left{
                    width: 50%;

                    h2{
                        font-size: 2rem;
                        padding-bottom: 1rem;
                    }

                    p{
                        font-size: 1.2rem;
                        padding-bottom: 4rem;
                        width: 80%;
                    }
                }

                div.right{
                    padding-left: 3rem;
                    div.flex{
                        @include flex(row, normal, normal);
                    }

                    div.box{
                        width: 70px;
                        height: 70px;
                        background-color: orange;
                        border-radius: 1rem;
                    }

                    div.text{
                        padding-left: 1rem;
                        p{
                            padding: 1rem 0 2rem;
                        }
                    }
                }
            }

            div.awards{
                margin-bottom: 6rem;
                    div.title{
                        text-align: center;
                        font-size: 1.3rem;
                    }

                    div.logos{
                        @include flex(row, normal, normal);
                        width: 100%;
                        div.imgs{
                            width: 100%;
                            img{
                                width: 50%;
                            }

                            p{
                                width: 70%;
                            }
                        }
                    }
                }
        }

        div.testimonials{
            padding-top: 6rem;
            @include flex(row, normal, normal);
            div.image-part{
                width: 50%;
                img{
                    width: 100%;
                    border-radius: 0.5rem;
                }
            }

            div.text-part{
                width: 50%;
                h2{
                    width: 60%;
                    font-size: 1.8rem;
                    margin: 3rem 5rem 2rem;
                }
                p{
                    margin-left: 5rem;
                    margin-bottom: .5rem;
                    font-size: 1.3rem;
                }

                p.subtext{
                    font-size: .8rem;
                }
            }

        }
    }
</style>