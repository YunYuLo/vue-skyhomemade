<template>
  <div>
    <v-parallax height="300" src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"></v-parallax>
    <v-row align="center" justify="center" style="transform: translate(0, -130%)">
      <v-col cols="12">
        <v-hover v-slot:default="{ hover }">
          <v-card :elevation="hover ? 12 : 2" class="mx-auto" height="300" max-width="500">
            <v-card-text class="my-4 text-center title">Welcome to Sky 天手感烘焙</v-card-text>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
  </div>
</template>