
<template>
  <div style="background: #232323; min-height: 100vh;">
    <header class="header sticky-header">
      <div class="header-inner">
        <div class="logo">WECOLLAB</div>
        <nav class="nav">
          <a href="#" class="nav-link">Log in</a>
          <a href="#" class="nav-link">Deals & Promo</a>
          <a href="#" class="nav-link">What's NEW?</a>
          <a href="#" class="nav-link">Booking</a>
          <button class="home-btn">HOME</button>
        </nav>
      </div>
    </header>
    <main class="main-content">
      <div class="hero">
        <div class="hero-center">
          <img src="/images/homepage/logo.png" alt="Logo" class="hero-logo-large" />
          <div class="hero-title">We collab</div>
          <div class="hero-tagline">CO-WORKING SPACE & CAFE</div>
        </div>
      </div>

      <!-- The Wecollab Story Section -->
      <section style="background: #f7f5ed; padding: 64px 0; display: flex; justify-content: center;">
        <div style="max-width: 1200px; width: 100%; display: flex; flex-direction: row; gap: 48px; align-items: flex-start; background: #f7f5ed; border-radius: 24px; box-shadow: 0 4px 16px rgba(0,0,0,0.06); padding: 48px;">
          <img src="/images/homepage/home1.png" alt="Wecollab Story" style="width: 400px; height: 400px; object-fit: cover; border-radius: 24px; box-shadow: 0 4px 16px rgba(0,0,0,0.10);">
          <div style="flex: 1; display: flex; flex-direction: column; justify-content: center;">
            <h2 style="font-size: 2.5rem; font-weight: bold; margin-bottom: 28px; color: #232323;">The Wecollab Story</h2>
            <p style="font-size: 1.35rem; color: #232323; margin-bottom: 32px; line-height: 1.7;">
              Founded on August 28, 2024, WeCollab.42 has quickly become known for its quiet and welcoming atmosphere. It’s a nice place where visitors can concentrate and accomplish their goals without distractions.
            </p>
            <a href="#" style="display: inline-block; background: #38613a; color: #fff; padding: 18px 40px; border-radius: 10px; font-size: 1.15rem; font-weight: 600; text-decoration: none; width: fit-content;">Learn More About Us</a>
          </div>
        </div>
      </section>

      <!-- Branch Section -->
      <section style="background: #f7f5ed; padding: 64px 0 80px 0; display: flex; flex-direction: column; align-items: center;">
        <h2 style="font-size: 2.5rem; font-weight: bold; color: #232323; margin-bottom: 48px;">BRANCH</h2>
        <div style="display: flex; flex-direction: row; gap: 48px; justify-content: center; align-items: flex-start; width: 100%; max-width: 1100px;">
          <div style="display: flex; flex-direction: column; align-items: center;">
            <img src="/images/homepage/branch.png" alt="We collab Jacinto" style="width: 420px; height: 280px; object-fit: cover; border-radius: 16px; box-shadow: 0 2px 8px rgba(0,0,0,0.10); margin-bottom: 18px;">
            <div style="font-size: 1.25rem; font-weight: 600; color: #232323; margin-bottom: 8px; text-align: center;">We collab Jacinto</div>
            <div style="font-size: 1.05rem; color: #888; text-align: center;">
              2F, Remfield Bldg. Juan, J. Dela Cruz St,<br>
              Poblacion District, Davao City, Davao del Sur
            </div>
          </div>
          <div>
            <img src="/images/homepage/map.png" alt="Map to WeCollab.42" style="width: 420px; height: 280px; object-fit: cover; border-radius: 16px; box-shadow: 0 2px 8px rgba(0,0,0,0.10);">
          </div>
        </div>
      </section>

      <!-- Reviews Section -->
  <section class="reviews-section" style="background: #f4f3f2; padding: 64px 0 80px 0; display: flex; flex-direction: column; align-items: center;">
        <h2 style="font-size: 2.5rem; font-weight: bold; color: #232323; margin-bottom: 48px;">REVIEWS</h2>

            <div class="testimonial-slide d-flex align-items-center justify-content-center">
              <img src="/images/review5.jpg" class="testimonial-profile rounded-circle" alt="Reviewer Five">
              <div class="testimonial-info ms-3">
                <div class="testimonial-name">Reviewer Five</div>
                <div class="testimonial-rating mb-2">
                  <span class="text-warning">★★★★☆</span>
                  <span class="testimonial-date ms-2">5 days ago</span>
                </div>
                <div class="testimonial-text">“Would recommend to friends.”</div>
              </div>
            </div>
      </section>
    </main>
  </div>
</template>

<style scoped>
html, body {
  width: 100%;
  max-width: 100vw;
  overflow-x: hidden !important;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

section, .main-content, .header, .header-inner, .hero, .review-carousel-container {
  width: 100% !important;
  max-width: 100vw !important;
  overflow-x: hidden;
  box-sizing: border-box;
}
html, body, #app, .main-content {
  width: 100vw;
  max-width: 100vw;
  overflow-x: hidden !important;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.header {
  background: #495846;
  color: #fff;
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  z-index: 100;
  box-shadow: 0 1px 6px rgba(0,0,0,0.03);
}
.header-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0.5rem 2rem;
  min-height: 54px;
  width: 100vw;
}
.logo {
  font-weight: bold;
  letter-spacing: 0.1em;
  font-size: 1.5rem;
  line-height: 1;
}
.nav {
  display: flex;
  gap: 1.5rem;
  align-items: center;
}
.nav-link {
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  padding: 0.3rem 0.7rem;
  border-radius: 6px;
  transition: background 0.2s, color 0.2s;
  line-height: 1.2;
}
.nav-link:hover {
  background: #fff;
  color: #495846;
}
.home-btn {
  background: #fff;
  color: #495846;
  border: none;
  border-radius: 6px;
  padding: 0.3rem 1rem;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: background 0.2s, color 0.2s;
  margin-left: 0.5rem;
  line-height: 1.2;
}
.home-btn:hover {
  background: #e0e0e0;
  color: #495846;
}
main.main-content {
  min-height: 100vh;
  background: #f5f5f5;
  width: 100vw;
  max-width: 100vw;
  overflow-x: hidden;
  margin-top: 54px;
}

section, .hero {
  width: 100vw !important;
  max-width: 100vw !important;
  overflow-x: hidden;
  box-sizing: border-box;
}

@media (max-width: 1200px) {
  .header-inner {
    padding: 0.5rem 1rem;
  }
}

@media (max-width: 900px) {
  .header-inner {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.5rem;
  }
  .main-content {
    padding: 0;
  }
  section, .hero {
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
}

@media (max-width: 600px) {
  .header-inner {
    padding: 0.5rem 0.5rem;
  }
  .main-content {
    padding: 0;
  }
  section, .hero {
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
}
  .hero {
    position: relative;
    width: 100vw;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    background-image: url('/images/homepage/hero.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: scroll;
  }
  .hero-center {
    position: relative;
    z-index: 2;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100vw;
    min-height: 80vh;
    color: #fff;
    text-align: center;
  }
  .hero-logo-large {
    width: 140px;
    height: 140px;
    margin-bottom: 2rem;
    object-fit: contain;
  }
  .hero-title {
    font-size: 3rem;
    font-weight: bold;
    margin-bottom: 1rem;
    letter-spacing: 0.04em;
    color: #fff;
    text-shadow: 0 2px 12px rgba(0,0,0,0.18);
  }
  .hero-tagline {
    font-size: 1.25rem;
    font-weight: 400;
    color: #fff;
    letter-spacing: 0.08em;
    text-shadow: 0 1px 8px rgba(0,0,0,0.15);
  }
  @media (max-width: 600px) {
    .hero-logo-large {
      width: 90px;
      height: 90px;
      margin-bottom: 1.2rem;
    }
    .hero-title {
      font-size: 2rem;
      margin-bottom: 0.7rem;
    }
    .hero-tagline {
      font-size: 1rem;
    }
    .hero-center {
      min-height: 60vh;
    }
  }

/* Testimonial Carousel Styles */

/* Refined Testimonial Carousel Styles */
/* Fix centering and container width */
.testimonial-slide {
  background: #fff;
  border-radius: 20px;
  box-shadow: 0 8px 32px rgba(0,0,0,0.13), 0 2px 8px rgba(0,0,0,0.10);
  padding: 48px 48px 48px 36px;
  display: flex;
  align-items: center;
  width: 100%;
  max-width: 500px;
  min-width: 0;
  min-height: 220px;
  margin: 0 auto;
  transition: box-shadow 0.3s, transform 0.3s;
  box-sizing: border-box;
}
.testimonial-profile {
  width: 90px;
  height: 90px;
  object-fit: cover;
  border: 3px solid #eee;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}
.testimonial-info {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 32px;
}
.testimonial-name {
  font-size: 1.35rem;
  font-weight: 700;
  margin-bottom: 0.3rem;
}
.testimonial-rating {
  font-size: 1.15rem;
  color: #ffc107;
  font-weight: 500;
}
.testimonial-date {
  font-size: 1rem;
  color: #888;
}
.testimonial-text {
  font-size: 1.18rem;
  color: #232323;
  margin-top: 0.7rem;
  font-style: italic;
}
.section-testimonials > .testimonial-slide,
section > .testimonial-slide {
  /* make testimonial slides participate in a responsive single-row grid when adjacent */
  box-sizing: border-box;
  margin: 12px auto;
}

.reviews-section > .testimonial-slide {
  box-sizing: border-box;
  margin: 12px auto;
}

.reviews-section {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 20px;
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
  padding: 0 12px;
  box-sizing: border-box;
}
@media (max-width: 900px) {
  .reviews-section {
    max-width: 98vw;
  }
  .testimonial-slide {
    max-width: 98vw;
    width: 100%;
    padding: 32px 10px 32px 10px;
    min-height: 180px;
  }
  .testimonial-profile {
    width: 64px;
    height: 64px;
  }
  .testimonial-info {
    margin-left: 16px;
  }
}
@media (max-width: 600px) {
  .testimonial-slide {
    flex-direction: column;
    align-items: flex-start;
    padding: 20px 6px 20px 6px;
    min-height: 120px;
  }
  .testimonial-profile {
    margin-bottom: 10px;
    width: 48px;
    height: 48px;
  }
  .testimonial-info {
    margin-left: 0;
  }
}
</style>