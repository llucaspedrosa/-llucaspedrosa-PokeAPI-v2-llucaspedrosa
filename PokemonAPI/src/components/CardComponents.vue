<template>
  <section>
    <ul>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
      <li>
        <div class="cardStatistics">
          <div class="displayNameOrder">
            <p class="namePokemon">Bulbasaur</p>
            <p class="orderPokemon">#0001</p>
          </div>
          <div class="displayType">
            <p class="typePokemon">Grass</p>
            <p class="typePokemon">Poison</p>
          </div>
          <img src="../assets/img/Bulbasaur.png" alt="" />
        </div>

        <div class="cardProfile">
          <button type="button">Ver estatística</button>
        </div>
      </li>
    </ul>
  </section>
</template>
<style scoped>
ul {
  width: 80%;
  height: 73vh;
  position: relative;
  display: flex;
  margin: 0 auto;
  margin-top: 10px;
  min-width: 394px;
  padding: 20px;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
  overflow-y: scroll;
  border-radius: 10px;
}
ul::-webkit-scrollbar {
  width: 10px;
}
ul::-webkit-scrollbar-thumb {
  background-color: rgb(255, 211, 17);
  border-radius: 5px;
}
ul::-webkit-scrollbar-track {
  background-color: transparent;
}
li {
  width: 200px;
  height: 270px;
  background-color: #49d0b0;
  border-radius: 30px;
}
.cardStatistics {
  background-color: #49d0b0;
  border-radius: 30px;
  width: 100%;
  height: 50%;
  padding: 20px;
}
.cardProfile {
  background-color: #ffffff;
  border-radius: 30px;
  width: 100%;
  height: 50%;
  display: flex;
  align-items: flex-end;
}
.namePokemon {
  color: #ffffff;
  font-weight: 700;
  font-size: 18px;
}
.orderPokemon {
  color: #ffffff;
  font-size: 12px;
  padding: 7px;
}
.displayNameOrder {
  display: flex;
  justify-content: space-between;
}
.typePokemon {
  font-size: 12px;
  color: #ffffff;
  background-color: #63e0c9;
  border-radius: 10px;
  padding: 1px 10px;
}
.displayType {
  display: flex;
  justify-content: flex-start;
  gap: 10px;
}
img {
  width: 170px;
  height: 100px;
  margin-top: 30px;
}
button {
  width: 90%;
  background-color: #63e0c9;
  padding: 10px;
  border-radius: 20px;
  color: #ffffff;
  margin: 0 auto;
  margin-bottom: 10px;
}
@media (max-width: 768px) {
  ul {
    width: 80%;
    height: 73vh;
    position: relative;
    display: flex;
    margin: 0 auto;
    margin-top: 10px;
    padding: 20px;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
    overflow-y: scroll;
    border-radius: 10px;
  }
  ul::-webkit-scrollbar {
    width: 10px;
  }
  ul::-webkit-scrollbar-thumb {
    background-color: rgb(255, 211, 17);
    border-radius: 5px;
  }
  ul::-webkit-scrollbar-track {
    background-color: transparent;
  }
  li {
    width: 200px;
    height: 270px;
    background-color: #49d0b0;
    border-radius: 30px;
  }
  .cardStatistics {
    background-color: #49d0b0;
    border-radius: 30px;
    width: 100%;
    height: 50%;
    padding: 20px;
  }
  .cardProfile {
    background-color: #ffffff;
    border-radius: 30px;
    width: 100%;
    height: 50%;
    display: flex;
    align-items: flex-end;
  }
  .namePokemon {
    color: #ffffff;
    font-weight: 700;
    font-size: 18px;
  }
  .orderPokemon {
    color: #ffffff;
    font-size: 12px;
    padding: 7px;
  }
  .displayNameOrder {
    display: flex;
    justify-content: space-between;
  }
  .typePokemon {
    font-size: 12px;
    color: #ffffff;
    background-color: #63e0c9;
    border-radius: 10px;
    padding: 1px 10px;
  }
  .displayType {
    display: flex;
    justify-content: flex-start;
    gap: 10px;
  }
  img {
    width: 170px;
    height: 100px;
    margin-top: 30px;
  }
  button {
    width: 90%;
    background-color: #63e0c9;
    padding: 10px;
    border-radius: 20px;
    color: #ffffff;
    margin: 0 auto;
    margin-bottom: 10px;
  }
}
</style>
