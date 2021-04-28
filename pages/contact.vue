<template>
  <div>
    <v-card class="mt-5 pl-5" elevation="2">
      <div class="row">
        <div class="col col-12 py-0">
          <h1>
            <v-icon class="pb-1" color="black" left> mdi-card-account-phone-outline </v-icon>
          ติดต่อเรา
          </h1>
          <v-divider> </v-divider>
        </div>
      </div>
      <div class="row">
        <div class="col col-12">
          <h3>
            <v-icon class="pb-1" left> mdi-map-marker </v-icon>ที่อยู่ :
            ร้านสมบูรณ์การเกษตร บ้านเลขที่ 335 หมู่ 6 ต.ท่าบ่อ อ.ท่าบ่อ
            จ.หนองคาย
          </h3>
          <h3>
            <v-icon class="pb-1" left> mdi-cellphone-sound </v-icon>โทร :
            0614651759 (เจ้ป๋อย)
          </h3>
          <h3>
            <v-icon class="pb-1" left> mdi-alpha-l-box </v-icon>Line :
            0614651759 (เพิ่มเพื่อนด้วยเบอร์โทรศัพท์)
          </h3>
          <h3>
            <v-icon class="pb-1" left> mdi-facebook </v-icon>Facebook :
            <a
              href="https://www.facebook.com/%E0%B8%AA%E0%B8%A1%E0%B8%9A%E0%B8%B9%E0%B8%A3%E0%B8%93%E0%B9%8C%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%81%E0%B8%A9%E0%B8%95%E0%B8%A3-1438873416177713"
              target="_bank"
            >
              สมบูรณ์การเกษตร
            </a>
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
      title: "ติดต่อเรา",
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
