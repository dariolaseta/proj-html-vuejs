<template>
    <section class="increase-brand">
        <div class="container">
            <div class="image-part">
                <img src="" alt="">
            </div>

            <div class="text-part">
                
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
            background-color: purple;
            height: 500px;
            width: 100%;
        }
    }
</style>