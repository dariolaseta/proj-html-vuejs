<template>
    <footer>
        <section class="top-footer">
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
        </section>

        <section class="bottom-footer">
            <div class="container">
                <div class="content">
                    <div class="socials">
                        <div class="title">
                            <h2>Grow Your Online Business Strategically, and Improve Customer Retention.</h2>
                        </div>

                        <div class="icons">

                        </div>
                    </div>

                    <div class="links">

                        <div class="services">
                            <ul>
                                <h3>Services</h3>
                                <li><a href="#">Marketing Plan</a></li>
                                <li><a href="#">Sales Development</a></li>
                                <li><a href="#">Digital Marketing</a></li>
                                <li><a href="#">Pricing</a></li>
                                <li><a href="#">Why Us</a></li>
                                <li><a href="#">Case Studies</a></li>
                            </ul>
                        </div>
    
                        <div class="resources">
                            <ul>
                                <h3>Resources</h3>
                                <li><a href="#">Learning Center</a></li>
                                <li><a href="#">Video Tutorials</a></li>
                                <li><a href="#">Customers</a></li>
                                <li><a href="#">Blog</a></li>
                            </ul>
                        </div>
    
                        <div class="company">
                            <ul>
                                <h3>Company</h3>
                                <li><a href="#">Who We Are</a></li>
                                <li><a href="#">Contact Us</a></li>
                                <li><a href="#">Careers</a></li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="bottom-content">
                    <div class="copyright">
                        <p>© 2020 • Avada Consultant • Powered by WordPress</p>
                    </div>

                    <div class="number">
                        <p>Call Us (555) 802-1234</p>
                    </div>

                    <div class="email">
                        <p>info@yourcompany.com</p>
                    </div>
                </div>
            </div>
        </section>
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
        color: white;

        div.form-container{
            margin: 2rem;
        }

        section.top-footer{
            background-color: black;
            margin-bottom: 3rem;

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

        section.bottom-footer{
            margin-top: 2rem;
            color: black;

            div.content{
                @include flex(row, normal, normal);
                width: 100%;

                div.links{
                    width: 55%;
                    @include flex(row, space-between, normal);
                    ul{
                        h3{
                            padding-bottom: 1rem;
                        }
                        li{
                            padding: .6rem 0;
                        }
                    }
                }

                div.socials{
                    width: 45%;
                    div.title{
                        h2{
                            width: 60%;
                            font-size: 1.7rem;
                        }

                        
                    }
                }

            }

            div.bottom-content{
                width: 100%;
                font-size: .8rem;
                margin-top: 7rem;
                @include flex(row, space-between, normal);
                div.copyright{
                    width: 30%;
                }

                div.number{
                    width: 40%;
                    margin-left: 19rem;
                }

                div.email{
                    width: 30%;
                    padding-left: 16rem;
                }
            }
        }
    }
</style>