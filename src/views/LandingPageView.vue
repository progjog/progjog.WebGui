<script setup lang="ts">
  import NavBar from '@/components/NavBar.vue';
</script>

<template>


  <section class="filteroptions_sidebar">

    <form>
      <input type="text" placeholder="search" />

      <br/>

      <label for="duration">Duration in weeks:</label>
      <select name="duration" id="duration">
        <option value="4">4</option>
        <option value="8">8</option>
        <option value="12">12</option>
        <option value="16">16</option>
      </select>

      <br />

      <label for="sessions">Sessions per week:</label>
      <select name="sessiont per week" id="sessions">
        <option value="1-3">1-3</option>
        <option value="3-5">3-5</option>
        <option value="5-7">5-7</option>
        <option value="7+">7+</option>
      </select>

      <br />

      <label for="rating"> Minimum rating:</label>
      <select name="minimum rating" id="rating">
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
      </select>

    </form>
  </section>

  <div class="quick-filter-navigations">
    <ul>
      <li> trail </li>
      <li> 5k </li>
      <li> 10k </li>
      <li> 21.1k </li>
      <li> marathon </li>
      <li> ultra </li>
    </ul>
  </div>

  <div class="list-trainingplans">

    <ul>
      <li> 

        <div class="trainingplan_preview">
          <!-- trainingplan preview goes here -->
        </div>

      </li>
    </ul>

  </div>
    


</template>
