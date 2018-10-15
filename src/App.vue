<template>
  <div id="app">
    <section-hero/>
    <section-get-started/>
    <section-buisnesses/>
    <section-contact/>
    <section-partners/>
    <the-footer/>
  </div>
</template>

<script>
import SectionHero from './components/Sections/SectionHero'
import SectionContact from './components/Sections/SectionContact'
import SectionGetStarted from './components/Sections/SectionGetStarted'
import SectionBuisnesses from './components/Sections/SectionBuisnesses'
import SectionPartners from './components/Sections/SectionPartners'
import TheFooter from './components/TheFooter/TheFooter'

export default {
  name: 'App',
  components: {
    SectionHero,
    SectionContact,
    SectionGetStarted,
    SectionBuisnesses,
    SectionPartners,
    TheFooter
  }
}
</script>

<!-- Global CSS -->
<style lang="scss">
  @import "./src/style/components/index";
  @import "./src/style/base/index";
</style>

<style scoped>
#app {
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  }
</style>
