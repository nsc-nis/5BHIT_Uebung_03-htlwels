<template>
  <h1>HTL Wels / {{ klasse }}</h1>
  <h2>JavaScript / DOM-Manipulation / Dynamic List</h2>
  <hr />
</template>

<script>
export default {
  name: 'Header',
  props: {
    klasse: { type: String, required: true },
  },
};
</script>

<style>
h1 {
  font-family: Ubuntu, Helvetica, Arial, sans-serif;
}
</style>
