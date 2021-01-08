<template>
  <div class="columns">
    <div class="column is-3 is-offset-1">
      <div class="container">
        <div class="box">
          <div class="content is-medium">
            <p class="mb-1">add ticker</p>
            <input class="input is-primary" type="text" placeholder="PLTR" />
            <div class="buttons mt-2">
              <button class="button is-primary">Add</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="column is-7">
      <div class="container">
        <div class="box">
          <div class="content">tickers will display here...</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tickers",
};
</script>

<style></style>
