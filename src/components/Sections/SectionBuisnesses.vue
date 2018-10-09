<template>
    <section class="buisness div-grey ">
        
            <div class="block_left">
                <h1 class="h1 h1__heading_accent">More business, more often.</h1>
                <ul class="h4 h4__accent">
                    <li>Free to join with no set up fees</li>
                    <li>Simple transaction process</li>
                    <li>User friendly administration portal</li>
                    <li>Extend the reach of your business</li>
                    <li>Extend the reach of your business</li>
                </ul>
                <button class="btn btn-pink btn-xl">REGISTER YOUR BUISNESS</button>
            </div>
            <div class="block_right container">
                <img class="img1" src="/static/img/business/mockups.png">
            </div>
     
    </section>
</template>

<style lang="scss" scoped>
.buisness {
display: flex;

}
.block_left {
    flex-grow: 1;
   flex-basis: 50%;
}
.block_right {
    flex-grow: 1;
    flex-basis: 50%;
    display: flex;
    background: linear-gradient(0deg, #E62343, #B5075B);
    justify-content: center;
   
}
.img1 {
    width: 50%;
    height: 50%;
    margin: 20px;
}



</style>
