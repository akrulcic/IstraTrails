<template>


  <nav id="nav" class="navbar navbar-expand-md navbar-light">
    <router-link to="/" class="navbar-brand">
                <img src="@/assets/logo.png" height="50" class="d-inline-block align-top" alt="Logo" />
            </router-link>
            
    <!--<router-link to="/">Home</router-link> |
    <router-link to="/login">Login</router-link>
    <router-link to="/signup">Signup</router-link> -->
    
  </nav>
  <br/>
  <br/>

  <div class="row">
    <div class="col-4">
      <nav class="navbar navbar-expand-lg navbar-light mb-2">
      <div class="sidebar">
        
        <ul class="nav_list">
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Najpopularnije</span>
            </a>
          </li>
          <br/>
          <br/>
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Novo</span>
            </a>
          </li>
          <br/>
          <br/>
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Težina staze:</span>
            </a>
          </li>
          <br/>
          <br/>
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Najbolje ocjenjeno</span>
            </a>
          </li>
          <br/>
          <br/>
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Duljina staze</span>
            </a>
          </li>
          <br/>
          <br/>
          <li>
            <a href="#">
              <img src="@/assets/pin.png" height="20"  />
              <span class="links_name">Želim posjetiti</span>
            </a>
          </li>

        </ul>
      </div>
      </nav>
    </div>
    <div class="col-8"></div>
  </div>

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
.nav_list{
    list-style:none;
    text-align: left;
    padding-left: 30px;
}
</style>
