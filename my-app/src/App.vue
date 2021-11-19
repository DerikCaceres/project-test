<template>
  <v-app>
    <Toolbar/>

    <Header/>
    <v-main >
      <HelloWorld/>
    </v-main>

    <Footer/>
    <Bottomnavigation/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Header from './components/Header';
import Footer from './components/Footer';
import Toolbar from './components/Toolbar';
import Bottomnavigation from './components/Bottomnavigation';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Header,
    Footer,
    Toolbar,
    Bottomnavigation
  },

  data: () => ({
    //
  }),
};
</script>
