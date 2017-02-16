<template>
    <div class="container-fluid">
        <div class="row">
            <side-bar></side-bar>
        </div>
    </div>
</template>

<style>

</style>

<script>
    import SideBar from './SideBar'

    export default{
        data(){
            return{
                msg:'hello vue'
            }
        },
        components:{
            SideBar
        }
    }
</script>
