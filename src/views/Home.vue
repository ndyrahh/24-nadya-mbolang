<template>
  <div class="home">
    <v-row>
      <v-col cols="12">
        <v-img src="@/assets/1.jpg" class="hero-img" height="574px">
          <div class="hero-text">
            <h1>
              Explore and <br />
              Travel
            </h1>
            <p>Travel is only glamorous in retrospect</p>
            <v-btn
              rounded
              style="
                background: #94b49f;
                color: white;
                border: none;
                width: 151px;
                height: 44px;
                font-size: 18px;
              "
              >SUBSCRIBE</v-btn
            >
          </div>
        </v-img>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="6">
        <v-card class="mx-auto">
          <v-img src="@/assets/2.jpg" height="300px"></v-img>

          <v-card-title>Nusa Penida</v-card-title>

          <v-card-subtitle>Beautiful beach</v-card-subtitle>

          <v-card-actions>
            <v-btn text block>
              Explore
              <v-spacer></v-spacer>
              <v-icon>mdi-chevron-right</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="6">
        <v-card class="mx-auto">
          <v-img src="@/assets/3.jpg" height="300px"></v-img>

          <v-card-title>Bromo</v-card-title>

          <v-card-subtitle>Beautiful place</v-card-subtitle>

          <v-card-actions>
            <v-btn text block>
              Explore
              <v-spacer></v-spacer>
              <v-icon>mdi-chevron-right</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
    <v-row class="mt-5">
      <v-col cols="12">
        <h2 class="mb-3">About Us</h2>
        <p>
          Creative.ly is the flagship digital consumer brand within the Columbus
          Travel Media portfolio. A comprehensive guide to the world’s best
          travel destinations.Available in English, German, French and Spanish
          versions, the WTG provides detailed and accurate travel content
          designed to inspire global travellers. It covers all aspects, from
          cities to airports, cruise ports to ski and beach resorts, attractions
          to events, and it also includes weekly travel news, features and
          quizzes. Updated every day by a dedicated global editorial team, the
          portal logs 1 million+ unique users monthly.
        </p>
      </v-col>
    </v-row>
    <Contact />
  </div>
</template>

<script>
import Contact from "@/components/ContactComponent.vue";

export default {
  name: "HomeView",
  components: {
    Contact,
  },
};
</script>

<style scoped>
.hero-img {
  padding-top: 75px;
  padding-left: 80px;
}

.hero-text {
  color: white;
}

.hero-text h1 {
  font-weight: 700;
  font-size: 48px;
  line-height: 57.6px;
}

.hero-text p {
  font-weight: 600;
  font-size: 24px;
  line-height: 28px;
}

.hero-text > * {
  margin: 10px 0;
}
</style>
