<template>
    <header class="flex justify-between ">
        <div class="flex items-center gap-[59px]">
            <img class="w-[286px] h-[70px]"  src="/logoHeader.png" alt="">

              <nav class="flex gap-[50px]">

                  <NuxtLink class="nav-link" to="/" active-class="active">О НАС</NuxtLink>
                  <NuxtLink class="nav-link" to="/portfolio" active-class="active">ПОРТФОЛИО</NuxtLink>
                  <NuxtLink class="nav-link" to="/service" active-class="active">УСЛУГИ</NuxtLink>
                  <NuxtLink class="nav-link" to="/contact" active-class="active">КОНТАКТЫ</NuxtLink>

              </nav>
        </div>

        <div class="flex items-center">
            <div class="flex items-center pr-[49px] gap-[16px]">
                <img class="w-[24px] h-[24px]" src="/wkHeader.png" alt="">
                <img class="w-[24px] h-[24px]" src="/odnoklassnikiHeader.png" alt="">
                <img class="w-[24px] h-[24px]" src="/facebookHeader.png" alt="">
                <img class="w-[24px] h-[24px]" src="/twitterHeader.png" alt="">
            </div>
            <div class="flex items-center pr-[39px] gap-[20px]">
                <img class="w-[24px] h-[24px]" src="/phone-call.png" alt="">
                <p class="phone text-[18px]">+7 495 257 55 65</p>
            </div>
            <button>НАПИСАТЬ НАМ</button>
        </div>

    </header>
  </template>

<style scoped>

    header{
        padding: 20px 30px;
        border-bottom: 2px solid rgba(146, 115, 152, 0.2);
    }

    a{
        font-family: 'Geoform', sans-serif;
    }
    p{
        font-family: 'Geoform', sans-serif;
    }

    .nav-link {
        color: #927398;
        font-weight: 300;
        font-size: 14px;

        position: relative;
        text-decoration: none;
        display: inline-block;
    }



    .nav-link.active {
        font-size: 14px;
        color: #fff;
        font-weight: 500;
    }

    .nav-link.active::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    height: 2px;
    background-color: #F25C3A;
    margin-bottom: -45px;
    
    }

    .phone{
        color: white;
    }

    button{
        font-family: 'Geoform', sans-serif;
        color: white;
        border: 2px solid white;
        padding: 7px 15px;
        font-weight: 500;
        font-size: 14px;
    }

</style>