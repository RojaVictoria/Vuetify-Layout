<template>
    <div>
        <v-toolbar dense color="blue-grey darken-3" dark>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>

            <v-toolbar-title>Vuetify Layout</v-toolbar-title>
            <v-spacer></v-spacer>

            <v-btn icon>
                <v-icon>mdi-magnify</v-icon>
            </v-btn>

            <v-btn icon>
                <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
                <v-icon>mdi-dots-vertical</v-icon>
            </v-btn>
        </v-toolbar>
    </div>
</template>

<script>

export default {
  name: "Navbar",
  data: () => ({

  }),
}
</script>