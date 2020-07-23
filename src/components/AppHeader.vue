<template>
  <div>
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
          <a class="navbar-brand" href="#">Navbar</a>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
              <li class="nav-item active">
                <router-link class="nav-link" to="/">Home <span class="sr-only">(current)</span></router-link>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Products</a>
              </li>
            </ul>
            <div>
              <ul class="navbar-nav">
                <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  0 cart
                </a>
                <div @click="$event.stopPropagation()">
                  <MiniCart/>
                </div>
              </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
  </div>
</template>

<script>
import MiniCart from './MiniCart'
export default {
components: {
  MiniCart
}
}
</script>

<style>

</style>