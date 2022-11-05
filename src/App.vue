<template>
  <div id="app">
    <transition name="fade" mode="out-in">
    <router-view></router-view>
    </transition>
    
  </div>
</template>

<style>

* {
  margin: 0; 
  padding: 0;
  box-sizing: border-box;
  font-family: 'Open Sans', sans-serif;
}
.fade-enter, .fade-leave-to {
  opacity: 0;
  transform: translateX(2em);
}
.fade-enter-active, .fade-leave-active {
  transition: all .3s ease;
}
</style>
