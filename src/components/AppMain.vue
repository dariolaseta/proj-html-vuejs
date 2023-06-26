<template>
    <AppJumbo />
    <MainCenterApp />
    <AppMiddleCenter />
    <AppBottom />
</template>

<script>
import AppJumbo from "./AppJumbo.vue"
import MainCenterApp from "./MainCenterApp.vue"
import AppMiddleCenter from "./AppMiddleCenter.vue"
import AppBottom from "./AppBottom.vue"

export default {
    name: "AppMain",
    components:{
        AppJumbo,
        MainCenterApp,
        AppMiddleCenter,
        AppBottom
    } 
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;
</style>