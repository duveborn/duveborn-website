<template>
  <main class="m-2">

    <div class="flex flex-wrap">

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Oskar Duveborn</h1>
          <img src="/images/oskar.jpg" class="rounded-full p-5" />
          <p>
            Tech, Design & Events
          </p>   
        </header>
        <p>
          I'm a developer, prototyper and designer at Valtech. 
        </p>   
        <p>
          I like to execute impeccably entertaining tech events, solve problems and build custom experiences. 

            I also volunteer for multiple non-profits mainly within arts & tech culture where I can apply my interest for people and technology.
            </p>
        <p class="text-xl">
          <a href="https://www.linkedin.com/in/duveborn/" target="blank">linkedin.com</a>
        </p>              
      </section>   

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Syntax Error Stockholm</h1>
          <img src="/images/syntaxerror.jpg" class="rounded-lg mb-5 mt-5" />
          <p>
            Organizer, DJ & Treasurer
          </p>
        </header>
        <p>
          This non-profit organisation promotes the video game (and demoscene, internet fan culture) music scene in Stockholm and organizes multiple events including a monthly and successful night club called Syntax Error, which was in early 2016 featured shortly in a 2 hour Swedish television special about video game music called Blip-Blop in Kulturmagasinet.
        </p>
        <p>
          So far I've had the chance to learn several new disciplines at this organisation like becoming a VJ artist, designing, programming and executing light shows, being a promoter and lots more.
        </p>
        <p class="text-xl">
          <a href="https://syntax-error.se" target="blank">syntax-error.se</a>
        </p>  
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Edison Demoparty</h1>
          <img src="/images/edison.jpg" class="rounded-lg mb-5 mt-5" />
          <p>
            Organizer & Chairman
          </p>
        </header>
        <p>
          This non-profit organisation promotes the demoscene in Stockholm mainly by organizing the biggest multiplatform demoparty in Sweden every summer since 2011 called Edison - drawing 150 or more extremely talented programmers, music and graphics artists to compete.
        </p>
        <p>
          Organizing such a large event, content-wise, takes the best part of half a year of spare time and seeing all the logistics and people come together to an amazing experience is worth every drop of blood, sweat and tears.
          </p>
        <p class="text-xl">
          <a href="https://edisonparty.com" target="blank">edisonparty.com</a>
        </p>  
      </section>  

    </div>

    <div class="flex flex-wrap">

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>Mandagsklubben.net AW</h1>
          <img src="/images/mandagsklubben.jpg" class="rounded-lg mb-5 mt-5" />
          <p>
            Organizer & Founder
          </p>
        </header>
        <p>
          Måndagsklubben is a loosely defined gathering of random people in the IT-industry in Stockholm every Monday at a pub, where any interesting activity is always allowed and often planned for like board games, beta-testing of indie games by developers visiting, screening of the latest demoscene results and much more. Or simply a few beverages with your friends.
        </p>
        <p>
          It was founded roughly nine years ago by me and a games programmer at King and was hosted at KGB Bar for its first four years before they shut down, followed by four years at Wokhouse on Regeringsgatan before Mondays became too popular and can now be found every Monday 17-01 downstairs at Medeltidskrogen Sjätte Tunnan in Gamla Stan. Drop by and say hi.
        </p>
        <p class="text-xl">
          <a href="https://mandagsklubben.net" target="blank">mandagsklubben.net</a>
        </p>  
      </section>  

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>SEC-T Security Conference</h1>
          <img src="/images/quiz-crowd.jpg" class="rounded-lg mb-5 mt-5" />
          <p>
            Club Manager
          </p>
        </header>
        <p>
          I've been organizing the CLUB SEC-T party for a couple of years in Stockholm and now I'm formally part of the conference crew, heading that area of the conference full-on.
        </p>
        <p>
          Other security conferences and companies has since hired me to help out with their events as well, like Security Fest Gothenborg and Detectify.
        </p>
        <p class="text-xl">
          <a href="https://sec-t.org" target="blank">sec-t.org</a>
        </p>  
      </section>        

      <section class="m-5 flex-1 max-width-960 min-width-280">
        <header>
          <h1>FlowersFX</h1>
          <img src="/images/led-screen.jpg" class="rounded-lg mb-5 mt-5" />
          <p>
            Creator & Founder
        </p>
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

    </div>

    <div class="w-full text-center mb-20">
        <header>
          <h1>Contact me</h1>
          <img src="/images/monowheel.jpg" class="rounded-lg mb-5 mt-5" />
          <p class="text-sm -mt-4 mb-3">
            I once got caught monowheeling in a skirt
          </p>          
        </header>
          <p class="text-xl text-link mx-4">
            <a href="https://www.linkedin.com/in/oskarduveborn/" target="blank">LinkedIn</a><br />
            <a href="https://github.com/duveborn" target="blank">Github</a><br />
            <a href="https://www.facebook.com/oskarduveborn" target="blank">Facebook</a><br />
            <a href="https://www.instagram.com/oskarduveborn/" target="blank">Instagram</a><br />
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
main {
  max-width: 1600px;
  margin: auto;
}
img {
  object-fit: cover;
  height: 280px;
}
img.rounded-full {
  height: 380px;
  margin: auto;
  display: block;
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
