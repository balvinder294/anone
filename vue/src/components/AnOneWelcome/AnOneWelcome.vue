<template>
  <div class="sp-component sp-welcome">
    <div class="sp-box sp-shadow">
      <div class="sp-welcome__header">
        <h2>Welcome to Another-1</h2>
      </div>
      <p>
        Text
      </p>
      <div class="sp-welcome__btns">
        <AnButton href="https://another-1.io/" target="_blank" type="primary">About</AnButton>
        <AnButton
            href="https://github.com/notional-labs/anone"
            target="_blank"
            type="secondary"
            class="sp-welcome__btns__github"
        >Github</AnButton
        >
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from 'vue'
import AnButton from '../AnButton/AnButton'

export default defineComponent({
  name: 'AnOneWelcome',
  components: {
    AnButton,
  },
})
</script>
