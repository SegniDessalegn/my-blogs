<script setup lang="ts">
defineOgImage()
</script>

<template>
  <div class="py-5">
    <div class="sm:grid grid-cols-8 px-6 py-5 sm:py-9 gap-5 container max-w-5xl  mx-auto">
      <div class="col-span-5  max-w-md">
        <div class="flex justify-between">
          <div>
            <h1 class="text-xl sm:text-4xl  pb-2 font-bold ">
              Segni Dessalegn
            </h1>

            <div class="my-3 space-x-3 pb-10">
              <NuxtLink
                to="https://github.com/SegniDessalegn"
                target="_blank"
                class="p-2 bg-gray-300 text-gray-800 rounded-md"
                aria-label="Github"
              >
                <Icon name="fa:github" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://www.linkedin.com/in/segni-dessalegn-331155228/"
                target="_blank"
                class="p-2 bg-gray-300 text-gray-800 rounded-md"
                aria-label="LinkedIn"
              >
                <Icon name="fa:linkedin-square" size="1em" />
              </NuxtLink>
            </div>
          </div>
          <div class="sm:hidden block col-span-3 pb-5">
            <NuxtImg
              src="/segni.jpg"
              width="125"
              height="115"
              quality="50"
              class="rounded-md"
            />
          </div>
        </div>
        <h3 class="text-base sm:text-3xl font-semibold pb-7 sm:pb-12">
          <div>
            🚧 Currently under development 🚧
          </div>
          Software Engineer, Problem Solver, AI Enthusiast.
        </h3>

        <p>Greetings and welcome. I'm an aspiring software engineer, currently in the process of learning and growing. I am interested in all aspects of software development. I also enjoy engaging in competitive programming and have dabbled in AI and ML to some extent. In short, I embrace each day's opportunities and steadily progress as a software engineer.</p>
      </div>
      <div class="hidden sm:block col-span-3">
        <NuxtImg
          src="/segni.jpg"
          width="450"
          height="500"
          quality="50"
          class="rounded-md"
        />
      </div>
    </div>
  </div>
</template>
