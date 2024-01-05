<script>

export default {
  name:'NetflixLandingPage',
  data(){
    return{
      show:false
    }

  },
  methods:{
    showMore(){
      this.show=!this.show
    }
  }
}
</script>

<template>
  <div>
    <section class="section-one">
      <div class="nav-bar">
        <div class="netflix-logo">
          <img src="../../assets/images/netflixlogo2.png"/>
        </div>
        <div class="sign-in">
          <button class="btn-1">Sign In</button>
        </div>
      </div>
      <div class="section-one-body">
        <div class="section-one-text">
        <h1>Unlimited movies, TV shows, and more</h1>
        <p>Watch anywhere. Cancel anytime.</p>
        <div class="section-one-form">
          <p>Ready to watch? Enter your email to create or restart your membership.</p>
          <div class="form">
            <div class="input">
              <input type="email" placeholder="Email address" name="email">
            </div>
            <button class="get-started-btn" >
              Get Started
              <div aria-hidden="true" class="right-cursor"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" data-mirrorinrtl="true" class="default-ltr-cache-4z3qvp e1svuwfo1" data-name="ChevronRight" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" d="M15.5859 12L8.29303 19.2928L9.70725 20.7071L17.7072 12.7071C17.8948 12.5195 18.0001 12.2652 18.0001 12C18.0001 11.7347 17.8948 11.4804 17.7072 11.2928L9.70724 3.29285L8.29303 4.70706L15.5859 12Z" fill="currentColor"></path></svg></div>
            </button>
          </div>
        </div>
        </div>
      </div>
    </section>
    <hr class="divider">
    <section class="section-two" style="background-color: black">
      <div class="section-two-body">
        <div class="section-two-text">
          <h1 class="heading-text">Enjoy on your TV</h1>
          <p class="body-text" style="padding-top: 15px">Watch on Smart TVs, PlayStations, Xbox,</p>
          <p class="body-text">Chromecast, Apple TV, Blu-ray players, and</p>
          <p class="body-text">more.</p>
        </div>
        <div class="section-two-image e9eyrqp3">
          <div class="default-ltr-cache-bjn8wh">
            <img alt="" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png" data-uia="nmhp-card-animation-asset-image" class="default-ltr-cache-1d3w5wq">
              <div data-uia="nmhp-card-animation-asset-motion" class="section-two-video e15c37ii14">
                <video data-uia="nmhp-card-animation-asset-video" autoplay="" playsinline="" muted="" loop=""><source src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-0819.m4v" type="video/mp4"></video>
                <div class="default-ltr-cache-0"></div><div data-uia="nmhp-card-animation-asset-custom" aria-hidden="true" class="default-ltr-cache-0 e15c37ii13"></div>
              </div>
          </div>
        </div>
      </div>
    </section>
    <hr class="divider" >
    <section class="section-three">
      <div class="section-three-body">
        <div class="section-three-img" style="width: 522px; height: 413.5px">
          <div class="sect-3-img">
            <img alt="" style="width: 506px; height: 409.5px; position: relative"    src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg" data-uia="nmhp-card-animation-asset-image" class="default-ltr-cache-1d3w5wq">
            <div data-uia="nmhp-card-animation-asset-motion" class="sect-3-box" style="width: 301px; height: 104px">
            <div class="default-ltr-cache-1cn8kex">
              <img data-uia="nmhp-card-animation-asset-animation" alt="" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/boxshot.png" class="default-ltr-cache-1t1z3a4">
            </div>
              <div class="stranger-things">
                <div id="" class="stranger-things-text" data-uia="">Stranger Things</div>
                <div id="" class="downloading" data-uia="">Downloading...</div>
              </div>
              <div data-uia="nmhp-card-animation-asset-custom" aria-hidden="true" class="sect-3-animation"></div>
            </div>
          </div>
        </div>
        <div class="section-three-text">
          <p class="heading-text">Download your shows </p>
          <p class="heading-text">to watch offline</p>
          <p class="body-text">Save your favorites easily and always have </p>
          <p class="body-text">something to watch.</p>
        </div>

      </div>
    </section>
    <hr class="divider" >
    <section class="section-four">
      <div class="section-four-body">
        <div style="margin-left:250px " class="section-three-text">
          <p class="heading-text" style="margin-bottom: 10px" > Watch Everywhere</p>
          <p class="body-text">Stream unlimited movies and TV</p>
          <p class="body-text">shows on your phone, tablet, laptop,</p>
          <p style="margin-bottom: 25px" class="body-text">and TV.</p>
        </div>
      </div>
    </section>
    <hr class="divider">
    <section class="section-five">
      <div class="section-four-body">
        <div class="sect-5-img">
          <div class="img"><img alt="" src="https://occ-0-5544-300.1.nflxso.net/dnm/api/v6/19OhWN2dO19C9txTON9tvTFtefw/AAAABejKYujIIDQciqmGJJ8BtXkYKKTi5jiqexltvN1YmvXYIfX8B9CYwooUSIzOKneblRFthZAFsYLMgKMyNfeHwk16DmEkpIIcb6A3.png?r=f55" data-uia="nmhp-card-animation-asset-image" class="default-ltr-cache-1d3w5wq">
           <div data-uia="nmhp-card-animation-asset-motion" class="default-ltr-cache-3snzoc e15c37ii15">
            <div class="default-ltr-cache-0"></div>
            <div data-uia="nmhp-card-animation-asset-custom" aria-hidden="true" class="default-ltr-cache-0 e15c37ii2"></div>
           </div>
          </div>
        </div>
        <div class="section-three-text">
          <p class="heading-text">Create profiles for</p>
          <p style="margin-bottom: 10px" class="heading-text">kids</p>
          <p class="body-text">Send kids on adventures with their favorite </p>
          <p class="body-text">characters in a space made just for them—free </p>
          <p class="body-text">with your membership.</p>

        </div>
      </div>

    </section>
    <hr class="divider">
    <section class="section-six">
      <div class="top-container">
        <div class="heading-text">
          Frequently Asked Questions
        </div>
        <div class="questions-list">
          <div class="faq">
            <div @click="show = 1" class="main" v-if="show!==1">
              <div class="body-text">What is Netflix?</div>
              <div v-if="show !== 1"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===1">
              <div class="body-text">What is Netflix?</div>
              <div v-if="show !== 1"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 1" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 1}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">Netflix is a streaming service that offers a wide variety of award-winning TV shows, movies, anime, documentaries, and more on thousands of internet-connected devices.<br><br>You can watch as much as you want, whenever you want without a single commercial – all for one low monthly price. There's always something new to discover and new TV shows and movies are added every week!</span>            </div>
          </div>
          <div class="faq">
            <div @click="show = 2" class="main" v-if="show!==2">
              <div class="body-text">How much does Netflix cost?</div>
              <div v-if="show !== 2"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===2">
              <div class="body-text">How much does Netflix cost?</div>
              <div v-if="show !== 2"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 2" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 2}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">Watch Netflix on your smartphone, tablet, Smart TV, laptop, or streaming device, all for one fixed monthly fee. Plans range from ₦1,200 to ₦4,400 a month. No extra costs, no contracts.</span>            </div>
          </div>
          <div class="faq">
            <div @click="show = 3" class="main" v-if="show!==3">
              <div class="body-text">Where can I watch?</div>
              <div v-if="show !== 3"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===3">
              <div class="body-text">Where can I watch?</div>
              <div v-if="show !== 3"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 3" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 3}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">Watch anywhere, anytime. Sign in with your Netflix account to watch instantly on the web at netflix.com from your personal computer or on any internet-connected device that offers the Netflix app, including smart TVs, smartphones, tablets, streaming media players and game consoles.<br><br>You can also download your favorite shows with the iOS, Android, or Windows 10 app. Use downloads to watch while you're on the go and without an internet connection. Take Netflix with you anywhere.</span>
            </div>
          </div>
          <div class="faq">
            <div @click="show = 4" class="main" v-if="show!==4">
              <div class="body-text">How do I cancel?</div>
              <div v-if="show !== 4"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===4">
              <div class="body-text">How do I cancel?</div>
              <div v-if="show !== 4"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 4" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 4}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">Netflix is flexible. There are no pesky contracts and no commitments. You can easily cancel your account online in two clicks. There are no cancellation fees – start or stop your account anytime.</span>
            </div>
          </div>
          <div class="faq">
            <div @click="show = 5" class="main" v-if="show!==5">
              <div class="body-text">What can I watch on Netflix?</div>
              <div v-if="show !== 5"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===5">
              <div class="body-text">What can I watch on Netflix?</div>
              <div v-if="show !== 5"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 5" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 5}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">Netflix has an extensive library of feature films, documentaries, TV shows, anime, award-winning Netflix originals, and more. Watch as much as you want, anytime you want.</span>
            </div>
          </div>
          <div class="faq">
            <div @click="show = 6" class="main" v-if="show!==6">
              <div class="body-text">Is Netflix good for kids?</div>
              <div v-if="show !== 6"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div @click="show = 0" class="main" v-if="show===6">
              <div class="body-text">Is Netflix good for kids?</div>
              <div v-if="show !== 6"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
              <div v-if="show === 6" style="transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(45deg) skew(0deg, 0deg);"><svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg" class="elj7tfr3 e164gv2o4 default-ltr-cache-l7vm9h e1svuwfo1" data-name="Plus" alt=""><path fill-rule="evenodd" clip-rule="evenodd" d="M17 17V3H19V17H33V19H19V33H17V19H3V17H17Z" fill="currentColor"></path></svg></div>
            </div>
            <div class="answer" :class="{'show':show=== 6}" style="opacity: 0; visibility: hidden; display: none; transform: translateY(0px) translateX(0px);">
              <span id="" data-uia="">The Netflix Kids experience is included in your membership to give parents control while kids enjoy family-friendly TV shows and movies in their own space.<br><br>Kids profiles come with PIN-protected parental controls that let you restrict the maturity rating of content kids can watch and block specific titles you don’t want kids to see.</span>
            </div>
          </div>
      </div>
    </div>
      <div class="section-one-form" style="margin-top: 15px; color: white;" >
        <p>Ready to watch? Enter your email to create or restart your membership.</p>
        <div class="form">
          <div class="input">
            <input type="email" placeholder="Email address" name="email">
          </div>
          <button class="get-started-btn">
            Get Started
            <a aria-hidden="true" class="right-cursor"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" data-mirrorinrtl="true" class="default-ltr-cache-4z3qvp e1svuwfo1" data-name="ChevronRight" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" d="M15.5859 12L8.29303 19.2928L9.70725 20.7071L17.7072 12.7071C17.8948 12.5195 18.0001 12.2652 18.0001 12C18.0001 11.7347 17.8948 11.4804 17.7072 11.2928L9.70724 3.29285L8.29303 4.70706L15.5859 12Z" fill="currentColor"></path></svg></a>
          </button>
        </div>
      </div>
      <hr class="divider" style="margin-top: 4.5rem">
    </section>

    <section class="footer">
      <a class="heading">
        Questions? Contact us.
      </a>
      <div class="body">
        <div class="column-container">
          <p>FAQ</p>
          <p>Investor Relations</p>
          <p>Privacy</p>
          <p>Speed Test</p>
        </div>
        <div class="column-container">
          <p>Help Center</p>
          <p>Jobs</p>
          <p>Cookie Preferences</p>
          <p>Legal Notices</p>
        </div>
        <div class="column-container">
          <p>Account</p>
          <p>Ways to Watch</p>
          <p>Cooperate Information</p>
          <p>Only on Netflix</p>
        </div>
        <div class="column-container">
          <p>Media Center</p>
          <p>Terms of Use</p>
          <p>Contact Us</p>
        </div>
      </div>
      <div class="bottom">
        <div data-layout="wrapper" class="default-ltr-cache-1b5mvc4 eslj5pt1"><div data-layout="container" class="default-ltr-cache-nmlfow eslj5pt0"><div data-layout="item" class="default-ltr-cache-18q8s1z ew2l6qe0"><div data-uia="language-picker+container" class=" e1jlx6kl1 default-ltr-cache-ei04ff ea3diy34"><label for="da919ca9ae4a1" data-uia="language-picker+label" class="default-ltr-cache-ftuahm ea3diy31">Select Language</label><div class="default-ltr-cache-1goff39 ea3diy33"><div role="img" aria-hidden="true" class="default-ltr-cache-iyxs8w e1vkmu654"><svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" class="default-ltr-cache-4z3qvp e1svuwfo1" data-name="Languages" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" d="M10.7668 5.33333L10.5038 5.99715L9.33974 8.9355L8.76866 10.377L7.33333 14H9.10751L9.83505 12.0326H13.4217L14.162 14H16L12.5665 5.33333H10.8278H10.7668ZM10.6186 9.93479L10.3839 10.5632H11.1036H12.8856L11.6348 7.2136L10.6186 9.93479ZM9.52722 4.84224C9.55393 4.77481 9.58574 4.71045 9.62211 4.64954H6.41909V2H4.926V4.64954H0.540802V5.99715H4.31466C3.35062 7.79015 1.75173 9.51463 0 10.4283C0.329184 10.7138 0.811203 11.2391 1.04633 11.5931C2.55118 10.6795 3.90318 9.22912 4.926 7.57316V12.6667H6.41909V7.51606C6.81951 8.15256 7.26748 8.76169 7.7521 9.32292L8.31996 7.88955C7.80191 7.29052 7.34631 6.64699 6.9834 5.99715H9.06968L9.52722 4.84224Z" fill="currentColor"></path></svg></div><select id="da919ca9ae4a1" name="LanguageSelect" data-uia="language-picker"><option selected="" lang="en" label="English" value="en-NG">English</option></select><div aria-hidden="true" class="default-ltr-cache-emv211 ea3diy32"><svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" class="default-ltr-cache-4z3qvp e1svuwfo1" data-name="CaretDown" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" d="M11.5976 6.5C11.7461 6.5 11.8204 6.67956 11.7154 6.78457L8.23574 10.2643C8.10555 10.3945 7.89445 10.3945 7.76425 10.2643L4.28457 6.78457C4.17956 6.67956 4.25393 6.5 4.40244 6.5H11.5976Z" fill="currentColor"></path></svg></div></div></div></div></div></div>
        <div class="column-container" style="text-decoration: none">Netflix Nigeria</div>
      </div>

    </section>





  </div>
</template>

<style scoped lang="scss">

@font-face {
  font-family: 'Netflix Sans Bold';
  src: url("../../assets/font/NetflixSans-Bold.woff2");
  font-weight: bold;
}
@font-face {
  font-family: 'Netflix Sans Regular';
  src: url("../../assets/font/NetflixSans-Regular.woff2");
  font-weight: normal;
}

.nav-bar{
  display: flex;
  flex-direction: row;
  padding: 0 147px 0 147px;
  justify-content: space-between;
  height: 70px;
}
.section-two{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: auto;
  padding: 4.5rem 0;

}
.sign-in{
margin-top: 40px;
}
.questions-list{
  display: flex;
  flex-direction: column;
  gap:9px;
  justify-content: center;
  align-items: center;
}
.faq{
  display: flex;
  cursor: pointer;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  width: 1000px;
  color: white;
}
.heading{
  cursor: pointer;
  text-decoration: underline;
  font-size: 1rem;
  font-family: "Netflix Sans Regular", sans-serif;
}
.body{
  display: flex;
  flex-direction: row;
  gap:140px;
  text-decoration: underline;
  font-family: "Netflix Sans Regular", sans-serif;
  font-size:  0.875rem;
}
.main{
  padding: 1.5rem;
  align-items: center;
  height: 84px;
  background-color: rgb(45,45,45);
  color: white;
  transition: background-color .2s!important;
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.main:hover{
  background-color: rgb(65,65,65);

}
.netflix-logo img{
  width: 180px;
  height: 100px;
}
.btn-1{
  font-family: "Netflix Sans Regular", sans-serif;
  justify-content: center;
  letter-spacing: normal;
  font-size: 0.875rem;
  font-weight: 500;
  min-height: 2rem;
  width: 76.91px;
  height: 32px;
  border: none;
  border-radius: 0.25rem;
  text-align: center;
  background: rgb(229, 9, 20);
  color: white;
  cursor: pointer;
}
.section-one-text{
  margin-top: 155px;
  opacity:1
}
.section-one-text h1{
  font-family: "Netflix Sans Regular", sans-serif;
  font-size: 48px;
  font-weight: 900;
  letter-spacing: 0;
}
.column-container{
  display: flex;
  flex-direction: column;
  gap:16px;
}
.column-container p{
  cursor: pointer;
}

.section-one-text p{
  font-family: "Netflix Sans Regular", sans-serif;
  margin-top: 1rem;
  font-size: 24px;
}
.section-one-form{
  display: flex;
  flex-direction: column;
  align-items: center;

}
.section-one-form p{
  font-family: "Netflix Sans Regular", sans-serif;
  margin-top: 1.5rem;
  font-size: 1.25rem;
}
.form{
  display: flex;
  align-items: flex-start;
  gap:7px;
  text-align: left;
  position: relative;
  margin: 1rem auto 0;
  max-width: 36.625rem;
}
.section-three-text{
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}
.section-one-body{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  color: white;
  background-image: url("../../assets/images/netflix-background2.jpg");
  width: 100%;
  height: 100vh;
  margin-top: -70px;
}
/*.input{
  position: relative;
  display: inline-flex;
  flex-wrap: wrap;
  vertical-align: text-top;
  background: transparent;
  border: 0 solid transparent;
  width: 100%;
  height: 56px;
}*/

input::placeholder{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 10px;
}
input{
  width: 368.75px;
  height: 56px;
  color: inherit;
  padding: 1.5rem 1rem 0.5rem;
  background: transparent;
  align-items: center;
  align-content: center;
  border-radius: 0.1875rem;
  border: 1px solid rgb(118, 118, 118);

}
.answer{
  font-family: "Netflix Sans Regular", sans-serif;
  font-size: 24px;
  background-color: rgb(45,45,45);
  color: white;
  margin-top: 1px;
  width: 100%;
  padding: 1.5rem;
  text-align: left;
}

.get-started-btn{
  font-family: "Netflix Sans Regular", sans-serif;
  font-size: 1.5rem;
  font-weight: 500;
  width: 209.25px;
  height: 56px;
  border-radius: 0.1875rem;
  border: 0;
  background: rgb(229, 9, 20);
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 5px;
  cursor: pointer;

}
.right-cursor{
   display: flex;
   align-items: center;
}
.section-two-text{
  color: rgb(255,255,255);
  height: 100%;
  box-sizing: border-box;
  flex-basis: 50%;
  z-index: 1;
  width: 100%;
  text-align: left;
  padding-right: 0.375rem;
}
.heading-text{
  font-family: "Netflix Sans Bold", sans-serif;
  color: rgb(255,255,255);
  font-size: 48px;
}
.body-text{
  font-family: "Netflix Sans Regular", sans-serif;
  font-size: 24px;
  color: rgb(255,255,255);

}
.section-two-body{
  min-height: auto;
  display:flex ;
  gap:45px;
  flex-direction: row;
  justify-content: center;
  text-align: center;
  align-items: center;

}
.section-three-body{
  min-height: auto;
  display:flex ;
  flex-direction: row;
  justify-content: center;
  text-align: center;
  align-items: center;

}
.section-four-body{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.section-two-image img{
  width: 505.5px;
  height: 378.63px;
  flex-basis: 50%;
  padding: 0;
  z-index: 1;
  position: relative;
}
.sect-5-img img{
  width: 546px;
  height: 409.5px;
}

/*.section-two-video {
  z-index: -1;
  overflow: hidden;
  width: 100%;
  height: 100%;
  max-width: 73%;
  max-height: 54%;
  position: absolute;
  top: 46%;
  left: 50%;
  transform: translate(-50%, -50%);
}*/
video {
  display: inline-block;
  vertical-align: baseline;
  width: 352.33px;
  height: 197.63px;
  position: absolute;
  top:20%;
  left: 13%;
}
.default-ltr-cache-bjn8wh {
  position: relative;
}
.section-three{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-height: auto;
  padding: 4.0625rem 0;
  background-color: black;
}
.section-four{
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  width: 100%;
  min-height: auto;
  padding: 4.0625rem 0;
  background-color: black;
}
.section-five{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-height: auto;
  padding: 4.0625rem 0;
  background-color: black;
}
.footer{
  padding-top: 72px;
  padding-bottom: 72px;
  padding-left: 170px;
  color: rgba(255,255,255,0.7);
  height: auto;
  background-color: black;
  text-align: left;
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.section-six{
  background-color: black;
}
.top-container{
  gap:20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-height: auto;
  padding-top: 4.5rem;
}

.sect-3-img{
  flex-basis: 50%;
  padding: 0;
  z-index: 1;
}
.default-ltr-cache-1cn8kex img{
  width: 57.14px;
  height: 80px;
}
.sect-3-box{
  position: absolute;
  top:241%;
  right: 57.6%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 0.5rem 0.75rem;
  align-items: center;
  border: 2px solid rgba(128,128,128,0.7);
  box-shadow: 0 0 2em 0 rgb(0,0,0);
  border-radius: 0.75rem;
  background: rgb(0,0,0);

}
.sect-3-animation{
    width: 3rem;
    height: 3rem;
    outline: 2px solid rgb(0,0,0);
    outline-offset: -2px;
    display: block;
    background: url(https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/download-icon.gif) center center no-repeat;
    background-size: 100%;
    content: '';
}
.stranger-things-text{
  font-family: "Netflix Sans Bold", sans-serif !important;
  font-weight: 500 !important;
  font-size: 16px;
  color: white;
}
.downloading{
  font-size: 0.875rem;
  font-weight: 400;
  color: #0071eb;
}
hr.divider{
  height:8px;
  border-width:0;
  color:dimgray;
  background-color: rgb(35,35,35);
}
.show{
  display: block!important;
  transition: height 5s;
  visibility: visible!important;
  opacity: 1!important;


}

</style>