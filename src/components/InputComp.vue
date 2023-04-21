<template>
    <!-- Input Area -->
    <div class=" flex flex-row space-x-6 pt-10 pl-5 md:pt-12 md:pl-14 ">

        <!-- DAY -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">DAY</p>
            <input type="text" 
                class="text-md md:text-lg pl-4 text-c-off-black font-bold basis-1/4 
                bg-transparent w-20 h-10 sm:w-28 sm:h-10 outline-none border border-c-light-grey rounded-md
                placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-md 
                md:placeholder:text-lg"
                placeholder="DD">
        </div>

        <!-- MONTH -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">MONTH</p>
            <input type="text" 
                class="text-md md:text-lg pl-4 text-c-off-black font-bold basis-1/4 
                bg-transparent w-20 h-10 sm:w-28 sm:h-10 outline-none border border-c-light-grey rounded-md
                placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-md 
                md:placeholder:text-lg"
                placeholder="MM">
        </div>

        <!-- YEAR -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">YEAR</p>
            <input type="text"
                class="text-md md:text-lg pl-4 text-c-off-black font-bold basis-1/4 
                bg-transparent w-20 h-10 sm:w-28 sm:h-10 outline-none border border-c-light-grey rounded-md
                placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-md 
                md:placeholder:text-lg"
                placeholder="YYYY">
        </div>

    </div>

    <!-- Divider -->
    <div class="relative mt-12 mx-4 sm:mx-5 md:mx-14  sm:mt-8 border-t-[0.75px] border-opacity-80 border-c-light-grey">
    <button type="submit" 
            class="bg-c-purple p-3 w-12 h-12 mx-28  
            sm:mr-4 md:w-16 md:h-16 rounded-full flex items-center justify-center absolute  sm:-right-4 
            -top-6 sm:-top-5 md:-top-8 hover:bg-black hover:transition-all">
        <svg xmlns="http://www.w3.org/2000/svg" width="46" height="44" viewBox="0 0 46 44">
            <g fill="none" stroke="#FFF" stroke-width="2">
                <path d="M1 22.019C8.333 21.686 23 25.616 23 44M23 44V0M45 22.019C37.667 21.686 23 25.616 23 44" />
            </g>
        </svg>
    </button>
</div></template>