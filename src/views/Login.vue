<template>
  <main>
    <Splash/>
    <div class="login">
      <div class="header-login">
        <div class="esquerda-login">
          Logo
        </div>
        <div class="direita-login">
          <svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0.978638 23.6205H23.62V0.979095H0.978638V23.6205Z" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M10.5118 15.2789L6.34106 11.1081L0.978638 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M23.62 17.6622L15.8743 8.72482L8.72437 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<circle cx="8.12854" cy="5.7457" r="1.78748" stroke="#111111" stroke-width="1.78748"/>
</svg>
        </div>
      </div>
      <section>
        <router-link to="/about">
        <div class="botão-login">
          <div class="esquerda-botão">
            <svg width="38" height="38" viewBox="0 0 38 38" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M26.125 28.5625C26.125 28.9767 26.4608 29.3125 26.875 29.3125C27.2892 29.3125 27.625 28.9767 27.625 28.5625H26.125ZM22.5105 22.9375V22.1875V22.9375ZM15.4895 22.9375V22.1875V22.9375ZM11.125 27.0447H10.375H11.125ZM10.375 28.5625C10.375 28.9767 10.7108 29.3125 11.125 29.3125C11.5392 29.3125 11.875 28.9767 11.875 28.5625H10.375ZM36.25 19C36.25 28.5269 28.5269 36.25 19 36.25V37.75C29.3553 37.75 37.75 29.3553 37.75 19H36.25ZM19 36.25C9.47309 36.25 1.75 28.5269 1.75 19H0.25C0.25 29.3553 8.64466 37.75 19 37.75V36.25ZM1.75 19C1.75 9.47309 9.47309 1.75 19 1.75V0.25C8.64466 0.25 0.25 8.64466 0.25 19H1.75ZM19 1.75C28.5269 1.75 36.25 9.47309 36.25 19H37.75C37.75 8.64466 29.3553 0.25 19 0.25V1.75ZM27.625 28.5625V27.0447H26.125V28.5625H27.625ZM27.625 27.0447C27.625 25.7413 27.0744 24.5012 26.1107 23.5943L25.0827 24.6867C25.756 25.3203 26.125 26.1695 26.125 27.0447H27.625ZM26.1107 23.5943C25.1485 22.6888 23.8527 22.1875 22.5105 22.1875V23.6875C23.4833 23.6875 24.4078 24.0516 25.0827 24.6867L26.1107 23.5943ZM22.5105 22.1875H15.4895V23.6875H22.5105V22.1875ZM15.4895 22.1875C14.1473 22.1875 12.8515 22.6888 11.8893 23.5943L12.9173 24.6867C13.5922 24.0516 14.5167 23.6875 15.4895 23.6875V22.1875ZM11.8893 23.5943C10.9256 24.5012 10.375 25.7413 10.375 27.0447H11.875C11.875 26.1695 12.244 25.3203 12.9173 24.6867L11.8893 23.5943ZM10.375 27.0447V28.5625H11.875V27.0447H10.375ZM22.75 13.9375C22.75 16.0086 21.0711 17.6875 19 17.6875V19.1875C21.8995 19.1875 24.25 16.837 24.25 13.9375H22.75ZM19 17.6875C16.9289 17.6875 15.25 16.0086 15.25 13.9375H13.75C13.75 16.837 16.1005 19.1875 19 19.1875V17.6875ZM15.25 13.9375C15.25 11.8664 16.9289 10.1875 19 10.1875V8.6875C16.1005 8.6875 13.75 11.038 13.75 13.9375H15.25ZM19 10.1875C21.0711 10.1875 22.75 11.8664 22.75 13.9375H24.25C24.25 11.038 21.8995 8.6875 19 8.6875V10.1875Z" fill="#69696B"/>
</svg>

          </div>
          <div class="meio-botão">
            <h1>AutoMe Breitkopf</h1>
            <p>***.***.**9-83</p>
          </div>
          <div class="direita-botão">
            <svg width="25" height="26" viewBox="0 0 25 26" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M1.35864 24.3207H0.464905C0.464905 24.8143 0.865045 25.2144 1.35864 25.2144L1.35864 24.3207ZM24 24.3207V25.2144C24.4936 25.2144 24.8937 24.8143 24.8937 24.3207H24ZM24 1.67932H24.8937C24.8937 1.18572 24.4936 0.785583 24 0.785583V1.67932ZM1.35864 1.67932V0.785583C0.865045 0.785583 0.464905 1.18572 0.464905 1.67932L1.35864 1.67932ZM10.2599 16.6111C10.6089 16.9601 11.1748 16.9601 11.5238 16.6111C11.8728 16.2621 11.8728 15.6962 11.5238 15.3472L10.2599 16.6111ZM6.72107 11.8084L7.35304 11.1764C7.17449 10.9978 6.92874 10.9031 6.67655 10.9157C6.42436 10.9283 6.18925 11.047 6.02936 11.2424L6.72107 11.8084ZM0.666928 17.7965C0.354363 18.1785 0.41067 18.7416 0.792694 19.0541C1.17472 19.3667 1.73779 19.3104 2.05036 18.9284L0.666928 17.7965ZM23.3246 18.9478C23.6479 19.3208 24.2123 19.3611 24.5853 19.0378C24.9583 18.7145 24.9987 18.1501 24.6754 17.7771L23.3246 18.9478ZM16.2543 9.42505L16.9297 8.83971C16.7559 8.6392 16.502 8.52626 16.2367 8.53148C15.9714 8.5367 15.7221 8.65954 15.5564 8.86674L16.2543 9.42505ZM8.40648 17.8041C8.09813 18.1896 8.16062 18.752 8.54606 19.0603C8.93149 19.3687 9.49391 19.3062 9.80226 18.9207L8.40648 17.8041ZM1.35864 25.2144H24V23.4269H1.35864V25.2144ZM24.8937 24.3207V1.67932H23.1063V24.3207H24.8937ZM24 0.785583H1.35864V2.57306H24V0.785583ZM0.464905 1.67932V24.3207H2.25238V1.67932H0.464905ZM11.5238 15.3472L7.35304 11.1764L6.0891 12.4403L10.2599 16.6111L11.5238 15.3472ZM6.02936 11.2424L0.666928 17.7965L2.05036 18.9284L7.41278 12.3743L6.02936 11.2424ZM24.6754 17.7771L16.9297 8.83971L15.5789 10.0104L23.3246 18.9478L24.6754 17.7771ZM15.5564 8.86674L8.40648 17.8041L9.80226 18.9207L16.9522 9.98336L15.5564 8.86674ZM9.40228 6.44592C9.40228 6.93952 9.00214 7.33966 8.50855 7.33966V9.12714C9.98934 9.12714 11.1898 7.92672 11.1898 6.44592H9.40228ZM8.50855 7.33966C8.01495 7.33966 7.61481 6.93952 7.61481 6.44592H5.82733C5.82733 7.92672 7.02775 9.12714 8.50855 9.12714V7.33966ZM7.61481 6.44592C7.61481 5.95233 8.01495 5.55219 8.50855 5.55219V3.76471C7.02775 3.76471 5.82733 4.96513 5.82733 6.44592H7.61481ZM8.50855 5.55219C9.00214 5.55219 9.40228 5.95233 9.40228 6.44592H11.1898C11.1898 4.96513 9.98934 3.76471 8.50855 3.76471V5.55219Z" fill="#69696B"/>
</svg>
          </div>
        </div>
        </router-link>
      </section>
    </div>
    <div class="arrow">
      
    </div>
  </main>
</template>

<script>
import Splash from '../components/Splash.vue'
  export default {
    components: {Splash}
  }
</script>

<style scoped>
@media screen and (min-width: 300px) and (max-width: 768px) {
  main {
  width: 100%;
  height: 100vh;
  background: #88BCE7;
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
  height:  10.7vh;
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
gap: 8px;
background: #EBEBF0;
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
background: #FFFFFF;
padding: 4px 4px;
}
section  a .botão-login .meio-botão h1 {
  font-family: 'Open Sans';
  font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 24px;
  color: #69696B;
}
section a .botão-login  .meio-botão p {
  font-family: 'Open Sans';
font-style: normal;
font-weight: 400;
font-size: 12px;
line-height: 20px;
color: #ABABB5;
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
  background: #88BCE7;
  
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
  height:  10.7vh;
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
background: #EBEBF0;
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
background: #FFFFFF;
padding: 4px 4px;
}
section  a .botão-login .meio-botão h1 {
  font-family: 'Open Sans';
  font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 24px;
  color: #69696B;
}
section a .botão-login  .meio-botão p {
  font-family: 'Open Sans';
font-style: normal;
font-weight: 400;
font-size: 12px;
line-height: 20px;
color: #ABABB5;
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