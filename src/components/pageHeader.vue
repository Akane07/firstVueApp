<template>
    <div class="homePageBaggin">
        <div class="header">
            <div class="logo"> <img src="../assets/logo.svg" alt=""></div>
            <div class="catalog">
                <div class="catalogCurs">
                    <p>Каталог курсов</p>
                    <button class="listButton"><img src="../assets/CaretDown.svg" alt=""></button>
                </div>
                <button class="selectedWorks">Избранное</button>
            </div>
            <div class="buttons">
                <button class="search"><img src="../assets/search.svg" alt=""></button>
                <button class="login">Вход</button>
                <button class="signin">Регистрация</button>
            </div>
        </div>
        <img src="../assets/Patern.svg" alt="" class="patern">
        <img src="../assets/Image.png" alt="хуй сосите" class="homePageImage">
        <div class="content">
              <p class="heroText">Основные языки программирования для начинающих</p>  
              <p class="heroContext">Мы предоставляем вам доступ к лучшим курсам по изучению программирования, позволяя вам изучить бесчисленное множество практических уроков по целому ряду тем.</p>
              <div class="searchDiv">
              <div class="searchInputDiv">
                <input class="searchInput" type="text" placeholder="Название курса, автор или предмет">
                <button class="searchButt"><img src="../assets/Search2.svg" alt=""></button>
              </div>
              <p class="heroSearch">Популярные : HTML, C++, Python, Java, JavaScript</p>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style>
    .homePageBaggin{
        display: flex;
        background-color: #1C1C1C;
        width: 100%;
        height: 732px;
        flex-wrap: wrap;
    }
    .homePageImage{
        width: 600px;
        height: 732px;
        position: absolute;
        right: 0;
    }
    .header{
        width: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        height: 80px;
        padding: 6px;
        justify-content: space-around;
        z-index: 2;
    }
    .catalog{
        display: flex;
        justify-content: space-around;
        font-family: "Plus Jakarta Sans";
        height: 26px;
        align-items: center;
        margin-left: 300px;
    }
    .catalogCurs{
        color: #F9F9F9;
        height: 24px;
        display: flex;
        justify-content: space-around;
    }
    .catalogCurs p{
        height: 24px;
    }
    .selectedWorks{
        background-color: #1C1C1C;
        outline: none;
        color: #F9F9F9;
        border: 0;
        width: 88px;
        height: 24px;
        margin: 50px;
    }
    .listButton{
        background-color: #1C1C1C;
        outline: none;
        color: #F9F9F9;
        border: 0;
        margin-top: 4px;
        cursor: pointer;
    }
    .buttons{
        z-index: 4;
        display: flex;
        align-items: center;
        height: 40px;
        margin-right: -40px;
        
    }
    .search{
        outline: none;
        border: 0;
        background: transparent;
        cursor: pointer;
        padding: 18px;
    }
    .login{
        outline: none;
        border: 1px solid #32BCA3;
        color: #32BCA3;
        border-radius: 20px;
        height: 40px;
        width: 102px;
        background: transparent;
        cursor: pointer;
    }
    .signin{
        outline: none;
        color: #FFFFFF;
        border: 1px solid #32BCA3;
        width: 164px;
        height: 40px;
        border-radius: 20px;
        background-color: #32BCA3;
        cursor: pointer;
        margin-left: 18px;
    }
    .patern{
        position: absolute;
        z-index: 1;
    }
    .content{
        width: 716px;
        height: 471px;
        margin-top: 64px;
        margin-left: 135px;
        z-index: 2;
    }
    .heroText{
        font-size: 70px;
        color: #F9F9F9;
    }
    .heroContext{
        color: #E0E0E0;
        font-size: 20px;
        margin-top: 14px;
    }
    .searchInputDiv{
        background-color: #FFFFFF;
        width: 716px;
        height: 40px;
        border-radius: 30px;
        margin-top: 60px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
    }
    .searchInput{
        height: 24px;
        width: 598px;
        color: #A8A8A8;
        font-size: 16px;
        border: 0;
        outline: none;
    }
    .heroSearch{
        font-size: 16px;
        color: #E0E0E0;
      
    }
    .searchButt{
        background-color: #32BCA3;
        width: 38px;
        height: 38px;
        border: 0;
        border-radius: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
    }
</style>