<template>
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Canteen Landing Page</title>
    <!-- Custom style -->

    <!-- Poppins font -->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
  </head>
  <body class="antialiased">

  <!--NAVBAR-->
  <NavbarComponent />

  <!--HERO-->
  <HeroComponent />
  <!--.HERO-->

  <!-- container -->
  <MainContainerComponent />
  <!-- .container -->

  <FooterComponent />

  <!-- AOS init -->
  <script>
    AOS.init();
  </script>
  </body>
  </html>
</template>

<style>
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
export default {
  name: 'IndexPage',
  components: {  },
}
</script>
