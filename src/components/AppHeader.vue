<template>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#"><img src="../assets/img/avada-marketing-logo.png" alt="logo"></a>
            </div>
    
            <div class="middle-section">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Why Us</a></li>
                    <li><a href="#">Case Studies</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </div>
    
            <div class="right-section">
                <ul>
                    <li><i class="fa-solid fa-phone"></i></li>
                    <li>(555) 802-1234</li>
                    <li><a href="#"><button class="light-orange">Free Quote</button></a></li>
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
        i{
            color: #f55e10;
        }
        div.container{
            padding: 1.5rem 0;
            @include flex(row, space-between, center);

            div.logo{
                width: 20%;
            }

            div.middle-section{
                width: 40%;
                ul{
                    @include flex(row, space-between, center);
                }
            }

            div.right-section{
                ul{
                    @include flex(row, normal, center);
                    
                    li{
                        margin-right: 2rem;
                    }
                }
            }
        }

    }
</style>