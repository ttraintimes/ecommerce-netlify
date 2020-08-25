<template>
  <footer>
    <section class="callout">
      <h2>"bottom words"</h2>
      <p>SPHINX</p>
    </section>
    <app-footer-links />
    <div class="sarahstuff">
      <p>@SPHINX2020
      </p>
    </div>
  </footer>
</template>

<script>

export default {
  components: {
  }
};
</script>

<style lang="scss" scoped>
.callout {
  width: 100%;
  height: 280px;
  background: url("/callout.jpg") center center no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: white;
  h2 {
    padding: 0 30px;
    text-align: center;
  }
}

.sarahstuff {
  background: black;
  width: 100%;
  padding: 10px 30px;
  color: white;
  text-align: center;
}

a,
a:visited,
a:active {
  color: #e6e6e6;
  font-weight: bold;
}
</style>