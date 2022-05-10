<template>
    <header>
        <img class="logo" alt="Vue logo" src="../assets/logo.svg" height="50" />
        <nav class="navigation">
            <ul class="navlist">
                <li class="navlist__item">Features</li>
                <li class="navlist__item">Pricing</li>
                <li class="navlist__item">Resources</li>
            </ul>
        </nav>
        <nav class="authentication">
            <ul class="navlist">
                <li class="navlist__item">Login</li>
                <li class="navlist__item btn btn--small">Sign Up</li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss">
header {
    font-weight: 700;
    display: flex;
    align-items: center;
    padding: 50px 165px;
    margin-bottom: 20px;

    p {
        margin-left: 1rem;
    }
}

.logo {
    height: 100%;
}

.navigation {
    margin-left: 10px;
}

.authentication {
    margin-left: auto;
}

.navlist {
    font-size: 15px;

    &__item {
        display: inline-flex;
        margin-left: 2rem;

        &:hover {
            color: $color-neutral-verydarkviolet;
            cursor: pointer;
        }
    }
}
</style>