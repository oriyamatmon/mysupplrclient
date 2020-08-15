<template>
  <b-navbar type="is-warning" :transparent="true">
    <template slot="end">
      <b-navbar-item href="#">
        ספקים
      </b-navbar-item>
      <b-navbar-item href="#">
        ארגונים
      </b-navbar-item>
      <b-navbar-item href="#">
        צור קשר
      </b-navbar-item>
      <b-navbar-item href="#">
        איך זה עובד
      </b-navbar-item>
    </template>
    <template slot="start">
      <b-navbar-item tag="div">
        <div class="buttons">
          <a class="button is-light is-outlined">
            <strong>כניסת ארגונים</strong>
          </a>
          <a class="button is-light is-outlined">
            <strong> כניסת ספקים </strong>
          </a>
        </div>
      </b-navbar-item>
    </template>
    <template slot="end">
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img
          src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
          alt="wizbiz logo"
        />
      </b-navbar-item>
    </template>
  </b-navbar>
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>
