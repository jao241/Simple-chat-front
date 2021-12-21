<template>
<main id="page">
  <list-of-contacts/>
  <div id="rightSide">
    <message-field/>
    <input-message-field/>
  </div>
</main>
</template>

<script>
import InputMessageField from '../components/InputMessageField.vue';
import ListOfContacts from '../components/ListOfContacts.vue';
import MessageField from '../components/MessageField.vue';

export default {
  name: 'Home',
  components: {
    ListOfContacts,
    MessageField,
    InputMessageField
    
  }
}
</script>

<style scoped>

#page{
  display: flex;
}

#rightSide{
  width: 100%;
}

</style>
