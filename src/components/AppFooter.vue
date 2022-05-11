<template>
    <footer class="footer">
        <img class="logo" alt="Vue logo" src="../assets/logo.svg" height="50" />
        <div class="footer__links">
            <ul class="links" aria-label="Features">
                <li class="links_item">
                    Link Shortening
                </li>
                <li class="links_item">
                    Branded Links
                </li>
                <li class="links_item">
                    Analytics
                </li>
            </ul>
            <ul class="links" aria-label="Resources">
                <li class="links_item">
                    Blog
                </li>
                <li class="links_item">
                    Developers
                </li>
                <li class="links_item">
                    Support
                </li>
            </ul>
            <ul class="links" aria-label="Company">
                <li class="links_item">
                    About
                </li>
                <li class="links_item">
                    Our Team
                </li>
                <li class="links_item">
                    Careers
                </li>
                <li class="links_item">
                    Contact
                </li>
            </ul>
        </div>
        <div class="footer__social">
            <img src="../assets/icon-facebook.svg" alt="" class="src">
            <img src="../assets/icon-twitter.svg" alt="" class="src">
            <img src="../assets/icon-pinterest.svg" alt="" class="src">
            <img src="../assets/icon-instagram.svg" alt="" class="src">
        </div>
    </footer>

</template>

<style lang="scss" scoped>
ul:before {
    content: attr(aria-label);
    font-weight: 700;
}

.footer {
    background: $color-neutral-verydarkviolet;
    color: $color-primary-bg;
    display: flex;
    justify-content: space-between;
    padding: 50px 165px;

    &__links {
        display: flex;
        flex: 1;
        justify-content: space-between;
        margin-left: 24%;
    }

    &__social {
        display: flex;
        flex: 1;
        max-width: 15%;
        margin-left: 50px;
        justify-content: space-between;
        align-items:flex-start;
    }
}

.links {
    text-align: left;
    font-size: 0.9em;
}


</style>