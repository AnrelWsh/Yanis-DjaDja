<template>
  <BigTitle title="ME CONTACTER" />
  <ContactContent />
</template>

<script>
import BigTitle from '../components/BigTitle.vue'
import ContactContent from '../components/ContactContent.vue'

export default {
  name: 'ProjetsView',
  components: {
    BigTitle,
    ContactContent
  }
}
</script>