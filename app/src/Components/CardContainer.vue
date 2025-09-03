<template>
  <div id="home_content_container"
    class="w-screen h-screen flex justify-center items-center
      bg-[url('/src/assets/pattern-background-mobile.svg')]
      md:bg-[url('/src/assets/pattern-background-desktop.svg')]">

    <div id="card_container"
      class="h-[75%] min-w-[30%] max-w-100 text-center">
      <img src="/src/assets/illustration-hero.svg"
        class="rounded-t-4xl w-full h-auto"
      />
        <div id="card_inner_content"
          class="h-100 w-full flex flex-col justify-center items-center rounded-b-4xl bg-white px-6">

          <h1
            class="">Order Summary</h1>

          <p class="">
            You can now listen to millions of songs, audiobooks, and podcasts on any
            device anywhere you like!
          </p>

          <span>
            <h2>Anual Plan</h2>
            <h3>$59.99/year</h3>
            <button>Change</button>
          </span>

          Proceed to Payment
          Cancel Order
        </div>
    </div>

  </div>
</template>

