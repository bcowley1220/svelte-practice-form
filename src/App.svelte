<script>
  import Header from "./Header.svelte";
  import Form from "./Form.svelte";
  import Footer from "./Footer.svelte";
</script>

<style>
  * {
    padding: 0px;
    margin: 0px;
  }
  body {
    height: 100vh;
    width: 100vw;
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 10% 80% 10%;
  }
</style>

<body>
  <Header />
  <Form />
  <Footer />
</body>
