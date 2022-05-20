<template>
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Foodie Hub Landing Page</title>

      <!-- Fonts -->
      <!-- Poppins font -->
      <link href="https://fonts.gstatic.com" rel="preconnect" />
      <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap"
        rel="stylesheet"
      />
    </head>
    <body class="antialiased">
      <!-- HEADER START -->

      <!-- NAVBAR START-->
      <NavbarComponent />
      <!-- NAVBAR END -->

      <!-- HEADER END -->

      <!-- MAIN CONTENT START -->
      <Nuxt />
      <!-- MAIN CONTENT END -->

      <!-- FOOTER START -->
      <FooterComponent />
      <!-- FOOTER END -->
    </body>
  </html>
</template>
