<template>
  <div id="app" class="container is-fullhd">
    <nav class="navbar has-shadow">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item" href="http://bulma.io">
            Klinik
          </a>
          <div class="navbar-burger burger">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
        <div class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item ">
              <b-icon icon="address-book"></b-icon>
              Phòng Khám
            </a>
            <a class="navbar-item ">
              <b-icon icon="address-book"></b-icon>
              Love
            </a>
          </div>

          <div class="navbar-end">
            <div class="navbar-item">
              <a class="bd-tw-button button">
                <span class="icon">
                  <i class="fa fa-twitter"></i>
                </span>
                <span>
                  User
                </span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <router-view style="margin-top: 10px"></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>

</style>
