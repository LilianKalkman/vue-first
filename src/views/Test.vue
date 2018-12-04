<template>
  <div class="test">
    <h1>This is an test page</h1>
    <p>{{ value }}</p>
    <p>{{ name }}</p>
    <Test message="Test Prop doorgegeven"/>
  </div>
</template>

<script>
import Test from "@/components/EventCard.vue";

export default {
  name: "test",
  components: {
    Test
  },
  data: function() {
    return {
      value: 3,
      name: "Lilian"
    };
  }
};
</script>
