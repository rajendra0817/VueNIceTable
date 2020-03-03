<template>
  <div id="app">
    <VueNiceTable :columns="columns" :rows="rows" />
  </div>
</template>

<script>
import VueNiceTable from "./components/VueNiceTable";

export default {
  name: "App",
  components: {
    VueNiceTable
  },
  data() {
    return {
      rows: [],
      columns: [
        {
          label: "filed_name",
          field: "field",
          tdClass: "text-left",
          thClass: "text-left"
        }
      ]
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
