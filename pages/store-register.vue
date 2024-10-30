<template>
    <NuxtLayout :name="layout">
        <store-register />
    </NuxtLayout>
</template>

<script setup lang="ts">
import StoreRegister from "../modules/store-register/index.vue";

const layout = "default";
</script>
