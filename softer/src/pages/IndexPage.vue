<template>
  <div>
    <CompHome/>
    <CompAbout/>
    <CompService/>
    <CompFeatures/>
    <CompWorks/>
  </div>
</template>
<script>
import CompHome from 'src/components/CompHome';
import CompAbout from 'src/components/CompAbout';
import CompService from 'src/components/CompService';
import CompFeatures from 'src/components/CompFeatures';
import CompWorks from 'src/components/CompWorks';
export default {
  name:'indexPage',
  components: {
    CompHome,
    CompAbout,
    CompService,
    CompFeatures,
    CompWorks
}
}
</script>


<style>

</style>
