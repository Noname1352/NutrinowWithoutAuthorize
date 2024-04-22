<template>
    <div class="header">
        <img src="../assets/logo.svg">
            <p>Составь свой рацион питания на день за пару минут!</p>
        <Main/>
    </div>
</template>
<script>
import Main from "./Main.vue"
export default {
    components: [Main],
}
</script>
<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    color: white;
}
.nav {
    width: 60%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.link {
    text-decoration: none;
    font-weight: 400;
    cursor: pointer;
    color: white;
    border-radius: 3px;
    border: solid 1px;
    padding: 10px;
}
p {
    margin: 2%;
    width: 100%;
}
</style>