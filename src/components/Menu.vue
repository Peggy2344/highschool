<template lang="pug">
    #menu
        p#club 社團介紹
        div.item(v-for="(club,index) of clubs" :key="club")
            | {{ club }}
</template>

<script>
export default {
  name: 'Menu',
  data () {
    return {
      clubs: ['吉他社', '熱舞社', '棒球社', '羽球社', '足球社', '童軍社']
    }
  }
}
</script>
