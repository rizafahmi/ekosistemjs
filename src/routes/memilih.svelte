<script>
  import Image from '../components/Image.svelte';
  import NavBottom from '../components/NavBottom.svelte';
</script>

<div class="container">
  <h1>Memilih Teknologi</h1>

  <Image title="Pertimbangan Memilih Teknologi" name="pertimbangan" />

  <p>Dan berikut merupakan data bagaimana responden memutuskan untuk memilih teknologi, pustaka atau <em>framework</em> untuk kebutuhan masing-masing.</p>
  <p>Developer friendly user friendly dan popularitas merupakan tiga alasan terbesar memilih sebuah teknologi. Developer friendly lebih ke bagaimana sebuah teknologi mudah digunakan oleh developer. Contohnya React sebagai alat bantu yang banyak memberikan kemudahan bagi developer untuk mengembangkan aplikasi yang kompleks sekalipun.</p>
  <p>User friendly disini lebih dimaksudkan kepada bagaimana sebuah teknologi dapat memanjakan pengguna. Contohnya Svelte dapat menghasilkan ukuran JavaScript yang sangat kecil sehingga aplikasi web yang diakses pengguna menjadi lebih cepat. Meskipun terkadang harus mengorbankan developer karena proses pengembangan mungkin tidak semudah menggunakan alat bantu yang lebih fokus kepada developer experience atau DX yang sudah kita bahas diatas.</p>
  <p>Ada pula yang memilih karena sebuah teknologi sudah matang atau <em>mature</em>, yang terkadang merupakan cara yang tepat dan bukanlah hal yang salah. Dan 3% dari responden juga mengaku memilih teknologi berdasarkan talenta yang ada. Ada juga yang memilih sebuah teknologi karena jarang digunakan. Ini juga pendekatan yang menarik.</p>
  
  <NavBottom
    prevHref="/belajar"
    prevLabel="Belajar" 
    nextHref="/testing"
    nextLabel="Testing"
    />
</div>
