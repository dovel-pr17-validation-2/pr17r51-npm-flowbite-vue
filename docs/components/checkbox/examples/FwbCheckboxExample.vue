<template>
  <div class="flex flex-col gap-2 vp-raw">
    <fwb-checkbox
      v-model="check"
      label="Default checkbox"
    />
    <fwb-checkbox
      v-model="checked"
      label="Checked state"
    />
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

import { FwbCheckbox } from '../../../../src/index'

const check = ref(false)
const checked = ref(true)
</script>
