<template>
  <div>
    <schoolinContain :detail="detail" />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: '輔大聖心高中',
      meta: [
        { charset: 'utf-8' },
        { hid: 'og:title'  , property: 'og:title'  , content: '青春博客來閱讀私角落' },
        { hid: 'og:image' , property: 'og:image' , content: require('@/assets/img/article/n01/2.jpg') },
        { hid: 'description', name: 'description', content: '輔大聖心高中「閱在花中！」' },
        { hid: 'og:description' , property: 'og:description' , content: '輔大聖心高中「閱在花中」' },
      ],
    }
  },
  layout: 'default',
  components: {
    schoolinContain: require('~/components/schoolin-contain.vue').default,
  },
  props: {
    
  },
  data () {
    return {
      detail: { img: require('@/assets/img/article/n01/2.jpg'), position: 'v', name: '輔大聖心高中', place: 'n', title: '閱在花中', desc: '三口', content: '校園一角花圃之中，藏匿的不只是五彩斑斕的花朵，也淺藏著知識的線索，走進這色彩中，悠悠地找尋自己所嚮往的那片理想。', link: '10102' },
    }
  },
  computed: {

  },
  methods: {
    
  },
  watch: {
    
  }
}
</script>

<style lang="scss" scoped>

</style>