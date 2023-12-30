<script setup>
import Feature from './Feature.vue'
import Section from './Section.vue'
</script>
<template>
  <Section class="features">
    <Feature 
      class="feature"
      title="Approchable"
      description="Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation."
    />
    <Feature 
      class="feature"
      title="Performant"
      description="Truly reactive, compiler-optimized rendering system that rarely requires manual optimization."
    />
    <Feature 
      class="feature"
      title="Versatile"
      description="A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework."
    />
  </Section>
</template>

<style scoped>
.features {
  display: flex;
  justify-content: space-between;
}

.features .feature {
  flex: 0 32%;
}
</style>