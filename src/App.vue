<template>
  <div id="app">

    <header>
  <h1 class="wedlogo">
    <img src="../image/awayddings-logo.png" class="wedlog" alt="Awayddings Logo" />
  </h1>

  <div class="hamburger" @click="toggleMenu">
    <span></span>
    <span></span>
    <span></span>
  </div>

  <nav :class="{ 'is-active': menuOpen }">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Destinations</a></li>
      <li><a href="#">Plan My Wedding</a></li>
      <li><a href="#">About Us</a></li>
      <li><a href="#">Contact</a></li>
      <li><a href="#">Register</a></li>
      <li><a href="#">Sign In</a></li>
    </ul>
  </nav>
</header>

    <main>
      <section class="img">
        <div class="img-image">
          <img src="" alt="Wedding on a Beach" width="1200" height="800" />
        </div>

      </section>

      <section class="content">
        <div class="account">
          <p class="icon_logo">
            <Icon icon="mdi:account" />
            BY KESARI AWAYDDINGS
          </p>
          <p class="icon_logo">
            <Icon icon="mdi:calendar" />
            24 JUN 2022
          </p>
        </div>

        <h2>Destination Weddings in Goa - Expectations vs. Reality</h2>
        <p>
          Goa is not only a haven for beach lovers but also has a magical romantic aesthetic to it.
          Scenic natural beauty, vibrant nightlife, secluded beaches - perfect for moments
          <br> that make your heart beat.
        </p>
        <p>If there is one destination would-be-married couples
          all around the country would like to exchange vows on, it's Goa!</p>

        <p>Destination weddings in Goa are perennially popular, but planning one can be really stressful and
          challenging. We are all still torn between what we really expect and what’s the reality of things. The
          couple's goal is always to find a balance between beauty, service, comfort, and of course the budget!</p>

        <p>Now, if you are not from Goa you must wonder, ‘how exactly do I plan on getting married at this
          destination?’, we at Kesari Awayddings aim to set your expectations right! So that nothing can take the shine
          away from the perfect intimate wedding of your dreams!</p>
        <P>If you are planning a destination wedding in Goa, don't expect it to be like a regular wedding. You will find
          that there are some things that are completely
          different, and you will have to adapt to them! But not everything is bad</P>


        <h4>Expectation: People of Goa are non-helpful<br>
          Reality: Goans are very warm! </h4>

        <p>The first thing that you should know is that the Goan people are very welcoming, friendly, and warm-hearted.
          They love to welcome guests with open arms,
          which make your stay more comfortable and fun.</p>
        <p>In fact, they love meeting guests of other cultures as well. This means that they will do everything possible
          to make sure that your stay is enjoyable and memorable!</p>

        <h4>Expectation: destination wedding in Goa will cost us a bomb! including stay.<br>
          Reality: Plan your wedding much prior to find out the best options including stay on
          <a href="https://www.awayddings.com/" style="text-decoration: none;"> Kesari Awayddings</a>
          <p>This is one of the biggest pain points of every couple - what if we told you, your bright sunset filled
            destination wedding in Goa will be handled within your budget?</p>
        </h4>

        <p>Get the best Wedding Packages, Venue Details and Prices for Top Wedding Locations in Goa, all you’ve to do is
          focus on your ‘I do’s’</p>
        <h4>Expectation: What is there to eat for vegetarians? it's only seafood<br>
          Reality: Goa, just like any other state has its own staple to enjoy and variety to offer!
        </h4>
        <p>Who says it's only seafood and non-veg? Goa may be a carnivore’s paradise but on the flip-side there are
          plenty of options for the mindful eaters coming to its shores.
        </p>
        <p>A destination wedding in Goa covers all bases for vegan couples from regional to international cuisines.</p>

        <p>Locals grow a lot of fresh produce and there is a lot to explore for vegetarians.</p>

      </section>
    </main>


    <footer class="footerr">
      <div class="footer-content">
        <div class="footerr-left">
          <h2>KESARI Awayddings</h2>
          <p>
            Welcome to Kesari Awayddings, your number one source for a memorable destination wedding. We are dedicated
            to assist you in booking a wedding venue at your dream destination along with wedding planning services.
          </p>
          <div class="social-icons">
            <a href="#">
              <Icon icon="mdi:facebook" class="footer-icons" />
            </a>
            <a href="#">
              <Icon icon="mdi:linkedin" class="footer-icons" />
            </a>
            <a href="#">
              <Icon icon="mdi:instagram" class="footer-icons" />
            </a>
          </div>
          <p class="footer-links">
            <a href="#">Terms & Conditions</a> |
            <a href="#">Refund Policy</a> |
            <a href="#">Privacy Policy</a>
          </p>
        </div>
        <div class="footer-right">
          <h2>Contact</h2>
          <p>
            <Icon icon="mdi:map-marker" />
            Kesari Awayddings Private Limited (Formerly <br>
            A2WEDTECH PRIVATE LIMITED)
            Plot No. 265/2,<br> Baner Road,
            Near Aromas Cafe & Bistro,
            Opp Mauli <br> Petrol Pump,
            Varsha Park Society, Pashan,
            Pune,<br> Maharashtra 411045
          </p>
          <p>
            <Icon icon="mdi:map-marker" /> Goa Address: Kesari Awayddings Private Limited (Formerly A2WEDTECH PRIVATE
            LIMITED), Rosary Apartments, Shop No-11, Miramar, Goa-403001, 3rd Floor, Shanta Building, 201, 301, 91
            Springboard, 18th June Rd, opposite Broadway Book Center, St. Inez, Santa Inez, Panaji, Goa 403001
          </p>
          <p>Phone: +91 9370 157 830</p>
          <p>Email: hello.kesari@awayddings.com</p>
        </div>
      </div>
    </footer>
    <footer class="footer">
      <p>&copy; 2022 by Awayddings.</p>
    </footer>


    <a href="https://wa.me/your-number" class="whatsapp-button" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" />
    </a>
  </div>
</template>

<script>
import { Icon } from '@iconify/vue';
export default {
  name: "App",
  components: {
    Icon,
  },
  data() {
    return {
      menuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    },
  },
};
</script>

<style>
#app {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  background-color: #fff;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}

.wedlogo {
  margin: 0;
  display: flex;
  align-items: center;
}

.wedlog {
  max-height: 60px;
}

nav ul {
  display: flex;
  list-style-type: none;
  padding: 0;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: red;
}

nav {
  display: flex;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}


.hamburger {
  display: none;
  flex-direction: column;
  cursor: pointer;
  gap: 5px;
}

.hamburger span {
  width: 30px;
  height: 3px;
  background-color: #333;
}


@media (max-width: 768px) {
  nav {
    display: none;
  }

  nav.is-active {
    display: block;
    position: absolute;
    background-color: #fff;
    top: 60px;
    left: 0;
    width: 100%;
  }

  nav ul {
    flex-direction: column;
    align-items: center;
    gap: 10px;
    margin: 0;
    padding: 0;
  }

  .hamburger {
    display: flex;
  }
}

.img {
  position: relative;
  height: 60vh;
  background-color: #e3e3e3;
}



.content {
  padding: 40px;
  flex-direction: '';
}

.account {
  display: flex;
  position: relative;
  justify-content: flex-start;
  align-items: center;
  gap: 20px;
  padding: 10px 0;
  font-size: 1rem;
  color: #666;
  font-style: italic;
}

.icon_logo {
  margin-right: 5px;
}

.account p {
  margin: 0;
}


.content h2 {
  color: #333;
  font-size: 2rem;
}

.content h3 {
  color: gray;
  font-size: 1.5rem;
}

.content p {
  color: #666;
  line-height: 1.6;
  margin: 20px 0;
}

footer {
  background-color: #333;
  color: white;
  padding: 10px;
  text-align: center;
}

.whatsapp-button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #25D366;
  border-radius: 50%;
  padding: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  z-index: 1000;
}

.whatsapp-button img {
  width: 50px;
  height: 50px;
}

@media (max-width: 1024px) {
  header {
    flex-direction: column;
    align-items: flex-start;
  }

  nav ul {
    flex-direction: row;
    flex-wrap: wrap;
    margin-top: 10px;
  }

  nav ul li {
    margin: 5px 10px;
  }

  .img {
    height: 50vh;
  }

  .content {
    padding: 30px;
  }

  .content h2 {
    font-size: 1.75rem;
  }

  .content h3 {
    font-size: 1.75rem;
  }
}

.footerr {
  background-color: #2c2c3a;
  color: #fff;
  padding: 30px;
  text-align: center;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 30px;
}

.footerr-left,
.footer-right {
  max-width: 45%;
}

.footerr-left h2,
.footer-right h2 {
  font-size: 1.5rem;
  margin-bottom: 20px;
}

.footerr-left p,
.footer-right p {
  font-size: 1rem;
  line-height: 1.6;
}

.social-icons a {
  margin: 0 10px;
  display: inline-block;
}

.footer-links {
  margin-top: 10px;
}

.footer-links a {
  color: #fff;
  text-decoration: none;
}

.footer-links a:hover {
  color: #f06c00;
}

@media (max-width: 768px) {
  .footer-content {
    flex-direction: column;
    text-align: left;
  }

  .footer-left,
  .footer-right {
    max-width: 100%;
  }
}


@media (max-width: 768px) {
  header {
    flex-direction: column;
  }

  nav ul {
    flex-direction: column;
    margin-top: 10px;
  }

  nav ul li {
    margin: 10px 0;
  }

  .img {
    height: 40vh;
  }

  .content {
    padding: 20px;
  }

  .content h2 {
    font-size: 1.5rem;
  }
}

@media (max-width: 480px) {
  .img {
    height: 30vh;
  }

  .content h2 {
    font-size: 1.25rem;
  }

  .content h3 {
    font-size: 1.75rem;
  }

  .content p {
    font-size: 0.9rem;
  }

  nav ul li {
    margin: 5px 0;
  }
}


.footer-icons {
  color: white;
  width: 30px;
  height: 30px;
}
</style>
