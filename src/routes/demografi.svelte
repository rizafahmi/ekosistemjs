<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>
<div class="container">
  <h1>Demografi</h1>
  <p>Total responden adalah 165 orang dari berbagai latar belakang dan tersebar di berbagai lokasi. Meskipun awalnya survei ini ditujukan untuk developer frontend, namun tidak sedikit pula yang bekerja sebagai developer backend hingga para pengambil keputusan seperti team lead, Vice President of Engineering hingga C-level seperti CTO juga turut serta sebagai responden.</p>
  <p>Satu fakta menarik lagi selain dari berbagai daerah di Indonesia, ada pula yang mengisi survei ini dari Singapura dan Taiwan!</p>

  <h2>Responden per Lokasi</h2>
  <Image title="Presentase per Lokasi" name="domisili-persentase" />

  <Image title="Peta Persebaran" name="domisili" />

  <Image title="Kisaran Umur" name="umur" />

  <Image title="Pengalaman Kerja" name="pengalaman" />

  <Image title="Kisaran Gaji" name="gaji" />

  <Image title="Perusahaan" name="pekerja" />

  <Image title="Kegiatan/Pekerjaan" name="kegiatan" />

  <Image title="Jenis Kelamin" name="gender" />

  <NavBottom 
    prevHref="/" 
    prevLabel="Pengantar" 
    nextHref="/komunitas"
    nextLabel="Komunitas"
    />
</div>
