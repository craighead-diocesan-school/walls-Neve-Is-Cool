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
    width: 15%;
    height: 20%;
    margin-left: 18%;
    margin-top: 2%;
  }

  div {
    width: 15%;
    background-color: #e4e0dd;
    height: 7%;
    text-align: center;
    display: flex;
    flex-direction: column;
    margin-left: 18%;
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
