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

<script>
export default {
  name: 'IndexPage',
  components: {  },
}
</script>
