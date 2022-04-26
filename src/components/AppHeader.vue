<template>
    <header>
        <img class="logo" alt="Vue logo" src="../assets/logo.svg" height="50" />
        <nav class="navigation">
            <ul>
                <li>Features</li>
                <li>Pricing</li>
                <li>Resources</li>
            </ul>
        </nav>
        <nav class="authentication">
            <ul>
                <li>Login</li>
                <li class="btn btn--small">Sign Up</li>
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

ul {
    font-size: 15px;
    list-style: none;
}

ul li {
    display: inline-flex;
    margin-left: 2rem;

    &:hover {
        color: $color-neutral-verydarkviolet;
        cursor: pointer;
    }
}
</style>