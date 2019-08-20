<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title>
          <img src="../assets/logo-full.svg" height="60px" style="padding: 0.7rem;">
        </q-toolbar-title>
        <q-btn flat stretch label="Demo" />
        <q-btn flat stretch label="Galeria" />
        <q-btn flat stretch label="Imprezy"> </q-btn>
        <q-btn flat stretch label="Instrumentarium i zaplecze" />
        <q-btn flat stretch label="Terminarz" />
        <q-btn flat stretch label="Kontakt" />
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
    <q-page-scroller
      expand
      position="top"
      :scroll-offset="800"
      :offset="[0, 0]"
    >
    </q-page-scroller>
  </q-layout>
</template>

<script>
export default {
  name: "MainLayout",
  data() {
    return {
      leftDrawerOpen: this.$q.platform.is.desktop
    };
  },
  methods: {
    onItemClick() {
      console.log("Clicked on an Item");
    }
  }
};
</script>

<style></style>
