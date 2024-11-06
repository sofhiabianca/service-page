<script setup>
import { ref, computed } from 'vue'

const props = defineProps(['value'])
const isVisible = computed({
  get: () => props.value,
  set: (value) => emit('update:value', value)
})

const closeModal = () => {
  isVisible.value = false
}

defineEmits(['update:value'])
</script>

<template>
    <div class="modal-overlay" v-if="isVisible" @click.self="closeModal">
      <div class="modal-content">
        <slot></slot>
        <button @click="closeModal">Close</button>
      </div>
    </div>
  </template>
  
  <style scoped>
  .modal-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 9999;
  }
  
  .modal-content {
    background-color: white;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.33);
  }
  </style>
  