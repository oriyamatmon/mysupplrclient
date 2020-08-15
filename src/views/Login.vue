<template>
  <section class="hero is-grey-light is-fullheight">
    <div class="hero-body">
      <div class="container">
        <img src="../assets/wizbizlogo.jpeg" />
        <div class="columns is-centered">
          <div
            class="column is-5-tablet is-4-desktop is-3-widescreen has-background-blue"
          >
            <LoginForm />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import LoginForm from "@/components/LoginForm.vue";
export default {
  name: "Home",
  components: {
    LoginForm
  }
};
</script>
