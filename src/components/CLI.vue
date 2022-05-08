<template>
  <div>
    <h1>Sample CLI</h1>
    <!-- <CountNumber /> -->
    <div>
      <textarea id="inputText" rows="1" cols="30"></textarea>
    </div>
    <div>
      <textarea name="resultWindow" id="resultWindow" cols="30" rows="10"></textarea>
    </div>
  </div>


</template>

<script>
// make the import line comment for further re-check
// import CountNumber from "./components/CountNumber.vue";

// some sample data
export default {
  data() {
    return {
      firstName: 'Tri',
      lastName: 'Luu'
    }
  },
}
</script>
