<script setup>
import Button from './Button.vue'
import Section from './Section.vue'
</script>
<template>
  <Section class="hero">
    <h1 class="title">The Progressive JavaScript Framework</h1>
    <p class="description">An approachable, performant and versatile framework for building web user interfaces.</p>
    <div class="actions">
      <Button class="action" label="Why vue ?" />
      <Button class="action" label="Get started" />
      <Button class="action" label="Install" />
    </div>
  </Section>
</template>

<style scoped>
.hero {
  text-align: center;
}

.title {
  background: -webkit-linear-gradient(315deg,#42d392 25%,#647eff);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 72px;
  font-weight: 800;
  line-height: 1.2;
  margin-bottom: 16px;
}

.description {
  margin-bottom: 16px;
}

.actions {
  display: flex;
  justify-content: center;
  width: 100%;
}

.actions .action:not(:last-child){
  margin-right: 8px;
}
</style>