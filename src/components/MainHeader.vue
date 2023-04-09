<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header__logo">MoGo</div>

        <nav class="nav">
          <NavLink text="About" to="#" />
          <NavLink text="Service" to="#" />
          <NavLink text="Blog" to="#" />
          <NavLink text="Work" to="#" />
          <NavLink text="Contact" to="#" />
          <!-- <a class="nav__link" href="#">
            <i class="fas fa-shopping-cart"></i>
          </a>
          <a class="nav__link" href="#">
            <i class="fas fa-search"></i>
          </a> -->
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
import NavLink from "./NavLink.vue";
export default {
  components: {
    NavLink,
  },
};
</script>

<style scoped>
.header {
  width: 100%;
  padding-top: 30px;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}

.header__inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header__logo {
  font-size: 30px;
  font-weight: 700;
  color: #fff;
}

/*Nav*/

.nav {
  font-size: 14px;
  text-transform: uppercase;
}
</style>
