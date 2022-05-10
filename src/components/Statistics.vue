<template>
    <section class="statistics">
        <h1 class="statistics__title">
            Advanced Statistics
        </h1>
        <h2 class="statistics__subtitle">
            Track how your links are performing across the web with our advanced statistics dashboard.
        </h2>
        <ul class="statistics__content">
            <li class="statcard">
                <div class="statcard__icon">
                    <img src="src/assets/icon-brand-recognition.svg" alt="Brand Recognition icon">
                </div>
                <h3 class="statcard__title">Brand Recognition</h3>
                <div class="statcard__content">Boost your brand recognition with each click. Generic links don't mean a
                    thing. Branded links help instil confidence in your content.</div>
            </li>
            <li class="statcard">
                <div class="statcard__icon">
                    <img src="src/assets/icon-detailed-records.svg" alt="Detailed Records icon">
                </div>
                <h3 class="statcard__title">Detailed Records</h3>
                <div class="statcard__content">Gain insights into who is clicking your links. Knowing when and where
                    people engage with your content helps inform better decisions.</div>
            </li>
            <li class="statcard">
                <div class="statcard__icon">
                    <img src="src/assets/icon-fully-customizable.svg" alt="Fully Customizable icon">
                </div>
                <h3 class="statcard__title">Fully Customizable</h3>
                <div class="statcard__content">Improve brand awareness and content discoverability through customizable
                    links, supercharging audience engagement.</div>
            </li>
            <li class="line"></li>
        </ul>
    </section>
</template>

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


.statcard {
    flex: 1;
    background: $color-primary-bg;
    position: relative;
    padding: 60px 30px;
    border-radius: 5px;
    text-align: left;
    display: flex;
    flex-direction: column;
    z-index: 20;
    &:nth-child(1) {
        align-self: flex-start;
    }
    &:nth-child(2) {
        align-self: center;
    }
    &:nth-child(3) {
        margin-top: 80px;
    }
    &__icon {
        border-radius: 50%;
        height: 80px;
        width: 80px;
        display: flex;
        align-items: center;
        justify-content: center;
        background: $color-primary-darkviolet;
        position: absolute;
        left: 20px;
        transform: translateY(-100px);
    }
    &__title {
        margin-top: 20px;
        color: $color-neutral-verydarkviolet;
        font-size: 1.2em;
    }
    &__content {
        margin-top: 10px;
        font-size: 0.83em;
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

  