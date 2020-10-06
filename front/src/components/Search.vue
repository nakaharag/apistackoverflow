<template>
  <div class="search">
    <div class="search-wrapper">
      <input class = "search" type="text" v-model="search" placeholder="Perguntar.."/>

      <div class="btn perguntar">Perguntar</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Search'
}
</script>

<style scoped>
  input.search {
    padding-left: 3rem;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 750px;
    height: 50px;
    font-family: "Fira Code Medium";
    font-size: 24px;
    background: url(../assets/stack.png) no-repeat left center;
    background-size: 2.5rem 2.5rem;
  }

  input.search::placeholder{
    font-family: "Fira Code Light";
    font-size: 20px;
  }

  .perguntar {
    cursor: pointer;
    color: #fff;
    background-color: #0095ff;
    padding: 25px;
    flex: fit-content;
    box-sizing: border-box;
    box-shadow: inset 0 1px 0 0 rgba(255,255,255,0.4);
    width: 20%;
    margin-top: 5px;
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 0;
    border-radius: 3px;
    border: 1px solid transparent;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    font-size: 23px;
  }

  .perguntar:hover {
    background-color: #007cf0;
  }
</style>