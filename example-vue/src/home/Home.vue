<template>
    <div class="hello">
        <h1 id='header'>EasyAudio Demo列表</h1>
        <router-link tag="li" to="/demo/quickstart" :event="['mousedown', 'touchstart']">
            <a>快速开始</a>
        </router-link>
        <router-link tag="li" to="/demo/setparam" :event="['mousedown', 'touchstart']">
            <a>设置参数</a>
        </router-link>
        <router-link tag="li" to="/demo/message" :event="['mousedown', 'touchstart']">
            <a>通信</a>
        </router-link>
        <router-link tag="li" to="/demo/longtest" :event="['mousedown', 'touchstart']">
            <a>较长的不常见格式视频的缓冲播放</a>
        </router-link>
        <router-link tag="li" to="/demo/decibel" :event="['mousedown', 'touchstart']">
            <a>音频可视化（全长分贝展示）</a>
        </router-link>
        <router-link tag="li" to="/demo/filter" :event="['mousedown', 'touchstart']">
            <a>滤波器</a>
        </router-link>
        <router-link tag="li" to="/demo/panner" :event="['mousedown', 'touchstart']">
            <a>声源位置改变</a>
        </router-link>
        <router-link tag="li" to="/demo/playlist" :event="['mousedown', 'touchstart']">
            <a>一个播放列表/音频可视化（频域）</a>
        </router-link>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data () {
        return {
        }
    },
    methods: {
    },
    created(){

    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body{
  width:100%;
  font-size:16px;
  line-height:30px;
}
#header{margin:30px 0 15px 0;}
h1, h2 {
  font-size:20px;
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  width:100%;
  display: inline-block;
}
a {
  width:100%;
  display:block;
  font-size:16px;
  line-height:30px;
  color: #42b983;
}
</style>
