<template>
  <button>
    <slot></slot>
  </button>
</template>

<style scoped>
button {
  font: inherit;
  border: 1px solid #141E61;
  background-color: #B2F9FC;;
  color: white;
  padding: 0.5rem 2rem;
  cursor: pointer;
  border-radius: 5px;
  border-color: white;
}

button:hover,
button:active {
  background-color: #141E61;
  border-color: #141E61
}
</style>