<template>
  <div id="app"><Kanban :data="data"/></div>
</template>

<script>
import Kanban from "./components/Kanban";
export default {
  name: "App",
  components: {
    Kanban,
  },
  data() {
    return {
      data: [
        {
          name: "todo",
          color: "#6699FF",
          tasks: [],
        },
        {
          name: "todo",
          color: "#6633FF",
          tasks: [],
        },
        {
          name: "todo",
          color: "#CC33CC",
          tasks: [],
        },
      ],
    };
  },
};
</script>

<style>
#app {
  height: 100vh;
}
</style>
