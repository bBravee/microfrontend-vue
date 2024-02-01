<template>
  <div class="main-wrapper">
    <div class="text-container">
    <h1>CHR<span class="orange">ON</span>OS</h1>
    <p>Śledź ile zostało czasu do najważniejszych wydarzeń w Twoim życiu dzięki spersonalizowanemu odliczaniu!</p>
    <div class="buttons-wrapper">
      <button class="btn-orange">Zobacz listę wydarzeń</button>
      <button class="btn-white">Dodaj nowe zdarzenie</button>
    </div>
    </div>
    <div class="image-container">
      <img src="../assets/images/undraw_time_management_re_tk5w-2.svg" alt="">

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
  .main-wrapper {
    height: 100%;
    background: url('../assets/images/main-background.png');
    background-size: 100% 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10rem
  }

  .text-container {
    width: 35%;
    display: flex;
    flex-direction: column;
  }

  h1, p {
    margin-top: 0;
    font-weight: 400;
  }

  span {
    font-weight: 600;
  }


  .buttons-wrapper {
    display: flex;
    flex-direction: column;
    gap: .6rem;
    margin-top: 1rem;
  }

  .image-container {
    width: 35%;
  }

  img {
    max-width: 100%;
  }

  .btn-orange {
    padding: .8rem 3.5rem;
    background-color: #F9A826;
    border: 2px solid #F9A826;
    color: white;
    border-radius: 6px;
  }

  .btn-white {
    padding: .8rem 3.5rem;
    background-color: #fff;
    border: none;
    color: #F9A826;
    border: 2px solid #F9A826;
    border-radius: 6px;
  }

  h1 {
    margin-top: 0px
  }

  .orange {
    color: #F9A826;
  }
</style>
