<script setup></script>

<template>
    <header class="bg-blue-500 p-4 flex justify-end items-center">
        <nav class="flex row gap-20 mr-10">
            <router-link to="/">Home</router-link>
            <router-link to="/Login">Login</router-link>
        </nav>
    </header>
    <main>
        <router-view></router-view>
    </main>
</template>