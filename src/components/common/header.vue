<template>
    <header>
        <span>{{title}}</span>
    </header>
</template>
<script type="text/javascript">
import Vue from 'vue';
    export default{
        data(){
            return{
                author:'first-component',
                title:'审核'
            }
        }
    }
</script>

<style>

header{
    position: relative;
    background-color: #289494;
    text-align: center;
    color: #fff;
    height: 45px;
    line-height: 45px;
    font-weight: bold;
}
.back{
    position: absolute;
    left: 1em;
    top: 1px;
}
</style>