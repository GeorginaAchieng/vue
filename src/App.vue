<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  

      <div class="container">
            <nav>
                <div class='nav-link'>
                  <RouterLink to="/" class='nav-item'>Home</RouterLink>
                  <RouterLink to="/about" class='nav-item'>About</RouterLink>
                  <RouterLink to="/services" class='nav-item'>Services</RouterLink>
                  <RouterLink to="/contact" class='nav-item'>Contact</RouterLink>
                  <RouterLink to="/login" class='nav-item'>Login</RouterLink>
                  <RouterLink to="/signup" class='nav-item'>Signup</RouterLink>
                </div>
            </nav>
      </div>
  <RouterView />
</template>

<style scoped>
.nav-link{
  background-color: darkgreen;
  padding: 14px;

}
.nav-link .nav-item{
padding: 10px;
color: white;
font-weight: bold;
font-size: large;
text-decoration: none;
}

</style>
