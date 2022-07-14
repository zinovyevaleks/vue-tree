<template>
  <div>
    <TreeItem :node="root"></TreeItem>
  </div>
</template>
<script>
import TreeItem from "@/components/TreeItem.vue";
export default {
  data() {
    return {
      root: {
        name: '/',
        children: [
          {
            name: "Dir 1",
            children: [
              {
                name: "Dir 1-1",
                children: [
                  {
                    name: "File 1-1-1",
                  },
                ],
              },
              {
                name: "File 1-2",
              },
            ],
          },
          {
            name: "Dir 2",
            children: [
              {
                name: "Dir 2-1",
              },
              {
                name: "File 2-1",
              },
            ],
          },
          {
            name: "File 3",
          },
        ],
      },
    };
  },
  components: {
    TreeItem,
  },
};
</script>

<style lang="scss"></style>