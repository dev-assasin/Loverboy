<template>
<div class="container">
  <nav class="navbar is-transparent">
    <div class="navbar-brand">
      <router-link class="navbar-item" to="/">
        <b class="title">loverboy</b>
      </router-link>

      <div class="navbar-burger burger" data-target="navMenuTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div class="navbar-menu">
      <div class="navbar-start navbar-middle">
        <router-link to="newest" class="navbar-item"><b class="subtitle">Newest Users</b></router-link>
        <router-link to="online" class="navbar-item nav-item"><b class="subtitle">Who's online <span class="icon tag is-white has-text-success is-small" style="margin-top:-15px; margin-left:-5px"><i class="fa fa-circle"></i></span></b></router-link>
      </div>

      <div class="navbar-end">
        <a class="navbar-item">
          <div class="search-icon">
            <span class="icon" style="color: #333;">
              <i class="fa fa-lg fa-search" style="margin-top: 11px"></i>
            </span>
          </div>
        </a>
        <a class="navbar-item">
            <img class="img" src="../assets/images/default user.jpeg" height="40" width="40" />
            <span class="icon has-text-danger badge"><i class="fa fa-comment fa-2x"></i></span>
        </a>
      </div>
    </div>
  </nav>    
</div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
