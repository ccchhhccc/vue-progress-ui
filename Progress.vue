<template>
  <div class="progress-c">
    <span class="progress-cpg"></span>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.progress-c {
  background: #1a1a1a;
  height: 35px;
  border-radius: 5px;
  box-shadow: 0 1px 5px #000 inset, 0 1px 0 #444;
  text-align: left;
}
.progress-cpg {
  display: inline-block;
  width: 50%;
  height: 100%;
  background-size: 30px 30px;
  background-image: linear-gradient(
    135deg,
    rgba(255, 255, 255, 0.15) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.15) 50%,
    rgba(255, 255, 255, 0.15) 75%,
    transparent 75%,
    transparent
  );
  background-color: #34c2e3;
  border-radius: 3px;
  box-shadow: 0 1px 0 rgba(255, 255, 255, .5) inset;
  animation: 3s progressAni linear infinite;
}
@keyframes progressAni{
  0%{
    background-position: 0 0;
  }
  100%{
    background-position: 60px 0;
  }
}
</style>
