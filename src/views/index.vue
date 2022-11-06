<template>
  <main>
    <Header />
    <div class="texto-resumo">
      <h3>bem-vindo a plataforma Breitkopf</h3>
      <h4>Informação 1</h4>
      <p>Texto longo com mais detalhes</p>
    </div>
    <div class="hotkey">
      <div class="hotkey-card"  v-for="item in carrosSemPlaca" :key="item.placa">
        <div class="hotkey-photo">
          <svg
            width="25"
            height="25"
            viewBox="0 0 25 25"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M0.978638 23.6205H23.62V0.979095H0.978638V23.6205Z"
              stroke="#111111"
              stroke-width="1.78748"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M10.5118 15.2789L6.34106 11.1081L0.978638 17.6622"
              stroke="#111111"
              stroke-width="1.78748"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M23.62 17.6622L15.8743 8.72482L8.72437 17.6622"
              stroke="#111111"
              stroke-width="1.78748"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <circle
              cx="8.12854"
              cy="5.7457"
              r="1.78748"
              stroke="#111111"
              stroke-width="1.78748"
            />
          </svg>
        </div>
        <div class="texto-hotkey">
          <p>Placa:{{item.placa}}</p>
        </div>
      </div>
    </div>
    <div class="footer-index">
      <div class="esquerda-footer">
        <div class="avancar">
          <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="1" y="1" width="34" height="34" rx="7" fill="white"/>
<path d="M15 24L21 18L15 12" stroke="#111111" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
<rect x="1" y="1" width="34" height="34" rx="7" stroke="#111111" stroke-width="2" stroke-linecap="round"/>
</svg>

        </div>
        <div class="avancar">
          <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="1" y="1" width="34" height="34" rx="7" fill="white"/>
<path d="M15 24L21 18L15 12" stroke="#111111" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
<rect x="1" y="1" width="34" height="34" rx="7" stroke="#111111" stroke-width="2" stroke-linecap="round"/>
</svg>

        </div>
      </div>
      <div class="meio-footer">
        <svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0.978638 23.6205H23.62V0.979126H0.978638V23.6205Z" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M10.5118 15.2789L6.34106 11.1082L0.978638 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M23.62 17.6622L15.8743 8.72485L8.72437 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<circle cx="8.12854" cy="5.74573" r="1.78748" stroke="#111111" stroke-width="1.78748"/>
</svg>

      </div>
      <div class="direita-footer">
        <div class="avancard">
          <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="1" y="1" width="34" height="34" rx="7" fill="white"/>
<path d="M15 24L21 18L15 12" stroke="#111111" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
<rect x="1" y="1" width="34" height="34" rx="7" stroke="#111111" stroke-width="2" stroke-linecap="round"/>
</svg>

        </div>
        <div class="avancard">
          <svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="1" y="1" width="34" height="34" rx="7" fill="white"/>
<path d="M15 24L21 18L15 12" stroke="#111111" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
<rect x="1" y="1" width="34" height="34" rx="7" stroke="#111111" stroke-width="2" stroke-linecap="round"/>
</svg>

        </div>
      </div>
    </div>
  </main>
</template>

<script>
import Header from "../components/Header-index.vue";

export default {
  components: { Header},
  mounted: function pegaId() {
    for(let elemento of this.carrosSemPlaca){
  this.idCarros.push(elemento.id);
}
  },
  data() {
    return {
      idCarros: [],
      carrosSemPlaca: [
        { id: 90, placa: "AHW9I98" },

        { id: 1270, placa: "AVO8F43" },

        { id: 1229, placa: "BAO4G47" },

        { id: 1220, placa: "BAS9G90" },

        { id: 217, placa: "BCR4A30" },

        { id: 103, placa: "FIH5G64" },

        { id: 1235, placa: "FZD4A28" },

        { id: 76, placa: "IWP1B50" },

        { id: 1219, placa: "IYH5H49" },

        { id: 108, placa: "IZN3F59" },

        { id: 100, placa: "LRJ7G90" },

        { id: 1256, placa: "MKV8D10" },

        { id: 1222, placa: "MLS9A01" },

        { id: 81, placa: "PWZ7J63" },

        { id: 107, placa: "QGU8C16" },

        { id: 77, placa: "QHM1F61" },

        { id: 1261, placa: "QHM4H87" },

        { id: 1244, placa: "QHW9D59" },

        { id: 1267, placa: "QID7J10" },

        { id: 1227, placa: "QII9A37" },

        { id: 1263, placa: "QIV3E31" },

        { id: 80, placa: "QIX3G32" },

        { id: 1246, placa: "QJA9B61" },

        { id: 1255, placa: "QJD7E58" },

        { id: 1264, placa: "QJE8A07" },

        { id: 214, placa: "QJF8G20" },

        { id: 102, placa: "QJH9A21" },

        { id: 106, placa: "QJI0D70" },

        { id: 1221, placa: "QJL1B72" },

        { id: 82, placa: "QJN7F02" },

        { id: 1252, placa: "QJO0F38" },

        { id: 91, placa: "QJR4A44" },

        { id: 94, placa: "QJT0A71" },

        { id: 1247, placa: "QJT7J16" },

        { id: 208, placa: "QJT9H20" },

        { id: 1238, placa: "QJX2I09" },

        { id: 84, placa: "QJY0D40" },

        { id: 1218, placa: "QJZ7D06" },

        { id: 1233, placa: "QTK4F10" },

        { id: 86, placa: "QTK7E86" },

        { id: 92, placa: "QTM0H60" },

        { id: 1253, placa: "QUA2C88" },

        { id: 1265, placa: "QYX0F31" },

        { id: 1245, placa: "RAB6E64" },

        { id: 85, placa: "RAE4B32" },

        { id: 1223, placa: "RAF3G56" },

        { id: 1232, placa: "RAG8H15" },

        { id: 105, placa: "RAI0A85" },

        { id: 216, placa: "RDS4J86" },

        { id: 1251, placa: "RDS8B78" },

        { id: 1234, placa: "RDS8D80" },

        { id: 1242, placa: "RDT8C07" },

        { id: 89, placa: "RDT9E10" },

        { id: 1230, placa: "RDT9J69" },

        { id: 95, placa: "RDU6A60" },

        { id: 215, placa: "RDU7G70" },

        { id: 98, placa: "RDW7J77" },

        { id: 213, placa: "RDY3G20" },

        { id: 93, placa: "RDY4I85" },

        { id: 1243, placa: "RDZ6E71" },

        { id: 83, placa: "REB4B51" },

        { id: 1241, placa: "RJK0B16" },

        { id: 78, placa: "RKW0G98" },

        { id: 99, placa: "RKW7H21" },

        { id: 88, placa: "RKW9C07" },

        { id: 1258, placa: "RKX1G85" },

        { id: 1231, placa: "RKX4H79" },

        { id: 87, placa: "RKX9J67" },

        { id: 1260, placa: "RKY4B98" },

        { id: 1236, placa: "RKZ4B68" },

        { id: 104, placa: "RLD7A56" },

        { id: 101, placa: "RLG1J67" },

        { id: 79, placa: "RLG6J28" },

        { id: 212, placa: "RLI8C91" },

        { id: 97, placa: "RLJ2B20" },

        { id: 1249, placa: "RLM2F47" },

        { id: 1269, placa: "RLM3A00" },

        { id: 1226, placa: "RLN6B43" },

        { id: 1239, placa: "RLP3H00" },

        { id: 1259, placa: "RXK8J88" },

        { id: 1217, placa: "RXM8F72" },

        { id: 1257, placa: "RXN9B94" },

        { id: 1248, placa: "RXO3H71" },

        { id: 1254, placa: "RXQ8D58" },
      ],
    };
  },
};
</script>

<style scoped>
@media all and (min-width: 300px) and (max-width: 768px) {
  main {
    width: 100%;
    height: 100vh;
    display: flex;
    background: #88bce7;
    position: absolute;
    flex-direction: column;
    align-items: center;
    overflow: scroll;
    gap: 20px;
    padding: 0 20px 0 20px;
  }
  .texto-resumo {
    width: 100%;
    height: 96px;
    display: flex;
    background: #ebebf0;
    border-radius: 4px;
    padding: 4px 7px;
    margin-top: 100px;
    gap: 3px;
    flex-direction: column;
    align-items: flex-start;
  }
  .texto-resumo h3 {
    font-family: "Open Sans";
    font-style: normal;
    white-space: nowrap;
    font-weight: 600;
    color: #111111;

    font-size: 1em;
    line-height: 32px;
  }
  .texto-resumo h4 {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    color: #111111;
    white-space: nowrap;
    font-size: 1em;
    line-height: 28px;
  }
  .texto-resumo p {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 500;
    color: #111111;
    white-space: nowrap;
    font-size: 1em;
    line-height: 26px;
  }
  .hotkey {
    display: flex;
    justify-content: center;
    padding: 0px 0px 12px 0px;
    gap: 12px;
    flex-wrap: wrap;
    width: 100%;
    overflow: scroll;
    max-height: 62vh;
  }
  .hotkey-card {
    width: 110px;
    height: 172px;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 6px 6px 0px;
    
    gap: 10px;
    background: #ebebf0;
    box-shadow: 0px 1px 2px rgba(52, 87, 140, 0.14);
    border-radius: 4px;
    transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1);
  }
  .hotkey-card:hover {
    transform: translateY(-10px);
  }
  .hotkey-photo {
    width: 104.67px;
    height: 128px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #ebebf0;
    border: 2.4px solid #c3c3fd;
    border-radius: 4.8px;
  }
  .texto-hotkey {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .texto-hotkey p {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 20px;
  }
  .footer-index {
    width: 100%;
    height: 50px;
    display: flex;
    position: fixed;
    bottom: 0;
    justify-content: space-evenly;
    background: #ebebf0;
    align-items: center;
  }
  .esquerda-footer {
    display: flex;
    height: 100%;
    align-items: center;
    gap: 10px;
  }
  .direita-footer {
    display: flex;
    height: 100%;
    align-items: center;
    gap: 10px;
  }
  .avancar {
    transform: rotate(180deg);
    display: flex;
    align-items: center;
    
    justify-content: center;
  }
  .avancard {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .meio-footer {
    width: 144px;
    height: 78px;
    background: #ebebf0;
    border: 2.4px solid #d5d5de;
    border-radius: 4.8px;
    display: flex;
    align-items: center;
    justify-content: center;
}
}
</style>
