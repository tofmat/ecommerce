<template>
  <div>
      <div class="col-3 mt-3">
        <div class="card" style="width: 18rem;">
            <img src="https://via.placeholder.com/150x100" class="card-img-top w-100" alt="...">
            <div class="card-body">
                <h5 class="card-title"><router-link :to="{name: 'product', params: {id: '23'}}">Product Title</router-link></h5>
                <strong>Price</strong>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>