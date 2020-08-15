<template>
  <div>
    <div class="columns">
      <div class="column">
        <Navbar />
      </div>
    </div>
    <div class="columns is-vcentered">
      <div class="column">
        <div class="container has-text-centered">
          <h1 class="title has-text-white">
            ניהול מאגר הספקים במקום אחד!
          </h1>
        </div>
      </div>
    </div>
    <div class="tile is-ancestor">
      <div class="tile is-vertical">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article
              class="tile is-child notification is-primary has-text-centered"
            >
              <p class="title">הרשמה מקוונת ונוחה</p>
            </article>
          </div>
          <div class="tile is-parent">
            <article
              class="tile is-child notification is-info has-text-centered"
            >
              <p class="title">רישום למאגר ספקים למגוון ארגונים</p>
            </article>
          </div>
          <div class="tile is-parent">
            <article
              class="tile is-child notification is-success has-text-centered"
            >
              <p class="title">אישור ספקים למאגר בקליק</p>
            </article>
          </div>
          <div class="tile is-parent">
            <article
              class="tile is-child notification is-warning has-text-centered"
            >
              <p class="title">רוצה לדעת עוד צור איתנו קשר</p>
            </article>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
export default {
  name: "Home",
  components: {
    Navbar
  }
};
</script>
