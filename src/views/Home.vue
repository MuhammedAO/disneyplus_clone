<template>
  <div class="my-8">
    <vue-glide :perView="1" :bullet="true" class="mb-12">
      <vue-glide-slide>
        <router-link to="/about">
          <img src="../assets/slide1.jpg" alt="mandalorian" class="rounded" />
        </router-link>
      </vue-glide-slide>
      <vue-glide-slide>
        <router-link to="/about">
          <img src="../assets/slide2.jpg" alt="mandalorian" class="rounded" />
        </router-link>
      </vue-glide-slide>
      <vue-glide-slide>
        <router-link to="/about">
          <img src="../assets/slide3.jpg" alt="mandalorian" class="rounded" />
        </router-link>
      </vue-glide-slide>
      <vue-glide-slide>
        <router-link to="/about">
          <img src="../assets/slide1.jpg" alt="mandalorian" class="rounded" />
        </router-link>
      </vue-glide-slide>

      <template slot="control">
        <button
          data-glide-dir="<"
          class="absolute w-8 h-8 rounded-full bg-gray-500"
          style="top: calc(50% - 16px); left: 10px"
        >
          <svg
            width="18"
            height="18"
            viewBox="0 0 24 24"
            style="margin-left: 6px"
          >
            <path
              d="M0 12l10.975 11 2.848-2.828-6.176-6.176H24v-3.992H7.646l6.176-6.176L10.975 1 0 12z"
            ></path>
          </svg>
        </button>
        <button
          data-glide-dir=">"
          class="absolute w-8 h-8 rounded-full bg-gray-500"
          style="top: calc(50% - 16px); right: 10px"
        >
          <svg
            width="18"
            height="18"
            viewBox="0 0 24 24"
            style="margin-left: 6px"
          >
            <path
              d="M13.025 1l-2.847 2.828 6.176 6.176h-16.354v3.992h16.354l-6.176 6.176 2.847 2.828 10.975-11z"
            ></path>
          </svg>
        </button>``
      </template>
    </vue-glide>
    <!-- end of scroll -->

    <!-- <div class="categories flex items-center mb-12 -mx-4">
      <div class="w-1/5 px-4">
        <a
          href=""
          class="bg-gray-800 h-32 flex justify-center items-center rounded-lg border border-gray-700 shadow-custom p-4 hover:bg-gray-900"
        >
          <img src="../assets/disney_logo.svg" alt="disney" />
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a
          href=""
          class="bg-gray-800 h-32 flex justify-center items-center rounded-lg border border-gray-700 shadow-custom p-4 hover:bg-gray-900"
        >
          <img src="../assets/pixar_logo.svg" alt="disney" />
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a
          href=""
          class="bg-gray-800 h-32 flex justify-center items-center rounded-lg border border-gray-700 shadow-custom p-4 hover:bg-gray-900"
        >
          <img src="../assets/marvel_logo.svg" alt="disney" />
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a
          href=""
          class="bg-gray-800 h-32 flex justify-center items-center rounded-lg border border-gray-700 shadow-custom p-4 hover:bg-gray-900"
        >
          <img src="../assets/star_wars_logo.svg" alt="disney" />
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a
          href=""
          class="bg-gray-800 h-32 flex justify-center items-center rounded-lg border border-gray-700 shadow-custom p-4 hover:bg-gray-900"
        >
          <img src="../assets/national_geographic_logo.svg" alt="disney" />
        </a>
      </div>
    </div> -->
    <div class="categories mb-12">
      <vue-glide
        :perView="5"
        :gap="20"
        :breakpoints="{
          1024: {
            perView: 3
          },
          800: {
            perView: 2
          },
          576: {
            perView: 1,
            peek: {
              before: 0,
              after: 0
            }
          }
        }"
      >
        <vue-glide-slide>
          <router-link
            to="/about"
            href="#"
            class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900"
          >
            <img src="@/assets/disney_logo.svg" alt="disney" />
          </router-link>
        </vue-glide-slide>
        <vue-glide-slide>
          <router-link
            to="/about"
            href="#"
            class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900"
          >
            <img src="@/assets/pixar_logo.svg" alt="disney" />
          </router-link>
        </vue-glide-slide>
        <vue-glide-slide>
          <router-link
            to="/about"
            href="#"
            class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900"
          >
            <img src="@/assets/marvel_logo.svg" alt="disney" />
          </router-link>
        </vue-glide-slide>
        <vue-glide-slide>
          <router-link
            to="/about"
            href="#"
            class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900"
          >
            <img src="@/assets/star_wars_logo.svg" alt="disney" />
          </router-link>
        </vue-glide-slide>
        <vue-glide-slide>
          <router-link
            to="/about"
            href="#"
            class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900"
          >
            <img src="@/assets/national_geographic_logo.svg" alt="disney" />
          </router-link>
        </vue-glide-slide>
        <template slot="control">
          <button
            data-glide-dir="<"
            class="absolute w-8 h-8 rounded-full bg-gray-500"
            style="top:calc(50% - 16px); left: 10px"
          >
            <svg
              width="18"
              height="18"
              viewBox="0 0 24 24"
              style="margin-left: 6px"
            >
              <path
                d="M0 12l10.975 11 2.848-2.828-6.176-6.176H24v-3.992H7.646l6.176-6.176L10.975 1 0 12z"
              ></path>
            </svg>
          </button>
          <button
            data-glide-dir=">"
            class="absolute w-8 h-8 rounded-full bg-gray-500"
            style="top:calc(50% - 16px); right: 10px"
          >
            <svg
              width="18"
              height="18"
              viewBox="0 0 24 24"
              style="margin-left: 6px"
            >
              <path
                d="M13.025 1l-2.847 2.828 6.176 6.176h-16.354v3.992h16.354l-6.176 6.176 2.847 2.828 10.975-11z"
              ></path>
            </svg>
          </button>
        </template>
      </vue-glide>
    </div>
    <!-- end of categories -->
    <div class="recommended px-6 mb-12">
      <h2 class="text-gray-500 mb-1">Recommended For You</h2>
      <div class="flex item-center">
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/star_wars_a_new_hope.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""><img src="../assets/snow_white.jpg" alt="star wars"/></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/black_panther.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""><img src="../assets/zootopia.jpg" alt="star wars"/></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/one_strange_rock.jpg" alt="star wars"
          /></a>
        </div>
      </div>
    </div>
    <!--continue watching  -->
    <div class="recommended px-6 mb-12">
      <h2 class="text-gray-500 mb-1">Continue Watching</h2>
      <div class="flex item-center">
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/the_sound_of_music.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/high_school_musical.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""><img src="../assets/cinderella.jpg" alt="star wars"/></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/remember_the_titans.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/avengers_infinity_war.jpg" alt="star wars"
          /></a>
        </div>
      </div>
    </div>
    <!-- end -->
    <!-- disney+ originals -->
    <div class="recommended px-6 mb-12">
      <h2 class="text-gray-500 mb-1">Disney+ Originals</h2>
      <div class="flex item-center">
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/lady_and_the_tramp.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/the_mandalorian.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""><img src="../assets/cinderella.jpg" alt="star wars"/></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/forky_asks_a_question.jpg" alt="star wars"
          /></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href=""
            ><img src="../assets/marvel_hero_project.jpg" alt="star wars"
          /></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>
