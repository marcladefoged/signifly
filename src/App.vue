<template>
<main id="app">
<Header />
<section class="headline">
<h1>CREATING WHAT'S NEXT</h1>
<h2>WITH DESIGN & TECHNOLOGY</h2>
</section>
<section class="filtering">
<Filtering />
</section>
<Case v-bind:cases="cases" />
<Footer />
</main>
</template>


<script>
import Case from './components/cases.vue' 
import Filtering from './components/filtering.vue'
import Header from './components/header.vue'
import Footer from './components/footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Case,
    Filtering,
    Footer
  },

  data: () => {
    return {
      cases: [
            {id: 1, tagline: '7-Eleven - Rebranding convenience', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1621236720-outdoor-2.jpg"},
            {id: 2, tagline: 'Zaptec - Electrifying the EV transport sector', solution: 'Website', thumbnail:"https://www.datocms-assets.com/7718/1617869680-zap-8.png"},
            {id: 3, tagline: 'Digitaliseringsstyrelsen - Driving digitalization across Denmark', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1617710934-korekort3.jpg"},
            {id: 4, tagline: 'CEC - Chronicling the journey of marine litter ', solution: 'Creative campaign', thumbnail:"https://www.datocms-assets.com/7718/1621244059-bus-stop.jpg"},
            {id: 5, tagline: 'Make Influence - Redefining influencer marketing', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1612266291-asset-16-2x.png"},
            {id: 6, tagline: 'Maersk - Changing global container sales', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1547131462-inline-feat-maersk.png"},
            {id: 7, tagline: 'Mads Nørgaard - New webshop for Danish fashion icon', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1549375262-my10141024x1024.jpg"},
            {id: 8, tagline: 'Ferm Living - E-commerce platform', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1578923711-hero-1b5e27fe01-1559-48e3-9b9c-68f9deb1218d1920x.png"},
            {id: 9, tagline: 'EatMyBill - Getting rid of the bill', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1602600455-eatmybillthumbnailimage.png"},
            {id: 10, tagline: 'DEA - Reimagining a policy institute', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1603879509-12.png"},
            {id: 11, tagline: 'Paperflow - New name and look', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1578927837-paperflowid-businesscards.png"},
            {id: 12, tagline: 'Risika - Rebrand of the Danish fintech scale-up', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1570090222-cards.png"},
            {id: 13, tagline: 'LLARSEN - Minimalist design for Danish watchmakers', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1547202735-llarsen-produktionen-i-svendborgfp-cinemascope-00011407-still004.png"},
            {id: 14, tagline: 'REMA 1000 - Online shopping platform', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1545331839-rema-overview.png"},
            {id: 15, tagline: 'Viking - New look for a Danish classic', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1547562221-petshape-overview-copy-7.png"},
            {id: 16, tagline: 'BotXO - Chatbot for humans', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1570105151-phones.png"},
            {id: 17, tagline: 'Vejdirektoratet - New website for the Danish Road Directorate', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1547483654-vd-feature-3.jpg"},
            {id: 18, tagline: 'Karmameju - A digital home for honest skincare brand', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1545058831-casecoverkarmameju.jpg"},
            {id: 19, tagline: 'ITU - Designing a new frontier for SME cyber security', solution: 'Visual Identity and Website', thumbnail:"https://www.datocms-assets.com/7718/1605621472-1920x1400-sikkercyber-visitkort.png"},
            {id: 20, tagline: 'Rehaler - Migraine treatment without drugs', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1572259636-rehalercase-24.png"},
            {id: 21, tagline: 'Pouri - Online platform for clean and natural supplements', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1572259636-rehalercase-24.png"},
            {id: 22, tagline: 'Klassik - Bringing vintage furniture into the digital age', solution: 'E-commerce'},
            {id: 23, tagline: 'Nautix - Making ship operations easier & safer', solution: 'Digital Experience'},
            {id: 24, tagline: 'Nordic Innovation House - A Nordic guide to Silicon Valley', solution: 'Digital Experience'},
            {id: 25, tagline: 'Universe - Mobile game for Universe Science Park', solution: 'Digital Experience'},
            {id: 26, tagline: 'Intellishore - Digital brandupdate for data wizards', solution: 'Digital Experience'},
            {id: 27, tagline: 'Powerside - Rebrand for global leader in power quality', solution: 'Branding'},
            {id: 28, tagline: 'Copenhagenize - The world\'s most bicycle friendly cities', solution: 'Digital Experience'},
            {id: 29, tagline: 'LIF - The future of health survey', solution: 'Digital Experience'},
            {id: 30, tagline: 'Danmarks Radio - \'Danmarkshistorien\' digital experience', solution: 'Digital Experience'},
            {id: 31, tagline: 'KOLEKTO - Streamlined e-commerce for artisan toymakers', solution: 'E-commerce'},
            {id: 32, tagline: 'Nørrebro Gymnasium - Highlighting multiculturalism in education', solution: 'Branding and Brandfilm'},
            {id: 33, tagline: 'Bloddonor Danmark - Make giving blood matter', solution: 'Digital Experience'},
            {id: 34, tagline: 'Petshape - A healthy gut for your furry friend', solution: 'Branding'},
            {id: 35, tagline: 'Bilabonnement - Driving without friction', solution: 'E-commerce'},
            {id: 36, tagline: 'Damvad Analytics - Leaders in data consulting', solution: 'Branding'},
            {id: 37, tagline: 'MY01 - Online presence for health start-up', solution: 'Digital Experience'},
            {id: 38, tagline: 'Nvizion - Visual Identity for exclusive real estate', solution: 'Branding'},
            {id: 39, tagline: 'Is it a Bird - Branding the innovators of tomorrow', solution: 'Digital Experience'},
            {id: 40, tagline: 'Novataris - Simple and fresh digital presence', solution: 'Digital Experience'},
            {id: 41, tagline: 'Trendday - Fashionably girly  e-commerce', solution: 'E-commerce'},
            {id: 42, tagline: 'Klikkit - Taking control of your habits', solution: 'Branding'},
            {id: 43, tagline: '7-Eleven - Remember there\'s a day tomorrow', solution: 'Campaign'},
            {id: 44, tagline: 'Yx - Getting the audience to reflect on what fuels their everyday.', solution: 'Brandfilm'},
            {id: 45, tagline: 'STX.nu - Win back a lost year', solution: 'Campaign'},
            {id: 46, tagline: 'YX Landbrug - Dear Farmer', solution: 'Brandfilm'},
            {id: 47, tagline: 'Google - The importance of web loading speed', solution: 'B2B Campaign'},
            {id: 48, tagline: 'Helsemin - Local Danish nutrient shop with a International online reach', solution: 'Campaign'},
            {id: 49, tagline: 'MATE. - More than electric transportation', solution: 'Campaign'},
            {id: 50, tagline: 'Notabene - Introducing the new concept store', solution: 'Web Content'},
            {id: 51, tagline: 'Kriminalforsorgen - A day in the Uniform', solution: 'Branded Entertainment'},
            {id: 52, tagline: 'Kriminalforsorgen - Experience the prison from outside the walls', solution: 'Interactive Experience'},
            {id: 53, tagline: 'Kriminalforsorgen - Exploring the job as a prison guard through gamification.', solution: 'Interactive Campaign'},
            ]
    }
  },

};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Black+Ops+One&family=Lato:ital,wght@1,900&display=swap');


img {
    height: 100px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.headline {
  font-family: 'Lato', sans-serif;
  font-weight: 800px;
  margin-top: 10vw;
  margin-left: 10vw;
  font-size: 2.5rem;

}
h2 {
  color: #647689;
}

.cases {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

</style>
