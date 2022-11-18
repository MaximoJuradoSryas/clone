<template>
  <div class="header">
      <div class="header-wrapp">
        <div class="logo">
            <img src="https://www.citi.com/CBOL/IA/Angular/assets/citilogoredesign.png" >
                <div class="cajaubi">
                <p class="ubi"><img src="https://cdn-icons-png.flaticon.com/512/535/535239.png" width="30" height="30" ><br>
                ATM/BRANCH
                </p>
                </div>
                
                    <div class="cajatra">
                        <p class="tradu"><img src="https://cdn-icons-png.flaticon.com/512/900/900782.png" width="30" height="30" ><br>
                        ESPAÑOL
                        </p>
                    </div>
        </div>
      </div>
  </div>


</template>

<script>
export default {

}
</script>

<style>

.header{
    width: 100%;
    height: 100px;
    display: flex;
}

.header-wrapp{
    width: 100%;
    padding: 0 35px 0 20px;
    display: grid;
    grid-auto-rows: 4fr;
    justify-content: space-between;
    
}
.cajaubi{
    justify-content: center;
    align-items: center;
    flex-direction: row;
    

}

.ubi{
    color:gray;
    margin: 10px;

}
.tradu{
    color: gray;
    margin: 10px;
}


.logo{
    display: flex;
    justify-content: start;
    margin: 3px;

}

</style>