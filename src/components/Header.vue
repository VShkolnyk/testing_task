<template>

    <header>
      <div class="flex wrapper">
        <div>
          <button class="btnHeader"><img src="@/assets/images/Arrow_back.png"> BACK</button>
          <button class="wrapper__smallScreen"><img src="@/assets/images/Arrow_back.png"></button>
        </div>

        <div class="flex wrapper__buy">
          <div class="flex">
            <img src="@/assets/images/coins.png" class="imgHeader">
            <div>
              <h5>100 254</h5>
              <p>Coins</p>
            </div>
            <button class="btnPlus">+</button>
          </div>

          <div class="flex">
            <img src="@/assets/images/crystals_2.png" class="imgHeader">
            <div>
              <h5>1 254</h5>
              <p>Crystals</p>
            </div>
            <button class="btnPlus">+</button>
          </div>
        </div>

        <div>
          <button class="btnHeader"><img src="@/assets/images/Home.png"> HOME</button>
          <button class="wrapper__smallScreen"><img src="@/assets/images/Home.png"></button>
        </div>
      </div>
    </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>

</style>