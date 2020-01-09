<template>
  <div class="container">
    <div>
      <div class="text">
        <h1 class="title">
          Core Defense reinvents tower defense (again) and launches January 16
        </h1>
        <div class="text__description">
          Berlin, Germany – January 9, 2020 – After releasing the multiplayer
          tower defense game Coregrounds in 2018, lead dev Mario "ehmprah"
          Kaiser went solo with a single-player spinoff which reinvents the
          tower defense genre yet again! CORE DEFENSE launches on January 16 on
          Itch.io and fuses tower defense with the best of roguelike and
          deckbuilding games into a simple, yet enticing and addictive formula –
          that will have players blissfully despair at its difficulty.
        </div>
      </div>

      <div class="text">
        <div class="text__description">
          "I wanted to make a game which gets you hooked easily but will take
          hundreds of hours to master and finally beat on the highest
          difficulty" – Mario "ehmprah" Kaiser
        </div>
      </div>

      <div class="text">
        <div class="text__description">
          After a public alpha during which the game was perfected in
          cooperation with the community, CORE DEFENSE will enter First Access
          on itch.io on January 16 before being released on Steam, the Play
          Store and the App Store later this year.
        </div>
      </div>

      <div class="section">
        <h2>Features</h2>
        <ul class="list">
          <li>Defeat fifty waves without losing your core</li>
          <li>
            Choose one out of several randomly rolled rewards after each wave
          </li>
          <li>
            Build a winning combination of walls, towers, abilities, upgrades
            and modules
          </li>
          <li>
            Enjoy infinite replayability through permadeath, randomized waves
            and rewards
          </li>
          <li>
            Play in short sessions of about an hour or binge for hours on end
          </li>
          <li>
            Beat a high base difficulty and many additional difficulty levels
          </li>
          <li>Unlock dozens of quirky achievements</li>
        </ul>
      </div>

      <div class="section">
        <h2>Links</h2>
        <ul class="list">
          <li>
            Itch.io:
            <a href="https://ehmprah.itch.io/core-defense"
              >https://ehmprah.itch.io/core-defense</a
            >
          </li>
          <li>
            Steam:
            <a href="https://store.steampowered.com/app/1203360/Core_Defense/"
              >https://store.steampowered.com/app/1203360/Core_Defense/</a
            >
          </li>
          <li>
            Game Trailer:
            <a href="https://www.youtube.com/watch?v=jB7aXX57a7I"
              >https://www.youtube.com/watch?v=jB7aXX57a7I</a
            >
          </li>
          <li>
            Presskit:
            <a href="https://coredefense.ehmprah.com/presskit/"
              >https://coredefense.ehmprah.com/presskit/</a
            >
          </li>
          <li>
            Game Website:
            <a href="https://coredefense.ehmprah.com/"
              >https://coredefense.ehmprah.com/</a
            >
          </li>
          <li>
            Discord Server:
            <a href="https://discord.gg/URcmzXm">https://discord.gg/URcmzXm</a>
          </li>
          <li>
            Twitter:
            <a href="https://twitter.com/ehmprah"
              >https://twitter.com/ehmprah</a
            >
          </li>
        </ul>
      </div>

      <div class="text">
        <h2>Contact</h2>
        <div class="text__description">
          Mario "ehmprah" Kaiser,
          <a href="mailto:ehmprah@gmail.com">ehmprah@gmail.com</a>
        </div>
      </div>

      <div class="footer">
        <Navigation />
      </div>
    </div>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue';

export default {
  components: {
    Navigation
  },
  head() {
    return {
      title:
        'Core Defense reinvents tower defense (again) and launches January 16'
    };
  }
};
</script>

<style lang="scss">
.title {
  margin-top: 2em;
  line-height: 1.5em;
}

.text {
  width: 80vw;
  max-width: 700px;
  margin: 0 auto 40px auto;
  &__description {
    text-align: left;
    margin: 1em 0;
  }
}

.section {
  max-width: 700px;
  margin: 40px auto;
}

.footer {
  margin: 4em 0 2em 0;
}
</style>
