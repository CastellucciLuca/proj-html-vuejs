<script>
export default {
    name: 'IndexHeader',
    data: function(){
    return{
    searchBar: ['Home' , 'Pages' , 'Courses' , 'Feautures' , 'Blog' , 'Shop']
    }
    }
}
</script>
<template>
<header>
    <div class="container p-2 d-flex align-items-center ">      
        <div class="row row-cols-auto align-items-center justify-content-between container-fluid p-0">
            <!-- logo section -->
            <div class="col">
                <img class="img-logo" src="../assets/img/dark-logo.png" alt="logo">
            </div>
            <div class="col">
                <ul class="d-flex m-0 align-items-center">
                <!-- CICLO GLI ELEMENTI IN HEADER IN UNA LISTA -->
                <li v-for="(element, index) in searchBar" :key="index" class="px-3">
                    <a href="#">
                    {{ element }}
                    <font-awesome-icon icon="fa-solid fa-chevron-down ms-1" />
                    </a>
                </li>
                <li class="px-3">
                    <a href="#">
                        <font-awesome-icon icon="fa-regular fa-circle-user" />
                    </a>
                </li>
                <li>
                    <div class="input-group">
                        <input type="text" class="form-control" placeholder="Search..." >
                        <span class="input-group-text" id="addon-wrapping">
                            <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
                        </span>
                    </div>
                </li>
                </ul>
            </div>
        </div>
    </div>
</header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
header{

    .img-logo{
    width: 150px;
    }
    li{
    list-style: none;
    a{
        text-decoration: none;
        color: $Edward;
        i{
            font-size: smaller;
        }
    }
    }
    .input-group{
        width: 70%;
        input, span{
        background-color: $HintOfRed;
        border: none;
        cursor: pointer;
        }
        input{
        font-size: 1.2rem;
        font-weight: 600;
        }
        span{
        color: $Basketball;
        }
    }
}
</style>
