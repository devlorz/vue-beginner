<template>
  <div class="hello">
    <h1>Hello again, {{ title }}</h1>
    <img :src="img.src" :alt="img.alt" />
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: "Example",
  data() {
    return {
      title: "Thor",
      message: "This is my first Vue template",
      name: "Chewwy",
      img: {
        src: "https://placeimg.com/200/200/animals",
        alt: "A placeholder image of animals"
      }
    };
  }
};
</script>
