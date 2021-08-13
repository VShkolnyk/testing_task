<template>
  <div class="cardWrapper">
    <div class="cart"
         v-for="(card, idx) in cards"
         :key="idx"
    >
      <img :src="require('@/assets/images/' + card.img)" class="cart__crystal">
      <div class="cart__text">
        <h5>&#10799;{{ card.number }}</h5>
        <p>Handful of Coins</p>
      </div>
      <div class="cart__btn">
        <button>Купить <span><img src="@/assets/images/crystals_2.png"></span> 10</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CartItemCoins",
  data() {
    return {
      cards: [
        {
          number: 1000,
          img: 'coins.png'
        },
        {
          number: 5000,
          img: 'coins_2.png'
        },
        {
          number: 10000,
          img: 'coins_3.png'
        },
        {
          number: 10000,
          img: 'coins_4.png'
        },
        {
          number: 1000,
          img: 'coins_5.png'
        },
        {
          number: 5000,
          img: 'coins_6.png'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>