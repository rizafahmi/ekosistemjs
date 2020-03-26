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
    <source type="image/webp" srcset="./img/{name}.webp" />
    <source type="image/png" srcset="./img/{name}.png" />
    <img src="img/{name}.png" alt="{name}" />
  </picture>
</a>
