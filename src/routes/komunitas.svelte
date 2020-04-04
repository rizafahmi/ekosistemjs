<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Komunitas Sekitar</h1>

  <p>Berikut adalah data komunitas di daerah masing-masing yang disebutkan oleh para responden. Komunitas yang paling banyak disebutkan adalah <a href="https://jakartajs.org" target="_blank">JakartaJS</a>. Sedangkan kota dengan jumlah komunitas yang paling banyak adalah Malang.</p>

  <p>Sedangkan untuk komunitas berdasarkan framework, yang paling banyak disebut oleh responden ternyata adalah komunitas JavaScript secara umum baik itu komunitas seperti JakartaJS, BandungJS, SurabayaJS hingga NodeJS dan masih banyak yang lainnya. Diluar komunitas JavaScript, komunitas React merupakan komunitas yang paling banyak dikenal dengan 7,88%.</p>

  <p>Satu hal yang menarik, ternyata ada lebih dari <strong>28%</strong> para responden yang tidak mengetahui komunitas di daerahnya. Ini menjadi peluang dan pekerjaan rumah untuk kita semua para penggerak komunitas untuk lebih menyebarluaskan informasi terkait komunitas masing-masing.</p>

  <Image title="Komunitas per Daerah" name="daerah" />
  <Image title="Komunitas per Framework" name="framework" />

  <NavBottom 
    prevHref="/demografi" 
    prevLabel="Demografi" 
    nextHref="/belajar" 
    nextLabel="Belajar" />
</div>
