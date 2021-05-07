<template>

    <div id="footer-wrapper">
       <nav> 
            <p>{{copyright}}</p>
        </nav>
    </div>

</template>

<script>

export default {
    props: {

    },

    data() {
    return {
     copyright: 'Copyright 2021 MyTodo App'
    }
    },

}
</script>

<style scoped>
#footer-wrapper {
    background: #9d9dd8;
    padding: 2px;
    margin-top:40px;
    text-align: center;
}
</style>
