<!-- <script>
  import NavBar from "../componets/NavBar.svelte";
</script>

<NavBar /> -->
<script>
  import NavBar from "../componets/NavBar.svelte";
  let title = "Strength N Number";
  let src = "images/connections.jpg";
</script>

<NavBar />
<h1 class="title">{title}</h1>

<p1 class="para">
  Copy Helping bring your organization together one connection at a time. We
  simplify the process of meeting new friends to a few simple clicks. Sign up or
  log in to get started connected with your peers!</p1
>

<button class="button">Create Account</button>

<img {src} class="img" alt="Connections" />

<style>
  .title {
    position: absolute;
    width: 1032px;
    height: 107px;
    left: 98px;
    top: 274px;
    font-family: Roboto;
    font-style: normal;
    font-weight: 900;
    font-size: 72px;
    line-height: 120.19%;
    /* or 87px */

    letter-spacing: 0.01em;

    color: #000000;
  }
  .para {
    position: absolute;
    width: 605px;
    height: 216px;
    left: 98px;
    top: 470px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 31px;
    letter-spacing: 0.03em;

    color: #000000;
  }
  .button {
    position: absolute;
    width: 278px;
    height: 60px;
    left: 98px;
    top: 610px;
    color: black;
    background-color: white;
    border-radius: 29px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
  }

  .img {
    position: absolute;
    width: 551px;
    height: 595px;
    left: 842px;
    top: 149px;

    background: linear-gradient(
        180.03deg,
        rgba(255, 255, 255, 0.7) 20.39%,
        rgba(0, 0, 0, 0) 99.97%
      ),
      url(DSC08951.jpg);
    border-radius: 20px;
  }
</style>
