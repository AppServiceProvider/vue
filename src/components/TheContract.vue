<template>
  <div>
    <section class="contact-section section-padding" id="section_5">
      <div class="container">
        <div class="row">
          <div class="col-lg-5 col-12">
            <form
              action="#"
              method="post"
              class="custom-form contact-form"
              role="form"
            >
              <h2 class="mb-4 pb-2">Contact Tiya</h2>

              <div class="row">
                <div class="col-lg-6 col-md-6 col-12">
                  <div class="form-floating">
                    <input
                      type="text"
                      name="full-name"
                      id="full-name"
                      class="form-control"
                      placeholder="Full Name"
                      required=""/>

                    <label for="floatingInput">Full Name</label>
                  </div>
                </div>

                <div class="col-lg-6 col-md-6 col-12">
                  <div class="form-floating">
                    <input
                      type="email"
                      name="email"
                      id="email"
                      pattern="[^ @]*@[^ @]*"
                      class="form-control"
                      placeholder="Email address"
                      required=""
                    />

                    <label for="floatingInput">Email address</label>
                  </div>
                </div>

                <div class="col-lg-12 col-12">
                  <div class="form-floating">
                    <textarea
                      class="form-control"
                      id="message"
                      name="message"
                      placeholder="Describe message here"
                    ></textarea>

                    <label for="floatingTextarea">Message</label>
                  </div>

                  <button type="submit" class="form-control">
                    Submit Form
                  </button>
                </div>
              </div>
            </form>
          </div>

          <div class="col-lg-6 col-12">
            <div class="contact-info mt-5">
              <div class="contact-info-item">
                <div class="contact-info-body">
                  <strong>London, United Kingdom</strong>

                  <p class="mt-2 mb-1">
                    <a href="tel: 010-020-0340" class="contact-link">
                      (020) 010-020-0340
                    </a>
                  </p>

                  <p class="mb-0">
                    <a href="mailto:info@company.com" class="contact-link">
                      info@company.com
                    </a>
                  </p>
                </div>

                <div class="contact-info-footer">
                  <a href="#">Directions</a>
                </div>
              </div>

              <img src="../assets/images/WorldMap.svg" class="img-fluid" alt="" />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
