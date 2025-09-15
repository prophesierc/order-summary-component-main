<template>
  <div id="home_content_container"
    class="w-screen h-screen flex justify-center items-center
      bg-[url('/src/assets/pattern-background-mobile.svg')]
      md:bg-[url('/src/assets/pattern-background-desktop.svg')]">

    <div id="card_container"
      class="h-full min-w-[25%] max-w-100 text-center flex flex-col justify-center items-center">
      <img src="/src/assets/illustration-hero.svg"
        class="rounded-t-4xl w-full h-auto"
      />
        <div id="card_inner_content"
          class="h-110 w-full flex flex-col items-center rounded-b-4xl bg-white px-8 font-family-RH">

          <h1
            class="font-extrabold text-3xl py-8 tracking-tighter"
            >Order Summary
          </h1>

          <p class="text-md text-(--neutral-clr-Grey)"
            >You can now listen to millions of songs, audiobooks, and podcasts on any
            device anywhere you like!
          </p>

          <span class="flex items-center my-4 w-full h-22 px-4
            bg-[var(--clr-plan-background)] rounded-2xl">
            <img src="/src/assets/icon-music.svg">
            <div class="flex flex-col items-start pl-6">
              <h2 class="font-extrabold"
                >Annual Plan</h2>
              <h3 class="text-(--neutral-clr-Grey)"
                >$59.99/year</h3>
            </div>
            <button class="ml-auto underline text-[var(--primary-clr-Blue-700)] font-extrabold cursor-pointer"
              >Change</button>
          </span>

          <div class="flex flex-row items-center justify-center bg-[var(--primary-clr-Blue-700)] text-white
            w-full h-12 rounded-xl font-extrabold my-2 mb-6 cursor-pointer"
            >Proceed to Payment</div>
          <div class="text-(--neutral-clr-Grey) font-extrabold cursor-pointer"
            >Cancel Order</div>
        </div>

    </div>

  </div>
</template>

