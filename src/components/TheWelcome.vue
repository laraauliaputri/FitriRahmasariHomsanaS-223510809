<script setup lang="ts">
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
    <template #heading>Tentang</template>
    Nama lengkap saya ialah Fitri Rahmasari Homsana, dan saya dilahirkan di Sorek satu, sebuah desa kecil yang terletak di Riau, Indonesia, pada tanggal 14 November 2004. Saat ini, saya sedang menjalani perjalanan pendidikan sebagai mahasiswi di Universitas Islam Riau yang beralamat di Jalan Kaharuddin Nst, Pekanbaru. Telah beberapa waktu saya habiskan dalam perjalanan pendidikan ini dan kini saya berada di semester keempat. Di lingkungan universitas ini, saya mengambil jurusan Teknik Informatika, sebuah bidang yang sejak awal telah memikat minat dan perhatian saya. Berada dalam atmosfer akademis ini memberikan peluang bagi saya untuk menimba ilmu dan tumbuh berkembang dalam bidang yang saya minati, sambil bertemu dengan berbagai individu yang memiliki minat dan impian yang serupa.
</WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/5692371065472000936B" target="_blank" rel="noopener">SDN 027 Bukit Kesuma</a></li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/FBDC73E3DB0411172E0A" target="_blank" rel="noopener">SMPN 1 Sei Suka</a></li>
      <li><a href="https://smaswastamitrainalum.sch.id/" target="_blank" rel="noopener">SMAS Mitra Inalum</a></li>
      <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    Ketrampilan adalah kunci kesuksesan dalam berinteraksi, berkolaborasi, dan menyesuaikan diri di dunia kerja    <ul>
      <li>C++</li>
      <li>css</li>
      <li>HTML</li>
      <li>jAVASCRIPT</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    <ul>
    <li>Anggota Osis</li>
      <li>Unit Kesehatan Sekolah</li>
      <li>Rohis</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
Saya menggunakan sosial media untuk mencari informasi dan memposting tugas, instagram
   :<a href="https://www.instagram.com/homsana_" target="_blank">homsana_</a>
  </WelcomeItem>
</template>