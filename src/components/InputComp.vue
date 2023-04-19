<template>
    <!-- Input Area -->
    <div class="container flex space-x-6 pt-12 pl-14">

        <!-- DAY -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">DAY</p>
            <input type="text"
                class="text-lg pl-4 text-c-off-black font-bold basis-1/4 bg-transparent w-28 h-10 outline-none border border-c-light-grey rounded-md placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-lg"
                placeholder="DD">
        </div>

        <!-- MONTH -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">MONTH</p>
            <input type="text"
                class="text-lg pl-4 text-c-off-black font-bold basis-1/4 bg-transparent w-28 h-10 outline-none border border-c-light-grey rounded-md placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-lg"
                placeholder="MM">
        </div>

        <!-- YEAR -->
        <div>
            <p class="tracking-widest text-xs text-c-smoke-grey pb-1 font-bold">YEAR</p>
            <input type="text"
                class="text-lg pl-4 text-c-off-black font-bold basis-1/4 bg-transparent w-28 h-10 outline-none border border-c-light-grey rounded-md placeholder:text-c-smoke-grey placeholder:font-extrabold placeholder:py-8 placeholder:text-lg"
                placeholder="YYYY">
        </div>

    </div>

    <!-- Divider -->
    <div class="relative mx-14 mt-8 border-t-[0.75px] border-opacity-80 border-c-light-grey">
    <div class="bg-c-purple w-16 h-16 rounded-full flex items-center justify-center absolute -right-4 -top-8">
        <svg xmlns="http://www.w3.org/2000/svg" width="46" height="44" viewBox="0 0 46 44">
            <g fill="none" stroke="#FFF" stroke-width="2">
                <path d="M1 22.019C8.333 21.686 23 25.616 23 44M23 44V0M45 22.019C37.667 21.686 23 25.616 23 44" />
            </g>
        </svg>
    </div>
</div></template>