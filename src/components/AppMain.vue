<template>
    <AppJumbo />
    <MainCenterApp />
</template>

<script>
import AppJumbo from "./AppJumbo.vue"
import MainCenterApp from "./MainCenterApp.vue"

export default {
    name: "AppMain",
    components:{
        AppJumbo,
        MainCenterApp
    } 
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;
</style>