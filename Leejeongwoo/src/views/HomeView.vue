<template>
  <v-container>
    <div id="home">
      <nav>
        <router-link to="/practive">정우 연습 공간</router-link>|
        
        <router-link to="/">Home!</router-link> |
        <router-link to="/bind-test">BindTest</router-link> |
        <router-link to="/click-test">클릭 테스트</router-link> |
        <router-link to="/component-test">컴포넌트 테스트</router-link> |
        <router-link to="/emit-test-board-game">emit 테스트(보드 게임)</router-link> |
        <router-link to="/component-test">컴포넌트 테스트</router-link> |
        <router-link to="/axios-test-page">Vue에서 Spring으로 데이터 전송하기</router-link> |
        <router-link to="/board-list-page">게시판</router-link> |
        <router-link to="/product-list-page">상품</router-link> |
      </nav>
      <router-view/>
    </div>
  </v-container>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  },
}
</script>