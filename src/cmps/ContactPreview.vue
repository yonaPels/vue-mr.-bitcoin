<template>
    <article class="contant-preview">
        <h2>{{ contact.name }}</h2>
    </article>
</template>

<script>
export default {
    props: {
        contact: { type: Object, required: true },
    }
}

</script>

<style lang="scss" scoped>

</style>