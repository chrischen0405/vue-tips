<template>
    <div class="tips1" @click="onClick">
        <ul>
            <li v-for="(item, index) in list" :key="index" :data-index="index">
                {{item}}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'tips1', // vue事件代理
    data () {
        return {
            list: ['项目1', '项目2', '项目3']
        }
    },
    methods: {
        onClick (e) {
            const index = e.target.getAttribute('data-index')
            console.log(index)
        }
    }
}
</script>

<style scoped>
.tips1 {
    width: 200px;
}

li {
    cursor: pointer;
}
</style>
