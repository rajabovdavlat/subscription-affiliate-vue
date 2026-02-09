<template>
  <section class="affiliates">
    <div class="container">
      <div>
        <h2 class="affiliates__title">Who can become an Affiliate?</h2>
      </div>

      <div class="affiliates__info">
        <div class="affiliates__wrapp">
          <h2 class="affiliates__text">Social Influencers</h2>
          <p class="affiliates__desc">
            Increase your earnings by incorporating affiliate links into your
            social media posts and descriptions.
          </p>
          <button class="affiliates__btn">Become an agency partner</button>
          <span class='affiliates__illustration'>Illustration by Freepik. </span>
        </div>

        <div class="affiliates__img-wrapper">
          <img
            class="affiliates__img"
            src="../assets/img/png/afiiliatesimg.png"
            alt=""
          />
        </div>
      </div>

      <div class="card__wrapper">
        <div class="affiliates__card">
          <img src="" alt="" />
          <h3 class="card__title">Agencies & Consultants</h3>
          <p class="card__desc">
            Show to your clients how utilizing BLOCS can benefit their business,
            and in turn, enhance your own earnings.
          </p>
        </div>

        <div class="affiliates__card">
          <img src="" alt="" />
          <h3 class="card__title">Agencies & Consultants</h3>
          <p class="card__desc">
            Show to your clients how utilizing BLOCS can benefit their business,
            and in turn, enhance your own earnings.
          </p>
        </div>

        <div class="affiliates__card">
          <img src="" alt="" />
          <h3 class="card__title">Agencies & Consultants</h3>
          <p class="card__desc">
            Show to your clients how utilizing BLOCS can benefit their business,
            and in turn, enhance your own earnings.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.affiliates {
  background-color: #030303;
  padding: 80px 0;
}

.affiliates__title {
  width: 542px;
  margin: 0 auto 3rem;
  color: #fff;
  font-weight: 700;
  font-size: 4rem;
  line-height: 4.375rem;
  text-align: center;
}

.affiliates__info {
  position: relative;
  display: flex;
  align-items: center;
  padding: 0 22px 0 51px;
  background-color: #0a0a0a;
  overflow: hidden;
}

.affiliates__wrapp {
  position: absolute;
  max-width: 516px;
  z-index: 2;
}

.affiliates__text {
  color: #fff;
  font-weight: 700;
  font-size: 4rem;
  line-height: 4.375rem;
  margin-bottom: 1rem;
  white-space: nowrap
}

.affiliates__desc {
  max-width: 516px;
  font-weight: 400;
  font-size: 1.375rem;
  line-height: 1.9375rem;
  margin-bottom: 3.25rem;
  color: #fff;
}

.affiliates__btn {
  font-weight: 600;
  font-size: 1.125rem;
  color: #333333;
  padding: 13px 42px;
  background-color: #f59f0a;
  border: none;
  cursor: pointer;
  border-radius: 2.125rem;
}

.affiliates__illustration {
  position: absolute;
  right: -140px;
  bottom: -100px;                
  color: #F0F0F0;
  font-weight: 400;
  font-size: 16px;
  z-index: 3;
  white-space: nowrap;
  opacity: 60%;
}
.affiliates__img-wrapper {
  margin-left: auto;
  width: 977px;
  height: 480px;
  overflow: hidden;
}

.affiliates__img {
  width: 977px;
  height: auto;
  display: block;
  transform: translateX(10%);
}

/* Карточки */
.card__wrapper {
  display: flex;
  gap: 20px;                    
  flex-wrap: wrap;              
  margin: 5rem auto 0;
  justify-content: center;     

}

.affiliates__card {
  background-color: #222222;
  padding: 42px 14px 62px 32px; /* твои паддинги сохранены */
  border-radius: 40px;
  flex: 1;
}

.card__title {
  font-weight: 400;
  font-size: 1.5rem;
  line-height: 2rem;
  color: #fff;
  margin-bottom: 1rem;
}

.card__desc {
  max-width: 21.125rem;
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.5rem;
  color: #818181;
}


</style> 