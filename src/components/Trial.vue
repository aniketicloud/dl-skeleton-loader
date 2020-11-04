<template>
  <div class="placeholder">
    <dl-skeleton type="circle" animation="fade" color="red"/>
    <dl-skeleton type="error" height="30" :errorMessage="errorMessage"/>
  </div>
</template>

<script>
import DLSkeleton from "./DLSkeleton";
export default {
  components: {
    "dl-skeleton": DLSkeleton,
  },

  data(){
    return{
      errorMessage: "from End of the world"
    }
  }
};
</script>

<style lang="scss" scoped>
.placeholder {
  margin: 15px;
  padding: 10px;
  border-radius: 5px;
  background-color: darkblue;
}
</style>