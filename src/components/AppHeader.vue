<template>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#"><img src="../assets/img/avada-marketing-logo.png" alt="logo"></a>
            </div>
    
            <div class="middle-section">
                <ul>
                    <li v-for="element in navItems"><a href="#" class="active">{{element.title}}</a></li>
                </ul>
            </div>
    
            <div class="right-section">
                <ul>
                    <li><i class="fa-solid fa-phone"></i> (555) 802-1234</li>
                    <li><a href="#"><button class="light-orange">Free Quote</button></a></li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "AppHeader",
    props:{
        navItems: {
            type: Array
        }
    }
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;

    header{
        z-index: 1;
        position: fixed;
        top: 0;
        width: 100%;
        background-color: white;
        i.fa-phone{
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

                    li{
                        a:hover{
                            color: #f55e10;
                            transition: 0.3s ease;
                            border-bottom: 3px solid #f55e10;
                            padding-bottom: .5rem;
                        }
                    }
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