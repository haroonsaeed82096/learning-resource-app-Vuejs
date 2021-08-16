<template>
  <ul>
    <learning-resource
      v-for="res in storedResources"
      :key="res.id"
      :title="res.title"
      :description="res.description"
      :link="res.link"
    ></learning-resource>
  </ul>
</template>

<script>
import LearningResource from './components/learning-resources/LearningResource.vue';

export default {
  components: {
    LearningResource: LearningResource
  },
  data() {
    return {
      storedResources: [
        {
          id: 'offcial-guide',
          title: 'official guide',
          description: 'The official Vue.js documentation',
          link: 'https://vuejs.org'
        },
        {
          id: 'Google',
          title: 'Google',
          description: 'Learn to google.....',
          link: 'https://google.org'
        }
      ]
    };
  }
};
</script>
