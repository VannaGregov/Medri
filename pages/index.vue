<template>
<div>
  <section>
    <div class="row my-row">
    <div class="col-md-4 my-col">
          <div class="welcome"><h1>Welcome!</h1>
          <div class="hr"></div>
          <div class="body-tekst"><p>Congratulations on making your first <br>step on what is about to be an<br> exciting journey!</p></div>
          <div class="btn-section"><Button /></div>
          <div class="row my-row-2">
            <div class="col-md-6 img-sveuciliste"><img src="/images/sveuciliste.svg" alt="sveuciliste-logo"></div>
            <div class="col-md-6 img-zgrada"><img src="/images/zgrada.svg" alt="zgrada-logo"></div>
          </div>
      </div>
    </div>
    <div class="col-md-8 col-right">
      <div class="section-1">
        <div class="start-app"><h1>START YOUR APPLICATION</h1></div>
        <div class="lorem"><p>Lorem ipsum lorem ipsum lorem. Lorem ipsum<br> lorem ipsum lorem.</p></div>
      </div>
      <div class="row section-2">
        <div class="col-md-6"><img src="/icons/help-circle.svg"></div>
        <div class="col-md-6 text-position"><h2 class="font-h2">HOW TO ENROLL?</h2><p class="font-p">Read  Our Instructions</p></div>
      </div>
      <div class="row section-3">
        <div class="col-md-4"><img src="/icons/document.svg"></div>
        <div class="col-md-4 text-position-2"><h2 class="font-h2">APPLY NOW</h2><p class="font-p">Become Our Student!</p></div>
      </div>
      <div class="img-position"><img src="/icons/beat.svg" alt=""></div>
    </div>
    </div>
  </section>
</div>
  
</template>
<script>
export default {
  
}
</script>
<style scoped>
.my-col {
  height: 1080px;
  background-color: #00417A;
   background-color: #F5F8FA;
    background: linear-gradient(0.06deg, rgba(0, 65, 122, 0.95) 4.03%, rgba(0, 65, 122, 0.92) 92.54%), url(/images/naslovna.jpg), #00417a;
    background-repeat: no-repeat;
    background-size: cover;
}
.welcome > h1 {
  font-family: 'Lora', serif;
  color: white;
  margin-top: 350px;
  margin-left: 70px;
  font-size: 64px;
  font-weight: 500;
}
.body-tekst > p {
  font-size: 20px;
  font-family: Arial, Helvetica, sans-serif;
  color: white;
  margin-left: 75px;
}
.hr {
  border-bottom: 3px solid #00AEEF;
  width: 93px;
  margin-top: 20px;
  margin-bottom: 30px;
  margin-left: 75px;
}
.img-sveuciliste {
  min-width: 200px;
}
.my-row-2 {
  margin-left: 30px;
  margin-top: 300px;
}
.btn-section {
  margin-left: 75px;
  margin-top: 38px;
}
.col-right {
  background-color: #F5F8FA;

}
.start-app > h1{
  font-size: 48px;
  font-family: 'Lora', serif;
  color: #40709B;
  font-weight: bold;
}
.lorem > p {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
  color: #8E8D8D;
  font-weight: bolder;
  margin-top: 30px;
}
.section-1 {
margin-top: 200px;
margin-left: 120px;
}
.section-2 {
  background-color: white;
    margin-right: 722px;
  margin-left: 120px;
  margin-bottom: 100px;
   padding-left: 30px;
  padding-top:40px;
  padding-bottom: 30px;
  margin-top: 70px;
    background: linear-gradient(315deg, rgba(0, 0, 0, 0.6) 0%, rgba(255, 255, 255, 0) 100%), #FFFFFF;
background-blend-mode: soft-light, normal;
/* Up / >64 */

box-shadow: -4.08333px -4.08333px 12.25px #FFFFFF, 6.125px 6.125px 12.25px rgba(174, 174, 192, 0.4), inset 0px 0px 0px 1px rgba(255, 255, 255, 0.2);
border-radius: 12px;
}
.section-3 {
    background-color: white;
    margin-right: 722px;
  margin-left: 120px;
  margin-bottom: 100px;
   padding-left: 30px;
  padding-top:40px;
  padding-bottom: 30px;
  background: linear-gradient(315deg, rgba(0, 0, 0, 0.6) 0%, rgba(255, 255, 255, 0) 100%), #FFFFFF;
background-blend-mode: soft-light, normal;
box-shadow: -4.08333px -4.08333px 12.25px #FFFFFF, 6.125px 6.125px 12.25px rgba(174, 174, 192, 0.4), inset 0px 0px 0px 1px rgba(255, 255, 255, 0.2);
border-radius: 12px;
}
.font-h2 {
  font-size: 20px;
  color: #40709B;
  font-family: 'Lora', serif;
  font-weight: bolder;
  min-width: 600px;
}
.font-p {
  color: #8E8D8D;
  font-size: 20px;
  font-family: Arial, Helvetica, sans-serif;
  min-width: 600px;
}
.text-position {
  margin-left: -80px;
  margin-top: 10px;
}
.text-position-2 {
  margin-left: -10px;
  margin-top: 10px;
}
.img-position {
  position:absolute;
  margin-top: -365px;
  margin-left: 547px;
}
</style>