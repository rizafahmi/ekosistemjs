<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Proses Belajar</h1>
  <p>Berikut adalah data terkait framework yang saat ini dikuasai, framework yang ingin dipelajari, dan bagaimana responden belajar framework tertentu.</p>

  <Image title="Framework Yang Dikuasai" name="framework-2" />
  <p>Untuk framework yang saat ini dikuasai didominasi oleh React dan Vue. React memimpin dengan angka nyaris <strong>30%</strong>, diikuti dengan Vue yang mendapatkan angka nyaris <strong>20%</strong>. Masih banyak pula yang saat ini menggunakan jQuery sebagai alat bantu dalam pekerjaannya sehari-hari, sekitar <strong>5,5%</strong> responden mengaku sebagai pengguna jQuery. Sedangkan <strong>40%</strong> responden lainnya menggunakan framework lain seperti Stimulus, Ember, Polymer dan termasuk yang tidak mengisi. Ada pula yang menggunakan Express, yang adalah sebuah framework di sisi server atau backend.</p>

  <Image title="Frontend Framework yang Ingin Dipelajari" name="frontend" />
  <p>Sedangkan untuk framework yang ingin dipelajari, di sisi frontend, React dan Vue merupakan framework yang paling diminati. Diikuti dengan jQuery, Angular dan Svelte. Sedangkan 41% responden memilih framework lain, framework backend atau memilih tidak memberikan jawaban. Adapula yang ingin belajar Next.js yang sebenarnya adalah framework diatas React.js.</p>

  <Image title="Backend Framework yang Ingin Dipelajari" name="backend" />

  <p>Meskipun survei ini difokuskan ke sisi frontend, namun ada beberapa responden yang adalah backend developer dan turut serta menambahkan framework yang ingin dipelajari. Juga ada beberapa responden dengan latar belakang frontend yang ingin belajar backend.</p>
  <Image title="Media Belajar Favorit" name="media" />
  <p>Untuk media pembelajaran, sebagian besar responden mengaku belajar dengan media video dan artikel. Sebagian kecil menjawab buku dan hanya satu orang yang menjawab belajar dari mentor. Selebihnya sekitar 63% tidak menjawab pertanyaan terkait media pembelajaran.</p>

  <Image title="Sumber Belajar Favorit" name="cara" />

  <p>Sedangkan untuk sumber belajar hasilnya cukup bervariasi. Nyaris 20% belajar dari dokumentasi resmi. 15% lainnya belajar dari tutorial ataupun artikel dan 15% berikutnya belajar dengan membangun proyek sederhana. Ada pula yang belajar dari contoh aplikasi, boilerplate yang disediakan dan sebagian yang lainnya langsung terjun dengan menggunakan di proyeknya.</p>

  <p>Ada sedikit paradoks dari dua data diatas. Dari statistik sebelumnya, banyak yang tertarik belajar via video, namun di statistik ini banyak yang belajar dari dokumentasi. Padahal dokumentasi biasanya berbentuk tulisan, bukan video. Apakah artinya dokumentasi dengan format video lebih menarik?</p>

  <NavBottom 
    prevHref="/komunitas" 
    prevLabel="Komunitas" 
    nextHref="/memilih"
    nextLabel="Memilih"
    />
</div>
