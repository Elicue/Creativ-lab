<template>
  <div class="home text-primary bg-blanc h-full">
    <div class="first relative w-full h-[100vh] mt-[8vh] flex flex-col">
      <div class="flower absolute bottom-[20vh] left-0 flex flex-row">
        <div class="img">
          <img class="rounded-br-full rounded-tr-full w-[40vh] h-[25vh] object-cover" src="imgs/flower.jpg" alt="flowers">
        </div>
        <div class="circle absolute -right-[20%] top-[18%]">
          <Circle/>
        </div>
      </div>
      <div class="content w-10/12 h-full mx-auto flex flex-row">
        <div class="left w-1/3 flex flex-col mt-[15vh]">
          <div class="title">
            <h3 class="uppercase text-6xl">penelope's</h3>
            <h3 class="font-rainbow text-5xl">floral design</h3>
          </div>
          <div class="content flex flex-col w-10/12 my-6">
            <p class="leading-8 tracking-wider">Welcome to my floral portfolio! As a florist, I take great pride in creating unique and beautiful arrangements for all occasions.</p>
          </div>
          <div class="ctas flex flex-row justify-between w-[80%]">
            <button class="capitalize border-blanc bg-primary border-[1px] rounded-full p-2 px-4 flex flow-row text-blanc">
              Our Products
              <svg class="ml-4" width="24" height="28" viewBox="0 0 24 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M10 27C17.1797 27 23 21.1797 23 14C23 7.15676 16.7124 1.5485 9.99997 1.03789" stroke="#F8F5F0"/>
                <path d="M1 13.5C0.723858 13.5 0.5 13.7239 0.5 14C0.5 14.2761 0.723858 14.5 1 14.5L1 13.5ZM15.3536 14.3536C15.5488 14.1583 15.5488 13.8417 15.3536 13.6464L12.1716 10.4645C11.9763 10.2692 11.6597 10.2692 11.4645 10.4645C11.2692 10.6597 11.2692 10.9763 11.4645 11.1716L14.2929 14L11.4645 16.8284C11.2692 17.0237 11.2692 17.3403 11.4645 17.5355C11.6597 17.7308 11.9763 17.7308 12.1716 17.5355L15.3536 14.3536ZM1 14.5L15 14.5V13.5L1 13.5L1 14.5Z" fill="#F8F5F0"/>
              </svg>
            </button>
            <button class="capitalize border-primary bg-blanc border-[1px] rounded-full p-2 px-4 flex flow-row">
              About Us
              <svg class="ml-4" width="24" height="28" viewBox="0 0 24 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M10 27C17.1797 27 23 21.1797 23 14C23 7.15676 16.7124 1.5485 9.99997 1.03789" stroke="#421815"/>
                <path d="M1 13.5C0.723858 13.5 0.5 13.7239 0.5 14C0.5 14.2761 0.723858 14.5 1 14.5L1 13.5ZM15.3536 14.3536C15.5488 14.1583 15.5488 13.8417 15.3536 13.6464L12.1716 10.4645C11.9763 10.2692 11.6597 10.2692 11.4645 10.4645C11.2692 10.6597 11.2692 10.9763 11.4645 11.1716L14.2929 14L11.4645 16.8284C11.2692 17.0237 11.2692 17.3403 11.4645 17.5355C11.6597 17.7308 11.9763 17.7308 12.1716 17.5355L15.3536 14.3536ZM1 14.5L15 14.5V13.5L1 13.5L1 14.5Z" fill="#421815"/>
              </svg>
            </button>
          </div>
        </div>
        <div class="mid w-1/3 flex flex-col text-right h-[70%] justify-end">
          <div class="img -ml-16">
            <svg width="161" height="161" viewBox="0 0 161 161" fill="none" xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_20_319)">
              <mask id="mask0_20_319" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="0" width="161" height="161">
              <path d="M46.4511 160.434L0 46.4511L113.983 -1.08264e-06L160.434 113.983L46.4511 160.434Z" fill="white"/>
              </mask>
              <g mask="url(#mask0_20_319)">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M103.706 66.3993C115.919 76.4217 127.034 89.0471 131.976 104.042C133.774 109.498 134.246 115.034 134.78 120.698C134.818 121.095 134.525 121.449 134.126 121.488C133.727 121.525 133.372 121.232 133.335 120.833C132.811 115.278 132.36 109.847 130.597 104.496C125.726 89.7145 114.728 77.2953 102.68 67.4325L102.513 67.6057C100.709 69.49 97.2403 70.1918 93.205 69.959C87.4209 69.6262 80.4662 67.4517 76.0159 64.7579C74.0165 63.547 72.5172 62.2168 71.7862 60.9139C71.2155 59.8984 71.082 58.8822 71.4333 57.9118C72.1833 55.8444 74.5348 54.9479 77.7243 55.0447C84.3948 55.2453 94.8322 59.5651 98.8436 62.5802C100.096 63.5221 101.344 64.4905 102.582 65.486C102.908 65.1632 103.226 64.8457 103.522 64.5231C104.361 63.6014 105.023 62.6197 105.169 61.1887C105.392 58.9584 104.664 56.6909 103.496 54.543C101.67 51.1923 98.7609 48.1386 96.4443 45.9615C83.541 33.838 68.688 31.2825 55.1847 32.1687C41.5475 33.0662 29.2689 37.4594 21.6695 39.1763C21.2788 39.2654 20.8916 39.0189 20.8026 38.6282C20.7135 38.2374 20.9592 37.8485 21.3507 37.7612C28.9989 36.0326 41.3619 31.6235 55.0902 30.7219C68.9519 29.8093 84.1916 32.4589 97.4379 44.9026C99.8517 47.1701 102.87 50.3588 104.77 53.8483C106.085 56.2646 106.864 58.8247 106.612 61.3348C106.385 63.5873 105.153 64.9474 103.706 66.3993ZM101.547 66.5161L101.465 66.6033C99.8878 68.2505 96.8171 68.7139 93.2888 68.5097C87.7311 68.1898 81.0457 66.1057 76.7677 63.5149C75.3004 62.6276 74.1226 61.6863 73.3991 60.731C72.8033 59.9424 72.5241 59.1609 72.7987 58.4074C73.0549 57.6944 73.6162 57.2243 74.3717 56.9267C75.2579 56.5759 76.3912 56.4565 77.6797 56.4946C84.0893 56.688 94.1169 60.8428 97.9715 63.7401C99.1675 64.6411 100.362 65.5655 101.547 66.5161Z" fill="#421815"/>
              <path fill-rule="evenodd" clip-rule="evenodd" d="M133.395 123.25C133.659 123.075 133.942 122.73 134.241 122.357C134.956 121.468 135.642 120.336 135.987 119.816C136.21 119.482 136.66 119.393 136.993 119.614C137.328 119.837 137.418 120.287 137.196 120.621C136.772 121.258 135.855 122.764 134.98 123.729C134.51 124.247 134.03 124.611 133.629 124.738C132.948 124.953 132.323 124.599 131.926 123.554C131.457 122.318 131.145 119.794 129.631 118.191C129.356 117.901 129.37 117.44 129.661 117.166C129.953 116.891 130.412 116.904 130.688 117.196C132.13 118.725 132.654 120.978 133.093 122.46C133.177 122.742 133.312 123.062 133.395 123.25Z" fill="#421815"/>
              </g>
              </g>
              <defs>
              <clipPath id="clip0_20_319">
              <rect width="123.084" height="123.084" fill="white" transform="matrix(0.377393 0.926053 0.926053 -0.377393 0 46.4511)"/>
              </clipPath>
              </defs>
            </svg>
          </div>
          <div class="txt">
            <p class=" leading-8 tracking-wider">My approach to floral design is rooted in the natural world. I draw inspiration from the seasons, incorporating the freshest blooms and greenery to create arrangements that feel organic and effortless.</p>
            <p class=" leading-8 tracking-wider"> I believe that flowers have the power to communicate emotions and tell stories, and I strive to capture that essence in every piece I create.</p>
          </div>
        </div>
        <div class="right w-1/3 flex flex-col items-center justify-center">
          <FloralDesign/>
        </div>
      </div>
    </div>
    <div class="second w-full flex flex-col bg-rose h-[80vh] justify-center">
      <div class="content w-11/12 flex flex-col mx-auto">
        <div class="title w-full justify-between flex flex-row items-center">
          <h2 class="text-7xl">
            Browse <span class="font-rainbow text-5xl">categories</span>
          </h2>
            <button class="flex flex-row items-center border-primary border-2 rounded-full px-4 h-2/3">
              Browse all products 
              <svg class="ml-4" width="20" height="8" viewBox="0 0 20 8" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M1 3.5C0.723858 3.5 0.5 3.72386 0.5 4C0.5 4.27614 0.723858 4.5 1 4.5V3.5ZM19.3536 4.35355C19.5488 4.15829 19.5488 3.84171 19.3536 3.64645L16.1716 0.464466C15.9763 0.269204 15.6597 0.269204 15.4645 0.464466C15.2692 0.659728 15.2692 0.976311 15.4645 1.17157L18.2929 4L15.4645 6.82843C15.2692 7.02369 15.2692 7.34027 15.4645 7.53553C15.6597 7.7308 15.9763 7.7308 16.1716 7.53553L19.3536 4.35355ZM1 4.5H19V3.5H1V4.5Z" fill="#421815"/>
            </svg>
            </button>
        </div>
        <div class="content flex flex-row items-center mt-[6vh]">
          <div class="menu flex flex-col w-[25%] text-right justify-center h-full border-r-2 border-primary">
            <div class="flex flex-col w-full text-right justify-between h-2/3 pr-10">
              <p>All products</p>
              <span></span>
              <p class="bg-primary rounded-tr-full rounded-br-full absolute left-0 text-rose px-4 py-2 mt-[6vh] w-[45vh]">Mixed bouquets</p>
              <p>Monochromatic bouquets</p>
              <p>Seasonal bouquets</p>
              <p>Garden-style bouquets</p>
            </div>
          </div>
          <div class="items flex flex-row w-[75%] justify-around">
            <Cat url="imgs/mix.jpg" title="Garden Delight" price="30$"/>
            <Cat url="imgs/lys.jpg" title="Classic Elegance" price="25$"/>
            <Cat url="imgs/basket.jpg" title="Rustic Charm" price="50$"/>
          </div>
        </div>
      </div>
    </div>
    <div class="third flex flex-row h-[80vh] w-11/12 mx-auto my-[8vh]">
      <div class="left w-1/2 h-full items-center flex justify-center relative">
        <img class="rounded-full w-1/2 h-2/3 object-cover" src="imgs/bouquet.jpg" alt="flowers">
        <div class="circle absolute bottom-[15vh] left-[20vh]">
          <Circle/>
        </div>
      </div>
      <div class="right w-1/2 h-full items-start justify-center flex flex-col relative">
        <div class="content w-11/12 flex flex-col">
          <div class="title flex flex-row justify-between mb-[5vh]">
            <h3 class="text-3xl">True Story</h3>
            <h3 class="flex flex-row items-center "><span><img class="w-[2vh] h-[2vh]  mr-[2vh]" src="imgs/chevron.svg " alt="chevron"></span> 01/05 <span><img class="-scale-100 ml-[2vh] w-[2vh] h-[2vh]" src="imgs/chevron.svg" alt="chevron"></span></h3>
          </div>
          <div class="txt w-11/12 leading-7 tracking-wider">
            <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "I recently purchased a bouquet of flowers for my sister's birthday and I couldn't be happier with my experience. The website was easy to navigate and had a great selection of arrangements to choose from. The checkout process was seamless and I received updates throughout the delivery process. When my sister received the bouquet, she was absolutely thrilled! The flowers were fresh, vibrant and arranged beautifully. She even sent me a picture to show me how lovely they looked in her home. I highly recommend this florist and will definitely be using them again for future occasions. Thank you for making my sister's birthday so special!"</p>
          </div>
          <div class="sign flex flex-row justify-between mt-[5vh] items-baseline">
            <h3 class="font-rainbow text-3xl">Sophia Rodriguez</h3>
            <p>February 2, 2023</p>
          </div>
        </div>
        <div class="arrow absolute -bottom-[10vh] -left-[25vh]">
          <svg width="254" height="254" viewBox="0 0 254 254" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_86_2)">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M141.146 166.098C165.147 166.257 190.397 162.311 210.737 149.598C218.139 144.973 224.069 138.965 230.196 132.869C230.626 132.442 230.628 131.743 230.2 131.311C229.769 130.879 229.071 130.877 228.639 131.308C222.63 137.285 216.827 143.192 209.569 147.728C189.517 160.26 164.604 164.08 140.95 163.893L140.924 163.529C140.647 159.575 137.278 155.385 132.339 151.736C125.26 146.505 115.024 142.287 107.209 141.11C103.697 140.582 100.653 140.679 98.5334 141.49C96.8802 142.122 95.7368 143.179 95.2043 144.654C94.0716 147.797 95.9471 151.129 99.7664 154.115C107.752 160.362 124.14 165.457 131.755 165.833C134.133 165.95 136.532 166.032 138.944 166.071C139.012 166.765 139.075 167.445 139.107 168.109C139.192 170.002 139.011 171.792 137.791 173.604C135.885 176.426 132.831 178.367 129.38 179.741C123.992 181.881 117.627 182.621 112.806 182.912C85.9553 184.535 66.1246 173.089 51.2139 158.934C36.1578 144.635 26.0852 127.574 18.8774 118.185C18.5076 117.701 17.8159 117.613 17.3322 117.983C16.8485 118.353 16.7577 119.046 17.13 119.528C24.3835 128.978 34.5393 146.14 49.6978 160.532C65.0015 175.066 85.3754 186.778 112.938 185.115C117.96 184.811 124.583 184.019 130.193 181.79C134.076 180.246 137.474 178.013 139.619 174.836C141.542 171.985 141.425 169.199 141.146 166.098ZM138.737 163.863L138.725 163.681C138.484 160.225 135.348 156.7 131.028 153.511C124.226 148.484 114.393 144.423 106.879 143.292C104.303 142.903 102.013 142.858 100.24 143.271C98.7774 143.613 97.692 144.254 97.2807 145.401C96.8871 146.483 97.086 147.577 97.6792 148.659C98.3736 149.93 99.5813 151.171 101.123 152.378C108.798 158.38 124.546 163.27 131.863 163.631C134.136 163.741 136.428 163.821 138.737 163.863Z" fill="#421815"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M231.059 128.541C231.197 129.004 231.193 129.681 231.179 130.408C231.149 132.141 230.851 134.129 230.749 135.072C230.684 135.678 231.124 136.22 231.729 136.286C232.335 136.35 232.878 135.913 232.943 135.306C233.067 134.151 233.459 131.501 233.375 129.523C233.329 128.462 233.122 127.569 232.777 127.033C232.191 126.119 231.117 125.925 229.638 126.76C227.889 127.748 225.072 130.392 221.747 130.794C221.144 130.865 220.712 131.418 220.786 132.02C220.859 132.626 221.408 133.057 222.014 132.984C225.184 132.599 227.986 130.476 229.938 129.172C230.309 128.925 230.778 128.681 231.059 128.541Z" fill="#421815"/>
            </g>
            <defs>
            <clipPath id="clip0_86_2">
            <rect width="187" height="187" fill="white" transform="translate(0.63623 88.6333) rotate(-28.0715)"/>
            </clipPath>
            </defs>
          </svg>
        </div>
      </div>
    </div>
    <span class="flex h-[6vh]"></span>
  </div>
</template>

<script>
import FloralDesign from '@/components/FloralDesign.vue'
import Circle from '@/components/Circle.vue'
import Cat from '@/components/Cat.vue'

export default {
  name: 'HomeView',
  
  components: {
    FloralDesign,
    Circle,
    Cat
  }
}
</script>

<style>

@keyframes circle {
  0% {
    transform: rotate(0);
  }
  100% {
    transform: rotate(360deg);
  }
}

.circle {
  animation: circle 10s linear infinite;
}

</style>
