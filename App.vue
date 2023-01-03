<template>
  <img :src="pic" :width="size" :height="size" >
  <h1>{{fistname}}  {{lastname}}</h1>
  <p>งานอดิเรก</p>
  <ul>
    <li>{{hobby[0]}}</li>
    <li>{{hobby[1]}}</li>
    <li>{{hobby[2]}}</li>
    <li>{{hobby[3]}}</li>
    <li>{{hobby[4]}}</li>
  </ul>
  <ul>
    <li>{{general.gender}}</li>
    <li>{{general.weight}}</li>
    <li>{{general.height}}</li>
  </ul>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      fistname:"sayaphorn",
      lastname:"hlongthong",
      hobby:["ฟังเพลง","เล่นเกม","กิน","นอน","ดูการ์ตูน"],
      size:150,
      pic:"https://scontent.fcnx1-1.fna.fbcdn.net/v/t1.6435-9/195887613_491690198762450_3181860344758943641_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=174925&_nc_eui2=AeGL6Ocb-tH5mZawNO1NQOupt5c2fHlSGZi3lzZ8eVIZmOcQ6o_uCXC97OZXk7lUFzW6i0c9rVa7MPDD87N2XMCO&_nc_ohc=MA8TFnm4SiEAX9IG3b4&_nc_ht=scontent.fcnx1-1.fna&oh=00_AfAydmifEIrkK-SoVC_3TregHTYanSg5T_MQPa9HHq_TNQ&oe=63DB057E",
      general:{gender:"female",weight:70,height:160,status:false}
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
