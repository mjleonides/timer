<template>
  <h1>My Timer</h1>
  <div><input id="seconds" type="number" v-model="seconds" />seconds</div>
  <button @click="startTimer">Start</button>
  <p>Time is currently {{ seconds }}</p>
</template>

<script></script>

<style scoped>
header {
  line-height: 1.5;
  display: flex;
  place-items: center;
  flex-direction: column;
}

@media (min-width: 1024px) {
  header {
    padding-right: calc(var(--section-gap) / 2);
  }
}
</style>
