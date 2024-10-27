<script>
import AppCards from "@/components/AppCards.vue";
  export default {
    components: {AppCards},
    setup() {
      return {
        cards: [
          {id: 1, image: 'https://s3-alpha-sig.figma.com/img/4722/a701/6041f976cd07ee5b9038fd520f5be944?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=grNRMLSLSQ-hf3pfA6qUn0y5ca1gvshM09ISnQ7vtKtlS7QoInm14n53-6zrmdA5Avkfms6jOpqA2aw9wa3z-Rc2j9ao~KOJpp014dByB0waon8Wdk2XGANl-GrEmloJmOelTQw0yxVGzFeA3Ak09~qI8IgxIi1RZsH4Nvh1nMmxfq7vnbXdOzV-iDkPjAIquJv5YPO1YpPF5tgHc~cXQCI1DF6Z1miGnWR~dAjb9Linnv58KyCkwfnx3qnqp7FXrdauH9cO41XHsgtv9UQX3XTTYX5uGNCyDraPk1f4wssUlAZUbVQZkKGse9YUb22oBWKgeoKeL12v63Cr9CCr3w__', title: 'GIR: One Year In', category: 'Case Study'},
          {id: 2, image: 'https://s3-alpha-sig.figma.com/img/e330/b518/0fdb9694a19f6fcd1b021b5bdf83cd8d?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=L9onZD0PzLdEXjQHsmTsR1BzIghvcMDJeclGhySI4hkRw3V3VqsFEmXnA~-QwW1MPaOCIUs1RnOWO4gHDfNNlE-JPEL4-CTWPW~gL3ameu86pA2YlKlmqjJU0UmG1pc4zC2DWpUGr7Mnd43Ek3h6LCksRqSbwG8huCYWiHsGZzo8mZIPc614qUF1UJ97K0aPVjB0WzBGM2oMBRJzdDrMVIYiVE34KGWd6oJmLrD0ik51si9gx2BJGEEiyYJwmdGLKs2ptFZ1YHMLFuk9eoIKtDvVaN4KyAxpBY21aSH~NLR52WkRLdkGJm3pwcwDcAR4wMZu1MAKkXPe0~HEOuDtng__', title: 'Introducing Onsen', category: 'new additions'},
          {id: 3, image: 'https://s3-alpha-sig.figma.com/img/ebde/7f18/3ade053c30b04e42b692397f2fb3bd7d?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=few-8b3j1Xszp9zIYJ4CA0MoexL8ODsE9yt-zPXosqMBv-lraqHSjgAmgpdC0HrdW8NvZsJq2d1SFRy0ITcnfn5ltVHe2GkRu261R1nx6Jsf~BvpQhGgBAYauBnpDCl6o1CeWrQGOIEuMOp9axqis~2t9OdDBqc-gXiACpLCzImmjFR9Fg3RxrFHpCzudYSmp5UtCx4R2i3VhIEHoACTveUXDoImaIhIdOaIo5s~~j0tqwSs~w2JkyBfeVwaFHcIuQEO~m7PyryxGkyy4Vg6AbhS2FmsizcDhjO8lguFUK8hOSX9C9QHy0UDEK3SvD1IrKqQ~Vh4KmzY-z4o-iBhtg__', title: 'Selling Your Shopify Brand: An Introduction', category: 'Mergers & Acquisitions 101'},
          {id: 4, image: 'https://s3-alpha-sig.figma.com/img/2afd/6e24/c7ee114742aaa78783dc4e6db8a01b40?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=WBfiZQaWY5523~S2zcbWDTSrtMYScKoiuS3ZqgBEKQ0jP6aDbFTZ~fb~-ucoxelAL2Phad23BTR4X6dJ71nOtdUxVJxI9XJKEKhs87Z9lhMcj8L2yKXQei~8ZHkQc3EHR0lNP3-GAIzEkG2NLh3KQgpROBnfVk7MSWSp9z7J4u6M~RQWq5NMhPK8XGiXMQTC47edYBIFwDbe9rYPw82ZYAtDIe71L4BZArPl-t7z7jl-z78BeD5TpEjX7490YVgOOnbQUVhJ3m~fOuXpywBOL5KIIZ3cwzm-KUElTzjJ710LOylDQhOvYc2ZP4IJIsyaBq2MZ-sjX2R1OEqtkI1xuA__', title: '5 Reasons We Are Optimistic for 2023', category: 'MERGERS & ACQUISITIONS 101'},
          {id: 5, image: 'https://s3-alpha-sig.figma.com/img/0683/141e/3512204d134210c361e260eb75d064f0?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=YFPO6RAxxbTYNjBB1by1j63zEokd91jc7KxHZYsiBSBozCJkjgyWRsWCCUXp9eLlk5AOK7yhaUlqmh0O-HoDx74Zbw-SjSOeFclAAh~MJr6yiFA1u8G4DGvPfannuvxoFiN32CpaXTGEGg7Gvf8aVZDikr7eNHisy93orqQ~4TMQQXQHRRx3XGPB8czrNCCN2KXN9VJx~0OwmuZBrYv~eTz1TiaJBWtgV6FwatDBykmMwSvwf9Jgnifivmc5o3W4Lw0ifsoQ7yoqs6UP1vA9IyXyHKOImAkVu4RDO-JorExaRWVDc0S3GEVsJn~guEneZzwKB4okcoKpMBlBk3hytw__', title: 'Why Right Now is a Great Time to Sell Your Brand', category: 'MERGERS & ACQUISITIONS 101'},
          {id: 6, image: 'https://s3-alpha-sig.figma.com/img/aa46/34fa/0cd33e670e657f624a062eeb35546ef2?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=pr1EVdPutPfFJt7T24OAHkdh4y7Eli0uGRDvLs1WjpoWzR6YIFLPqbAyZF7MGJ7UIN~HrgCVXKcMTUS7MxeyDsBp2XsA08q45pLYazqIuX0g7JSq98vk5jO8Q1Ws7126o-tY8xQu8qE8l35JjQ9SPkxleILz60uPQE0KaMHACsN4C91BOPLs4FHhKWjzMFRChYhfIGrHVM9AQNAdJpizCgQKW9x~SkQLGkCwy3lDOKWTIcGTmfSK0vaOsudKoK2~XEhSTAzP88tNGpC6G0EWmLPyPwNeVThWdpcaqS8SU2EkIwBJFRTHoZfyj-Uc1mR6Zn-wf6T-VJ149aJO9ObMZA__', title: 'Selling Your Shopify Brand: Week 1', category: 'Mergers & Acquisitions 101'},
          {id: 7, image: 'https://s3-alpha-sig.figma.com/img/9c99/d1ff/c0e37f13919bb47ca3a4a1338d822625?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=DdnbmZmH5HTKPRZbo9CZ5r4rie4U50Nh7IWsMA~5o4bB0rYxhVDSSxC0Rns~8uwtsNyPPMXCqrEIAsPOCpJ0ECyjxnC2hNI22Zsf1UiiATGQONQSYVVniSUa-uJEExCurycowgEuMuUwpx7nRo-qcNylWeZCJp7C5nD~HzvNRFGM-ShqK3rRF~VDp-bRxCx6hv56mfq-NvJij0Cg3jZKv8dqdsx39qty2UNfdG1qASaG4xiRH3Fr8SoEAbOi~bypFmdTUhCTzUFnHUYsocr7D07DDSG4DUVVfIHzs4cLuLZDKYmEAGNpSqxRC6YZQFrygfg9xW4kCETAdAUwLwT~zw__', title: "Pattern's 2022 Update", category: 'THOUGHT LEADERSHIP'},
          {id: 8, image: 'https://s3-alpha-sig.figma.com/img/e59f/1cb7/fcb1636f68531e062f6e0cc402a7ef44?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=jDtx55Zw0UDg4vVwk38Oa31or6SeML4zYlZMP8fqy5OeDBP3fZxOCoskIB4zDU0uGewMahSXChDOtAjssmBbFfFDPNk1w~7bvOKQSpqTfVOAHaAHXBOtTFBfumiiQRrX9AhT8XD6EF3voBvROJpZKAV8JsAQZUuFs6LpnxWgt6nhqVYFYw8Dgb5bzyDOYOqwuRxwWI4AkOKUCYN8wQZAr0yjt4E9o1VdEwd-O55R4dCqeNFUzNnkfDzLcW-QUhvSGeuqEVE7-8Z19HRK0~ZGGyODGItbvvauzgg327hhZRMGPhx-kSwvgenIgI4M5t7GlARNY8DvmM5hSZARsGNJaw__', title: 'Introducing Yield', category: 'New Additions'},
          {id: 9, image: 'https://s3-alpha-sig.figma.com/img/ac1e/1aff/b5e62d6cdb2da36eef0dbe19e6ac32f3?Expires=1730678400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=Fa~UrK2XA6fksM0Dyh5r0DrtwPp3ngwVq8cHoCdpUEQYNtLP-NlC9Slf~b2RxnkUyWDfi7nGPoQ4fZ30evdqO1FUyT-mDeKM0MOXgmXQJzCZt4YO61W4A2LA9Kx~qBtCQ8ptHo0t04J~3obI2e-xEg~YO7LFQ6AIfQ8DNRAA9rNqblLs2aX169KCNm32dqhbstWEJLko6Fa5-f85Z6l6W9mH130Ev3BQUb8picNL8qML6j9AY-PS6idgOUb~WQG8~JoXk77RydBlIV1NL0B4xV0tY3SLOEvYym8jXLt4iZkihrRaQWFTwsF8myXMqJSRESx8ujAPvBBEez1iBhZk8w__', title: 'Introducing Poketo', category: 'new additions'},
        ]
      }
    }
  }
</script>

<template>
  <header class="container">
    <p class="header-extra-text">BUSINESS thoughts 💭</p>
    <h1 class="header-text">For founders on building, growing, and selling your brand</h1>
  </header>
  <section class="container" id="press">
    <h2 class="section-text">Explore the brands joining Pattern Brands, the sales process & the founders behind them.👇🏽</h2>
    <AppCards :cards="cards" />
  </section>

</template>

<style>

</style>