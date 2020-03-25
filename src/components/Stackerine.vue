<template>
  <div>
    <h1>Stackerine component</h1>
    <ul>
      <li v-for="(teamate,i) in team" :key="i" v-show="teamate.isMaster">{{teamate.name}}</li>
    </ul>
    <input type="text" v-model="name" />
    <span>{{name}}</span>
  </div>
</template>

<script>
export default {
  name: "Stackerine",
  data: () => ({
    name: "Stackerine",
    counter: 0,
    isVisible: false,
    team: [
      { name: "Adeline", isMaster: true },
      { name: "Pauline", isMaster: true },
      { name: "Axelle", isMaster: true },
      { name: "Joe", isMaster: false }
    ]
  })
};
</script>

<style>
</style>