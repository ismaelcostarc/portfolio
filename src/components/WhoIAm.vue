<template>
  <section class="whoIAm" id="quem-sou">
    <div class="row">
      <aside class="col col-3">
        <img src="@/assets/img/picture.png" alt="Ismael Costa" />
      </aside>
      <section class="col col-9">
        <div>
          <p class="specialization font-condensed text-md">desenvolvedor front-end</p>

          <h2 ref="hello" class="font-mono text-3xl">olá, me chamo ismael_</h2>
        </div>

        <p class="description font-sans-serif text-light text-lg">
          Desenvolvedor front-end com foco em Javascript moderno, Vue.js, React, Node e UX/UI.
          Conhecimento em integração com APIs RESTful, métodos ágeis, banco de dados, programação
          funcional e orientada a objetos.
        </p>
      </section>
    </div>
  </section>
</template>
<script>
export default {
  mounted: {
    /*  mounted() {
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'l');
      }, 400);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'á');
      }, 600);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', ',');
      }, 800);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', ' ');
      }, 1000);

      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'm');
      }, 1200);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'e');
      }, 1400);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'u');
      }, 1600);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', ' ');
      }, 1800);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'n');
      }, 2000);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'o');
      }, 2200);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'm');
      }, 2400);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'e');
      }, 2600);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', ' ');
      }, 2800);

      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'é');
      }, 3000);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', ' ');
      }, 3200);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'i');
      }, 3400);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 's');
      }, 3600);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'm');
      }, 3800);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'a');
      }, 4000);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'e');
      }, 4200);
      setTimeout(() => {
        this.$refs.hello.insertAdjacentHTML('beforeEnd', 'l');
      }, 4400);
    }, */
  },
};
</script>
<style lang="scss" scoped>
@import '@/assets/scss/index.scss';

img {
  width: 100%;
  border: 10px solid #000;
  border-style: double;
}

.whoIAm {
  padding: 120px 0;

  section {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 30px;
    justify-content: center;
    padding: 30px;

    .specialization {
      color: $primary;
      margin-bottom: 15px;
    }

    .description {
      line-height: 40px;
    }
  }
}
</style>
