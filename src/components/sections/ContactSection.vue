<template>
    <div class="container">
        <div class="text-center">
            <h4>Contact Us</h4>
            <p>If you are planning on developing a product landing.</p>
            <div class="row">
                <div class="col">
                    <div class="boximage">
                        <img src="../../assets/img/StaticMapService.GetMapIma.png" alt="maps">
                    </div>
                </div>
                <div class="col">
                    <div class="imagebox">
                        <img src="../../assets/img/35.png" alt="logo">
                    </div>
                    <address>
                        <h6>9840 Shore St. Found Du Lac, WI 54935</h6>
                        <p>0 1223 456 789<br>
                        mailr@softbox.com</p> 
                    </address>
                    <div class="social">
                        <button type="button" class="btn btn-outline-primary btn-square-md" data-mdb-ripple-color="dark"><i class="fa-brands fa-facebook-f"></i></button>
                        <button type="button" class="btn btn-outline-primary btn-square-md" data-mdb-ripple-color="dark"><i class="fa-brands fa-twitter"></i></button>
                        <button type="button" class="btn btn-outline-primary btn-square-md" data-mdb-ripple-color="dark"><i class="fa-brands fa-github"></i></button>
                        <button type="button" class="btn btn-outline-primary btn-square-md" data-mdb-ripple-color="dark"><i class="fa-brands fa-instagram"></i></button>
                    </div>
                    <h5>Get in touch</h5>
                    <form>
                        <div class="row justify-content-between">
                            <div class="col-6">
                                <input type="text" class="form-control" placeholder="Your Name">
                            </div>
                            <div class="col-6">
                                <input type="text" class="form-control" placeholder="Your Email">
                            </div>
                            <div class="col-12">
                                <input type="text" class="form-control" placeholder="Your Subject">
                            </div>
                            <div class="col-12">
                                <!-- <input type="text" class="form-control" placeholder="Your Message"> -->
                                <textarea placeholder="Your Message" rows="10" cols="40"></textarea>
                            </div>
                            <div class="button"><button type="button" class="btn btn-primary">Send Message</button></div>
                            
                        </div>
                    </form>
                </div>
            </div>
      </div>
    </div>
  
</template>

<script>
export default {
    name:'ContactSection'

}
</script>

<style scoped lang="scss">
.text-center{
    margin: 4rem auto;
    p{
    color:var(--quinary-colortext);
    font-size: smaller;
    }
    a{
        text-decoration: none;
        color:inherit;
    
    }
}
.row{
    text-align: start;
}
.btn-square-md {
width: 30px;
height: 30px;
text-align: center;
padding: 0px;
font: size 1rem;
border: .0625rem solid var(--senary-colorborder) !important;
}
.col-6{
    max-width: calc(50% - 1rem);
}
// spacing
h6, h5{
    padding: 2rem 0;
}
.social{
    padding-top: 2rem;
}
.row{
    gap: 2rem;
}
// border
.form-control, textarea{
    border: .0625rem solid var(--secondary-colorborder);
}
</style>