<template>
  <div class="">
    推荐页面
  </div>
</template>

<script>
import { getRecommend } from '@/service/recommend'

export default {
  name: 'recommend',
  components: {},
  props: {},
  data() {
    return {
    }
  },
  methods: {},
  async created() {
    const result = await getRecommend()
    console.log(result)
  }
}
</script>
<style lang="scss" scoped>
</style>
