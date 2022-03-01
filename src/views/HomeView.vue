<template>
  <div>
    <WhoIAm />
    <SkillsSection />
    <ExperienceSection />
    <AcademicFormation />
    <NavBar />
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue';
import WhoIAm from '../components/WhoIAm.vue';
import SkillsSection from '../components/SkillsSection.vue';
import ExperienceSection from '../components/ExperienceSection.vue';
import AcademicFormation from '../components/AcademicFormation.vue';

export default {
  name: 'HomeView',
  components: {
    NavBar,
    WhoIAm,
    SkillsSection,
    ExperienceSection,
    AcademicFormation,
  },
};
</script>
