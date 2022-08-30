<template>
    <div>
        <input type="text" v-bind:value="userId" readonly/>
        <input type="text" :value="userId" readonly/> <!-- v-bind 생략 가능-->
        <br>
        <img :src="imgSrc" alt="" style="width:100px; height:auto;">
        <br>
        <input type="search" name="" id="" v-model="txt1" />
        <button v-bind:disabled="txt1 === ''">search</button>
    </div>
</template>
<script>
export default {
    components: {},
    data () {
        return {
            userId: 'uno',
            imgSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png'
        }
    },
    setup () {},
    created () {},
    mounted () {},
    unmounted () {},
    methods: {}
}
</script>
