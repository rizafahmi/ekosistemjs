<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Testing</h1>

  <p>Dari data yang didapat, ternyata banyak juga yang belum menerapkan testing untuk pengembangan aplikasi. Dari keseluruhan responden ada 21% yang menyatakan bahwa aplikasi yang dikembangkan belum menggunakan testing sama sekali. Sedangkan 19% lainnya sudah menerapkan testing meski belum seluruhnya. Hanya sekitar 13% yang mengharuskan testing untuk aplikasi yang dikembangkan.</p>

  <Image title="Penerapan Testing" name="testing" />
  <Image title="Alat Bantu Testing" name="alat" />

  <p>Dan untuk alat bantu testing sendiri, ternyata Jest memimpin cukup jauh dengan pencapaian hampir 30%. Hal ini mungkin dikarenakan Jest cukup populer digunakan di sisi frontend, meski tidak jarang Jest juga digunakan di sisi backend. Kemudian disusul dengan Mocha yang mencapai 9%, lalu karma dengan 2%. Ada pula dua responden yang menggunakan testing library dan satu orang menggunakan ava.</p>

  <NavBottom 
    prevHref="/memilih" 
    prevLabel="Memilih" 
    nextHref="/kesimpulan"
    nextLabel="Kesimpulan"
    />
</div>
