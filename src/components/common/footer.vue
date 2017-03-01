<template>
        <footer>
            <mt-tabbar fixed v-model="selected">
              <mt-tab-item id="首页">
                <!-- <img slot="icon" src="./image/1.png"> -->
                首页
              </mt-tab-item>
              <mt-tab-item id="直播">
                <!-- <img slot="icon" src="./image/2.png"> -->
                直播
              </mt-tab-item>
              <mt-tab-item id="关注">
                <!-- <img slot="icon" src="./image/3.png"> -->
                关注
              </mt-tab-item>
              <mt-tab-item id="发现">
                <!-- <img slot="icon" src="./image/4.png"> -->
                发现
              </mt-tab-item>
              <mt-tab-item id="我的">
                <!-- <img slot="icon" src="./image/5.png"> -->
                我的
              </mt-tab-item>
            </mt-tabbar>
        </footer>
</template>
<script type="text/javascript">
import Vue from 'vue';
import { Tabbar, TabItem } from 'mint-ui';
Vue.component(Tabbar.name, Tabbar);
Vue.component(TabItem.name, TabItem);
    export default{
        data(){
            return{
                selected:''
            }
        }
    }
</script>

<style>

footer .mint-tab-item-label{
    font-size: 15px;
}
</style>