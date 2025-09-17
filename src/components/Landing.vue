<template>
  <v-container class="fill-height" max-width="800">
    <div class="w-100">
      <div class="text-center mb-12">
        <h1 class="text-h2 font-weight-bold mb-2">Beccah Dunklin</h1>
      </div>

      <v-row align="stretch" justify="center">
        <v-col cols="12" md="5" sm="6">
          <v-card
            class="h-100 d-flex flex-column"
            elevation="2"
            hover
            :href="resumeLink"
            rel="noopener noreferrer"
            rounded="lg"
            target="_blank"
          >
            <v-img
              cover
              height="200"
              src="https://via.placeholder.com/300x200/E3F2FD/1976D2?text=Resume"
            />
            <v-card-title class="text-h5 text-center">Resume</v-card-title>
            <v-card-text class="text-center flex-grow-1 d-flex align-center justify-center">
              <div>View my professional resume and experience</div>
            </v-card-text>
            <v-card-actions class="justify-center pb-4">
              <v-icon>mdi-file-document-outline</v-icon>
            </v-card-actions>
          </v-card>
        </v-col>

        <v-col cols="12" md="5" sm="6">
          <v-card
            class="h-100 d-flex flex-column"
            elevation="2"
            hover
            :href="portfolioLink"
            rel="noopener noreferrer"
            rounded="lg"
            target="_blank"
          >
            <v-img
              cover
              height="200"
              src="https://via.placeholder.com/300x200/F3E5F5/7B1FA2?text=Portfolio"
            />
            <v-card-title class="text-h5 text-center">Portfolio</v-card-title>
            <v-card-text class="text-center flex-grow-1 d-flex align-center justify-center">
              <div>Explore my work and project portfolio</div>
            </v-card-text>
            <v-card-actions class="justify-center pb-4">
              <v-icon>mdi-briefcase-outline</v-icon>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </v-container>
</template>

<script setup>
  const resumeLink = 'https://docs.google.com/document/d/1SieuUrI-yPR78w_I5VbJtiLXvUHdFiPb-ZwmC2j2YwE/'
  const portfolioLink = 'https://docs.google.com/presentation/d/1F7k1dO6krLYVKx1hizboKNYVgD1byXvTdJGLsOTVx7Q/edit'
</script>
