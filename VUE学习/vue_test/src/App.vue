<template>
    <div>
        <img src="./assets/logo.png" alt="">
        <schoolName></schoolName>
    </div>
</template>

<script>
//引入组件
import schoolName from './components/SchoolName'
export default {
    name: 'App',
    components:{
        schoolName,
    }
}
</script>

<style>
</style>