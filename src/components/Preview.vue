<script setup lang="ts">

</script>

<template>
  <div class="preview" />
</template>

<style lang="scss">
.preview {
  --iu: inline-block
    w-360px h-360px;

  background-image: linear-gradient(45deg,rgba(0,0,0,.2) 25%, transparent 0, transparent 75%, rgba(0,0,0,.2) 0),
    linear-gradient(45deg,rgba(0,0,0,.2) 25%, transparent 0, transparent 75%, rgba(0,0,0,.2) 0);
  background-size: 30px 30px;
  background-position: 0 0,15px 15px;

  .dark & {
    background-image: linear-gradient(45deg,rgba(255,255,255,.2) 25%, transparent 0, transparent 75%, rgba(255,255,255,.2) 0),
      linear-gradient(45deg,rgba(255,255,255,.2) 25%, transparent 0, transparent 75%, rgba(255,255,255,.2) 0);
  }
}
</style>

<preview>
<CodeBox />
</preview>
