<template>
  <q-page>
    <div class="rmob">HOME PAGE MOBILE</div>
    <div class="rtab">HOME PAGE TABLET</div>
    <div class="rdes">HOME PAGE DESKTOP</div>
    <q-btn label="Chnage" @click="changename" />
    {{ name }}
  </q-page>
</template>

<script setup>
let name = $ref('test');

const changename = () => {
  name = 'changed';
};
</script>
<style lang=""></style>
