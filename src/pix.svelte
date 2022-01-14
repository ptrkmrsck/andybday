<script>
  let picNum = Math.floor(Math.random() * 4) + 1

  let src = 'pix/andrew1.png';
  let picTempo = setInterval(() => {
    src = `pix/andrew${Math.floor(Math.random() * 4) + 1}.png`
  }, 350);
</script>

<img {src} alt="andy flexin">


<style>
  *{ 
    justify-content: center;
  }
  img {
    width: 100%;
  }
</style>

