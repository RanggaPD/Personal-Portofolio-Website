<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>

    Saya
    Seorang Mahasiswa jurusan Fisika yang saat ini sedang menempuh semester 5 di Universitas Negeri Medan. Mempunyai ketertarikan terhadap dunia dan skill digital terutama pada bidang Web Development dan Cyber Security. Aktif mengikuti pelatihan-pelatihan untuk mengembangkan skill digital seperti mengikuti Mata Kuliah Kecerdasan Digital Dasar bersama Progate yang diselenggarakan oleh CFDS FISIP Universitas Gadjah Mada dan mengikuti pelatihan Basic Cyber Security untuk Bidang Kesehatan yang diselenggarakan oleh DIGITALENT dari Kementerian Komunikasi dan Informatika Republik Indonesia.
  </WelcomeItem>
</template>
