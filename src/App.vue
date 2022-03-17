<template>


  <nav id="nav" class="navbar navbar-light">
    <router-link to="/" class="navbar-brand">
      <img src="@/assets/logo.png" height="50" class="d-inline-block align-top" alt="Logo" />
    </router-link>

    <form id="search" class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="traži" aria-label="Search">
    </form>

    <router-link to="" class="navbar-brand">
      <img id="user" src="@/assets/user.png" height="35" class="d-inline-block" alt="user" />
    </router-link>
            
    <!--<router-link to="/">Home</router-link> |
    <router-link to="/login">Login</router-link>
    <router-link to="/signup">Signup</router-link> -->
    
  </nav>
  <br/>
  <br/>

  

  <router-view/>
</template>

<style lang="scss">

nav {
  padding: 30px;

  a {
    color: #000000;

    &.router-link-exact-active {
      color: #42b983;
    }
  }

}


</style>
