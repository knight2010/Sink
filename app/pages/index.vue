<script setup lang="ts">
definePageMeta({
  layout: false,
})

useSeoMeta({
  title: 'Laya 分类历史',
})
</script>

<template>
  <a
    href="/dashboard"
    style="position: fixed; top: 12px; right: 12px; z-index: 50; padding: 6px 12px; border-radius: 999px; background: rgba(0, 0, 0, 0.6); color: #fff; font-size: 13px; text-decoration: none;"
  >
    后台管理
  </a>
  <iframe
    src="https://laya.1919919.xyz/"
    title="Laya 分类历史"
    style="width: 100%; height: 100vh; height: 100dvh; border: 0; display: block;"
  />
</template>
