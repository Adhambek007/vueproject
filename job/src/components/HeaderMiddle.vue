<template>
  <header class="header p-8">
    <div class=" max-w-[1200px] mx-auto">
      <div class="flex  items-center justify-between ">
        <div class="flex   items-center gap-[33px]">
          <img :src="fresh" alt="Freshnesecom">
          <div class="flex items-center border rounded-[12px] overflow-hidden w-full max-w-xl shadow-sm">
            <!-- Category Dropdown -->
            <div class="flex items-center px-4 py-2 bg-white text-black font-semibold whitespace-nowrap">
              All categories
              <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
              </svg>
            </div>

            <!-- Divider -->
            <div class="h-6 w-px bg-gray-300 mx-2"></div>

            <!-- Search Input -->
            <input
                type="text"
                placeholder="Search Products, categories ..."
                class="flex-1 py-2 px-2 text-sm outline-none placeholder-gray-400"
            />

            <!-- Search Icon -->
            <div class="px-4 text-gray-500 cursor-pointer">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2"
                   viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="11" cy="11" r="8"></circle>
                <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
              </svg>
            </div>
          </div>

        </div>

        <div class="flex items-center gap-[33px] ">
          <img :src="people" alt="">
          <img :src="basket" alt="">
        </div>

      </div>

    </div>
    <div class="bg-[#F9F9F9] mt-[48px]">
      <div class="max-w-[1200px] mx-auto">
        <div class=" py-[16px] flex items-center gap-[50px]">
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Bakery
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Fruit and vegetables
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Meat and fish
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Drinks
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Kitchen
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Special nutrition
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Baby
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>
          <div class="flex items-center gap-[2px]">
            <p class="font-semibold text-[15px]">
              Pharmacy
            </p>
            <svg class="w-4 h-4 ml-1 text-green-600" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.292l3.71-4.06a.75.75 0 111.08 1.04l-4.25 4.655a.75.75 0 01-1.08 0L5.25 8.27a.75.75 0 01-.02-1.06z" clip-rule="evenodd" />
            </svg>
          </div>


        </div>
      </div>
    </div>
  </header>
</template>
<script setup>
import fresh from '../assets/Freshnesecom.svg'
import people from '../assets/peopleLogo.svg'
import basket from '../assets/basket.svg'
</script>