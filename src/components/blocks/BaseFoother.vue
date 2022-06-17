<template>
    <div class="container-fluid">
        <hr>
        <div class="foother">
            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <div class="boximage">
                            <img src="../../assets/img/35.png" alt="">
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime itaque explicabo, ipsum quaerat quis sequi, corrupti nulla</p>
                        <p>Copirighr @2018 <a href="#">Sofbox</a></p>
                    </div>
                    <div class="col-3">
                        <h6>title list</h6>
                        <ul>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                        </ul>
                    </div>
                    <div class="col-3">
                        <h6>title list</h6>
                        <ul>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                        </ul>
                    </div>
                    <div class="col-3">
                        <h6>title list</h6>
                        <ul>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                            <li>insert value</li>
                        </ul>
                    </div>
                </div>
        </div>
        </div>
        
        
    </div>
</template>

<script>
export default {
    name: 'BaseFoother',
    data:

}
</script>

<style scoped lang="scss">

ul{
    list-style-type: none; /* Remove bullets */
    padding: 0; /* Remove padding */
    margin: 0; /* Remove margins */
    color: var(--quinary-colortext);
    line-height: 2.5rem;
}
p{
    color:var(--quinary-colortext);
    font-size: smaller;
}
a{
    text-decoration: none;
    color:var(--tertiary-colortext);
}
hr{ 
    color:var(--septenary-colorborder);
}
</style>