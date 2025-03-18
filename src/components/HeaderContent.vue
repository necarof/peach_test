<script setup>
import IconLogo from './icons/IconLogo.vue'
</script>

<template>
  <div class="container">
    <header class="header">
      <div class="header__logo">
        <a href="/"><IconLogo /></a>
      </div>
      <nav>
        <ul class="header__nav">
          <li class="header__nav-item">
            <a class="header__nav-link" href="#">Облачные решения</a>
          </li>
          <li class="header__nav-item">
            <a class="header__nav-link" href="#">Кибербезопасность</a>
          </li>
          <li class="header__nav-item">
            <a class="header__nav-link" href="#">Импортозамещение</a>
          </li>
          <li class="header__nav-item">
            <a class="header__nav-link" href="#">Цифровая трансформация</a>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>
