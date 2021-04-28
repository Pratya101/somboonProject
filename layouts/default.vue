<template>
  <v-app app>
    <v-app-bar fixed color="green" app>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title>
        <v-avatar size="70">
          <img src="/logo/logo.png" class="avatar" alt="" />
        </v-avatar>
      </v-toolbar-title>
      <v-btn x-large text color="dark" to="/">
        <v-icon left> mdi-home </v-icon>หน้าเเรก</v-btn
      >
      <v-btn x-large text color="dark" to="/product">
        <v-icon left> mdi-cube-outline </v-icon>สินค้า</v-btn
      >
      <v-btn x-large text color="dark" to="/about">
        <v-icon left> mdi-information-variant </v-icon>เกี่ยวกับเรา</v-btn
      >
      <v-btn x-large text color="dark" to="/contact">
        <v-icon left> mdi-card-account-phone-outline </v-icon>ติดต่อเรา</v-btn
      >
      <v-spacer></v-spacer>
      <!-- 
      <v-btn x-large text color="dark">
        <v-icon left> mdi-account-plus-outline</v-icon>สมัครสมาชิก</v-btn
      >
      <v-btn x-large text color="dark">
        <v-icon left> mdi-login-variant</v-icon>เข้าสู่ระบบ</v-btn
      > -->
    </v-app-bar>
    <v-main>
      <v-container class="mt-12">
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/"
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500&display=swap");
html {
  font-family: "Sarabun", sans-serif;
}
h1 {
  font-family: "Sarabun", sans-serif;
}
h2 {
  font-family: "Sarabun", sans-serif;
}
h3 {
  font-family: "Sarabun", sans-serif;
}
h4 {
  font-family: "Sarabun", sans-serif;
}
h5 {
  font-family: "Sarabun", sans-serif;
}
h6 {
  font-family: "Sarabun", sans-serif;
}
div {
  font-family: "Sarabun", sans-serif;
}
p {
  font-family: "Sarabun", sans-serif;
}
</style>
