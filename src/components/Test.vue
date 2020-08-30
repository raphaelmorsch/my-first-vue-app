<template>
   <div v-html="myHTML">

   </div>
    
</template>

<script>
export default {
    data() {
        return {
            title: 'Hola VueJS',
            user: {
                firstName: 'Joe',
                lastName: 'McMillan'
            },
            myHTML: '<h3>Hola vue</h3>'
        }
    }
    
}
</script>

<style scoped>
</style>