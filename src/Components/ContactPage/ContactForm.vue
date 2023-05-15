<template>
  <section>
    <div class="container-fluid py-5">
      <div class="row d-flex">
        <div class="col-12 col-xl-6 col-lg-6 col-md-6 col-sm-12 order-sm-0 order-12" style="margin-right:-120px;">
          <img class="img-fluid" src="@/assets/contact-page.jpg">
        </div>
        <div class="col-12 col-xl-6 col-lg-5 col-md-6 col-sm-12 order-first order-xl-0 party">
          <!-- HTML !-->
          <h3>Remember to leave us a message</h3>
          <button class="button-40" role="button">
            <a href="mailto:jacquesstephan10@gmail.com">Via Mail</a>
          </button>
          <p/>
          <h3>Follow me on</h3>
          <a target="_blank" href="https://www.linkedin.com/in/stephen-jacques-a4a6161ba/">
            <img class="img-fluid ratio" src="@/assets/social/linkedin.png">
          </a>
          <a target="_blank" href="https://wa.me/+237698803159?text=Hello!">
            <img class="img-fluid ratio" src="@/assets/social/whatsapp.png">
          </a>
          <a target="_blank" href="https://github.com/Stephen2304">
            <img class="img-fluid ratio" src="@/assets/social/github.png">
          </a>
          <a target="_blank" href="https://twitter.com/StephenJacque16">
            <img class="img-fluid ratio" src="@/assets/social/twitter.png">
          </a>
          <a target="_blank" href="https://www.facebook.com/people/Stephen-Jacques/100081056631138/">
            <img class="img-fluid ratio" src="@/assets/social/facebook.png">
          </a>
          <!-- https://wa.me/+237698803159?text=Hello! -->
          <!-- <a href="mailto:contact@arthurmonney.me" class="inline-block mt-4 sm:mt-0 text-sm leading-5 font-medium text-white py-2.5 px-4 bg-slate-900 hover:bg-black rounded-full"><span class="sr-only">Email Address</span>via Email</a> -->

          <!-- https://wa.me/<numéro_de_téléphone>?text=<votre_message_avec_le_lien></votre_message_avec_le_lien> -->
        </div>
        </div>
      </div>
  </section>
</template>

<script>
export default {
  name: 'ContactForm'
}
</script>

<style scoped>
.ratio {
  width: 5%;
  margin-right: 1%;
}
.party{
  left: 10%;
  top: 10rem;
}
/* CSS */
.button-40 > a {
  color: white;
  text-decoration: none;
}
.button-40 {
  background-color: #0F172A;
  border: 1px solid transparent;
  border-radius: 25px;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  flex: 0 0 auto;
  font-family: "Inter var",ui-sans-serif,system-ui,-apple-system,system-ui,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
  font-size: 1.125rem;
  font-weight: 600;
  line-height: 1.5rem;
  padding: .75rem 1.2rem;
  text-align: center;
  text-decoration: none #6B7280 solid;
  text-decoration-thickness: auto;
  transition-duration: .2s;
  transition-property: background-color,border-color,color,fill,stroke;
  transition-timing-function: cubic-bezier(.4, 0, 0.2, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  width: auto;
}

.button-40:hover {
  background-color: #374151;
}

.button-40:focus {
  box-shadow: none;
  outline: 2px solid transparent;
  outline-offset: 2px;
}

@media (min-width: 768px) {
  .button-40 {
    padding: .75rem 1.5rem;
  }
}
</style>
