<template>
  <TheContent />
</template>

<script>
import TheContent from '@/components/TheContent.vue';

export default {
  name: 'App',
  components: {
    TheContent
  }
}
</script>

<style lang="scss">
body {
  font-family: $font-base;
  color: $black-1000;
  font-size: 16px;
  font-weight: 400;
  line-height: 25px;
}

p {
  padding: 0;
  margin: 0;
}

h1,
h2,
h3,
h4 {
  padding-top: 10px;
  font-weight: 500;
}

h1 {
font-size: 34px;
line-height: 46px;
}
h2 {
font-size: 28px;
line-height: 38px;
}
h3 {
font-size: 24px;
line-height: 32px;
}
h4 {
  font-size: 22px;
line-height: 28px;
}

a {
  text-decoration: none;
  color: $blue-500;
  cursor: pointer;

  @media (hover: hover) {
        &:hover {
          text-decoration: underline;
        }
      }
}
</style>
