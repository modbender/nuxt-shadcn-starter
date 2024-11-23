<template>
  <Card is="header" class="border-t-0 border-x-0 p-3">
    <div class="container flex items-center">
      <SiteLink class="font-bold" to="/">
        {{ siteConfig.name }}
      </SiteLink>
      <div class="flex gap-3 ml-auto">
        <CustomizeSite />
      </div>
    </div>
  </Card>
</template>

<script setup>
const siteConfig = useSiteConfig()
</script>

<style></style>