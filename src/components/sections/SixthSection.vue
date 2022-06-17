<template>
  <div class="container">
      <div class="text-center">
        <h4>Latest Posts</h4>
        <p>If you are planning on developing a product landing.</p>
      </div>
      <div class="row justify-content-between">
          <div class="col">
              <div class="boximage">
                  <img src="../../assets/img/19.jpg" alt="presentation">
                  <div class="timebox">
                      <p>November 28,2019</p>
                  </div>
              </div>
              <div class="boxtext">
                  <h5>Life Lack Meaning</h5>
                  <p>It is a long estabilished fact that a reader will be distracted by the readble</p>
              </div>

          </div>
          <div class="col">
              <div class="boximage">
                  <img src="../../assets/img/18.jpg" alt="presentation">
                  <div class="timebox">
                      <p>November 28,2019</p>
                  </div>
              </div>
              <div class="boxtext">
                  <h5>Life Lack Meaning</h5>
                  <p>It is a long estabilished fact that a reader will be distracted by the readble</p>
              </div>

          </div>
          <div class="col">
              <div class="boximage">
                  <img src="../../assets/img/17.jpg" alt="presentation">
                  <div class="timebox">
                      <p>November 28,2019</p>
                  </div>
              </div>
              <div class="boxtext">
                  <h5>Life Lack Meaning</h5>
                  <p>It is a long estabilished fact that a reader will be distracted by the readble</p>
              </div>

          </div>
      </div>
      
  </div>
</template>

<script>
export default {
    name:'SixthSection',

}
</script>

<style scoped lang="scss">
//need 1 position absolute//
.text-center{
    margin: 4rem auto;    
}
.col{
    border:.0625rem solid var( --secondary-colorborder);
    padding:.75rem;
    margin: 1rem;
    padding: 1rem 3rem  2rem 1rem;
    background-color:var(--primary-color);
    max-width: calc(30% - 2rem);
    img{
        width:100%;
    }
p{
    color:var(--quinary-colortext);
    font-size: smaller;
    }
}


</style>