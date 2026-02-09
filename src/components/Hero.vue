<template>
  <section class="hero">
    <div class="container">
      <div class="hero__info">
        <div>
          <p class="info">BECOME AN AFFILIATE</p>
          <h2 class="hero__title">Earn on Every Subscription</h2>
          <div class="hero__desc">
            <strong
              >Grow your business and boost your income through BLOCS
              Affiliate.</strong
            >
            <span class="secondary">Earn on each subscription</span>
            <span class="secondary">for the first 12 months</span>
          </div>
          <button class="hero__btn">Start earning</button>
        </div>
        <div>
          <img src="../assets/img/heroimg.png" alt="hero-img" />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  background-color: #0a0a0a;
  padding-top: 5rem;
}
.hero__info {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.info {
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.5rem;
  color: #ffffff;
  margin-bottom: 2.625rem;
}

.hero__title {
  font-weight: 700;
  font-size: 3rem;
  line-height: 3.25rem;
  letter-spacing: -1px;
  color: #ffffff;
  margin-bottom: 16px;
}

.hero__desc {
  width: 100%;
  max-width: 512px;
  font-weight: 400;
  font-size: 1.1187rem;
  line-height: 1.6238rem;
  color: #ffffff;
  letter-spacing: 0.0125rem;
  margin-bottom: 1.6875rem;
}

.hero__btn {
  font-weight: 700;
  font-size: 1.125rem;
  line-height: 1.35rem;
  color: #333333;
  padding: 27px 82px;
  background-color: #f59f0a;
  border-radius: 34px;
  border: none;
  cursor: pointer;

  box-shadow: 4px 4px 25px 15px rgba(245, 159, 10, 0.25);
}
</style>
