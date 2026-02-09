<template>
  <section class="how-it-works">
    <div class="container">
      <h2 class="section-title">How the Affiliate Program Works</h2>

      <div class="steps">
        <div class="step-card">
          <div class="step-icon">
            <img src="../assets/img/svg/overlay.svg" alt="Sign Up icon" />
          </div>
          <h3 class="step-title">Sign Up</h3>
          <p class="step-description">
            Join our affiliate program today to earn extra income, simply sign
            up for a free account.
          </p>
        </div>

        <div class="step-card">
          <div class="step-icon">
            <img src="../assets/img/svg/peopleimg.svg" alt="Share icon" />
          </div>
          <h3 class="step-title">Share with your audience</h3>
          <p class="step-description">
            Receive a referral code from us to share with your friends,
            colleagues, and followers.
          </p>
        </div>

        <div class="step-card">
          <div class="step-icon">
            <img src="../assets/img/svg/cardsvg3.svg" alt="Earn icon" />
          </div>
          <h3 class="step-title">Earn Passive Income</h3>
          <p class="step-description">
            Earn 10% from your referral's subscription fees in their first year,
            and track your earnings.
          </p>
        </div>
      </div>

      <div class="action-button-wrapper">
        <button class="start-button">Start earning</button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.how-it-works {
  background: #000000;
  padding: 100px 0;
  color: white;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.section-title {
  font-size: 4rem;
  font-weight: 700;
  text-align: center;
  margin-bottom: 6.25rem;
  line-height: 1.2;
  color: #fff;
}

.steps {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.step-card {
  position: relative;
  background: #111111;
  border-radius: 16px;
  padding: 100px 40px 79px 40px;
  text-align: center;
  min-height: 320px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}

.step-icon {
  position: absolute;
  top: -30px;
  left: 145px;
  width: 72px;
  height: 72px;
  margin: 0 auto 1.8rem;
  border-radius: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.step-icon img {
  width: 70px;
  height: 70px;
}

.step-title {
  font-weight: 500;
  font-size: 1.5rem;
  margin-bottom: 0.6875rem;
  color: #fff;
}

.step-description {
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.5rem;
  color: #818181;
}

.action-button-wrapper {
  text-align: center;
}

.start-button {
  background: #f59f0a;
  color: #1a1a1a;
  font-size: 1.25rem;
  font-weight: 600;
  padding: 1rem 3.2rem;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  transition: background-color 0.25s ease, transform 0.15s ease;
}

@media (max-width: 992px) {
  .section-title {
    font-size: 2.8rem;
    margin-bottom: 4rem;
  }

  .steps {
    gap: 1.5rem;
  }
}

@media (max-width: 640px) {
  .section-title {
    font-size: 2.4rem;
    margin-bottom: 3.5rem;
  }

  .step-card {
    padding: 2rem 1.5rem;
    min-height: auto;
  }

  .step-title {
    font-size: 1.5rem;
  }

  .step-description {
    font-size: 1rem;
  }

  .start-button {
    font-size: 1.125rem;
    padding: 0.9rem 2.8rem;
  }
}
</style>
