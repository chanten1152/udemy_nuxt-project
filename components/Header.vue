<template>
  <div>
    <header class="header">
      <ul class="nav-items">
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/Users">Users</nuxt-link>
        </li>
      </ul>
    </header>
  </div>
</template>

<style scoped>
  .header{
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: lightgray;
  }
  .nav-items{
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
  }

  .nav-items a {
    text-decoration: none;
    color: black;
  }
  .nav-items a:hover,
  .nav-items a:active {
    color: white;
  }

</style>