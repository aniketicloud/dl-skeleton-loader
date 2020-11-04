<template>
  <div class="error" :style="style" >
    <h1>[Widget Name] failed to load</h1>
    <p>
      {{errorMessage}}
    </p>
  </div>
</template>

<script>
export default {
  props: {
    height: {
      type: [Number, String],
      default: 35,
    },
    errorMessage: {
      type: String,
      default: "from Error Component"
    },
  },

  computed:{
    style(){
      return{
        height: `${this.height}rem`
      }
    }
  }
};
</script>

<style scoped>
.error {
  padding: 2rem;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

</style>