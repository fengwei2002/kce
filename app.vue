<template>
    <MonacoEditor id="editor" lang="cpp" :options="{ theme: 'vs-dark' }" />
</template>

<style>
html,
body,
#__nuxt,
#editor {
  margin-top: 15px !important;
  width: 100%;
  height: 100%;
  margin: 0;
}
</style>
