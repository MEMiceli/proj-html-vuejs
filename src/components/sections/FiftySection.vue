<template>
    <div class="container">
        <div class="row justify-content-around">
            <div class="col-5">
                <div class="boximage d-flex justify-content-center">
                    <img src="../../assets/img/26.jpeg" alt="">
                </div>
                <h6>Julia Aann <span>-COO Sofbox</span></h6>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatibus dolores maiores, sequi labore quos aperiam, doloremque consequuntur earum velit expedita, accusamus quibusdam tempore? Magni, doloremque vel totam repellendus dolorem numquam!</p>
            </div>
            <div class="col-5">
                <div class="boximage d-flex justify-content-center">
                    <img src="../../assets/img/27.jpeg" alt="">
                </div>
                <h6>Mac Znder <span>- Manager Sofbox</span></h6>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatibus dolores maiores, sequi labore quos aperiam, doloremque consequuntur earum velit expedita, accusamus quibusdam tempore? Magni, doloremque vel totam repellendus dolorem numquam!</p>
            </div>
        </div>
        <div class="text-center">
            <i class="fas fa-square blue"></i> <i class="fas fa-square black"></i>
        </div>
    </div>
  
</template>

<script>
export default {
    name: 'FiftySection'

}
</script>

<style scoped lang="scss">
// need effect scroll card
img{
    border-radius: 50%;
    width:3.1875rem;
}
p{
    color:var(--quinary-colortext);
    font-size: smaller;
}
.col-5{
    padding: 2rem;
    background-image: url("../../assets/img/absent.png");
    background-repeat: no-repeat;
    background-size: 20%;
    background-position: center;
     box-shadow: 0px 0px 20px 5px var(--quinary-color);
    h5{
        text-align: center;
    }
    span{
        color:var(--quinary-colortext);
    }
}
.text-center{
    padding: 2rem;
    font-size: 1rem;
    .blue{
    color:var(--tertiary-colortext);
    }
    .black{
    color:var(--septenary-colortext);
    }
}


</style>