<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Button from './components/Button.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld 
        :msg="'Hello Header!'"
      />
    </div>
  </header>

  <main>
  <Button :text="'submit'" />
  
  <Button :text="'dfgdf'" />
  <Button :text="'item'" />
  <Button :text="'456'" />
  <Button :text="'2345cvb'" />
  </main>
</template>