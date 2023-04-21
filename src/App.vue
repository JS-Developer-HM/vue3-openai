<template>
  <div class="gpt-app">
    <div class="gradient_bg">
      <Navbar />
      <Header />
    </div>
    <Brand />
    <WhatGpt3 />
    <Feature />
    <Possibility />
    <Cta />
    <Blog />
    <Footer />
  </div>
</template>

<style lang="scss"></style>

<script lang="ts">
import * as Containers from "@/containers/index";
import { Navbar, Cta, Brand } from "@/components/index";

export default {
  components: {
    ...Containers,

    Navbar,
    Brand,
    Cta,
  },
};
</script>
