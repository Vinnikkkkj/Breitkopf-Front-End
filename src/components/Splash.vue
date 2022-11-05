<template>
    <div>
        <div class="splash" v-if="splashCarregando">
            <h1 class="intro">
                <span class="logo"><img src="../assets/img-grupo-removebg-preview.png" alt="">
</span>
            </h1>
        </div>
    </div>
</template>

<script>
    export default {
    data: () => {
            return {
            splashCarregando: true
        }
    },
    mounted() {
        document.onreadystatechange = () => {
            if (document.readyState == "complete") {
                setInterval(() => {
                    this.splashCarregando = false;
                }, 2500);
                    
                
            }
        }
    },
    }
</script>

<style scoped>
@media screen and (min-width: 300px) and (max-width: 1900px) {
.splash {
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100vh;
    background-color: #88BCE7;
    transition: 1s;
}
.intro {
    display: flex;
    position: absolute;
    justify-content: center;
    align-items: center;
}
.logo {
    position: relative;
    display: inline-block;
    fill: #fff;
    bottom: 0;
    opacity: 1;
    animation: logo 2s forwards;
}
.logo img {
width: 100%;
height: 100%;
}

@keyframes logo  {
    0% {
        opacity: 0;
        transform: translateY(50px);
    }
    20% {
        opacity: 0.2;
        
    }
    100% {
        opacity: 1;
        transform:translateY(-5px)
    }
}
}

</style>