<template>
  <div>
    <CompHome/>
    <CompAbout/>
    <CompService/>
    <CompFeatures/>
  </div>
</template>
<script>
import CompHome from 'src/components/CompHome';
import CompAbout from 'src/components/CompAbout';
import CompService from 'src/components/CompService';
import CompFeatures from 'src/components/CompFeatures.vue';
export default {
  name:'indexPage',
  components: {
    CompHome,
    CompAbout,
    CompService,
    CompFeatures
}
}
</script>


<style>

</style>
