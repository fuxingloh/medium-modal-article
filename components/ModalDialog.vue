<template>
  <div class="absolute position-0 index-1">
    <div class="bg-overlay p-24 flex-center wh-100">
      <div class="bg-white p-24 border-3">
        <h3>Dialog Title</h3>
        <p class="mt-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

        <div class="mt-16 flex-end">
          <button class="border" @click="$emit('close')">Close</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'ModalDialog'
  }
</script>
