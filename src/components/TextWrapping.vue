<template>
<v-app>
    <div
      class="text-no-wrap text-example"
      style="width: 8rem;"
    >
      This text should overflow the parent.
    </div>
  </v-app>
</template>

<style lang="scss">
  .text-example {
    background-color: rgba(86, 61, 124,.15);
    border: 1px solid rgba(86, 61, 124,.15);
    }
  .v-application--wrap {
    min-height: 100% !important;
  }
  .theme--light.v-application {
    background: none !important;
  }
</style>