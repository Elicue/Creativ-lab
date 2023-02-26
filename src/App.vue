<template>
  <header class="bg-blanc bg-opacity-50 flex flex-row w-full h-[8vh] fixed top-0 items-center text-primary border-b-[1px] z-[90] border-b-primary">
    <div class="content w-10/12 mx-auto flex flex-row items-center h-full ">
      <nav class="w-1/4 justify-between flex flex-row h-full items-center">
        <router-link to="/">Home</router-link>
        <router-link to="/">Menu</router-link>
        <router-link to="/">Offer</router-link>
        <router-link to="/">About us</router-link>
      </nav>
      <div class="title w-1/2 justify-center flex flex-row h-full items-center">
        <h2 class="font-rainbow text-2xl">Penelope's</h2>
      </div>
      <div class="others w-1/5 justify-between flex flex-row h-full items-center">
        <a href="#">Faq</a>
        <a class="border-primary border-[1px] rounded-full p-2 px-4" href="#">Contact</a>
        <a class="w-[4vh] h-[4vh] bg-primary rounded-full justify-center flex items-center" href="#">
          <svg class="w-[2vh] h-[2vh] text-blanc" width="20" height="23" viewBox="0 0 20 23" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_16_27)">
          <path d="M7.14286 5.03125C7.14286 3.44551 8.42411 2.15625 10 2.15625C11.5759 2.15625 12.8571 3.44551 12.8571 5.03125V7.1875H7.14286V5.03125ZM5 7.1875H2.14286C0.959821 7.1875 0 8.15332 0 9.34375V18.6875C0 21.0684 1.91964 23 4.28571 23H15.7143C18.0804 23 20 21.0684 20 18.6875V9.34375C20 8.15332 19.0402 7.1875 17.8571 7.1875H15V5.03125C15 2.25059 12.7634 0 10 0C7.23661 0 5 2.25059 5 5.03125V7.1875ZM6.07143 9.34375C6.35559 9.34375 6.62811 9.45734 6.82904 9.65953C7.02998 9.86171 7.14286 10.1359 7.14286 10.4219C7.14286 10.7078 7.02998 10.982 6.82904 11.1842C6.62811 11.3864 6.35559 11.5 6.07143 11.5C5.78727 11.5 5.51475 11.3864 5.31381 11.1842C5.11288 10.982 5 10.7078 5 10.4219C5 10.1359 5.11288 9.86171 5.31381 9.65953C5.51475 9.45734 5.78727 9.34375 6.07143 9.34375ZM12.8571 10.4219C12.8571 10.1359 12.97 9.86171 13.171 9.65953C13.3719 9.45734 13.6444 9.34375 13.9286 9.34375C14.2127 9.34375 14.4853 9.45734 14.6862 9.65953C14.8871 9.86171 15 10.1359 15 10.4219C15 10.7078 14.8871 10.982 14.6862 11.1842C14.4853 11.3864 14.2127 11.5 13.9286 11.5C13.6444 11.5 13.3719 11.3864 13.171 11.1842C12.97 10.982 12.8571 10.7078 12.8571 10.4219Z" fill="white"/>
          </g>
          <defs>
          <clipPath id="clip0_16_27">
          <rect width="20" height="23" fill="white"/>
          </clipPath>
          </defs>
          </svg>
        </a>
      </div>
    </div>
  </header>
  <router-view class="bg-blanc"/>
</template>
