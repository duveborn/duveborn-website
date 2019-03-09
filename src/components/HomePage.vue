<template>
  <main class="m-2">

    <div class="flex flex-wrap">

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Oskar Duveborn</h1>
          <p>
            Technology & Events
          </p>   
        <img src="/images/oskar.jpg" class="rounded-full p-5" />
        </header>
        <p>
          I'm a developer, prototyper and designer with multiple non-profit organization member and board seats who likes to execute impeccably entertaining technology events.
        </p>   
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>FlowersFX</h1>
          <p>
            Creator & Founder
        </p>
        <img src="/images/flowersfx.png" class="rounded-lg mb-5 mt-5" />
        </header>
        <p>
          FlowersFX rose out of the 1998 class of Virtual Reality at Nackadmin and is about creative arts, the demoscene, computer graphics, games and my closest friends. 
          </p>
          <p>
            We're poly-skilled individuals covering various fields like 3D graphics, 2D graphics, software development, video editing, video production, live event broadcasts, event recordings, event organizing, vj:ing, dj:ing and special effects.
        </p>
        <p class="text-xl">
          <a href="http://www.flowersfx.com" target="blank">flowersfx.com</a>
        </p>          
      </section>   

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Syntax Error</h1>
          <p>
            Organizer, DJ & Treasurer
          </p>
        <img src="/images/syntaxerror.jpg" class="rounded-lg mb-5 mt-5" />
        </header>
        <p>
          This non-profit organisation promotes the video game (and demoscene, internet fan culture) music scene in Stockholm and organizes multiple events including a monthly and successful night club called Syntax Error, which was in early 2016 featured shortly in a 2 hour Swedish television special about video game music called Blip-Blop in Kulturmagasinet.
        </p>
        <p>
          So far I've had the chance to learn several new disciplines at this organisation like becoming a great VJ artist, designing and executing light shows, being a promoter and there will be more to come.
        </p>
        <p class="text-xl">
          <a href="https://syntax-error.se" target="blank">syntax-error.se</a>
        </p>  
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Mandagsklubben.net</h1>
          <p>
            Organizer & Founder
          </p>
        </header>
        <p>
          Måndagsklubben is a loosely defined gathering of random people in the IT-industry in Stockholm every Monday at a pub, where any interesting activity is always allowed and often planned for like board games, beta-testing of indie games by developers visiting, screening of the latest demoscene results and much more. Or simply a few beverages with your friends.
        </p>
        <p>
          It was founded roughly five years ago by me and a games programmer at King and was hosted at KGB Bar for its first four years before they shut down and can now be found every Monday 17-23 at Wokhouse on Regeringsgatan. Drop by and say hi.
        </p>
        <p class="text-xl">
          <a href="https://mandagsklubben.net" target="blank">mandagsklubben.net</a>
        </p>  
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Edison</h1>
          <p>
            Organizer & Chairman
          </p>
        </header>
        <p>
          This non-profit organisation promotes the demoscene in Stockholm mainly by organizing the biggest multiplatform demoparty in Sweden every summer since 2011 called Edison - drawing 150 or more extremely talented programmers, music and graphics artists to compete.
        </p>
        <p class="text-xl">
          <a href="https://edisonparty.com" target="blank">edisonparty.com</a>
        </p>  
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>SEC-T</h1>
          <p>
            Club Manager
          </p>
        </header>
        <p>
          I've been organizing the somewhat amazing CLUB SEC-T party for a couple of years in Stockholm and now I'm formally part of the conference crew, heading that area of the conference full-on.
        </p>
        <p class="text-xl">
          <a href="https://sec-t.org" target="blank">sec-t.org</a>
        </p>  
      </section>        
     
      <section id="effect" class="m-5 flex-1 max-width-960 min-width-280">
      </section>        
      <section class="m-5 flex-1 max-width-960 min-width-280">
      </section>        
      <section class="m-5 flex-1 max-width-960 min-width-280">
      </section>        

    </div>

    <div class="w-full text-center mb-20">
        <header>
          <h1>Contact me</h1>
          <p>
            I once got caught monowheeling in a skirt
          </p>          
        <img src="/images/monowheel.jpg" class="rounded-lg mb-5 mt-5" />
        </header>
          <p class="text-xl text-link">
            <a href="https://twitter.com/oskarduveborn" target="blank">E-mail</a> ▬
            <a href="https://www.linkedin.com/in/oskarduveborn/" target="blank">LinkedIn</a> ▬
            <a href="https://github.com/duveborn" target="blank">Github</a> ▬
            <a href="https://www.facebook.com/oskarduveborn" target="blank">Facebook</a> ▬
            <a href="https://www.instagram.com/oskarduveborn/" target="blank">Instagram</a> ▬
            <a href="https://twitter.com/oskarduveborn" target="blank">Twitter</a>
          </p>  
    </div>

  </main>
</template>

<script>
export default {
  name: 'HomePage',
  components: {
  }
}
</script>

<style scoped>
img {
  filter: grayscale(100%);
  transition: filter 1s;
}
img:hover {
  filter: grayscale(0);
}
img.nofilter {
  filter: grayscale(0);
}
.min-width-280 {
  min-width: 280px;
}
.max-width-960 {
  max-width: 960px;
}
.no-bullet {
  list-style-type: none;
}
</style>
