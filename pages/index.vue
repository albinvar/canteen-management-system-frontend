<template>
<div class="container">

  <!--HERO START-->
    <HeroComponent />
  <!--HERO STOP-->

  <!-- CONTAINER START -->
    <MainContainerComponent />
  <!-- CONTAINER END -->
</div>
</template>

<style>
/*primary color*/
.bg-cream {
  background-color: #FFF2E1;
}

/*font*/
body {
  font-family: 'Poppins', sans-serif;
}

.bg-yellow-500 {
  background-color: #F48C06;
}
.text-yellow-500 {
  color: #F48C06;
}
.text-darken {
  color: #2F327D;
}

.floating {
  animation-name: floating;
  animation-duration: 3s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}
@keyframes floating {
  0% { transform: translate(0, 0px); }
  50% { transform: translate(0, 8px); }
  100% { transform: translate(0, -0px); }
}
.floating-4 {
  animation-name: floating;
  animation-duration: 4s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}
@keyframes floating-4 {
  0% { transform: translate(0, 0px); }
  50% { transform: translate(0, 8px); }
  100% { transform: translate(0, -0px); }
}

.floating-2 {
  animation-name: floating;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}
@keyframes floating-2 {
  0% { transform: translate(0, 0px); }
  50% { transform: translate(0, 8px); }
  100% { transform: translate(0, -0px); }
}
</style>


<script>

import aosMixin from '~/mixins/aos'

export default {
  name: 'IndexPage',
  components: { },
  mixins: [aosMixin],
  data() {
    return {
      //
    }
  },
}
</script>
