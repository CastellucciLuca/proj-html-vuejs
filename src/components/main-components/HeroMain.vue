<script>
export default {
    name: 'HeroMain',
    data() {
        return {
            
        }
    },
}
</script>
<template>
    <section id="hero-main">
        <div class="wrapped-container d-flex position-relative">
            <div id="left-section">
                <h2 class="fw-bold">
                    Distant learning for further expansion
                </h2>

                <p>Learning is a life-long journey that in fact we never find the terminate stop. Stop searching, enjoy the process.</p>

                <button class="rounded py-3 px-5">
                    <font-awesome-icon icon="fa-solid fa-download" /> Download free guide
                </button>

                <p>Have more question? <span class="green fw-bold">Get free sample <font-awesome-icon icon="fa-solid fa-right-long"/></span> </p>
            </div>
            <div class="about-me-imgs position-relative text-center">
                <div id="my-circle" class="rounded-pill position-absolute"></div>
                <img src="../../assets/img/maxcoach-shape-08.png" alt="" class="first-bg">
                <img src="../../assets/img/maxcoach-shape-08.png" alt="" class="second-bg">
                <img src="../../assets/img/maxcoach-shape-07-150x150.png" alt="" class="third-bg">
                <img src="../../assets/img/maxcoach-shape-02.png" alt="" class="fourth-bg">
                <img src="../../assets/img/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg" alt="about-me" class="about-me position-relative">
            </div>
        </div>
        <div class="wrapped-container me-5 p-5">
            <img src="../../assets/img/client-logo-01.png" alt="client-logo1" class="client m-5">
            <img src="../../assets/img/client-logo-02.png" alt="client-logo2" class="client m-5">
            <img src="../../assets/img/client-logo-03.png" alt="client-logo3" class="client m-5">
            <img src="../../assets/img/client-logo-04.png" alt="client-logo4" class="client m-5">
            <img src="../../assets/img/client-logo-05.png" alt="client-logo5" class="client m-5">
            <img src="../../assets/img/client-logo-06.png" alt="client-logo6" class="client m-5">
        </div>

        <div class="lateral-options position-absolute text-center fs-4 rounded-2 shadow-lg">
            <font-awesome-icon icon="fa-solid fa-ruler" />
            <font-awesome-icon icon="fa-solid fa-life-ring" />
            <font-awesome-icon icon="fa-solid fa-book" />
            <font-awesome-icon icon="fa-solid fa-cart-shopping" />

        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/variables' as *;
    section#hero-main{
        padding-top: 50px;
    }
    #left-section {
        width: 45%;
        height: 45%;
        margin: 0 5rem;
        padding: 8rem;
        h2{
            color:$GunPowder;
            font-size: 3rem;
        }
        p{
            color: $ShadyLady;
            font-weight: 700;
        }
        button {
                background-color: $Basketball ;
                color: white;
                font-weight: 700;
                width: 280px;
                margin-bottom:2rem;
                border: none;
            }
            button:hover{
                background-color: $GunPowder;
                color: white;
            }
        .green{
            color: $JungleGreen;
            border-bottom: 1px solid $ShadyLady;
            cursor: pointer;
        }
        
    }
    #my-circle{
        height: 80px;
        width: 80px;
        border: 10px solid $first-circle;
        left: -10%;
        top: 59%;
        z-index: 1;
    }
    img.first-bg{
        position: absolute;
        top: 25%;
        left: -5%;
        transform: translateX(-40%);

    }
    img.second-bg{
        position: absolute;
        top: 50%;
        left: -5%;
        transform: translateX(-40%);
    }
    img.third-bg{
        position: absolute;
        bottom: 0;
        right: 5%;
        transform: translateY(-35%);
    }
    img.fourth-bg{
        position: absolute;
        right: 0;
        top: 20%;
        transform: translateX(100%);
    }
    img.about-me{
        border-radius: 50%;
        width: 550px;
        height: 550px;
        }
    .lateral-options {
        height: 145px;
        width: 35px;
        right: 0;
        top: 20%;
        cursor: pointer;
    }
</style>