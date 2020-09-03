<template>
  <div class="modal-wrapper">
    <div class="modal-content">
      <div class="close" @click="close">
        <svg
          width="48"
          height="48"
          viewBox="0 0 48 48"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <circle cx="24" cy="24" r="24" fill="#DE1C4B" />
          <rect
            x="14.1006"
            y="16.9287"
            width="4"
            height="24"
            rx="2"
            transform="rotate(-45 14.1006 16.9287)"
            fill="#0C0C0C"
          />
          <rect
            x="31.0713"
            y="14.1006"
            width="4"
            height="24"
            rx="2"
            transform="rotate(45 31.0713 14.1006)"
            fill="#0C0C0C"
          />
        </svg>
      </div>
      <a
        class="item"
        href="https://t.me/web_kottte"
        target="_blank"
        @click="tgClick"
      >
        <img src="/tg.png" alt="Telegram" />
      </a>
      <a
        class="item"
        href="https://wa.me/+79397820875"
        target="_blank"
        @click="waClick"
      >
        <img src="/wa.png" alt="whatsapp" />
      </a>
      <a
        class="item"
        href="mailto:work@kottte.ru"
        target="_blank"
        @click="emailClick"
      >
        <img src="/mail.png" alt="email" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ModalContacts',
  mounted() {
    this.$ga.event('contacts', 'open form')
  },
  methods: {
    tgClick() {
      this.$ga.event('contacts', 'tg click')
    },
    waClick() {
      this.$ga.event('contacts', 'wa click')
    },
    emailClick() {
      this.$ga.event('contacts', 'email click')
    },
    close() {
      this.$emit('close')
    },
  },
}
</script>

<style lang="postcss">
@keyframes fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
.modal-wrapper {
  position: fixed;
  height: 100vh;
  width: 100vw;
  left: 0;
  top: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 999;
  .modal-content {
    max-width: 1000px;
    max-height: 600px;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 100%;
    background: rgba(18, 18, 18, 0.87);
    border: 0.5px solid #2f2f2f;
    box-sizing: border-box;
    box-shadow: 0px 12px 6px rgba(0, 0, 0, 0.15),
      0px 4px 4px rgba(0, 0, 0, 0.25);
    backdrop-filter: blur(12px);
    border-radius: 16px;
    padding-left: 164px;
    padding-right: 164px;
    position: relative;
    animation: fade 0.4s ease-in;
  }
  .item {
    text-decoration: none;
    img {
      width: 120px;
      height: 120px;
      font-size: 0;
    }
  }
  .close {
    position: absolute;
    right: 32px;
    top: 32px;
    font-size: 0;
    display: flex;
    cursor: pointer;
  }
}
</style>
