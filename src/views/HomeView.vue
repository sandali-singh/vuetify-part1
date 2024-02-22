<template>
  <div class="home">
    <h1>home page</h1>
    <p class="red white--text">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Beatae sit at,
      officiis aliquam dolore labore quidem optio rerum incidunt quaerat
      voluptatum temporibus nihil eveniet commodi, nisi ratione voluptatem odit
      debitis.
    </p>
    <p class="pink lighten-4 red--text text--darken-4">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae eum soluta
      totam, quasi delectus perferendis perspiciatis, dolorem nostrum doloribus
      quod et odit magni! Dolore error omnis neque ex, temporibus voluptatem?
    </p>
    <h1 class="display-4">Massive Display</h1>
    <h1 class="display-1">smaller Display</h1>
    <p class="headline">This is a heading</p>
    <p class="subheading font-weight-bold">This is a subheading</p>
    <p class="caption">This is a caption</p>
    <v-btn>click me</v-btn>
    <v-btn color="pink">click me</v-btn>
    <v-btn depressed color="pink">click me</v-btn>
    <v-btn depressed class="pink">click me</v-btn>
    <v-btn dark color="pink">click me</v-btn>

    <v-btn class="pink">
      <v-icon>email</v-icon>
      <!--not working -->
    </v-btn>
    <v-btn icon color="pink">
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn depressed dark fab color="purple">
      <v-icon>mdi-heart</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {};
</script>
