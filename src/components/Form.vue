<template>
    <div class="box no-radius">
        <div class="columns">
            <div
                class="column is-8"
                role="form"
                aria-label="Form to create a new task"
            >
                <input
                    class="input"
                    type="text"
                    placeholder="What task do you want to begin?"
                />
            </div>
            <div class="column">
                <div
                    class="is-flex is-align-items-center is-justify-content-space-between"
                >
                    <section>
                        <strong>00:00:00</strong>
                    </section>
                    <button class="button">
                        <span class="icon">
                            <i class="fas fa-play"></i>
                        </span>
                        <span>play</span>
                    </button>
                    <button class="button">
                        <span class="icon">
                            <i class="fas fa-stop"></i>
                        </span>
                        <span>stop</span>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
export default {
    name: "Form",
    setup() {
        return {};
    },
};
</script>

<style scoped>
.no-radius {
    border-radius: 0%;
}
</style>
