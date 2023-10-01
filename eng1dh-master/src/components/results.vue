<template>
  <div v-if="results">
    <div v-for="(result, index) in results" :key="index">
      <p>Nom et Prénom: {{ result.fullName }}</p>
      <br />
      <p>Email: {{ result.email }}</p>
      <br />
      <p>Numéro: {{ result.phoneNumber }}</p>
      <br />
      <p>Genre: {{ result.gender }}</p>
      <br />
      <p>Poste: {{ result.post }}</p>
      <br />
      <p>Code: {{ result.code }}</p>
      <br />
      <div style="display:flex">
        <img style="width:33%;height:auto" :src="result.frontCin" alt="zebi" />
        <img style="width:33%;height:auto" :src="result.backCin" alt="zebi" />
        <img style="width:33%;height:auto" :src="result.selfieCin" alt="zebi" />
      </div>
      <br /><br />
      <hr />
    </div>
  </div>
</template>
<script>
import axios from "axios";
export default {
  name: "Results",
  data: () => {
    return {
      results: null,
    };
  },
  async beforeMount() {
    var results = await axios.get("https://first-dilevery.herokuapp.com/api/results/zebeb");
    this.results = results.data;
  },
};
</script>
