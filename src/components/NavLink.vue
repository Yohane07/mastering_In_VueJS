<template>
    <a href="url">{{ text }}</a> <span>{{ separateur }}</span> <a href="url2">{{ text2 }}</a>
</template>

<script>
export default {
    name: 'NavLink',
    props:['url', 'text', 'separateur', 'url2', 'text2']
    }
</script>

<style>
a{
    text-decoration: none;
    color: #42b983;
}
</style>