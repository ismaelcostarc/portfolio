<template>
  <div>
    <nav class="container">
      <img src="@/assets/img/logo.png" alt="Ismael Costa" height="20" />
      <ul>
        <li>&lt; quem sou /&gt;</li>
        <li>skills</li>
        <li>estudos</li>
        <li>carreira</li>
        <li>contatos</li>
        <li>download CV <i class="fas fa-download"></i></li>
      </ul>
    </nav>

    <div class="sections">
      <section class="whoIAm container">
        <aside class="img__wrapper">
          <img src="@/assets/img/picture.png" alt="Ismael Costa" />
        </aside>
        <section>
          <div>
            <p class="specialization">desenvolvedor front-end</p>

            <h2 ref="hello">o</h2>
            <h2>_</h2>
          </div>

          <p class="description">
            Desenvolvedor front-end com foco em Javascript moderno, Vue.js, React, Node e UX/UI.
            Conhecimento em integração com APIs RESTful, métodos ágeis, banco de dados, programação
            funcional e orientada a objetos.
          </p>
        </section>
      </section>

      <div class="skills__wrapper">
        <section class="skills container">
          <section class="skills__list">
            <ul>
              <li>Javascript</li>
              <li>HTML</li>
              <li>CSS</li>
            </ul>
          </section>
          <aside class="skills__title">
            <h2>skills</h2>
          </aside>
        </section>
      </div>

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
/* eslint-disable */

export default {
  name: "HomeView",
  data() {
    return {
      helloText: "olá, meu nome é ismael",
    };
  },
  mounted() {
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "l");
    }, 400);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "á");
    }, 600);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", ",");
    }, 800);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", " ");
    }, 1000);

    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "m");
    }, 1200);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "e");
    }, 1400);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "u");
    }, 1600);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", " ");
    }, 1800);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "n");
    }, 2000);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "o");
    }, 2200);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "m");
    }, 2400);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "e");
    }, 2600);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", " ");
    }, 2800);

    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "é");
    }, 3000);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", " ");
    }, 3200);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "i");
    }, 3400);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "s");
    }, 3600);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "m");
    }, 3800);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "a");
    }, 4000);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "e");
    }, 4200);
    setTimeout(() => {
      this.$refs.hello.insertAdjacentHTML("beforeEnd", "l");
    }, 4400);
  },
};
</script>
<style lang="scss">
.container {
  width: 1140px;
  margin: 0 auto;
}

.sections {
  display: flex;
  flex-direction: column;
  gap: 60px;
  padding: 60px 0;
}

.img__wrapper {
  width: 400px;

  img {
    width: 100%;
    border: 10px solid #000;
    border-style: double;
  }
}

nav {
  padding: 20px 0;
  display: flex;
  justify-content: space-between;
  font-family: "Roboto", sans-serif;
  font-weight: 700;
  align-items: center;

  ul {
    display: flex;

    li {
      padding: 15px;
      &:last-child {
        border-radius: 50px;
        background-color: #185b63;
        color: #fff;
      }
    }
  }
}

.whoIAm {
  display: flex;

  section {
    width: 100%;
    display: flex;
    flex-direction: column;
    padding: 60px;
    gap: 30px;
    justify-content: center;

    h2 {
      font-size: 55px;
      font-family: "Ubuntu Mono", monospace;
      display: inline;
    }

    .specialization {
      color: #185b63;
      font-size: 20px;
      margin-bottom: 15px;
      font-family: "Open Sans Condensed", sans-serif;
    }

    .description {
      font-family: "Roboto", sans-serif;
      font-size: 25px;
      font-weight: 300;
      line-height: 40px;
    }
  }
}

.skills__wrapper {
  background-color: #185b63;

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
      font-size: 55px;
      font-family: "Ubuntu Mono", monospace;
    }
  }
}
</style>
