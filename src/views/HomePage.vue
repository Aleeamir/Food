<template>

  <div class="home-first-banner">
    <!-- <img src="@/assets/Images/div.bg-wrap.png" alt=""> -->
    <h1>NATURAL PRODUCTS <br> FOR LOVER OF <br> HEALTHY ORGANIC FOOD</h1>

    <button class="button-3" role="button">Discover More</button>


  </div>
  <div class="second-banner-complete">
    <div class="home-second-banner">
      <div class="second-banner-text">
        <h4>Get to Know us</h4>
        <h2>
          Leader in agriculture market
        </h2>
        <p>There are many variations of passages of Lorem Ipsum available
          majority have suffered alteration in some form, by injected humour,
          or randomised words which don’t look even slightly believable.</p>
      </div>
      <div class="second-banner-second-portion">
        <div class="second-banner-text">
          <h4>Modern agriculture types</h4>
          <p>Modern agriculture types</p>
          <button class="button-3" role="button">Discover More</button>

        </div>
        <div class="second-portion-img">
          <img src="@/assets/Images/img.png" alt="">
        </div>

      </div>
    </div>
    <div class="home-second-banner">
      <div class="images-for-right">
        <img src="@/assets/Images/img1.png" alt="">
        <img src="@/assets/Images/img2.png" alt="">
      </div>
    </div>
  </div>
  <div class="service-portion">
    <h4>Our services</h4>
    <h2> Who We Are</h2>
    <div id="service">
      <ServiceBox imgSrc="@/assets/Images/s1.png" heading="Service 1" description="Description for Service 1." />
      <ServiceBox imgSrc="@/assets/Images/s2.png" heading="Service 2" description="Description for Service 2." />
      <ServiceBox imgSrc="@/assets/Images/s3.png" heading="Service 3" description="Description for Service 3." />
    </div>
  </div>
  <div class="after-service-banner">
    <div class="images-portion-service">
      <img src="@/assets/Images/green.png" alt="Image 1" class="image image-1">
      <img src="@/assets/Images/serviceimg2.png" alt="Image 2" class="image image-2">
    </div>
    <div class="text-area">
      <h4>Frequently Asked Questions</h4>
      <h2>You've Any Questions</h2>
      <h3>World’s hottest destinations for vegans</h3>
      <h3>Let’s grow naturaly and live naturaly</h3>
      <p>Suspendisse finibus urna mauris, vitae consequat quam vel. Vestibulum leo
        ligula, molestie ullamcorper vulputate vitae sodales commodo nisl. Nulla
        facilisi. Pellentesque est metus many of some form.</p>
      <h3>Best vegetables for your healthy hair</h3>
    </div>

  </div>
  <div class="fourth-banner">
    <div class="right-text">
      <h4>Our recent work</h4>
      <h2>Recently Completed
        Projects
      </h2>
    </div>
    <div class="left-text">
      <p>Lorem ipsum dolor sit amet consectetur adipiscing elit penatibsenectus,
        sem mus etiam pharetra lacus ac tortor vitae, amet tincidunt congue fusce
        ridiculus cubilia ad feugiat fames placerat</p>
    </div>
  </div>
  <div class="fifth-banner">
    <img src="@/assets/Images/fifth-banner.png" alt="">
  </div>
  <div class="six-banner">
    <!-- <img src="" alt=""> -->
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  components: {
    ServiceBox: {
      props: ['imgSrc', 'heading', 'description'],
      template: `
        <div class="service-box">
          <img :src="imgSrc" :alt="heading + ' Image'">
          <h2>{{ heading }}</h2>
          <p>{{ description }}</p>
        </div>
      `
    }
  }
}
</script>

<style>
.home-first-banner {
  box-sizing: border-box;
  overflow: hidden;
  background-image: url(@/assets/Images/div.bg-wrap.png);
}

.home-first-banner h1 {
  font-size: 60px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  text-align: center;
  color: white;
  /* margin-top: 30px; */
  padding: 40px;
}



/* CSS BUTTON */
.button-3 {
  margin: 2% 45% 10% 45%;
  appearance: none;
  background-color: #2ea44f;
  border: 1px solid rgba(27, 31, 35, .15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, .1) 0 1px 0;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  font-size: 14px;
  font-weight: 600;
  line-height: 20px;
  padding: 8px 45px;
  position: relative;
  text-align: center;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
  white-space: nowrap;
}

.button-3:focus:not(:focus-visible):not(.focus-visible) {
  box-shadow: none;
  outline: none;
}

.button-3:hover {
  background-color: #2c974b;
}

.button-3:focus {
  box-shadow: rgba(46, 164, 79, .4) 0 0 0 3px;
  outline: none;
}

.button-3:disabled {
  background-color: #94d3a2;
  border-color: rgba(27, 31, 35, .1);
  color: rgba(255, 255, 255, .8);
  cursor: default;
}

.button-3:active {
  background-color: #298e46;
  box-shadow: rgba(20, 70, 32, .2) 0 1px 0 inset;
}

.second-banner-text h4 {
  font-size: 20px;
  font-family: 'Courier New', Courier, monospace;
  color: #EEC044;
}

.second-banner-text h2 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 30px;
}

.second-banner-text p {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 14px;

}

.second-banner-second-portion {
  display: flex;
  flex-direction: row;
  gap: 60px;
}

.second-banner-text .button-3 {
  margin: 10px 40px 20px 20px;
  padding: 8px 20px;
}

.second-banner-complete {
  display: flex;
  flex-direction: row;
  margin: 70px 10px 30px 70px;
}

.images-for-right {
  display: flex;
  flex-direction: row;
}

.service-portion h4 {
  font-size: 20px;
  font-family: 'Courier New', Courier, monospace;
  color: #EEC044;
  text-align: center;
}

.service-portion {
  margin: 60px 10px 60px 10px;

}

.service-portion h2 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 30px;
  text-align: center;
}

#serice {
  display: flex;
  justify-content: space-around;
  align-items: center;
  min-height: 100vh;
  background-color: #f4f4f4;
}

.service-box {
  text-align: center;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 8px;
  margin: 10px;
}

.service-box img {
  max-width: 100%;
  height: auto;
  border-radius: 50%;
  margin-bottom: 10px;
}

.service-box h2 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.service-box p {
  color: #666;
}

/* .images-portion-service img {
  width: 200px;
} */
.image-2 {
  z-index: 0;
  /* Lower z-index to appear behind */
  left: 50%;
  /* Move the second image halfway */
  transform: translateX(-50%);
  margin-top: 10%;
  height: 400px;
  width: 300px;
}

.image-1 {
  height: 500px;
  width: 300px;
}

.text-area {
  padding: 6% 5% 10% 5%;
}

.text-area h4 {
  font-size: 20px;
  font-family: 'Courier New', Courier, monospace;
  color: #EEC044;
}

.text-area h2 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 30px;
  /* text-align: center; */
}

.text-area h3 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 15px;
}

.text-area p {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 14px;
}

.after-service-banner {
  display: flex;
  flex-direction: row;
  gap: 50px;
}

.images-portion-service {
  display: flex;
  flex-direction: row;
}

.right-text h4 {
  font-size: 20px;
  font-family: 'Courier New', Courier, monospace;
  color: #EEC044;
}

.left-text p {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 14px;
  padding-top: 70px;
}

.fourth-banner {
  display: flex;
  flex-direction: row;
  padding: 4% 12% 4% 12%;
  gap: 20%;
}

.right-text h2 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 30px;
  /* text-align: center; */
}

.fifth-banner {
  overflow: hidden;
  /* display: block; */
  margin-bottom: 30px;
}

.fifth-banner img {
  width: 1350px;
  /* border-top-left-radius: 50%; */
  /* border-bottom-left-radius: 50%; */
}

.six-banner {
  background-image: url('@/assets/Images/fifth.png');
  margin-bottom: 40px;
  height: 200px;
}
</style>
