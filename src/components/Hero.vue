<template>
    <section class="hero">
        <div class="hero__content">
            <h1 class="hero__title">
                {{ title }}
            </h1>
            <p class="hero__text">
                Build your brand's recognition and get detailed insights on how your links are performing.
            </p>
            <a href="#" class="btn hero__getstarted">
                Get Started
            </a>
        </div>
        <div class="hero__illustration">
            <img src="../assets/illustration-working.svg" alt="Illustration working">
        </div>
    </section>
</template>

<style lang="scss">

.hero {
    display: flex;
    text-align: left;
    &__title {
        color: $color-neutral-verydarkviolet;
        font-size: 4.3rem;
    }
}

</style>

<script setup>

defineProps({
  title: String
})

</script>