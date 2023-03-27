<template>
  <button @click="fetchData()">Say Hello</button>
</template>

<script>
export default {
  name: 'ViButtonName',
  props: {
    judul: String,
  },
  methods: {
    fetchData() {
      console.log('masuk fungsi');
      fetch('https://jsonplaceholder.typicode.com/posts/1')
        .then(function (response) {
          return response.json();
        })
        .then(function (data) {
          // Example:
          // where 'title' is a key
          console.log(data.title);
        });
    },
  },
};
</script>
