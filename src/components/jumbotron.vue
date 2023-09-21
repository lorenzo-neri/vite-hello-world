<script>
export default {
    data() {
        return {
            img: 'https://picsum.photos/200/300',
            msg: 'JUMBOTRON'
        }
    }
}
</script>

<template>
    <div>{{ msg }}</div>
    <img :src="img" />
</template>

<style scoped></style>