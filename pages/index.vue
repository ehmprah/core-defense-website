<template>
  <div class="container">
    <div>
      <img class="logo" src="/logo.svg" alt="Core Defense Logo" />

      <div class="about">
        <div class="about__short">A roguelike tower defense game.</div>
        <div class="about__description">
          Defeat fifty waves without losing your core. Choose a reward after
          each wave and build a winning combination of walls, towers, abilities,
          upgrades and modules. Highly replayable through permadeath, randomized
          waves and rewards and a high difficulty.
        </div>
        <Follow />
      </div>

      <div class="trailer">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/jB7aXX57a7I"
          frameborder="0"
          allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>

      <div class="screenshots">
        <h2>Screenshots</h2>
        <div class="screenshots__container">
          <Screenshot url="/img/screenshot_low_core.png" />
          <Screenshot url="/img/screenshot_rewards.png" />
          <Screenshot url="/img/screenshot_reward_detail.png" />
          <Screenshot url="/img/screenshot_tower_detail.png" />
          <Screenshot url="/img/screenshot_aoe.png" />
          <Screenshot url="/img/screenshot_final_wave.png" />
          <Screenshot url="/img/screenshot_flawless_bonus.png" />
          <Screenshot url="/img/screenshot_sawblades.png" />
        </div>
      </div>

      <div class="section">
        <h2>Quick Facts</h2>
        <ul class="list">
          <li>Public alpha is coming early 2020</li>
          <li>Coming for PC, Mac, Linux</li>
          <li>
            Developed by solo dev
            <a href="https://twitter.com/ehmprah">ehmprah</a>
          </li>
          <li>
            Singleplayer spinoff from
            <a href="https://frgmnts.blog/f/how-not-to-make-a-game.html"
              >Coregrounds</a
            >
          </li>
        </ul>
      </div>

      <div class="section">
        <h2>Follow</h2>
        <Follow />
      </div>

      <div class="section">
        <h2>Newsletter</h2>
        <Subscription />
      </div>

      <div class="footer">
        <a href="/imprint">Imprint</a>
      </div>
    </div>
  </div>
</template>

<script>
import Follow from '~/components/Follow.vue';
import Screenshot from '~/components/Screenshot.vue';
import Subscription from '~/components/Subscription.vue';

export default {
  components: {
    Follow,
    Screenshot,
    Subscription
  },
  head() {
    return {
      title: 'Core Defense'
    };
  }
};
</script>

<style lang="scss">
.logo {
  max-width: 280px;
  margin-top: 40px;
}

.about {
  width: 80vw;
  max-width: 480px;
  margin: 0 auto 80px auto;

  &__short {
    font-size: 1.25em;
  }

  &__description {
    text-align: left;
    margin: 1em 0;
  }
}

.screenshots {
  max-width: 960px;
  margin: 80px auto;
  &__container {
    display: flex;
    flex-wrap: wrap;
    .screenshot {
      flex: 1 0 200px;
    }
  }
}

.section {
  max-width: 400px;
  margin: 80px auto;
}

.newsletter {
  margin: 80px auto;
  &__info {
    font-size: 0.8em;
    color: #aaa;
  }
}

.footer {
  margin: 4em 0 2em 0;
}
</style>
