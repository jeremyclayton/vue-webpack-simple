<template>
<div id="app">
    <nav class="navbar navbar-default navbar-fixed-top">
        <div class="container">
            <h3>Header</h3>
        </div>
    </nav>
    <ul id='list'>
        <router-link to="/book/">Book</router-link>
    </ul>
</div>
</template>

<script>
export default {
    name: 'app',

}
</script>

<style lang="scss">
#list {
    padding-top: 50px;
}

</style>
