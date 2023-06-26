<template>
    <header>
        <div class="container">
            <div class="logo">
                Logo
            </div>
    
            <div class="middle-section">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="@">Services</a></li>
                    <li><a href="#">Why Us</a></li>
                    <li><a href="#">Case Studies</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </div>
    
            <div class="right-section">
                <ul>
                    <li><a href="#">(555) 802-1234</a></li>
                    <li><a href="#"><button>Free Quote</button></a></li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "AppHeader"
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    header{
        background-color: red;
        div.container{
            padding: 1.5rem 0;
            @include flex(row, space-between, center);

            div.logo{
            }

            div.middle-section{
                width: 60%;
                ul{
                    @include flex(row, space-between, center);
                }
            }

            div.right-section{
                ul{
                    @include flex(row, normal, normal);

                    li{
                        margin-right: 1rem;
                    }
                }
            }
        }

    }
</style>