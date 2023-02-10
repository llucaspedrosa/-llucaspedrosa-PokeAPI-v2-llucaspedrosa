<template>
  <label>
    <input type="text" placeholder="Pesquise seu pokémon aqui!" />
  </label>
</template>

<style scoped>
label {
  display: flex;
  flex-direction: column;
  font-size: 12px;
  color: #999999;
  z-index: 1;
  margin-top: 80px;
}

input {
  background: #ffffff;
  border: 2px solid #333333;
  border-radius: 5px;
  width: 73%;
  padding: 15px;
  margin: 0 auto;
  z-index: 0;
  min-width: 394px;
}
@media (max-width: 768px) {
  label {
    display: flex;
    flex-direction: column;
    font-size: 12px;
    color: #999999;
    z-index: 1;
    margin-top: 80px;
  }

  input {
    background: #ffffff;
    border: 2px solid #333333;
    border-radius: 5px;
    
    padding: 15px;
    margin: 0 auto;
    z-index: 0;
  }
}
</style>
