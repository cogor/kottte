<template>
  <div class="homepage">
    <header class="">
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
      <picture>
        <source
          srcset="/first-circle.png"
          media="(min-width: 576px)"
          class="circle-one"
        />
        <source
          srcset="/first-circle-mobile.png"
          media="(min-width: 320px)"
          class="circle-one"
        />
        <img
          src="/first-circle.png"
          class="circle-one"
          alt="first circle"
          draggable="false"
        />
      </picture>
      <div class="glass-panel">
        <div class="text">
          создаём простые сайты для решения непростых задач
        </div>
        <div class="cta">
          <img src="/cta.png" alt="cta-btn" loading="lazy" />
        </div>
      </div>
      <div class="scroll-trigger">скрооооооолль</div>
    </section>
    <section class="second-block">
      <picture>
        <source
          srcset="/second-back@2x.png"
          media="(min-width: 576px)"
          class="second-block__back"
        />
        <source
          srcset="/second-back-mobile.png"
          media="(min-width: 320px)"
          class="second-block__back"
        />
        <img
          src="/second-back@2x.png"
          class="second-block__back"
          alt="second block background"
          draggable="false"
        />
      </picture>
      <picture>
        <source
          srcset="/second-front.png"
          media="(min-width: 576px)"
          class="second-block__front"
          loading="lazy"
        />
        <source
          srcset="/second-front-mobile.png"
          media="(min-width: 320px)"
          class="second-block__front"
          loading="lazy"
        />
        <img
          src="/second-front.png"
          class="second-block__front"
          alt="second block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <div class="second-block_middle">
        <div class="second-block__circle">
          <img src="/second-circle.png" alt="Second circle" loading="lazy" />
          <div class="time">
            0.4<br />
            секунды
          </div>
          <div class="wzuh">вжух вжух вжух</div>
          <div class="go">Поехали!</div>
          <div class="annotation">
            Скорость загрузки наших<br />
            самых быстрых сайтов
          </div>
        </div>
      </div>
    </section>
    <section class="third-block">
      <picture>
        <source
          srcset="/third-back.png"
          media="(min-width: 768px)"
          class="third-block__back"
          loading="lazy"
        />
        <source
          srcset="/third-back-tablet.png"
          media="(min-width: 576px)"
          class="third-block__back"
          loading="lazy"
        />
        <source
          srcset="/third-back-mobile.png"
          media="(min-width: 320px)"
          class="third-block__back"
          loading="lazy"
        />
        <img
          src="/third-back.png"
          class="third-block__back"
          alt="third block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <picture>
        <source
          srcset="/third-front.png"
          media="(min-width: 768px)"
          class="third-block__front"
          loading="lazy"
        />
        <source
          srcset="/third-front-tablet.png"
          media="(min-width: 576px)"
          class="third-block__front"
          loading="lazy"
        />
        <source
          srcset="/third-front-mobile.png"
          media="(min-width: 320px)"
          class="third-block__front"
          loading="lazy"
        />
        <img
          src="/third-front.png"
          class="third-block__front"
          alt="third block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <h2>Но почему это важно?</h2>
      <div class="list">
        <div class="item first-cause">
          Посетители любят когда сайт<br />
          загружается мгновенно
        </div>
        <div class="item second-cause">
          Поисковые алгоритмы тоже<br />
          любят быстрые сайты
        </div>
        <div class="item third-cause">
          Поэтому быстрому сайту проще<br />
          попасть в топ поисковых запросов
        </div>
        <div class="item fourth-cause">
          а значит — вы сможете<br />
          меньше тратить на рекламу
        </div>
      </div>
    </section>
    <section class="fourth-block">
      <picture>
        <source
          srcset="/fourth-back.png"
          media="(min-width: 768px)"
          class="fourth-block__back"
          loading="lazy"
        />
        <source
          srcset="/fourth-back-tablet.png"
          media="(min-width: 576px)"
          class="fourth-block__back"
          loading="lazy"
        />
        <source
          srcset="/fourth-back-mobile.png"
          media="(min-width: 320px)"
          class="fourth-block__back"
          loading="lazy"
        />
        <img
          src="/fourth-back.png"
          class="fourth-block__back"
          alt="fourth block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <picture>
        <source
          srcset="/fourth-front.png"
          media="(min-width: 768px)"
          class="fourth-block__front"
          loading="lazy"
        />
        <source
          srcset="/fourth-front-tablet.png"
          media="(min-width: 576px)"
          class="fourth-block__front"
          loading="lazy"
        />
        <source
          srcset="/fourth-front-mobile.png"
          media="(min-width: 320px)"
          class="fourth-block__front"
          loading="lazy"
        />
        <img
          src="/fourth-front.png"
          class="fourth-block__front"
          alt="fouth block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <picture>
        <source
          srcset="/fourth-circle.png"
          media="(min-width: 768px)"
          class="fourth-circle"
          loading="lazy"
        />
        <source
          srcset="/fourth-circle-mobile.png"
          media="(min-width: 320px)"
          class="fourth-circle"
          loading="lazy"
        />
        <img
          src="/fourth-circle.png"
          class="fourth-circle"
          alt="fourth circle"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <div class="text">
        Наши смелые идеи ярко выделяют вас среди конкурентов на рынке
      </div>
    </section>
    <section class="fifth-block">
      <picture>
        <source
          srcset="/fifth-back.png"
          media="(min-width: 768px)"
          class="fifth-block__back"
          loading="lazy"
        />
        <source
          srcset="/fifth-back-mobile.png"
          media="(min-width: 320px)"
          class="fifth-block__back"
          loading="lazy"
        />
        <img
          src="/fifth-back.png"
          class="fifth-block__back"
          alt="fifth block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <picture>
        <source
          srcset="/fifth-front.png"
          media="(min-width: 768px)"
          class="fifth-block__front"
          loading="lazy"
        />
        <source
          srcset="/fifth-front-mobile.png"
          media="(min-width: 320px)"
          class="fifth-block__front"
          loading="lazy"
        />
        <img
          src="/fifth-front.png"
          class="fifth-block__front"
          alt="fifth block background"
          draggable="false"
          loading="lazy"
        />
      </picture>
      <div class="work-block left">
        <img
          src="/ural-main.png"
          alt="Ural Art Bronze project"
          loading="lazy"
        />
      </div>
      <div class="work-block right">
        <img src="/andrag.png" alt="Andrag project" loading="lazy" />
      </div>
      <div class="work-block left">
        <img src="/med.png" alt="Medovkrym project" loading="lazy" />
      </div>
    </section>
    <section class="sixth-block">
      <h2>Сколько стоит?</h2>
      <div class="type">
        Сайт визитка <span>/</span> Лендинг <span>/</span> Портфолио
      </div>
      <div class="work-desc">Дизайн + разработка + адаптация + поддержка</div>
      <div class="price-list">
        <div class="price-block">
          <div class="price-block__header">
            <div class="price-title">Минималка</div>
            <div class="free-hosting">Бесплатный хостинг</div>
          </div>
          <div class="price-block__features">
            <div class="price-feature">
              <div class="price-feature__description">Экономно</div>
            </div>
          </div>
          <div class="price-block__footer">
            <div class="price-duration">
              <div class="duration-title">до 20 рабочих дней</div>
            </div>
            <div class="price-amount">25 000 Руб.</div>
          </div>
        </div>
        <div class="price-block highlight">
          <div class="price-block__header">
            <div class="price-title">Оптимум</div>
            <div class="free-hosting">Бесплатный хостинг</div>
          </div>
          <div class="price-block__features">
            <div class="price-feature">
              <div class="price-feature__title">3 месяца</div>
              <div class="price-feature__description">Бесплатная поддержка</div>
              <div class="price-feature__annotation">
                Затем 2 часа поддержки в месяц бесплатно*
              </div>
            </div>
            <div class="price-feature">
              <div class="price-feature__description">
                Уникальная креативная концепция
              </div>
            </div>
          </div>
          <div class="price-block__footer">
            <div class="price-duration">
              <div class="duration-title">до 20 рабочих дней</div>
              <div class="duration-description">
                всё внимание уделяем только вашему проекту
              </div>
            </div>
            <div class="price-amount">40 000 Руб.</div>
          </div>
        </div>
        <div class="price-block">
          <div class="price-block__header">
            <div class="price-title">Максималка</div>
            <div class="free-hosting">Бесплатный хостинг</div>
          </div>
          <div class="price-block__features">
            <div class="price-feature">
              <div class="price-feature__title">6 месяцев</div>
              <div class="price-feature__description">Бесплатная поддержка</div>
              <div class="price-feature__annotation">
                Затем 5 часов поддержки в месяц бесплатно*
              </div>
            </div>
            <div class="price-feature">
              <div class="price-feature__description">
                Уникальная креативная<br />
                концепция + айдентика
              </div>
            </div>
          </div>
          <div class="price-block__footer">
            <div class="price-duration">
              <div class="duration-title">до 14 рабочих дней</div>
              <div class="duration-description">
                всё внимание уделяем только вашему проекту
              </div>
            </div>
            <div class="price-amount">80 000 Руб.</div>
          </div>
        </div>
      </div>
      <div class="hourly-support-price">
        *час платной технической поддержки стоит 1200 ₽
      </div>
      <h2>А ещё мы делаем сайты-каталоги</h2>
      <h3>Пишите и мы всё обговорим</h3>
      <button>
        <img src="/cta.png" alt="" loading="lazy" />
      </button>
      <div class="bottom-cat">
        <picture>
          <source
            srcset="/botton-cat.png"
            media="(min-width: 768px)"
            loading="lazy"
          />
          <source
            srcset="/botton-cat-mobile.png"
            media="(min-width: 320px)"
            loading="lazy"
          />
          <img
            src="/botton-cat.png"
            draggable="false"
            loading="lazy"
            alt="cat"
          />
        </picture>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Kottte',
      description: 'Создаём простые сайты для решения непростых задач',
      meta: [
        { hid: 'og:title', name: 'title', content: 'Kottte' },
        {
          hid: 'og:description',
          name: 'description',
          content: 'Создаём простые сайты для решения непростых задач',
        },
        { name: 'og:image', content: '/site.png' },
        { name: 'og:url', content: 'https://kottte.ru' },
      ],
    }
  },
}
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
    justify-content: space-between;
    flex-direction: column;
    min-height: 90vh;
    position: relative;
    overflow-x: hidden;
    @media (max-width: 576px) {
      min-height: 100vh;
    }
    .circle-one {
      pointer-events: none;
      user-select: none;
      margin-top: -50px;
      @media (max-width: 576px) {
        max-width: 100vw;
        margin-top: 0;
      }
    }
    .glass-panel {
      padding: 16px 24px;
      background: rgba(18, 18, 18, 0.87);
      opacity: 0.8;
      border: 1px solid #2f2f2f;
      box-sizing: border-box;
      box-shadow: 0 12px 6px rgba(0, 0, 0, 0.15), 0 4px 4px rgba(0, 0, 0, 0.25);
      backdrop-filter: blur(12px);
      border-radius: 16px;
      display: flex;
      align-items: center;
      position: absolute;
      max-width: 880px;
      top: 30%;
      @media (max-width: 768px) {
        max-width: 600px;
        top: 27%;
        justify-content: space-between;
      }
      @media (max-width: 576px) {
        max-width: calc(100vw - 48px);
        top: 20%;
      }
      .text {
        font-family: 'IBM Plex Mono', monospace;
        font-weight: 300;
        font-size: 48px;
        line-height: 120%;
        text-transform: uppercase;
        color: #ebe9f3;
        @media (max-width: 768px) {
          font-size: 32px;
        }
        @media (max-width: 576px) {
          font-size: 24px;
          max-width: 60%;
        }
      }
      .cta {
        width: 84px;
        img {
          cursor: pointer;
          border-radius: 50%;
        }
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
      margin-bottom: 195px;
      @media (max-width: 768px) {
        margin-bottom: 185px;
      }
      @media (max-width: 768px) {
        margin-bottom: 185px;
      }
    }
  }
  .second-block {
    position: relative;
    min-height: 940px;
    overflow-x: hidden;
    @media (max-width: 768px) {
      min-height: 700px;
    }
    @media (max-width: 576px) {
      min-height: 570px;
    }
    .second-block__back {
      max-width: 1200px;
      height: auto;
      position: absolute;
      z-index: 1;
      object-fit: contain;
      left: calc(50% - 600px);
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 100vw;
        left: 0;
      }
    }
    .second-block__front {
      position: absolute;
      z-index: 20;
      height: auto;
      object-fit: contain;
      max-width: 1070px;
      left: calc(50% - 610px);
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 90vw;
        left: -12px;
      }
    }
    .second-block_middle {
      position: absolute;
      right: 24px;
      z-index: 10;
      width: 100%;
      display: flex;
      justify-content: flex-end;
      .second-block__circle {
        max-width: 816px;
        width: 100%;
        position: relative;
        margin-right: 13%;
        @media (max-width: 768px) {
          margin-right: 0;
          max-width: 650px;
        }
        @media (max-width: 576px) {
          margin-right: -85px;
        }
        img {
          z-index: 10;
          width: 100%;
          max-width: 816px;
          height: auto;
          top: 45px;
          @media (max-width: 768px) {
            max-width: 650px;
            height: auto;
          }
        }
        .time {
          font-style: italic;
          font-weight: 900;
          font-size: 85px;
          line-height: 100%;
          color: #ebe9f3;
          transform: rotate(-13.99deg);
          position: absolute;
          left: 195px;
          top: 330px;
          z-index: 11;
          text-align: center;
          @media (max-width: 768px) {
            width: 100%;
            left: 0;
            top: 270px;
            font-size: 60px;
          }
          @media (max-width: 576px) {
            font-size: 32px;
            top: 180px;
          }
        }
        .wzuh {
          font-style: italic;
          font-weight: 500;
          font-size: 32px;
          line-height: 120%;
          color: #ffffff;
          transform: rotate(-13.99deg);
          position: absolute;
          right: 510px;
          top: 274px;
          z-index: 11;
          @media (max-width: 768px) {
            width: 100%;
            left: 0;
            top: 150px;
          }
          @media (max-width: 576px) {
            font-size: 16px;
          }
        }
        .go {
          font-style: italic;
          font-weight: 500;
          font-size: 32px;
          line-height: 120%;
          color: #ffffff;
          transform: rotate(-13.99deg);
          position: absolute;
          right: 840px;
          top: 520px;
          z-index: 11;
          @media (max-width: 768px) {
            width: 100%;
            left: -40px;
            top: 310px;
          }
          @media (max-width: 576px) {
            font-size: 16px;
            top: 240px;
          }
        }
        .annotation {
          font-style: italic;
          font-weight: 500;
          font-size: 32px;
          line-height: 120%;
          color: #ffffff;
          transform: rotate(-13.99deg);
          position: absolute;
          right: 370px;
          top: 581px;
          z-index: 11;
          width: 490px;
          @media (max-width: 768px) {
            width: 100%;
            left: 12px;
            top: 440px;
          }
          @media (max-width: 576px) {
            font-size: 16px;
            top: 280px;
          }
        }
      }
    }
    @media (max-width: 1440px) {
      max-width: 100vw;
    }
  }
  .third-block {
    padding-top: 172px;
    position: relative;
    min-height: 1600px;
    overflow-x: hidden;
    @media (max-width: 768px) {
      min-height: 1100px;
    }
    @media (max-width: 1440px) {
      max-width: 100%;
    }
    @media (max-width: 576px) {
      min-height: 1160px;
    }
    .list {
      padding-left: calc(50% - 500px);
      padding-right: calc(50% - 500px);
      z-index: 30;
      position: relative;
      @media (max-width: 768px) {
        padding-left: 32px;
        padding-right: 32px;
      }
      .first-cause {
        margin-top: 122px;
        @media (max-width: 768px) {
          margin-top: 60px;
        }
        @media (max-width: 576px) {
          margin-top: 78px;
        }
      }
      .second-cause {
        margin-top: 46px;
        display: flex;
        justify-content: flex-end;
        @media (max-width: 768px) {
          margin-top: 24px;
        }
        @media (max-width: 576px) {
          margin-top: 36px;
        }
      }
      .third-cause {
        margin-top: 190px;
        @media (max-width: 768px) {
          margin-top: 24px;
        }
        @media (max-width: 576px) {
          margin-top: 150px;
        }
      }
      .fourth-cause {
        margin-top: 46px;
        display: flex;
        justify-content: flex-end;
        @media (max-width: 768px) {
          margin-top: 80px;
        }
        @media (max-width: 576px) {
          margin-top: 96px;
        }
      }
    }
    h2 {
      font-style: italic;
      font-weight: 900;
      font-size: 85px;
      line-height: 100%;
      text-align: center;
      color: #ebe9f3;
      position: relative;
      z-index: 19;
      @media (max-width: 768px) {
        font-size: 60px;
      }
      @media (max-width: 576px) {
        font-size: 38px;
        margin-top: 105px;
      }
    }
    .third-block__back {
      max-width: 1136px;
      height: auto;
      position: absolute;
      z-index: 1;
      object-fit: contain;
      left: calc(50% - 550px);
      top: 0;
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 100vw;
        left: 0;
      }
    }
    .third-block__front {
      position: absolute;
      z-index: 20;
      height: auto;
      object-fit: contain;
      max-width: 1146px;
      left: calc(50% - 570px);
      top: 0;
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 100vw;
        left: 0;
        top: 60px;
      }
    }
    .item {
      font-weight: 500;
      font-size: 32px;
      line-height: 150%;
      color: #ebe9f3;
      @media (max-width: 768px) {
        font-size: 24px;
      }
      @media (max-width: 576px) {
        font-size: 16px;
        line-height: 150%;
      }
    }
  }
  .fourth-block {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    overflow-x: hidden;
    min-height: 1200px;
    @media (max-width: 1440px) {
      max-width: 100%;
      min-height: 830px;
    }
    @media (max-width: 576px) {
      font-size: 16px;
      line-height: 150%;
      min-height: 1000px;
    }
    .fourth-block__back {
      max-width: 1159px;
      height: auto;
      position: absolute;
      z-index: 1;
      object-fit: contain;
      left: calc(50% - 580px);
      top: 0;
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 90vw;
        left: 32px;
        top: 0;
      }
    }
    .fourth-block__front {
      position: absolute;
      z-index: 20;
      height: auto;
      object-fit: contain;
      max-width: 1196px;
      left: calc(50% - 640px);
      top: -130px;
      @media (max-width: 768px) {
        max-width: 90vw;
        left: 32px;
        top: 110px;
      }
    }
    .fourth-circle {
      z-index: 30;
      position: relative;
      width: 772px;
      height: auto;
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
    }
    .text {
      max-width: 612px;
      font-style: italic;
      font-weight: 600;
      font-size: 40px;
      line-height: 120%;
      text-align: center;
      color: #edecf0;
      text-shadow: -10px 12px 12px rgba(97, 97, 97, 0.15),
        -6px 4px 8px rgba(99, 99, 99, 0.25);
      margin-top: -190px;
      position: relative;
      z-index: 20;
      @media (max-width: 1440px) {
        margin-top: -140px;
      }
      @media (max-width: 576px) {
        font-size: 20px;
        padding-left: 50px;
        padding-right: 50px;
        margin-top: -180px;
      }
    }
  }
  .fifth-block {
    position: relative;
    display: flex;
    align-items: flex-start;
    justify-content: center;
    flex-direction: column;
    padding: 440px calc(50% - 650px) 550px;
    overflow-x: hidden;
    @media (max-width: 768px) {
      padding: 100px 32px 100px;
    }
    @media (max-width: 576px) {
      padding: 150px 0 450px;
      min-height: 1900px;
    }
    .fifth-block__back {
      max-width: 1377px;
      height: auto;
      position: absolute;
      z-index: 1;
      object-fit: contain;
      left: calc(50% - 688px);
      top: 0;
      @media (max-width: 768px) {
        max-width: 100vw;
        left: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 100vw;
      }
    }
    .fifth-block__front {
      position: absolute;
      z-index: 20;
      height: auto;
      object-fit: contain;
      max-width: 1332px;
      right: calc(50% - 666px);
      top: -130px;
      @media (max-width: 768px) {
        width: 100vw;
        max-width: 100vw;
        left: 0;
        top: 0;
      }
      @media (max-width: 576px) {
        max-width: 100vw;
        width: 100vw;
      }
    }
    .work-block {
      background: rgba(18, 18, 18, 0.87);
      border: 1px solid #2f2f2f;
      box-sizing: border-box;
      box-shadow: 0 12px 6px rgba(0, 0, 0, 0.15), 0 4px 4px rgba(0, 0, 0, 0.25);
      backdrop-filter: blur(12px);
      border-radius: 16px;
      max-width: 1000px;
      z-index: 15;
      padding: 40px;
      margin-bottom: 88px;
      img {
        max-width: 100%;
        height: auto;
        z-index: 40;
      }
      &.left {
        align-self: flex-start;
      }
      &.right {
        align-self: flex-end;
      }
      @media (max-width: 576px) {
        padding: 16px;
        margin-bottom: 80px;
        max-width: calc(100% - 16px);
        margin-left: 8px;
      }
    }
  }
  .sixth-block {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 calc(50% - 650px) 0;
    overflow-x: hidden;
    @media (max-width: 768px) {
      padding: 0 24px 0;
    }
    @media (max-width: 576px) {
      padding: 0;
    }
    h2 {
      font-style: italic;
      font-weight: 900;
      font-size: 85px;
      line-height: 100%;
      text-align: center;
      color: #ebe9f3;
      margin-bottom: 80px;
      max-width: 860px;
      @media (max-width: 768px) {
        font-size: 64px;
        margin-bottom: 32px;
      }
      @media (max-width: 576px) {
        font-size: 38px;
        margin-bottom: 50px;
      }
    }
    h3 {
      font-size: 32px;
      line-height: 150%;
      text-align: center;
      color: #ebe9f3;
      margin-top: 24px;
      @media (max-width: 768px) {
        font-size: 24px;
        margin-top: 0;
      }
      @media (max-width: 576px) {
        font-size: 20px;
        margin-top: -12px;
      }
    }
    button {
      background: transparent;
      border: 0;
      margin-top: 80px;
      img {
        height: 140px;
        width: 140px;
      }
    }
    .type {
      font-size: 32px;
      line-height: 150%;
      text-align: center;
      color: #ffffff;
      @media (max-width: 576px) {
        font-size: 20px;
        margin-bottom: 8px;
      }
      span {
        color: #4d289f;
      }
    }
    .work-desc {
      font-size: 20px;
      line-height: 150%;
      text-align: center;
      color: #ebe9f3;
      margin-bottom: 120px;
      @media (max-width: 768px) {
        margin-bottom: 64px;
      }
      @media (max-width: 576px) {
        font-size: 14px;
        margin-bottom: 88px;
      }
    }
    .price-list {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-gap: 60px;
      width: 100%;
      margin-bottom: 120px;
      @media (max-width: 768px) {
        grid-template-columns: 1fr;
        grid-gap: 64px;
      }
      @media (max-width: 576px) {
        margin-bottom: 50px;
      }
    }
    .price-block {
      width: 100%;
      box-sizing: border-box;
      border-radius: 16px;
      padding-top: 32px;
      padding-bottom: 36px;
      height: 620px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      position: relative;
      @media (max-width: 768px) {
        width: 500px;
        margin-left: auto;
        margin-right: auto;
      }
      @media (max-width: 576px) {
        font-size: 20px;
        margin-bottom: 8px;
        width: 100%;
        max-width: calc(100vw - 16px);
        margin-left: 8px;
        height: auto;
      }
      &:before {
        box-shadow: 0 0 40px #bababa, 6px 0 8px rgba(180, 180, 180, 0.5);
        background: rgba(18, 18, 18, 0.87);
        border: 0.5px solid #a4a4a4;
        backdrop-filter: blur(12px);
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        content: '';
        border-radius: 16px;
        z-index: -1;
        opacity: 0.24;
      }
      &.highlight {
        transform: scale(1.06);
        @media (max-width: 576px) {
          transform: scale(1);
        }
        &:before {
          background: rgba(18, 18, 18, 0.87);
          border: 0.5px solid #de1c4b;
          box-shadow: 0 0 40px #de1c4b, 6px 0 8px rgba(222, 28, 75, 0.5);
          backdrop-filter: blur(12px);
          width: 100%;
          height: 100%;
          position: absolute;
          top: 0;
          left: 0;
          content: '';
          border-radius: 16px;
          z-index: 1;
          opacity: 0.24;
        }
        .price-amount {
          font-size: 40px;
          color: #de1c4b;
        }
        .price-title {
          color: #ebe9f3;
        }
        .price-duration {
          color: #ebe9f3;
        }
        .price-feature {
          .price-feature__title {
            color: #ebe9f3;
          }
        }
      }
      .price-title {
        font-weight: 900;
        font-size: 40px;
        line-height: 100%;
        text-align: center;
        color: #a8a6b1;
        @media (max-width: 576px) {
          font-size: 32px;
        }
      }
      .free-hosting {
        font-size: 16px;
        line-height: 150%;
        text-align: center;
        color: #a8a6b1;
        margin-top: 44px;
        @media (max-width: 576px) {
          font-size: 16px;
        }
      }
      .price-block__features {
        display: grid;
        grid-template-columns: 1fr;
        grid-gap: 48px;
        @media (max-width: 576px) {
          margin-top: 56px;
        }
      }
      .price-feature {
        display: flex;
        flex-direction: column;
        align-items: center;
        .price-feature__description {
          font-size: 16px;
          line-height: 120%;
          text-align: center;
          color: #a8a6b1;
        }
        .price-feature__title {
          font-weight: 900;
          font-size: 24px;
          line-height: 100%;
          text-align: center;
          color: #ebe9f3;
          margin-bottom: 4px;
        }
        .price-feature__annotation {
          font-weight: normal;
          font-size: 13px;
          line-height: 16px;
          text-align: center;
          color: #c7c5cd;
          margin-top: 8px;
          max-width: 180px;
        }
      }
      .price-duration {
        @media (max-width: 576px) {
          margin-top: 90px;
        }
        .duration-title {
          font-weight: 900;
          font-size: 24px;
          line-height: 100%;
          text-align: center;
          color: #ebe9f3;
        }
        .duration-description {
          font-size: 16px;
          line-height: 150%;
          text-align: center;
          color: #a8a6b1;
          max-width: 270px;
          margin-top: 4px;
        }
      }
      .price-amount {
        font-weight: 900;
        font-size: 24px;
        line-height: 100%;
        text-align: center;
        color: #ebe9f3;
        margin-top: 64px;
      }
    }
    .hourly-support-price {
      font-size: 16px;
      line-height: 120%;
      text-align: center;
      color: #ebe9f3;
      margin-bottom: 160px;
      @media (max-width: 576px) {
        padding-left: 48px;
        padding-right: 48px;
      }
    }
    .bottom-cat {
      display: flex;
      justify-content: flex-start;
      width: 100%;
      margin-top: 60px;
      img {
        width: 500px;
        height: auto;
      }
      @media (max-width: 576px) {
        img {
          max-height: 300px;
          width: auto;
        }
      }
    }
  }
}
</style>
