<template>
  <v-app>
    <v-content>
      <!-- fill-height는 브라우저 높이를 100%, 수직으로 가운데 정렬시킴 -->
      <v-container fluid fill-height >
        <v-row>
          <!-- text-center는 수평 가운데 정렬 -->
          <v-col cols="12" class="text-center">
            <!-- 타이포 스타일은 title, 글자색은 흰색으로 설정  -->
            <h1 class="title white--text">안녕하세요!! 한건희 입니다. </h1>
            <p class="caption">파이어베이스로 hosting 해봅니다.</p>
            <img src="./assets/hello-pwa.png" alt="" />
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>
<script>
  export default {
    name: 'App',
    created () {
      // 배경색을 다크모드로 함
      this.$vuetify.theme.dark = true;
    }
  }
</script>