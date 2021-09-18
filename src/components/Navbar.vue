<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <div class="container-fluid">
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <a class="navbar-brand" href="#"><b>Port</b>ofolio</a>
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            
          </ul>
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <router-link class="nav-link">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link">About</router-link>
            </li>
            <li>
              <router-link class="nav-link">Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>

</style>