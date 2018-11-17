
<template>
  <div class="hello">
    <table style="width:65%;height:90%;" align="center">    
      <tr style="background-color:#32A9EE;color:white;">
        <th>Rank</th>
        <th>Team</th>
        <th>Point</th>
        <th>Rating</th>
      </tr>
      <tr v-for="item in items">
        <td><b>{{item.rank}}</b></td>
        <td>{{item.team}}</td>
        <td>{{item.point}}</td>
        <td>{{item.rating}}</td>
      </tr>
    </table>
    </div>
</template>
<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to VUE JS',
      items: [
        {rank: 1,team:'Bangladesh', point: '11',rating:'21'},
        {rank: 2,team:'India', point: '12',rating:'22'},
        {rank: 3,team:'West Indies', point: '13',rating:'23'},
        {rank: 4,team:'Pakistan', point: '14',rating:'24'},
        {rank: 5,team:'Zimbabwe', point: '15',rating:'25'}
      ]
    }
  }
  
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
