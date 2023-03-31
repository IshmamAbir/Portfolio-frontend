<template>
  <div
    class="rn-portfolio-area rn-section-gap section-separator"
    id="portfolio"
  >
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div
            data-aos="fade-up"
            data-aos-duration="500"
            data-aos-delay="100"
            data-aos-once="true"
            class="section-title text-center"
          >
            <span class="subtitle"
              >Visit my portfolio and keep your feedback</span
            >
            <h2 class="title">My Portfolio</h2>
          </div>
        </div>
      </div>

      <div class="row row--25 mt--10 mt_md--10 mt_sm--10">
        <!-- Start Single Portfolio -->
        <div
          data-aos="fade-up"
          data-aos-delay="100"
          data-aos-once="true"
          class="col-lg-6 col-xl-4 col-md-6 col-12 mt--50 mt_md--30 mt_sm--30"
        >
          <div
            class="rn-portfolio"
            data-toggle="modal"
            data-target="#exampleModalCenter"
          >
            <div class="inner">
              <div class="thumbnail">
                <a href="javascript:void(0)">
                  <img
                    src="@/assets/images/portfolio/portfolio-01.jpg"
                    alt="Personal Portfolio Images"
                  />
                </a>
              </div>
              <div class="content">
                <div class="category-info">
                  <div class="category-list">
                    <a href="javascript:void(0)">Development</a>
                  </div>
                  <div class="meta">
                    <span
                      ><a href="javascript:void(0)"
                        ><i class="feather-heart"></i
                      ></a>
                      600</span
                    >
                  </div>
                </div>
                <h4 class="title">
                  <a href="javascript:void(0)"
                    >The services provide for design
                    <i class="feather-arrow-up-right"></i
                  ></a>
                </h4>
              </div>
            </div>
          </div>
        </div>
        <!-- End Single Portfolio -->

        <!-- Start Single Portfolio -->
        <div
          data-aos="fade-up"
          data-aos-delay="300"
          data-aos-once="true"
          class="col-lg-6 col-xl-4 col-md-6 col-12 mt--50 mt_md--30 mt_sm--30"
        >
          <div
            class="rn-portfolio"
            data-toggle="modal"
            data-target="#exampleModalCenter"
          >
            <div class="inner">
              <div class="thumbnail">
                <a href="javascript:void(0)">
                  <img
                    src="@/assets/images/portfolio/portfolio-02.jpg"
                    alt="Personal Portfolio Images"
                  />
                </a>
              </div>
              <div class="content">
                <div class="category-info">
                  <div class="category-list">
                    <a href="javascript:void(0)">Application</a>
                  </div>
                  <div class="meta">
                    <span
                      ><a href="javascript:void(0)"
                        ><i class="feather-heart"></i
                      ></a>
                      750</span
                    >
                  </div>
                </div>
                <h4 class="title">
                  <a href="javascript:void(0)"
                    >Mobile app landing design & app maintain<i
                      class="feather-arrow-up-right"
                    ></i
                  ></a>
                </h4>
              </div>
            </div>
          </div>
        </div>
        <!-- End Single Portfolio -->

        <!-- Start Single Portfolio -->
        <div
          data-aos="fade-up"
          data-aos-delay="500"
          data-aos-once="true"
          class="col-lg-6 col-xl-4 col-md-6 col-12 mt--50 mt_md--30 mt_sm--30"
        >
          <div
            class="rn-portfolio"
            data-toggle="modal"
            data-target="#exampleModalCenter"
          >
            <div class="inner">
              <div class="thumbnail">
                <a href="javascript:void(0)">
                  <img
                    src="@/assets/images/portfolio/portfolio-03.jpg"
                    alt="Personal Portfolio Images"
                  />
                </a>
              </div>
              <div class="content">
                <div class="category-info">
                  <div class="category-list">
                    <a href="javascript:void(0)">Photoshop</a>
                  </div>
                  <div class="meta">
                    <span
                      ><a href="javascript:void(0)"
                        ><i class="feather-heart"></i
                      ></a>
                      630</span
                    >
                  </div>
                </div>
                <h4 class="title">
                  <a href="javascript:void(0)"
                    >Logo design creativity & Application
                    <i class="feather-arrow-up-right"></i
                  ></a>
                </h4>
              </div>
            </div>
          </div>
        </div>
        <!-- End Single Portfolio -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppPortfolio",
};
</script>
