<script>
  export default {
    setup() {
      return {
        footerlinks: [
            [
              {text: 'Open Sourse', link: '#'},
              {text: 'GIR', link: '#'},
              {text: 'Letterfolk', link: '#'},
              {text: 'Yield', link: '#'},
              {text: 'Poketo', link: '#'},
              {text: 'Equal Parts', link: '#'}
            ],
            [
                {text: 'Careers', link: '#'},
                {text: 'Press', link: '#'},
            ],
            [
                {text: 'Instagram', link: '#'},
                {text: 'Twitter', link: '#'},
            ],
            [
                {text: '228 Park Ave S.', link: '#'},
                {text: 'New York, NY 10003', link: '#'},
                {text: 'acquisitions@patternbrands.com', link: '#'},
            ]
        ]
      }
    }
  }
</script>

<template>
<footer class="container" id="join">
  <div class="contact">
    <p class="contact-title">contact</p>
    <p class="contact-text">We're focused on building brands and a better future. If you'd like to partner with us, we're here to talk</p>
  </div>
  <div class="footer-links">
    <ul class="footer-links-list" v-for="column in footerlinks">
      <li class="footer-link" v-for="row in column"><a :href="row.link">{{ row.text }}</a></li>
    </ul>
  </div>
  <div class="hr"></div>
  <div class="copyright">
    © 2022 Pattern Brands
  </div>
</footer>
</template>

<style>

</style>