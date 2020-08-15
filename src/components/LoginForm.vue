<template>
  <div>
    <b-field label="דואר אלקטרוני: " custom-class="is-large has-text-white">
      <b-input></b-input>
    </b-field>

    <b-field label="סיסמא:" custom-class="is-large has-text-white">
      <b-input type="password"></b-input>
    </b-field>
    <b-button expanded type="is-success">
      התחבר
    </b-button>
  </div>
</template>
<script>
export default {
  name: "LoginForm",
  data: function() {
    return {
      userError: "",
      passwordError: ""
    };
  },
  methods: {
    login: function() {
      if (!this.email) {
        this.userError = "you have to insert an email";
      }
      if (!this.password) {
        this.userError = "you have to insert password";
      }
    }
  }
};
</script>
