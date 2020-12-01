<template>

  <div class="appx">

        <p>
          <!-- use router-link component for navigation. -->
          <!-- specify the link by passing the `to` prop. -->
          <!-- `<router-link>` will be rendered as an `<a>` tag by default -->
          <router-link id="home" to="/">|| Home ||</router-link>
          <router-link id="ping" to="/ping">|| Go to Ping ||</router-link>
          <router-link id="person" to="/persons">|| Go to Persons ||</router-link>
          <router-link id="rol" to="/rol">|| Go to Rol ||</router-link>
        </p>
    <router-view/>
  </div>
</template>


<style>
.appx {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#home{
  margin-right: 50px;
}
#ping{
  margin-right: 50px;
}
#person{
  margin-right: 50px;
}
#rol{
  margin-right: 50px;
}

</style>


