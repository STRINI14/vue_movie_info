<template>
  <header>
    <router-link to="/">
      <h1><span>Movie</span>Info</h1>
    </router-link>
  </header>
  <main>
    <router-view />
  </main>
</template>

<style lang="less">
*{
  margin:0;
  padding: 0;
  box-sizing:border-box;
  font-family: 'Fira Sans', sans-serif;

  &::selection{
    background: transparentize(cornflowerblue, 0.5);
  }
}

body{
  background-color: #142d01;
}

a{
  text-decoration: none;
}

header{
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: #2c3d4e;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.1);

  h1{
    color: white;
    font-size: 28px;

    span{
      color:crimson;
      
    }
  }
}
</style>
