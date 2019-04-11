<template>
  <footer>
    <img id="dog_footer" :src="dog" alt="Transparent Dog footer">
  </footer>
</template>

<script>
import dog from './assets/img/dog.png';
export default {
  data: function(){
    return {
      dog: dog
    };
  }
}
</script>

