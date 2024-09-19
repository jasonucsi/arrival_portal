<template>
  <div>
    <div class="pre-arrival">
      <h1>International Pre-Arrival Checklist</h1>
      <a href="https://www.ucsiuniversity.edu.my/Admission-Pre-Arrival/international/kuala-lumpur-campus" target="_blank">Click Here!</a>
    </div>
    <div class="arrival">
      <h1>International Arrival Checklist</h1>
      <a href="https://www.ucsiuniversity.edu.my/admission-arrival/international/Kuala-lumpur-campus" target="_blank">Click Here!</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>

<style scoped>
.pre-arrival {
  margin-bottom: 50px; /* Adjust this value to control the space */
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
