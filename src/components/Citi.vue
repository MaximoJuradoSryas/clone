<template>

<div>
    <div class="header">
        <div class="header-wrapp">
                    <img src="https://www.citi.com/CBOL/IA/Angular/assets/citilogoredesign.png" >
                <div class="cajaubi">
                        <p class="ubi"><img src="https://cdn-icons-png.flaticon.com/512/535/535239.png" width="30" height="30" ><br>
                        ATM/BRANCH
                        </p>
                        <br>
                        <p class="tradu"><img src="https://cdn-icons-png.flaticon.com/512/900/900782.png" width="30" height="30" ><br>
                        ESPAÑOL
                        </p>
                </div>
        </div>
    </div>
    <div class="divbar">
        <nav class="bar">
            <ul>
                <li><a class="menu" href="#">Credit Cards</a></li>
                <li><a class="menu" href="#">Banking</a></li>
                <li><a class="menu" href="#">Lending</a></li>
                <li><a class="menu" href="#">Investing</a></li>
                <li><a class="menu" href="#">Wealth Management</a></li>
                
                <li class="help"> <a href="#"><i id="Lupita" class="fa-solid fa-magnifying-glass"></i>  How can we help?</a></li>
            </ul>
        </nav>
        
    </div>
    <div class="box-loading">
        <div class="textoinici">
            <p class="indo1">CITI® CHECKING ACCOUNTS</p>
            <p class="indo2"> Checking Made Simple</p>
            <p class="indo3">Enjoy checking with 24/7 digital banking and no minimum opening deposit.</p> 
            <div class="learn">
                <p class="learns">Learn More</p>
            </div>

        </div>
    <div class="mujer">
        <img src="https://online.citi.com/JRS/banners/homepage2/HP_277_Generic_Hero_Image.png" width="300" height="300" >

    </div>
    <div class="box-sing">
        <div class="sing">
            <div class="box-user-cont"> 
                <div class="user-box">
                    <p class="user">User ID</p>
                </div>
                <div class="password-box">
                    <p class="password">Password</p>
                </div>
            </div>
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
@import url('https://fonts.googleapis.com/css2?family=Alfa+Slab+One&family=Belleza&family=Source+Sans+Pro:ital,wght@0,200;0,900;1,700&display=swap');

.user{
    font-size: small;
    width: 50px;
    margin: 0;
    padding: 0;

}
.password{
    font-size: small;
    width: 50px;
    margin: 0;
    padding: 0;

}

.box-user-cont{
    flex-direction: row;
    height: 33.3%;
    background-color: yellow;
}

.box-sing{
    width: 500px;
    height: 400px;
    display: flex;
    
}

.sing{
    width: 80%;
    height: 80%;
    justify-content: center;
    align-items: center;
    align-items: center;
    border: 5px;
    border-radius: 5%;
    margin: 10%;
    -webkit-box-shadow: 0px 0px 29px -6px rgba(135,135,135,1);
    -moz-box-shadow: 0px 0px 29px -6px rgba(135,135,135,1);
    box-shadow: 0px 0px 29px -6px rgba(135,135,135,1);
    flex-direction: row;
}

.header{
    width: 100%;
    height: 75px;
    display: flex;
}

.header-wrapp{
    width: 100%;
    padding: 0 35px 0 20px;
    display: flex;
    justify-content: space-between;
    
}
.cajaubi{
    justify-content: center;
    align-items: center;
    flex-direction: row;
    display: flex;
    width: 200px;
}
.menu{
    font-family: 'Alfa Slab One', cursive;
    font-family: 'Belleza', sans-serif;
    font-family: 'Source Sans Pro', sans-serif;
    font-size: small;
}
.ubi{
    color:gray;
    margin: 10px;
    width: 100px;
    font-size: small;

}
.tradu{
    color: gray;
    margin: 0;
    width: 100px;
    font-size: small;
}

.textoinici{
    margin-left: 10px;
    justify-content: center;
    padding: 0;
    margin-top:20px;
    flex-direction: column;
}
.indo1{
    padding: 0;
    margin: 0;
}
.indo2{
    padding: 0;
    margin: 20px;
    font-size: 30px;
    font-weight: bold;
    font-family: 'Alfa Slab One', cursive;
    font-family: 'Belleza', sans-serif;
    font-family: 'Source Sans Pro', sans-serif;
}
.indo3{
    padding: 0;
    margin: 0;
}
.logo{
    display: flex;
    justify-content: start;
    margin: 3px;

}

.bar{
    width: 100%;
    background-color: rgb(0,45,114);
    height: 45px;
    padding: 0%;
    display: block;
}

nav {
    float: left;
    justify-content: center;
    align-items: center;
    text-align: center;
}

nav ul {
    list-style: none;
    overflow: hidden; 
    display: flex;
    margin: 0px;
    justify-content: center;
    align-items: center;
    text-align: center;
}

nav ul li {
    float: left;
    font-family: Arial, sans-serif;
    justify-content: center;
    align-items: center;
    
}

nav ul li a {
    display: block; 
    color: #fff;
    text-decoration: none;
    margin: 14px;
    justify-content: center;
    align-items: center;
    text-align: center;
    
}

nav ul li:hover {
    background: #226cff;
    justify-content: center;
    align-items: center;
    text-align: center;

}


.help{
    margin-left: auto;
    margin-right: 50px;
}
.divbar{
    width: 100%;
    height: 45px;
}
.box-loading{
    width: 100%;
    height: 700px;
    display:flex;
}

.learn{
    background-color: rgb(33, 118, 245);
    width: 150px;
    justify-content: center;
    align-items: center;
    text-align: center;
    height: 50px;
    margin:10%;
    margin-left: 40%;
    display : flex;
    border-radius: 10px;
    color: white;
    
    
}
.mujer{
    margin-top:50px;
}



</style>