<template>
  <div class="vp-raw">
    <fwb-file-input
      v-model="file"
      label="Upload file"
    >
      <template #helper>
        SVG, PNG, JPG or GIF (MAX. 800x400px).
      </template>
    </fwb-file-input>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

import { FwbFileInput } from '../../../../src/index'

const file = ref(null)
</script>
