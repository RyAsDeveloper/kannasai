<script setup lang="ts">


</script>

<!--Vueの基本: https://qiita.com/TakahiRoyte/items/bd2496ccf181610dc072 -->
<!-- 源柔ゴシックのライセンスについて http://jikasei.me/info/license.html#SIL_Open_Font_License_11_3 -->



<template>
  <img src="./assets/img/logo.png" alt="logo" class="logo">

  <img src="./assets/img/dishes.png" alt="Logo" class="dishes">

  <div class="main">
    <div class="box">
      <div class="food">
        <p class="title">Food Menu</p>
        <div class="content">
          <p class="foodname">さいころステーキ串 ¥100</p>
          <p class="foodname">塩/たれ</p>
          <p class="alergy">牛肉 大豆 たまご 乳成分 ゼラチン</p>
          <p class="alergy">(たれ味のみ りんご ごま 小麦)</p>

          <p class="foodname addspace">ポテト ¥100</p>

          <p class="foodname addspace">餃子 ¥150 (5個)</p>
          <p class="alergy">豚肉 鶏肉 ごま 大豆 小麦</p>

          <p class="foodname addspace">焼きおにぎり ¥100 (2個)</p>
          <p class="alergy">ごま 大豆</p>

          <p class="foodname addspace">からあげ ¥100 (2個)</p>
          <p class="alergy">鶏肉 小麦 大豆</p>

          <p class="foodname addspace">えだまめ ¥100</p>
          <p class="alergy">大豆</p>
        </div>
      </div>

      <div class="example_drink">
        <p class="example">メニューの見方</p>
        <div class="content_example">
          <p class="foodname">メニュー名 ¥価格</p>
          <p class="alergy">アレルゲン</p>
        </div>

        <p class="title">Drink Menu</p>
        <div class="content">
          <p class="drinkprice">all ¥50</p>
          <p class="foodname addspace">コーラ</p>

          <p class="foodname addspace">麦茶</p>
          <p class="alergy">小麦</p>

          <p class="foodname addspace">オレンジジュース</p>
          <p class="alergy">オレンジ</p>

          <p class="foodname addspace">こどもビール</p>
        </div>

      </div>

      


    </div>
    
  </div>
</template>

<style>
.logo {
  position: absolute;

  width: 50%;
  margin-left: 5px;

  top: 3%;
  left: 10%;

  transform:rotate(-15deg);
}

.dishes {
  width: 90%;

  margin: 0px;
  margin-top: 25%;
  padding-left: 5%;
  padding-right: 5%;
}

.main {
  display: inline-block;



  width: 90vw;
  
  margin: 2%;
}





/* Menuitem用のスタイルシート */
.box {
    width: 95vw;
    height: fit-content;

    display: flex;
}

.food {
  width: 43vw;
}

.example_drink {
  width: 43vw;
  margin-left: 4vw;
}

.content {
  text-align: left;

  border-radius: 20px;
  background-color: #fcefb6;

  padding-top: 30px;
  padding-bottom: 10px;

  margin-top: -15%;

}

.content_example {
  text-align: left;

  border-radius: 20px;
  background-color: #fcefb6;

  padding-top: 10px;
  padding-bottom: 10px;

  margin-top: -15%;
}

.title {
    font-family: "forte", "genjyuuX";
    font-size: 30px;

    color: #ac1410;

    margin: 0px;
}

.example {
  font-family: 'genjyuuX-bold';
  font-size: 20px;

  color: #ac1410;

  height: 45px;

  padding-top: 1px;

  margin: 0px;
}

.drinkprice {
  font-family: "genjyuuX-bold";
  font-size: 3.2vw;


  padding-left: 10px;
  margin: 0px;

  color: #ac1410;
}

.foodname {
  font-family: "genjyuuX-heavy";
  font-size: 3.2vw;

  
  padding-left: 10px;
  margin: 0px;

}

.addspace {
  margin-top: 10px;
}

.alergy {
  font-family: "genjyuuX-medium";
  font-size: 2.2vw;

  padding-left :10px;
  margin: 0px;
}


</style>