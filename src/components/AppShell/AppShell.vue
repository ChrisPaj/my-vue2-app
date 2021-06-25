<template>
  <div>
    <scale-app-shell>
        <top-bar slot="header"></top-bar>
        <scale-footer slot="footer"></scale-footer>
		<scale-button />
    </scale-app-shell>
  </div>
</template>

<script>
import Vue from "vue";
import { ScaleAppShell, ScaleButton } from "@telekom/scale-components-vue";
import TopBar from "../../components/TopBar/TopBar.vue";
import ScaleFooter from "../../components/Footer/Footer.vue";

export default Vue.extend({
  name: "AppShell",
  components: { ScaleAppShell, TopBar, ScaleFooter, ScaleButton },
  data() {
    return {};
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
