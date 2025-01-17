<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Markdown from './sections/Markdown.vue'
import BibTeX from './sections/BibTeX.vue'
import Markdown1 from './sections/Markdown-1.vue'
import Markdowndataset from './sections/Markdown-dataset.vue'
import Markdownqualitative from './sections/Markdown-qualitative.vue'

export default {
  components: {
    Title,
    Abstract,
    Markdown,
    Markdown1,
    Markdowndataset,
    Markdownqualitative,
    BibTeX
  }
}
</script>

<template>
  <Title/>

  <Markdown/>
  <Abstract/>
  <Markdown-1/>
  <Markdownqualitative/>
  <Markdowndataset/>

  <BibTeX/>

</template>