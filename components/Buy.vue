<template>
  <ul class="buy">
    <li>
      <a
        href="https://play.google.com/store/apps/details?id=com.ehmprah.coredefense"
      >
        <img
          src="/badges/google-play.png"
          alt="Get Core Defense on Google Play"
        />
      </a>
    </li>
    <li>
      <a href="https://apps.apple.com/us/app/core-defense/id1546364145">
        <img
          src="/badges/app-store.png"
          alt="Get Core Defense on the App Store"
        />
      </a>
    </li>
    <li>
      <a href="https://store.steampowered.com/app/1203360/Core_Defense/">
        <img src="/badges/steam.png" alt="Buy Core Defense on Steam" />
      </a>
    </li>
    <li>
      <a href="https://ehmprah.itch.io/core-defense">
        <img src="/badges/itchio.png" alt="Buy Core Defense on itch.io" />
      </a>
    </li>
  </ul>
</template>

<script>
export default {
  name: 'Buy'
};
</script>

<style lang="scss">
ul.buy {
  margin: 60px auto;
  max-width: 700px;
  padding: 0;
  list-style-type: none;
  display: flex;
  justify-content: center;
  li {
    margin: 0 0.5em;
    a {
      display: block;
      border-bottom: none;
      transition: all 0.1s;
      &:hover {
        transform: scale(1.05);
      }
    }
    img {
      display: block;
    }
  }
}
</style>
