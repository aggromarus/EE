<script setup>
</script>

<template>
  <main>
    <div class="main__section">
      <div class="wrapper">
        <div class="elevator">лифт</div>
      </div>
      <div class="levels">
        <div class="level">1
        <button class="btn"></button>
        </div>
        <div class="level">2
        <button class="btn"></button>
        </div>
        <div class="level">3
        <button class="btn"></button>
        </div>
        <div class="level">4
        <button class="btn"></button>
        </div>
        <div class="level">5
        <button class="btn"></button>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
.main__section {
  background-color: cornflowerblue;
  width: 350px;
  height: 500px;
  border: 1px solid red;
  position: absolute;
}

.levels {
  display: flex;
  justify-content: stretch;
  flex-direction: column-reverse;
  background-color: grey;
  height: 100%;
  width: 100%;
}
.level{
  position: relative;
  height: 100%;
}
.btn{
  margin: 0;
  padding: 5px;
  border-radius: 30px;
}
.wrapper {
  position: absolute;
  background-color: green;
  width: 50px;
  right: 1px;
  height: 100%;
}
.elevator {
  width: 40px;
  height: 60px;
  border: 3px lightcoral dashed;
  background-color: antiquewhite;
  position: absolute;
}
</style>
