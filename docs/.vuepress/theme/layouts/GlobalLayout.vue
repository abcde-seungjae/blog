<template>
  <div id="global-layout">
    <component :is="$page.path ? 'Layout' : 'NotFound'" />
    <footer class="siteFooter">
      &copy; ㅎㅇㅎㅇ
    </footer>
  </div>
</template>