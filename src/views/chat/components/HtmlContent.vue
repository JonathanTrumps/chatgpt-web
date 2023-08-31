<template>
    <div v-html="htmlContent"></div>
  </template>
  
  <script lang="ts">
  import { PropType } from 'vue';
  
  export default {
    props: {
      htmlContent: {
        type: String as PropType<string>,
        required: true,
      },
    },
  };
  </script>
  