<!-- In Vue.js, computed properties enable you to create a property that can be used to modify, manipulate, and display data within your components in a readable and efficient manner.

You can use computed properties to calculate and display values based on a value or set of values in the data model -->

<template>
    <div>
        <h2>Article Component</h2>
        <h2>{{ title }}</h2>
        <h2>Likes - {{ likes }}</h2>
        <h2>Published - {{ isPublished ? 'Yes' : 'No' }}</h2>
    </div>
</template>

<script>
    export default {
    name: 'ArticlePage',
    props: {
        title: {
            type: String,
            required: true,
            default: 'Article default title'
        },
        likes: Number,
        isPublished: Boolean,
        
    }
}

</script>

<style lang="scss" scoped>

</style>