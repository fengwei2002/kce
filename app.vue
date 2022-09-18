<template>
    <MonacoEditor id="editor" lang="cpp" :options="{ theme: 'konng' }" />
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

<script> 
import * as monaco from 'monaco-editor'




monaco.editor.defineTheme(konng, themeData)
monaco.editor.setTheme(konng)


</script>