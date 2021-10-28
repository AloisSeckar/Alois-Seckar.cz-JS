<template>
    <div id="profile">
        <img id="photo" src="~/assets/profile.webp">
        <h1>Alois Sečkár</h1>
        <h2>Programátor / Běžec / Politik</h2>
        <div>
            <a href="mailto:seckar@svobodni.cz"><img class="contact" src="~/assets/fa-envelope.webp"></a>
            <a href="https://www.facebook.com/alois.seckar"><img class="contact" src="~/assets/fa-facebook.webp"></a>
            <a href="https://www.instagram.com/alois.seckar/"><img class="contact" src="~/assets/fa-instagram.webp"></a>
            <a href="https://twitter.com/AloisSeckar"><img class="contact" src="~/assets/fa-twitter.webp"></a>
            <a href="https://www.linkedin.com/in/alois-seckar"><img class="contact" src="~/assets/fa-linkedin.webp"></a>
        </div>
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

  h1 {
    font-family: kaushanScript;
    font-size: 4rem;
    font-weight: 100;
    transform: rotate(-5deg);
  }
  h2 {
    font-family: 'Courier New', monospace;
    font-size: 1.2rem;
    font-weight: 85;
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