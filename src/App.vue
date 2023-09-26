<script setup>
</script>

<template>
  <main>
    <div class="main__section">
      здание
      <div class="elevator wrapper">
        лифт
      </div>
      <div class="levels">
        <div class="level">1</div>
        <div class="level">2</div>
        <div class="level">3</div>
        <div class="level">4</div>
        <div class="level">5</div>
      </div>
    </div>
  </main>
</template>

<style>
.main__section {
  width: 350px;
  height: 500px;
  border: 1px solid red;
}

.elevator {
  width: 40px;
  height: 60px;
  border: 3px lightcoral dashed;
}

.levels {
  background-color: grey;
  height: 100%;
  width: 100%;
}
</style>
