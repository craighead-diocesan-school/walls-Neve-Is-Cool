<script>
  export let src = ""
  export let alt = ""
  export let description = ""
  export let price = ""
</script>

<img {src} {alt} class="image" />

<div>
  <p class="name">{description}</p>
  <p class="cost">{price}</p>
</div>

<style>
  img {
    width: 10%;
    height: 10%;
  }

  div {
    width: 10%;
    background-color: #e4e0dd;
    height: 60px;
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
</style>
