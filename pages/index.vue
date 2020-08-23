<template>
  <div class="homepage">
    <header>
      <div class="logo">
        <svg
          width="92"
          height="16"
          viewBox="0 0 92 16"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M3.03086 0V8.84553L8.41732 4.24932H12.7108L7.32432 8.58537L13.1662 15.7429H9.08316L4.94988 10.4963L3.03714 12.0449V15.7615H0V0H3.03086Z"
            fill="#E6E7F2"
          />
          <path
            d="M50.7959 6.15717V3.98915H53.2269V0.433594H56.2609V3.98915H59.4142V6.15717H56.2483V11.4069C56.2483 12.7325 56.3143 13.4448 57.3476 13.4448C58.0951 13.4448 58.7986 13.4262 59.5241 13.4015V15.5695C58.7529 15.6852 57.9738 15.7432 57.1937 15.7429C53.5001 15.7429 53.2143 14.4421 53.2143 12.271V6.15717H50.7959Z"
            fill="#E6E7F2"
          />
          <path
            d="M59.3765 6.15717V3.98915H61.7949V0.433594H64.8289V3.98915H67.9885V6.15717H64.8289V11.4069C64.8289 12.7325 64.8948 13.4448 65.9281 13.4448C66.6756 13.4448 67.3792 13.4262 68.1047 13.4015V15.5695C67.3386 15.6844 66.5649 15.7424 65.7899 15.7429C62.0964 15.7429 61.8106 14.4421 61.8106 12.271V6.15717H59.3765Z"
            fill="#E6E7F2"
          />
          <path
            d="M67.9541 6.15717V3.98915H70.3725V0.433594H73.4065V3.98915H76.5724V6.15717H73.4065V11.4069C73.4065 12.7325 73.4725 13.4448 74.5058 13.4448C75.2533 13.4448 75.9568 13.4262 76.6824 13.4015V15.5695C75.9111 15.6852 75.132 15.7432 74.3519 15.7429C70.6583 15.7429 70.3725 14.4421 70.3725 12.271V6.15717H67.9541Z"
            fill="#E6E7F2"
          />
          <path
            d="M84.9743 13.7485C86.9749 13.7485 87.8544 13.0516 88.448 12.0977H91.7458C91.0863 13.3768 89.5033 15.9165 85.0622 15.9165C79.8077 15.9165 77.8384 12.8998 77.8384 9.84293C77.8384 6.00553 80.7185 3.55566 84.8518 3.55566C90.0184 3.55566 92.0002 6.69929 92.0002 10.0597V10.4933H81.0074C81.0828 11.7725 81.9622 13.7485 84.9743 13.7485ZM84.9083 5.5936C83.5012 5.5936 81.5225 6.24402 81.0169 8.58548H88.8437C88.47 6.28738 86.4033 5.5936 84.9083 5.5936Z"
            fill="#E6E7F2"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M20.2956 16.0001C15.1792 15.9506 13.21 12.9618 13.21 9.82127C13.21 6.68383 15.1792 3.69506 20.2956 3.64551H43.7133V5.9467H20.2956C17.4469 6.00245 16.3759 7.85457 16.3759 9.82127C16.3759 11.788 17.4469 13.6432 20.2956 13.6989L43.7133 13.6989V16.0001L20.2956 16.0001ZM43.7133 5.9467V3.64551C48.8297 3.69506 50.7958 6.68074 50.7958 9.82127C50.7958 12.9618 48.8265 15.9506 43.7133 16.0001V13.6989C46.5589 13.6432 47.6299 11.7849 47.6299 9.82127C47.6299 7.85766 46.5589 6.00245 43.7133 5.9467Z"
            fill="#E6E7F2"
          />
        </svg>
      </div>
    </header>
    <section class="first-block">
      <img
        class="circle-one"
        src="/first-circle.png"
        alt="First circle"
        draggable="false"
      />
      <div class="glass-panel">
        <div class="text">
          создаём простые сайты для решения непростых задач
        </div>
        <div class="cta">
          <img src="/cta.png" alt="cta-btn" />
        </div>
      </div>
      <div class="scroll-trigger">
        скрооооооолль
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss">
.homepage {
  header {
    padding-top: 24px;
  }
  .logo {
    display: flex;
    justify-content: center;
    font-size: 0;
    align-items: center;
  }
  .first-block {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    min-height: 100vh;
    .circle-one {
      pointer-events: none;
      user-select: none;
    }
  }
  .glass-panel {
    padding: 16px 24px;
    background: rgba(18, 18, 18, 0.87);
    opacity: 0.8;
    border: 0.5px solid #2f2f2f;
    box-sizing: border-box;
    box-shadow: 0 12px 6px rgba(0, 0, 0, 0.15), 0 4px 4px rgba(0, 0, 0, 0.25);
    backdrop-filter: blur(12px);
    border-radius: 16px;
    display: flex;
    align-items: center;
    position: absolute;
    max-width: 880px;
    .text {
      font-family: 'IBM Plex Mono', monospace;
      font-weight: 300;
      font-size: 48px;
      line-height: 120%;
      text-transform: uppercase;
      color: #ebe9f3;
    }
    .cta {
      width: 84px;
      cursor: pointer;
    }
  }
  .scroll-trigger {
    font-family: 'IBM Plex Mono', monospace;
    font-size: 16px;
    line-height: 100%;
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: 0.185em;
    text-transform: uppercase;
    color: #8f74fb;
    transform: rotate(90deg);
  }
}
</style>
