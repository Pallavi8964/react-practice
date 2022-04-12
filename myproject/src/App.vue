<template>
  <div id="app">
    <b-row>
      <b-col >
        <Nav></Nav>
      </b-col>
      <b-col cols="11"> 
        <Header></Header>
        <Sidebar></Sidebar>
        <router-view/>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
