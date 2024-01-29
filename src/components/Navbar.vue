<template>
    <nav>
        <router-link to="/">
            <img id="logo" src="../assets/logo.png" alt="">
        </router-link>
        <router-link to="/">Home</router-link> |
        <router-link to="/pedidos">About</router-link>
    </nav>
</template>

<script>


    export default{
        name: "Navbar",
    }
</script>