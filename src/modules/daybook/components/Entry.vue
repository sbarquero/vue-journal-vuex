<template>
    <div
      class="entry-container mb-3 pointer p-2"
      @click="$router.push({ name: 'entry', params: { id: 10 }})"
    >
        <!-- Título -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">19</span>
            <span class="mx-1 fs-5">Agosto</span>
            <span class="mx-2 fw-light">2021, jueves</span>
        </div>
        <!-- Descripción -->
        <div class="entry-description">
            Amet irure consectetur eu nulla consectetur aliquip exercitation ex consectetur quis exercitation cupidatat qui ullamco. Do sit ut est officia deserunt occaecat ut dolor deserunt tempor ut. Sint proident deserunt aute anim do nostrud aute incididunt dolor ad Lorem exercitation tempor.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    borde-botton: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}
</style>