<template>
  <main>
    <section class="section-fading">
      <div class="container">
        <h1 class="section-header intro-header">
          A social media marketing platform <br />
          that <span class="poppins-bold">actually</span> helps you grow
        </h1>
        <div class="row">
          <div class="col-md-6">
            <img
              src="../assets/Hp--visual--planner-f0bab8b1.png"
              alt="Visual Planner Image"
              style="max-width: 100%"
            />
          </div>
          <div class="col-md-6">
            <h6 class="salmon-text section-subheader">Visual Planner</h6>
            <h1>Plan a month's worth of social media posts in minutes</h1>
            <p>
              Scheduling your social media content is as simple as
              dragging-and-droppinf. No, serviously, Later will tell you your
              unique Best Time to Post, so you can schedule in batches and
              publish without a hitch.
            </p>
            <br />
            <a class="button" href="https://later.com/schedule/"
              >Visual Planner
              <b-icon-chevron-right class="icon"></b-icon-chevron-right>
            </a>
            <img
              class="decorative_icon"
              src="../assets/square.svg"
              alt="square"
              style="position: absolute; right: 0; bottom: -140px"
            />
          </div>
        </div>
      </div>
    </section>
    <section class="testimonials--section">
      <div class="container">
        <h6 class="section-header text-center">What Our Customers Say</h6>
        <div class="row justify-content-center customer_testimonial--row">
          <div class="col-lg-4 customer_testimonial--container">
            <div class="col customer_testimonial">
              <div class="row customer_testimonial-stars--row">
                <img
                  class="customer_testimonial-stars"
                  src="../assets/stars-069fa221.svg"
                  alt="5 Stars"
                />
              </div>
              <div class="row customer_testimonial-review--row">
                <p class="customer_testimonial-review">
                  We've been using Later for a little over 2 years. The visual
                  planner is one of the tools that has helped us become more
                  efficient and it's an important part of our marketing toolkit
                </p>
                <br />
                <br />
              </div>
              <div class="row customer_testimonial-profile">
                <p class="customer_testimonial-profile--info">
                  <img
                    src="../assets/ryan-babenzien-188b1ec5.png"
                    alt="Ryan Babenzien Pic"
                  />
                  <span class="customer_testimonial-profile--info__name"
                    >Ryan Babenzien</span
                  ><br />
                  <span class="custoemr_testimonial-profile--info__title"
                    >Founder and CEO of GREATS</span
                  >
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 customer_testimonial--container">
            <div class="col customer_testimonial">
              <div class="row customer_testimonial-stars--row">
                <img
                  class="customer_testimonial-stars"
                  src="../assets/stars-069fa221.svg"
                  alt="5 Stars"
                />
              </div>
              <div class="row customer_testimonial-review--row">
                <p class="customer_testimonial-review">
                  Later's powerful automation tools and helpful trainings have
                  helped drive me business forward. My business has grown with
                  the platform, taking my brand from a lowly wedding blog to a
                  successful destination wedding business.
                </p>
                <br />
                <br />
              </div>
              <div class="row customer_testimonial-profile">
                <p class="customer_testimonial-profile--info">
                  <img
                    src="../assets/olivia-desantos-39b7b4c7.png"
                    alt="Olivia DeSantos Pic"
                  />
                  <span class="customer_testimonial-profile--info__name"
                    >Olivia DeSantos</span
                  ><br />
                  <span class="customer_testimonial-profile--info__title"
                    >Wedding Planner, Nulyweds</span
                  >
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 customer_testimonial--container">
            <div class="col customer_testimonial">
              <div class="row customer_testimonial-stars--row">
                <img
                  class="customer_testimonial-stars"
                  src="../assets/stars-069fa221.svg"
                  alt="5 Stars"
                />
              </div>
              <div class="row customer_testimonial-review--row">
                <p class="customer_testimonial-review">
                  Later has enabled our team to focus on producing quality,
                  engaging content by freeing up time that would have been spent
                  on collecting user-generated assets, planning and scheduling.
                </p>
                <br />
                <br />
              </div>
              <div class="row customer_testimonial-profile">
                <p class="customer_testimonial-profile--info">
                  <img
                    src="../assets/me-undies-423a19b1.png"
                    alt="MeUndies Logo"
                  />
                  <span class="customer_testimonial-profile--info__name"
                    >Social Media Team</span
                  ><br />
                  <span class="customer_testimonial-profile--info__title"
                    >MeUndies</span
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "StyleSheet",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.decorative_icon {
  position: absolute;
}
.testimonials--section {
  padding-bottom: 60px;
}
.customer_testimonial--row .row {
  margin: 20px 0;
}
.customer_testimonial {
  background: white;
  box-shadow: $shadow;
  height: 90%;
  padding: 30px 25px;
}
.customer_testimonial p {
  font-size: $header5-size;
}
.row .customer_testimonial-stars--row {
  margin: 0;
}
.customer_testimonial-profile--info {
  position: absolute;
  bottom: 0;
  left: 0;
  padding-left: 25px;
  padding-right: 25px;
  width: 100%;
}
.customer_testimonial-profile img {
  width: 62px;
  float: left;
  margin-right: 12px;
}
.customer_testimonial-profile--info__name {
  font-weight: $bold-font-weight;
  color: $primary;
}
</style>
