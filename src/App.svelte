<script>
  import logo from './assets/svelte.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <img src={logo} alt="Svelte Logo" />
  <h1>Hello SVELTE ~</h1>
  <Counter />
</main>

<style lang="less">
  main {
    height: 100%;
    display: flex;
    flex-flow: column nowrap;
    align-items: center;
    justify-content: center;

    img {
      height: 100px;
      width: 100px;
    }
    h1 {
      color: #ff3e00;
      text-transform: uppercase;
      font-size: 20px;
      font-weight: normal;
      margin: 2rem auto;
    }
  }
</style>
