<template>
  <div class="cardWrapper">
    <div class="cart"
         v-for="(card, idx) in cards"
         :key="idx"
    >
          <img :src="require('@/assets/images/' + card.imgFrame)" class="cart__frame">
          <img :src="require('@/assets/images/' + card.img)" class="cart__crystal">
      <div class="cart__text">
        <h5>&#10799;{{ card.number }}</h5>
        <p>Handful of Coins</p>
      </div>
      <div class="cart__btn">
        <button>Купить <span>$</span> 10</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CartItem",
  data() {
    return {
      cards: [
        {
          number: 100,
          imgFrame: 'Frame.png',
          img: 'crystals_1.png'
        },
        {
          number: 500,
          imgFrame: 'Frame.png',
          img: 'crystals_2.png'
        },
        {
          number: 1000,
          imgFrame: 'Frame_750.png',
          img: 'crystals_3.png'
        },
        {
          number: 1500,
          imgFrame: 'Frame.png',
          img: 'crystals_4.png'
        },
        {
          number: 100,
          imgFrame: 'Frame.png',
          img: 'crystals_5.png'
        },
        {
          number: 500,
          imgFrame: 'Frame.png',
          img: 'crystals_6.png'
        },
        {
          number: 1000,
          imgFrame: 'Frame_750.png',
          img: 'crystals_7.png'
        },
        {
          number: 1500,
          imgFrame: 'Frame.png',
          img: 'crystals_8.png'
        },
        {
          number: 100,
          imgFrame: 'Frame.png',
          img: 'crystals_9.png'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>