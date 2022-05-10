<template>
    <div>
        <button @click="$emit('MudarImg')">Trocar foto</button>
    </div>
</template>

<script>
export default {
    name: 'MudarImg',
    emits: ['MudarImg']
}
</script>r