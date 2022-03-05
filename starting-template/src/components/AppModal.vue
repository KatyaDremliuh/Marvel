<template>
  <div
    class="modal fade"
    id="exampleModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Человек-паук</h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <img
            src="https://i.annihil.us/u/prod/marvel/i/mg/9/30/538cd33e15ab7/standard_xlarge.jpg"
            class="img-fluid rounded-start"
            alt="..."
          />
          <div>
            <h5>Описание:</h5>
            <p>
              Укушенный радиоактивным пауком, старшеклассник Питер Паркер обрел
              скорость, силу и силу паука. Приняв имя Человек-паук, Питер
              надеялся начать карьеру, используя свои новые способности.
              Наученный тому, что с большой силой приходит большая
              ответственность, Паук поклялся использовать свои силы, чтобы
              помогать людям.
            </p>

            <h5>Комиксы:</h5>
            <ul>
              <li>Spider-Man: 101 Ways to End the Clone Saga (1997) #1</li>
              <li>2099 Alpha (2019) #1</li>
              <li>A YEAR OF MARVELS TPB (Trade Paperback)</li>
              <li>A Year of Marvels: April Infinite Comic (2016) #1</li>
              <li>A Year of Marvels: February Infinite Comic (2016) #1</li>
              <li>A+X (2012) #4</li>
              <li>Absolute Carnage (2019) #1</li>
              <li>Absolute Carnage (2019) #2</li>
              <li>Absolute Carnage (2019) #5</li>
              <li>Absolute Carnage: Symbiote Spider-Man (2019) #1</li>
              <li>
                Actor Presents Spider-Man and the Incredible Hulk (2003) #1
              </li>
              <li>Adventures of Spider-Man (1996) #1</li>
              <li>Adventures of Spider-Man (1996) #2</li>
              <li>Adventures of Spider-Man (1996) #3</li>
              <li>Adventures of Spider-Man (1996) #4</li>
              <li>Adventures of Spider-Man (1996) #5</li>
              <li>Adventures of Spider-Man (1996) #6</li>
              <li>Adventures of Spider-Man (1996) #7</li>
              <li>Adventures of Spider-Man (1996) #8</li>
              <li>Adventures of Spider-Man (1996) #9</li>
            </ul>
          </div>
        </div>
        <div class="modal-footer">
          <button
            type="button"
            class="btn btn-secondary"
            data-bs-dismiss="modal"
          >
            Закрыть
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppModal",
};
</script>

<style scoped></style>
