<template>
  <header class="bg-indigo-700 m-auto">
    <div class="grid grid-rows-4">
      <div>
        <slot name="logo" />
      </div>
      <div>
        <slot name="search" />
      </div>
      <div>
        <slot name="signIn" />
      </div>
      <div>
        <slot name="navigation" />
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "App-Header",
};
</script>

<style></style>
