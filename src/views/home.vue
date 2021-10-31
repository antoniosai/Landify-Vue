<template>
  <div class="home-container">
    <div class="home-main">
      <div class="home-blur-background"></div>
      <header class="home-header">
        <div class="home-logo">
          <img
            alt="image"
            src="/playground_assets/logotype-dark.svg"
            class="home-image"
          />
        </div>
        <div class="home-menu">
          <span class="home-text">About</span>
          <span class="home-text01">Products</span>
          <span class="home-text02">Pricing</span>
          <span class="home-text03">Blog</span>
          <span class="home-text04">Jobs</span>
          <span class="home-text05">More</span>
          <svg viewBox="0 0 1024 1024" class="home-icon">
            <path d="M316 366l196 196 196-196 60 60-256 256-256-256z"></path>
          </svg>
        </div>
        <div class="home-container01"><store-banner></store-banner></div>
        <svg viewBox="0 0 1024 1024" class="home-menu1">
          <path
            d="M810.667 725.333h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
          ></path>
          <path
            d="M810.667 426.667h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
          ></path>
          <path
            d="M810.667 128h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
          ></path>
        </svg>
      </header>
      <div class="home-hero">
        <div class="home-container02">
          <h1 class="home-text06 headline1">
            <span>Organize projects.</span>
            <br />
            <span>Get more done.</span>
          </h1>
          <primary-button button="Get Started"></primary-button>
        </div>
        <img
          alt="image"
          src="/playground_assets/iPhoneX-1200h.png"
          class="home-image01"
        />
      </div>
      <img
        alt="image"
        src="/playground_assets/turquoise-circle.svg"
        class="home-turquoise-cirble"
      />
      <img
        alt="image"
        src="/playground_assets/purple-circle.svg"
        class="home-purple-circle"
      />
      <img alt="image" src="/playground_assets/left.svg" class="home-left" />
      <img alt="image" src="/playground_assets/right.svg" class="home-right" />
    </div>
    <div class="home-clients">
      <div class="home-divider"></div>
      <img alt="image" src="/playground_assets/logo-1.svg" class="home-image02" />
      <img alt="image" src="/playground_assets/logo-4.svg" class="home-image03" />
      <img alt="image" src="/playground_assets/logo-3.svg" class="home-image04" />
      <img alt="image" src="/playground_assets/logo-5.svg" class="home-image05" />
      <img alt="image" src="/playground_assets/logo-6.svg" class="home-image06" />
      <div class="home-divider1"></div>
    </div>
    <div class="home-features">
      <h2 class="headline2 home-text10">Tailor-made features</h2>
      <span class="home-text11">
        <span class="home-text12">
          Lorem ipsum is common placeholder text used to demonstrate the graphic
          elements of a document or visual presentation.
        </span>
      </span>
      <div class="home-features1">
        <feature-card title="Robust workflow"></feature-card>
        <feature-card
          title="Flexibility"
          image_src="/playground_assets/02.svg"
        ></feature-card>
        <feature-card
          title="User friendly"
          image_src="/playground_assets/03.svg"
        ></feature-card>
        <feature-card
          title="Multiple layouts"
          image_src="/playground_assets/04.svg"
        ></feature-card>
        <feature-card
          title="Better compoents"
          image_src="/playground_assets/05.svg"
        ></feature-card>
        <feature-card
          title="Well organized"
          image_src="/playground_assets/06.svg"
        ></feature-card>
      </div>
    </div>
    <div class="home-testimonials">
      <div class="home-container03">
        <div class="home-container04">
          <img
            alt="image"
            src="/playground_assets/quote-mark.svg"
            class="home-image07"
          />
          <h1 class="home-text13 headline2">Real Stories from Real Customers</h1>
          <span>Get inspired by these stories.</span>
          <div class="home-container05">
            <testimonials-card
              image_src="/playground_assets/logo-4.svg"
            ></testimonials-card>
          </div>
        </div>
        <div class="home-container06">
          <div class="home-container07">
            <testimonials-card
              src="/playground_assets/logo-1.svg"
              text="I used Landify and created a landing page for my startup within a week. The Landify UI Kit is simple and highly intuitive, so anyone can use it."
              text1="Jane Cooper"
              text2="CEO, Airbnb"
              image_src="/playground_assets/logo-1.svg"
            ></testimonials-card>
          </div>
          <div class="home-container08">
            <testimonials-card
              text="Landify saved our time in designing my company page."
              text1="Kristin Watson"
              text2="Co-Founder, FedEx"
              image_src="/playground_assets/logo-2.svg"
            ></testimonials-card>
          </div>
        </div>
      </div>
    </div>
    <div class="home-achievements">
      <div class="home-container09">
        <h2 class="home-text15">
          <span class="home-text16">
            Our 18 years of
            <span v-html="rawdz99"></span>
          </span>
          <br />
          <span>achievements</span>
        </h2>
        <span class="home-text19">
          <span class="home-text20">
            With our super powers we have reached this
          </span>
        </span>
      </div>
      <div class="home-container10">
        <div class="home-container11">
          <stats-card
            number="10,000+"
            image_src="/playground_assets/01.svg"
            description="Downloads per day"
          ></stats-card>
          <stats-card
            number="2 Milion"
            image_src="/playground_assets/04.svg"
            description="Users"
          ></stats-card>
        </div>
        <div class="home-container12">
          <stats-card number="500+" description="Clients"></stats-card>
          <stats-card
            number="140"
            image_src="/playground_assets/07.svg"
            description="Countries"
          ></stats-card>
        </div>
      </div>
    </div>
    <div class="home-feature1">
      <div class="home-container13">
        <img
          alt="image"
          src="/playground_assets/iPhoneX-1200h.png"
          image_src="/playground_assets/iPhoneX-1200h.png"
          class="home-image08"
        />
      </div>
      <div class="home-container14">
        <h3 class="headline3">Headline</h3>
        <span class="home-text22 lead1">
          <span class="home-text23">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Condimentum
            diam orci pretium a pharetra, feugiat cursus. Dictumst risus, sem
            egestas odio cras adipiscing vulputate. Nisi, risus in suscipit non.
            Non commodo volutpat, pharetra, vel.
          </span>
        </span>
        <link-icon-button text="Get Started"></link-icon-button>
      </div>
    </div>
    <div class="home-feature2">
      <div class="home-container15">
        <h2 class="headline2 home-text24">
          <span class="home-text25">Enter the world of all fashion trends</span>
        </h2>
        <span class="home-text26 lead1">
          <span class="home-text27">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Condimentum
            diam orci pretium a pharetra, feugiat cursus. Dictumst risus, sem
            egestas odio cras adipiscing vulputate. Nisi, risus in suscipit non.
            Non commodo volutpat, pharetra, vel.
          </span>
        </span>
      </div>
      <img
        alt="image"
        src="https://images.unsplash.com/photo-1535157412991-2ef801c1748b?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        image_src="/playground_assets/iPhoneX-1200h.png"
        class="home-image09"
      />
    </div>
    <div class="home-c-t-a">
      <div class="home-container16">
        <div class="home-container17">
          <h2 class="headline2 home-text28">
            <span class="home-text29">Manage your projects from your mobile</span>
          </h2>
          <span class="home-text30 lead1">
            <span class="home-text31">
              Download the app to manage your projects, keep track of the progress
              and complete tasks without procastinating. Stay on track and
              complete on time!
            </span>
          </span>
          <span class="home-text32 subtitle2">
            <span class="home-text33">Get the App</span>
          </span>
          <store-banner></store-banner>
        </div>
        <div class="home-container18">
          <img
            alt="image"
            src="/playground_assets/iPhoneX-1200h.png"
            image_src="/playground_assets/iPhoneX-1200h.png"
            class="home-image10"
          />
          <img
            alt="image"
            src="/playground_assets/iPhoneX-1200h.png"
            image_src="/playground_assets/iPhoneX-1200h.png"
            class="home-image11"
          />
        </div>
      </div>
    </div>
    <div class="home-footer">
      <footer class="home-container19">
        <img
          alt="image"
          src="/playground_assets/logotype-light.svg"
          class="home-image12"
        />
        <div class="home-container20">
          <span class="home-text34">About</span>
          <span class="home-text35">Features</span>
          <span class="home-text36">Pricing</span>
          <span class="home-text37">Careers</span>
          <span class="home-text38">Help</span>
          <span class="home-text39">Privacy Policy</span>
        </div>
        <div class="home-divider2"></div>
        <div class="home-container21">
          <span class="home-text40 body2">
            Â© 2020 Landify UI Kit. All rights reserved
          </span>
          <div class="home-container22">
            <a
              href="https://instagram.com"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link"
            >
              <div class="home-container23">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon05">
                  <path
                    d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                  ></path>
                </svg>
              </div>
            </a>
            <a
              href="https://dribbble.com"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link1"
            >
              <div class="home-container24">
                <svg viewBox="0 0 877.7142857142857 1024" class="home-icon07">
                  <path
                    d="M585.143 857.143c-5.714-33.143-27.429-147.429-80-284.571-0.571 0-1.714 0.571-2.286 0.571 0 0-222.286 77.714-294.286 234.286-3.429-2.857-8.571-6.286-8.571-6.286 65.143 53.143 148 85.714 238.857 85.714 52 0 101.143-10.857 146.286-29.714zM479.429 510.286c-9.143-21.143-19.429-42.286-30.286-63.429-193.143 57.714-378.286 53.143-384.571 53.143-0.571 4-0.571 8-0.571 12 0 96 36.571 184 96 250.286v0c102.286-182.286 304.571-247.429 304.571-247.429 5.143-1.714 10.286-2.857 14.857-4.571zM418.286 389.143c-65.143-115.429-134.286-209.143-139.429-216-104.571 49.143-182.286 145.714-206.857 261.714 9.714 0 166.286 1.714 346.286-45.714zM809.143 571.429c-8-2.286-112.571-35.429-233.714-16.571 49.143 135.429 69.143 245.714 73.143 268 84-56.571 143.429-146.857 160.571-251.429zM349.143 148c-0.571 0-0.571 0-1.143 0.571 0 0 0.571-0.571 1.143-0.571zM686.286 230.857c-65.714-58.286-152.571-93.714-247.429-93.714-30.286 0-60 4-88.571 10.857 5.714 7.429 76.571 100.571 140.571 218.286 141.143-52.571 194.286-133.714 195.429-135.429zM813.714 508c-1.143-88.571-32.571-170.286-85.143-234.286-1.143 1.143-61.143 88-209.143 148.571 8.571 17.714 17.143 36 25.143 54.286 2.857 6.286 5.143 13.143 8 19.429 129.143-16.571 256.571 11.429 261.143 12zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                  ></path>
                </svg>
              </div>
            </a>
            <a
              href="https://twitter.com"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link2"
            >
              <div class="home-container25">
                <svg viewBox="0 0 950.8571428571428 1024" class="home-icon09">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </a>
            <a
              href="https://youtube.com"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link3"
            >
              <div class="home-container26">
                <svg viewBox="0 0 1024 1024" class="home-icon11">
                  <path
                    d="M406.286 644.571l276.571-142.857-276.571-144.571v287.429zM512 152c215.429 0 358.286 10.286 358.286 10.286 20 2.286 64 2.286 102.857 43.429 0 0 31.429 30.857 40.571 101.714 10.857 82.857 10.286 165.714 10.286 165.714v77.714s0.571 82.857-10.286 165.714c-9.143 70.286-40.571 101.714-40.571 101.714-38.857 40.571-82.857 40.571-102.857 42.857 0 0-142.857 10.857-358.286 10.857v0c-266.286-2.286-348-10.286-348-10.286-22.857-4-74.286-2.857-113.143-43.429 0 0-31.429-31.429-40.571-101.714-10.857-82.857-10.286-165.714-10.286-165.714v-77.714s-0.571-82.857 10.286-165.714c9.143-70.857 40.571-101.714 40.571-101.714 38.857-41.143 82.857-41.143 102.857-43.429 0 0 142.857-10.286 358.286-10.286v0z"
                  ></path>
                </svg>
              </div>
            </a>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import StoreBanner from '../components/store-banner'
import PrimaryButton from '../components/primary-button'
import FeatureCard from '../components/feature-card'
import TestimonialsCard from '../components/testimonials-card'
import StatsCard from '../components/stats-card'
import LinkIconButton from '../components/link-icon-button'

export default {
  name: 'Home',
  components: {
    StoreBanner,
    PrimaryButton,
    FeatureCard,
    TestimonialsCard,
    StatsCard,
    LinkIconButton,
  },

  data() {
    return {
      rawdz99: ' ',
    }
  },

  metaInfo: {
    title: 'Landify',
    meta: [
      {
        property: 'og:title',
        content: 'Landify',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-main {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.home-blur-background {
  top: 0px;
  left: auto;
  right: 0px;
  width: 100%;
  bottom: auto;
  filter: blur(60px);
  height: 70vh;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  background-color: #f2f2f2;
}
.home-header {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  max-width: 1110px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-logo {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-image {
  width: 100px;
  object-fit: cover;
}
.home-menu {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-text {
  transition: 0.3s;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-text:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text01 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-text01:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text02 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-text02:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text03 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-text03:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text04 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-doubleunit);
}
.home-text04:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text05 {
  transition: 0.3s;
}
.home-text05:hover {
  color: var(--dl-color-turquoise-default);
}
.home-icon {
  width: 24px;
  height: 24px;
}
.home-container01 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-menu1 {
  width: 24px;
  height: 24px;
  display: none;
  margin-left: var(--dl-space-space-unit);
}
.home-hero {
  flex: 0 0 auto;
  width: 100%;
  height: 80vh;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  max-width: 1110px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-container02 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text06 {
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-image01 {
  width: 320px;
  object-fit: cover;
}
.home-turquoise-cirble {
  top: 439px;
  left: auto;
  right: 430px;
  width: 170px;
  bottom: auto;
  filter: blur(60px);
  opacity: 0.6;
  position: absolute;
  object-fit: cover;
}
.home-purple-circle {
  top: -100px;
  left: auto;
  right: -26px;
  width: 400px;
  bottom: auto;
  filter: blur(60px);
  opacity: 0.4;
  position: absolute;
  object-fit: cover;
}
.home-left {
  top: 653px;
  left: 0px;
  right: auto;
  width: 420px;
  bottom: auto;
  position: absolute;
  object-fit: cover;
}
.home-right {
  top: 441px;
  left: auto;
  right: 0px;
  width: 612px;
  bottom: auto;
  position: absolute;
  object-fit: cover;
}
.home-clients {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  z-index: 100;
  overflow: hidden;
  position: relative;
  flex-wrap: wrap;
  max-width: 1110px;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-divider {
  top: 0px;
  left: auto;
  right: auto;
  width: 100%;
  bottom: auto;
  height: 1px;
  position: absolute;
  background: linear-gradient(90deg, rgba(192, 204, 218, 0.1) 0%, rgba(192, 204, 218, 0.6) 50.38%, rgba(192, 204, 218, 0.1) 100%);;
}
.home-image02 {
  width: 100px;
  object-fit: cover;
}
.home-image03 {
  width: 100px;
  object-fit: cover;
}
.home-image04 {
  width: 100px;
  object-fit: cover;
}
.home-image05 {
  width: 100px;
  object-fit: cover;
}
.home-image06 {
  width: 100px;
  object-fit: cover;
}
.home-divider1 {
  top: auto;
  left: auto;
  right: auto;
  width: 100%;
  bottom: 0px;
  height: 1px;
  position: absolute;
  background: linear-gradient(90deg, rgba(192, 204, 218, 0.1) 0%, rgba(192, 204, 218, 0.6) 50.38%, rgba(192, 204, 218, 0.1) 100%);;
}
.home-features {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  max-width: 1110px;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text11 {
  max-width: 500px;
  text-align: center;
}
.home-text12 {
  white-space: pre-wrap;
}
.home-features1 {
  display: flex;
  flex-wrap: wrap;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-testimonials {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: center;
  background-color: var(--dl-color-turquoise-100);
}
.home-container03 {
  display: flex;
  flex-wrap: wrap;
  max-width: 1100px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-container04 {
  flex: 0 0 auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.home-image07 {
  top: -22px;
  left: -65px;
  right: auto;
  width: 100px;
  bottom: auto;
  z-index: 10;
  position: absolute;
  object-fit: cover;
}
.home-text13 {
  z-index: 100;
  max-width: 500px;
}
.home-container05 {
  flex: 0 0 auto;
  width: 350px;
  display: flex;
  align-self: flex-end;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-container06 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-left: var(--dl-space-space-doubleunit);
  flex-direction: column;
}
.home-container07 {
  width: 350px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container08 {
  width: 300px;
  display: flex;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: column;
}
.home-achievements {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  flex-wrap: wrap;
  max-width: 1110px;
  align-items: center;
  flex-direction: row;
  justify-content: flex-start;
}
.home-container09 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text16 {
  white-space: pre-wrap;
}
.home-text20 {
  white-space: pre-wrap;
}
.home-container10 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-container11 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-container12 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-feature1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  max-width: 1110px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-container13 {
  flex: 0 0 auto;
  width: 540px;
  height: 540px;
  display: flex;
  overflow: hidden;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-purple-100);
}
.home-image08 {
  width: 360px;
  margin-top: 100px;
  object-fit: cover;
}
.home-container14 {
  flex: 1;
  margin: var(--dl-space-space-doubleunit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text22 {
  max-width: 400px;
  margin-top: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-text23 {
  white-space: pre-wrap;
}
.home-feature2 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  max-width: 1110px;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-container15 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: flex-start;
}
.home-text25 {
  white-space: pre-wrap;
}
.home-text26 {
  max-width: 400px;
  margin-top: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-text27 {
  white-space: pre-wrap;
}
.home-image09 {
  width: 100%;
  height: 400px;
  margin-top: var(--dl-space-space-tripleunit);
  object-fit: cover;
}
.home-c-t-a {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-turquoise-default);
}
.home-container16 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  flex-wrap: wrap;
  max-width: 1110px;
  align-items: center;
  flex-direction: row;
  justify-content: flex-start;
}
.home-container17 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text29 {
  white-space: pre-wrap;
}
.home-text30 {
  max-width: 500px;
}
.home-text31 {
  white-space: pre-wrap;
}
.home-text32 {
  max-width: 400px;
  margin-top: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text33 {
  white-space: pre-wrap;
}
.home-container18 {
  width: 520px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: row;
  justify-content: flex-start;
}
.home-image10 {
  top: -100px;
  left: auto;
  right: var(--dl-space-space-doubleunit);
  width: 232px;
  bottom: auto;
  position: absolute;
  object-fit: cover;
}
.home-image11 {
  top: auto;
  left: var(--dl-space-space-doubleunit);
  right: auto;
  width: 232px;
  bottom: -100px;
  position: absolute;
  object-fit: cover;
}
.home-footer {
  flex: 0 0 auto;
  color: var(--dl-color-gray-white);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
  background-color: var(--dl-color-gray-black);
}
.home-container19 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  z-index: 100;
  flex-wrap: wrap;
  max-width: 1110px;
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.home-image12 {
  object-fit: cover;
}
.home-container20 {
  display: flex;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: center;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: flex-start;
}
.home-text34 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-unit);
}
.home-text34:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text35 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-unit);
}
.home-text35:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text36 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-unit);
}
.home-text36:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text37 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-unit);
}
.home-text37:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text38 {
  transition: 0.3s;
  margin-right: var(--dl-space-space-unit);
}
.home-text38:hover {
  color: var(--dl-color-turquoise-default);
}
.home-text39 {
  transition: 0.3s;
  white-space: nowrap;
}
.home-text39:hover {
  color: var(--dl-color-turquoise-default);
}
.home-divider2 {
  width: 100%;
  height: 1px;
  opacity: 0.2;
  background-color: var(--dl-color-gray-white);
}
.home-container21 {
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-text40 {
  color: var(--dl-color-gray-300);
  margin-top: var(--dl-space-space-unit);
}
.home-container22 {
  flex: 0 0 auto;
  width: 200px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-link {
  display: contents;
}
.home-container23 {
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-icon05 {
  fill: var(--dl-color-gray-white);
  width: var(--dl-size-size-unit);
  height: var(--dl-size-size-unit);
  transition: 0.3s;
}
.home-icon05:hover {
  fill: var(--dl-color-purple-default);
}
.home-link1 {
  display: contents;
}
.home-container24 {
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-icon07 {
  fill: var(--dl-color-gray-white);
  width: var(--dl-size-size-unit);
  height: var(--dl-size-size-unit);
  transition: 0.3s;
}
.home-icon07:hover {
  fill: var(--dl-color-pink-default);
}
.home-link2 {
  display: contents;
}
.home-container25 {
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-icon09 {
  fill: var(--dl-color-gray-white);
  width: var(--dl-size-size-unit);
  height: var(--dl-size-size-unit);
  transition: 0.3s;
}
.home-icon09:hover {
  fill: var(--dl-color-turquoise-default);
}
.home-link3 {
  display: contents;
}
.home-container26 {
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-icon11 {
  fill: var(--dl-color-gray-white);
  width: var(--dl-size-size-unit);
  height: var(--dl-size-size-unit);
  transition: 0.3s;
}
.home-icon11:hover {
  fill: var(--dl-color-orange-default);
}
@media(max-width: 991px) {
  .home-container01 {
    display: none;
  }
  .home-menu1 {
    display: none;
  }
  .home-hero {
    height: auto;
    flex-direction: column;
  }
  .home-container02 {
    align-items: center;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .home-text06 {
    text-align: center;
  }
  .home-container03 {
    flex-direction: column;
  }
  .home-container05 {
    align-self: center;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .home-container06 {
    align-items: center;
    margin-left: 0px;
  }
  .home-container08 {
    width: 350px;
  }
  .home-achievements {
    flex-direction: column;
  }
  .home-container10 {
    margin-top: var(--dl-space-space-doubleunit);
  }
  .home-feature1 {
    flex-direction: column;
  }
  .home-container14 {
    margin-left: 0px;
    margin-right: 0px;
  }
  .home-container15 {
    align-items: flex-start;
    flex-direction: column;
  }
  .home-container18 {
    display: none;
  }
}
@media(max-width: 767px) {
  .home-menu {
    display: none;
  }
  .home-menu1 {
    display: block;
  }
  .home-text06 {
    font-size: 50px;
    text-align: center;
  }
  .home-clients {
    justify-content: center;
  }
  .home-image02 {
    margin: var(--dl-space-space-unit);
  }
  .home-image03 {
    margin: var(--dl-space-space-unit);
  }
  .home-image04 {
    margin: var(--dl-space-space-unit);
  }
  .home-image05 {
    margin: var(--dl-space-space-unit);
  }
  .home-image06 {
    margin: var(--dl-space-space-unit);
  }
  .home-text10 {
    font-size: 40px;
  }
  .home-container04 {
    align-items: center;
  }
  .home-image07 {
    top: -2px;
    left: 21px;
    right: auto;
    width: 50px;
    bottom: auto;
  }
  .home-text13 {
    font-size: 40px;
    text-align: center;
  }
  .home-text15 {
    font-size: 40px;
  }
  .home-text24 {
    font-size: 40px;
  }
  .home-text28 {
    font-size: 40px;
  }
  .home-container20 {
    flex-wrap: wrap;
    justify-content: center;
  }
  .home-container21 {
    flex-direction: column;
  }
  .home-text40 {
    margin-top: var(--dl-space-space-unit);
    margin-bottom: var(--dl-space-space-unit);
  }
}
@media(max-width: 479px) {
  .home-container01 {
    display: none;
  }
  .home-text10 {
    text-align: center;
  }
  .home-text11 {
    text-align: center;
  }
  .home-container09 {
    align-items: center;
  }
  .home-text15 {
    text-align: center;
  }
  .home-text19 {
    text-align: center;
  }
  .home-container11 {
    flex-direction: column;
  }
  .home-container12 {
    flex-direction: column;
  }
}
</style>
