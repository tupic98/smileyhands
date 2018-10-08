<template>
    <div class="page-wrapper" style="height: 100%">
        <toolbar />
        <v-content style="height: 100%">
            <router-view class="animated slideInUp"></router-view>
        </v-content>
    </div>
</template>

<script>
import Toolbar from "../components/navigation/Toolbar.vue";
export default {
    
  data() {
    return {
      show: true,
    };
  },

  components: {
    Toolbar,
  },

  methods: {
  }
};
</script>

<style scoped>
.page-wrapper {
  background-color: #e1e4e5;
}

</style>