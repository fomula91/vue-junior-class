<template>
  <div>
    <app-header v-bind:propsdata="str" v-on:renew="renewStr"></app-header>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
export default {
  data: function () {
    return {
      str: "appHeader",
    };
  },
  components: {
    "app-header": AppHeader,
  },
  methods: {
    renewStr: function (event) {
      console.log(event);
      this.str = "hi";
    },
  },
};
</script>

<style></style>
