<template>
  <div>
    <PageTitle></PageTitle>
    <JumboHero></JumboHero>
  </div>
</template>

<script>
import PageTitle from "./components/PageTitle.vue";
import JumboHero from "./components/JumboHero.vue";
export default {
  name: "App",
  components: {
    PageTitle,
    JumboHero,
  },
};
</script>


