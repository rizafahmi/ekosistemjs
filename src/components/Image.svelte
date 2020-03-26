<script>
  export let name;
  export let title;
</script>
<style>
  picture {
    display: flex;
    justify-content: center;
  }
</style>
<h3>{title}</h3>
<a href="./img/{name}.png" target="_blank">
  <picture>
    <source type="image/webp" srcset="./img/{name}.webp" loading="lazy" />
    <source type="image/png" srcset="./img/{name}.png" loading="lazy" />
    <img src="img/{name}.png" alt="{name}" loading="lazy" />
  </picture>
</a>
