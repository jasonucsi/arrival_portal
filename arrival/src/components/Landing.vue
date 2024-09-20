<!-- <template>
  <div>
    <div class="pre-arrival">
      <h1>International Pre-Arrival Checklist</h1>
      <a href="https://www.ucsiuniversity.edu.my/Admission-Pre-Arrival/international/kuala-lumpur-campus" target="_blank">Click Here!</a>
    </div>
    <div class="arrival">
      <h1>International Arrival Checklist</h1>
      <a href="https://www.ucsiuniversity.edu.my/admission-arrival/international/Kuala-lumpur-campus" target="_blank">Click Here!</a>
    </div>
    <div class="orientation">
      <h1>Orientation Day</h1>
      <a href="https://www.ucsiuniversity.edu.my/orientation-day" target="_blank">Click Here!</a>
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

.arrival {
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
  color: #e00f16;
}
</style> -->

<template>
  <div class="container">
    <div class="section">
      <div class="header">
        <i class="fas fa-folder"></i>
        <h3>International Pre-Arrival Checklist</h3>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="https://www.ucsiuniversity.edu.my/Admission-Pre-Arrival/international/kuala-lumpur-campus" target="_blank">Admission Pre Arrival</a>
      </div>
      <!-- <div class="item">
        <i class="fas fa-file"></i>
        <a href="#">Laboratory Safety Guide</a>
      </div> -->
    </div>
    <div class="section">
      <div class="header">
        <i class="fas fa-folder"></i>
        <h3>International Arrival Checklist</h3>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="https://www.ucsiuniversity.edu.my/admission-arrival/international/Kuala-lumpur-campus" target="_blank">Admission Arrival</a>
      </div>
    </div>
    <div class="section">
      <div class="header">
        <i class="fas fa-folder"></i>
        <h3>Orientation Day</h3>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="https://www.ucsiuniversity.edu.my/orientation-day" target="_blank">Click Here!</a>
      </div>
    </div>
    <!-- <div class="section">
      <div class="header">
        <i class="fas fa-folder"></i>
        <h3>Extra-curricular Learning Experience (ELE)</h3>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="#">ELE Handbook</a>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="#">ELE E-Briefing</a>
      </div>
      <div class="item">
        <i class="fas fa-file"></i>
        <a href="#">ELE Portal Manual for Student Organisations</a>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>

<style scoped>
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center; /* Center the sections horizontally */
  align-items: flex-start; /* Align items to the top */
  max-width: 1200px; /* Optional: set a max width for better layout */
  margin: 0 auto; /* Center the container itself */
}

.section {
  width: 48%; /* Each section takes up 48% of the container */
  margin: 10px; /* Add some space between sections */
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.header {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}

.header i {
  font-size: 24px;
  margin-right: 10px;
}

.header h3 {
  margin: 0;
}

.item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.item i {
  font-size: 16px;
  margin-right: 10px;
}

.item a {
  text-decoration: none;
  color: #e00f16;
}

.item a:hover {
  text-decoration: underline;
}

</style>
