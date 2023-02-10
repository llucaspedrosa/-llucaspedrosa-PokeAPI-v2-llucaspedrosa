<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>
<template>
  <section class="backgroundModal">
    <div class="positionCard">
      <div class="modalCardUp">
        <div class="positionButtonClose">
          <button  class="closeButton">X</button>
        </div>

        <p class="allEvolution">Evoluções</p>

        <div class="positionEvolution">
          <button class="nameEvolution">bulbasaur</button>
          <button class="nameEvolution">ivisauro</button>
          <button class="nameEvolution">chupassauro</button>
          <button class="nameEvolution">chupassauro</button>
          <button class="nameEvolution">chupassauro</button>
        </div>
        <div class="paddingCard">
          <div class="positionNameOrder">
            <p class="cardName">Bulbasaur</p>
            <p class="cardOrder">#0001</p>
          </div>
          <div class="positionType">
            <p class="cardType">Grass</p>
            <p class="cardType">Poison</p>
          </div>
        </div>
      </div>
      <img src="../assets/img/Bulbasaur.png" alt="" />
      <div class="modalCardLow">
        <p class="cardAbility">Sobre</p>
        <div class="positionAboutPokemon">
          <div class="positionAbout">
            <p class="statisticBase">Hp</p>
            <p class="statistic">10</p>
          </div>
          <div class="positionAbout">
            <p class="statisticBase">Attack</p>
            <p class="statistic">20</p>
          </div>
          <div class="positionAbout">
            <p class="statisticBase">Defense</p>
            <p class="statistic">9</p>
          </div>
          <div class="positionAbout">
            <p class="statisticBase">Special Attack</p>
            <p class="statistic">20</p>
          </div>
          <div class="positionAbout">
            <p class="statisticBase">Special Defense</p>
            <p class="statistic">1</p>
          </div>
          <div class="positionAbout">
            <p class="statisticBase">Speed</p>
            <p class="statistic">15</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.backgroundModal {
  position: absolute;
  width: 100%;
  height: 100%;
  background: var(--color-Background-Modal);
  top: 0;
  z-index: 7;
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 423px;
}
.positionCard {
  width: 50%;
  height: 700px;
  background-color: var(--color-secondary);
  border-radius: 30px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  animation: modalAnimation 2s;
}
@keyframes modalAnimation {
  0% {
    opacity: 0;
    transform: translateY(-50%);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
.modalCardUp {
  background-color: var(--color-secondary);
  width: 100%;
  height: 50%;
  border-radius: 30px;
}
.positionButtonClose {
  width: 95%;
  display: flex;
  justify-content: flex-end;
  
}
.closeButton {
    color:var(  --color-Grey-0);
    cursor: pointer;
    border-radius:50%;
    width: 30px;
    height: 30px;
    margin-top: 20px;
    background-color: red;
    
}
.allEvolution {
  font-weight: 600;
  font-size: var(--heading-1);
  text-align: center;
  color: var(--color-Grey-0);
  margin-top: 10px;
}
.positionEvolution {
  display: flex;

  width: 100%;
  overflow-x: auto;
}
.positionEvolution::-webkit-scrollbar {
  width: 10px;
  height: 5px;
}
.positionEvolution::-webkit-scrollbar-thumb {
  background-color: black;
  border-radius: 5px;
}
.positionEvolution::-webkit-scrollbar-track {
  background-color: transparent;
}
.nameEvolution {
  font-size: 20px;
  font-weight: 600;
  color: whitesmoke;
  background-color: transparent;
  border-radius: 20px;
  height: 50px;
  width: max-content;
  padding: 10px;

  cursor: pointer;
}
.nameEvolution:hover {
  background-color: var(--color-Grey-100);
}
.positionNameOrder {
  display: flex;
  justify-content: space-between;
}
.paddingCard {
  padding: 30px;
  border-top: solid 2px rgba(128, 128, 128, 0.185);
}

.cardOrder {
  color: var(--color-Grey-0);
  font-size: var(--heading-2);
  padding: 7px;
  font-size: 15px;
}
.cardName {
  color: var(--color-Grey-0);
  font-weight: 700;
  font-size: 28px;
}
.positionType {
  display: flex;
  justify-content: flex-start;
  gap: 10px;
}
.cardType {
  font-size: var(--heading-2);
  color: var(--color-Grey-0);
  background-color: var(--color-secondary-50);
  border-radius: 10px;
  padding: 10px 20px;
  margin-top: 10px;
  font-size: 14px;
}
img {
  width: 300px;
  height: 170px;
  margin-top: 30px;
  position: absolute;
  display: flex;
  top: 33%;
  left: 42%;
}
.modalCardLow {
  background-color: var(--color-Grey-0);
  width: 100%;
  height: 50%;
  border-radius: 30px;
}

.cardAbility {
  margin-top: 60px;
  text-align: center;
  color: var(--color-Grey-50);
  font-size: 22px;
  font-weight: 600;
}
.positionAboutPokemon {
  padding: 10px;
}
.positionAbout {
  display: flex;
  justify-content: space-between;
  padding: 10px;
}
.statisticBase {
  color: var(--color-Grey-50);
  font-size: var(--heading-1);
}
.statistic {
  font-weight: 400;
  font-size: var(--heading-1);
}
@media (max-width: 768px) {
  .backgroundModal {
    position: absolute;
    width: 100%;
    height: 100%;
    background: var(--color-Background-Modal);
    top: 0;
    z-index: 7;
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 423px;
  }
  .positionCard {
    width: 80%;
    height: 700px;
    background-color: var(--color-secondary);
    border-radius: 30px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }
  .modalCardUp {
    background-color: var(--color-secondary);
    width: 100%;
    height: 50%;
    border-radius: 30px;
  }
  .allEvolution {
    font-weight: 600;
    font-size: var(--heading-1);
    text-align: center;
    color: var(--color-Grey-0);
    margin-top: 10px;
  }
  .positionEvolution {
    display: flex;

    width: 100%;
    overflow-x: auto;
  }
  .positionEvolution::-webkit-scrollbar {
    width: 10px;
    height: 5px;
  }
  .positionEvolution::-webkit-scrollbar-thumb {
    background-color: black;
    border-radius: 5px;
  }
  .positionEvolution::-webkit-scrollbar-track {
    background-color: transparent;
  }
  .nameEvolution {
    font-size: 20px;
    font-weight: 600;
    color: whitesmoke;
    background-color: transparent;
    border-radius: 20px;
    height: 50px;
    width: max-content;
    padding: 10px;

    cursor: pointer;
  }
  .nameEvolution:hover {
    background-color: var(--color-Grey-100);
  }
  .positionNameOrder {
    display: flex;
    justify-content: space-between;
  }
  .paddingCard {
    padding: 30px;
    border-top: solid 2px rgba(128, 128, 128, 0.185);
  }

  .cardOrder {
    color: var(--color-Grey-0);
    font-size: var(--heading-2);
    padding: 7px;
    font-size: 15px;
  }
  .cardName {
    color: var(--color-Grey-0);
    font-weight: 700;
    font-size: 28px;
  }
  .positionType {
    display: flex;
    justify-content: flex-start;
    gap: 10px;
  }
  .cardType {
    font-size: var(--heading-2);
    color: var(--color-Grey-0);
    background-color: var(--color-secondary-50);
    border-radius: 10px;
    padding: 10px 20px;
    margin-top: 10px;
    font-size: 14px;
  }
  img {
    width: 300px;
    height: 170px;
    margin-top: 30px;
    position: absolute;
    display: flex;
    top: 33%;
    left: 32%;
  }
  .modalCardLow {
    background-color: var(--color-Grey-0);
    width: 100%;
    height: 50%;
    border-radius: 30px;
  }

  .cardAbility {
    margin-top: 60px;
    text-align: center;
    color: var(--color-Grey-50);
    font-size: 22px;
    font-weight: 600;
  }
  .positionAboutPokemon {
    padding: 10px;
  }
  .positionAbout {
    display: flex;
    justify-content: space-between;
    padding: 10px;
  }
  .statisticBase {
    color: var(--color-Grey-50);
    font-size: var(--heading-1);
  }
  .statistic {
    font-weight: 400;
    font-size: var(--heading-1);
  }
}
</style>
