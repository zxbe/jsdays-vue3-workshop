<template>
  <h3>Work Tracker</h3>
  <h5>Budget: [xx] days, logged days: [xx]</h5>
  <p>
    <span class="badge badge-warning">Out of money</span>
  </p>
  <table class="table table-bordered">
    <tr class="header">
      <td>Project Name</td>
      <td>Estimated Days</td>
      <td>Logged Days</td>
      <td>Actions</td>
    </tr>
  </table>
</template>

<script>
import { projects } from "./projects";

export default {
  name: "App",
  data() {
    return {};
  },
  computed: {},
  methods: {},
};
</script>

<style scoped>
.header {
  font-weight: bold;
  background-color: #f5f5f5;
}
</style>
