<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Proses Belajar</h1>

  <Image title="Framework Yang Dikuasai" name="framework-2" />
  <Image title="Frontend Framework yang Ingin Dipelajari" name="frontend" />
  <Image title="Backend Framework yang Ingin Dipelajari" name="backend" />
  <Image title="Media Belajar Favorit" name="media" />
  <Image title="Cara Belajar Favorit" name="cara" />

  <NavBottom 
    prevHref="/komunitas" 
    prevLabel="Komunitas" 
    nextHref="/memilih"
    nextLabel="Memilih"
    />
</div>
