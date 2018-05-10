<template>
  <router-view></router-view>
</template>

<style lang="sass">
// 1. Your custom variables and variable overwrites.
@import "./assets/vars";

// 2. Import default variables and available mixins.
@import "uikit/src/scss/variables-theme.scss";
@import "uikit/src/scss/mixins-theme.scss";

// 3. Your custom mixin overwrites.

// 4. Import UIkit.
@import "uikit/src/scss/uikit-theme.scss";
</style>
