<script>
  let picNum = Math.floor(Math.random() * 4) + 1

  let src = '/andrew1.png';
  let picTempo = setInterval(() => {
    src = `/andrew${Math.floor(Math.random() * 4) + 1}.png`
  }, 500);
</script>

<img {src} alt="andy flexin">


<style>

</style>