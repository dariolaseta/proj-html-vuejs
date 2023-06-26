<template>
    <AppJumbo />
    <MainCenterApp />
    <AppMiddleCenter />
</template>

<script>
import AppJumbo from "./AppJumbo.vue"
import MainCenterApp from "./MainCenterApp.vue"
import AppMiddleCenter from "./AppMiddleCenter.vue"

export default {
    name: "AppMain",
    components:{
        AppJumbo,
        MainCenterApp,
        AppMiddleCenter
    } 
}
</script>

<style scoped lang="scss">
    @use "../styles/partials/_mixins" as *;
    @use "../styles/partials/_variables" as *;
</style>