<template>
    <div>
        <div>
            <input type="radio" name="" id="html" value="HTML" v-model="favoriteLang">
            <label for="html">HTML</label>
            <input type="radio" name="" id="css" value="CSS" v-model="favoriteLang">
            <label for="css">CSS</label>
            <input type="radio" name="" id="js" value="JS" v-model="favoriteLang">
            <label for="js">JS</label>
        </div>
        <div>
            select lang : {{favoriteLang}}
        </div>
    </div>
</template>
<script>
export default {
    components: {},
    data () {
        return {
            favoriteLang: 'JS'
        }
    },
    setup () {},
    created () {},
    mounted () {},
    unmounted () {},
    methods: {}
}
</script>
