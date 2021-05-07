<template>
  <div>
    <nav>
        <ul>
            <li>Tasks List</li>
            <li>Add a New Task</li>
        </ul>
    </nav>
  </div>
</template>

<script>

export default {
    props: {

    },
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<style scoped>
ul {
    list-style-type: none;
    text-align: center;
    margin: 0;
}
li{
    display: inline-block;
    margin: 0 10px;
    color: #ffe484;
    font-size: 20px;
}
a{
    color:#ffe484;
    text-decoration: none;
    padding: 6px 8px;
    border-radius: 10px;
}
nav {
    background: #7952b3;
    padding: 14px 0;
}
</style>
