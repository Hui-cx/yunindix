<template>
  <div>关于本站：YuIndex 极客范儿的浏览器主页</div>
  <div>
    <a href="javascript:;">
      代码开源，欢迎 star 和贡献~
    </a>
  </div>
  <div></div>
  <div>
    作者：
    <a href="javascript:;">
      程序员陈晓辉
    </a>
  </div>
</template>

<script setup lang="ts">
interface InfoBoxProps {
  seconds: string;
}

const props = withDefaults(defineProps<InfoBoxProps>(), {});
</script>

<style scoped></style>
