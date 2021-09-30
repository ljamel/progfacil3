<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div id="displayContent">
      {{ data }}
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default({
 

  el: '#displayContent',
  data () {
    return {
      data: null
    }
  },

  mounted () {
    axios
      .get('https://api.coindesk.com/v1/bpi/currentprice.json')
      .then(response => (this.data = response))
      console.log(this.data)
  }

})
</script>
