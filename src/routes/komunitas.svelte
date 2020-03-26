<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>
<div class="container">
  <h1>Komunitas Sekitar</h1>

  <Image title="Komunitas per Daerah" name="daerah" />
  <Image title="Komunitas per Framework" name="framework" />

  <NavBottom 
    prevHref="/demografi" 
    prevLabel="Demografi" 
    nextHref="/ketertarikan" 
    nextLabel="Ketertarikan" />
</div>
