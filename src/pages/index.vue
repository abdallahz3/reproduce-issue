<script setup>
import Index from "~/playgrounds/example/Index.jsx";
</script>


<template>
  <div class="about">
    <h1>This is an about page</h1>
    <!-- the line below first just reexports ~/playgrounds/example/Index.jsx, Works! -->
    <Hello client:only />
    <!-- the line below uses the component directly, does NOT works -->
    <!-- <Index client:only /> -->
  </div>
</template>

<style>
</style>
