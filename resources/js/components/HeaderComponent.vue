<template>
  <div class="container-fluid bg-dark mb-3">
    <div class="container">
      <nav class="navbar navbar-dark">
        <span class="navbar-brand mb-0 h1">Internalize English</span>
        <div>
          <router-link v-bind:to="{name: 'vocabulary.list'}">
            <button class="btn btn-success">Vocubulary</button>
          </router-link>
          <router-link v-bind:to="{name: 'vocabulary.create'}">
            <button class="btn btn-success">Add</button>
          </router-link>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
  export default {}
</script>