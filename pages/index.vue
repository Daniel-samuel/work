<template>
  <div class="mb-10">
    <nav class="container mx-auto flex items-center justify-between">
      <div class="hidden md:flex items-center space-x-10 py-10">
        <a href="" class="text-[#686C75] hover:opacity-80">HOME</a>
        <a href="" class="text-[#686C75] hover:opacity-80">ABOUT</a>
        <a href="" class="text-[#686C75] hover:opacity-80">SERVICE</a>
      </div>
      <div>
        <h2 class="text-2xl font-bold md:text-3xl py-10">Wok-Space</h2>
      </div>
      <div class="hidden md:flex items-center space-x-10">
        <a href="" class="text-[#686C75] hover:opacity-80">SERVICE</a>
        <a href="" class="text-[#686C75] hover:opacity-80">SPACES</a>
        <a href="" class="text-[#686C75] hover:opacity-80">EVENTS</a>
      </div>
      <button id="menu-btn" class="block hamburger md:hidden">
        <span class="hamburger-top"></span>
        <span class="hamburger-middle"></span>
        <span class="hamburger-bottom"></span>
      </button>
    </nav>
    <div class="md:hidden">
      <div
        id="menu"
        class="absolute flex-col z-10 items-center hidden self-end py-8 mt-10 space-y-6 font-bold bg-white sm:w-auto sm:self-center left-6 right-6 drop-shadow-md"
      >
        <a href="#">HOME</a>
        <a href="#">ABOUT</a>
        <a href="#">SERVICE</a>
        <a href="#">SPACES</a>
        <a href="#">EVENTS</a>
      </div>
    </div>

    <!--  -->

    <div class="mb-20">
      <div
        class="container mx-auto flex flex-col items-center md:flex-row mb-10"
      >
        <div class="w-full md:w-1/2">
          <img
            src="@/assets/css/icons/header-icon.svg"
            class="mb-4 animate-bounce"
            alt=""
          />
          <h1
            class="text-3xl font-bold md:text-[2.5rem] lg:text-5xl max-w-sm md:max-w-md mb-10"
          >
            We help you to increase your working productivity
          </h1>
        </div>
        <div class="right-0 top-0 space-x-14 flex items-center">
          <div class="">
            <img
              src="@/assets/css/images/coworking-space-21.png"
              class="w-full h-fit"
              alt=""
            />
          </div>
          <div class="hidden md:block">
            <img
              src="@/assets/css/images/coworking-space-31.png"
              class="w-full"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>

    <!-- Partners -->
    <div class="container mx-auto justify-center mb-32">
      <div class="hidden md:flex flex-row justify-center space-x-12">
        <div class="">
          <img src="@/assets/css/icons/google.svg" alt="" />
        </div>
        <div class="">
          <img src="@/assets/css/icons/slack.svg" alt="" />
        </div>
        <div class="">
          <img src="@/assets/css/icons/atlassian.svg" alt="" />
        </div>
        <div class="">
          <img src="@/assets/css/icons/dropbox.svg" alt="" />
        </div>
        <div class="">
          <img src="@/assets/css/icons/shopify.svg" alt="" />
        </div>
      </div>
      <div class="block md:hidden">
        <div class="flex flex-row justify-center space-x-12 mb-10">
          <div class="">
            <img src="@/assets/css/icons/google.svg" alt="" />
          </div>
          <div class="">
            <img src="@/assets/css/icons/slack.svg" alt="" />
          </div>
          <div class="">
            <img src="@/assets/css/icons/atlassian.svg" alt="" />
          </div>
        </div>
        <div class="flex flex-row justify-center space-x-12">
          <div class="">
            <img src="@/assets/css/icons/dropbox.svg" alt="" />
          </div>
          <div class="">
            <img src="@/assets/css/icons/shopify.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
    <!-- serc=vice -->
    <div class="container mx-auto mb-40">
      <div
        class="flex flex-col-reverse justify-left space-x-16 md:flex-row md:justify-center md:items-end"
      >
        <div class="w-full md:w-1/2">
          <img
            src="@/assets/css/images/coworking-spac11.png"
            class="w-full"
            alt=""
          />
        </div>
        <div class="w-full md:w-1/2 text-left mb-10">
          <h3 class="text-xl font-medium tracking-[3px] text-purple-heart mb-6">
            SERVICES
          </h3>
          <h1
            class="max-w-sm text-3xl lg:max-w-md md:text-6xl tracking-[3px] leading-[5rem] font-bold mb-10"
          >
            Solutions designed for all your needs
          </h1>
          <p class="text-md leading-[3rem] mb-20">
            Coworking is an arrangement in which workers of different companies
            share an office space, allowing cost savings and convenience through
            the use of common infrastructures, such as equipment, utilities, and
            receptionist and custodial services, and in some cases refreshments
            and parcel acceptance services.
          </p>
          <div class="flex flex-row space-x-12">
            <button
              class="bg-purple-heart text-white text-md py-4 px-7 rounded-md hover:opacity-95"
            >
              View Availability
            </button>
            <img
              src="@/assets/css/icons/3d-tour.svg"
              class="cursor-pointer animate-bounce"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>

    <!-- Vision -->
    <div class="container mx-auto mb-20">
      <div
        class="flex flex-col justify-left lg:flex-row md:justify-center md:items-end"
      >
        <div class="w-full text-left">
          <h3 class="text-xl font-medium tracking-[3px] text-purple-heart mb-6">
            VISION
          </h3>
          <h1
            class="text-[3rem] tracking-[3px] leading-[5rem] font-medium mb-10"
          >
            Our vision in Work-space is to make something
          </h1>
          <p class="text-md leading-[2.5rem] mb-14">
            Coworking is an arrangement in which workers of different companies
            share an office space, allowing cost savings and convenience through
            the use of common infrastructures services.
          </p>
          <div class="flex flex-row space-x-16 items-center">
            <div class="flex flex-row items-start mb-6 space-x-2">
              <div>
                <img src="@/assets/css/icons/hight_quality.svg" alt="" />
              </div>
              <div>
                <h6 class="font-semibold mb-3">
                  High quality co-living spaces
                </h6>
                <p class="text-sm max-w-xs">
                  Coworking is an arrangement in which workers of different
                  companies.
                </p>
              </div>
            </div>
            <div class="flex flex-row items-start mb-6 space-x-2">
              <div>
                <img src="@/assets/css/icons/equipped.svg" alt="" />
              </div>
              <div>
                <h6 class="font-semibold mb-3">Equipped for productivity</h6>
                <p class="text-sm max-w-xs">
                  Coworking is an arrangement in which workers of different
                  companies.
                </p>
              </div>
            </div>
          </div>
          <div class="flex flex-row items-start space-x-2 mb-16">
            <div>
              <img src="@/assets/css/icons/simple&inclusive.svg" alt="" />
            </div>
            <div>
              <h6 class="font-semibold mb-3">Simple and inclusive</h6>
              <p class="text-sm max-w-xs">
                Coworking is an arrangement in which workers of different
                companies.
              </p>
            </div>
          </div>
          <div class="flex flex-row space-x-12">
            <button
              class="bg-purple-heart text-white text-md py-4 px-7 rounded-md hover:opacity-95"
            >
              View Explore More
            </button>
          </div>
        </div>
        <div class="w-full">
          <img
            src="@/assets/css/images/vision-img.png"
            class="relative w-fit -mr-32"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- Why Choose us -->
    <div class="container mx-auto text-center mb-20">
      <h3 class="text-xl font-medium tracking-[3px] text-purple-heart mb-2">
        WHY CHOOSE US?
      </h3>
      <h1
        class="mx-auto text-[3rem] tracking-[3px] leading-[5rem] font-medium mb-10 max-w-lg"
      >
        The benefits that will make you comfort
      </h1>
      <div class="grid gap-4 grid-cols-2 md:grid-cols-4 lg:grid-cols-5">
        <div class="flex flex-col items-center justify-center">
          <img src="@/assets/css/icons/event.svg" class="w-14 mb-3" calt="" />
          <h1 class="font-bold text-md mb-3">Community Events</h1>
          <p class="text-xs leading-[1.5rem]">
            Allowing cost savings and convenience through the use of common
            infrastructures.
          </p>
        </div>
        <div class="flex flex-col items-center justify-center">
          <img
            src="@/assets/css/icons/exercise-facility-icon.svg"
            class="w-24 mb-3"
            calt=""
          />
          <h1 class="font-bold text-md mb-3">Exercise Facilities</h1>
          <p class="text-xs leading-[1.5rem]">
            Allowing cost savings and convenience through the use of common
            infrastructures.
          </p>
        </div>
        <div class="flex flex-col items-center justify-center">
          <img
            src="@/assets/css/icons/wifi-icon.svg"
            class="w-14 mb-3"
            calt=""
          />
          <h1 class="font-bold text-md mb-3">High-Speed Wireless</h1>
          <p class="text-xs leading-[1.5rem]">
            Allowing cost savings and convenience through the use of common
            infrastructures.
          </p>
        </div>
        <div class="flex flex-col items-center justify-center">
          <img
            src="@/assets/css/icons/globe-icon.svg"
            class="w-14 mb-3"
            calt=""
          />
          <h1 class="font-bold text-md mb-3">Global Availability</h1>
          <p class="text-xs leading-[1.5rem]">
            Allowing cost savings and convenience through the use of common
            infrastructures.
          </p>
        </div>
        <div class="flex flex-col items-center justify-center">
          <img
            src="@/assets/css/icons/confort-lounge.svg"
            class="w-14 mb-3"
            calt=""
          />
          <h1 class="font-bold text-md mb-3">Comfort Lounges</h1>
          <p class="text-xs leading-[1.5rem]">
            Allowing cost savings and convenience through the use of common
            infrastructures.
          </p>
        </div>
      </div>
    </div>

    <!-- galary -->
    <div class="container mx-auto mb-40">
      <div
        class="flex flex-col-reverse justify-left lg:flex-row md:justify-center space-x-8"
      >
        <div class="w-full lg:w-[60%] text-left md:items-center md:mx-auto">
          <h3 class="text-xl font-medium tracking-[3px] text-purple-heart mb-6">
            GALLARY
          </h3>
          <h1 class="text-[3rem] tracking-[3px] leading-[5rem] font-bold mb-10">
            Immersive beautiful co-working space gallery
          </h1>
          <div class="grid grid-cols-3 gap-8">
            <div class="max-h-52 w-full">
              <img
                src="@/assets/css/images/galary_img_1.png"
                class="h-full w-full"
                alt=""
              />
            </div>
            <div class="col-span-2 max-h-52 w-full">
              <img
                src="@/assets/css/images/galary_img_2.png"
                class="h-full w-full"
                alt=""
              />
            </div>
            <div class="col-span-2 max-h-52 w-full">
              <img
                src="@/assets/css/images/galary_img_3.png"
                class="h-full w-full"
                alt=""
              />
            </div>
            <div class="max-h-52 w-full">
              <img
                src="@/assets/css/images/galary_img_4.png"
                class="h-full w-full"
                alt=""
              />
            </div>
          </div>
        </div>
        <div class="w-full lg:w-[40%]">
          <img
            src="@/assets/css/images/galary_img_5.png"
            class="w-fit h-full md:items-center md:mx-auto mb-10"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- Become a member -->
    <div class="container mx-auto mb-20">
      <div
        class="flex flex-col space-x-10 lg:justify-between lg:flex-row md:justify-center md:items-end"
      >
        <div class="w-full text-left mb-10">
          <h3 class="text-xl font-medium tracking-[3px] text-purple-heart mb-6">
            BECOME A MEMBER
          </h3>
          <h1
            class="text-[3rem] tracking-[3px] leading-[5rem] font-medium mb-10"
          >
            Ready to try different work environment now?
          </h1>
          <p class="text-md leading-[2.5rem] mb-20">
            Coworking is an arrangement in which workers of different companies
            share an office space, allowing cost savings and convenience through
            the use of common infrastructures, such as equipment, utilities, and
            receptionist and custodial services, and in some cases refreshments
            and parcel acceptance services.
          </p>
          <div class="flex flex-row space-x-12">
            <button
              class="bg-purple-heart text-white text-md py-4 px-7 rounded-md hover:opacity-95"
            >
              Sign Up Now
            </button>
            <button
              class="bg-white text-purple-heart hover:shadow-2xl hover:text-purple-heart border border-purple-heart text-md py-4 px-7 rounded-md"
            >
              Schesule Visit
            </button>
          </div>
        </div>
        <div class="w-full">
          <img
            src="@/assets/css/images/become_a_member_img.png"
            class="mx-auto justify-center"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- footer -->
    <div class="bg-gradient-to-r from-[#fcfbfb] to-[#fcfbfb]">
      <div class="container mx-auto py-32">
        <div class="grid gap-12 grid-cols-2 md:grid-cols-4">
          <div>
            <h1 class="text-2xl mb-4 font-semibold">Wok-Space</h1>
            <p class="text-md max-w-md leading-[2rem]">
              Men cannot not live by exchanging articles, but producing them.
              They live by work not trade.
            </p>
          </div>
          <div>
            <h1 class="text-[18px] font-semibold mb-4 text-purple-heart">
              Company
            </h1>
            <div class="flex flex-col space-y-4">
              <a href="" class="hover:text-purple-heart">Global Localities</a>
              <a href="" class="hover:text-purple-heart">Missions</a>
              <a href="" class="hover:text-purple-heart">Careers</a>
              <a href="" class="hover:text-purple-heart">Investors</a>
              <a href="" class="hover:text-purple-heart">Newsroom</a>
            </div>
          </div>
          <div>
            <h1 class="text-[18px] font-semibold mb-4 text-purple-heart">
              Partnership
            </h1>
            <div class="flex flex-col space-y-4">
              <a href="" class="hover:text-purple-heart">Tasks</a>
              <a href="" class="hover:text-purple-heart">Profile</a>
              <a href="" class="hover:text-purple-heart">Events</a>
              <a href="" class="hover:text-purple-heart">Services</a>
            </div>
          </div>
          <div>
            <h1 class="text-[18px] font-semibold mb-4 text-purple-heart">
              Follow us
            </h1>
            <div class="flex flex-row space-x-3">
              <img
                src="@/assets/css/icons/Facebook-icon.svg"
                class="cursor-pointer bg-white p-4 rounded-full h-12 w-12"
                alt=""
              />

              <img
                src="@/assets/css/icons/Twitter-Icon.svg"
                class="cursor-pointer bg-white p-4 rounded-full h-12 w-12"
                alt=""
              />

              <img
                src="@/assets/css/icons/Dribbble-Icon.svg"
                class="cursor-pointer bg-white p-4 rounded-full h-12 w-12"
                alt=""
              />
              <img
                src="@/assets/css/icons/LinkedInIcon.svg"
                class="cursor-pointer bg-white p-4 rounded-full h-12 w-12"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
