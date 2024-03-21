<script>
  import photo1 from "$lib/images/photo.jpg";
  import photo2 from "$lib/images/photo2.jpg";
  import photo3 from "$lib/images/photo3.jpg";
  import photo4 from "$lib/images/photo4.jpg";
  import photo5 from "$lib/images/photo5.jpg";
</script>

<div class="container">
  <img alt="фото 1" src={photo1} width="400" />
  <br />
  <img alt="фото 2" src={photo2} width="400" />
  <br />
  <img alt="фото 3" src={photo3} width="400" />
  <br />
  <img alt="фото 4" src={photo4} width="400" />
  <br />
  <img alt="фото 5" src={photo5} width="400" />
  <br />
</div>

<style>
  .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px;
  }
</style>
