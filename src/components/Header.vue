<template>
<v-app>
  <div class="header">
    <div class="container">
      <h1 class="name"> Michael Murwayi_ </h1>
      <h5>Software Developer, Cyber Security</h5>
      <div class="row">

      <div class="label" style="margin-left:15px; margin-top:30px; color:black; font-size:2.5vh;"> 
      <p><strong>Age:</strong></p> 
      <p><strong>Phone:</strong></p>
      <p><strong>Address:</strong></p>
    </div>
    <div class="details" style="margin-left:45px; margin-top:30px; font-size:2.5vh;">
      <p><strong>23</strong></p> 
      <p><strong>0746256084</strong></p>
      <p><strong>Nairobi Kenya</strong></p>
    </div>
  </div>
  </div>
  </div>  
</v-app>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.header{
  background-image:linear-gradient(to right, rgba(0, 0, 252, 0.73), rgba(106, 90, 205, 0.73)), url('../assets/me.jpeg');
  background-size: cover;
  height: 60vh;
  width: 100vw;
  position: absolute;
  top: 0px;
  left: 0px;
}
.container{
  position: absolute;
  top:20vh;
  left: 40vw;
  width: 500px;
  color: white;
}
.label{
  color:white;

}
</style>
