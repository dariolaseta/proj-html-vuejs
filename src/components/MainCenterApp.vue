<template>
    <section class="increase-brand">
        <div class="container">
            <div class="image-part">
                <img src="../assets/svg/img1.svg" alt="img 1">
            </div>

            <div class="text-part">
                <div class="business-growth">
                    <p class="icon-container blue"></p>
                    <span>Business Growth</span>
                </div>

                <div class="text">
                    <h1>Increase Brand Awareness</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <button>Get A Consultation</button>
                </div>
            </div>
        </div>
    </section>

    <section class="investors">
        <div class="container">
            <div class="text-part">
                <div class="investor-in-people">
                    <p class="icon-container yellow"></p>
                    <span>Investors In People</span>
                </div>

                <div class="text">
                    <h1>In-House Sales Training</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <button>Get A Consultation</button>
                </div>
            </div>
            
            <div class="image-part">
                <img src="../assets/svg/img2.svg" alt="investors in people img">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "MainCenterApp"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    section.increase-brand{
        div.container{
            width: 100%;
            @include flex(row, normal, normal);

            div.image-part{
                width: 45%;
                padding: 5rem 0;

                img{
                    width: 100%;
                }
            }

            div.text-part{
                width: 55%;
                padding: 10rem;

                div.business-growth{
                    @include flex(row, normal, center);

                    span{
                        font-size: 1.3rem;
                        padding-left: 1rem;
                    }
                }

                h1{
                    font-size: 2.9rem;
                }

                p{
                    font-size: 1.3rem;
                    margin: 1rem 0;
                }
            }
        }
    }

    section.investors{
        div.container{
            @include flex(row, normal, normal);
        }

        div.text-part{
                width: 55%;
                padding: 5rem 0;
                div.investor-in-people{
                    @include flex(row, normal, center);

                    span{
                        font-size: 1.3rem;
                        padding-left: 1rem;
                    }
                }

                h1{
                    font-size: 2.9rem;
                }

                p{
                    font-size: 1.3rem;
                    margin: 1rem 0;
                }
            }
    }
</style>