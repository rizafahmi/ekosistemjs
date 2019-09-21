<script>
  import { onMount } from 'svelte';

  onMount(() => {
    window.sk=window.sk||function(){(sk.q=sk.q||[]).push(arguments)};

    sk('form', 'init', {
      id: '65993958bc37',
      element: '#email-form'
    });


  })
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
  a {
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
    <form id="email-form" action="">
      <input type="email" required id="email" name="email">
      <button type="submit">Ingatkan saya</button>

      <div data-sk-error="email"></div>
    </form>
  </div>
  <div class="cta">
    <a href="https://rizafahmi.com" target="_blank">Ikuti Survey</a>
  </div>
</div>
