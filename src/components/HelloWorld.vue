<template>
  <h2>404 NOT FOUND</h2>
  <br>
  <div class="logo">
    <img alt="Vue logo" src="../assets/Scarecrow.png" />
  </div>
  <div class="menssage">
    <b>I have bad news for you</b>
    <p>The page you are looking for might be removed or is temporaly unavailable</p>
    <br><br>
    <button>BACK TO HOMEPAGE</button>
  </div>
  <div class="footer">
    <h2>@giansl</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
