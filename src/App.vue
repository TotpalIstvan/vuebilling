<template>
  <div id="app">
    
    <table>
      <th>Kerék</th>
      <tr>
        <td>100</td>
        <td>12</td>
      </tr>
      <th>Teleszkóp</th>
      <tr>
        <td>1000</td>
        <td>300</td>
      </tr>
      <th>Kormány</th>
      <tr>
        <td>230</td>
        <td>5</td>
      </tr>
      <th>Ajtó</th>
      <tr>
        <td>45120</td>
        <td>321</td>
      </tr>
    </table>
  </div>
</template>

<script>


export default {
  name: 'App',
  
  data() {
    return {
      rows: [
        {
          title: 'Kerék',
          price: 100,
          quantity: 12
        },
        {
          title: 'Teleszkóp',
          price: 1000,
          quantity: 300
        },
        {
          title: 'Kormány',
          price: 230,
          quantity: 5
        },
        {
          title: 'Ajtó',
          price: 45120,
          quantity: 321
        },
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
