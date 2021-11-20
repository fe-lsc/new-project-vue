<template>
    <div>
        <ul>
            <li v-for=" (cake, index) in cakes" :key="index">
                {{cake}}
            </li>
        </ul>
    </div>
</template>


<script>
export default {
    data() {
        return {
            cakes: ['Cheesecake', 'Strawberry', 'Chocolatecake']
        }
    }
}
</script>


<style scoped>

    li{
    color: red;
    }
</style>
