<template>
  <header>
    <img alt="Vue logo" src="../assets/logo.svg" height="50" />
    <nav>
      <ul>
        <li>Features</li>
        <li>Pricing</li>
        <li>Resources</li>
      </ul>
    </nav>
    <nav>
      <ul>
        <li>Login</li>
        <li class="btn">Sign Up</li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss">
header {
  font-weight: 700;
  display: flex;
  padding: 0.5rem 1rem;
  p {
    margin-left: 1rem;
  }
}

nav {
  margin-left: auto;

  ul {
    font-size: 15px;
    list-style: none;
  }

  ul li {
    display: inline-flex;
    margin-left: 1rem;
    &:hover {
      color: $color-neutral-verydarkviolet;
      cursor: pointer;
    }
  }
}
</style>