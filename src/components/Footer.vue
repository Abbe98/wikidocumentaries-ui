<template>
    <footer>
        <ul>
            <li><a href="https://wikidocumentaries.wmflabs.org/">Wikidocumentaries wiki</a></li>
            <li><a href="http://blog.wikidocumentaries.io/en/">Blog</a></li>
            <li><a href="https://www.facebook.com/groups/wikidocumentaries/">Facebook group</a></li>
            <li><a href="https://github.com/wikidocumentaries">Codebase</a></li>
        </ul>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>
<style scoped>
footer {
  height: 45px;
  background: white;
  padding: 10px 20px;
  box-sizing: border-box;
  display: flex;
  justify-content: space-between;
}

footer a {
  color: var(--main-dimmed);
}
</style>
