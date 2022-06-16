<template>
  <div class="container-fluid">
      <div class="container">
          <div class="row">
          <div class="col-6 textbox">
              <h1>The biggest platform for your growth.</h1>
              <p>There are many variants of paassages of Lorem Ipsum available but the majority have suffered alteration in fome form</p>
              <button type="button" class="btn btn-primary">Read More</button>
          </div>
          <div class="col-6 p-5">
              <div class="imgbox position-relative">
                  <img src="../../assets/img/27-1.png" alt="">
              </div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'BaseRunner',

}
</script>

<style scoped lang="scss">
.container-fluid{
    background-color: var(--secondary-color);
    max-width: 1200px !important;
    height: 24.5rem;
    
}
p{
    color:var(--quinary-colortext);
}
img{
    max-width: 130%;
    position: absolute;
    top: 0.5rem;
}
.textbox{
    margin-top: 3rem;
}
</style>