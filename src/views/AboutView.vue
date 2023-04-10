<template>
  <div class="about">
    <h1>This is a vue.js todo web-application</h1>
     <p>
      The goal is to practice skills in vue.js basics by creating a vue.js todo web-application from scratch
     </p>
     <p>List of techs, libs, skills(basic fundamentals) used in vue.js todo web-app:</p>

     <ul>
        <li>html,css,js</li>
        <li>vite.js</li>
        <li>Composition API</li>
        <li>ref(), reactive(), computed(), watch() methods from Reactivity API</li>
        <li>slots</li>
        <li>component events (Emitting and Listening to Events, declaring events)</li>
        <li>props</li>
        <li>directives (v-model, v-if, v-else, v-bind, v-show, v-on)</li>
        <li>vue-router</li>
      </ul>

     <p>List of TO-DO to improve functionality of todo web-app:</p>

      <ul>
        <li><s>create todos on input enter keyup</s></li>
        <li>drag and reorder todo items</li>
        <li>animate the creation & deletion of todos</li>
        <li>add multi-language (internationalization - maybe vue-I18n)</li>
        <li>maybe fullstack web-app (track days)</li>
      </ul>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    display: grid;
    gap: 1rem;
    align-items: center;
    justify-content: center;
    text-align: center;
    margin: 10px auto;
  }
}
</style>
