<template>
    <section class="shorten">
        <form action="" class="shorten__form">
            <input type="url" class="shorten__input" name="url" id="url" placeholder="Shorten a link here..." />
            <input type="submit" class="btn shorten__input shorten__input--submit" value="Shorten It!" />
        </form>
        <div class="shorten__links"></div>
    </section>
</template>

<style lang="scss">

.shorten {
    margin-top: 100px;
    display: flex;
    flex-direction: column;
    background: $color-neutral-bg;

    &__form {
        transform: translateY(-50%);
        background-color: $color-primary-darkviolet;
        padding: 2rem;
        border-radius: 10px;
        background-image: url("../assets/bg-shorten-desktop.svg");
        display: flex;
        justify-content: space-between;
        gap: 1rem;
        width: 100%;
        font-size: 1.2rem;
    }

    &__input {
        width: 100%;
        padding: 0.6rem 1.5rem;
        border-radius: 0.5rem !important;
        border: 1px solid $color-primary-bg;
        font-size: 1em;

        &::placeholder {
            color: $color-neutral-grayishviolet;
        }

        &:focus {
            outline: none;
        }

        &--submit {
            cursor: pointer;
            border: 1px solid $color-primary-cyan;
            flex: 1;
            font-weight: 700;
            transition: all 0.2s ease-in-out;
            &:hover {
                border: 1px solid lighten($color: $color-primary-cyan, $amount: 20%);
            }
            &:active {
                transform: translateY(5px);
            }
        }
    }
}
</style>
