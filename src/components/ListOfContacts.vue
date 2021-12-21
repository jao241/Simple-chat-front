<template>
  <section id="asideListContactField">
    <h2>Contatos</h2>
    <ul>
      <li>João</li>
      <li>Mateus</li>
      <li>Carol</li>
      <li>Ana</li>
    </ul>
  </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>

#asideListContactField{
  width: 20%;
  background-color: lightblue;
}

section h2{
  font-size: 32px;
  padding: 10px;
  border-bottom: 2px solid black;
}

section ul{
  list-style: none;
  padding: 0;
}

section li{
  padding: 20px;
  border-bottom: 1px solid grey;
}

section li:hover{
  background-color: lightgreen;
}


</style>