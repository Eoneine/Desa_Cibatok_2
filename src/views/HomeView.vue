<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold mt-4">Visi</p>
      <p> “ Lanjutkan Suksesi Pembangunan Untuk Mewujudkan Cibatok Dua Yang Bermartabat (Bersih, Sehat, Religius, Mandiri, Tertib, Aman, Berbudaya dan Transparan) dan Berkeadaban" M</p>
      <p class="text-lg font-semibold mt-4">Misi</p>
      <ul>
      <li>1. Menciptakan Tata Kelola Pemerintahan Desa yang baik dan bersih (good and clean governance), akuntabel dan transparan dengan meningkatkan wawasan dan pengetahuan perangkat desa dan peran serta lembaga desa yang terkait;</li>
      <li>2. Menumbuhkembangkan serta mengoptimalkan seluruh potensi untuk meningkatkan derajat kesehatan dan pendidikan masyarakat desa;</li>
      <li>3. Menciptakan dan meningkatkan kemandirian usaha dengan menumbuhkembangkan potensi lokal desa serta mengoptimalkan peran serta BUMDES serta Pembangunan Fisik Infrastruktur bagi peningkatan perekonomian masyarakat;</li>
      <li>4. Menjaga kondusifitas, keamanan dan ketertiban masyarakat dengan menjaga serta menumbuhkembangkan semangat gotong royong dan kebersamaan;</li>
      <li>5. Menjaga nilai-nilai keagamaan dan kearifan lokal dalam upaya menciptakan kondisi masyarakat desa yang religious dan berkeadaban“.</li>
      </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/Struktur_Desa.jpeg" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
