<template>
  <div class="navbar__wrapper container">
    <div class="container">
      <nav class="row navbar">
        <div class="col col-2">
          <!-- <img src="@/assets/img/logo.png" alt="Ismael Costa" /> -->
          <div class="font-mono text-md logo"><span>i</span>smael costa</div>
        </div>
        <div class="col col-10">
          <ul class="text-bold font-sans-serif navbar__menu">
            <li class="menu__item" id="link--quem-sou"><a href="#quem-sou">quem sou</a></li>
            <li class="menu__item" id="link--skills"><a href="#skills">skills</a></li>
            <li class="menu__item" id="link--experiencia">
              <a href="#experiencia">experiência</a>
            </li>
            <li class="menu__item" id="link--formacao-academica">
              <a href="#formacao-academica">formação acadêmica</a>
            </li>
            <li class="menu__item menu__button">download CV <i class="fas fa-download"></i></li>
          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  name: 'NavBar',
};
</script>
<style lang="scss" scoped>
@import '@/assets/scss/index.scss';

.logo {
  letter-spacing: 5px;
  span {
    background-color: $secondary;
    color: #fff;
    border-radius: 100%;
    width: 23px;
    height: 23px;
    display: inline-block;
    text-align: center;
  }
}

.navbar__wrapper {
  width: 100%;
  background-color: #fff;
  position: fixed;
  top: 0;
}

.navbar {
  padding: 20px 0;
  align-items: center;
}

.navbar__menu {
  display: flex;
  justify-content: flex-end;
}

.menu__item {
  padding: 15px;
  cursor: pointer;
}

#quem-sou:target ~ .navbar__wrapper #link--quem-sou a {
  text-decoration: underline $secondary solid 3px;
}

#skills:target ~ .navbar__wrapper #link--skills a {
  text-decoration: underline $secondary solid 3px;
}

#formacao-academica:target ~ .navbar__wrapper #link--formacao-academica a {
  text-decoration: underline $secondary solid 3px;
}

#experiencia:target ~ .navbar__wrapper #link--experiencia a {
  text-decoration: underline $secondary solid 3px;
}

.menu__button {
  border-radius: 50px;
  background-color: $primary;
  color: #fff;
}
</style>
