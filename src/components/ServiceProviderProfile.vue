<template>
  <v-container >
  <v-container class="gig-overview">
    <h1> I will design responsive website for your business</h1>
  
    <v-container>
    <v-row >
      <!-- Left Column: Image Avatar -->
      <v-col cols="2">
        <v-avatar size="60">
          <v-img src="https://cdn.vuetifyjs.com/images/john.jpg"></v-img>
        </v-avatar>
      </v-col>
      
      <!-- Right Column: Name and Username -->
      <v-col cols="10">
        <div class="name">Dominic Jovin</div>
        <div class="username">@Dom1003</div>
      </v-col>
    </v-row>
  </v-container>
</v-container>
</v-container>

 

</template>

<script>
export default {
  name: 'ServiceProviderProfile',
};
</script>




<!-- <style scoped>
.service-provider-profile {
  text-align: center;
  padding: 20px;
}

.service-provider-profile img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
}

.service-provider-profile h1 {
  font-size: 24px;
  margin: 10px 0;
}

.service-provider-profile p {
  font-size: 16px;
}
</style> -->
<style scoped>
.avatar{
  float: left;
}
</style>