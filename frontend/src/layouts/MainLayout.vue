<template>
  <q-layout view="hHh lpR fFf">
    <q-header class="bg-white text-dark q-mt-lg">
      <div class="row justify-center no-wrap q-mb-md">
        <div class="column justify-center items-center">
          <q-avatar size="7rem" class="q-mb-lg">
            <q-img
              src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_jvgHbdQJGnsp-pkTl2TqusMRD4lhW5yPUQ&s'
            />
          </q-avatar>
          <q-toolbar-title class="q-mb-sm">
            Abdullah Kiran
          </q-toolbar-title>
          <q-badge color="purple">
            Software Developer
          </q-badge>
        </div>
      </div>
      <q-separator color="gray" inset></q-separator>
      <router-view></router-view>
    </q-header>
    <q-page-container>
      <router-view/>
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  methods: {}
}
</script>

<style scoped>
.badge-text-color {
  color: #000;
}
</style>
