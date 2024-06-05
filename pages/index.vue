<script setup lang="ts">

useJsonld({
  '@context': 'https://schema.org',
  '@type': 'WebPage',
  mainEntity: [
    {
      '@type': 'AboutPage',
      name: 'Over ons',
      url: 'https://www.rqst.studio/over-ons',
      description: 'Ontdek het verhaal achter RQST en maak kennis met ons team van creatieve geesten.',
      mainEntityOfPage: {
        '@type': 'WebPage',
        '@id': 'https://www.rqst.studio/over-ons',
      },
    },
    {
      '@type': 'CollectionPage',
      name: 'Cases',
      url: 'https://www.rqst.studio/cases',
      description: 'Ontdek onze creaties.',
      mainEntityOfPage: {
        '@type': 'WebPage',
        '@id': 'https://www.rqst.studio/cases',
      },
    },
    {
      '@type': 'ContactPage',
      name: 'Contact',
      url: 'https://www.rqst.studio/contact',
      description: 'Heb je een RQST? Wij staan voor je klaar.',
      mainEntityOfPage: {
        '@type': 'WebPage',
        '@id': 'https://www.rqst.studio/contact',
      },
    },
  ],
});
</script>

<template>
  <div>
    <head>
      <title>Studio RQST: Waar Webdevelopment, Webdesign en Branding samenkomen - Just Request It</title>
      <meta name="description"
            content="Stap binnen in de wereld van Studio RQST, waar we jouw visie omzetten in digitale realiteit.">

      <meta name="keywords" content="webdevelopment, webdesign, branding, website, op maat, creatieve website">

      <!-- Adres -->
      <meta name="address" content="Bazelstraat 16, 3555 CS Utrecht, Nederland" />

    </head>
    <NavbarNavBar/>
    <HomePage/>
    <Footer></Footer>
  </div>
</template>