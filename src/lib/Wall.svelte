<script>
  export let src = ""
  export let alt = ""
  export let description = ""
  export let price = ""
</script>

<div class="wall">
  <img {src} {alt} class="image" />
  <div>
    <p class="name">{description}</p>
    <p class="cost">${price}</p>
  </div>
</div>

<style>
  .wall {
    display: flex;
    flex-direction: column;
    width: 20%;
    margin-top: 5%;
    margin-left: 5%;
    margin-right: 5%;
  }

  div {
    width: 100%;
    background-color: #e4e0dd;
    text-align: center;
  }

  p {
    font-family: "Gelasio", serif;
  }

  .name {
    color: #1d1e18;
  }

  .cost {
    color: #4059ad;
  }

  @media screen and (max-width: 1000px) {
    .wall {
      width: 80%;
      margin-top: 5%;
      margin-left: 10%;
      margin-right: 10%;
    }
  }
</style>
