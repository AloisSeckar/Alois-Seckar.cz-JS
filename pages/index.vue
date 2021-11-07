<template>
    <div id="profile">
        <img id="photo" src="~/assets/profile.webp">
        <h1 id="name" class="borderless">Alois Sečkár</h1>
        <h2 id="desc" class="borderless">
          <nuxt-link to="/programovani" title="Programování">Programátor</nuxt-link> / 
          <nuxt-link to="/sport" title="Sport">Sportovec</nuxt-link> / 
          <nuxt-link to="/politika" title="Politika">Politik</nuxt-link>
        </h2>
        <div id="other"><nuxt-link to="/other" title="Ostatní">...a pár dalších věcí</nuxt-link></div>
        <div>
            <a href="mailto:seckar@svobodni.cz" title="Email"><img class="contact" src="~/assets/fa-envelope.webp"></a>
            <a href="https://www.facebook.com/alois.seckar" title="Facebook"><img class="contact" src="~/assets/fa-facebook.webp"></a>
            <a href="https://www.instagram.com/alois.seckar/" title="Instagram"><img class="contact" src="~/assets/fa-instagram.webp"></a>
            <a href="https://twitter.com/AloisSeckar" title="Twitter"><img class="contact" src="~/assets/fa-twitter.webp"></a>
            <a href="https://www.linkedin.com/in/alois-seckar" title="LinkedIn"><img class="contact" src="~/assets/fa-linkedin.webp"></a>
        </div>
        <page-footer />
    </div>
</template>

<style>

  #profile {
      margin: 4rem auto 0;
      width: 50%;
      text-align: center;
  }

  #photo {
    width: 12rem;
    border-radius: 50%;
  }

  img.contact {
    width: 2rem;
    border-radius: 50%;
    border: 1px solid white;
    margin: 0.4rem;
    padding: 0.4rem;
  }

  #name {
    color: white;
    font-family: kaushanScript;
    font-size: 4rem;
    font-weight: normal;
    transform: rotate(-5deg);
  }
  #desc {
    color: white;
    font-family: 'Courier New', monospace;
    font-size: 1.5rem;
    font-weight: normal;
  }
  #other {
    font-family: 'Courier New', monospace;
    margin-bottom: 2rem;
  }

  @media only screen and (max-width: 400px) {
    #photo {
      width: 10rem;
    }
    h1 {
      font-size: 3rem;
    }
  }

  @media only screen and (max-width: 300px) {
    #photo {
      width: 8rem;
    }
    h1 {
      font-size: 2.5rem;
    }
    h2 {
      font-size: 0.9rem;
    }
  }

</style>