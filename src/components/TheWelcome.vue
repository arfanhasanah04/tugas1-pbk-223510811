<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>

    
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
        * SD Islam Al-Amin, Payakumbuh (2009 - 2015): <br>
        Menyelesaikan pendidikan dasar dengan rata-rata nilai 9,0. <br>
        * SMP Negeri 5 Jakarta (2015 - 2018):<br>
        Aktif dalam kegiatan ekstrakurikuler seperti Paduan Suara dan Paskibra.<br>
         *SMA Negeri 10 Jakarta (2018-2021): <br>
        Menjadi ketua kelas dan berpartisipasi dalam berbagai kegiatan sosial di sekolah.<br>
         *Universitas Islam Riau, Pekanbaru (2022 - Sekarang):<br>
        Jurusan Pendidikan Bahasa dan Sastra Indonesia.
        Menjadi anggota aktif dalam organisasi mahasiswa dan mengikuti berbagai seminar dan workshop terkait dengan bidang studi.
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pengalaman Pendidikan</template>

    
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
     Program Pertukaran Pelajar di Universitas Teknologi Sydney (Februari 2024 - Juni 2024)

Sebagai bagian dari program pertukaran pelajar, saya mendapatkan kesempatan untuk belajar di luar negeri di Universitas Teknologi Sydney di Australia. Selama tinggal di sana, saya mengambil mata kuliah lanjutan dalam bidang keamanan informasi dan pengembangan perangkat lunak. Saya juga terlibat dalam proyek kolaboratif lintas budaya dengan mahasiswa dari berbagai negara untuk mengembangkan aplikasi mobile berbasis Android untuk membantu pelacakan polusi udara di kota metropolitan.

    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a> 
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      ></a>

    <br />

     <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Prestasi</template>
    1.Juara 1 Kompetisi Pengembangan Perangkat Lunak (2022). <br>
      Sebagai anggota tim pengembangan perangkat lunak, kami berhasil meraih juara 1 dalam kompetisi nasional yang diadakan oleh Asosiasi Pengembang Perangkat Lunak Indonesia. Produk kami, sebuah platform e-learning berbasis cloud dengan fitur interaktif dan adaptif, dinilai oleh para juri sebagai solusi yang inovatif dan relevan dalam mendukung pembelajaran jarak jauh di masa pandemi COVID-19.

    2.Penghargaan "Mahasiswa Teladan" (2021).<br>
    Dalam pengakuan atas prestasi akademik dan kontribusi positif dalam kegiatan ekstrakurikuler, saya dianugerahi sebagai "Mahasiswa Teladan" oleh Dekan Fakultas Teknik Universitas Bina Nusantara. Prestasi ini mencerminkan dedikasi saya dalam mencapai prestasi akademik yang tinggi sambil tetap aktif dalam organisasi mahasiswa dan kegiatan sosial di lingkungan kampus.

    
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Sosial</template>

    instagram: @arfanhasanah <br>
    facebook : Rfanhas_4

    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a> 
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sertifikasi</template>
    1.Sertifikasi Google Associate Cloud Engineer <br>
    2.Sertifikasi Cisco Certified Network Associate (CCNA) <br>
    3.Sertifikasi Microsoft Certified: Azure Fundamentals <br>
    4.Sertifikasi AWS Certified Solutions Architect - Associate <br>

    
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">Thanks you</a>.
  </WelcomeItem>
</template>
