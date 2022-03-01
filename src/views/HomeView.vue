<template>
  <div>
    <NavBar />

    <div class="sections">
      <WhoIAm />

      <SkillsSection />

      <section class="studies">
        <aside class="studies__title">
          <h2>carreira</h2>
        </aside>
        <section class="studies__list">
          <ul>
            <li>Javascript</li>
            <li>HTML</li>
            <li>CSS</li>
          </ul>
        </section>
      </section>
    </div>
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue';
import WhoIAm from '../components/WhoIAm.vue';
import SkillsSection from '../components/SkillsSection.vue';

export default {
  name: 'HomeView',
  components: { NavBar, WhoIAm, SkillsSection },
};
</script>
<style lang="scss" scoped>
@import '@/assets/scss/index.scss';

.sections {
  display: flex;
  flex-direction: column;
  gap: 60px;
  padding: 60px 0;
}
</style>
