<template>
  <div class="container">
    <div>
      <h1 class="title">PRESSKIT "Core Defense"</h1>

      <div class="text">
        <h2>Description</h2>
        <div class="text__description">
          Core defense is a roguelike tower defense game with a dash of
          deckbuilding. Survive fifty waves without losing your core. Choose a
          reward, update your build, survive the next wave, repeat. Highly
          replayable through permadeath, randomized waves and rewards and high
          difficulty.
        </div>
      </div>

      <div class="text">
        <h2>History</h2>
        <div class="text__description">
          Core Defense is a singleplayer spinoff from Coregrounds, a multiplayer
          tower defense game released in 2018, and shut down in early 2019 due
          to
          <a href="https://frgmnts.blog/f/how-not-to-make-a-game.html"
            >various reasons.</a
          >
          After the shutdown, lead developer Mario "ehmprah" Kaiser still had an
          itch that could only be scratched by reinventing the tower defense
          genre yet again, this time with solo project Core Defense.
        </div>
      </div>

      <div class="trailer">
        <h2>Videos</h2>
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
        <p><a href="/img/Core-Defense-Screenshots.zip">Download as .zip</a></p>
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

      <div class="screenshots screenshots--gif">
        <h2>GIFs</h2>
        <p><a href="/gifs/Core-Defense-GIFs.zip">Download as .zip</a></p>
        <div class="screenshots__container">
          <Screenshot url="/gifs/Core-Defense-1.gif" />
          <Screenshot url="/gifs/Core-Defense-2.gif" />
          <Screenshot url="/gifs/Core-Defense-3.gif" />
          <Screenshot url="/gifs/Core-Defense-4.gif" />
        </div>
      </div>

      <div class="logos">
        <h2>Logos</h2>
        <p><a href="/logo/Core-Defense-Logos.zip">Download as .zip</a></p>
        <div class="logos__container">
          <img class="logo" src="/logo/core.svg" />
          <img class="logo" src="/logo/core_defense_logo_final.svg" />
          <img class="logo" src="/logo/core_defense_logo_font_only.svg" />
        </div>
      </div>

      <div class="section">
        <h2>Quick Facts</h2>
        <ul class="list">
          <li>Developer: solo dev ehmprah, based in Berlin</li>
          <li>Platforms: Windows, Mac, Linux, Android, iOS</li>
          <li>Release: January 16, 2020 (First Access on Itch.io)</li>
          <li>Release on Steam, Play Store, App Store later in 2020</li>
        </ul>
      </div>

      <div class="section">
        <h2>Links</h2>
        <ul class="list-inline">
          <li>
            <a href="https://ehmprah.itch.io/core-defense">Itch.io</a>
          </li>
          <li>
            <a href="https://store.steampowered.com/app/1203360/Core_Defense/"
              >Steam</a
            >
          </li>
          <li>
            <a href="https://discord.gg/URcmzXm">Discord</a>
          </li>
          <li>
            <a href="https://twitter.com/ehmprah">Twitter</a>
          </li>
        </ul>
      </div>

      <div class="section">
        <h2>Mentions</h2>
        <p>
          "Addictive Tower Defense" – Calum Fraser,
          <a
            href="https://twitter.com/gameralphabeta/status/1208815708169224192"
            >AlphaBetaGamer</a
          >
        </p>
      </div>

      <div class="section">
        <h2>Press copy and other requests</h2>
        Send a mail to <a href="mailto:ehmprah@gmail.com">ehmprah@gmail.com</a>
      </div>

      <div class="section">
        <h2>Join ehmprah's newsletter</h2>
        <Subscription />
      </div>

      <div class="footer">
        <Navigation />
      </div>
    </div>
  </div>
</template>

<script>
import Screenshot from '~/components/Screenshot.vue';
import Subscription from '~/components/Subscription.vue';
import Navigation from '~/components/Navigation.vue';

export default {
  components: {
    Screenshot,
    Navigation,
    Subscription
  },
  head() {
    return {
      title: 'Presskit "Core Defense"'
    };
  }
};
</script>

<style lang="scss">
.title {
  margin-top: 2em;
  line-height: 1.5em;
  font-size: 2em;
}

.text {
  width: 80vw;
  max-width: 640px;
  margin: 0 auto 80px auto;
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
  &--gif {
    .screenshot {
      flex: 1 0 200px;
      height: 112px;
      overflow: hidden;
    }
  }
}

.logos {
  &__container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    .logo {
      flex: 0 0 150px;
      margin: 1em;
      height: auto;
    }
  }
}

.section {
  max-width: 600px;
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
