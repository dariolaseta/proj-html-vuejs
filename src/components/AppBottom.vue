<template>
    <section class="marketing">
        <div class="container">
            <div class="title">
                <h1>Marketing Resources: Insider Advice on How to Increase Online Sales</h1>
                <div class="button">
                    <button class="orange">Explore All Resources</button>
                </div>
            </div>

            <div class="blog">
                <div class="img">
                    <img src="../assets/img/blog-posts-6.jpg" alt="blog post">
                    <h2>Marketing Tips And Tricks For Your Website</h2>
                </div>

                <div class="img">
                    <img src="../assets/img/blog-posts-5.jpg" alt="blog post">
                    <h2>How to Write Stunning Blog Post Titles</h2>
                </div>

                <div class="img">
                    <img src="../assets/img/blog-posts-4.jpg" alt="blog post">
                    <h2>Techniques to Reduce Facebook Ads Spend</h2>
                </div>
            </div>
        </div>
        
    </section>
</template>

<script>
export default {
    name: "AppBottom"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    section.marketing{
        margin-top: 8rem;
        div.container{
            div.title{
                margin-bottom: 2rem;

                @include flex(row, space-between, center);
                h1{
                    width: 50%;
                    font-size: 3rem;
                }
            }

            div.blog{
                padding-bottom: 3rem;
                padding-top: 2rem;
                @include flex(row, normal, normal);
                div.img{
                    width: 100%;
                    padding: 1rem;
                    img{
                        width: 100%;
                    }

                    h2{
                        font-size: 2rem;
                        padding-top: 1rem;
                    }
                }
            }
        }
    }
</style>