<template>
  <Badge vertical="middle" :text="version" />
</template>

<script>
import pkg from '@/package.json'
export default {
  name: 'Version',
  data() {
    return {
      version: pkg.version
    }
  }
}
</script>
