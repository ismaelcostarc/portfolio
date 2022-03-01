<template>
  <div class="navbar__wrapper">
    <nav class="row">
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
  </div>
</template>
<script>
export default {
  name: 'NavBar',
};
</script>
<style lang="scss" scoped>
@import '@/assets/scss/index.scss';

.navbar__wrapper {
  width: 100%;
  background-color: #fff;
  position: fixed;
}

nav {
  padding: 20px 0;
  display: flex;
  justify-content: space-between;
  font-weight: 700;
  align-items: center;
  position: sticky;

  ul {
    display: flex;

    li {
      padding: 15px;
      &:last-child {
        border-radius: 50px;
        background-color: $primary;
        color: #fff;
      }
    }
  }
}
</style>
