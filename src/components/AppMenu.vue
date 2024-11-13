<template>
  <v-toolbar color="primary">
    <v-spacer />
    <v-btn
      @click="$emit('show-qr-scanner')"
    >
      <v-icon>
        mdi-qrcode-scan
      </v-icon>
      Scan
    </v-btn>
    <v-spacer />
  </v-toolbar>
</template>

<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: "AppMenu",
  emits: [
    'show-qr-scanner'
  ],
});
</script>