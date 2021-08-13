<template>
  <main>

    <section>
      <h2>Кристаллы Незера</h2>
        <CartItem/>
    </section>

    <section>
      <h2>Монеты Незера</h2>
      <CartItemCoins />
    </section>
  </main>
</template>

<script>
import CartItem from "@/components/CartItem";
import CartItemCoins from "@/components/CartItemCoins";
export default {
  name: "MainContent",
  components: {CartItem, CartItemCoins},

}
</script>

<style scoped>

</style>