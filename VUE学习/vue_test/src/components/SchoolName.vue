<template lang="">
<!-- 组件的结构 -->
    <div class="demo">
        <h2>学校名称：{{name}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="showName">点我提示学校名</button>
    </div>
</template>

<script>
// 组件交互相关的代码
export default {
    name:'SchoolName',
    data() {
        return {
            name: '尚硅谷',
            address: '北京昌平'
        }
    },
    methods: {
        showName() {
            alert(this.name)
        }
    },
}

</script>
<style>
/* 样式 */
.demo {
    background-color: orange;
}
</style>