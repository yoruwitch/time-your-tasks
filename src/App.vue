<script lang="ts">
import Form from "./components/Form.vue";
import Sidebar from "./components/Sidebar.vue";

export default {
    components: { Sidebar, Form },
};
</script>

<template>
    <main class="columns is-gapless is-multiline">
        <div class="column is-one-quarter">
            <Sidebar />
        </div>
        <div class="column is-three-quarter">
            <Form />
        </div>
    </main>
</template>

<style >
body {
    background-color: rgb(3, 20, 35);
}
</style>
