<template>
  <div>
    <!-- Image from: https://source.unsplash.com/1dGMs4hhcVA -->
    <!-- other link: https://unsplash.com/photos/1dGMs4hhcVA -->
    <section
      class="
        mx-auto
        max-w-screen-xl
        overflow-hidden
        bg-[url(https://images.unsplash.com/photo-1529511582893-2d7e684dd128?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxfDB8MXxyYW5kb218MHx8fHx8fHx8MTY2ODI2Njg5MQ&ixlib=rb-4.0.3&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1080)]
        bg-cover bg-center bg-no-repeat
      "
    >
      <div class="bg-black/50 p-8 md:p-12 lg:px-16 lg:py-24">
        <div class="max-w-lg text-center sm:text-left">
          <h2 class="text-2xl font-bold text-white sm:text-3xl md:text-5xl">
            Pozdravljeni!
          </h2>

          <p
            class="
              max-w-md
              text-white/90
              md:mt-6 md:block md:text-lg md:leading-relaxed
            "
          >
            Pri nas vam ponujamo ugodno priložnost za pridelavo moke vrhunske
            kvalitete. Naši proizvodi bodo poskrbeli, da žito iz vašega polja
            ohrani najboljšo prehrambno vrednost ter tako lahko postane čudovit
            kruh, žganci ali kakršnokoli pecivo si želite.
          </p>

          <div class="mt-4 sm:mt-8">
            <a
              href="#"
              class="
                inline-flex
                items-center
                rounded-full
                bg-indigo-700
                px-8
                py-3
                text-white
                shadow-lg
                transition
                hover:bg-indigo-600
                focus:outline-none focus:ring
              "
            >
              <span class="text-sm font-medium"> Izdelki </span>

              <svg
                class="ml-3 h-5 w-5"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17 8l4 4m0 0l-4 4m4-4H3"
                />
              </svg>
            </a>
          </div>

          <h2
            class="
              text-lg
              font-bold
              max-w-md
              text-white/90
              md:mt-6 md:block md:text-lg md:leading-relaxed
            "
          >
            In kakšna je najboljša moka?
          </h2>

          <p
            class="
              max-w-md
              text-white/90
              md:mt-6 md:block md:text-lg md:leading-relaxed
            "
          >
            In kakšna je najboljša moka? To se lahko vprašamo šele danes, ko se za
            zalaganje veleblagovnic uporablja gromozanske količine industrijsko
            pridelane moke, ki ji je bilo v tem procesu, kjer se gleda predvsem na
            kvantiteto in ne kvaliteto, odvzeto mnogo pomembnih sestavin. Naši
            izdelki se zgledujejo po načinu pridelave moke pred časom današnjega
            masovnega proizvajanja, ko se še ni bilo treba bati nizko kvalitetne
            moke. Z zgledom do danes skoraj "izumrlih" vaških mlinov in sit, kjer
            je moč vode neprenehoma poganjala mlin in je tako vztrajno nastajala
            izvrstna moka, vam tudi mi nudimo rešitev, ki vam bo omogočila takšno
            kvaliteto. ​Vendar tokrat brez potrebe po potoku blizu vašega doma.
          </p>
        </div>
      </div>
    </section>

    <!-- LUSCILEC  -->
    <section>
      <div class="mx-auto max-w-screen-xl px-4 py-16 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 gap-8 lg:grid-cols-2 lg:gap-16">
          <div
            class="
              relative
              h-64
              overflow-hidden
              rounded-lg
              sm:h-80
              lg:order-last lg:h-full
            "
          >
            <img
              alt="Party"
              src="https://images.unsplash.com/photo-1527529482837-4698179dc6ce?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1770&q=80"
              class="absolute inset-0 h-full w-full object-cover"
            />
          </div>

          <div class="lg:py-24">
            <h2 class="text-3xl font-bold sm:text-4xl">LUŠČILEC</h2>

            <p class="mt-4 text-gray-600">
              Zmogljiv luščilec za razne vrste žit za potrebe manjših
              pridelovalcev žita.
            </p>

            <a
              href="/luscilec"
              class="
                mt-8
                inline-flex
                items-center
                rounded
                border border-indigo-600
                bg-indigo-600
                px-8
                py-3
                text-white
                hover:bg-transparent hover:text-indigo-600
                focus:outline-none focus:ring
                active:text-indigo-500
              "
            >
              <span class="text-sm font-medium"> Več Informacij </span>

              <svg
                class="ml-3 h-5 w-5"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17 8l4 4m0 0l-4 4m4-4H3"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
