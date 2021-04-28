<template>
  <div>
    <v-card class="mt-5 pl-5" elevation="2">
      <div class="row">
        <div class="col col-12 py-0">
          <h1>
            <v-icon class="pb-1" color="black" left> mdi-information-variant </v-icon
            >เกี่ยวกับเรา
          </h1>
          <v-divider> </v-divider>
        </div>
      </div>
      <div class="row">
        <div class="col col-12">
          <h2>
            <v-icon class="pb-1" color="black" left> mdi-store-outline </v-icon>
            ร้านสมบูรณ์การเกษตร
          </h2>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            จำหน่าย อาหารสัตว์ทุกชนิด
          </h3>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            จำหน่าย พันธุ์สัตว์
          </h3>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            จำหน่าย น้ำเชื้อสุกร
          </h3>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            จำหน่าย เเม่พันธุ์สุกร
          </h3>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            บริการ ส่งฟรี (โซนหนองคาย)
          </h3>

          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            มีหมอให้คำปรึกษาฟรี
          </h3>
          <h3 class="ml-10">
            <v-icon class="pb-1" color="black" left> mdi-arrow-right </v-icon>
            รับซื้อคืน หมู วัว ไก่บ้าน ราคาสูง
          </h3>
        </div>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  head() {
    return {
      title: "เกี่ยวกับเรา",
      meta: [
        {
          name: "description",
          content: ""
        },
        {
          name: "keywords",
          content: ""
        }
      ],
      link: []
    };
  }
};
</script>

<style lang="scss" scoped>
h3 {
  margin-top: 30px;
  margin-bottom: 30px;
}
</style>
