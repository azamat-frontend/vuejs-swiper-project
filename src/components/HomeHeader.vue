<template>
  <header class="home-header">
    <div class="top-line">
      <a class="logo" href="/">
        <span class="logo__image-wrapper">
          <img class="logo__svg" src="@/assets/images/logo.svg" alt="" />
        </span>
        <span class="logo__text">Азамат</span>
      </a>
      <div class="top-line__decoration"></div>
      <div class="top-line__contacts">
        <span>Телефон:</span> <a class="top-line__number" href="tel:+998(95)004-40-48">+998(95)004-40-48</a>
        <span class="top-line__separator"></span>
        <span class="top-line__address-wrapper">
          <span>Адрес:</span><a class="top-line__address" href="https://maps.google.com/maps?q=41.364945,69.199264&ll=41.364945,69.199264&z=16" target="_blank">ул. Ташкент, 37</a>
        </span>
      </div>
      <div class="top-line__decoration"></div>
      <div class="menu-button-container">
        <div class="menu-button"></div>
      </div>
    </div>

    <div class="home-header__content">
      <aside class="home-aside">
        <div class="home-aside__decoration"></div>
        <div class="home-aside__socials">
          <div class="home-aside__socials-items">
            <a class="social-item" href="#" target="_blank">
              <img src="@/assets/images/instagram.svg" alt="Instagram" />
            </a>
            <a class="social-item" href="#" target="_blank">
              <img src="@/assets/images/telegram.svg" alt="Instagram" />
            </a>
            <a class="social-item" href="#" target="_blank">
              <img src="@/assets/images/facebook.svg" alt="Instagram" />
            </a>
            <a class="social-item" href="#" target="_blank">
              <img src="@/assets/images/twitter.svg" alt="Instagram" />
            </a>
          </div>
        </div>
        <div class="home-aside__share"></div>
      </aside>

      <div class="slider-container">
        slider container

        <div class="slider-bottom">
          <div class="slider-share">
            <div class="slider-share__items">
              <a class="social-item slider-share__item" href="#" target="_blank">
              <img src="@/assets/images/instagram.svg" alt="Instagram" />
              </a>
              <a class="social-item slider-share__item" href="#" target="_blank">
                <img src="@/assets/images/telegram.svg" alt="Instagram" />
              </a>
              <a class="social-item slider-share__item" href="#" target="_blank">
                <img src="@/assets/images/facebook.svg" alt="Instagram" />
              </a>
            </div>
          </div>
          <div class="slider-pagination">222</div>
          <div class="slider-scrollbar">333</div>
          <div class="slider-navigation">444</div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

</style>