<template>
    <v-main-show>
      <v-card
          class="mx-auto"
          max-width="100%"
      >
        <v-img
            class="white--text align-end"
            height="200px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
        >
          <v-card-title>Top 10 Australian beaches</v-card-title>
        </v-img>

        <v-card-subtitle class="pb-0">
          Number 10
        </v-card-subtitle>

        <v-card-text class="text--primary">
          <div>Whitehaven Beach</div>

          <div>Whitsunday Island, Whitsunday Islands</div>
        </v-card-text>

        <v-card-actions>
          <v-btn
              color="orange"
              text
          >
            Share
          </v-btn>

          <v-btn
              color="orange"
              text
          >
            Explore
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-main-show>

</template>

<script>
import main from "../components/main";

export default {
  components: {
    'v-main-show': main,
  },
  data: () => ({
    links: [
      'Dashboard',
      'Messages',
      'Profile',
      'Updates',
    ],
  }),
}
</script>
