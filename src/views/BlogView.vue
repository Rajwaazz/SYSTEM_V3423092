<script setup lang="ts">
import CategoryContent from '@/components/CategoryContent.vue'
import JoinContent from '@/components/JoinContent.vue'
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <main class="w-full h-full overflow-x-hidden">
      <!-- Hero -->
      <section
        class="bg-x-lavender p-[80px] flex justify-between items-center gap-8"
      >
        <div class="flex flex-col gap-5">
          <h5 class="text-x-black font-medium tracking-[3px]">FEATURED POST</h5>
          <h2
            class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
          >
            Step-by-step guide to choosing great font pairs
          </h2>
          <p class="text-x-black text-sm font-medium leading-[20px]">
            By <span class="text-x-yellow">James West</span> &nbsp;|&nbsp; May
            23, 2022
          </p>
          <p class="text-x-mediumgrey leading-[28px]">
            Duis aute irure dolor in reprehenderit in voluptate velit esse
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
            cupidatat non proident.
          </p>
          <a
            href="blog/post"
            class="w-[204px] flex items-center justify-center bg-x-blue px-[48px] py-[16px] text-white font-bold hover:bg-x-yellow transition duration-150 ease-in-out"
          >
            Read More >
          </a>
        </div>
        <img
          src="@/assets/images/misc/man-with-white-shirt.png"
          alt="Man with white T-Shirt"
        />
      </section>

      <!-- All Post -->
      <section class="p-[80px] flex flex-col gap-8">
        <h2
          class="text-x-black text-4xl font-bold leading-[48px] tracking-[-2px]"
        >
          All Post
        </h2>
        <div
          class="flex flex-col gap-8 pt-[48px] border-t border-x-mediumgrey border-opacity-32"
        >
          <a href="blog/post" class="flex justify-start items-center gap-8">
            <img
              src="@/assets/images/misc/two-woman-in-erase-board.png"
              alt="Two woman in erase board"
            />
            <div class="flex flex-col gap-4">
              <p
                class="text-x-yellow font-semibold leading-[20px] tracking-[3px]"
              >
                STARTUP
              </p>
              <h2
                class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
              >
                Design tips for designers that cover everything you need
              </h2>
              <p class="text-x-mediumgrey leading-[28px]">
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident.
              </p>
            </div>
          </a>
          <a href="blog/post" class="flex justify-start items-center gap-8">
            <img
              src="@/assets/images/misc/people-doing-handshake.png"
              alt="People doing handshake"
            />
            <div class="flex flex-col gap-4">
              <p
                class="text-x-yellow font-semibold leading-[20px] tracking-[3px]"
              >
                BUSINESS
              </p>
              <h2
                class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
              >
                How to build rapport with your web design clients
              </h2>
              <p class="text-x-mediumgrey leading-[28px]">
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident.
              </p>
            </div>
          </a>
          <a href="blog/post" class="flex justify-start items-center gap-8">
            <img
              src="@/assets/images/misc/woman-looking-man.png"
              alt="Woman looking at man"
            />
            <div class="flex flex-col gap-4">
              <p
                class="text-x-yellow font-semibold leading-[20px] tracking-[3px]"
              >
                STARTUP
              </p>
              <h2
                class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
              >
                Logo design trends to avoid in 2022
              </h2>
              <p class="text-x-mediumgrey leading-[28px]">
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident.
              </p>
            </div>
          </a>
          <a href="blog/post" class="flex justify-start items-center gap-8">
            <img
              src="@/assets/images/misc/people-walking.png"
              alt="People walking"
            />
            <div class="flex flex-col gap-4">
              <p
                class="text-x-yellow font-semibold leading-[20px] tracking-[3px]"
              >
                TECHNOLOGY
              </p>
              <h2
                class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
              >
                8 Figma design systems you can download for free today
              </h2>
              <p class="text-x-mediumgrey leading-[28px]">
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident.
              </p>
            </div>
          </a>
          <a href="blog/post" class="flex justify-start items-center gap-8">
            <img
              src="@/assets/images/misc/two-woman-in-erase-board.png"
              alt="Two woman in erase board"
            />
            <div class="flex flex-col gap-4">
              <p
                class="text-x-yellow font-semibold leading-[20px] tracking-[3px]"
              >
                ECONOMY
              </p>
              <h2
                class="text-x-black text-4xl font-bold tracking-[-2px] leading-[48px]"
              >
                Font sizes in UI design: The complete guide to follow
              </h2>
              <p class="text-x-mediumgrey leading-[28px]">
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident.
              </p>
            </div>
          </a>
          <div class="flex justify-center items-center gap-4">
            <a
              class="text-x-mediumgrey text-2xl text-center font-bold leading-[32px]"
              href="#"
              >< Prev</a
            >
            <a
              class="text-x-black text-3xl text-center font-bold leading-[40px] tracking-[-1px]"
              href="#"
              >Next ></a
            >
          </div>
        </div>
      </section>

      <!-- All Category -->
      <h2
        class="text-x-black text-4xl text-center font-bold leading-[48px] tracking-[-2px]"
      >
        All Category
      </h2>
      <CategoryContent />

      <JoinContent />
    </main>
  </MainLayout>
</template>
