<template>
    <header class="app-header">
        <img src="../assets/img/logo.svg">
        <ul class="clean-list">
            <li>
                <RouterLink to="/">Features</RouterLink>
            </li>
            <li>
                <RouterLink to="/">Team</RouterLink>
            </li>
            <li>
                <RouterLink to="/">Sign In</RouterLink>
            </li>
        </ul>
    </header>
</template>
<script>
import { RouterLink, RouterView } from 'vue-router'
</script>