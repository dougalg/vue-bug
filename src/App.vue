<template>
  <div id="app">
    <h2>Overview</h2>
    <p>This should be a table with 5 row, but it only has 1</p>
    <table>
      <tr>
        <th># of members</th>
        <td>{{ totalMembers }}</td>
      </tr>
      <tr>
        <th># of Invitess</th>
        <td>Coming soon</td>
      </tr>
      <tr>
        <th># of Discussion Topics</th>
        <td>Coming soon</td>
      </tr>
      <tr>
        <th># of Posts</th>
        <td>Coming soon</td>
      </tr>
      <tr>
        <th># of Shared Files</th>
        <td>Some text</td>
      </tr>
    </table>
  </div>
</template>

<script lang="ts">
export default {
  name: 'App',
  setup() {
    return {
      totalMembers: 123,
    };
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
