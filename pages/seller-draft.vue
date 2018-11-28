<template>

  <div>
<header id="home" class="header h-fullscreen" style="">
      <div class="container">
        <div class="row align-items-center h-100">

          <div class="col-lg-10">
            <h1 class="display-4"><strong>Check How Many Extra Sales/Month our Private Network of 15 millions visitors/month can Drive !
            </strong>
            </h1>
            <p class="lead mt-5">Enter your Store URL to know how much extra sales/month our network can send you !</p>
            <hr class="w-10 ml-0 my-2">


              <div id="submission" class="container">
          <div class="row">

              <form class="input-glass mb-5" action="https://app.actiboost.com/sign_up" method="GET" target="_blank">
                  <div class="input-group ">
                    <input type="hidden" name="type" value="seller">
                    <input type="text" name="website" class="form-control border border-warning" placeholder="Enter your Store URL">
                    <span class="input-group-append">
                      <button class="btn btn-warning" type="submit">Get Started<i class="ti-arrow-right ml-2"></i></button>
                    </span>
                  </div>
                </form>
          <a href="#" class="learn-more a-learnmore" @click="scrollMeTo('section-features')" >Not ready to get started? Learn more</a>
            </div>
          </div>
          </div>

          <!-- <div class="col-lg-6 ml-auto">
            <div class="video-wrapper ratio-16x9 rounded shadow-6 mt-8 mt-lg-0">
              <div class="poster" style="background-image: url(/img/preview/shot-1.png)"></div>
              <button class="btn btn-circle btn-lg btn-info"><i class="fa fa-play"></i></button>
              <iframe width="560" height="315" src="https://www.youtube.com/embed/M5S_JBRjd1s?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen=""></iframe>
            </div>
          </div> -->


        </div>
      </div>
    </header><!-- /.header -->

    <div id="more" v-show="displayMore">
    <!-- Main Content -->

    <main class="main-content">


            <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Partner
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <section class="section bg-white py-6">
        <div class="container">

          <div class="partner partner-sm">
            <img src="/img/sellers/aukey.png" alt="Aukey">
            <img src="/img/sellers/klim.png" alt="Klim">
            <img src="/img/sellers/MadameParis.png" alt="Madame Paris">
            <img src="/img/sellers/twinz_up.png" alt="Twinz' Up">
            <img src="/img/sellers/zenacolor.png" alt="Zenacolor">
          </div>
          <p class="text-center">Trusted by hundreds of seller</p>

        </div>
      </section>


      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Features
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <section ref="section-features"  id="section-features" class="section" style="background-image: linear-gradient(150deg, #fdfbfb 0%, #eee 100%);">
        <div class="container">
          <header class="section-header">
            <small>FEATURES</small>
            <h2>What is Actiboost ?</h2>
            <p>A place that give you access to thousands of websites having millions of visitors/month that will be happy to promote your brand</p>
            <hr>
          </header>

         <div class="row gap-y align-items-center">
            <img src="/img/comparaison.png" alt="Cpmaraison">
          </div>

          <hr class="my-8">

          <div class="row gap-y align-items-center">
            <div class="col-md-6 ml-auto">
              <h4>Higher Sales, Higher Ranking.</h4>
              <p>By driving external traffic to your listing, Actiboost will increase your sales and ranking. More sales will drive to even more sales thanks to Actiboost.</p>
            </div>

            <div class="col-md-5 order-md-first">
              <img src="/img/vector/10.png" alt="..."/>
            </div>
          </div>


          <hr class="my-8">


          <div class="row gap-y align-items-center">
            <div class="col-md-6 mr-auto">
              <h4>Higher Brand Awareness</h4>
              <p>By driving external traffic to your listing, Actiboost will increase your sales and ranking. More sales will drive to even more sales thanks to Actiboost.</p>
            </div>

            <div class="col-md-5">
              <img src="img/vector/11.png" alt="...">
            </div>
          </div>


          <hr class="my-8">


          <div class="row gap-y align-items-center">
            <div class="col-md-6 ml-auto">
              <h4>External Trafic.</h4>
              <p>Amazon loves external traffic and will increase your ranking. Also by having your own source of traffic from Actiboost, you reduce your amazon dependency.</p>
            </div>

            <div class="col-md-5 order-md-first">
              <img src="img/vector/12.png" alt="...">
            </div>
          </div>

          <hr class="my-8">


          <div class="row gap-y align-items-center">
            <div class="col-md-6 mr-auto">
              <h4>Cheapest and less risky acquisition channel</h4>
              <p>Everytime our network make a sale you pay 9%. You can see the source of the sales in your dashboard. That’s nothing compare to other channel, where you pay per clics then hope for a sale. With us you only pay 9% ACOS. If we don’t sale you don’t pay, so there is absolutely NO risk for you.</p>
              <p>
                  Here is a sample of one of our client. We’ve generated 21 650€ of sales in 1 month, and for that amount he only paid actiboost 1948€ of sales
              </p>
            </div>

            <div class="col-md-5">
              <img src="img/vector/11.png" alt="...">
            </div>
          </div>

          <hr class="my-8">


          <div class="row gap-y align-items-center">
            <div class="col-md-6 ml-auto">
              <h4>Before/After Actiboost</h4>
              <p>Actiboost drives qualify traffic to your listing from people looking for info on google and youtube. It will increase your impression and conversion. Here is the result above for one of our clients.</p>
            </div>

            <div class="col-md-5 order-md-first">
              <img src="img/vector/12.png" alt="...">
            </div>
          </div>
        </div>
      </section>


      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Features
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <!-- <section class="section bg-gray">
        <div class="container">
          <div class="row gap-y">

            <div class="col-lg-4">
              <div class="card card-body border text-center">
                <p class="my-5"><i class="icon-layers lead-8 text-lighter"></i></p>
                <h5>Channels</h5>
                <p>Organize your team conversations in open channels. Make a channel for a project, a team, or everyone has a transparent view.</p>
                <p><a class="small-3 fw-600" href="#">Read more <i class="fa fa-angle-right small-5 pl-1"></i></a></p>
              </div>
            </div>


            <div class="col-lg-4">
              <div class="card card-body border text-center">
                <p class="my-5"><i class="icon-chat lead-8 text-lighter"></i></p>
                <h5>Direct Messages</h5>
                <p>Send messages directly to another and any person or to a small group of people for more focused conversations.</p>
                <p><a class="small-3 fw-600" href="#">Read more <i class="fa fa-angle-right small-5 pl-1"></i></a></p>
              </div>
            </div>


            <div class="col-lg-4">
              <div class="card card-body border text-center">
                <p class="my-5"><i class="icon-mic lead-8 text-lighter"></i></p>
                <h5>Calls</h5>
                <p>Take a conversation from typing to face-to-face by starting a Slack voice or video call in any Channel or Direct Message.</p>
                <p><a class="small-3 fw-600" href="#">Read more <i class="fa fa-angle-right small-5 pl-1"></i></a></p>
              </div>
            </div>

          </div>
        </div>
      </section> -->


      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | CTA
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <!-- <section class="section text-center">
        <div class="container">

          <div class="row">
            <div class="col-md-6 mx-auto">
              <p><img src="img/vector/13.png" alt="..."></p>
              <br>
              <h3 class="mb-6"><strong>Reclaim your workday</strong></h3>
              <p class="lead text-muted">Less email. More productive. Our customers see an average 48.6% reduction in internal email, helping them enjoy a simpler, more pleasant, and more productive work life.</p>
              <br>
              <a class="btn btn-lg btn-round btn-success px-7" href="#">Start now</a>
            </div>
          </div>

        </div>
      </section> -->


      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Pricing
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <!-- <section id="section-pricing" class="section bg-gray">
        <div class="container">
          <header class="section-header">
            <h2>Affordable Pricing</h2>
            <hr>
            <p class="lead">Slack for Teams is a single workspace for your small- to medium-sized company or team.</p>
          </header>


          <div class="text-center my-7">
            <div class="btn-group btn-group-toggle" data-toggle="buttons">
              <label class="btn btn-round btn-outline-dark w-150 active">
                <input type="radio" name="pricing" value="monthly" autocomplete="off" checked> Monthly
              </label>
              <label class="btn btn-round btn-outline-dark w-150">
                <input type="radio" name="pricing" value="yearly" autocomplete="off"> Yearly
              </label>
            </div>
          </div>


          <div class="row gap-y text-center">

            <div class="col-md-4">
              <div class="pricing-1">
                <p class="plan-name">Free</p>
                <br>
                <h2 class="price">free</h2>
                <p class="small text-lighter">Forever!</p>

                <div class="text-muted">
                  <small>Searchable messages up to 10K</small><br>
                  <small>10 apps or service integrations</small><br>
                  <small>5GB total file storage for the team</small><br>
                </div>

                <br>
                <p class="text-center py-3">
                  <a class="btn btn-outline-primary" href="#">Get started</a>
                </p>
              </div>
            </div>


            <div class="col-md-4">
              <div class="pricing-1 popular">
                <p class="plan-name">Standard</p>
                <br>
                <h2 class="price text-success">
                  <span class="price-unit">$</span>
                  <span data-bind-radio="pricing" data-monthly="6.67" data-yearly="75">6.67</span>
                </h2>
                <p class="small text-lighter">
                  Per user/
                  <span data-bind-radio="pricing" data-monthly="month" data-yearly="year">month</span>
                </p>

                <div class="text-muted">
                  <small>Unlimited searchable message archives</small><br>
                  <small>Unlimited apps and service integrations</small><br>
                  <small>10GB file storage per team member</small><br>
                </div>

                <br>
                <p class="text-center py-3">
                  <a class="btn btn-success" href="#" data-bind-href="pricing" data-monthly="#monthly" data-yearly="#yearly">Get started</a>
                </p>
              </div>
            </div>


            <div class="col-md-4">
              <div class="pricing-1">
                <p class="plan-name">Plus</p>
                <br>
                <h2 class="price">
                  <span class="price-unit">$</span>
                  <span data-bind-radio="pricing" data-monthly="12.5" data-yearly="120">12.5</span>
                </h2>
                <p class="small text-lighter">
                  Per user/
                  <span data-bind-radio="pricing" data-monthly="month" data-yearly="year">month</span>
                </p>

                <div class="text-muted">
                  <small>Everything in Free & Standard, and</small><br>
                  <small>SAML-based single sign-on (SSO)</small><br>
                  <small>Compliance Exports of all messages</small><br>
                </div>

                <br>
                <p class="text-center py-3">
                  <a class="btn btn-outline-primary" href="#" data-bind-href="pricing" data-monthly="#monthly" data-yearly="#yearly">Get started</a>
                </p>
              </div>
            </div>

          </div>


        </div>
      </section> -->




<!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Block 1
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->



      <section class="section">
        <div class="container">
          <header class="section-header">
            <h2>What our customer says</h2>
            <!-- <br>
            <p class="lead">We waited until we could do it right. Then we did! Instead of creating a carbon copy.</p> -->
          </header>

          <div class="row gap-y text-center">

            <div class="col-lg-4">
              <blockquote class="blockquote">
                <div><img class="avatar avatar-xl" src="/img/avatar/1.jpg" alt="..."></div>
                <br>
                <p class="small">Thanks to Actiboost, what ever i type in google around my niche i can see my product everywhere on top of the comparison chart.</p>
                <footer>Paul - Klim</footer>
              </blockquote>
            </div>

            <div class="col-lg-4">
              <blockquote class="blockquote">
                <div><img class="avatar avatar-xl" src="/img/avatar/2.jpg" alt="..."></div>
                <br>
                <p class="small">Actiboost helped us successfully launch all of our products. They currently drive more than 20 000€ sales per month.</p>
                <footer>Simon - MadameParis</footer>
              </blockquote>
            </div>

            <div class="col-lg-4">
              <blockquote class="blockquote">
                <div><img class="avatar avatar-xl" src="/img/avatar/3.jpg" alt="..."></div>
                <br>
                <p class="small">I was skeptical about it at first, but it really worked for us. I’m happy to see that our brand is now on a lot of websites, driving ton of trafic to our listings. Helped us from going to 540 BSR to 92 in our competitive categorie.</p>
                <footer>Michelle - Prosenic</footer>
              </blockquote>
            </div>

          </div>

        </div>
      </section>

      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | FAQ
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <section id="section-faq" class="section">
        <div class="container">
          <header class="section-header">
            <small>FAQ</small>
            <h2>Frequently Asked Questions</h2>
            <hr>
            <p>Got a question? We've got answers. If you have some other questions, <a href="http://help.actiboost.com/seller-faq"> check our Seller FAQs here !</a></p>
          </header>


          <!-- <div class="row gap-y">
            <div class="col-md-6 col-xl-4">
              <h5>Is this a secure site for purchases?</h5>
              <p>Absolutely! We work with top payment companies which guarantees your safety and security. All billing information is stored on our payment processing partner which has the most stringent level of certification available in the payments industry.</p>
            </div>


            <div class="col-md-6 col-xl-4">
              <h5>Can I cancel my subscription?</h5>
              <p>You can cancel your subscription anytime in your account. Once the subscription is cancelled, you will not be charged next month. You will continue to have access to your account until your current subscription expires.</p>
            </div>


            <div class="col-md-6 col-xl-4">
              <h5>How long are your contracts?</h5>
              <p>Currently, we only offer monthly subscription. You can upgrade or cancel your monthly account at any time with no further obligation.</p>
            </div>


            <div class="col-md-6 col-xl-4">
              <h5>Can I update my card details?</h5>
              <p>Yes. Go to the billing section of your dashboard and update your payment information.</p>
            </div>


            <div class="col-md-6 col-xl-4">
              <h5>Can I request refund?</h5>
              <p>Unfortunately, not. We do not issue full or partial refunds for any reason.</p>
            </div>


            <div class="col-md-6 col-xl-4">
              <h5>Can I try your service for free?</h5>
              <p>Of course! We’re happy to offer a free plan to anyone who wants to try our service.</p>
            </div>
          </div> -->

        </div>
      </section>


      <!--
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      | Subscribe
      |‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒‒
      !-->
      <!-- <section class="section py-10" style="background-image: url(img/bg/4.jpg)">
        <div class="container">
          <div class="row">
            <div class="col-md-8 col-xl-6 mx-auto">

              <div class="section-dialog bg-primary text-white shadow-6">
                <h4>Latest news direct to your inbox</h4>
                <br><br>
                <p class="text-right small pr-5">Subscribe Now</p>
                <form class="input-glass input-round" action="" method="post" target="_blank">
                  <div class="input-group">
                    <input type="text" name="EMAIL" class="form-control" placeholder="Enter Email Address">
                    <span class="input-group-append">
                      <button class="btn btn-glass btn-light" type="button">Sign up <i class="ti-arrow-right fs-9 ml-2"></i></button>
                    </span>
                  </div>
                </form>
              </div>

            </div>
          </div>
        </div>
      </section> -->


    </main>


    <!-- Footer -->
    <!-- <footer id="footer" class="footer py-9">
      <div class="container">
        <div class="row gap-y">

          <div class="col-xl-4 order-md-last">
            <h6 class="mb-4"><strong>Get Started</strong></h6>
            <p>Form so, head allowed how found at right, chosen put sad. Copy of field phase offers texts. Great family there first about that.</p>
            <a class="btn btn-primary mr-2" href="#">Start trial</a>
            <a class="btn btn-secondary" href="#">Contact</a>
          </div>

          <div class="col-6 col-md-4 col-xl-2">
            <h6 class="mb-4"><strong>Product</strong></h6>
            <div class="nav flex-column">
              <a class="nav-link" href="#">Features</a>
              <a class="nav-link" href="#">Pricing</a>
              <a class="nav-link" href="#">Security</a>
              <a class="nav-link" href="#">Help</a>
              <a class="nav-link" href="#">Success Story</a>
            </div>
          </div>

          <div class="col-6 col-md-4 col-xl-2">
            <h6 class="mb-4"><strong>Company</strong></h6>
            <div class="nav flex-column">
              <a class="nav-link" href="#">About</a>
              <a class="nav-link" href="#">Blog</a>
              <a class="nav-link" href="#">Press</a>
              <a class="nav-link" href="#">Policy</a>
              <a class="nav-link" href="#">Contact</a>
            </div>
          </div>

          <div class="col-xl-4 order-md-first">
            <h6 class="mb-4"><strong>We Are Awesome</strong></h6>
            <p>We’re a team of experienced designers and developers. We can combine beautiful, modern designs with clean, functional and high-performance code to produce stunning websites.</p>
            <small class="opacity-70">© 2018 TheThemeio. All rights reserved.</small>
          </div>

        </div>
      </div>
    </footer>/.footer -->
    </div>
     <!-- Scroll top -->
    <button class="btn btn-circle btn-primary scroll-top"><i class="fa fa-angle-up"></i></button>


    <!-- Scripts -->
    <script src="js/page.min.js"></script>
    <script src="js/script.js"></script>
  </div>





</template>

<script>


export default {
  data() {
    return {
      displayMore: false
    }
  },
  methods: {
    scrollMeTo(refName) {
      this.displayMore = true;

      // var element = this.$refs[0];

      // console.log(this.$refs)
      this.$nextTick(function () {
        var el = this.getEl(refName);
        var top = el.offsetTop;

        window.scrollTo({ top: top, behavior: 'smooth' });

      })
    },
    getEl: function(name) {
      return document.getElementById(name);
    }
  },

}
</script>

<style>

</style>
