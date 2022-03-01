<template>
  <div class="skills__wrapper">
    <section class="skills row">
      <section class="skills__list">
        <ul>
          <li>Javascript</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
      </section>
      <aside class="skills__title font-mono text-3xl">
        <h2>skills</h2>
      </aside>
    </section>
  </div>
</template>
<script></script>
<style lang="scss" scoped>
@import '@/assets/scss/index.scss';

.skills__wrapper {
  background-color: $primary;

  .skills {
    display: flex;
    justify-content: space-between;
    color: #fff;
    padding: 60px;

    .skills__list {
      width: 50%;
    }

    .skills__title {
      width: 50%;
      text-align: right;
    }
  }
}
</style>
