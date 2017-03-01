<style  src='./widget/css/api.css'></style>

<template>
    <div id="app">
        <comheader></comheader>
        <h1>{{ msg }}</h1>
        <router-view></router-view>
        <comfooter></comfooter>
    </div>
</template>

<script>

import Vue from 'vue';

import comheader from './components/common/header.vue'
import comfooter from './components/common/footer.vue'

export default {
    data () {
        return {
            msg: 'Hello World!  content占位',
            selected:''
        }
    },
    components:{
        comheader,
        comfooter
    }
}
</script>

<style>

</style>

