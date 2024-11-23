<template>
  <Card is="footer" class="border-b-0 border-x-0 p-5 mt-auto">
    <div class="container text-center">
      <div class="font-thin">
        © {{ new Date().getFullYear() }} {{ siteConfig.name }}
      </div>
    </div>
  </Card>
</template>

<script setup>
const siteConfig = useSiteConfig()
</script>

<style></style>