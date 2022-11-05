<template>
  <div class="header-div">
    <div class="header-index">
      <div class="esquerda-header">
        <svg
          width="48"
          height="48"
          viewBox="0 0 48 48"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g clip-path="url(#clip0_914_951)">
            <circle
              cx="28"
              cy="24"
              r="17.25"
              fill="white"
              stroke="#D5D5DE"
              stroke-width="1.5"
              stroke-linecap="round"
            />
            <path
              d="M35.125 33.5625C35.125 33.9767 35.4608 34.3125 35.875 34.3125C36.2892 34.3125 36.625 33.9767 36.625 33.5625H35.125ZM31.5105 27.9375V27.1875V27.9375ZM24.4895 27.9375V27.1875V27.9375ZM20.125 32.0447H19.375H20.125ZM19.375 33.5625C19.375 33.9767 19.7108 34.3125 20.125 34.3125C20.5392 34.3125 20.875 33.9767 20.875 33.5625H19.375ZM36.625 33.5625V32.0447H35.125V33.5625H36.625ZM36.625 32.0447C36.625 30.7413 36.0744 29.5012 35.1107 28.5943L34.0827 29.6867C34.756 30.3203 35.125 31.1695 35.125 32.0447H36.625ZM35.1107 28.5943C34.1485 27.6888 32.8527 27.1875 31.5105 27.1875V28.6875C32.4833 28.6875 33.4078 29.0516 34.0827 29.6867L35.1107 28.5943ZM31.5105 27.1875H24.4895V28.6875H31.5105V27.1875ZM24.4895 27.1875C23.1473 27.1875 21.8515 27.6888 20.8893 28.5943L21.9173 29.6867C22.5922 29.0516 23.5167 28.6875 24.4895 28.6875V27.1875ZM20.8893 28.5943C19.9256 29.5012 19.375 30.7413 19.375 32.0447H20.875C20.875 31.1695 21.244 30.3203 21.9173 29.6867L20.8893 28.5943ZM19.375 32.0447V33.5625H20.875V32.0447H19.375Z"
              fill="#ABABB5"
            />
            <path
              d="M28 23.4375C30.4853 23.4375 32.5 21.4228 32.5 18.9375C32.5 16.4522 30.4853 14.4375 28 14.4375C25.5147 14.4375 23.5 16.4522 23.5 18.9375C23.5 21.4228 25.5147 23.4375 28 23.4375Z"
              stroke="#ABABB5"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </g>
          <defs>
            <clipPath id="clip0_914_951">
              <rect
                width="36"
                height="36"
                fill="white"
                transform="translate(10 6)"
              />
            </clipPath>
          </defs>
        </svg>
      </div>
      <div class="meio-header">
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
      <div class="direita-header">
<svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0.978638 23.6205H23.62V0.979095H0.978638V23.6205Z" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M10.5118 15.2789L6.34106 11.1081L0.978638 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M23.62 17.6622L15.8743 8.72482L8.72437 17.6622" stroke="#111111" stroke-width="1.78748" stroke-linecap="round" stroke-linejoin="round"/>
<circle cx="8.12854" cy="5.7457" r="1.78748" stroke="#111111" stroke-width="1.78748"/>
</svg>

      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media all and (min-width: 280px) and (max-width: 768px) {
  .header-div {
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 10;
    right: 0;
  }
  .header-index {
    width: 100%;
    height: 60px;
    background: #ebebf0;
    display: flex;
    z-index: 10;
    justify-content: space-evenly;
    align-items: center;
  }
  .esquerda-header {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0px 10px;
    gap: 10px;
    width: 64px;
    height: 64px;
  }
  .direita-header {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0px 10px;
    gap: 10px;
    width: 64px;
    height: 64px;
  }
  .meio-header {
    width: 192px;
    height: 92px;
    background: #ebebf0;
    border: 2.4px solid #d5d5de;
    border-radius: 4.8px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

}
</style>
