<template>
    <section id="inputMessageField">
      <input type="text" name="input" id="input" placeholder="Digite algo!">
      <p>botao</p>
    </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>

section{
  display: flex;
}

#inputMessageField{
  background-color: lightgray;
  padding: 10px;
}

section input{
  width: 90%;
  padding: 2px;
  outline: none;
  cursor: pointer;
}

</style>