<template>
  <v-container>
    <v-row>
      <v-col cols="12" lg="12" md="12" xs="12" align="center">
        <v-img src="vue-file-uploader.png" width="200" height="200" class="text-center"></v-img>
        <div class="text-center">
          <p style="color: #424242; font-size: 3rem">Handy Uploader</p>
          <p style="color: #757575; font-size: 1.5rem">Complete and simple file uploader with image compressor in Vue.js</p>
        </div>
        <v-col cols="12" lg="12" md="12" xs="12">
          <div class="text-center ma-2">
            <v-chip
              large
              class="ma-2"
              color="green darken-1"
              label
              text-color="white"
              to="/thumbnail"
            >
              <v-icon left>mdi-image-plus</v-icon>
              Thumbnail File Uploader
            </v-chip>

            <v-chip
              large
              class="ma-2"
              color="green darken-1"
              label
              text-color="white"
              to="/simple"
            >
              <v-icon left>mdi-file-upload</v-icon>
              Simple File Uploader
            </v-chip>

            <v-chip
              large
              class="ma-2 text-center"
              color="green darken-1"
              label
              text-color="white"
              to="/table"
            >
              <v-icon left>mdi-table</v-icon>
              Table File Uploader
            </v-chip>
          </div>
        </v-col>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  components: {
  },
  data: () => ({

  }),
  methods:{

  },
}
</script>
