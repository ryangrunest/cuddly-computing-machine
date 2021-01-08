<template>
  <div class="columns">
    <div class="column is-10 is-offset-1">
      <div class="container">
        <div class="box">
          <div class="content is-medium">
            <h2>hello {{ user }}. If you're looking for a:</h2>
            <ul>
              <li>easy to use stock ticker tracker</li>
              <li>good time</li>
              <li>dead simple website</li>
            </ul>
            <p>then you've come to the right place.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: ["user"],
};
</script>

<style></style>
