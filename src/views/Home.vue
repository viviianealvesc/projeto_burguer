<template>
  <div class="main-container">
    <Banner />
   <h1>Monte o seu burger</h1>
   <BurgForm />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import BurgForm from "../components/BurgForm.vue"

export default {
  name: "Home",
  components: {
    Banner,
    BurgForm
  }
}
</script>
