<template>
  <div>
    {{ node.name }}
    <TreeItem v-for="child in node.children" :key="child.name" :node="child" />
  </div>
</template>

<script>
export default {
  props: {
    node: Object,
  },
};
</script>