<script>
  import Header from "$lib/Header.svelte"
  import Wall from "$lib/Wall.svelte"

  const walls = [
    {
      name: "Brick wall painted white",
      img: "https://digitech.craighead.school.nz/wall-shop-images/white-brick.jpg",
      price: 14.9,
    },
    {
      name: "Brick wall painted pink",
      img: "https://digitech.craighead.school.nz/wall-shop-images/pink-brick.jpg",
      price: 19.9,
    },
    {
      name: "Unpainted brick wall",
      img: "https://digitech.craighead.school.nz/wall-shop-images/unpainted-brick.jpg",
      price: 9.9,
    },
    {
      name: "Plaster wall painted orange",
      img: "https://digitech.craighead.school.nz/wall-shop-images/orange-plaster.jpg",
      price: 11.9,
    },
    {
      name: "Run-down wall painted yellow",
      img: "https://digitech.craighead.school.nz/wall-shop-images/yellow-run-down.jpg",
      price: 4.9,
    },
    {
      name: "Run-down wall painted grey",
      img: "https://digitech.craighead.school.nz/wall-shop-images/grey-run-down.jpg",
      price: 4.9,
    },
    {
      name: "Run-down wall painted tan",
      img: "https://digitech.craighead.school.nz/wall-shop-images/tan-run-down.jpg",
      price: 4.9,
    },
    {
      name: "Really rough wall",
      img: "https://digitech.craighead.school.nz/wall-shop-images/rough.jpg",
      price: 4.9,
    },
    {
      name: "Wall with flowers",
      img: "https://digitech.craighead.school.nz/wall-shop-images/flowers.jpg",
      price: 24.9,
    },
    {
      name: "Art-deco wall",
      img: "https://digitech.craighead.school.nz/wall-shop-images/art-deco.jpg",
      price: 34.9,
    },
  ]
</script>

<Header />
<div></div>
<main>
  <section>
    {#each walls as wall}
      <Wall src={wall.img} alt={wall.name} description={wall.name} price={wall.price} />
    {/each}
  </section>
</main>

<div></div>

<footer>
  <p>&copy; NeveGaffaney2025</p>
</footer>

<style>
  main {
    background-color: #afd5be;
    height: 1500px;
  }

  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  div {
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

  @media screen and (max-width: 1000px) {
    main {
      height: 3870px;
    }

    section {
      flex-direction: column;
      align-items: center;
    }

    div {
      height: 20px;
    }
  }
</style>
