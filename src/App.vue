<template>
  <ul></ul>
</template>

<script>
export default {
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
