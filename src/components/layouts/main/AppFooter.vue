<template>
  <div class="container">
    <div class="titles">
      <h2>Support Center</h2>
      <div>
        <span>800-25-Platt</span>
        <span class="small">800-257-5288</span>
      </div>
      <span class="bold grey">4 a.m. - 12 a.m. (pst)</span>
      <span class="bold grey">7 Days a week</span>
    </div>
    <button class="help-button">
      <img src="@/assets/icon/black/ic_comment.png" />
      <span>Live Help</span>
    </button>
    <div class="bottom-links">
      <a class="bold">Contact Us</a>
      <a class="bold">What’s New</a>
      <a class="bold">FAQ’s</a>
    </div>
  </div>
</template>

<script lang="ts">
import { Vue } from "vue-class-component";

export default class AppFooter extends Vue {}
</script>

<style lang="scss" scoped>
.container {
  padding: 1.5rem 1rem;
  background-color: var(--grey);
  color: var(--white);

  .titles {
    text-align: center;

    h2 {
      margin: 0.5rem 0rem 1rem 0rem;
    }
  }

  span,
  a {
    margin-top: 0.2rem;
    margin-bottom: 0.2rem;
    display: block;
    font-size: 1.2rem;

    &.bold {
      font-weight: bold;
    }
    &.small {
      font-size: 0.8rem;
      font-weight: 300;
      margin-bottom: 1rem;
    }
    &.grey {
      color: var(--grey-light);
    }
  }

  .help-button {
    margin: 1.5rem 0rem 1.5rem 0rem;
    padding: 0.5rem 5rem;
    border-radius: 7rem;
    display: flex;
    align-items: center;

    img {
      margin-right: 0.5rem;
    }
    span {
      font-size: 1rem;
    }
  }

  .bottom-links {
    margin: 1rem 0.5rem 0rem 0.5rem;
    width: 100%;
    display: flex;
    justify-content: space-evenly;
  }
}
</style>
