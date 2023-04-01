<template>
  <div class="app">
    <section class="slidebar__left">
      <div class="slidebar__list">
        <div class="slidebar__container">
          <MenuComponent/>
        </div>
        <div class="chats__container">  
          <ChatsComponent/>
        </div>
      </div>
    </section>
    <section class="content">
      <div class="container">
        <!-- <ContentComponent/> -->
        <!-- <ProfileComponent/> -->
        <!-- <SellComponent/> -->
      </div>
    </section>
  </div>
</template>

<script>
import MenuComponent from './components/MenuComponent.vue';
// import ContentComponent from './components/ContentComponent.vue';
// import SellComponent from './components/SellComponent.vue';
// import ProfileComponent from './components/ProfileComponent.vue'
import ChatsComponent from './components/ChatsComponent.vue'

export default {
  name: 'App',
  components: {
    MenuComponent,
    // ContentComponent,
    // SellComponent,
    // ProfileComponent,
    ChatsComponent,
}

}
</script>

<style lang="scss">
.app{
  display: flex;
}
.slidebar{
  &__left{
    min-height: 100vh;
  }
  &__container{
    min-width: 220px;
    height: 100%;
  }
  &__list{
    display: flex;
  }
}
.chats__container{
  width: 100%;
  height: 100vh;
}
.content{
  width: 100%;
  height: 100%;
}
.container{
  margin: 20px auto;
  max-width: 1700px;
  display: flex;


}
/* Указываем box sizing */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* Убираем внутренние отступы */
ul[class],
ol[class] {
  padding: 0;
}

/* Убираем внешние отступы */
body,
h1,
h2,
h3,
h4,
p,
ul[class],
ol[class],
li,
figure,
figcaption,
blockquote,
dl,
dd {
  margin: 0;
}

/* Выставляем основные настройки по-умолчанию для body */
body {
  font-family: 'Inter';
  min-height: 100vh;
  scroll-behavior: smooth;
  text-rendering: optimizeSpeed;
  line-height: 1.5;

}

/* Удаляем стандартную стилизацию для всех ul и il, у которых есть атрибут class*/
ul[class],
ol[class] {
  list-style: none;
}

/* Элементы a, у которых нет класса, сбрасываем до дефолтных стилей */
a:not([class]) {
  text-decoration-skip-ink: auto;
}

/* Упрощаем работу с изображениями */
img {
  max-width: 100%;
  display: block;
}

/* Указываем понятную периодичность в потоке данных у article*/
article > * + * {
  margin-top: 1em;
}

/* Наследуем шрифты для инпутов и кнопок */
input,
button,
textarea,
select {
  font: inherit;
}

/* Удаляем все анимации и переходы для людей, которые предпочитай их не использовать */
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}
</style>
