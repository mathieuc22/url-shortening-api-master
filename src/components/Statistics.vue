<template>
    <section class="statistics">
        <h1 class="statistics__title">
            Advanced Statistics
        </h1>
        <h2 class="statistics__subtitle">
            Track how your links are performing across the web with our advanced statistics dashboard.
        </h2>
        <ul class="statistics__content">
            <StatisticsCard icon="icon-brand-recognition.svg" title="Brand Recognition" content="Boost your brand recognition with each click. Generic links don't mean a
                    thing. Branded links help instil confidence in your content." />
            <StatisticsCard icon="icon-detailed-records.svg" title="Detailed Records" content="Gain insights into who is clicking your links. Knowing when and where
                    people engage with your content helps inform better decisions." />
            <StatisticsCard icon="icon-fully-customizable.svg" title="Fully Customizable" content="Improve brand awareness and content discoverability through customizable
                    links, supercharging audience engagement." />
            <li class="line"></li>
        </ul>
    </section>
</template>

<script setup>
import StatisticsCard from './StatisticsCard.vue';
</script>

<style lang="scss">
.statistics {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: $color-neutral-bg;

    &__title {
        color: $color-neutral-verydarkviolet;
        font-size: 2.1em;
    }

    &__subtitle {
        margin-top: 30px;
        font-size: 1em;
        font-weight: 500;
        max-width: 600px;
    }

    &__content {
        display: flex;
        gap: 2.5%;
        padding-top: 100px;
        position: relative;
    }
}

.line {
    position: absolute;
    top: 50%;
    width: 100%;
    height: 8px;
    background: $color-primary-cyan;
    z-index: 10;
}
</style>

  