<template>
  <div class="app-container">1003</div>
</template>
<script>
import Dialog from "@/components/ModalDialog/Dialog.vue";
import pageMixin from "@/utils/mixin";
export default {
  components: {
    Dialog,
  },
  mixins: [pageMixin],
  data() {
    return {
      params: {
        page: 0,
        size: 50,
        direction: "ASC",
        properties: "id",
      },
    };
  },
  created() {},
  methods: {},
};
</script>
