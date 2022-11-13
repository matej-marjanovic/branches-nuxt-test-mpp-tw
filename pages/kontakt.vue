<template>
  <div class="text-gray-600 body-font">
    <!-- component -->
    <section>
      <div class="mx-auto max-w-screen-xl px-4 py-4 sm:px-6 lg:px-8">
        <div class="mt-8 grid grid-cols-1 gap-8 md:grid-cols-2">
          <div class="relative overflow-hidden">
            <div class="flex items-center justify-center p-4">
              <!-- Author: FormBold Team -->
              <!-- Learn More: https://formbold.com -->
              <div class="mx-auto w-full">
                <form action="https://formbold.com/s/9x5N3" method="POST">
                  <div class="mb-5">
                    <label
                      for="name"
                      class="mb-3 block text-base font-medium text-[#07074D]"
                    >
                      Full Name
                    </label>
                    <input
                      type="text"
                      name="name"
                      id="name"
                      placeholder="Full Name"
                      class="
                        w-full
                        rounded-md
                        border border-[#e0e0e0]
                        bg-white
                        py-3
                        px-6
                        text-base
                        font-medium
                        text-[#6B7280]
                        outline-none
                        focus:border-[#6A64F1] focus:shadow-md
                      "
                    />
                  </div>
                  <div class="mb-5">
                    <label
                      for="email"
                      class="mb-3 block text-base font-medium text-[#07074D]"
                    >
                      Email Address
                    </label>
                    <input
                      type="email"
                      name="email"
                      id="email"
                      placeholder="example@domain.com"
                      class="
                        w-full
                        rounded-md
                        border border-[#e0e0e0]
                        bg-white
                        py-3
                        px-6
                        text-base
                        font-medium
                        text-[#6B7280]
                        outline-none
                        focus:border-[#6A64F1] focus:shadow-md
                      "
                    />
                  </div>

                  <!-- <div class="mb-5">
                    <label
                      for="subject"
                      class="mb-3 block text-base font-medium text-[#07074D]"
                    >
                      Subject
                    </label>
                    <input
                      type="text"
                      name="subject"
                      id="subject"
                      placeholder="Enter your subject"
                      class="
                        w-full
                        rounded-md
                        border border-[#e0e0e0]
                        bg-white
                        py-3
                        px-6
                        text-base
                        font-medium
                        text-[#6B7280]
                        outline-none
                        focus:border-[#6A64F1] focus:shadow-md
                      "
                    />
                  </div> -->

                  <div class="mb-5">
                    <label
                      for="message"
                      class="mb-3 block text-base font-medium text-[#07074D]"
                    >
                      Message
                    </label>
                    <textarea
                      rows="4"
                      name="message"
                      id="message"
                      placeholder="Type your message"
                      class="
                        w-full
                        resize-none
                        rounded-md
                        border border-[#e0e0e0]
                        bg-white
                        py-3
                        px-6
                        text-base
                        font-medium
                        text-[#6B7280]
                        outline-none
                        focus:border-[#6A64F1] focus:shadow-md
                      "
                    ></textarea>
                  </div>
                  <div>
                    <button
                      class="
                        hover:shadow-form
                        rounded-md
                        bg-[#6A64F1]
                        py-3
                        px-8
                        text-base
                        font-semibold
                        text-white
                        outline-none
                      "
                    >
                      Pošlji sporočilo
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>

          <div class="lg:py-4 px-4">
            <article class="space-y-4 text-gray-600">
              <h2 class="text-gray-900 text-lg mb-1 font-medium title-font">
                Kontakt
              </h2>
              <p class="leading-relaxed mb-5 text-gray-600">
                V stik z nami lahko stopite preko spodnjega formularja, preko
                emaila (info@mpp.si) ali pa nas enostavno pokličete na 041 447
                058 (Pavel).
              </p>
              <h2 class="text-gray-900 text-lg mb-1 font-medium title-font">
                Naslov in bančne informacije
              </h2>
              <div class="paragraph">
                ​MPP d.o.o.<br />Brezje 80e<br />4243 Brezje<br />​Slovenija<br />Telefon:
                041 447 058<br />E-pošta: info@mpp.si<br /><br /><strong
                  >Bančni račun</strong
                ><br />IBAN: SI56 07000-0000486254<br />GORENJSKA BANKA, d.d.,
                Kranj, Slovenija<br />SWIFT: GORESI2X
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>

    <div class="mx-auto max-w-screen-xl relative inset-0 bg-gray-300 min-h-[450px]">
      <div class="absolute inset-0 bg-gray-300">
        <!-- <iframe
        width="100%"
        height="100%"
        frameborder="0"
        marginheight="0"
        marginwidth="0"
        title="map"
        scrolling="no"
        src="https://maps.google.com/maps?width=100%&height=600&hl=en&q=Brezje+(MPP)&ie=UTF8&t=&z=14&iwloc=B&output=embed"
        style=""
      ></iframe> -->
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d301180.72308223863!2d14.19336724988089!3d46.268980274866806!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477abdd74c63300f%3A0xd53b96b621c19b0!2sMpp%2C%20podjetje%20za%20proizvodno%2C%20trgovino%20in%20storitve%2C%20d.o.o.!5e0!3m2!1sen!2ssi!4v1668269991521!5m2!1sen!2ssi"
          width="100%"
          height="100%"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
    </div>
  </div>
</template>
