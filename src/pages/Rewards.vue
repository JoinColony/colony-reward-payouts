<template>
  <q-page class="flex justify-center">
    <div class="row self-start" style="width: 1024px;">
      <Payouts class="q-px-md col-12 col-sm-8" />
      <Toolbar class="q-px-md col-12 col-sm-4 column" />
    </div>
  </q-page>
</template>

<script>
import Payouts from "components/Payouts";
import Toolbar from "components/Toolbar";

export default {
  components: {
    Payouts,
    Toolbar
  }
};
</script>
