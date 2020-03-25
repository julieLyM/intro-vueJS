<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <img
      src="https://cdn.shopify.com/s/files/1/0255/3184/2642/products/sticker-licorne-dab-sticker-une-licorne-332375_2000x.jpg?v=1574259825"
    />
    <p>
      <a :href="href">Fais ta licorne du genre</a>
    </p>
    <a :href="licorneUrl">licorne site</a>

    <p>{{text}}</p>
    <p>{{question}}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: () => ({
    isVisible: true,
    name: "Stackerine"
  }),
  props: {
    msg: String,
    text: String,
    href: String,
    licorneUrl: String,
    question: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
