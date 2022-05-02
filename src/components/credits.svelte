<script>
  console.log(Neutralino.app.open);
  const buyABeerLink = 'https://www.buymeacoffee.com/raffaelemori';
  function buyABeer() {
    Neutralino.os.open(buyABeerLink);
  }
</script>
<fieldset>
  <legend>Credits</legend>
  If you think it's a good project and you'd like to thank the developer, why not offer him a
  <span role="link" on:click={buyABeer} alt="offer a beer to the developer" target="_blank">beer</span>?

</fieldset>

<style>
  fieldset {
    border-radius: 5px;
    padding: 50px 20px;
  }

  [role="link"] {
    cursor: pointer;
    text-decoration: underline;
    color: #0000EE;
  }
</style>