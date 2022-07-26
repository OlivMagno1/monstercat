<template>
  <div class="home">
    <MenuStructure />
  </div>
</template>

<script>
// @ is an alias to /src
import MenuStructure from "@/components/menu/MenuStructure.vue";

export default {
  name: "HomeView",
  components: {
    MenuStructure,
  },
};
</script>
