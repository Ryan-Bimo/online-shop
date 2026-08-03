<script setup>
import ProductCard from '../components/ProductCard.vue'
 
const daftarProduk = [
  { id: 1, nama: 'James Boogie | Ventile', harga: 750000, gambar: 
'https://jamesboogie.com/_next/image?url=https:%2F%2Fvps.jamesboogie.com%2Fwp-content%2Fuploads%2F2026%2F03%2FTest-Ventile2-1-of-1-scaled.jpg&w=3840&q=75' },
  { id: 2, nama: 'Caps James Boogie', harga: 350000, gambar: 
'https://tse3.mm.bing.net/th/id/OIP.2InhwRieaLNZFpzTfwqhrwHaJQ?r=0&rs=1&pid=ImgDetMain&o=7&rm=3' },
  { id: 3, nama: 'SlingBag LadsClub', harga: 120000, gambar: 
'https://down-id.img.susercontent.com/file/id-11134207-822wq-mm8nbwxjmp6o75' },
]
</script>
 
<template>
  <main>
    <h1>Produk Kami</h1>
    <div class="grid">
      <ProductCard
        v-for="produk in daftarProduk"
        :key="produk.id"
        :nama="produk.nama"
        :harga="produk.harga"
        :gambar="produk.gambar"
      />
    </div>
  </main>
</template>
 
<style scoped>
.grid {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}
</style>