<template>
    <div class="container-fluid">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-8">
                    <h4>Popular feature that your business needs</h4>
                    <div class="col-8">
                        <p>Faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser cras nice one boot fanny</p>
                    </div>
                    
                </div>
                <div class="col-4">
                    <button type="button" class="btn btn-primary">Explore more Feature</button>
                </div>
            </div>
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-3 hovercard">Customized Invoice
                        <div class="blue"><i class="fa-solid fa-chart-line"></i></div>
                    </div>
                    <div class="col-3 hovercard">Stock Management
                        <div class="red"><i class="fa-solid fa-paper-plane"></i></div>
                    </div>
                    <div class="col-3 hovercard">Receivable &amp; Payables
                        <div class="green hovercard"><i class="fa-solid fa-user-tie"></i></div>
                    </div>
                    <div class="col-3 hovercard">Manage Buyin
                        <div class="blue"><i class="fa-solid fa-user-tie"></i></div>
                    </div>
                    <div class="col-3 hovercard">Powerful &amp; Secure
                        <div class="red"><i class="fa-solid fa-cloud"></i></div>
                    </div>
                    <div class="col-3 hovercard">Fastest return Filing
                        <div class="green"><i class="fa-solid fa-user-tie"></i></div>
                    </div>
                    <div class="col-3 hovercard">Montly Detailed
                        <div class="blue"><i class="fa-solid fa-file-signature"></i></div>
                    </div>
                    <div class="col-3 hovercard">Product Management
                        <div class="red"><i class="fa-solid fa-thumbs-up"></i></div>
                    </div>
                </div>
            </div>
        </div>
    </div> 
</template>

<script>
export default {
    name: 'ThreeSection'

}
</script>

<style scoped lang="scss">
.container-fluid{
    padding-top: 5rem;
    background-image: url("../../assets/img/14.png");
    background-size: 25%;
    background-repeat: no-repeat;
    background-position: -12.5% 50%;
    
}
p{
    color:var(--quinary-colortext);
    font-size: smaller;
}
.col-3{
    margin: 1rem;
    padding: 1rem 3rem  2rem 1rem;
    background-color:var(--primary-color);
    box-shadow: 0px 0px 20px 5px var(--quinary-color);
    max-width: calc(25% - 2rem);
    div{
        font-size: 2rem;
    }
    .blue{
        color:var(--tertiary-colortext);

    }
    .red{
        color:var(--quaterny-colortext);
    }
    .green{
        color:var(--secondary-colortext);
    }
    &:hover{
        background-color: #6CDAC1 !important;
        color:white !important;
    }
}
.hovercard:hover{
    // background-color: var(--secondary--colortext) !important;
    // color: var(--primary--colortext) !important;
    // background-color: black;
}

</style>