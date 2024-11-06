<script setup>
// import Modal from './ContactModal.vue'

// const modalVisible = ref(false)
import { defineComponent } from 'vue'
import { CCard, CCardImage, CCardBody, CCardText } from '@coreui/vue'

defineComponent({
  components: {
    CCard,
    CCardImage,
    CCardBody,
    CCardText
  }
})

</script>

<template>
  <div class="frame-1">
    <img alt="Cover image" class="cover" src="/images/cover-image.png" width="100%" height="100%" />
    <div class="text-1">
      <h1 class="services">Services</h1>
      <div class="contact">
            <button @click="openModal">Book an appointment</button>
            <!-- <Modal v-model="modalVisible">
              <h2>This is the modal content</h2>
              <p>You can add any content here.</p>
            </Modal> -->
       </div>
    </div>
  </div>
  <h1 class="text-cards">Comprehensive Marketing Plan</h1>
  <div class="cards-container">
    <div class="card-1">
      <CCard style="width: 13rem">
        <CCardImage orientation="top" src="/images/responsive.png" style="width: 120px; display: block; margin-left: auto; margin-right: auto;" />
        <CCardBody>
          <CCardText class="custom-font">Responsive</CCardText>
        </CCardBody>
      </CCard>
      </div>

      <div class="card-2">
        <CCard style="width: 13rem">
              <CCardImage orientation="top" src="/images/syndication.png" style="width: 120px; display: block; margin-left: auto; margin-right: auto;" />
              <CCardBody>
                <CCardText class="custom-font">Syndication</CCardText>
              </CCardBody>
            </CCard>
      </div>

      <div class="card-3">
        <CCard style="width: 13rem">
        <CCardImage orientation="top" src="/images/virtual.png" style="width: 120px; display: block; margin-left: auto; margin-right: auto;" />
        <CCardBody>
          <CCardText class="custom-font">Virtual Tour</CCardText>
        </CCardBody>
      </CCard>
      </div>

    <div class="card-4">
      <CCard style="width: 13rem">
        <CCardImage orientation="top" src="/images/photography.png" style="width: 120px; display: block; margin-left: auto; margin-right: auto;" />
        <CCardBody>
          <CCardText class="custom-font">Photography</CCardText>
        </CCardBody>
      </CCard>
    </div>
</div>

  <div class="frame-2">
    <div class="group-1">
      <h2 class="frame-text-1">Decor Guidance</h2>
      <img alt="First image" class="decor" src="/images/decor.jpg" width="50%" height="100%" />
    </div>

    <div class="group-2">
      <h2 class="frame-text-2">Intentional Layout</h2>
      <img alt="Second image" class="layout" src="/images/layout.jpg" width="50%" height="100%" />
    </div>
  </div>

  <div class="frame-3">
    <h2 class="expertise">My Staging Expertise</h2>
      <div class="list">
        <li>Unclutter and organize your home</li>
        <li>Neatly arrange drawers and cabinets</li>
        <li>Keep pets outdoors or off the premises</li>
        <li>Play soft music</li>
      </div>
  </div>

  <div class="frame-4">
    <h1 class="selling">The Selling Process</h1>
      <div class="process">
        <p class="process-1">Initial consultation & Planning</p>
        <p class="process-2">Devise & Execute marketing plan</p>
        <p class="process-3">Review offers & Agreement with buyer</p>
        <p class="process-4">Complete transaction process</p>
        <p class="process-5">After-sale service</p>
      </div>

      <h1 class="buying">The Buying Process</h1>
      <div class="second-process">
        <p class="pr-1">Initial consultation & Planning</p>
        <p class="pr-2">Search for a home & Get pre-approved</p>
        <p class="pr-3">Submit an offer</p>
        <p class="pr-4">Complete settlement process</p>
      </div>
  </div>

  <div class="frame-5">
    <img alt="Cover image" class="cover-2" src="/images/marketing.jpg" width="100%" height="100%" />
      <div class="description-1">
        <p class="desc-1">We combine data gained from your home’s Comparative Market Analysis with local market research to create a marketing plan 
          designed to help you meet your selling goals. Your home’s carefully designed plan will include a range of online, print, and other marketing 
          tools targeted to the best-qualified pool of buyers. ​​​​​​​ Successfully marketing a home in today’s real estate environment requires a firm with 
          experience and flexibility. Hansen Partners provides both.</p>
      </div>

      <img alt="Cover image" class="cover-3" src="/images/success.jpg" width="100%" height="100%" />
      <div class="description-2">
        <p class="desc-2">We provide every one of our clients with a level of service they won’t find anywhere else. We give them what they need, often 
          before they know they need it. ​​​​​​​In real estate, almost everything can be negotiated. When you choose Hansen Partners It is experience is 100% 
          nonnegotiable. ​​​​​​​ ​​​​​​​And it’s an experience like no other..</p>
      </div>

      <img alt="Cover image" class="cover-4" src="/images/tablet.jpg" width="100%" height="100%" />
      <div class="description-3">
        <p class="desc-3">We have created this as a wonderful tool so that we can communicate with you daily, provide you with updates on what is happening 
          with your home. We are available at the with a click of your tablet.</p>
      </div>
  </div>

  <div class="benefit">
    <h2 class="b-title">Benefits:</h2>
    <div class="b-list">
      <li class="b-lists">Review all documents and sign in the comfort of your home or anywhere.</li>
      <li class="b-lists">Stay up to date on all marketing activities, review materials, photos, etc. in real time</li>
      <li class="b-lists">Meet with us face to face on our Gotomeeting.com platform to go over and discuss the events of the week.</li>
      <li class="b-lists">You have your own email assigned just for you and your common space to quickly write a note, or quickly send a 
        video message to us for fast communication using our Bomb bomb video messaging system.</li>
    </div>

    <p class="b-desc">
      We believe that transparency and guiding you and your family through the process is key to having the best experience. 
       During these uncertain times. It is a good feeling to know you have some one with a proven track record you can count on.  
      We will be here to handle your needs during the Real Estate process.  We think of it before a need even arises. Because, that is
       just what we do.  Who you work with does matter! 
    </p>
      
  </div>

  <div class="strat">
    <h2 class="strat-title">We Market Your Home to the World</h2>
    <p class="strat-subtitgle">Our Online Marketing Strategy</p>
    <p class="strat-desc">​​​​​​​The Bay Area remains one of the world's most 
      sought-after regions to live in, and when looking to sell, it is vital that your home be 
      marketed online to audiences locally, nationally, and internationally.</p>

    <div class="strat-container">
      <div class="s-container1">
        <h3 class="s-container-title">Local Exposure</h3>
        <p class="s-container-desc">Through our partnership with Nextdoor, the private online social network now used in over 80% of U.S. 
          neighborhoods and virtually all Bay Area neighborhoods, we make sure your home receives targeted local exposure. When you list your 
          home with Hansen Partners it will automatically appear on Nextdoor in your neighborhood.</p>
      </div>
      <div class="s-container2">
        <h3 class="s-container-title">National Exposure</h3>
        <p class="s-container-desc">We secure strategic positioning and enhancement on Realtor.com, Trulia, and Zillow, driving more consumers to your home and 
          increasing exposure. We  will receive every inquiry about your property directly.</p>
      </div>
      <div class="s-container3">
        <h3 class="s-container-title">International Exposure</h3>
        <p class="s-container-desc">To expose your luxury listing to millions of potential homebuyers worldwide, we promote on prominent international real estate 
          portals, including: Wall Street Journal, LuxuryPortfolio.com, LuxuryRealEstate.com, LeadingRE.com, UniqueHomes.com, China.apr.com, Caimeiju, Juwai, Country Life UK</p>
      </div>
    </div>
  </div>

  <div class="frame-6">
    <h2 class="partners">Our Partners in Luxury</h2>
    <p class="partners-desc">We're Global</p>
        <div class="partner-container">
            <img src="/images/partner-1.jpg" alt="Image 1" width="10%">
            <img src="/images/partner-2.jpg" alt="Image 2" width="10%">
            <img src="/images/partner-3.jpg" alt="Image 3" width="10%">
    </div>

        <div class="partners-logo-desc">
          <p class="partner-desc2">Leading Real Estate Companies of The World® & Luxury Portfolio International</p>
          <p class="partner-desc3">JRockcliff is a founding member of Luxury Portfolio International®, the luxury division 
          of Leading Real Estate Companies of the World®. With more than 500 member firms around the world, Our luxury listings 
          are exposed to a vast global audience and reach potential buyers and investors in over 50 countries.</p>
        </div>
  </div>

  <div class="frame-7">
    <h2 class="luxury">Who's Who in Luxury Real Estate</h2>
      <div class="lux-paragraph">
        <p class="lux-desc1">Who’s Who in Luxury Real Estate is a global collection of luxury real estate brokers.</p>
        <p class="lux-desc2">Through our international affiliations, we have a strong presence in over 50 countries. 
          Our luxury listings are sent to prominent international real estate sites, reaching over 70 million potential 
          buyers and investors worldwide through our relationships with our partners.</p>
        <p class="lux-desc3">We also have several well-positioned affiliate offices in China, providing our clients with 
          access to buyers in Hong Kong, Shanghai, and Beijing. </p>
      </div>
  </div>

  <div class="sponsor-container">
            <img src="/images/sponsor-1.jpg" alt="Image 1" width="20%">
    </div>

    <div class="frame-8">
    <img alt="Cover image" class="cover" src="/images/cover-2.jpg" width="100%" height="100%" />
    <div class="text-1">
      <h1 class="work">Work with us</h1>
      <p class="work-desc">With decades of experience in luxurious Tri Valley real estate, our team 
        is here to ensure that your dreams are a reality. Let us guide you through your home buying journey, contact us today!</p>
      <div class="contact-2">
            <button @click="openModal">CONTACT US</button>
       </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Arimo:ital,wght@0,400..700;1,400..700&family=Newsreader:ital,opsz,wght@0,6..72,200..800;1,6..72,200..800&display=swap');
/*SERVICES*/ 
.services{
  font-family: "Newsreader", serif;
  position: absolute;
  transform: translate(-50%, -50%);
  top: 35%;
  left: 50%;
  transform-origin: center center;
  color: rgb(232, 232, 232);
  font-size: 4.5rem;
  font-weight: 200;
}
.contact{
  position: absolute;
  transform: translate(-50%, -50%);
  top: 55%;
  left: 50%;
  transform-origin: center center;
}
button{
  font-family: "Arimo", sans-serif;
  background-color: transparent;
  color: rgb(232, 232, 232);
  font-size: 0.8rem;
  border-radius: 20%;
  width: 200px;
  height: 50px;
  border:none;
  border:solid 1px rgb(232, 232, 232);
  border-radius: 5px;
  cursor: pointer;
}
  button:hover{
    background-color: rgb(143, 155, 71);
    transition: 0.2s ease-in;
    color:  rgb(232, 232, 232);
    font-weight: bold;
    border: none;
  }

  
/*TEXT CARDS*/ 
.text-cards{
  font-family: "Newsreader", serif;
  font-size: 3rem;
  font-weight: 400;
  color: rgb(14, 14, 14);
  text-align: center;
  margin-top: 5%;
}
.custom-font{
  font-family: "Newsreader", serif;
    font-size: 1.2rem;
    text-align: center;
}

.cards-container{
  margin-top: 5%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 100px;
}
.card-1,.card-2,.card-3,.card-4 {
  background-color: transparent;
  border: none;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 15%;
  padding: 20px 0px 20px 0px;
}
/* .card {
  margin-bottom: 20px;
  width: calc(33.333% - 20px);
} */

@media (max-width: 768px) {
  .card {
    width: 100%;
  }
}

/*DECOR GUIDANCE */
.frame-2{
  margin-top: 25%;
}
.frame-text-1{
  width: 20px;
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  margin-left: 15%;
}

.decor{
  float: right;
  margin-top: -25%;
}
.frame-text-2{
  width: 20px;
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  margin-right: -20%;
  margin-top: 25%;
  float: right;
}

.layout{
  float: left;
  margin-top: 15%;
}

/**EXPERTISE */
.frame-3{
  margin-top: 70%;
}
.list{
  background-color: transparent;
  border: none;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  float: right;
  padding: 80px 40px 80px 40px;
  margin: 0 50px 0 50px;
  margin-top: -20%;
}
.expertise{
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  width: 25%;
  margin-left: 10%;
}
.list{
  background-color: transparent;
  border: none;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  float: right;
  padding: 80px 40px 80px 40px;
  margin: 0 50px 0 50px;
  margin-top: -20%;
}
li{
  font-family: "Arimo", sans-serif;
  line-height: 40px;
  margin-left: 15%;
}

/**THE SELLING */
.selling{
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  text-align: center;
  margin-top: 25%;
}
    .buying{
      font-family: "Newsreader", serif;
      font-weight: 400;
      font-size: 3rem;
      text-align: center;
      margin-top: 15%;
    }
.process{
  font-family: "Arimo", sans-serif;
  margin-top: 10%;
}
    .second-process{
      font-family: "Arimo", sans-serif;
      margin-top: 20%;
    }
.process-1{
  width: 20%;
  padding: 20px 0 20px 100px;
  background-color: rgb(168, 164, 81);
}
    .pr-1{
      width: 20%;
      padding: 20px 0 20px 100px;
      margin-top: -133px;
      background-color: rgb(168, 164, 81);
      float: right;
    }
.process-2{
  width: 30%;
  padding: 20px 0 20px 100px;
  margin-top: -15px;
  background-color: rgb(168, 164, 81);
}
    .pr-2{
      width: 30%;
      padding: 20px 0 20px 100px;
      margin-top: -74px;
      background-color: rgb(168, 164, 81);
      float: right;
    }
.process-3{
  width: 40%;
  padding: 20px 0 20px 100px;
  margin-top: -15px;
  background-color: rgb(168, 164, 81);
}
    .pr-3{
      width: 40%;
      padding: 20px 0 20px 100px;
      margin-top: -15px;
      background-color: rgb(168, 164, 81);
      float: right;
    }
.process-4{
  width: 50%;
  padding: 20px 0 20px 100px;
  margin-top: -15px;
  background-color: rgb(168, 164, 81);
}
    .pr-4{
      width: 50%;
      padding: 20px 0 20px 100px;
      margin-top: -15px;
      background-color: rgb(168, 164, 81);
      float: right;
    }
.process-5{
  width: 60%;
  padding: 20px 0 20px 100px;
  margin-top: -15px;
  background-color: rgb(168, 164, 81);
}

/**images with cards */
.cover-2{
  margin-top: 15%;
}
.description-1 {
  position: absolute;
  right: 0;
  background-color: rgb(143, 155, 71);
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  padding: 40px 40px 40px 40px;
  margin: -120px 50px 0 0; /* Changed from 0 50px 0 50px to 0 50px 0 0 */
  z-index: 1;
}
    .desc-1, .desc-2, .desc-3{
      font-family: "Arimo", sans-serif;
      text-align: center;
    }

    .cover-3{
  margin-top: 20%;
}
.description-2 {
  position: absolute;
  left: 0;
  background-color: rgb(143, 155, 71);
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  padding: 40px 40px 40px 40px;
  margin: -120px 0 0 50px; /* Changed from 0 50px 0 50px to 0 50px 0 0 */
  z-index: 1;
}
    .cover-4{
  margin-top: 20%;
}
.description-3 {
  position: absolute;
  right: 0;
  background-color: rgb(143, 155, 71);
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  padding: 40px 40px 40px 40px;
  margin: -100px 50px 0 0; /* Changed from 0 50px 0 50px to 0 50px 0 0 */
  z-index: 1;
}

.benefit{
  position: absolute;
  left: 7%;
  background-color: transparent;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 80%;
  padding: 40px 40px 40px 40px;
  margin-top: 15%;
  align-items: center;
}
.b-title{
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 1.5rem;
}
.b-desc{
  font-family: "Arimo", sans-serif;
  text-align: center;
}
.b-lists{
  font-family: "Arimo", sans-serif;
  line-height: 40px;
  margin-left: 0%;
}

/**STRAT */
.strat {
  height: 2300px; /* Adjust this value as needed */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.strat-title {
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
}

.strat-subtitle {
  font-family: "Arimo", sans-serif;
  font-size: 1.2rem;
}

.strat-desc {
  font-family: "Arimo", sans-serif;
  font-size: 1rem;
  width: 70%;
}
.strat-container{
  margin-top: 5%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 100px;
}
.s-container1,.s-container2, .s-container3{
  background-color: transparent;
  border: none;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 20%;
  padding: 40px 40px 40px 40px;
  text-align: left;
}
.s-container-title{
  font-family: "Newsreader", serif;
  font-weight: 500;
  font-size: 1.5rem;
}
.s-container-desc{
  font-family: "Arimo", sans-serif;
  font-size: 0.8rem;
  line-height: 20px;
}

/**PARTNERS */
.frame-6{
  margin-top: -50%;
}
.partners{
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  text-align: center;
}
.partners-desc{
  font-family: "Arimo", sans-serif;
  font-size: 1.2rem;
  text-align: center;
}
.partner-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5%;
  gap: 150px;
}
.partners-logo-desc{
  font-family: "Arimo", sans-serif;
  font-size: 1rem;
  text-align: center;
  margin-top: 8%;
}
.partner-desc3{
  margin-top: 2%;
  font-size: 1rem;
  text-align: center;
}

/**LUXURY */
.frame-7{
  margin-top: 20%;
}
.luxury{
  font-family: "Newsreader", serif;
  font-weight: 400;
  font-size: 3rem;
  width: 30%;
  margin-left: 10%;
}
.lux-paragraph{
  font-family: "Arimo", sans-serif;
  background-color: transparent;
  border: none;
  border-radius: 10px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  width: 40%;
  float: right;
  padding: 50px 40px 50px 40px;
  margin: 0 50px 0 50px;
  margin-top: -20%;
  line-height: 20px;
}

/**SPONSOR */
.sponsor-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 15%;
}

/**WORK */
.frame-8{
  margin-top: 10%;
}
.work{
  font-family: "Newsreader", serif;
  color: rgb(232, 232, 232);
  font-size: 4.5rem;
  font-weight: 200;
  margin-top: -30%;
  text-align: center;
}
.work-desc{
  font-family: "Arimo", sans-serif;
  color: rgb(232, 232, 232);
  font-size: 1rem;
  font-weight: 200;
  text-align: center;
  width: 70%;
  margin-left: 15%;
}
.contact-2{
  position: absolute;
  margin-top: 2%;
  margin-left: 42%;
}
button{
  font-family: "Arimo", sans-serif;
  background-color: transparent;
  color: rgb(232, 232, 232);
  font-size: 0.8rem;
  border-radius: 20%;
  width: 200px;
  height: 50px;
  border:none;
  border:solid 1px rgb(232, 232, 232);
  border-radius: 5px;
  cursor: pointer;
}
  button:hover{
    background-color: rgb(143, 155, 71);
    transition: 0.2s ease-in;
    color:  rgb(232, 232, 232);
    font-weight: bold;
    border: none;
  }
</style>