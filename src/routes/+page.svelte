<script>
  import Header from "$lib/Header.svelte"
  import Image from "$lib/Wall.svelte"
</script>

<Header />
<section></section>
<main>
  <div class="first-row">
    <Image src="placeholder-image.png" alt="Brick wall painted white" description="Brick wall painted white" price="$14.90" />
    <Image src="placeholder-image.png" alt="Brick wall painted pink" description="Brick wall painted pink" price="$19.90" />
    <Image src="placeholder-image.png" alt="Unpainted brick wall" description="Unpainted brick wall" price="$9.90" />
  </div>
  <div class="second-row">
    <Image src="placeholder-image.png" alt="Plaster wall painted orange" description="Plaster wall painted orange" price="$11.90" />
    <Image src="placeholder-image.png" alt="Run-down wall painted yellow" description="Run-down wall painted yellow" price="$4.90" />
    <Image src="placeholder-image.png" alt="Run-down wall painted grey" description="Run-down wall painted grey" price="$4.90" />
  </div>
  <div class="third-row">
    <Image src="placeholder-image.png" alt="Run-down wall painted tan" description="Run-down wall painted tan" price="$4.90" />
    <Image src="placeholder-image.png" alt="Really rough wall" description="Really rough wall" price="$4.90" />
    <Image src="placeholder-image.png" alt="Wall with flowers" description="Wall with flowers" price="$24.90" />
  </div>
  <div class="last-row">
    <Image src="placeholder-image.png" alt="Art-deco wall" description="Art-deco wall" price="$34.90" />
  </div>
</main>

<section></section>

<footer>
  <p>&copy; NeveGaffaney2025</p>
</footer>

<style>
  main {
    background-color: #afd5be;
    height: 1500px;
  }

  .first-row {
    display: flex;
    justify-content: center;
  }
  .second-row {
    display: flex;
    justify-content: center;
  }
  .third-row {
    display: flex;
    justify-content: center;
  }
  .last-row {
    display: flex;
    justify-content: center;
  }

  section {
    background-color: #4059ad;
    height: 30px;
  }

  footer {
    background-color: #cfe3f2;
    color: #4059ad;
    text-align: center;
    height: 50px;
    font-family: "Gelasio", serif;
    padding-top: 15px;
  }
</style>
