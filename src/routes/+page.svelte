<script>
  import Header from "$lib/Header.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Header />
<section></section>
<main>
  <Image src="https://digitech.craighead.school.nz/wall-shop-images/white-brick.jpg&quot;" alt="Brick wall painted white" description="Brick wall painted white" price="$14.90" />
</main>

<section></section>

<footer>
  <p>&copy; Craighead Diocesan School 2024</p>
</footer>

<style>
  main {
    background-color: #afd5be;
  }

  section {
    background-color: #4059ad;
    height: 30px;
  }
</style>
