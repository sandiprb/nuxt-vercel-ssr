<template>
<div class="text-center text-2xl">
    slug: {{slug}}
</div>
</template>

<script>
export default {
    name: 'sample-slug',
    asyncData(ctx){
        const {slug} = ctx.params
        return {
            slug
        }
    },


    data: () => ({}),

    methods: {},
}
</script>
<style lang="postcss" scoped>
</style>