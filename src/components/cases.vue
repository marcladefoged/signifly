<template>
<div id="cases">

<!-- <ul id="case-rendering">
  <li v-for="case in cases" :key="case.tagline">{{ case.tagline }}</li>
</ul> -->

<!--  <ul>
  <li v-for="case in cases">{{ case }}</li>
</ul> -->
 
<div id="7eleven" class="caseframe">
    <a href="https://signifly.com/work/7-eleven">
    <img src="https://www.datocms-assets.com/7718/1621236720-outdoor-2.jpg" alt="case image">
    <p>{{ cases[0].solution }} </p> 
   <h1> {{ cases[0].tagline }} </h1> 
    </a>
</div>

 <div id="Zaptec" class="caseframe">
     <a href="https://signifly.com/work/zaptec">
    <img src="https://www.datocms-assets.com/7718/1617869680-zap-8.png" alt="case image">
    <p>{{ cases[1].solution }} </p>
   <h1> {{ cases[1].tagline }} </h1> 
     </a>
</div>

<div id="Digitaliseringsstyrelsen" class="caseframe">
    <a href="https://signifly.com/work/digitaliseringsstyrelsen">
    <img src="https://www.datocms-assets.com/7718/1617710934-korekort3.jpg" alt="case image">
    <p>{{ cases [2].solution }} </p> 
   <h1> {{ cases[2].tagline }} </h1> 
     </a> 
</div> 

<div id="CEC" class="caseframe">
    <a href="https://signifly.com/work/cec">
    <img src="https://www.datocms-assets.com/7718/1621244059-bus-stop.jpg" alt="case image">
    <p>{{ cases[3].solution }} </p>
   <h1> {{ cases[3].tagline }} </h1> 
    </a>
</div>

<div id="makeinfluence" class="caseframe">
    <a href="https://signifly.com/work/make-influence">
    <img src="https://www.datocms-assets.com/7718/1612266291-asset-16-2x.png" alt="case image">
    <p>{{ cases[4].solution }} </p> 
   <h1> {{ cases[4].tagline }} </h1> 
    </a>
</div>

<div id="maersk" class="caseframe">
    <a href="https://signifly.com/work/maersk-line">
    <img src="https://www.datocms-assets.com/7718/1547131462-inline-feat-maersk.png" alt="case image">
    <p>{{ cases[5].solution }} </p>
   <h1> {{ cases[5].tagline }} </h1> 
    </a>
</div>

<div id="madsnoerregaard" class="caseframe">
    <a href="https://signifly.com/work/madsnoerregaard">
    <img src="https://www.datocms-assets.com/7718/1549375262-my10141024x1024.jpg" alt="case image">
    <p>{{ cases[6].solution }} </p>
   <h1> {{ cases[6].tagline }} </h1>  
    </a>
</div>

<div id="fermliving" class="caseframe">
    <a href="https://signifly.com/work/ferm-living">
    <img src="https://www.datocms-assets.com/7718/1578923711-hero-1b5e27fe01-1559-48e3-9b9c-68f9deb1218d1920x.png" alt="case image">
    <p>{{ cases[7].solution }} </p> 
   <h1> {{ cases[7].tagline }} </h1> 
    </a>
</div>

<div id="eatmybill" class="caseframe">
    <a href="https://signifly.com/work/eatmybill">
    <img src="https://www.datocms-assets.com/7718/1602600455-eatmybillthumbnailimage.png" alt="case image">
    <p>{{ cases[8].solution }} </p> 
   <h1> {{ cases[8].tagline }} </h1> 
    </a>
</div>

<div id="dea" class="caseframe">
    <a href="https://signifly.com/work/dea">
    <img src="https://www.datocms-assets.com/7718/1603879509-12.png" alt="case image">
    <p>{{ cases[9].solution }} </p> 
   <h1> {{ cases[9].tagline }} </h1> 
    </a>
</div>

<div id="paperflow" class="caseframe">
    <a href="https://signifly.com/work/paperflow">
    <img src="https://www.datocms-assets.com/7718/1578927837-paperflowid-businesscards.png" alt="case image">
    <p>{{ cases[10].solution }} </p> 
   <h1> {{ cases[10].tagline }} </h1> 
    </a>
</div>

<div id="risika" class="caseframe">
    <a href="https://signifly.com/work/risika">
    <img src="https://www.datocms-assets.com/7718/1570090222-cards.png" alt="case image">
    <p>{{ cases[11].solution }} </p> 
   <h1> {{ cases[11].tagline }} </h1> 
    </a>
</div>

<div id="llarsen" class="caseframe">
    <a href="https://signifly.com/work/llarsen-watches">
    <img src="https://www.datocms-assets.com/7718/1547202735-llarsen-produktionen-i-svendborgfp-cinemascope-00011407-still004.png" alt="case image">
    <p>{{ cases[12].solution }} </p> 
   <h1> {{ cases[12].tagline }} </h1> 
    </a>
</div>

<div id="rema" class="caseframe">
    <a href="https://signifly.com/work/rema-1000">
    <img src="https://www.datocms-assets.com/7718/1545331839-rema-overview.png" alt="case image">
    <p>{{ cases[13].solution }} </p> 
   <h1> {{ cases[13].tagline }} </h1> 
    </a>
</div>

<div id="viking" class="caseframe">
    <a href="https://signifly.com/work/viking">
    <img src="https://www.datocms-assets.com/7718/1547562221-petshape-overview-copy-7.png" alt="case image">
    <p>{{ cases[14].solution }} </p> 
   <h1> {{ cases[14].tagline }} </h1> 
    </a>
</div>

<div id="botxo" class="caseframe">
    <a href="https://signifly.com/work/botxo">
    <img src="https://www.datocms-assets.com/7718/1570105151-phones.png" alt="case image">
    <p>{{ cases[15].solution }} </p> 
   <h1> {{ cases[15].tagline }} </h1> 
    </a>
</div>

<div id="vejdirektoratet" class="caseframe">
    <a href="https://signifly.com/work/danish-road-directorate-vejdirektoratet">
    <img src="https://www.datocms-assets.com/7718/1547483654-vd-feature-3.jpg" alt="case image">
    <p>{{ cases[16].solution }} </p> 
   <h1> {{ cases[16].tagline }} </h1> 
    </a>
</div>

<div id="karmameju" class="caseframe">
    <a href="https://signifly.com/work/karmameju">
    <img src="https://www.datocms-assets.com/7718/1545058831-casecoverkarmameju.jpg" alt="case image">
    <p>{{ cases[17].solution }} </p> 
   <h1> {{ cases[17].tagline }} </h1> 
    </a>
</div>

<div id="itu" class="caseframe">
    <a href="https://signifly.com/work/itu">
    <img src="https://www.datocms-assets.com/7718/1605621472-1920x1400-sikkercyber-visitkort.png" alt="case image">
    <p>{{ cases[18].solution }} </p> 
   <h1> {{ cases[18].tagline }} </h1> 
    </a>
</div>

<div id="rehaler" class="caseframe">
    <a href="https://signifly.com/work/rehaler">
    <img src="https://www.datocms-assets.com/7718/1572259636-rehalercase-24.png" alt="case image">
    <p>{{ cases[19].solution }} </p> 
   <h1> {{ cases[19].tagline }} </h1> 
    </a>
</div>

<div id="puori" class="caseframe">
    <a href="https://signifly.com/work/puori">
    <img src="https://www.datocms-assets.com/7718/1570193204-puori-home.png" alt="case image">
    <p>{{ cases[20].solution }} </p> 
   <h1> {{ cases[20].tagline }} </h1> 
    </a>
</div>

<div id="klassik" class="caseframe">
    <a href="https://signifly.com/work/klassik">
    <img src="https://www.datocms-assets.com/7718/1578921839-kliassik598401920x.jpg" alt="case image">
    <p>{{ cases[21].solution }} </p> 
   <h1> {{ cases[21].tagline }} </h1> 
    </a>
</div>

<div id="nautix" class="caseframe">
    <a href="https://signifly.com/work/nautix">
    <img src="https://www.datocms-assets.com/7718/1569919840-logo-on-image.jpg" alt="case image">
    <p>{{ cases[22].solution }} </p> 
   <h1> {{ cases[22].tagline }} </h1> 
    </a>
</div>

<div id="nordic-innovation-house" class="caseframe">
    <a href="https://signifly.com/work/nordic-innovation-house">
    <img src="https://www.datocms-assets.com/7718/1570101149-ebook2.png" alt="case image">
    <p>{{ cases[23].solution }} </p> 
   <h1> {{ cases[23].tagline }} </h1> 
    </a>
</div>

<div id="universe" class="caseframe">
    <a href="https://signifly.com/work/universe">
    <img src="https://www.datocms-assets.com/7718/1547562795-universe.png" alt="case image">
    <p>{{ cases[24].solution }} </p> 
   <h1> {{ cases[24].tagline }} </h1> 
    </a>
</div>

<div id="intellishore" class="caseframe">
    <a href="https://signifly.com/work/intellishore">
    <img src="https://www.datocms-assets.com/7718/1570095826-intellishore-home-mobile.png" alt="case image">
    <p>{{ cases[25].solution }} </p> 
   <h1> {{ cases[25].tagline }} </h1> 
    </a>
</div>

<div id="powerside" class="caseframe">
    <a href="https://signifly.com/work/powerside/">
    <img src="https://www.datocms-assets.com/7718/1570108962-logo-paper.jpg" alt="case image">
    <p>{{ cases[26].solution }} </p> 
   <h1> {{ cases[26].tagline }} </h1> 
    </a>
</div>

<div id="copenhagenize" class="caseframe">
    <a href="https://signifly.com/work/copenhagenize">
    <img src="https://www.datocms-assets.com/7718/1570105752-copenhagenize-fan-responsive.jpg" alt="case image">
    <p>{{ cases[27].solution }} </p> 
   <h1> {{ cases[27].tagline }} </h1> 
    </a>
</div>

<div id="lif" class="caseframe">
    <a href="https://signifly.com/work/lif">
    <img src="https://www.datocms-assets.com/7718/1570106736-lif-case-4.png" alt="case image">
    <p>{{ cases[28].solution }} </p> 
   <h1> {{ cases[28].tagline }} </h1> 
    </a>
</div>

<div id="dr" class="caseframe">
    <a href="https://signifly.com/work/dr">
    <img src="https://www.datocms-assets.com/7718/1545130186-casecoverdr.jpg" alt="case image">
    <p>{{ cases[29].solution }} </p> 
   <h1> {{ cases[29].tagline }} </h1> 
    </a>
</div>

<div id="kolekto" class="caseframe">
    <a href="https://signifly.com/work/kolekto">
    <img src="https://www.datocms-assets.com/7718/1605627186-kolekto-mobile-cusotmize-flow.png" alt="case image">
    <p>{{ cases[30].solution }} </p> 
   <h1> {{ cases[30].tagline }} </h1> 
    </a>
</div>

<div id="norrebro-gymnasium" class="caseframe">
    <a href="https://signifly.com/work/norrebro-gymnasium">
    <img src="https://www.datocms-assets.com/7718/1607070467-symbol.png" alt="case image">
    <p>{{ cases[31].solution }} </p> 
   <h1> {{ cases[31].tagline }} </h1> 
    </a>
</div>

<div id="bloddonorer" class="caseframe">
    <a href="https://signifly.com/work/bloddonorer-danmark">
    <img src="https://www.datocms-assets.com/7718/1570088830-two-iphones-tilt.jpg" alt="case image">
    <p>{{ cases[32].solution }} </p> 
   <h1> {{ cases[32].tagline }} </h1> 
    </a>
</div>

<div id="petshape" class="caseframe">
    <a href="https://signifly.com/work/petshape">
    <img src="https://www.datocms-assets.com/7718/1570008493-petshapecase-04.png" alt="case image">
    <p>{{ cases[33].solution }} </p> 
   <h1> {{ cases[33].tagline }} </h1> 
    </a>
</div>

<div id="bilabonnement" class="caseframe">
    <a href="https://signifly.com/work/bilabonnement">
    <img src="https://www.datocms-assets.com/7718/1545550609-bil-abonnement-overview.png" alt="case image">
    <p>{{ cases[34].solution }} </p> 
   <h1> {{ cases[34].tagline }} </h1> 
    </a>
</div>

<div id="damvad" class="caseframe">
    <a href="https://signifly.com/work/damvad-analytics">
    <img src="https://www.datocms-assets.com/7718/1545053088-casecover.jpg" alt="case image">
    <p>{{ cases[35].solution }} </p> 
   <h1> {{ cases[35].tagline }} </h1> 
    </a>
</div>

<div id="my01" class="caseframe">
    <a href="https://signifly.com/work/my01">
    <img src="https://www.datocms-assets.com/7718/1602622614-web-1920-12.png" alt="case image">
    <p>{{ cases[36].solution }} </p> 
   <h1> {{ cases[36].tagline }} </h1> 
    </a>
</div>

<div id="nvizion" class="caseframe">
    <a href="https://signifly.com/work/nvizion">
    <img src="https://www.datocms-assets.com/7718/1570108566-logo-blue.jpg" alt="case image">
    <p>{{ cases[37].solution }} </p> 
   <h1> {{ cases[37].tagline }} </h1> 
    </a>
</div>

<div id="isitbird" class="caseframe">
    <a href="https://signifly.com/work/is-it-a-bird-website">
    <img src="https://www.datocms-assets.com/7718/1545050568-caseiiabcover.jpg" alt="case image">
    <p>{{ cases[38].solution }} </p> 
   <h1> {{ cases[38].tagline }} </h1> 
    </a>
</div>

<div id="novataris" class="caseframe">
    <a href="https://signifly.com/work/novataris">
    <img src="https://www.datocms-assets.com/7718/1570107889-novataris-mobile.jpg" alt="case image">
    <p>{{ cases[39].solution }} </p> 
   <h1> {{ cases[39].tagline }} </h1> 
    </a>
</div>

<div id="trendday" class="caseframe">
    <a href="https://signifly.com/work/trendday">
    <img src="https://www.datocms-assets.com/7718/1545125327-sc1-trendday.jpg" alt="case image">
    <p>{{ cases[40].solution }} </p> 
   <h1> {{ cases[40].tagline }} </h1> 
    </a>
</div>

<div id="klikkit" class="caseframe">
    <a href="https://signifly.com/work/klikkit">
    <img src="https://www.datocms-assets.com/7718/1545335202-klikit-overview.png" alt="case image">
    <p>{{ cases[41].solution }} </p> 
   <h1> {{ cases[41].tagline }} </h1> 
    </a>
</div>

<div id="remember" class="caseframe">
    <a href="https://signifly.com/work/remember">
    <img src="https://www.datocms-assets.com/7718/1639654186-frame-1.png" alt="case image">
    <p>{{ cases[42].solution }} </p> 
   <h1> {{ cases[42].tagline }} </h1> 
    </a>
</div>

<div id="yx-norge" class="caseframe">
    <a href="https://signifly.com/work/yx-norge">
    <img src="https://www.datocms-assets.com/7718/1639655926-thumb.png" alt="case image">
    <p>{{ cases[43].solution }} </p> 
   <h1> {{ cases[43].tagline }} </h1> 
    </a>
</div>

<div id="stx" class="caseframe">
    <a href="https://signifly.com/work/2-arig-stx">
    <img src="https://www.datocms-assets.com/7718/1639997831-thumb.png" alt="case image">
    <p>{{ cases[44].solution }} </p> 
   <h1> {{ cases[44].tagline }} </h1> 
    </a>
</div>

<div id="yx-landbrug" class="caseframe">
    <a href="https://signifly.com/work/yx-landbrug">
    <img src="https://www.datocms-assets.com/7718/1640003628-yx-cover.png" alt="case image">
    <p>{{ cases[45].solution }} </p> 
   <h1> {{ cases[45].tagline }} </h1> 
    </a>
</div>

<div id="google-web" class="caseframe">
    <a href="https://signifly.com/work/google-web">
    <img src="https://www.datocms-assets.com/7718/1640004796-hover1.png" alt="case image">
    <p>{{ cases[46].solution }} </p> 
   <h1> {{ cases[46].tagline }} </h1> 
    </a>
</div>

<div id="helsemin" class="caseframe">
    <a href="https://signifly.com/work/helsemin">
    <img src="https://www.datocms-assets.com/7718/1640004944-group-2403.png" alt="case image">
    <p>{{ cases[47].solution }} </p> 
   <h1> {{ cases[47].tagline }} </h1> 
    </a>
</div>

<div id="mate" class="caseframe">
    <a href="https://signifly.com/work/mate">
    <img src="https://www.datocms-assets.com/7718/1640010997-hover.png" alt="case image">
    <p>{{ cases[48].solution }} </p> 
   <h1> {{ cases[48].tagline }} </h1> 
    </a>
</div>

<div id="notabene" class="caseframe">
    <a href="https://signifly.com/work/notabene">
    <img src="https://www.datocms-assets.com/7718/1640014162-web-27.jpg" alt="case image">
    <p>{{ cases[49].solution }} </p> 
   <h1> {{ cases[49].tagline }} </h1> 
    </a>
</div>

<div id="kriminalforsorgen-influencer" class="caseframe">
    <a href="https://signifly.com/work/kriminalforsorgen-influencer">
    <img src="https://www.datocms-assets.com/7718/1640086924-hero.png" alt="case image">
    <p>{{ cases[50].solution }} </p> 
   <h1> {{ cases[50].tagline }} </h1> 
    </a>
</div>

<div id="krim-vr" class="caseframe">
    <a href="https://signifly.com/work/krim-vr">
    <img src="https://www.datocms-assets.com/7718/1640171543-0101.jpg" alt="case image">
    <p>{{ cases[51].solution }} </p> 
   <h1> {{ cases[51].tagline }} </h1> 
    </a>
</div>

<div id="krim-scenario" class="caseframe">
    <a href="https://signifly.com/work/krim-vr">
    <img src="https://www.datocms-assets.com/7718/1640181220-cover.jpg" alt="case image">
    <p>{{ cases[52].solution }} </p> 
   <h1> {{ cases[52].tagline }} </h1> 
    </a>
</div>

</div>
</template>

<script>
export default {
    name: "Case",
    props: ['cases'],
   
data: () => {
    return {
            /* cases: [
            {id: 1, tagline: '7-Eleven - Rebranding convenience', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1621236720-outdoor-2.jpg"},
            {id: 2, tagline: 'Zaptec - Electrifying the EV transport sector', solution: 'Website', thumbnail:"https://www.datocms-assets.com/7718/1617869680-zap-8.png"},
            {id: 3, tagline: 'Digitaliseringsstyrelsen - Driving digitalization across Denmark', solution: 'Digital Experience', thumbnail:"https://www.datocms-assets.com/7718/1617710934-korekort3.jpg"},
            {id: 4, tagline: 'CEC - Chronicling the journey of marine litter ', solution: 'Creative campaign', thumbnail:"https://www.datocms-assets.com/7718/1621244059-bus-stop.jpg"},
            {id: 5, tagline: 'Make Influence - Redefining influencer marketing', solution: 'Branding', thumbnail:"https://www.datocms-assets.com/7718/1612266291-asset-16-2x.png"},
            {id: 6, tagline: 'Maersk - Changing global container sales', solution: 'E-commerce', thumbnail:"https://www.datocms-assets.com/7718/1547131462-inline-feat-maersk.png"},
            {id: 7, tagline: 'Mads Nørgaard - New webshop for Danish fashion icon', solution: 'E-commerce"', thumbnail:"https://www.datocms-assets.com/7718/1549375262-my10141024x1024.jpg"},
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
            ] */
    }
  },
}  



        
</script>

<style scoped>

* {
    margin: 0;
    padding: 0;  
}

.caseframe img {
background-size: cover;
background-position: 50%;
background-repeat: no-repeat;
max-height: 440px;
height: 35vw;
max-width: 350px;
object-fit: cover;
}

#cases {
display: grid;
grid-template-columns: repeat(3, 1fr);
margin-left: 6vw;
margin-right: 6vw;
}

#cases div {
    padding: 2vw;
}

.caseframe {
display: block;
color: inherit;
text-decoration: none;
margin-bottom: 124px;
max-height: 440px;
height: 35vw;
width: 350px;

}

.caseframe a{
    text-decoration: none;
    color: black;
    width: 20vw;
}

.caseframe a:hover {
    transition: yellow .3s ease-in-out;
}

.caseframe h1 {
    font-size: 1.2rem;
    margin-top: 2vh;
}

.caseframe p {
    font-size: 0.9rem;
    margin-top: 2vh;
}

   @media all and (max-width: 576px) {

       .caseframe img {
            max-height: 440px;
            height: 40vw;
            max-width: 650px;           

       }
        
        #cases {
            margin-top: 10vh;
            grid-template-columns: 1fr;
            width: 10vw;
            margin-bottom: 1rem;
            
             }

        .caseframe {
            width: 60vw;
            margin-top: 5vh;
        }

        }
</style>

