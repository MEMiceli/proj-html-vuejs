<template>
  <header>
      <div class="container mt-2 mb-2">
          <div class="row align-items-center">
              <div class="col-4">
                  <div class="boxlogo">
                      <img src="../../assets/img/logo-2.png" alt="logo">
                  </div>
              </div>
              <div class="col-8 d-flex justify-content-end">
                  <ul>
                      <li v-for="(link, index) in links" :key="index"><a @click.prevent="onClickMenuItem(link)" :href="link.url" :class="{active : link.current}">{{link.text}}</a></li>
                      <!-- <li>About us</li>
                      <li>Feature</li>
                      <li>Testimonials</li>
                      <li>Contact us</li> -->
                      <li><i class="fa-solid fa-magnifying-glass"></i> <i class="fa-solid fa-cart-shopping"></i></li>
                      <li><button type="button" class="btn btn-primary">Get Started</button></li>
                  </ul> 
              </div>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name:'BaseHeader',
    data(){
        return{
            links: [
                {
                text:"Home",
                url: "#",
                },
                {
                text:"About us",
                url: "#",
                },
                {
                text:"Feature",
                url: "#",
                },
                {
                text:"Testimonials",
                url: "#",
                },
                {
                text:"contact Us",
                url: "#",
                },
            ]
        }
        
    }

}
</script>

<style scoped lang="scss">

ul {
    display:flex;
    align-items: center;
    gap:1.5rem;
    list-style-type: none; /* Remove bullets */
    padding: 0; /* Remove padding */
    margin: 0; /* Remove margins */
    font-size: smaller;
    a{
        text-decoration: none;
        color:var(--otonary-colortext);
    }
};
img{
    max-height: 2.375rem;
}
</style>