<template>
    <HeaderComponentVue></HeaderComponentVue>
    <router-view></router-view> 
</template>
<script>
import HeaderComponentVue from '../../components/header_footer/HeaderComponent.vue';
export default {
    components: { HeaderComponentVue },

    data (){
        return{}
    },
    
}
</script>
<style lang="css" scoped>
    
</style>