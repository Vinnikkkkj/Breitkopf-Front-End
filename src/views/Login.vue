<template>
  <main>
    <Splash />
    <div class="login">
      <div class="header-login">
        <div class="esquerda-login">
          <img
            src="../assets/AutoMe_Positivo 01.png"
            width="30"
            height="30"
            alt="aa"
          />
        </div>
        <div class="direita-login">
          <svg
            width="30"
            height="30"
            viewBox="0 0 40 39"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M35 2.5C35.663 2.5 36.2989 2.76339 36.7678 3.23223C37.2366 3.70107 37.5 4.33696 37.5 5V25C37.5 25.663 37.2366 26.2989 36.7678 26.7678C36.2989 27.2366 35.663 27.5 35 27.5H11.035C9.70903 27.5003 8.43746 28.0273 7.5 28.965L2.5 33.965V5C2.5 4.33696 2.76339 3.70107 3.23223 3.23223C3.70107 2.76339 4.33696 2.5 5 2.5H35ZM5 0C3.67392 0 2.40215 0.526784 1.46447 1.46447C0.526784 2.40215 0 3.67392 0 5L0 36.9825C5.25372e-05 37.2298 0.0734815 37.4716 0.210993 37.6772C0.348505 37.8828 0.543917 38.043 0.772498 38.1374C1.00108 38.2319 1.25255 38.2565 1.49509 38.208C1.73763 38.1595 1.96033 38.0401 2.135 37.865L9.2675 30.7325C9.73623 30.2636 10.372 30.0001 11.035 30H35C36.3261 30 37.5979 29.4732 38.5355 28.5355C39.4732 27.5979 40 26.3261 40 25V5C40 3.67392 39.4732 2.40215 38.5355 1.46447C37.5979 0.526784 36.3261 0 35 0L5 0Z"
              fill="white"
            />
            <path
              d="M7.5 8.75C7.5 8.41848 7.6317 8.10054 7.86612 7.86612C8.10054 7.6317 8.41848 7.5 8.75 7.5H31.25C31.5815 7.5 31.8995 7.6317 32.1339 7.86612C32.3683 8.10054 32.5 8.41848 32.5 8.75C32.5 9.08152 32.3683 9.39946 32.1339 9.63388C31.8995 9.8683 31.5815 10 31.25 10H8.75C8.41848 10 8.10054 9.8683 7.86612 9.63388C7.6317 9.39946 7.5 9.08152 7.5 8.75ZM7.5 15C7.5 14.6685 7.6317 14.3505 7.86612 14.1161C8.10054 13.8817 8.41848 13.75 8.75 13.75H31.25C31.5815 13.75 31.8995 13.8817 32.1339 14.1161C32.3683 14.3505 32.5 14.6685 32.5 15C32.5 15.3315 32.3683 15.6495 32.1339 15.8839C31.8995 16.1183 31.5815 16.25 31.25 16.25H8.75C8.41848 16.25 8.10054 16.1183 7.86612 15.8839C7.6317 15.6495 7.5 15.3315 7.5 15ZM7.5 21.25C7.5 20.9185 7.6317 20.6005 7.86612 20.3661C8.10054 20.1317 8.41848 20 8.75 20H21.25C21.5815 20 21.8995 20.1317 22.1339 20.3661C22.3683 20.6005 22.5 20.9185 22.5 21.25C22.5 21.5815 22.3683 21.8995 22.1339 22.1339C21.8995 22.3683 21.5815 22.5 21.25 22.5H8.75C8.41848 22.5 8.10054 22.3683 7.86612 22.1339C7.6317 21.8995 7.5 21.5815 7.5 21.25Z"
              fill="white"
            />
          </svg>
        </div>
      </div>
      <section>
        <router-link to="/about">
          <div class="botão-login">
            <div class="esquerda-botão">
              <svg
                width="38"
                height="38"
                viewBox="0 0 38 38"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M26.125 28.5625C26.125 28.9767 26.4608 29.3125 26.875 29.3125C27.2892 29.3125 27.625 28.9767 27.625 28.5625H26.125ZM22.5105 22.9375V22.1875V22.9375ZM15.4895 22.9375V22.1875V22.9375ZM11.125 27.0447H10.375H11.125ZM10.375 28.5625C10.375 28.9767 10.7108 29.3125 11.125 29.3125C11.5392 29.3125 11.875 28.9767 11.875 28.5625H10.375ZM36.25 19C36.25 28.5269 28.5269 36.25 19 36.25V37.75C29.3553 37.75 37.75 29.3553 37.75 19H36.25ZM19 36.25C9.47309 36.25 1.75 28.5269 1.75 19H0.25C0.25 29.3553 8.64466 37.75 19 37.75V36.25ZM1.75 19C1.75 9.47309 9.47309 1.75 19 1.75V0.25C8.64466 0.25 0.25 8.64466 0.25 19H1.75ZM19 1.75C28.5269 1.75 36.25 9.47309 36.25 19H37.75C37.75 8.64466 29.3553 0.25 19 0.25V1.75ZM27.625 28.5625V27.0447H26.125V28.5625H27.625ZM27.625 27.0447C27.625 25.7413 27.0744 24.5012 26.1107 23.5943L25.0827 24.6867C25.756 25.3203 26.125 26.1695 26.125 27.0447H27.625ZM26.1107 23.5943C25.1485 22.6888 23.8527 22.1875 22.5105 22.1875V23.6875C23.4833 23.6875 24.4078 24.0516 25.0827 24.6867L26.1107 23.5943ZM22.5105 22.1875H15.4895V23.6875H22.5105V22.1875ZM15.4895 22.1875C14.1473 22.1875 12.8515 22.6888 11.8893 23.5943L12.9173 24.6867C13.5922 24.0516 14.5167 23.6875 15.4895 23.6875V22.1875ZM11.8893 23.5943C10.9256 24.5012 10.375 25.7413 10.375 27.0447H11.875C11.875 26.1695 12.244 25.3203 12.9173 24.6867L11.8893 23.5943ZM10.375 27.0447V28.5625H11.875V27.0447H10.375ZM22.75 13.9375C22.75 16.0086 21.0711 17.6875 19 17.6875V19.1875C21.8995 19.1875 24.25 16.837 24.25 13.9375H22.75ZM19 17.6875C16.9289 17.6875 15.25 16.0086 15.25 13.9375H13.75C13.75 16.837 16.1005 19.1875 19 19.1875V17.6875ZM15.25 13.9375C15.25 11.8664 16.9289 10.1875 19 10.1875V8.6875C16.1005 8.6875 13.75 11.038 13.75 13.9375H15.25ZM19 10.1875C21.0711 10.1875 22.75 11.8664 22.75 13.9375H24.25C24.25 11.038 21.8995 8.6875 19 8.6875V10.1875Z"
                  fill="#69696B"
                />
              </svg>
            </div>
            <div class="meio-botão">
              <h1>AutoMe Breitkopf</h1>
              <p>***.***.**9-83</p>
            </div>
            <div class="direita-botão">
              <svg width="24" height="24" viewBox="0 0 19 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M15.81 2.47C15.73 2.47 15.65 2.45 15.58 2.41C13.66 1.42 12 1 10.01 1C8.02999 1 6.14999 1.47 4.43999 2.41C4.19999 2.54 3.89999 2.45 3.75999 2.21C3.69762 2.09305 3.68363 1.95629 3.72103 1.82913C3.75843 1.70197 3.84423 1.59457 3.95999 1.53C5.81999 0.52 7.85999 0 10.01 0C12.14 0 14 0.47 16.04 1.52C16.29 1.65 16.38 1.95 16.25 2.19C16.2104 2.27336 16.1482 2.34387 16.0703 2.3934C15.9925 2.44294 15.9023 2.46949 15.81 2.47V2.47ZM1.49999 7.72C1.40781 7.72086 1.3172 7.69617 1.2382 7.64866C1.1592 7.60116 1.0949 7.5327 1.05243 7.45088C1.00997 7.36906 0.991001 7.27708 0.99763 7.18514C1.00426 7.09319 1.03623 7.00488 1.08999 6.93C2.07999 5.53 3.33999 4.43 4.83999 3.66C7.97999 2.04 12 2.03 15.15 3.65C16.65 4.42 17.91 5.51 18.9 6.9C18.9384 6.95374 18.9657 7.01455 18.9804 7.07891C18.9952 7.14328 18.997 7.20993 18.9859 7.27501C18.9747 7.34009 18.9508 7.40232 18.9154 7.4581C18.8801 7.51388 18.8341 7.56211 18.78 7.6C18.55 7.76 18.24 7.71 18.08 7.48C17.2043 6.24038 16.041 5.23156 14.69 4.54C11.82 3.07 8.14999 3.07 5.28999 4.55C3.92999 5.25 2.78999 6.25 1.88999 7.51C1.80999 7.65 1.65999 7.72 1.49999 7.72V7.72ZM7.74999 19.79C7.68441 19.7908 7.6194 19.7779 7.55912 19.752C7.49884 19.7262 7.44463 19.688 7.39999 19.64C6.52999 18.77 6.05999 18.21 5.38999 17C4.69999 15.77 4.33999 14.27 4.33999 12.66C4.33999 9.69 6.87999 7.27 9.99999 7.27C13.12 7.27 15.66 9.69 15.66 12.66C15.66 12.94 15.44 13.16 15.16 13.16C14.88 13.16 14.66 12.94 14.66 12.66C14.66 10.24 12.57 8.27 9.99999 8.27C7.42999 8.27 5.33999 10.24 5.33999 12.66C5.33999 14.1 5.65999 15.43 6.26999 16.51C6.90999 17.66 7.34999 18.15 8.11999 18.93C8.30999 19.13 8.30999 19.44 8.11999 19.64C8.00999 19.74 7.87999 19.79 7.74999 19.79ZM14.92 17.94C13.73 17.94 12.68 17.64 11.82 17.05C10.33 16.04 9.43999 14.4 9.43999 12.66C9.43999 12.38 9.65999 12.16 9.93999 12.16C10.22 12.16 10.44 12.38 10.44 12.66C10.44 14.07 11.16 15.4 12.38 16.22C13.09 16.7 13.92 16.93 14.92 16.93C15.16 16.93 15.56 16.9 15.96 16.83C16.23 16.78 16.49 16.96 16.54 17.24C16.59 17.51 16.41 17.77 16.13 17.82C15.56 17.93 15.06 17.94 14.92 17.94V17.94ZM12.91 20C12.87 20 12.82 19.99 12.78 19.98C11.19 19.54 10.15 18.95 9.05999 17.88C8.36927 17.198 7.82157 16.385 7.44896 15.4887C7.07634 14.5923 6.88631 13.6307 6.88999 12.66C6.88999 11.04 8.26999 9.72 9.96999 9.72C11.67 9.72 13.05 11.04 13.05 12.66C13.05 13.73 13.98 14.6 15.13 14.6C16.28 14.6 17.21 13.73 17.21 12.66C17.21 8.89 13.96 5.83 9.95999 5.83C7.11999 5.83 4.51999 7.41 3.34999 9.86C2.95999 10.67 2.75999 11.62 2.75999 12.66C2.75999 13.44 2.82999 14.67 3.42999 16.27C3.52999 16.53 3.39999 16.82 3.13999 16.91C2.87999 17.01 2.58999 16.87 2.49999 16.62C2.01813 15.3553 1.77076 14.0134 1.76999 12.66C1.76999 11.46 1.99999 10.37 2.44999 9.42C3.77999 6.63 6.72999 4.82 9.95999 4.82C14.51 4.82 18.21 8.33 18.21 12.65C18.21 14.27 16.83 15.59 15.13 15.59C13.43 15.59 12.05 14.27 12.05 12.65C12.05 11.58 11.12 10.71 9.96999 10.71C8.81999 10.71 7.88999 11.58 7.88999 12.65C7.88999 14.36 8.54999 15.96 9.75999 17.16C10.71 18.1 11.62 18.62 13.03 19.01C13.3 19.08 13.45 19.36 13.38 19.62C13.33 19.85 13.12 20 12.91 20V20Z" fill="black"/>
</svg>

            </div>
          </div>
        </router-link>
      </section>
    </div>
    <div class="arrow"></div>
  </main>
</template>

<script>
import Splash from "../components/Splash.vue";
export default {
  components: { Splash },
};
</script>

<style scoped>
@media screen and (min-width: 300px) and (max-width: 768px) {
  main {
    width: 100%;
    height: 100vh;
    background: #88bce7;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .login {
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 10px;
    gap: 10px;
  }
  .header-login {
    width: 100%;
    height: 10.7vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: baseline;
    padding: 12px 0px;
    animation-duration: 1s;
    animation-iteration-count: 1;
    animation-name: aparecer;
    animation-delay: 2.5s;
  }
  .header-login .esquerda-login {
    width: 54px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .header-login .esquerda-login img {
    width: 40px;
    height: 40px;
  }
  .header-login .direita-login {
    width: 54px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section {
    width: 100%;
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    animation-duration: 1.5s;
    animation-iteration-count: 1;
    animation-name: aparecer;
    animation-delay: 2.5s;
  }
  section a {
    width: 100%;
    text-decoration: none;
    color: #fff;
  }
  section a .botão-login {
    width: 100%;
    height: 45px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 2px 0px;
    gap: 4px;
    background: #ebebf0;
    box-shadow: 0px 4px 8px rgba(52, 87, 140, 0.12);
    border-radius: 8px;
  }
  section a .botão-login .direita-botão {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section a .botão-login .esquerda-botão {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section a .botão-login .meio-botão {
    width: 60%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    background: #ffffff;
    padding: 4px 4px;
  }
  section a .botão-login .meio-botão h1 {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    color: #69696b;
  }
  section a .botão-login .meio-botão p {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 20px;
    color: #ababb5;
  }
  .arrow,
  .arrow:before {
    position: absolute;
    left: 50%;
  }
  .arrow {
    width: 40px;
    height: 40px;
    bottom: 5%;
    margin: -20px 0 0 -20px;
    -webkit-transform: rotate(45deg);
    border-left: none;
    border-top: none;
    border-right: 2px #fff solid;
    border-bottom: 2px #fff solid;
  }
  .arrow:before {
    content: "";
    width: 20px;
    height: 20px;
    top: 50%;
    margin: -10px 0 0 -10px;
    border-left: none;
    border-top: none;
    border-right: 1px #fff solid;
    border-bottom: 1px #fff solid;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-name: seta;
  }
  @keyframes aparecer {
    0% {
      opacity: 0;
      transform: translateY(-50px);
    }
    100% {
      opacity: 1;
    }
  }
  @keyframes seta {
    0% {
      opacity: 1;
    }
    50% {
      opacity: 0.1;
    }
    100% {
      opacity: 0;
      transform: translate(-5px, -5px);
    }
  }
}
@media screen and (min-width: 768px) and (max-width: 1900px) {
  main {
    width: 100%;
    height: 100vh;
    background: #88bce7;

    display: flex;
    justify-content: center;
    align-items: center;
  }
  .login {
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px 100px 0px 100px;
    gap: 10px;
  }
  .header-login {
    width: 100%;
    height: 10.7vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: baseline;
    padding: 12px 0px;
    animation-duration: 1s;
    animation-iteration-count: 1;
    animation-name: aparecer;
    animation-delay: 2.5s;
  }
  .header-login .esquerda-login {
    width: 40px;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .header-login .esquerda-login img {
    width: 40px;
    height: 40px;
  }
  .header-login .direita-login {
    width: 40px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section {
    width: 100%;
    height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    animation-duration: 1.5s;
    animation-iteration-count: 1;
    animation-name: aparecer;
    animation-delay: 2.5s;
  }
  section a {
    width: 50vw;
    text-decoration: none;
    color: #fff;
  }
  section a .botão-login {
    width: 100%;
    height: 45px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 2px 0px;
    gap: 8px;
    background: #ebebf0;
    box-shadow: 0px 4px 8px rgba(52, 87, 140, 0.12);
    border-radius: 8px;
  }
  section a .botão-login .direita-botão {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section a .botão-login .esquerda-botão {
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  section a .botão-login .meio-botão {
    width: 60%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    background: #ffffff;
    padding: 4px 4px;
  }
  section a .botão-login .meio-botão h1 {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    color: #69696b;
  }
  section a .botão-login .meio-botão p {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 20px;
    color: #ababb5;
  }
  .arrow,
  .arrow:before {
    position: absolute;
    left: 50%;
  }
  .arrow {
    width: 40px;
    height: 40px;
    bottom: 5%;
    margin: -20px 0 0 -20px;
    -webkit-transform: rotate(45deg);
    border-left: none;
    border-top: none;
    border-right: 2px #fff solid;
    border-bottom: 2px #fff solid;
  }
  .arrow:before {
    content: "";
    width: 20px;
    height: 20px;
    top: 50%;
    margin: -10px 0 0 -10px;
    border-left: none;
    border-top: none;
    border-right: 1px #fff solid;
    border-bottom: 1px #fff solid;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-name: seta;
  }
  @keyframes aparecer {
    0% {
      opacity: 0;
      transform: translateY(-50px);
    }
    100% {
      opacity: 1;
    }
  }
  @keyframes seta {
    0% {
      opacity: 1;
    }
    50% {
      opacity: 0.1;
    }
    100% {
      opacity: 0;
      transform: translate(-5px, -5px);
    }
  }
}
</style>
