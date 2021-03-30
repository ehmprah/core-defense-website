<template>
  <div class="container">
    <div>
      <img class="logo" src="/logo.svg" alt="Core Defense Logo" />

      <div class="about">
        <div class="about__short">A roguelike tower defense game.</div>
        <div class="about__description">
          A roguelike tower defense game with a dash of deckbuilding. Choose a
          reward, improve your build, survive the next wave, repeat. Highly
          replayable, difficult, and addictive. You'll want just one more wave,
          just one more run!
        </div>
      </div>

      <Buy />

      <div class="trailer">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/47SFM1lvpq4"
          frameborder="0"
          allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>

      <div class="screenshots">
        <h2>Screenshots</h2>
        <div class="screenshots__container">
          <Screenshot url="/img/Core-Defense-Screenshot-1.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-2.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-3.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-4.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-5.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-6.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-7.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-8.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-9.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-10.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-11.png" />
          <Screenshot url="/img/Core-Defense-Screenshot-12.png" />
        </div>
      </div>

      <div class="section">
        <h2>Follow</h2>
        <Follow />
      </div>

      <div class="section">
        <h2>Quick Facts</h2>
        <QuickFacts />
      </div>

      <div class="section">
        <h2>Newsletter</h2>
        <Subscription />
      </div>

      <div class="footer">
        <Navigation />
      </div>
    </div>
  </div>
</template>

<script>
import Buy from '~/components/Buy.vue';
import Follow from '~/components/Follow.vue';
import Navigation from '~/components/Navigation.vue';
import QuickFacts from '~/components/QuickFacts.vue';
import Screenshot from '~/components/Screenshot.vue';
import Subscription from '~/components/Subscription.vue';

export default {
  components: {
    Buy,
    Follow,
    Navigation,
    QuickFacts,
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
  max-width: 520px;
  margin: 0 auto 40px auto;

  &__short {
    font-size: 1.25em;
  }

  &__description {
    text-align: justify;
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
  max-width: 640px;
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
