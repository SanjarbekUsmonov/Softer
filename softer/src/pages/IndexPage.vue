<template>
  <div>
    <CompHome/>
    <CompAbout/>
    <CompService/>
  </div>
</template>
<script>
import CompHome from 'src/components/CompHome';
import CompAbout from 'src/components/CompAbout';
import CompService from 'src/components/CompService';
export default {
    components: {
    CompHome,
    CompAbout,
    CompService
}
}
</script>
<style>

</style>
