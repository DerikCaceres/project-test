<template>
  <v-app>
    <Header/>

    <v-main >
      <HelloWorld/>
    </v-main>

    <Footer/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Header from './components/Header';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Header,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>
