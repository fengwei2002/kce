<template>
    <MonacoEditor id="editor" lang="cpp" :options="{ theme: 'vs' }" />
</template>

<style>
html,
body,
#__nuxt,
#editor {
  width: 100%;
  height: 100%;
  margin: 0;
}

#editor {
  margin-top: 15px !important;
}
</style>
