<script>
  function showAlert() {
    alert("Akan segera hadir. Nanti dikabari via email.");
    document.getElementById('field_0').focus();
  }
</script>
<style>

  h1 {
    text-align: center;
    margin: 0 auto;
    font-size: 2.8em;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 0.5em 0;
    color: #FF6260;
    font-family: 'Minecrafter';
    text-shadow: 8px 8px rgba(78, 53, 60, 255);
  }
  h1 > .ekosistem {
    color: #FF6260;
  }
  h1 > .javascript {
    color: #645AFF;
  }
  h1 > .indonesia {
    color: #34C2F2;
  }
  p {
    font-family: Minecrafter;
    font-size: 1.5em;
    text-shadow: 4px 4px rgba(78, 53, 60, 255);
    text-align: center;
    color: #1DD8DF;
  }

  .email-form {
    text-align: center;
    border: 0.5em groove #34C2F2;
    padding: 1.5em;
    margin: 4em;
  }
  form {
    margin: 0.5em;
  }
  .cta {
    display: flex;
    justify-content: center;
  }
  input {
    font-family: New;
    font-size: 1.25em;
    padding: 0.5em;
    color: #34C2F2;
    background-color: #262E36;
    border: 0.2em groove #34C2F2;
  }
  button {
    font-family: New;
    font-size: 1.0em;
    padding: 0.6em 0.5em 0.6em 0.5em;
    border: 0.5em groove #34C2F2;
    background-color: #262E36;
    color: #34C2F2;
  }

  .container {
    border: 1em groove #34C2F2;
    padding: 1.5em;
  }
  a.button {
    border: 0.75em groove #34C2F2;
    padding: 1em;
    text-decoration: none;
    font-family: Minecrafter;
  }
  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
</style>

<svelte:head>
  <title>Ekosistem JavaScript di Indonesia</title>
</svelte:head>

<div class="container">
  <h1><span class="ekosistem">Ekosistem</span> <span class="javascript">JavaScript</span> <span class="indonesia">di Indonesia</span></h1>
  <p>Statistik dan survey ekosistem JavaScript di Indonesia</p>

  <div class="email-form">
    <h2>Segera mengudara</h2>
    <span>Akan dikabarkan melalui email</span>
    <form method="post"
      action="https://emailoctopus.com/lists/c8bff2b5-dc4e-11e9-be00-06b4694bee2a/members/embedded/1.3/add"
      class="email-octopus-form"
      data-sitekey="6LdYsmsUAAAAAPXVTt-ovRsPIJ_IVhvYBBhGvRV6"
    >
      <input id="field_0" name="field_0" type="email" placeholder="alamat email kamu">
      <input type="text" name="hpc8bff2b5-dc4e-11e9-be00-06b4694bee2a"
                         tabindex="-1"
                         style="display: none;"
                         autocomplete="nope">
      <input type="hidden"
             name="successRedirectUrl"
             value="https://ekosistemjs.herokuapp.com/terimakasih">
      <button type="submit">Ingatkan saya</button>
    </form>
  </div>
  <div class="cta">
    <a class="button" on:click={showAlert}>Ikuti Survey</a>
  </div>
</div>


