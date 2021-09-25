<template>
    <div id="navigation">
        <ul>
            <li>Houses</li>
            <li>About</li>
        </ul>

    </div>
</template>

<script>
export default {}
</script>


<style scoped>
#navigation {
    display: flex;
    width: 100%;
    margin-bottom: 50px;
    margin-left: 10px;
}
ul {
    display: flex;
    list-style: none;
    padding: 0;
    margin: 0 20px 0 0;
  }
  li {
      font-size: 2rem;
      padding: 2px 10px;
      cursor: pointer;
    }
    li:hover {
        color: #7ca971;
      }
</style>