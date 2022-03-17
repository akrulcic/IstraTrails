<template>
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

          <div class="col-8">
              <card/>

          </div>
    </div>

  
</template>

<script>
// @ is an alias to /src
import card from '@/components/card.vue'

export default {
  name: 'HomeView',
  components: {
    card
  }
}
</script>

<style lang="scss">
.nav_list{
    list-style:none;
    text-align: left;
    padding-left: 30px;
}
</style>
