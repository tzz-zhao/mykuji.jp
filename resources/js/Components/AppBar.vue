<template>
    <v-app-bar color="red-darken-1" density="compact">
        <template v-slot:prepend>
          <v-app-bar-nav-icon icon="mdi-bullseye-arrow" size="x-large"></v-app-bar-nav-icon>
        </template>

        <v-app-bar-title>MyKuji.JP</v-app-bar-title>

        <template v-slot:append>
          <v-btn icon="mdi-dots-vertical"></v-btn>
        </template>
    </v-app-bar>
</template>