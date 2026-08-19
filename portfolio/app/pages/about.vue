<template>
    <div>
        This page is about me.
    </div>

    <div>
        <button @click="enableCustomLayout">
        Update layout
        </button>
    </div>
</template>

<script setup>
// definePageMeta({
//   layout: 'custom',
// })
function enableCustomLayout () {
  setPageLayout('custom')
}
</script>