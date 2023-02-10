<template>
  <header>
    <img
      class="imgPokemonLogo"
      src="../assets/img/Logo_Pokemon.png"
      alt="Logo Pokemon"
    />
    <img
      class="imgPikachu"
      src="../assets/img/Pikachu.png"
      alt="Foto Pikachu"
    />
  </header>
</template>

<style scoped>
header {
  background-color: var(--color-primary);
  border-bottom-right-radius: 20px;
  border-bottom-left-radius: 20px;
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
  z-index: 3;
  min-width: 394px;
}

.imgPokemonLogo {
  height: 120px;
  width: 120px;
}
.imgPikachu {
  width: 190px;
  height: 150px;
  position: absolute;
  top: 32px;
  display: flex;
  left: 55%;
  z-index: 1;
}
@media (max-width: 768px) {
  header {
    background-color: var(--color-primary);
    border-bottom-right-radius: 20px;
    border-bottom-left-radius: 20px;
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    z-index: 3;
  }

  .imgPokemonLogo {
    height: 120px;
    width: 120px;
  }
  .imgPikachu {
    width: 190px;
    height: 150px;
    position: absolute;
    top: 32px;
  display: flex;
  left: 55%;
    z-index: 1;
  }
}
</style>
