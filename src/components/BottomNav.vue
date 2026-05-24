<script setup lang="ts">

</script>

<template>
<v-bottom-navigation>
    <v-btn to="/feed" value="feed">
     <v-icon icon="mdi-newspaper-variant-outline" size="x-large"></v-icon>
     <span>Feed</span>
   </v-btn>
 
  <v-btn to="/post" value="post">
    <v-icon icon="mdi-note-edit-outline" size="x-large"></v-icon>
    <span>Be Grateful</span>
  </v-btn>

  <v-btn to="/friends" value="friends">
    <v-icon icon="mdi-account-group-outline" size="x-large"></v-icon>
    <span>Friends</span>
  </v-btn>

  <v-btn to="/profile" value="profile">
    <v-icon icon="mdi-account-circle-outline" size="x-large"></v-icon>
    <span>Profile</span>
  </v-btn>

</v-bottom-navigation>

</template>


<style scoped>

</style>
