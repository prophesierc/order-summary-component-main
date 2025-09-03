<template>
  <div id="home_content_container"
    class="w-screen h-screen flex justify-center items-center
      bg-[url('/src/assets/pattern-background-mobile.svg')]
      md:bg-[url('/src/assets/pattern-background-desktop.svg')]">

    <div id="card_container"
      class="h-[75%] min-w-[25%] max-w-100 text-center ">
      <img src="/src/assets/illustration-hero.svg"
        class="rounded-t-4xl w-full h-auto"
      />
        <div id="card_inner_content"
          class="h-100 w-full flex flex-col items-center rounded-b-4xl bg-white px-8 font-family-RH">

          <h1
            class="font-bold text-3xl py-6 tracking-tighter">
              Order Summary
          </h1>

          <p class="text-md text-(--neutral-clr-Grey)">
            You can now listen to millions of songs, audiobooks, and podcasts on any
            device anywhere you like!
          </p>

          <span class="flex flex-row">
            <img src="/src/assets/icon-music.svg">
            <div class="flex flex-col">
              <h2>Annual Plan</h2>
              <h3>$59.99/year</h3>
            </div>
            <button>Change</button>
          </span>

          <div>Proceed to Payment</div>
          <div>Cancel Order</div>
        </div>

    </div>

  </div>
</template>

