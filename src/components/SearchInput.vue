<template>
  <div class="searchWrapper">
    <input type="text" id="search" name="search" v-model="searchValue" @input="handleInput"/>
  </div>
</template>

<script>
export default {
  name: 'SearchInput',
};
</script>

<style lang="scss" scoped>
  .searchWrapper {
    margin-top: 50px;
    width: 250px;
    display: flex;
    flex-direction: column;

    input {
      height: 30px;
      border: 0;
      background: none;
      border-bottom: 1px solid black;
    }
  }
</style>
