<template>
  <div>
      <div class="fir">
          <div v-for="first in firsts" :key="first.id"></div>

      </div>
      <div class="sec">
          <div v-for="two in twos" :key="two.id">

          </div>
      </div>
  </div>
</template>
<script>
export default {
    data (){
        return{
            firsts :[
                {},
                {}
            ],
            twos :[
                {},
                {},
                {}

            ]
        }
    }
  
}
</script>
<style>
.fir{
    width: 53%;
    height: 670px;
    border: 1px solid black;
    box-sizing: border-box;
    float: left;
}
.sec{
    margin-left: 2%;
    width: 44%;
    height: 670px;
    border: 1px solid red;
    box-sizing: border-box;
    float: left;
}

.fir div{
    width: 100%;
    height: 49%;
    border: 1px solid red;
    box-sizing: border-box
}
.fir :nth-child(2){
    margin-top: 13px;
}
.sec div{
    width: 100%;
    height: 31.5%;
    border: 1px solid blue;
    box-sizing: border-box;
}
.sec :nth-child(2){
    margin-top: 20px;
}
.sec :nth-child(3)
{
    margin-top: 20px;
}
</style>


