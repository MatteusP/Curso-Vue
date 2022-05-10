<template>
<!-- a notação ":" equivale ao "v-bind" -->
    <img :src="avatar" :alt="descricao">
</template>

<script>
export default {
    name: 'PictureS',
    data() {
        return{ 
            avatar: '/public/avatar.png',
            descricao: 'icon'
            
        }     
    },
}
</script>