<template>
  <div id="app">
    <h1>Calculator</h1>

    <input type="number" value="0" placeholder="Value" /> <br /><br />

    <select>
      <option>+</option>
      <option>-</option>
      <option>/</option>
      <option>*</option>
    </select>
    <br /><br />

    <input type="number" value="0" placeholder="Value" /> <br /><br />

    <button @click="calculate">Calculate!</button>

    <br /><br />

    <Result />
  </div>
</template>

<script>
import Result from "./components/Result";

export default {
  name: "App",
  components: {
    Result,
  },
  methods: {
    calculate: () => {
      console.log("bla bla bla");
      window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
    },
  },
};
</script>
