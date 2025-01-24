<template>
    <header>
        <h1>
            <img src="../assets/images/tyt-logo.png" alt="Logo" />
        </h1>
    </header>
</template>

<script lang="ts">
export default {
    name: "Sidebar",
    data() {
        return {};
    },
};
</script>

<style scoped>
header {
    padding: 1rem;
    background: #e9ecef;
    width: 100%;
    height: 100vh;
}
@media only screen and (max-width: 768px) {
    header {
        padding: 0.1rem;
        height: auto;
        align-items: center;
        display: flex;
        justify-content: center;
    }
}
</style>
