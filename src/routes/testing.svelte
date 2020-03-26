<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Testing</h1>

  <Image title="Penerapan Testing" name="testing" />
  <Image title="Alat Bantu Testing" name="alat" />

  <NavBottom 
    prevHref="/memilih" 
    prevLabel="Memilih" 
    nextHref="/kesimpulan"
    nextLabel="Kesimpulan"
    />
</div>
